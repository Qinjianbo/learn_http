今天复习一下之前看过但是未总结的HTTP 状态码知识吧！

常见状态码总结：

### 2XX

- 200：访问正常返回：OK
- 204：没有符合的内容：No Content
- 206：范围内容：Partial Content

### 3XX

- 301：访问的资源永久性移除：Moved Permanently
- 302：临时重定向：Found
- 303：明确让客户端使用GET请求访问另一个URI：See Other
- 304：服务端无符合附加请求条件的资源：Not Modified
- 307：临时重定向,POST不能改成GET：Temporary Redirect

### 4XX

- 400：客户端错误：Bad Request
- 401：没有权限：Unauthorized
- 403：禁止访问：Forbidden
- 404：资源不存在：Not Found

### 5XX

- 500：服务器内部错误：Internal Server Error
- 503：服务不可用：Service Unavailable
