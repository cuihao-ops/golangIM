# golangIM

# 客户端打包
go build -o client.exe .\client.go
# 服务端打包
go build -o  server.exe  .\main.go .\server.go .\user.go