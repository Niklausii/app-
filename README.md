# app爬虫
抓取网页数据可以采用模拟访问网站然后抓取网页接收内容的模式进行数据抓取。而app更倾向于通过截获数据传输包的形式进行（Wireshark和Fiddler+python）
很多网站和手机app基本都是先把架子写好，然后往架子里填充数据，这些数据基本都是通过手机app或者网站向服务器发起请求，之后服务器返回json或者xml数据，然后网站或者手机app对数据进行解析到各个地方。、

## 关于Fiddler
Fidder是一个抓包神器，用来检查电脑和互联网之间所有的通讯内容。
首先设置Fiddler
