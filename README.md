
最近我开始写Java相关的技术系列，先从数据结构与算法入手。大家可以去[【公众号】](#公众号)获取或者加我[【微信】](#微信)提意见(别忘记**Star**哟)。

原创文章每周最少两篇，公众号首发文章。博客会晚一两篇。




<p align="center">
  <a href="#微信"><img src="https://img.shields.io/badge/weChat-微信群-blue.svg" alt="微信群"></a>
  <a href="#公众号"><img src="https://img.shields.io/badge/公众号-一角钱小助手-lightgrey" alt="公众号"></a>
  <a href="https://www.toutiao.com/c/user/token/MS4wLjABAAAAOhN0XemrWZKDxa6wo4TLfcNFiLU9oYveWN1-R8MimFA/"><img src="https://img.shields.io/badge/toutiao-头条-9cf" alt="投稿"></a>
  <a href="https://juejin.im/user/307518986264109"><img src="https://img.shields.io/badge/juejin-掘金-blue.svg" alt="公众号"></a>
  <a href="https://www.zhihu.com/people/hejianhui-72"><img src="https://img.shields.io/badge/zhihu-知乎-informational" alt="投稿"></a>
  <a href="https://blog.csdn.net/org_hjh"><img src="https://img.shields.io/badge/csdn-CSDN-red.svg" alt="投稿"></a>
</p>



# 目录

**注 : 没链接的是还没写**

- 数据结构与算法

    - [时间复杂度和空间复杂度分析](https://mp.weixin.qq.com/s/YwmEkaQgT36InDUaF0QjyA)
    - [数组的基本实现和特性](https://mp.weixin.qq.com/s?__biz=MzA4NjI1MTkyNw==&mid=302508523&idx=1&sn=70f4b4ca4f3f5adc2b833a1f592edae3&scene=19#wechat_redirect)
    - 链表和跳表的基本实现和特性
    - 栈、队列、优先队列、双端队列的实现与特性
    - 哈希表、映射、集合的实现与特性
    - [树、二叉树、二叉搜索树的实现与特性](https://mp.weixin.qq.com/s?__biz=MzA4NjI1MTkyNw==&mid=2449993586&idx=1&sn=5016403995c555669baa8a10c956c96c&chksm=8838cf8abf4f469c287fa0cd5e590d43d98f0c72148579af1f1b8711a8e4bab29861d8623228&scene=178#rd)
    - 堆和二叉堆的实现和特性
    - 图的实现和特性
    - 递归的实现、特性以及思维要点
    - [分治、回溯的实现和特性](https://mp.weixin.qq.com/s?__biz=MzA4NjI1MTkyNw==&mid=2449992294&idx=1&sn=0279a09ff528c0f4848d3f24c2725c20&scene=19#wechat_redirect)
    - [深度优先搜索、广度优先搜索的实现和特性](https://mp.weixin.qq.com/s?__biz=MzA4NjI1MTkyNw==&mid=2449992325&idx=1&sn=3028a98312b163ecd7f4700677bd4092&scene=19#wechat_redirect)
    - 贪心算法的实现和特性
    - [二分查找的实现和特性](https://mp.weixin.qq.com/s?__biz=MzA4NjI1MTkyNw==&mid=2449992484&idx=1&sn=b4090c8939b2c1fb86bd06d8a59c637a&chksm=8838cbdcbf4f42ca67d9e03b48ccdfa52d7c604aa53571a47fa21d0944c7cb5f02f8b9dd4fba&scene=178#rd)
    - [动态规划的实现及关键点](https://mp.weixin.qq.com/s?__biz=MzA4NjI1MTkyNw==&mid=2449992469&idx=1&sn=15634db09ed5bf36972e4941a7823d35&chksm=8838cbedbf4f42fb04baca5df20763a7567df8e3c480390f080729e9241108572b726862b528&scene=178#rd)
    - [Tire树的基本实现和特性](https://mp.weixin.qq.com/s?__biz=MzA4NjI1MTkyNw==&mid=2449992499&idx=1&sn=3ffe17cdfca02c8bf41846526c3bb54d&chksm=8838cbcbbf4f42dd82b673d41cacd31cbdd03cb0d098361806ed703a770345eb9b3a58033ce7&scene=178#rd)
    - [并查集的基本实现和特性](https://mp.weixin.qq.com/s?__biz=MzA4NjI1MTkyNw==&mid=2449992525&idx=1&sn=35f5c7c82744d59e83dfb81e7b7f504a&chksm=8838cbb5bf4f42a3d27515e6cf59871cc72c048674177352dacd677df990f54bfa884c70e8e5&scene=178#rd)
    - 剪枝的实现和特性
    - 双向BFS的实现和特性
    - 启发式搜索的实现和特性
    - [AVL树和红黑树的实现和特性](https://mp.weixin.qq.com/s?__biz=MzA4NjI1MTkyNw==&mid=2449992684&idx=1&sn=9722cce6d498ae69022796f887b07245&chksm=8838cb14bf4f420242679ff5d30c445cb5e1fd78b77742b917068879e3c28d19f854b9f58d56&scene=178#rd)
    - [位运算基础与实战要点](https://mp.weixin.qq.com/s?__biz=MzA4NjI1MTkyNw==&mid=2449992539&idx=1&sn=16dea41601c559135336b18f46e416c6&chksm=8838cba3bf4f42b5bd6a14e43c62306ea213925b51bf150e1b395dafafeae394402cac5f622d&scene=178#rd)
    - [布隆过滤器的实现及应用](https://mp.weixin.qq.com/s?__biz=MzA4NjI1MTkyNw==&mid=2449992555&idx=1&sn=3f16f8ac4c74b9af8d3629dbed698606&chksm=8838cb93bf4f42853f2436b2174adbfcd69bbf56f53e5ee486b652d848fade2f03c60f5a845a&scene=178#rd)
    - LRU Cache的实现及应用
    - 初级排序和高级排序的实现和特性
    - 字符串算法
    
- 性能优化

    - [MySQL索引底层数据结构与算法](https://mp.weixin.qq.com/s?__biz=MzA4NjI1MTkyNw==&mid=2449993426&idx=1&sn=ee5259d80cd38189a7d5001a063b1044&chksm=8838ce2abf4f473cc2f00957e7ced6cf57104d418e622a694b48e53ef74ed6b6ba4fbb61f950&scene=178#rd)
    - [MySQL性能优化原理-前篇](https://mp.weixin.qq.com/s?__biz=MzA4NjI1MTkyNw==&mid=2449993619&idx=1&sn=0e17f482b7bd97706a475e203e107806&chksm=8838cf6bbf4f467d3c3ce00597ff5e7979ed4f33303ae08091768b1e5bd8dc6062159bf9c701&scene=178#rd)
    - [MySQL性能优化-实践篇1](https://mp.weixin.qq.com/s/Etb39rkjtG32_jIAN0TUnQ)
    - [MySQL性能优化-实践篇2](https://mp.weixin.qq.com/s?__biz=MzA4NjI1MTkyNw==&mid=2449993711&idx=1&sn=9919c439750cffb835ec1fef410ccf07&chksm=8838cf17bf4f4601f7a0c6f9800c92de8a81ee557283db167306a44ae69b23146d14974c092e&scene=178#rd)
    - [深入理解MySQL锁与事物隔离级别](https://www.juejin.im/post/6875264015048638472)
    - [Tomcat深入解析与性能优化](https://mp.weixin.qq.com/s?__biz=MzA4NjI1MTkyNw==&mid=2449993199&idx=1&sn=ccbc65a939a8feb878355f357b6cd840&chksm=8838cd17bf4f44015274633bde1941301d743af6f9358be7a8bcb14e4e71a78bc2d8fa0b8c72&token=191979212&lang=zh_CN#rd)

技术交流群：添加我微信  org_hejianhui  备注【加群】即可

  <a name="微信"></a>  <a name="公众号"></a>
  
 ![](http://note.youdao.com/yws/public/resource/dc48a3654a1f505ae44450989de42c93/xmlnote/951B6B9454D548668E9208D249FEA2F8/19927)