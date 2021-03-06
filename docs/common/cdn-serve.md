## CDN 提供的服务

### 下载

下载服务是 CDN 提供的最简单的服务，通常是一些终端用户，如网游用户、软件用户、程序开发员及要下载大量文件的用户会使用到。通过使用CDN，人们便无需使用高带宽连接到昂贵的数据中心，并且通过CDN节点，这些文件会放到离终端用户更近的地方。



### 静态文件 / 图片

CDN 最常用的用途是用来给终端用户发布静态文件，如图片、java脚本、css文件等。通常这些类型的文件很少变更，即便有变更，也是少量的，所以，把文件发布并存放到离终端用户比较近的地方会极大地提高网站速度，在地理位置分散或连接性能很差的地方，网站速度提高会显得更加明显。请注意，该服务仅仅用于处理静态文件，如主要的网站页面，所有动态内容，都是由主网站服务器提供。这通常是分开处理的，通过不同的子域名进行处理，如images.mydomain.com，与www.是分开的。


### 整体网站加速

从名称便可知道，它是用来加速整个网站的，包括所有的静态的东西及动态的东西，如网页、购物车及推荐信息等。基本情况是，终端用户只连接到CDN，CDN连接到网站，然后缓存所有的东西，CDN代表用户向实体的网站后台发送请求，获取动态数据。</p>


### 流媒体内容

媒体类网站使用越来越多的流媒体内容，如视频，包括来自于其它网站(如Netflix、Hulu、或Youtube及中国的Tudou/Youku)的实际的电视节目、影片等。对于这些内容而言，CDN提供特别的下载服务，通常称之为点播或Vod，可以处理并控制所有视频，包括快进/后退视频，可以访问经过授权的内容，提供各种跟踪服务等。对于这些服务而言，视频通常是加载到CDN，并且通过特定的URL直接提供视频。此外，一些CDN还提供现场流体内容，如，体育或其它事件等实时播放，进行现场内容直播。


### 其它

CDN 有许多其它功能及服务，以满足特殊需求，如电商、预加载、网游、动态加速、安全及 DRM 控制等。此外，还提供特殊的满足地理要求或网络要求(如中国移动或CERNET)的特别服务。

CDN 还有一个服务容易被人忽略，就是安全服务。例如，许多 CDN 可提供防DDoS攻击服务，由于它们比任何一个网站的带宽都大，而且分散，所以能够经受住此类攻击。此外，一些专门的CDN如，CloudFlare 及 AnQuanBao 也提供像防火墙一样的应用程序，如防止SQL注入攻击、XSS攻击及其它防攻击手段以保护后台站点。

另一个特别的主要服务就是“内容感知”网络服务。这是一种新新服务，是通过CDN系统的更智能化管理的内容，可以给不同用户，如移动或DSL或办公室用户等提供不同的优化过的内容。它可以对内容进行处理，以便提供给不同设备，也可以对内容进行优化，以便将最重要的内容优先下载下来，使用户获得最佳体验。它们还会判断在哪个地方存放哪些内容，总之，该系统能够使网站在复杂的互联网环境下有良好的性能表现。

最后，有些CDN还提供全球服务，帮助客户开拓新区域或国际区域，如中国、拉美或国外其它地区。对于全球品牌而言，这种服务非常重要，对于想要获得国际客户的中国公司而言，这种服务也非常重要。这种全球或局部CDN帮助人们在无需数据中心及特别带宽等情形下，便可获得庞大的用户群。

根据您的需求及站点架构，使用CDN是非常容易的。对于静态图片CDN而言，关键的一点在于能够将静态内容或图片分离到特定的域名，然后存放到同一服务器上不同的虚拟机上。
