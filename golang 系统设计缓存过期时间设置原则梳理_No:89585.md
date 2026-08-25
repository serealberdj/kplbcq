最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计缓存过期时间设置原则梳理
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://zhishi.z6tw20.asia/blog/3693819.sHtML

原标题：golang 系统设计灰度发布流量切分实现
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://zhishi.z6tw20.asia/blog/7841321.sHtML

原标题：golang 系统设计第三方接口 mock 单元测试
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://zhishi.z6tw20.asia/blog/3755515.sHtML

原标题：golang 单例模式实现几种方式
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://zhishi.z6tw20.asia/blog/7102235.sHtML

原标题：golang 系统设计代码仓库权限管理方案
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://zhishi.z6tw20.asia/blog/4867951.sHtML

原标题：golang 项目目录分层规范设计
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://zhishi.z6tw20.asia/blog/4295656.sHtML

原标题：部署实践：多实例服务部署无状态改造
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://zhishi.z6tw20.asia/blog/6145482.sHtML

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://zhishi.z6tw20.asia/blog/2518889.sHtML

原标题：业务幂等键设计防重复逻辑
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://zhishi.z6tw20.asia/blog/3133540.sHtML

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://zhishi.z6tw20.asia/blog/4445926.sHtML

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://zhishi.z6tw20.asia/blog/7625088.sHtML

原标题：方案设计：多租户系统架构三种实现模式对比
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://zhishi.z6tw20.asia/blog/9233508.sHtML

原标题：部署实践：Nginx高可用配置方案实践
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://zhishi.z6tw20.asia/blog/1048994.sHtML

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://zhishi.z6tw20.asia/blog/8589497.sHtML

原标题：包管理器依赖冲突解决方案
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://zhishi.z6tw20.asia/blog/3485916.sHtML

原标题：golang 分页查询封装通用工具
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://zhishi.z6tw20.asia/blog/1092056.sHtML

原标题：golang 系统设计缓存故障降级处理方案
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://zhishi.z6tw20.asia/blog/2968586.sHtML

原标题：golang 系统设计分布式事务几种方案优缺点
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://zhishi.z6tw20.asia/blog/5920082.sHtML

原标题：快速上手简单性能监控指标查看
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://zhishi.z6tw20.asia/blog/4635750.sHtML

原标题：安全实践：容器最小化镜像减少攻击面
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://zhishi.z6tw20.asia/blog/1972713.sHtML

原标题：快速入门对象存储基础使用场景
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://zhishi.z6tw20.asia/blog/4104245.sHtML

原标题：简易日志收集集中管理方案
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://zhishi.z6tw20.asia/blog/5770011.sHtML

原标题：部署复盘：静态资源版本哈希缓存策略
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://zhishi.z6tw20.asia/blog/2640818.sHtML

原标题：部署实践：多实例服务部署无状态改造
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://zhishi.z6tw20.asia/blog/9486832.sHtML

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://zhishi.z6tw20.asia/blog/4865879.sHtML

原标题：golang 系统设计无锁编程思路简单示例
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://zhishi.z6tw20.asia/blog/1645821.sHtML

原标题：实践：分布式事务本地模拟验证实践
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://zhishi.z6tw20.asia/blog/1958030.sHtML

原标题：前后端会话登录状态持久化
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://zhishi.z6tw20.asia/blog/6731000.sHtML

原标题：golang 系统设计日志采样降低存储开销方案
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://zhishi.z6tw20.asia/blog/6785087.sHtML

原标题：golang ip 限流黑名单实现方案
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://zhishi.z6tw20.asia/blog/7814611.sHtML

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://zhishi.z6tw20.asia/blog/3871786.sHtML

原标题：golang k8s 网络策略网络隔离设置
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://zhishi.z6tw20.asia/blog/1565011.sHtML

原标题：ICMP 放通网络丢包问题修复
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://zhishi.z6tw20.asia/blog/3946862.sHtML

原标题：nodejs jwt 登录鉴权完整示例
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://zhishi.z6tw20.asia/blog/1612866.sHtML

原标题：Performance：JSON序列化性能优化实践
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://zhishi.z6tw20.asia/blog/0062459.sHtML

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://zhishi.z6tw20.asia/blog/0149324.sHtML

原标题：golang docker 镜像体积优化技巧
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://zhishi.z6tw20.asia/blog/4286428.sHtML

原标题：部署实践：多实例服务部署无状态改造
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://zhishi.z6tw20.asia/blog/3575424.sHtML

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://zhishi.z6tw20.asia/blog/8294758.sHtML

原标题：实践：数据库备份脚本自动化编写实践
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://zhishi.z6tw20.asia/blog/0107562.sHtML


二、踩坑排错｜Troubleshooting
原标题：golang 项目目录分层规范设计
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://zhishi.z6tw20.asia/blog/9352562.sHtML

原标题：架构笔记：多数据源架构设计事务处理难点
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://zhishi.z6tw20.asia/blog/9759416.sHtML

原标题：golang 系统设计监控告警阈值设置思路
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://zhishi.z6tw20.asia/blog/9136917.sHtML

原标题：数值类型溢出错乱问题修复
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://zhishi.z6tw20.asia/blog/8983502.sHtML

原标题：CI 流水线构建失败日志排查
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://zhishi.z6tw20.asia/blog/4473938.sHtML

原标题：性能复盘：锁等待严重业务逻辑优化记录
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://zhishi.z6tw20.asia/blog/4835468.sHtML

原标题：Practice：简易限流器分布式版本Redis实现
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://zhishi.z6tw20.asia/blog/1242639.sHtML

原标题：golang 文件上传下载接口开发
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://zhishi.z6tw20.asia/blog/0805506.sHtML

原标题：golang 系统设计第三方调用超时重试熔断
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://zhishi.z6tw20.asia/blog/8836909.sHtML

原标题：Architecture：对象存储接入业务整体架构
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://zhishi.z6tw20.asia/blog/7323065.sHtML

原标题：golang 系统设计技术方案文档模板参考
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://zhishi.z6tw20.asia/blog/2721999.sHtML

原标题：多套环境灵活切换配置方案
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://zhishi.z6tw20.asia/blog/1933133.sHtML

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://zhishi.z6tw20.asia/blog/1013622.sHtML

原标题：缓存穿透防护保护数据库
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://zhishi.z6tw20.asia/blog/2785381.sHtML

原标题：golang 系统设计数据库连接池调优实践
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://zhishi.z6tw20.asia/blog/7508507.sHtML

原标题：多套环境灵活切换配置方案
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://zhishi.z6tw20.asia/blog/0056575.sHtML

原标题：读懂开源项目 README 实用技巧
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://zhishi.z6tw20.asia/blog/6730593.sHtML

原标题：开发记录：文件锁实现多进程互斥实践
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://zhishi.z6tw20.asia/blog/0872531.sHtML

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://zhishi.z6tw20.asia/blog/0416273.sHtML

原标题：跨平台换行符统一异常修复
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://zhishi.z6tw20.asia/blog/8213416.sHtML

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://zhishi.z6tw20.asia/blog/1883264.sHtML

原标题：golang 静态文件服务搭建教程
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://zhishi.z6tw20.asia/blog/8902493.sHtML

原标题：Fork 开源项目同步上游代码
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://zhishi.z6tw20.asia/blog/1117601.sHtML

原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://zhishi.z6tw20.asia/blog/1549455.sHtML

原标题：对象存储上传下载权限实操
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://zhishi.z6tw20.asia/blog/0754685.sHtML

原标题：golang k8s configmap secret 配置
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://zhishi.z6tw20.asia/blog/8719082.sHtML

原标题：nodejs 进程间通信 IPC 实操
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://zhishi.z6tw20.asia/blog/5254973.sHtML

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://zhishi.z6tw20.asia/blog/3754413.sHtML

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://zhishi.z6tw20.asia/blog/3579495.sHtML

原标题：复盘总结：技术选型对比文档模板实践
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://zhishi.z6tw20.asia/blog/1657030.sHtML

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://zhishi.z6tw20.asia/blog/9035681.sHtML

原标题：golang 系统设计日志级别业务使用原则梳理
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://zhishi.z6tw20.asia/blog/1638292.sHtML

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://zhishi.z6tw20.asia/blog/4028618.sHtML

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://zhishi.z6tw20.asia/blog/1783019.sHtML

原标题：golang jwt 鉴权中间件完整示例
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://zhishi.z6tw20.asia/blog/4461751.sHtML

原标题：部署实践：DockerCompose管理多服务环境
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://zhishi.z6tw20.asia/blog/5931102.sHtML

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://zhishi.z6tw20.asia/blog/8611830.sHtML

原标题：golang redis 过期策略内存淘汰
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://zhishi.z6tw20.asia/blog/5628449.sHtML

原标题：golang mysql 联合索引最左匹配
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://zhishi.z6tw20.asia/blog/8235247.sHtML

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://zhishi.z6tw20.asia/blog/5760100.sHtML

三、实战开发｜Practice
原标题：golang 系统设计联合索引设计避坑要点
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://zhishi.z6tw20.asia/blog/7516536.sHtML

原标题：rebase 操作防止代码丢失
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://zhishi.z6tw20.asia/blog/1908903.sHtML

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://zhishi.z6tw20.asia/blog/6736918.sHtML

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://zhishi.z6tw20.asia/blog/8727682.sHtML

原标题：golang docker 私有仓库搭建使用
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://zhishi.z6tw20.asia/blog/9317791.sHtML

原标题：文件句柄耗尽资源泄露处理
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://zhishi.z6tw20.asia/blog/1956946.sHtML

原标题：实战项目：实现分布式任务调度最小原型
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://zhishi.z6tw20.asia/blog/2368439.sHtML

原标题：golang gorm ORM 数据库操作
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://zhishi.z6tw20.asia/blog/5209069.sHtML

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://zhishi.z6tw20.asia/blog/7864726.sHtML

原标题：ICMP 放通网络丢包问题修复
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://zhishi.z6tw20.asia/blog/0753718.sHtML

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://zhishi.z6tw20.asia/blog/3755726.sHtML

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://zhishi.z6tw20.asia/blog/8680548.sHtML

原标题：实践：Git工作流主干开发团队协作实践
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://zhishi.z6tw20.asia/blog/8221576.sHtML

原标题：Hands‑on：简易图片压缩处理服务demo
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://zhishi.z6tw20.asia/blog/4894455.sHtML

原标题：开发记录：分布式ID生成器实现与压力测试
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://zhishi.z6tw20.asia/blog/4537684.sHtML

原标题：golang docker 镜像安全扫描漏洞
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://zhishi.z6tw20.asia/blog/5994757.sHtML

原标题：golang 系统设计滑动窗口限流代码示例
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://zhishi.z6tw20.asia/blog/8577530.sHtML

原标题：开发测试生产多环境配置区分
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://zhishi.z6tw20.asia/blog/2256948.sHtML

原标题：Hands‑on：简易短链接服务完整开发实践
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://zhishi.z6tw20.asia/blog/9481835.sHtML

原标题：安全实践：生产环境禁止开启debug调试模式
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://zhishi.z6tw20.asia/blog/5587610.sHtML

原标题：golang 系统设计降级策略开关配置方案
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://zhishi.z6tw20.asia/blog/8999750.sHtML

原标题：golang alertmanager 钉钉告警推送
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://zhishi.z6tw20.asia/blog/7071905.sHtML

原标题：Architecture：API网关核心能力与组件拆分
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://zhishi.z6tw20.asia/blog/6192431.sHtML

原标题：快速上手简单的限流逻辑模拟实现
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://zhishi.z6tw20.asia/blog/8212780.sHtML

原标题：golang 系统设计灰度发布流量切分实现
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://zhishi.z6tw20.asia/blog/5072980.sHtML

原标题：SSH 密钥配置 GitHub 免密登录
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://zhishi.z6tw20.asia/blog/3794703.sHtML

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://zhishi.z6tw20.asia/blog/5022790.sHtML

原标题：golang 系统设计密码存储哈希加盐实现
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://zhishi.z6tw20.asia/blog/6033823.sHtML

原标题：分布式 ID 全局唯一生成方案
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://zhishi.z6tw20.asia/blog/7447483.sHtML

原标题：文件编码统一随机乱码修复
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://zhishi.z6tw20.asia/blog/7538133.sHtML

原标题：实战：数据库索引设计，复合索引最佳实践
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://zhishi.z6tw20.asia/blog/2727763.sHtML

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://zhishi.z6tw20.asia/blog/9378365.sHtML

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://zhishi.z6tw20.asia/blog/6304166.sHtML

原标题：golang kafka 消费者偏移量管理
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://zhishi.z6tw20.asia/blog/6098918.sHtML

原标题：golang redis pipeline 批量操作
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://zhishi.z6tw20.asia/blog/7674105.sHtML

原标题：golang 系统设计数据库表设计通用规范模板
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://zhishi.z6tw20.asia/blog/2929176.sHtML

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://zhishi.z6tw20.asia/blog/6048059.sHtML

原标题：golang md5 sha 加密工具实现
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://zhishi.z6tw20.asia/blog/4572423.sHtML

原标题：开发复盘：海量日志轮转清理脚本实践
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://zhishi.z6tw20.asia/blog/0510061.sHtML

原标题：golang 系统设计密钥轮换安全实践思路
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://zhishi.z6tw20.asia/blog/3219351.sHtML

四、架构设计｜Architecture
原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://zhishi.z6tw20.asia/blog/3729353.sHtML

原标题：Practice：实现接口防重提交组件实践
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://zhishi.z6tw20.asia/blog/5735833.sHtML

原标题：golang mysql 行锁表锁场景区分
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://zhishi.z6tw20.asia/blog/1590715.sHtML

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://zhishi.z6tw20.asia/blog/8580169.sHtML

原标题：golang 系统设计缓存优化落地实操指南
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://zhishi.z6tw20.asia/blog/0370782.sHtML

原标题：golang 系统设计 rest http 方法使用原则
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://zhishi.z6tw20.asia/blog/0207514.sHtML

原标题：排错：对象存储跨域配置不生效前端上传失败
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://zhishi.z6tw20.asia/blog/7572833.sHtML

原标题：golang redis 批量 pipeline 实践
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://zhishi.z6tw20.asia/blog/6893671.sHtML

原标题：消息队列生产消费模型入门
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://zhishi.z6tw20.asia/blog/6476507.sHtML

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://zhishi.z6tw20.asia/blog/9021802.sHtML

原标题：nodejs 数据库连接池配置调优
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://zhishi.z6tw20.asia/blog/0580162.sHtML

原标题：golang 系统设计 webhook 回调处理架构
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://zhishi.z6tw20.asia/blog/5505055.sHtML

原标题：golang 系统设计压测工具 wrk 使用实操
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://zhishi.z6tw20.asia/blog/4216273.sHtML

原标题：灰度发布策略服务平滑升级
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://zhishi.z6tw20.asia/blog/6658940.sHtML

原标题：golang 系统设计消息发送确认机制配置实操
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://zhishi.z6tw20.asia/blog/6721117.sHtML

原标题：端口占用访问失败排查方案
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://zhishi.z6tw20.asia/blog/6469236.sHtML

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://zhishi.z6tw20.asia/blog/0712381.sHtML

原标题：坑点：软链接权限问题容器读取文件失败
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://zhishi.z6tw20.asia/blog/3909761.sHtML

?
