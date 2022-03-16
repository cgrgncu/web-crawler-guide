# web-crawler-guide
練習爬蟲


### 網路封包(TCP)
  + https://en.wikipedia.org/wiki/Transmission_Control_Protocol

 
 ### 網路封包(UDP)
  + https://en.wikipedia.org/wiki/User_Datagram_Protocol

### Server- client
  + Server: 網頁伺服器
  + Client: 瀏覽器
## IP
  + IP v4 : 四個數字組成，140.115.21.38。

  + 私人網路: 「192.168.x.x」，「10.10.x.x」。
  + 本機網路: 「127.0.0.1」，「localhost」。
  
## Port
  + https://zh.wikipedia.org/wiki/TCP/UDP%E7%AB%AF%E5%8F%A3%E5%88%97%E8%A1%A8
  + HTTP是使用80
  + HTTPS是使用433

## 網址(域名系統，DNS)
  + Google DNS Server : 8.8.8.8


## 運作模式
  + 瀏覽器發送TCP請求，內容類似:
    ```
    GET /hello.html HTTP/1.1
    Host: 127.0.0.1
    Connection: keep-alive
    Upgrade-Insecure-Requests: 1
    User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/99.0.4844.51 Safari/537.36 Edg/99.0.1150.39
    sec-ch-ua: " Not A;Brand";v="99", "Chromium";v="99", "Microsoft Edge";v="99"
    sec-ch-ua-mobile: ?0
    sec-ch-ua-platform: "Windows"
    Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9
    Sec-Fetch-Site: none
    Sec-Fetch-Mode: navigate
    Sec-Fetch-User: ?1
    Sec-Fetch-Dest: document
    Accept-Encoding: gzip, deflate, br
    Accept-Language: zh-TW,zh;q=0.9,en;q=0.8,en-GB;q=0.7,en-US;q=0.6
    ```
+ Server回應:
+ 其中有一個部分就是HTML的內文。
## FTP Server
  + port 21。
  + 下次提供範例。
