## TrackerListsBale

很多BT下载客户端只能配置一个tracker list订阅源，如果想要订阅多个只好手动合并，非常麻烦。通过这个Url，可以将多个订阅源合并为一个，结果自动去重。

> https://tracker-lists.koharu.top

## 参数

不传`reset`参数的情况下，默认使用该项目[list.txt](https://github.com/koharubiyori/TrackerListsBale/blob/master/list.txt)文件中定义的订阅源。

* `divider`：返回的tracker之间的分隔字符，默认为换行符(`\n`)
* `append`：要追加的订阅源，多个订阅源之间以逗号分割。
* `reset`：覆盖list.txt文件中的订阅源，多个订阅源之间以逗号分割。