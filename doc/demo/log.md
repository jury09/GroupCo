### 实践之日志分析。
#### 技术选型与架构
- 异步日志收集服务{可集群}(GroupCo)
- logstash(统一处理)
- elasticsearch(索引、存储)
- 异步api返回处理结果(GroupCo)
- ui展示(前端)

#### GroupCo在中间担任日志收集与日志结果返回的角色。利用异步特性，很好的应对上报日志时较高的并发。


