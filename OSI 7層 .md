# (一) 實體層 (Physical Layer)
~~~
在硬體上傳送數位訊號，各種硬體標準，傳輸時電壓的規範等等
例如：集線器(Repeater 1轉1)、中繼器(Hub 1轉多)、線路、無線電、光纖、針腳、電壓、線纜規範、網卡、主機介面卡
~~~
# (二) 資料鏈結層 (Data-Link Layer)
~~~
訊框 (frame) 與實體位置 (MAC)
分為兩個子層：
(一)邏輯連結控制(Logical Link Control, 簡稱LLC)：訊框遞送、錯誤通知、資料流控制
(二)媒介存取控制(Media Access Control, 簡稱MAC)：定義傳輸媒體存取的方式，如CSMA/CD、Token Ring等
例子 ：Physical Address、OSI規定網路上各乙太網路、記號環網路、橋接器等都是在此層運作的。
~~~
# (三) 網路層 (Network Layer)
~~~
邏輯定址

(資料封包 (packet) 的傳輸路徑(Routing)選擇)

功能：1.決定移動資料的最佳方式(RIP、EIGRP、OSPF) 2.資料遶送 3.錯誤控制少用
例子：IP、IPX、ICMP、IPX、BGP、OSPF、RIP、IGRP、EIGRP、ARP、RARP、X.25、路由器
~~~
# (四) 傳輸層 (Transport Layer)
~~~
提供可靠或不可靠的遞送
重傳之前先校正錯誤
功能 ：(封包順序、資料流量控制、偵測重複的封包、緊急資料的傳送、複雜的錯誤與回復處理、以及安全方面的課題)
例子 ：TCP UDP、UDP、RTP、SCTP、SPX、ATP、IL
~~~
# (五) 交談層 (Session Layer)   
~~~
(負責建立、管理、以及終止兩個通訊主機的對話)
功能 ：使不同應用程式的資料與其他應用程式的資料分開
例子 ：ASAP、ISO 8327 / CCITT X.225、RPC、NetBIOS、ASP、IGMP、Winsock、BSD sockets
~~~
# (六) 表現層 (Presentation Layer)
~~~
(處理不同資料格式之間的字碼轉換及編碼及解碼)
功能：字元碼轉換  資料形態轉換  對資料進行壓縮和加密﹐以提高速度和增加安全性
例子：ASCII 碼和 EDCDIC 碼之間的轉換
XDR、ASN.1、SMB、AFP、NCP
~~~
# (七) 應用層 (Application Layer)
~~~
提供使用者介面
功能：檔案、印表、訊息、資料庫、應用服務
例子：HTTP 、 Telnet 、 SMTP 、 POP3 、 FTP 、 SNMP
~~~
