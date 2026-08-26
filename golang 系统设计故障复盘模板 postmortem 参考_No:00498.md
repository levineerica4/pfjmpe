最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.2dk0mf.asia/arts/229510.Doc

原标题：服务器 Swap 关闭提升响应速度
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.2dk0mf.asia/arts/073737.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.2dk0mf.asia/arts/099369.Doc

原标题：Architecture：对象存储接入业务整体架构
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.2dk0mf.asia/arts/256968.Doc

原标题：入门实践：简易进度条CLI工具实现demo
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.2dk0mf.asia/arts/332138.Doc

原标题：零基础理解模块化与组件化基础思想
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.2dk0mf.asia/arts/536525.Doc

原标题：实战项目：GitSubmodule管理多仓库实践
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.2dk0mf.asia/arts/658314.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.2dk0mf.asia/arts/128095.Doc

原标题：性能笔记：线程池参数调优任务队列策略
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://wiki.2dk0mf.asia/arts/521583.Doc

原标题：布隆过滤器误判问题修正
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.2dk0mf.asia/arts/164706.Doc

原标题：实践：灰度流量切分简易实现方案
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.2dk0mf.asia/arts/108316.Doc

原标题：CDN 缓存刷新获取最新静态资源
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.2dk0mf.asia/arts/321645.Doc

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.2dk0mf.asia/arts/816363.Doc

原标题：实战：Nginx负载均衡多种策略配置实践
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://wiki.2dk0mf.asia/arts/991671.Doc

原标题：golang 系统设计定时任务分布式锁
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.2dk0mf.asia/arts/928800.Doc

原标题：部署复盘：容器OOM问题完整排查流程
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://wiki.2dk0mf.asia/arts/336491.Doc

原标题：golang 系统信号信号量处理
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.2dk0mf.asia/arts/383685.Doc

原标题：Security：RPC调用身份认证安全加固
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.2dk0mf.asia/arts/758878.Doc

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.2dk0mf.asia/arts/339861.Doc

原标题：复盘总结：系统压测报告模板与分析思路
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.2dk0mf.asia/arts/913491.Doc

原标题：golang 系统设计一致性哈希原理讲解
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.2dk0mf.asia/arts/554792.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.2dk0mf.asia/arts/660000.Doc

原标题：安全实践：接口速率限制防止暴力破解
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.2dk0mf.asia/arts/168432.Doc

原标题：golang es bool 查询条件组合技巧
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://wiki.2dk0mf.asia/arts/851668.Doc

原标题：golang 系统设计故障演练简单落地思路方法论
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.2dk0mf.asia/arts/379513.Doc

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.2dk0mf.asia/arts/298776.Doc

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://wiki.2dk0mf.asia/arts/710765.Doc

原标题：golang k8s liveness readiness 探针
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.2dk0mf.asia/arts/521054.Doc

原标题：OOMKilled 容器被杀完整排查
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://wiki.2dk0mf.asia/arts/966218.Doc

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://wiki.2dk0mf.asia/arts/328734.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.2dk0mf.asia/arts/451886.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.2dk0mf.asia/arts/680790.Doc

原标题：从零学习简单分页逻辑实现思路
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://wiki.2dk0mf.asia/arts/052668.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.2dk0mf.asia/arts/984540.Doc

原标题：golang kafka 核心概念分区副本
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.2dk0mf.asia/arts/261209.Doc

原标题：环境变量不生效问题修复
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.2dk0mf.asia/arts/995887.Doc

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.2dk0mf.asia/arts/643022.Doc

原标题：Security：反序列化漏洞风险识别与规避
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.2dk0mf.asia/arts/773616.Doc

原标题：从零搭建简单定时任务demo
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.2dk0mf.asia/arts/128003.Doc

原标题：Nginx 丢失请求头配置修正
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.2dk0mf.asia/arts/828491.Doc


二、踩坑排错｜Troubleshooting
原标题：golang k8s 网络策略网络隔离设置
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.2dk0mf.asia/arts/592503.Doc

原标题：Performance：大事务拆分，减少锁持有时间
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.2dk0mf.asia/arts/757132.Doc

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.2dk0mf.asia/arts/553063.Doc

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.2dk0mf.asia/arts/888947.Doc

原标题：排错：前端缓存304异常更新不及时
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.2dk0mf.asia/arts/636753.Doc

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.2dk0mf.asia/arts/591738.Doc

原标题：实践：数据库慢查询分析与索引优化实战演练
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.2dk0mf.asia/arts/371378.Doc

原标题：golang ci 流水线制品仓库上传下载
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.2dk0mf.asia/arts/403422.Doc

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.2dk0mf.asia/arts/634234.Doc

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://wiki.2dk0mf.asia/arts/349278.Doc

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.2dk0mf.asia/arts/269341.Doc

原标题：时间同步修复令牌提前过期
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://wiki.2dk0mf.asia/arts/256141.Doc

原标题：Performance：缓存策略优化，降低数据库压力
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.2dk0mf.asia/arts/573379.Doc

原标题：express 中间件开发业务实践
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.2dk0mf.asia/arts/336501.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.2dk0mf.asia/arts/342825.Doc

原标题：golang 系统设计内部 rpc 接口设计原则梳理
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://wiki.2dk0mf.asia/arts/859220.Doc

原标题：消息队列生产消费模型入门
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.2dk0mf.asia/arts/153737.Doc

原标题：DevOps：多环境镜像标签版本管理规范
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.2dk0mf.asia/arts/155612.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://wiki.2dk0mf.asia/arts/843320.Doc

原标题：golang mysql 读写分离简单实现
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.2dk0mf.asia/arts/266281.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.2dk0mf.asia/arts/106649.Doc

原标题：golang 告警推送钉钉机器人实现
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.2dk0mf.asia/arts/625831.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://wiki.2dk0mf.asia/arts/740113.Doc

原标题：golang 系统设计限流算法原理代码实现
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.2dk0mf.asia/arts/937942.Doc

原标题：Architecture：静态资源分发CDN整体架构思路
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.2dk0mf.asia/arts/000731.Doc

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.2dk0mf.asia/arts/961242.Doc

原标题：golang 系统设计链路追踪架构简单讲解
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.2dk0mf.asia/arts/454705.Doc

原标题：golang 系统设计分表字段选择路由规则设计
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.2dk0mf.asia/arts/936589.Doc

原标题：项目实践：分布式会话Redis存储落地实践
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.2dk0mf.asia/arts/991911.Doc

原标题：golang 系统设计内部服务链路 trace 传递实现
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.2dk0mf.asia/arts/125433.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.2dk0mf.asia/arts/054984.Doc

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.2dk0mf.asia/arts/598739.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.2dk0mf.asia/arts/084243.Doc

原标题：Architecture：大文件上传下载系统架构设计
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.2dk0mf.asia/arts/738431.Doc

原标题：实践：静态站点自动化部署到GitHubPages
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.2dk0mf.asia/arts/673757.Doc

原标题：前后端交互跨域问题完整处理
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://wiki.2dk0mf.asia/arts/410184.Doc

原标题：优化实践：多级缓存减少下游服务调用压力
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://wiki.2dk0mf.asia/arts/719232.Doc

原标题：golang kafka 监控指标简单梳理
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.2dk0mf.asia/arts/414168.Doc

原标题：Nginx 反向代理路由配置实战
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.2dk0mf.asia/arts/072235.Doc

原标题：nodejs 流处理大文件不占内存
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.2dk0mf.asia/arts/794083.Doc

三、实战开发｜Practice
原标题：golang 系统设计短信发送限流降级
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.2dk0mf.asia/arts/292435.Doc

原标题：golang 系统设计故障演练简单思路
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.2dk0mf.asia/arts/336236.Doc

原标题：Architecture：事件溯源架构模式适用业务场景
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://wiki.2dk0mf.asia/arts/239951.Doc

原标题：实践：Git工作流主干开发团队协作实践
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://wiki.2dk0mf.asia/arts/265857.Doc

原标题：golang mysql 长连接短连接对比
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.2dk0mf.asia/arts/714761.Doc

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://wiki.2dk0mf.asia/arts/110098.Doc

原标题：性能复盘：内存泄漏定位，内存持续上涨优化
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://wiki.2dk0mf.asia/arts/650639.Doc

原标题：运维笔记：系统文件句柄数调整生产配置
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.2dk0mf.asia/arts/267807.Doc

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.2dk0mf.asia/arts/097753.Doc

原标题：安全实践：备份文件访问权限安全管控
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.2dk0mf.asia/arts/182353.Doc

原标题：golang 系统设计分库分表本地测试调试技巧
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://wiki.2dk0mf.asia/arts/452515.Doc

原标题：序列化版本不一致解析失败
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.2dk0mf.asia/arts/125899.Doc

原标题：golang prometheus histogram 指标
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.2dk0mf.asia/arts/694357.Doc

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.2dk0mf.asia/arts/198426.Doc

原标题：消息队列消费堆积扩容处理
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.2dk0mf.asia/arts/528840.Doc

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.2dk0mf.asia/arts/814284.Doc

原标题：golang docker 网络模式桥接 host
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.2dk0mf.asia/arts/629931.Doc

原标题：golang 系统设计灰度发布实现思路
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://wiki.2dk0mf.asia/arts/296140.Doc

原标题：golang 系统设计内部服务 mock 集成测试方案
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.2dk0mf.asia/arts/063735.Doc

原标题：golang csv 读写批量数据处理
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.2dk0mf.asia/arts/389146.Doc

原标题：golang cpu pprof 性能分析实操
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://wiki.2dk0mf.asia/arts/996217.Doc

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.2dk0mf.asia/arts/666581.Doc

原标题：golang 系统设计对象池复用减少内存分配
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://wiki.2dk0mf.asia/arts/718896.Doc

原标题：golang mysql 连接泄漏检测方法
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://wiki.2dk0mf.asia/arts/599509.Doc

原标题：多套环境灵活切换配置方案
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.2dk0mf.asia/arts/899248.Doc

原标题：实战：单元测试+集成测试完整项目落地实践
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.2dk0mf.asia/arts/009200.Doc

原标题：golang 文件上传下载接口开发
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.2dk0mf.asia/arts/952225.Doc

原标题：golang 系统设计指标聚合计算存储选型对比
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.2dk0mf.asia/arts/672383.Doc

原标题：golang 系统设计并发控制协程池任务池实现
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://wiki.2dk0mf.asia/arts/321826.Doc

原标题：程序预加载加快服务启动速度
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.2dk0mf.asia/arts/247538.Doc

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://wiki.2dk0mf.asia/arts/040943.Doc

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.2dk0mf.asia/arts/863597.Doc

原标题：Architecture：大文件上传下载系统架构设计
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://wiki.2dk0mf.asia/arts/825369.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.2dk0mf.asia/arts/499702.Doc

原标题：K8s 镜像拉取网络故障修复
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://wiki.2dk0mf.asia/arts/770735.Doc

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://wiki.2dk0mf.asia/arts/677083.Doc

原标题：入门实践：简单批量处理脚本编写
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://wiki.2dk0mf.asia/arts/197830.Doc

原标题：golang prometheus metrics 埋点开发
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.2dk0mf.asia/arts/885455.Doc

原标题：集成测试业务流程编写示例
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://wiki.2dk0mf.asia/arts/423686.Doc

原标题：前端 pdf 预览渲染方案对比
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://wiki.2dk0mf.asia/arts/748876.Doc

四、架构设计｜Architecture
原标题：golang 系统设计无锁编程思路简单示例
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.2dk0mf.asia/arts/647105.Doc

原标题：从零编写简易 CLI 命令行工具
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.2dk0mf.asia/arts/225438.Doc

原标题：开源项目构建失败排查步骤
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.2dk0mf.asia/arts/250429.Doc

原标题：golang consul 服务发现简单示例
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.2dk0mf.asia/arts/110040.Doc

原标题：设计思考：业务系统如何设计优雅失败架构
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.2dk0mf.asia/arts/450897.Doc

原标题：golang 系统设计数据库迁移工具 go‑migrate 实操
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.2dk0mf.asia/arts/293229.Doc

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://wiki.2dk0mf.asia/arts/160012.Doc

原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.2dk0mf.asia/arts/970374.Doc

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.2dk0mf.asia/arts/833933.Doc

原标题：golang 系统设计 rest 错误返回格式统一规范
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.2dk0mf.asia/arts/260399.Doc

原标题：异步编程 Promise 执行流程解析
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.2dk0mf.asia/arts/281189.Doc

原标题：运维笔记：备份策略数据库定时备份脚本
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://wiki.2dk0mf.asia/arts/230816.Doc

原标题：css 动画性能优化 GPU 加速
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.2dk0mf.asia/arts/662143.Doc

原标题：DevOps：容器健康探针livenessreadiness配置
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://wiki.2dk0mf.asia/arts/678065.Doc

原标题：golang 系统设计大流量削峰处理方案
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.2dk0mf.asia/arts/135566.Doc

原标题：文件锁正确使用避免死锁
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.2dk0mf.asia/arts/344734.Doc

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.2dk0mf.asia/arts/895144.Doc

原标题：Debug：并发场景下数据覆盖丢失问题定位
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.2dk0mf.asia/arts/233910.Doc

?
