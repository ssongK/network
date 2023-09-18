# TCP packet Sniffer

## 컴파일 및 실행
```
sudo apt update
sudo apt install -y libpcap-dev
gcc -o sniff_tcp sniff_tcp.c -lpcap
sudo ./sniff_tcp
```

## 실행 결과
![](result.png)
