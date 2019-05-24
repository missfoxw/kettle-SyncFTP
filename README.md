## kettle-SyncFTP
使用Kettle完成通用DB数据获取生成指定分隔符的文件并通过FTP上传的功能

* [概要说明](./Sample-FTP/readme.md)
* [**具体功能博客介绍**](https://www.cnblogs.com/missfox18/p/7642026.html)


## 不基于时间戳的简单增量同步[GO](https://github.com/missfoxw/pdi-Kettle/blob/master/%E5%AE%8C%E6%95%B4%E7%9A%84%E5%BC%80%E5%8F%91%E5%AE%9E%E4%BE%8B/README.md#82-%E4%B8%80%E6%AC%A1%E5%9F%BA%E4%BA%8E%E8%B5%84%E6%BA%90%E5%BA%93%E5%92%8Cjenkin%E8%B0%83%E5%BA%A6%E7%9A%84linux%E5%BC%80%E5%8F%91%E6%A1%88%E4%BE%8B)
场景：B业务系统提供数据，DB->Oracle；A业务系统需要周期对B系统现网数据进行增量同步，DB->Informix。
![](./Sync-incremental/sync-incremental.png)
