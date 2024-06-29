


## 操作命令

```sh

# 测试 mvn helloworld 使用框架快速构建helloworld
mvn archetype:generate -DgroupId=com.example -DartifactId=helloworld -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

cd helloworld && mvn clean package && mvn exec:java -Dexec.mainClass=com.example.App


```



