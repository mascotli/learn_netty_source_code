在工作中, 虽然我经常使用到 Netty 库, 但是很多时候对 Netty 的一些概念还是处于知其然, 不知其所以然的状态, 因此就萌生了学习 Netty 源码的想法.
刚开始看源码的时候, 自然是比较痛苦的, 主要原因有两个: 第一, 网上没有和详尽的 Netty 源码分析的教程; 第二, 我也是第一次系统地学习这么大代码量的源码. 由于这两个原因, 最开始时, 看代码的进度很慢, 甚至一度想放弃了, 不过最后很庆幸自己能够坚持下去, 并因此从 Netty 源码中学到了很多宝贵的知识.

下面我将自己在 Netty 源码学习过程记录下来, 整理成博客, 与大家分享交流, 共同学习. 由于本人才疏学浅, 文章中难免有不少错误之处, 期待能得到大家的建议和斧正.

最后, 忘了提了, 我使用的 Netty 版本: **4.0.33.Final**

https://segmentfault.com/a/1190000007403873 (原博客地址) <br/>
https://www.jianshu.com/u/90ab66c248e6 （占小狼博客）<br/>
https://www.jianshu.com/p/6b48196b5043 （占小狼消息读取博客）<br/>
https://blog.csdn.net/lemon89/article/details/77427338 （nio博客）<br/>
https://www.zhihu.com/question/24322387 (知乎神解释) <br/>
https://blog.csdn.net/jone_lu/article/details/49532171 (分布式rpc框架) <br/>
https://www.nutgeek.com/ (坚果极客) <br/>
https://blog.csdn.net/a953713428/article/details/68939371 (rpc) <br/>
https://blog.csdn.net/column/details/15621.html (rpc) <br/>
https://blog.csdn.net/linsongbin1/article/details/77915686 (rpc) <br/>
http://outofmemory.cn/code-snippet/ (rpc) <br/>
