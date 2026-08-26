最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计开源项目 release 发布流程
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://wiki.egapnd.asia/arts/879529.Doc

原标题：TCP 长连接参数优化 TIME_WAIT
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.egapnd.asia/arts/036001.Doc

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.egapnd.asia/arts/153618.Doc

原标题：golang 系统设计接口返回格式统一规范
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://wiki.egapnd.asia/arts/385256.Doc

原标题：时间精度统一业务判断修复
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.egapnd.asia/arts/499862.Doc

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.egapnd.asia/arts/830080.Doc

原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://wiki.egapnd.asia/arts/407667.Doc

原标题：golang 系统设计敏感数据加密存储方案
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.egapnd.asia/arts/676379.Doc

原标题：Practice：实现IP黑名单拦截中间件实践
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.egapnd.asia/arts/840503.Doc

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.egapnd.asia/arts/599696.Doc

原标题：限流窗口绕过漏洞修复方案
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.egapnd.asia/arts/596307.Doc

原标题：golang 系统设计秒杀防超卖方案
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.egapnd.asia/arts/473696.Doc

原标题：golang 系统设计内部 rpc 接口设计原则梳理
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.egapnd.asia/arts/139090.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.egapnd.asia/arts/880479.Doc

原标题：golang 系统设计 mq 消息积压解决方案
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.egapnd.asia/arts/596571.Doc

原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.egapnd.asia/arts/707922.Doc

原标题：网关集成鉴权限流日志一体化
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.egapnd.asia/arts/171608.Doc

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://wiki.egapnd.asia/arts/347620.Doc

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://wiki.egapnd.asia/arts/322801.Doc

原标题：golang 优雅处理 http 超时设置
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.egapnd.asia/arts/654775.Doc

原标题：Practice：实现数据库事务消息最终一致性demo
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.egapnd.asia/arts/483009.Doc

原标题：静态网页 HTML CSS 快速入门实战
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.egapnd.asia/arts/522542.Doc

原标题：golang redis 地理位置 geo 使用
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.egapnd.asia/arts/748028.Doc

原标题：golang 系统设计 csrf 接口防护实现
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://wiki.egapnd.asia/arts/195585.Doc

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.egapnd.asia/arts/970189.Doc

原标题：golang 系统设计索引设计通用方法论汇总
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://wiki.egapnd.asia/arts/567016.Doc

原标题：golang redis hyperloglog 基数统计
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.egapnd.asia/arts/413385.Doc

原标题：nodejs 事件循环机制完整讲解
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://wiki.egapnd.asia/arts/736149.Doc

原标题：golang 简易埋点日志上报实现
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://wiki.egapnd.asia/arts/203225.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.egapnd.asia/arts/204697.Doc

原标题：磁盘占满服务不可用清理方案
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.egapnd.asia/arts/426223.Doc

原标题：死信队列处理消息阻塞业务
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.egapnd.asia/arts/815375.Doc

原标题：golang docker volume 数据持久化
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.egapnd.asia/arts/074253.Doc

原标题：nodejs 脚手架工具开发完整教程
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.egapnd.asia/arts/469005.Doc

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.egapnd.asia/arts/333850.Doc

原标题：golang kafka offset 提交策略
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.egapnd.asia/arts/311448.Doc

原标题：golang 系统设计内网外网服务隔离方案
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.egapnd.asia/arts/613181.Doc

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.egapnd.asia/arts/597103.Doc

原标题：golang 系统设计网关缓存静态资源实现思路
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://wiki.egapnd.asia/arts/163983.Doc

原标题：容器资源限制防止宿主机过载
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.egapnd.asia/arts/639904.Doc


二、踩坑排错｜Troubleshooting
原标题：架构笔记：海量消息堆积架构处理能力设计
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.egapnd.asia/arts/788860.Doc

原标题：性能笔记：线程池参数调优任务队列策略
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://wiki.egapnd.asia/arts/961725.Doc

原标题：golang es 分页深分页性能优化
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.egapnd.asia/arts/355733.Doc

原标题：开发生产环境资源路径统一
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.egapnd.asia/arts/740340.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.egapnd.asia/arts/016248.Doc

原标题：golang ip 限流黑名单实现方案
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://wiki.egapnd.asia/arts/429272.Doc

原标题：golang 日志脱敏敏感字段过滤
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.egapnd.asia/arts/663382.Doc

原标题：线上接口超时故障排查思路
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.egapnd.asia/arts/526804.Doc

原标题：golang redis pipeline 批量操作
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.egapnd.asia/arts/156800.Doc

原标题：开发记录：分布式ID生成器实现与压力测试
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://wiki.egapnd.asia/arts/450950.Doc

原标题：golang 数据库批量更新性能优化
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.egapnd.asia/arts/415895.Doc

原标题：golang 系统设计配置敏感信息加密存储
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.egapnd.asia/arts/556054.Doc

原标题：浏览器本地存储安全使用技巧
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://wiki.egapnd.asia/arts/473649.Doc

原标题：golang k8s rbac 权限控制配置示例
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.egapnd.asia/arts/960354.Doc

原标题：golang rate‑limiter 限流组件
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.egapnd.asia/arts/204029.Doc

原标题：Debug：Websocket频繁断开重连根因分析
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.egapnd.asia/arts/388131.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.egapnd.asia/arts/722869.Doc

原标题：Security：密码存储哈希加盐最佳实践
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.egapnd.asia/arts/962350.Doc

原标题：golang 系统设计分布式锁选型对比
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.egapnd.asia/arts/785309.Doc

原标题：Hands‑on：简易网关路由转发组件开发
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.egapnd.asia/arts/867947.Doc

原标题：Git 混乱提交历史清理方法
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://wiki.egapnd.asia/arts/927762.Doc

原标题：nodejs 跨域中间件配置细节
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.egapnd.asia/arts/606624.Doc

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.egapnd.asia/arts/605819.Doc

原标题：接口幂等性防重复请求实现
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.egapnd.asia/arts/742819.Doc

原标题：golang redis bitmap 位图统计实现
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.egapnd.asia/arts/153817.Doc

原标题：开发复盘：数据库批量更新优化性能实践
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.egapnd.asia/arts/923707.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.egapnd.asia/arts/652544.Doc

原标题：golang es bool 查询条件组合技巧
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.egapnd.asia/arts/978373.Doc

原标题：golang cpu pprof 性能分析实操
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.egapnd.asia/arts/992927.Doc

原标题：Hands‑on：简易请求转发代理中间件实现
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.egapnd.asia/arts/845117.Doc

原标题：Security：服务器最小权限账号运维实践
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.egapnd.asia/arts/749555.Doc

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.egapnd.asia/arts/834695.Doc

原标题：golang 系统设计数据脱敏架构实现
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://wiki.egapnd.asia/arts/453816.Doc

原标题：多环境配置中心灵活切换方案
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://wiki.egapnd.asia/arts/712929.Doc

原标题：设计思考：业务系统中什么时候不要用微服务
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://wiki.egapnd.asia/arts/035876.Doc

原标题：golang 日志与链路 ID 关联打印
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.egapnd.asia/arts/913651.Doc

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.egapnd.asia/arts/484793.Doc

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.egapnd.asia/arts/974396.Doc

原标题：语义化版本依赖管理防错乱
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.egapnd.asia/arts/665113.Doc

原标题：任务执行锁防止并发重复调度
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.egapnd.asia/arts/154023.Doc

三、实战开发｜Practice
原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.egapnd.asia/arts/952142.Doc

原标题：定时任务周期调度 demo 开发
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.egapnd.asia/arts/454257.Doc

原标题：golang 系统设计字符串拼接性能优化技巧
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.egapnd.asia/arts/644724.Doc

原标题：Hands‑on：简易短链接服务完整开发实践
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.egapnd.asia/arts/122468.Doc

原标题：golang 系统设计联合索引设计避坑要点
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://wiki.egapnd.asia/arts/238175.Doc

原标题：入门实践：简易进度条CLI工具实现demo
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.egapnd.asia/arts/201606.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.egapnd.asia/arts/072359.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.egapnd.asia/arts/636695.Doc

原标题：项目构建脚本编译打包解析
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.egapnd.asia/arts/463642.Doc

原标题：极简方式搭建个人技术文档站点
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://wiki.egapnd.asia/arts/908905.Doc

原标题：golang 系统设计消息队列解耦削峰
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.egapnd.asia/arts/648196.Doc

原标题：golang prometheus counter gauge 使用
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.egapnd.asia/arts/311401.Doc

原标题：golang 系统设计 changelog 变更日志维护
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.egapnd.asia/arts/898520.Doc

原标题：WSL 内存上限限制防止资源耗尽
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.egapnd.asia/arts/860135.Doc

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.egapnd.asia/arts/092024.Doc

原标题：运维笔记：系统内核参数调优生产服务器
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.egapnd.asia/arts/304554.Doc

原标题：Performance：数据库分表解决单表过大性能衰减
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.egapnd.asia/arts/697386.Doc

原标题：预编译 SQL 防注入实现
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.egapnd.asia/arts/315098.Doc

原标题：golang rsa 非对称加密签名验签
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.egapnd.asia/arts/722204.Doc

原标题：安全实践：生产环境禁止开启debug调试模式
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.egapnd.asia/arts/556205.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://wiki.egapnd.asia/arts/901497.Doc

原标题：golang 系统设计大文件上传架构
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.egapnd.asia/arts/658944.Doc

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.egapnd.asia/arts/244464.Doc

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.egapnd.asia/arts/815215.Doc

原标题：golang 系统设计开源项目协作流程梳理
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://wiki.egapnd.asia/arts/394352.Doc

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.egapnd.asia/arts/529943.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.egapnd.asia/arts/004079.Doc

原标题：设计思考：分布式会话架构选型对比
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://wiki.egapnd.asia/arts/785214.Doc

原标题：后端分页查询逻辑代码实现
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.egapnd.asia/arts/883347.Doc

原标题：Practice：实现跨机器文件同步脚本实践
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://wiki.egapnd.asia/arts/556422.Doc

原标题：设计思考：分布式锁选型、风险、业务约束
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.egapnd.asia/arts/388011.Doc

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.egapnd.asia/arts/088962.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.egapnd.asia/arts/191071.Doc

原标题：golang 日志与链路 ID 关联打印
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.egapnd.asia/arts/476376.Doc

原标题：golang 系统设计消息重试次数间隔策略设置
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.egapnd.asia/arts/291734.Doc

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.egapnd.asia/arts/053985.Doc

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://wiki.egapnd.asia/arts/937716.Doc

原标题：手写简易 RPC 服务通信原型
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.egapnd.asia/arts/860599.Doc

原标题：ORM 框架数据库增删改查实操
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.egapnd.asia/arts/563824.Doc

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.egapnd.asia/arts/126697.Doc

四、架构设计｜Architecture
原标题：golang 项目 docker compose 本地调试
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://wiki.egapnd.asia/arts/750733.Doc

原标题：布隆过滤器误判问题修正
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.egapnd.asia/arts/200841.Doc

原标题：项目目录结构规范化最佳实践
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.egapnd.asia/arts/085433.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.egapnd.asia/arts/296180.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.egapnd.asia/arts/601392.Doc

原标题：golang 系统设计分布式锁超时业务防死锁处理
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://wiki.egapnd.asia/arts/309832.Doc

原标题：从零搭建简单Mock接口服务
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.egapnd.asia/arts/129401.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.egapnd.asia/arts/624041.Doc

原标题：从零搭建简单定时任务demo
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.egapnd.asia/arts/326808.Doc

原标题：golang 系统设计单元测试编写原则最佳实践
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.egapnd.asia/arts/095001.Doc

原标题：入门实践：实现简单文件读写功能
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://wiki.egapnd.asia/arts/884370.Doc

原标题：零基础理解缓存基础原理与简单使用
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.egapnd.asia/arts/185741.Doc

原标题：golang k8s pod 优雅关闭流程讲解
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.egapnd.asia/arts/472836.Doc

原标题：golang csv 读写批量数据处理
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://wiki.egapnd.asia/arts/111333.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.egapnd.asia/arts/260007.Doc

原标题：golang docker compose 部署 minio
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.egapnd.asia/arts/782367.Doc

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.egapnd.asia/arts/288320.Doc

原标题：坑点：软链接权限问题容器读取文件失败
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.egapnd.asia/arts/193550.Doc

?
