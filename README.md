#docker-xwl-client

http://101.200.176.31:8181/nexus/service/local/artifact/maven/resolve?r=snapshots&g=com.xunwulian&a=xwl-cmpp-client&v=1.0-SNAPSHOT


wget http://101.200.176.31:8181/nexus/service/local/artifact/maven/resolve?r=snapshots&g=com.xunwulian&a=xwl-cmpp-client&v=1.0-SNAPSHOT

docker build -t xwl-client .

docker run --name xwl-client -d xwl-client

