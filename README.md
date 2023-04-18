# NettyServiceProvider\
Simple Netty Server &amp; Client Connection \
\
사용법:\
    서버사이드:\
          Server server = new Server();\
          CompleteableFuture<Channel> futureServerChannel = server.run(port);\
    클라이언트사이드:\
          Client client = new Client();\
          CompleteableFuture<Channel> futureClientChannel = client.run(host, port);\
