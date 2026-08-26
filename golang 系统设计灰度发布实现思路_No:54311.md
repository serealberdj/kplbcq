最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计灰度发布实现思路
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.ea7a5m.asia/arts/097549.Doc

原标题：Performance：避免大报文，减少内存占用优化
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.ea7a5m.asia/arts/122232.Doc

原标题：golang 系统设计滑动窗口限流代码示例
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.ea7a5m.asia/arts/884874.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.ea7a5m.asia/arts/718070.Doc

原标题：设计思考：分布式会话架构选型对比
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.ea7a5m.asia/arts/274419.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://wiki.ea7a5m.asia/arts/210662.Doc

原标题：golang kafka 批量发送消费优化
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.ea7a5m.asia/arts/461685.Doc

原标题：Spring 事务传播机制配置生效
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.ea7a5m.asia/arts/049692.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.ea7a5m.asia/arts/348106.Doc

原标题：golang 系统设计 mq 故障降级业务策略
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.ea7a5m.asia/arts/054305.Doc

原标题：golang 系统设计数据库扩容几种方式
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.ea7a5m.asia/arts/321695.Doc

原标题：golang docker compose 依赖启动顺序
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://wiki.ea7a5m.asia/arts/514564.Doc

原标题：golang 系统设计服务优雅停机完整流程
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.ea7a5m.asia/arts/969691.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.ea7a5m.asia/arts/858448.Doc

原标题：新手参与开源社区贡献指南
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.ea7a5m.asia/arts/727711.Doc

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://wiki.ea7a5m.asia/arts/254557.Doc

原标题：数据库死锁成因规避方案
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.ea7a5m.asia/arts/728432.Doc

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.ea7a5m.asia/arts/607874.Doc

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.ea7a5m.asia/arts/934391.Doc

原标题：调优方案：静态资源缓存头Cache‑Control优化
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.ea7a5m.asia/arts/554540.Doc

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.ea7a5m.asia/arts/506091.Doc

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.ea7a5m.asia/arts/536690.Doc

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.ea7a5m.asia/arts/427472.Doc

原标题：DevOps：CI构建产物缓存复用加速编译
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.ea7a5m.asia/arts/098541.Doc

原标题：实战项目：容器资源限制配置压力测试实践
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.ea7a5m.asia/arts/815765.Doc

原标题：golang 系统设计避免索引失效书写 sql 原则
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://wiki.ea7a5m.asia/arts/416587.Doc

原标题：golang 系统设计 webhook 回调处理架构
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.ea7a5m.asia/arts/618586.Doc

原标题：golang 系统设计指标埋点代码低侵入实现
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.ea7a5m.asia/arts/858853.Doc

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.ea7a5m.asia/arts/420366.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.ea7a5m.asia/arts/416794.Doc

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.ea7a5m.asia/arts/378605.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.ea7a5m.asia/arts/370788.Doc

原标题：golang 系统设计开源版本发布 changelog 维护
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.ea7a5m.asia/arts/330672.Doc

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.ea7a5m.asia/arts/347271.Doc

原标题：Practice：批量异步任务处理系统设计实现
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.ea7a5m.asia/arts/344181.Doc

原标题：golang 系统设计 api 文档 swagger redoc 落地
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.ea7a5m.asia/arts/668927.Doc

原标题：﻿【GettingStarted】从零搭建本地开发环境完整指南
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.ea7a5m.asia/arts/159954.Doc

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.ea7a5m.asia/arts/047259.Doc

原标题：golang 系统设计海量数据分页查询
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.ea7a5m.asia/arts/932626.Doc

原标题：快速入门异步编程基础模型
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://wiki.ea7a5m.asia/arts/940709.Doc


二、踩坑排错｜Troubleshooting
原标题：golang docker 镜像构建最佳实践
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://wiki.ea7a5m.asia/arts/505784.Doc

原标题：golang 系统设计数据库慢请求排查流程
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.ea7a5m.asia/arts/222187.Doc

原标题：Issue：开源项目升级大版本后API不兼容踩坑
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.ea7a5m.asia/arts/885860.Doc

原标题：golang mysql 批量导入数据实操
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://wiki.ea7a5m.asia/arts/911513.Doc

原标题：golang es 分词器选型业务适配
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.ea7a5m.asia/arts/756764.Doc

原标题：服务熔断防止故障级联传播
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.ea7a5m.asia/arts/051524.Doc

原标题：坑点：环境配置写死代码，上线忘记修改
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.ea7a5m.asia/arts/567298.Doc

原标题：gitignore 文件编写过滤规则
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.ea7a5m.asia/arts/898855.Doc

原标题：序列化版本不一致解析失败
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.ea7a5m.asia/arts/935322.Doc

原标题：坑点：软链接权限问题容器读取文件失败
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.ea7a5m.asia/arts/710770.Doc

原标题：系统字符集统一乱码修复
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.ea7a5m.asia/arts/573695.Doc

原标题：设计思考：分布式会话架构选型对比
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.ea7a5m.asia/arts/809391.Doc

原标题：并发数据覆盖加锁安全处理
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.ea7a5m.asia/arts/766393.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://wiki.ea7a5m.asia/arts/313742.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.ea7a5m.asia/arts/530372.Doc

原标题：前后端交互跨域问题完整处理
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.ea7a5m.asia/arts/826701.Doc

原标题：线程调度优化减少上下文切换
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.ea7a5m.asia/arts/789668.Doc

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.ea7a5m.asia/arts/940171.Doc

原标题：复盘总结：线上故障完整复盘报告模板示例
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://wiki.ea7a5m.asia/arts/847247.Doc

原标题：优化实践：内存池思想减少频繁分配释放
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.ea7a5m.asia/arts/377166.Doc

原标题：服务器 Swap 关闭提升响应速度
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.ea7a5m.asia/arts/933073.Doc

原标题：golang mysql 连接泄漏检测方法
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.ea7a5m.asia/arts/348821.Doc

原标题：golang toml 配置文件解析教程
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.ea7a5m.asia/arts/765329.Doc

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.ea7a5m.asia/arts/871284.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.ea7a5m.asia/arts/309262.Doc

原标题：Mock 接口服务快速搭建实操
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.ea7a5m.asia/arts/784179.Doc

原标题：golang 系统设计故障应急响应完整流程梳理
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.ea7a5m.asia/arts/014439.Doc

原标题：nodejs 日志轮转生产环境配置
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.ea7a5m.asia/arts/894339.Doc

原标题：nodejs 消息队列消费服务开发
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.ea7a5m.asia/arts/963686.Doc

原标题：线程池拒绝策略任务丢失防护
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.ea7a5m.asia/arts/660334.Doc

原标题：对象存储上传下载权限实操
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.ea7a5m.asia/arts/966015.Doc

原标题：golang http 服务性能优化调参
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.ea7a5m.asia/arts/898622.Doc

原标题：golang 系统设计读写穿透更新缓存几种方案
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.ea7a5m.asia/arts/523962.Doc

原标题：开发记录：敏感数据加密存储解密业务实践
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.ea7a5m.asia/arts/015551.Doc

原标题：Performance：长连接管理优化减少连接重建开销
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.ea7a5m.asia/arts/608180.Doc

原标题：golang 系统设计数据库迁移工具 go‑migrate 实操
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://wiki.ea7a5m.asia/arts/269138.Doc

原标题：golang 分库分表简单路由实现
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.ea7a5m.asia/arts/084361.Doc

原标题：golang prometheus histogram 指标
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.ea7a5m.asia/arts/537154.Doc

原标题：配置与镜像分离防止信息泄露
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.ea7a5m.asia/arts/783198.Doc

原标题：安全实践：接口错误信息不要暴露内部细节
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://wiki.ea7a5m.asia/arts/864406.Doc

三、实战开发｜Practice
原标题：golang kafka 监控指标简单梳理
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://wiki.ea7a5m.asia/arts/638102.Doc

原标题：golang k8s ingress 路由域名转发
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.ea7a5m.asia/arts/292237.Doc

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.ea7a5m.asia/arts/606605.Doc

原标题：安全笔记：Cookie安全属性SecureHttpOnly
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.ea7a5m.asia/arts/962030.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.ea7a5m.asia/arts/336949.Doc

原标题：快速上手搭建简易内网测试服务
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.ea7a5m.asia/arts/117082.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.ea7a5m.asia/arts/824931.Doc

原标题：CORS 跨域问题多种解决方案
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.ea7a5m.asia/arts/351131.Doc

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.ea7a5m.asia/arts/936016.Doc

原标题：golang 系统设计分布式锁选型对比
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.ea7a5m.asia/arts/921509.Doc

原标题：Shell 脚本自动化命令编写
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.ea7a5m.asia/arts/125209.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://wiki.ea7a5m.asia/arts/506617.Doc

原标题：零基础理解会话、Cookie、Session基础
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.ea7a5m.asia/arts/114904.Doc

原标题：golang 系统设计降级策略开关配置方案
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.ea7a5m.asia/arts/881578.Doc

原标题：CI 流水线超时时间延长配置
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://wiki.ea7a5m.asia/arts/147578.Doc

原标题：golang 单例模式实现几种方式
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.ea7a5m.asia/arts/932136.Doc

原标题：golang kafka 核心概念分区副本
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.ea7a5m.asia/arts/451360.Doc

原标题：golang 数据库连接泄露排查
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.ea7a5m.asia/arts/162963.Doc

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.ea7a5m.asia/arts/824276.Doc

原标题：多实例部署 Session 共享方案
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.ea7a5m.asia/arts/050503.Doc

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://wiki.ea7a5m.asia/arts/065803.Doc

原标题：Performance：避免循环查询N+1问题完整优化
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.ea7a5m.asia/arts/277163.Doc

原标题：YAML 配置文件语法快速上手
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.ea7a5m.asia/arts/881528.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.ea7a5m.asia/arts/303860.Doc

原标题：golang 参数校验业务接口处理
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.ea7a5m.asia/arts/930492.Doc

原标题：Hands‑on：简易邮件发送服务封装实践
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.ea7a5m.asia/arts/812623.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.ea7a5m.asia/arts/087890.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.ea7a5m.asia/arts/395083.Doc

原标题：golang 系统设计压测工具 vegeta 使用示例
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.ea7a5m.asia/arts/494519.Doc

原标题：golang http grpc 全链路埋点示例
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.ea7a5m.asia/arts/458282.Doc

原标题：读懂开源项目 README 实用技巧
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.ea7a5m.asia/arts/777809.Doc

原标题：golang redis lua 脚本开发调试
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://wiki.ea7a5m.asia/arts/402616.Doc

原标题：开发记录：分布式ID生成器实现与压力测试
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://wiki.ea7a5m.asia/arts/111006.Doc

原标题：golang 系统设计分布式锁超时业务防死锁处理
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://wiki.ea7a5m.asia/arts/107604.Doc

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.ea7a5m.asia/arts/505460.Doc

原标题：golang redis 缓存雪崩完整处理
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.ea7a5m.asia/arts/673226.Doc

原标题：数据库死锁成因规避方案
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.ea7a5m.asia/arts/835053.Doc

原标题：golang 系统设计 api 网关核心能力完整梳理
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.ea7a5m.asia/arts/695006.Doc

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.ea7a5m.asia/arts/484894.Doc

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.ea7a5m.asia/arts/968142.Doc

四、架构设计｜Architecture
原标题：Redis 内存淘汰策略数据防丢失
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.ea7a5m.asia/arts/776639.Doc

原标题：golang k8s 基础概念 pod deployment
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.ea7a5m.asia/arts/308733.Doc

原标题：HelloDocker：编写你的第一个Dockerfile
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.ea7a5m.asia/arts/884782.Doc

原标题：golang 系统设计告警规则阈值设置方法论
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.ea7a5m.asia/arts/206737.Doc

原标题：Hands‑on：简易验证码生成校验后端实践
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://wiki.ea7a5m.asia/arts/306009.Doc

原标题：包管理器依赖冲突解决方案
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.ea7a5m.asia/arts/017762.Doc

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.ea7a5m.asia/arts/676613.Doc

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://wiki.ea7a5m.asia/arts/672899.Doc

原标题：WebSocket 双向通信 demo 开发
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.ea7a5m.asia/arts/539538.Doc

原标题：golang 系统设计索引设计通用方法论汇总
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.ea7a5m.asia/arts/936518.Doc

原标题：golang docker 部署 redis 配置要点
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.ea7a5m.asia/arts/933383.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.ea7a5m.asia/arts/389255.Doc

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://wiki.ea7a5m.asia/arts/217396.Doc

原标题：数值类型溢出错乱问题修复
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.ea7a5m.asia/arts/239845.Doc

原标题：排错：CI流水线构建失败，日志无明确报错
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.ea7a5m.asia/arts/230302.Doc

原标题：实践：数据库慢查询分析与索引优化实战演练
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.ea7a5m.asia/arts/799170.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.ea7a5m.asia/arts/906032.Doc

原标题：设计思考：分布式锁选型、风险、业务约束
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.ea7a5m.asia/arts/484259.Doc

?
