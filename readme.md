# 背景
作为一个Java开发者，在开发的过程中，总有一些代码是经常要用到的。有些可能是一些第三方JAR，但是总有一部分是我们自己造的轮子，而且自己造的用起来也比较顺畅，这个工具类就是这么而来的，也算是自己的一个积累，开源出来，有码同享嘛。

# 原则
不依赖任何第三方JAR。就是这么任性，不想受到别人的牵制。

# 功能说明
### Cache模块
实现了一套本地缓存。
### concurrent模块
对JDK自带的任务调度API进行了简单的封装。
### jdbc模块
主要是对SQL语法串的拼接操作等封装。
### io模块
主要是对File文件操作的api封装
### http
对Java原生的URLConnection进行封装，支持GET、POST、文件下载，文件上传等
### utils模块
这部分最有用个人觉得，里面是一些常用的工具类，每个工具类差不多都很独立，可以单独copy出来使用。
### domain
主要是常用的domain
### bt
这里放着一些奇奇怪怪的黑科技，指不定哪天你就会用到
（1）tracker 一个耗时日志打点工具，主要用来临时记录超长RT执行逻辑
（2）tabooed 一个敏感词过滤器，个人感觉好像效率不是很好，有待验证
（3）status 一个状态检查器工具，目前实现了内存使用和负载状态检查
