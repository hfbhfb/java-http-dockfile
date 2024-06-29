
IMG=for-http-dockerfile
TAG=0.1

default:
	gowatch

docker: package
	docker build -f Dockerfile -t ${IMG}:${TAG} .

package:
	mvn clean # 
	mvn compile # 编译
	mvn package # 

run:
	java -jar target/for-http-dockerfile-1.0-SNAPSHOT.jar
