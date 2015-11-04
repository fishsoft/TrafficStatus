# TrafficStatus
获取当前网速的小工具
static long  getMobileRxBytes()  //获取通过Mobile连接收到的字节总数，不包含WiFi  
static long  getMobileRxPackets()  //获取Mobile连接收到的数据包总数  
static long  getMobileTxBytes()  //Mobile发送的总字节数  
static long  getMobileTxPackets()  //Mobile发送的总数据包数  
static long  getTotalRxBytes()  //获取总的接受字节数，包含Mobile和WiFi等  
static long  getTotalRxPackets()  //总的接受数据包数，包含Mobile和WiFi等  
static long  getTotalTxBytes()  //总的发送字节数，包含Mobile和WiFi等  
static long  getTotalTxPackets()  //发送的总数据包数，包含Mobile和WiFi等   
static long  getUidRxBytes(int uid)  //获取某个网络UID的接受字节数  
static long  getUidTxBytes(int uid) //获取某个网络UID的发送字节数   
总接受流量TrafficStats.getTotalRxBytes()， 
总发送流量TrafficStats.getTotalTxBytes()); 
不包含WIFI的手机GPRS接收量TrafficStats.getMobileRxBytes()); 
不包含Wifi的手机GPRS发送量TrafficStats.getMobileTxBytes()); 
某一个进程的总接收量TrafficStats.getUidRxBytes(Uid)); 
某一个进程的总发送量TrafficStats.getUidTxBytes(Uid)); 
