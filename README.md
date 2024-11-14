# websocket_client_server
a dmeo for websocket about client and server


参考链接 https://blog.csdn.net/mo_sss/article/details/132616479
1.服务端 websocket_server
可以用websocket 在线测试访问 ws://localhost:8001/websocket-server


2.客户端 websocket_client
org.java-websocket 这个包可能下载失败 然后去 https://mvnrepository.com 直接搜索然后点击对应版本的Files 的jar下载下来后存入仓库对应的文件下就可以
postman 测试post 方法访问 127.0.0.1:8002/send2server 格式为raw  输入参数后服务端可显示