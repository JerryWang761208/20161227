<!-- $theme: default -->

# <strong style="color:#e74c3c;font-size:100px">CDN</strong>
## &&
# <strong style="color:#3498db;font-size:100px">Microsoft</strong> Open Source

---

# Agenda
1. What is CDN
2. Why we need CDN 
3. KKBox
4. Microsoft

---

## 1. What is CDN

+ Content Delivery Network
+ Content Distribution Network
![](http://i2.wp.com/nitroxenon.com/wp-content/uploads/2014/10/cdn.jpg?zoom=2&resize=565%2C375)

---

## 2. Why we need CDN

+ Load balance 
+ Scalability 
+ Reliability 
+ Performance 

---

+ **offload static parts**: css, js, images, videos ... etc.

---

![](https://cdn.keycdn.com/img/cdn-benefits-explained.png)

---

[![](https://img.youtube.com/vi/SdVWAX2Js-g/0.jpg)](https://www.youtube.com/watch?v=SdVWAX2Js-g)

---

## KKBox
[smokeping](https://smokeping.kkbox.com.tw/)

---

## first slide
CDN 是什麼?
內容傳遞網路（Content delivery network或Content distribution network，常簡寫成 CDN ）是指一種透過網際網路互相連接的電腦網路系統，提供高效能、可擴展性、及低成本的網路將內容傳遞給使用者。

![](http://i2.wp.com/nitroxenon.com/wp-content/uploads/2014/10/cdn.jpg?zoom=2&resize=565%2C375)

---
<!-- page_number: true -->

## second slide
對於TCP傳輸而言，TCP的速度（throughput）會受到延遲時間（latency）與封包漏失率（packet loss）影響。為了改善這些負面因素，內容傳遞網路通常會指派較近、較順暢的伺服器節點將資料傳輸給使用者。雖然距離並不是絕對因素，但這麼做可以盡可能提高效能，使用者將會覺得比較順暢。這使得一些比較高頻寬的應用（傳輸高畫質畫質的影片）更容易推動。
內容傳遞網路另外一個好處在於有異地備援。當某個伺服器故障時，系統將會調用其他鄰近地區的伺服器服務，進而提供接近100%的可靠度。
除此之外，內容傳遞網路提供給服務提供者更多的控制權。提供服務的人可以針對客戶、地區，或是其他因子調整。

---

A Content Delivery Network (or Content Distribution Network) is a system of strategically positioned servers around the globe. These servers maintain and accelerate your content. The main goals of a CDN are about **speed, scalability and high-availability**. A request from a user will always be routed to the nearest point of presence (POP). User’s distance to these servers has an impact on loading time. A closer and highly performing POP will significantly improve user experience as a result of reduced **loading time, lower latency and minimized package loss**. A Content Delivery Network will also cut the operational cost and makes it easy to scale seamlessly without extra effort. We supercharge your content delivery whether it’s a game, software or any other web data.

---

![](https://cdn.keycdn.com/img/cdn-benefits-explained.png)

---

網頁上的圖片、CSS檔案以及JS檔案都不需要透過我們自己的主機來提供，而是透過CDN的主機來提供

---

1. 用戶在瀏覽器中輸入要訪問的域名；

2. 瀏覽器向域名解析伺服器發出解析請求，由於CDN對域名解析過程進行了調整，所以用戶端一般得到的是該域名對應的CNAME記錄，此時瀏覽器需要再次對獲得的CNAME域名進行解析才能得到緩存伺服器實際的IP位址。

註：在此過程中，全局負載均衡DNS解析伺服器會根據用戶端的源IP位址，如地理位置（深圳還是上海）、接入網類型（電信還是網通）將用戶的訪問請求定位到離用戶路由最短、位置最近、負載最輕的Cache節點（緩存伺服器）上，實現就近定位。定位優先原則可按位置、可按路由、也可按負載等。

3. 再次解析後瀏覽器得到該域名CDN緩存伺服器的實際IP位址，向緩存伺服器發出訪問請求；

4. 緩存伺服器根據瀏覽器提供的域名，通過Cache內部專用DNS解析得到此域名源伺服器的真實IP位址，再由緩存伺服器向此真實IP位址提交訪問請求；

5. 緩存伺服器從真實IP位址得到內容後，一方面在本地進行保存，以備以後使用，同時把得到的數據發送到客戶端瀏覽器，完成訪問的響應過程；
原文網址：https://read01.com/xDGn3D.html

6. 用戶端得到由緩存伺服器傳回的數據後顯示出來，至此完成整個域名訪問過程。
原文網址：https://read01.com/xDGn3D.html