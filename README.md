last update at: 2020.03.05 v1.2

debian or centos please run
```
curl -fsSL https://github.com/tokumeikoi/aurora/raw/master/install.sh | bash -s websiteurl token nodeid localport license
```

docker please run
```
docker run -d --name=aurora \
-p 连接端口:连接端口 \
-p 连接端口:连接端口/udp \
-e API=API \
-e TOKEN=TOKEN \
-e NODE=NODEID \
-e LICENSE=LICENSE \
tokumeikoi/aurora
```

old version  
https://github.com/tokumeikoi/aurora/releases

build
```
https://github.com/tokumeikoi/aurora.git
docker build ./aurora
```

buy it telegram @v2aurora