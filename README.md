### Simple multi-user chat client&server example.

```
$ javac -cp '.:jedis-2.9.0.jar:commons-pool2-2.5.0.jar' -d . ChatServer.java
$ java -cp '.:jedis-2.9.0.jar:commons-pool2-2.5.0.jar' libs.ChatServer
$ telnet localhost 9001
```
