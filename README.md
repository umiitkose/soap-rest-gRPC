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

Sunumu kaçıran arkadaşlar için youtube kanalımda SOAP ve REST'i anlatmıştım. gRPC'yi de yakın zamanda ekliyor olacağım.

[REST Web Servis anlatımı](https://www.youtube.com/watch?v=nOEctXEVUo0&t=662s)

[SOAP Anlatımı](https://www.youtube.com/watch?v=V2Zy22PffvE&t=630s)

[SOAP Jax-ws örneği](https://www.youtube.com/watch?v=UIQO1Z0e8SE&t=26s)

**Yararlandığım Kaynaklar: **

[SOAP 1.1](https://www.w3.org/TR/2000/NOTE-SOAP-20000508/)

[SOAP 1.2](https://www.w3.org/TR/soap12/)

[WSDL](https://www.w3.org/TR/2001/NOTE-wsdl-20010315)

[Örnek Soap Web Service](http://www.dneonline.com/calculator.asmx?wsdl)

[HTTP 1.0](https:/datatracker.ietf.org/doc/html/rfc1945)

[HTTP 1.1](https://datatracker.ietf.org/doc/html/rfc2616)

[HTTP 2.0](https:/datatracker.ietf.org/doc/html/rfc9113)

[HTTP 3.0](https:/datatracker.ietf.org/doc/rfc9114/)

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

[HTTP 1.1 vs HTTP 2.0 ](http://www.http2demo.io/)

**gRPC için yararlandığım tutoriallar** 

[gRPC Döküman](https://github.com/grpc/grpc)

[gRPC g 'sinin açılımları](https://github.com/grpc/grpc/blob/master/doc/g_stands_for.md)

[Easily Understanding gRPC](https://www.youtube.com/watch?v=jq7ZkSap9ko)

[gRPC Web](https://grpc.io/docs/platforms/web/quickstart/)

[gRPC Core Concept](https://grpc.io/docs/what-is-grpc/core-concepts/)

[protobuf github adresi](https://github.com/protocolbuffers/protobuf)

[gRPC github adresi](https://github.com/grpc/grpc?tab=readme-ov-file)

[Protocol buffers resmi site](https://protobuf.dev/)

[gRPC örnek kullanım - (Türkçe)](https://medium.com/deliveryherotechhub/grpc-nedir-ve-nas%C4%B1l-uygulan%C4%B1r-microservice-mimarisi-ile-grpc-9f1dc0847475)

[Bytebytego ](https://blog.bytebytego.com/p/ep32-how-does-grpc-work)

[ByteBytego youtube kanalı](https://www.youtube.com/@ByteByteGo)

