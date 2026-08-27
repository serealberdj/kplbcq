最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计开源项目维护简单经验分享
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.nmnfoc.asia/blog/9382540.sHtMl

原标题：CPU 亲和性配置负载均衡调度
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://book.nmnfoc.asia/blog/1634600.sHtMl

原标题：Nginx 缓冲区调优大文件上传
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://book.nmnfoc.asia/blog/5611085.sHtMl

原标题：部署复盘：容器OOM问题完整排查流程
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://book.nmnfoc.asia/blog/4541692.sHtMl

原标题：DevOps：日志标准输出容器日志收集方案
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://book.nmnfoc.asia/blog/4509432.sHtMl

原标题：golang consul 服务发现简单示例
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://book.nmnfoc.asia/blog/4644209.sHtMl

原标题：OpenSource：开源项目贡献者协作流程规范
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://book.nmnfoc.asia/blog/4922359.sHtMl

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://book.nmnfoc.asia/blog/5956728.sHtMl

原标题：实践：数据库慢查询分析与索引优化实战演练
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://book.nmnfoc.asia/blog/1508145.sHtMl

原标题：golang 系统设计短链接服务实现思路
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://book.nmnfoc.asia/blog/4502980.sHtMl

原标题：内存溢出问题现象识别排查
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.nmnfoc.asia/blog/1871536.sHtMl

原标题：golang zap 日志按日期切割方案
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://book.nmnfoc.asia/blog/9874614.sHtMl

原标题：golang prometheus 指标暴露实现
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.nmnfoc.asia/blog/1610810.sHtMl

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://book.nmnfoc.asia/blog/6336292.sHtMl

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://book.nmnfoc.asia/blog/9085071.sHtMl

原标题：Git 标签版本标记发布管理
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://book.nmnfoc.asia/blog/8851225.sHtMl

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://book.nmnfoc.asia/blog/4379500.sHtMl

原标题：golang 错误包装 errors.wrap 用法
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://book.nmnfoc.asia/blog/9535651.sHtMl

原标题：golang 系统设计内部服务 mock 集成测试方案
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.nmnfoc.asia/blog/8870310.sHtMl

原标题：Issue：CI脚本超时，构建任务无故终止
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://book.nmnfoc.asia/blog/5588580.sHtMl

原标题：Security：反序列化漏洞风险识别与规避
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.nmnfoc.asia/blog/0885873.sHtMl

原标题：新手指南：本地防火墙端口访问失败排查
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.nmnfoc.asia/blog/1228355.sHtMl

原标题：golang redis bitmap 位图统计实现
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://book.nmnfoc.asia/blog/7238862.sHtMl

原标题：Spring 事务传播机制配置生效
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://book.nmnfoc.asia/blog/2403329.sHtMl

原标题：分布式任务调度集群原型开发
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://book.nmnfoc.asia/blog/9636838.sHtMl

原标题：单元测试用例编写入门实操
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://book.nmnfoc.asia/blog/3100494.sHtMl

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://book.nmnfoc.asia/blog/5356026.sHtMl

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://book.nmnfoc.asia/blog/7571454.sHtMl

原标题：golang redis 缓存雪崩完整处理
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://book.nmnfoc.asia/blog/3537894.sHtMl

原标题：配置外部化线上部署防错误
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://book.nmnfoc.asia/blog/7287754.sHtMl

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://book.nmnfoc.asia/blog/1956987.sHtMl

原标题：模拟登录鉴权权限判断示例
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.nmnfoc.asia/blog/6735100.sHtMl

原标题：golang kafka 生产者参数调优
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://book.nmnfoc.asia/blog/8738098.sHtMl

原标题：Git LFS 大文件推送失败解决
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://book.nmnfoc.asia/blog/8504505.sHtMl

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://book.nmnfoc.asia/blog/3094265.sHtMl

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://book.nmnfoc.asia/blog/2069206.sHtMl

原标题：方案设计：异步解耦业务架构边界识别
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.nmnfoc.asia/blog/7984896.sHtMl

原标题：实战项目：容器健康探针配置完整实践示例
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://book.nmnfoc.asia/blog/4830123.sHtMl

原标题：部署实践：多实例服务部署无状态改造
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://book.nmnfoc.asia/blog/2628386.sHtMl

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://book.nmnfoc.asia/blog/1242369.sHtMl


二、踩坑排错｜Troubleshooting
原标题：golang ip 限流黑名单实现方案
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.nmnfoc.asia/blog/5634196.sHtMl

原标题：golang 系统设计服务优雅停机完整流程
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://book.nmnfoc.asia/blog/7434248.sHtMl

原标题：HelloDocker：编写你的第一个Dockerfile
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://book.nmnfoc.asia/blog/2128473.sHtMl

原标题：端口占用访问失败排查方案
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.nmnfoc.asia/blog/9776801.sHtMl

原标题：golang 大文件 http 下载服务
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://book.nmnfoc.asia/blog/3813370.sHtMl

原标题：golang redis lua 脚本开发调试
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://book.nmnfoc.asia/blog/6262561.sHtMl

原标题：nodejs 日志轮转生产环境配置
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://book.nmnfoc.asia/blog/2047775.sHtMl

原标题：golang 系统设计一致性哈希原理讲解
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.nmnfoc.asia/blog/5340507.sHtMl

原标题：golang 系统设计熔断算法 hystrix 思路
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://book.nmnfoc.asia/blog/0929003.sHtMl

原标题：运维笔记：系统监控指标大盘搭建实操
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.nmnfoc.asia/blog/8844865.sHtMl

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://book.nmnfoc.asia/blog/6738693.sHtMl

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://book.nmnfoc.asia/blog/6032096.sHtMl

原标题：零基础理解依赖管理与包管理器
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.nmnfoc.asia/blog/9949836.sHtMl

原标题：安全实践：接口错误信息不要暴露内部细节
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://book.nmnfoc.asia/blog/8965387.sHtMl

原标题：架构笔记：WebSocket大规模连接服务架构
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.nmnfoc.asia/blog/3800279.sHtMl

原标题：golang github actions 发布 release 包
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://book.nmnfoc.asia/blog/0905868.sHtMl

原标题：配置与镜像分离防止信息泄露
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://book.nmnfoc.asia/blog/3866566.sHtMl

原标题：零基础理解JSON、XML数据格式处理
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.nmnfoc.asia/blog/2021251.sHtMl

原标题：golang docker 多阶段构建 go 镜像
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://book.nmnfoc.asia/blog/8606358.sHtMl

原标题：golang 系统设计消息体序列化选型对比
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://book.nmnfoc.asia/blog/3979877.sHtMl

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.nmnfoc.asia/blog/2616378.sHtMl

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://book.nmnfoc.asia/blog/0805811.sHtMl

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://book.nmnfoc.asia/blog/8809526.sHtMl

原标题：golang k8s pod 优雅关闭流程讲解
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://book.nmnfoc.asia/blog/7531027.sHtMl

原标题：内网 DNS 不稳定随机报错排查
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://book.nmnfoc.asia/blog/0500136.sHtMl

原标题：安全复盘：Redis未授权访问漏洞防护
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://book.nmnfoc.asia/blog/3595404.sHtMl

原标题：运维笔记：备份策略数据库定时备份脚本
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://book.nmnfoc.asia/blog/0516634.sHtMl

原标题：部署复盘：服务启动顺序依赖处理方案
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://book.nmnfoc.asia/blog/0854658.sHtMl

原标题：golang 系统设计日志规范结构化日志落地
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://book.nmnfoc.asia/blog/9645198.sHtMl

原标题：Redis 分布式锁高并发安全实现
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://book.nmnfoc.asia/blog/4425774.sHtMl

原标题：react hooks 常见陷阱避坑指南
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://book.nmnfoc.asia/blog/2116759.sHtMl

原标题：入门实践：简单的请求封装与异常捕获
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://book.nmnfoc.asia/blog/9686540.sHtMl

原标题：golang 系统设计监控缺失指标补全完整流程
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://book.nmnfoc.asia/blog/9370595.sHtMl

原标题：CI 流水线超时时间延长配置
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://book.nmnfoc.asia/blog/8910288.sHtMl

原标题：Performance：后端接口性能优化完整分析流程
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://book.nmnfoc.asia/blog/5842777.sHtMl

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://book.nmnfoc.asia/blog/3045073.sHtMl

原标题：无用对象回收抑制内存上涨
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://book.nmnfoc.asia/blog/5894434.sHtMl

原标题：golang 系统设计限流服务架构讲解
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://book.nmnfoc.asia/blog/4246771.sHtMl

原标题：golang 系统设计定时任务执行超时中断防护
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://book.nmnfoc.asia/blog/7544271.sHtMl

原标题：golang redis 持久化 RDB AOF 对比
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.nmnfoc.asia/blog/4063200.sHtMl

三、实战开发｜Practice
原标题：AI‑Dev：利用AI快速阅读陌生开源项目源码
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://book.nmnfoc.asia/blog/2340029.sHtMl

原标题：服务器时钟同步任务错乱修复
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://book.nmnfoc.asia/blog/4270241.sHtMl

原标题：golang 系统设计接口频率限制业务落地
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://book.nmnfoc.asia/blog/7511725.sHtMl

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://book.nmnfoc.asia/blog/5797853.sHtMl

原标题：golang 系统设计数据库死锁分析规避
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.nmnfoc.asia/blog/7872757.sHtMl

原标题：零基础理解会话、Cookie、Session基础
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://book.nmnfoc.asia/blog/8244165.sHtMl

原标题：golang redis 五种数据结构实战
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://book.nmnfoc.asia/blog/4942486.sHtMl

原标题：项目实践：本地模拟多节点分布式系统实践
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://book.nmnfoc.asia/blog/6803107.sHtMl

原标题：Practice：实现接口防重提交组件实践
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://book.nmnfoc.asia/blog/5672214.sHtMl

原标题：手写简易 RPC 服务通信原型
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://book.nmnfoc.asia/blog/0448641.sHtMl

原标题：nodejs 脚手架工具开发完整教程
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.nmnfoc.asia/blog/1347998.sHtMl

原标题：优化实践：接口批量合并减少网络请求次数
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://book.nmnfoc.asia/blog/2567628.sHtMl

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.nmnfoc.asia/blog/2086985.sHtMl

原标题：实践：分布式事务本地模拟验证实践
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://book.nmnfoc.asia/blog/9379900.sHtMl

原标题：golang 系统设计 rest 资源命名规范汇总
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.nmnfoc.asia/blog/8226337.sHtMl

原标题：开发复盘：统一错误码体系设计落地实践
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://book.nmnfoc.asia/blog/9260398.sHtMl

原标题：实战：WebSocket断线重连完整业务处理实践
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://book.nmnfoc.asia/blog/8837949.sHtMl

原标题：调优方案：Docker容器内核参数性能调优
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://book.nmnfoc.asia/blog/1914496.sHtMl

原标题：安全复盘：定时任务权限过大风险管控
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://book.nmnfoc.asia/blog/1253472.sHtMl

原标题：安全复盘：Redis命令注入风险防护手段
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://book.nmnfoc.asia/blog/4898457.sHtMl

原标题：golang gin 路由分组权限管控
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://book.nmnfoc.asia/blog/5713990.sHtMl

原标题：golang 系统设计配置敏感信息加密存储
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://book.nmnfoc.asia/blog/0446307.sHtMl

原标题：入门实践：简单的请求封装与异常捕获
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://book.nmnfoc.asia/blog/9872270.sHtMl

原标题：golang minio 存储桶权限管控配置
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://book.nmnfoc.asia/blog/2205833.sHtMl

原标题：golang 系统设计多租户数据隔离方案
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://book.nmnfoc.asia/blog/6368549.sHtMl

原标题：nodejs 多进程任务分发处理
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.nmnfoc.asia/blog/6141837.sHtMl

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.nmnfoc.asia/blog/2216961.sHtMl

原标题：实战：Nginx负载均衡多种策略配置实践
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://book.nmnfoc.asia/blog/8738290.sHtMl

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://book.nmnfoc.asia/blog/1678847.sHtMl

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://book.nmnfoc.asia/blog/5617358.sHtMl

原标题：golang 系统设计告警风暴抑制方案实现
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.nmnfoc.asia/blog/5310669.sHtMl

原标题：Nginx 请求头大小上限调整
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.nmnfoc.asia/blog/8644974.sHtMl

原标题：服务器时钟同步任务错乱修复
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://book.nmnfoc.asia/blog/5992861.sHtMl

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://book.nmnfoc.asia/blog/3740810.sHtMl

原标题：golang 系统设计本地缓存更新失效方案实现
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://book.nmnfoc.asia/blog/2215523.sHtMl

原标题：Architecture：API网关核心能力与组件拆分
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://book.nmnfoc.asia/blog/7227384.sHtMl

原标题：部署复盘：容器OOM问题完整排查流程
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://book.nmnfoc.asia/blog/0166901.sHtMl

原标题：数据库 utf8mb4 支持 emoji 存储
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://book.nmnfoc.asia/blog/2977869.sHtMl

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://book.nmnfoc.asia/blog/6230570.sHtMl

原标题：RPC 报文大小上限调优大请求
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://book.nmnfoc.asia/blog/7879240.sHtMl

四、架构设计｜Architecture
原标题：Hands‑on：简易请求转发代理中间件实现
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://book.nmnfoc.asia/blog/3351327.sHtMl

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://book.nmnfoc.asia/blog/5039479.sHtMl

原标题：golang 系统设计定时任务调度时间校准要点
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://book.nmnfoc.asia/blog/3780316.sHtMl

原标题：Issue：本地可以访问，容器内部网络不通
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.nmnfoc.asia/blog/7300154.sHtMl

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://book.nmnfoc.asia/blog/6096462.sHtMl

原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://book.nmnfoc.asia/blog/4419764.sHtMl

原标题：monorepo 项目多包管理最佳实践
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://book.nmnfoc.asia/blog/3276471.sHtMl

原标题：性能笔记：磁盘IO过高业务优化手段
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://book.nmnfoc.asia/blog/2380701.sHtMl

原标题：golang excel 简单读写操作示例
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://book.nmnfoc.asia/blog/0676356.sHtMl

原标题：Practice：实现接口幂等性多种方案对比实践
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://book.nmnfoc.asia/blog/3854505.sHtMl

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.nmnfoc.asia/blog/8576297.sHtMl

原标题：文件描述符优化进程卡死修复
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.nmnfoc.asia/blog/7505053.sHtMl

原标题：快速入门GraphQL基础查询语法示例
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://book.nmnfoc.asia/blog/8292640.sHtMl

原标题：golang 系统设计定时任务分片执行分布式思路
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://book.nmnfoc.asia/blog/7846552.sHtMl

原标题：golang docker 基础命令实操汇总
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://book.nmnfoc.asia/blog/9502441.sHtMl

原标题：开发记录：跨域中间件完整配置与边界处理
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://book.nmnfoc.asia/blog/1403094.sHtMl

原标题：接口压测定位系统性能瓶颈
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://book.nmnfoc.asia/blog/3664867.sHtMl

原标题：线上故障：慢查询拖垮整个数据库服务
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://book.nmnfoc.asia/blog/4940927.sHtMl

?
