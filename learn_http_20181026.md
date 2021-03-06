地铁睡意学，所记知识点总结：

- 不同协议版本对请求方法的支持

|请求方法|协议版本 |说明 |
|:------:|:-------:|:---:|
|GET     |1.0   1.1|请求资源|
|POST    |1.0   1.1|传输实体主体|
|HEAD    |1.0   1.1|获取报文首部|
|PUT     |1.0   1.1|传送文件|
|DELETE  |1.0   1.1|删除文件|
|TRACE   |1.1      |追踪路径|
|CONNECT |1.1      |要求用隧道协议链接代理|
|OPTIONS |1.1      |询问支持的方法|
|LINK    |1.0      |建立与资源之间的联系|
|UNLINK  |1.0      |断开与资源之间的联系|

- HTTP 是无状态的 stateless, COOKIE可以弥补状态问题
- HTTP/1.1 及部分 HTTP/1.0 支持长连接 Connection:keep-alive 。支持长连接后就可以不用多次握手了。然后再加上管线化，就可以在上一个请求没有返回时继续发送下一个请求。
- MIME - Multipurpose Internet Mail Extensions - 多用途因特网邮件扩展 :> 多部分对象集合Multipart使HTTP可以报文发送的主体可以包含多种类型实体。
- 范围请求 - Range: bytes=5001-10000 (http断点续传)
