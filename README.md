# NettyServiceProvider
Simple Netty Server &amp; Client Connection \
[주의] 보안설정이 없기에 로컬 네트워크 안에서만 사용하시는걸 추천합니다 \
\
사용법:\
    서버사이드:\
          Server server = new Server();\
          CompleteableFuture<Channel> futureServerChannel = server.run(port);\
    클라이언트사이드:\
          Client client = new Client();\
          CompleteableFuture<Channel> futureClientChannel = client.run(host, port);\
