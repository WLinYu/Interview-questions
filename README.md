# Interview--summary
###1.页面输入url到页面加载完成显示的过程。
<smal>
---
</smal>
    1.发送一个url请求时，浏览器会开启一个线程来处理这个请求，t同时在远程的DNS服务器上启动一个DSN查询，使浏览器获得请求对应的IP。
    2.浏览器与远程的web服务通过TCP三次握手协商来建立一个TCP/IP连接。握手包括：一个同步报文，一个同步-应答报文，一个应答报文（在浏览器和服务器之间传递）。
    3.TCP/IP连接建立后，浏览器通过该链接向远程服务器发送http的get请求。远程服务器找到资源并使用http响应返回该资源（值为200的http响应表示一个正确的响应）。
    4.web服务器提供资源服务，客户端开始下载资源。
    5.请求返回后，浏览器会解析html生成DOM Tree,其次会根据CSS生成CSS Rule Tree，而javascript可根据DOM API操作DOM。
