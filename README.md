# NettyServiceProvider
Simple Netty Server &amp; Client Connection 
\n
사용법:\n
    서버사이드:\n
          Server server = new Server();\n
          CompleteableFuture<Channel> futureServerChannel = server.run(port);
    클라이언트사이드:
          Client client = new Client();
          CompleteableFuture<Channel> futureClientChannel = client.run(host, port);
