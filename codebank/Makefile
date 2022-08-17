gen:
	protoc --proto_path=infrastructure/grpc infrastructure/grpc/protofile/*.proto --go_out=infrastructure/ --go-grpc_out=infrastructure/

egrpc:
	evans -r repl p=50051

.PHONY: gen egrpc