# 专为 gpt2api 项目 + Zeabur 定制
FROM golang:1.21-alpine
WORKDIR /app
COPY . .
RUN mkdir -p bin && go build -o ./bin/server
CMD ["./bin/server"]
