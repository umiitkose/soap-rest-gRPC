# soap-rest-gRPC
Ankara Tekmerde gerçekleştirilen Türkiye Java Community tarafından düzenlenen etkinlikte SOAP'tan REST'e, REST'ten gRPC'ye isimli etkinliğe ait dosyaları içeren repo'dur.

**Protocol Buffer için compiler:**
```
protoc  --java_out=.  weather.proto
```

**wsimport ile wsdl generate:**
```
wsimport -keep -verbose -s src/main/java/ http://localhost:8080/calculator\?wsdl
```


Yararlandığım Kaynaklar: 

[REST doktora tezi](https://ics.uci.edu/~fielding/pubs/dissertation/fielding_dissertation_2up.pdf)
[REST tezindeki yanlış anlaşılmalar](https://twobithistory.org/2020/06/28/rest.html)
[Facebook yazdığı Apache thrift](https://thrift.apache.org/static/files/thrift-20070401.pdf)
[gRPC ile JSON Kullanımı](https://grpc.io/blog/grpc-with-json/)
[Apache Avro](https://avro.apache.org/)
[SOAPUI](https://www.soapui.org/)
[POSTMAN](https://www.postman.com/)
[gRPC Java Dökümantasyonu](https://grpc.io/docs/languages/java/)
[HTTP 2 ile HTTP 1.1 Farkı Görsel](https://imagekit.io/demo/http2-vs-http1)
[HTTP 2 Multiplexing örnek](https://www.youtube.com/watch?v=2QVxUuTHLus)

**gRPC için yararlandığım tutoriallar** 

[Easily Understanding gRPC](https://www.youtube.com/watch?v=jq7ZkSap9ko)
[gRPC Web](https://grpc.io/docs/platforms/web/quickstart/)
[gRPC Core Concept](https://grpc.io/docs/what-is-grpc/core-concepts/)
[protobuf github adresi](https://github.com/protocolbuffers/protobuf)
[gRPC github adresi](https://github.com/grpc/grpc?tab=readme-ov-file)

[Protocol buffers resmi site](https://protobuf.dev/)
[gRPC örnek kullanım - (Türkçe)](https://medium.com/deliveryherotechhub/grpc-nedir-ve-nas%C4%B1l-uygulan%C4%B1r-microservice-mimarisi-ile-grpc-9f1dc0847475)

**Not: Eklemeler yapılacaktır**
