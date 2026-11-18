# 嵌入式 Linux 学习代码

socket TCP 编程示例，服务端/客户端通信。

## 文件

- `server.c` — TCP 服务端：socket → bind → listen → accept → recv
- `client.c` — TCP 客户端：socket → connect → send

## 编译

```bash
gcc server.c -o server
gcc client.c -o client

运行

./server          # 终端 1
./client 127.0.0.1 8888    # 终端 2
