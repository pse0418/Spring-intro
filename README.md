# Welcome page
src > main > resources > static
index.html



# thymeleaf 템플릿 엔진 동작
src > main > java > hello > hellospring > controller

HelloController.java


src > main > resources > templates

hello.html



# 빌드하고 실행하기(cmd)
gradlew.bat

cd build

cd libs

java –jar hello-spring-0.0.1-SNAPSHOT.jar



# 정적 컨텐츠
src > main > resources > static

hello-static.html	localhost:8080/hello-static.html



# MVC : Model, View, Controller
src > main > java > hello > hellospring > controller

HelloController.java 18~22


src > main > resources > templates

hello-template.html	localhost:8080/hello-mvc?name=spring!!!



# API
src > main > java > hello > hellospring > controller

HelloController.java	24-28 localhost:8080/hello-string?name=spring!!!

@ResponseBody	30-48 localhost:8080/hello-api?name=spring!!! (JSON방식)
