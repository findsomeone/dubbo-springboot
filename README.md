# dubbo-springboot
dubbo+springboot的框架

1.下载zookeeper
http://www.apache.org/dyn/closer.cgi/zookeeper
将conf下的zoo_sample.cfg 重命名为zoo.cfg 
将路径改变即可

# The number of milliseconds of each tick
tickTime=2000
# The number of ticks that the initial 
# synchronization phase can take
initLimit=10
# The number of ticks that can pass between 
# sending a request and getting an acknowledgement
syncLimit=5
## the directory where the snapshot is stored.
dataDir=F:\\zookeeper\\data
dataDirLog=F:\\zookeeper\\log
## the port at which the clients will connect
clientPort=2181

