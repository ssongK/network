# TCP packet Sniffer



## 컴파일 및 실행
```
sudo apt update
sudo apt install -y libpcap-dev
gcc -o sniff_tcp sniff_tcp.c -lpcap
sudo ./sniff_tcp
```


## 실행 결과
로컬호스트와 가상머신 간의 nc 연결 후 패킷 교환 수행

![](result.png)
