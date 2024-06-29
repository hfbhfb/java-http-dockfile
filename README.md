


## 操作命令

```sh

# 测试 mvn helloworld 使用框架快速构建helloworld
mvn archetype:generate -DgroupId=com.example -DartifactId=helloworld -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

cd helloworld
mvn clean package
mvn compile # 编译
#mvn exec:java -Dexec.mainClass=com.example.App # 这个参数 -Dexec.mainClass=com.example.App 似乎没有生效 
mvn exec:java


# 改造成http应用和构建镜像
mvn archetype:generate -DgroupId=com.hfbhfb -DartifactId=for-http-dockerfile -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

cd for-http-dockerfile
mvn clean package
mvn compile # 编译
#mvn exec:java -Dexec.mainClass=com.hfbhfb.App  # 这个参数 -Dexec.mainClass=com.example.App 似乎没有生效 
mvn exec:java 


```



