### Command for creating source code from wsdl file
> wsimport - d src/main/java -p org.lelyak.demo.webservices -extension -Xnocompile http://www.webservicex.net/geoipservice.asmx?WSDL

#### some ip addresses:
  
  * Googgle   -   173.194.113.192  
  * BBC       -   212.58.244.20
  
-------------- 
  
####СДП таск 1:
Есть сервис Рест сервис 
>freegeoip.net

формат запроса freegeoip.net/{format}/{ip_or_hostname}  
там указаны форматы запроса. 

####Задача: 
написать фреймворк, который будет включать rest client основанный на JAX-RS
должны быть модели и использован mapping.
для маппинга энтитей с JSONом используй Jackson, для мапинга с XML - JAXB
в качестве тестового фреймворка - TestNG

####приклад 
>http://www.developer.com/java/creating-restful-web-services-with-jax-rs.html  
>http://ru.wikipedia.org/wiki/JSON

####Аналогічний сервіс під соап: таск такий же як для реста
>http://www.webservicex.net/geoipservice.asmx?WSDL

####корисні лінки - javabrains:
https://www.youtube.com/watch?v=6hqDMS-oJ9k  
https://www.youtube.com/watch?v=KFlDdb65w3U

#####REST:
>https://www.youtube.com/watch?v=maEtpN-kTyI&index=11

CXF Jax-RS Client API (це в останню чергу REST):
>http://cxf.apache.org/docs/jax-rs-client-api.html

CXF Jax-WS Client API:
>http://cxf.apache.org/docs/developing-a-consumer.html  