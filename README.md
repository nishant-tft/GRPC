# GRPC

Activate environment:-

pipenv shell

python -m grpc_tools.protoc --proto_path=. ./unary.proto --python_out=. --grpc_python_out=.

Start server:-

python3 unary_server.py


Start client:-

python3 unary_client.py
