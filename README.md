# Spring Cloud Gate way

'''bash
$ ./gradlew clean bootRun

$ curl http://localhost:9000/hello
{"koreatime":"2025-10-17T11:28:52.689173148+09:00[Asia/Seoul]","message":"Hello, World!","timesptamp":1760668132689}%
$ curl http://localhost:9000/abc2
{"koreatime":"2025-10-17T11:28:48.327956872+09:00[Asia/Seoul]","message":"Hello, World!","timesptamp":1760668128327}% 
$ curl http://localhost:9000/abc
{"timestamp":"2025-10-17T02:28:46.409+00:00","status":404,"error":"Not Found","path":"/abc"}%   
```
