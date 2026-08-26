最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.t55d91.asia/arts/976752.Doc

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.t55d91.asia/arts/899974.Doc

原标题：记一次限流组件误配置把正常用户拦截
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.t55d91.asia/arts/611761.Doc

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.t55d91.asia/arts/347570.Doc

原标题：golang 限流熔断降级完整示例
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.t55d91.asia/arts/199858.Doc

原标题：业务错误码完整落地实践
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.t55d91.asia/arts/571913.Doc

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.t55d91.asia/arts/638393.Doc

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.t55d91.asia/arts/785830.Doc

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.t55d91.asia/arts/087084.Doc

原标题：实践：Git大仓库历史清理减小仓库体积实践
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://wiki.t55d91.asia/arts/567477.Doc

原标题：开发复盘：数据库批量更新优化性能实践
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.t55d91.asia/arts/770330.Doc

原标题：入门实践：简单批量处理脚本编写
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://wiki.t55d91.asia/arts/093963.Doc

原标题：golang 系统设计故障预案编写模板参考示例
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.t55d91.asia/arts/239328.Doc

原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.t55d91.asia/arts/888665.Doc

原标题：实战：单元测试+集成测试完整项目落地实践
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.t55d91.asia/arts/213692.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.t55d91.asia/arts/320687.Doc

原标题：线上异常：线程池队列拒绝策略配置错误丢任务
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.t55d91.asia/arts/364737.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.t55d91.asia/arts/486837.Doc

原标题：golang 系统设计监控缺失指标补全完整流程
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.t55d91.asia/arts/371307.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://wiki.t55d91.asia/arts/204351.Doc

原标题：golang redis 五种数据结构实战
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.t55d91.asia/arts/823230.Doc

原标题：golang mysql 时间类型选型避坑
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.t55d91.asia/arts/119574.Doc

原标题：业务幂等键设计防重复逻辑
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.t55d91.asia/arts/600657.Doc

原标题：Practice：实现异步回调处理通用组件封装
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.t55d91.asia/arts/572731.Doc

原标题：golang jwt 鉴权中间件完整示例
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.t55d91.asia/arts/693070.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.t55d91.asia/arts/027299.Doc

原标题：ORM 框架数据库增删改查实操
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.t55d91.asia/arts/587803.Doc

原标题：SSH 密钥配置 GitHub 免密登录
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.t55d91.asia/arts/859832.Doc

原标题：新手教程：如何给开源项目提交第一个PR
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.t55d91.asia/arts/607700.Doc

原标题：Docker 多阶段构建镜像瘦身
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://wiki.t55d91.asia/arts/275949.Doc

原标题：开发环境变量配置全平台教程
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.t55d91.asia/arts/415997.Doc

原标题：安全实践：敏感信息加密存储传输完整方案
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.t55d91.asia/arts/592345.Doc

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.t55d91.asia/arts/888447.Doc

原标题：hosts 配置本地回环访问修复
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.t55d91.asia/arts/728650.Doc

原标题：API 接口调试与异常处理实战
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.t55d91.asia/arts/679587.Doc

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.t55d91.asia/arts/188281.Doc

原标题：golang 系统设计故障止损降级回滚执行原则
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://wiki.t55d91.asia/arts/482803.Doc

原标题：架构复盘：多实例部署业务状态无状态改造
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.t55d91.asia/arts/856873.Doc

原标题：慢查询分析索引调优数据库实战
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.t55d91.asia/arts/822922.Doc

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.t55d91.asia/arts/530708.Doc


二、踩坑排错｜Troubleshooting
原标题：性能复盘：锁等待严重业务逻辑优化记录
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.t55d91.asia/arts/083680.Doc

原标题：Security：开源项目安全审计简易检查清单
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.t55d91.asia/arts/827362.Doc

原标题：golang 系统设计消息可靠性投递实现
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://wiki.t55d91.asia/arts/534766.Doc

原标题：nestjs 框架模块化项目搭建
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.t55d91.asia/arts/526227.Doc

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.t55d91.asia/arts/949680.Doc

原标题：端口占用访问失败排查方案
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.t55d91.asia/arts/230384.Doc

原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://wiki.t55d91.asia/arts/897271.Doc

原标题：golang kafka 消费者偏移量管理
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.t55d91.asia/arts/867398.Doc

原标题：Git 分支管理多人协作实战教程
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.t55d91.asia/arts/839871.Doc

原标题：安全复盘：业务登录暴力破解防护完整方案
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.t55d91.asia/arts/728021.Doc

原标题：Hands‑on：实现WebSocket聊天室完整前后端demo
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.t55d91.asia/arts/330068.Doc

原标题：golang es 分词器选型业务适配
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://wiki.t55d91.asia/arts/458845.Doc

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://wiki.t55d91.asia/arts/676057.Doc

原标题：golang 系统设计网关缓存静态资源实现思路
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.t55d91.asia/arts/237379.Doc

原标题：golang 系统设计 rest 资源命名规范汇总
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://wiki.t55d91.asia/arts/978025.Doc

原标题：golang 系统设计接口超时设计原则梳理
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.t55d91.asia/arts/669467.Doc

原标题：golang 系统设计定时任务分布式锁
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.t55d91.asia/arts/260717.Doc

原标题：数据库分表存储大表优化方案
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.t55d91.asia/arts/782177.Doc

原标题：快速入门ORM，实现简单数据库增删改查
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://wiki.t55d91.asia/arts/539587.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://wiki.t55d91.asia/arts/683584.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.t55d91.asia/arts/270614.Doc

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.t55d91.asia/arts/594036.Doc

原标题：程序日志分级输出规范实践
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.t55d91.asia/arts/481282.Doc

原标题：Performance：后端接口性能优化完整分析流程
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.t55d91.asia/arts/492964.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.t55d91.asia/arts/305942.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.t55d91.asia/arts/974938.Doc

原标题：golang 系统设计 cpu 高占用排查步骤
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.t55d91.asia/arts/560190.Doc

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.t55d91.asia/arts/978538.Doc

原标题：golang 系统设计配置热更新不重启服务实现
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://wiki.t55d91.asia/arts/800426.Doc

原标题：golang mysql 分表 id 路由逻辑
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.t55d91.asia/arts/919025.Doc

原标题：实践：数据库回滚点业务调试实践
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.t55d91.asia/arts/601182.Doc

原标题：Hands‑on：简易短链接服务完整开发实践
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.t55d91.asia/arts/271171.Doc

原标题：Architecture：静态配置与动态配置架构分离
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.t55d91.asia/arts/789911.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://wiki.t55d91.asia/arts/167722.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.t55d91.asia/arts/422941.Doc

原标题：golang k8s ingress 路由域名转发
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.t55d91.asia/arts/676098.Doc

原标题：golang 系统设计开源项目维护简单经验分享
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.t55d91.asia/arts/347022.Doc

原标题：golang nginx 反向代理 go 服务配置
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.t55d91.asia/arts/786658.Doc

原标题：系统字符集统一乱码修复
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://wiki.t55d91.asia/arts/461715.Doc

原标题：请求重试组件退避策略实现
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.t55d91.asia/arts/536003.Doc

三、实战开发｜Practice
原标题：多实例部署 Session 共享方案
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.t55d91.asia/arts/043708.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.t55d91.asia/arts/977884.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.t55d91.asia/arts/867007.Doc

原标题：golang 系统设计代码评审高效沟通原则思路
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.t55d91.asia/arts/072839.Doc

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.t55d91.asia/arts/239581.Doc

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.t55d91.asia/arts/823879.Doc

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.t55d91.asia/arts/605480.Doc

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.t55d91.asia/arts/404364.Doc

原标题：布隆过滤器数据高效去重实现
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.t55d91.asia/arts/088257.Doc

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://wiki.t55d91.asia/arts/550224.Doc

原标题：golang gorm ORM 数据库操作
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://wiki.t55d91.asia/arts/611049.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.t55d91.asia/arts/852579.Doc

原标题：golang 系统设计延迟队列业务实现
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://wiki.t55d91.asia/arts/279397.Doc

原标题：运维笔记：线上服务健康检查脚本编写
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.t55d91.asia/arts/382592.Doc

原标题：golang 系统设计压测工具 wrk 使用实操
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.t55d91.asia/arts/475743.Doc

原标题：golang 系统设计 websocket 协议原理梳理
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://wiki.t55d91.asia/arts/450419.Doc

原标题：service‑worker 离线缓存实践
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://wiki.t55d91.asia/arts/947698.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.t55d91.asia/arts/578127.Doc

原标题：golang 速率限制令牌桶实现
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.t55d91.asia/arts/234447.Doc

原标题：golang 系统设计 mq 故障降级业务策略
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.t55d91.asia/arts/964066.Doc

原标题：版本升级服务启动失败处理
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.t55d91.asia/arts/497691.Doc

原标题：线程池拒绝策略任务丢失防护
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.t55d91.asia/arts/319584.Doc

原标题：踩坑记录：端口被占用导致服务启动失败
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://wiki.t55d91.asia/arts/863092.Doc

原标题：golang k8s 日志收集 efk 简单架构
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.t55d91.asia/arts/270707.Doc

原标题：数值类型溢出错乱问题修复
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://wiki.t55d91.asia/arts/292749.Doc

原标题：golang 配置文件多环境加载
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.t55d91.asia/arts/904137.Doc

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.t55d91.asia/arts/193662.Doc

原标题：开源实践：开源项目如何写好PullRequest
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://wiki.t55d91.asia/arts/230586.Doc

原标题：坑点：软链接权限问题容器读取文件失败
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.t55d91.asia/arts/081335.Doc

原标题：新手教程：本地项目初始化gitignore配置
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.t55d91.asia/arts/269947.Doc

原标题：golang es 更新文档注意版本冲突
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.t55d91.asia/arts/864418.Doc

原标题：Nginx 静态代理负载均衡全套配置
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.t55d91.asia/arts/788437.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://wiki.t55d91.asia/arts/408807.Doc

原标题：golang url 参数编码处理方案
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.t55d91.asia/arts/271353.Doc

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.t55d91.asia/arts/719542.Doc

原标题：golang 系统设计回调签名校验防伪造实现
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.t55d91.asia/arts/577418.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.t55d91.asia/arts/453356.Doc

原标题：分布式 ID 生成器高并发实现
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.t55d91.asia/arts/718750.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://wiki.t55d91.asia/arts/304778.Doc

原标题：golang redis 过期 key 监听业务
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.t55d91.asia/arts/429813.Doc

四、架构设计｜Architecture
原标题：入门实践：使用Git完成第一次代码提交与推送
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.t55d91.asia/arts/078024.Doc

原标题：DevOps：GitLabCI完整流水线配置示例
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://wiki.t55d91.asia/arts/704363.Doc

原标题：数据库连接池参数调优
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.t55d91.asia/arts/273460.Doc

原标题：golang docker compose 依赖启动顺序
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.t55d91.asia/arts/003588.Doc

原标题：快速上手阅读开源项目源码的入门思路
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.t55d91.asia/arts/452412.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.t55d91.asia/arts/067695.Doc

原标题：方案设计：接口版本管理架构向前兼容策略
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.t55d91.asia/arts/159325.Doc

原标题：golang 系统设计 tcc 事务简单原理业务示例
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://wiki.t55d91.asia/arts/099864.Doc

原标题：golang es 高亮搜索结果实现方案
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://wiki.t55d91.asia/arts/874302.Doc

原标题：golang 系统设计容器镜像安全加固要点
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.t55d91.asia/arts/331463.Doc

原标题：端口占用访问失败排查方案
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.t55d91.asia/arts/852897.Doc

原标题：调优方案：静态资源缓存头Cache‑Control优化
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.t55d91.asia/arts/974071.Doc

原标题：Practice：实现文件监控自动重启开发服务工具
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.t55d91.asia/arts/783446.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.t55d91.asia/arts/627316.Doc

原标题：golang docker 容器资源限制设置
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.t55d91.asia/arts/082008.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.t55d91.asia/arts/615367.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.t55d91.asia/arts/664523.Doc

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.t55d91.asia/arts/548213.Doc

?
