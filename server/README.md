### Python Proto File Compile
```
python -m grpc_tools.protoc -I. --python_out=. --grpc_python_out=. ice_cream.proto
```
### NodeJS Proto File Compile
```
protoc-gen-grpc --js_out=import_style=commonjs,binary:./client/ --grpc_out=./client --proto_path proto/ ./proto/ice_cream.proto
```