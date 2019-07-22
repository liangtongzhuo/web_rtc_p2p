# WebRTC WebSocket Server and Html Client Demo
一个完整的WebRTC Demo，包含了websocket websocket server和浏览器代码，使用方法：  
  
A complete WebRTC Demo, including a websocket server and browser side code. Usage:
```bash
npm insall
npm install -g http-server
# 启动http服务，默认8080端口
http-server
# 启动node.js服务
node server.js
```
开两个标签页，访问localhost:8080（根据http-server的端口号，注意需要使用localhost域名，因为webrtc只能运行在localhost或者https环境），这个时候在线用户就会显示一个，然后在一个标签页呼叫一下，另外一个标签页就能收到呼叫请求，点击同意即可。  
  
Open two browser tab, both visit localhost:8080 (based on your http-server, you should run in localhost or https domain due to webrtc requirement)，call the user showing on the online user list in one tab and press agree button in another tab. 
