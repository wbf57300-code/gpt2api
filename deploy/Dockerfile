# Zeabur 专属适配版
FROM golang:1.21-alpine
WORKDIR /app
COPY . .
# 核心修复：创建bin目录+编译
RUN mkdir -p bin && go build -o ./bin/server
CMD ["./bin/server"]
