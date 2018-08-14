## 什么是流量劫持


![](https://ws1.sinaimg.cn/large/a3fc3b79ly1fu9da5f298j20g4096ac1.jpg)

流量劫持，是利用各种恶意软件修改浏览器、锁定主页或不停弹出新窗口，强制用户访问某些网站，从而造成用户流量损失的情形。

流量劫持是一种古老的攻击方式，比如早已见惯的广告弹窗(如下图)等，很多人已经对此麻木，并认为流量劫持不会造成什么损失。

而事实上，流量劫持可以通过多种你无法觉察的方式窃取信息!

流量劫持是一个非常庞大的产业链，所以十分普遍，目前百度、谷歌等均已全站HTTPS 。


## 流量劫持能做什么？


![](https://ws1.sinaimg.cn/large/a3fc3b79ly1fu9d9i97ktj21o01hckjl.jpg)

1. 重定向下载链接，参考之前“UC 事件”，下载 A 软件，实际得到的是 B 软件，当然隐秘一点的可以给你换成带推广的 A 软件。

![](https://ws1.sinaimg.cn/large/a3fc3b79ly1fu9dc4o443j20ny0drgty.jpg)

2. 网页内插入广告，目前已经可以实现按时段，按用户，按次数展示，十分隐蔽。


3. 重定向推广。比如访问商品时候，会302 重定向加入推广链接，等待用户支付后，以收取平台佣金，而用户端是无感知的。


4. 劫持网页，直接跳转到 xx赌场  等等。 （之前有企业因为流量劫持到不正规网站而被误认为从事非法项目，直接封杀公众号，无法解封）


## HTTPS 如何预防流量劫持


![](https://ws1.sinaimg.cn/large/a3fc3b79ly1fu9dhr8jyij20cs08lgm6.jpg)

参考之前文章，由于 HTTPS 足够安全，且无法伪造，因此一般劫持者不会选择运营商下手。

1. DNS 劫持： 实际上 HTTPS 并不能预防 DNS 劫持，但是由于用户访问页面会空白或者显示网页 HTTPS 不正常，此时会找运营商投诉，因此一般运营商对 DNS 劫持比较慎重，HTTPS 反而是安全的。

2. HTTP 劫持：事实上，劫持者一般会直接放行 HTTPS 流量，劫持 HTTPS 网页并不能让用户端显示正常的网页内容。

3. 预置证书： 像一些公司，网吧会强制预置根证书，配合网关达到 HTTPS 劫持的目的。（此方式只能通过 解析 CAA 记录解决劫持，但网页显示空白）

## 流量劫持有多广泛

大到运营商，路由器厂商，甚至浏览器，杀毒软件... 都有存在流量劫持的行为，HTTPS 是网页唯一的救命稻草。

