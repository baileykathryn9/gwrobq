最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Hands‑on：简易跨进程通信demo开发实践
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.dyjdtcd.asia/blog/0835627.sHtMl

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://book.dyjdtcd.asia/blog/1028327.sHtMl

原标题：运维笔记：系统内核参数调优生产服务器
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://book.dyjdtcd.asia/blog/7509284.sHtMl

原标题：业务幂等键设计防重复逻辑
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://book.dyjdtcd.asia/blog/8976328.sHtMl

原标题：golang mongodb 索引优化查询速度
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://book.dyjdtcd.asia/blog/9791793.sHtMl

原标题：golang lru 缓存淘汰算法编写
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://book.dyjdtcd.asia/blog/2028809.sHtMl

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://book.dyjdtcd.asia/blog/1083065.sHtMl

原标题：golang 表单文件大小限制配置
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.dyjdtcd.asia/blog/6120925.sHtMl

原标题：Security：接口鉴权越权漏洞检测与修复
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.dyjdtcd.asia/blog/0736169.sHtMl

原标题：golang ci 流水线漏洞扫描依赖检查
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.dyjdtcd.asia/blog/0232923.sHtMl

原标题：golang 系统设计技术方案评审关注点清单参考
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://book.dyjdtcd.asia/blog/3194253.sHtMl

原标题：golang 系统设计 saga 事务补偿模式实现思路
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://book.dyjdtcd.asia/blog/9466498.sHtMl

原标题：布隆过滤器数据高效去重实现
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://book.dyjdtcd.asia/blog/0456953.sHtMl

原标题：新手向：开源项目依赖安装失败排查
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://book.dyjdtcd.asia/blog/7409228.sHtMl

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.dyjdtcd.asia/blog/0967914.sHtMl

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://book.dyjdtcd.asia/blog/9700799.sHtMl

原标题：golang docker compose 完整语法
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://book.dyjdtcd.asia/blog/4556910.sHtMl

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://book.dyjdtcd.asia/blog/9704833.sHtMl

原标题：零基础理解数据库事务基础ACID概念
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.dyjdtcd.asia/blog/7510229.sHtMl

原标题：开发记录：批量接口请求并发控制实践
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://book.dyjdtcd.asia/blog/3256686.sHtMl

原标题：从零学习简单分布式ID生成思路
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://book.dyjdtcd.asia/blog/9837359.sHtMl

原标题：服务健康检查监控接口开发
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://book.dyjdtcd.asia/blog/7095080.sHtMl

原标题：实战：Nginx负载均衡多种策略配置实践
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://book.dyjdtcd.asia/blog/1497066.sHtMl

原标题：开源实践：开源项目本地调试构建排坑经验
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://book.dyjdtcd.asia/blog/4768687.sHtMl

原标题：golang redis 连接池参数最佳值
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://book.dyjdtcd.asia/blog/0166210.sHtMl

原标题：golang redis 集群 hash 槽讲解
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.dyjdtcd.asia/blog/3200869.sHtMl

原标题：golang lru 缓存淘汰算法编写
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://book.dyjdtcd.asia/blog/7287534.sHtMl

原标题：golang docker 镜像安全扫描漏洞
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://book.dyjdtcd.asia/blog/9393552.sHtMl

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://book.dyjdtcd.asia/blog/2196656.sHtMl

原标题：golang 系统设计内网外网服务隔离方案
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.dyjdtcd.asia/blog/6386973.sHtMl

原标题：架构笔记：多数据源架构设计事务处理难点
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://book.dyjdtcd.asia/blog/1653500.sHtMl

原标题：golang 系统设计开源项目依赖版本升级维护
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://book.dyjdtcd.asia/blog/5062197.sHtMl

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://book.dyjdtcd.asia/blog/9201912.sHtMl

原标题：Architecture：链路追踪架构核心组件与埋点
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.dyjdtcd.asia/blog/7597797.sHtMl

原标题：安全实践：接口速率限制防止暴力破解
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://book.dyjdtcd.asia/blog/3135832.sHtMl

原标题：golang 大文件读取内存优化
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://book.dyjdtcd.asia/blog/7427240.sHtMl

原标题：Practice：实现跨机器文件同步脚本实践
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.dyjdtcd.asia/blog/4424487.sHtMl

原标题：golang md5 sha 加密工具实现
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://book.dyjdtcd.asia/blog/9956638.sHtMl

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://book.dyjdtcd.asia/blog/8352160.sHtMl

原标题：踩坑：大事务引发数据库连接池耗尽
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://book.dyjdtcd.asia/blog/5020971.sHtMl


二、踩坑排错｜Troubleshooting
原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.dyjdtcd.asia/blog/9344045.sHtMl

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.dyjdtcd.asia/blog/0883028.sHtMl

原标题：前端下载导出文件功能实现
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://book.dyjdtcd.asia/blog/3824944.sHtMl

原标题：轻量 API 后端接口服务快速开发
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://book.dyjdtcd.asia/blog/6407784.sHtMl

原标题：无用对象回收抑制内存上涨
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://book.dyjdtcd.asia/blog/9491737.sHtMl

原标题：设计思考：分布式锁选型、风险、业务约束
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://book.dyjdtcd.asia/blog/2152395.sHtMl

原标题：实践：前后端时间格式统一规范落地实践
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.dyjdtcd.asia/blog/0959677.sHtMl

原标题：Hands‑on：实现WebSocket聊天室完整前后端demo
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://book.dyjdtcd.asia/blog/7099358.sHtMl

原标题：从零学习基础的接口请求与参数处理
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://book.dyjdtcd.asia/blog/8257093.sHtMl

原标题：前端权限路由动态生成实现
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://book.dyjdtcd.asia/blog/0899543.sHtMl

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://book.dyjdtcd.asia/blog/1799193.sHtMl

原标题：避坑：批量操作未分批次，一次性内存打爆
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://book.dyjdtcd.asia/blog/5086537.sHtMl

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://book.dyjdtcd.asia/blog/8857674.sHtMl

原标题：golang kafka 核心概念分区副本
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://book.dyjdtcd.asia/blog/3819467.sHtMl

原标题：前端骨架屏提升页面体验
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://book.dyjdtcd.asia/blog/1504613.sHtMl

原标题：golang mongodb 事务多文档使用
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://book.dyjdtcd.asia/blog/0768506.sHtMl

原标题：golang 系统设计单元测试编写原则最佳实践
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://book.dyjdtcd.asia/blog/1603816.sHtMl

原标题：golang 系统设计消息重试次数间隔策略设置
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://book.dyjdtcd.asia/blog/2107187.sHtMl

原标题：调优方案：静态资源缓存头Cache‑Control优化
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://book.dyjdtcd.asia/blog/6465343.sHtMl

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://book.dyjdtcd.asia/blog/9709214.sHtMl

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://book.dyjdtcd.asia/blog/3928951.sHtMl

原标题：Redis 分布式锁高并发安全实现
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://book.dyjdtcd.asia/blog/6036054.sHtMl

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://book.dyjdtcd.asia/blog/4842570.sHtMl

原标题：Git 标签版本标记发布管理
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://book.dyjdtcd.asia/blog/5355836.sHtMl

原标题：golang k8s 滚动更新回滚策略
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://book.dyjdtcd.asia/blog/5983163.sHtMl

原标题：版本升级服务启动失败处理
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://book.dyjdtcd.asia/blog/4912363.sHtMl

原标题：记一次本地运行正常，线上环境报错诡异问题
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://book.dyjdtcd.asia/blog/6029311.sHtMl

原标题：golang 单元测试 table‑driven
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://book.dyjdtcd.asia/blog/7077895.sHtMl

原标题：golang 系统设计缓存与数据库一致性权衡
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://book.dyjdtcd.asia/blog/1929217.sHtMl

原标题：golang kafka 批量发送消费优化
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.dyjdtcd.asia/blog/3068176.sHtMl

原标题：golang k8s service 服务暴露几种类型
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://book.dyjdtcd.asia/blog/5230497.sHtMl

原标题：实战项目：容器健康探针配置完整实践示例
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://book.dyjdtcd.asia/blog/4047799.sHtMl

原标题：从零学习简单分布式ID生成思路
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://book.dyjdtcd.asia/blog/5431327.sHtMl

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://book.dyjdtcd.asia/blog/1938095.sHtMl

原标题：Practice：实现熔断降级组件简单原型代码
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://book.dyjdtcd.asia/blog/7947356.sHtMl

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://book.dyjdtcd.asia/blog/7506541.sHtMl

原标题：golang redis 锁超时业务处理
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://book.dyjdtcd.asia/blog/3729506.sHtMl

原标题：部署复盘：配置热更新不用重启服务方案
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://book.dyjdtcd.asia/blog/5692933.sHtMl

原标题：程序预加载加快服务启动速度
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.dyjdtcd.asia/blog/5936132.sHtMl

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://book.dyjdtcd.asia/blog/5836322.sHtMl

三、实战开发｜Practice
原标题：代码格式化工具团队统一风格
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.dyjdtcd.asia/blog/7558559.sHtMl

原标题：多版本开发环境共存配置
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://book.dyjdtcd.asia/blog/0311230.sHtMl

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.dyjdtcd.asia/blog/2125627.sHtMl

原标题：AI‑Dev：利用AI快速阅读陌生开源项目源码
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://book.dyjdtcd.asia/blog/0836169.sHtMl

原标题：golang kafka 批量发送消费优化
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://book.dyjdtcd.asia/blog/0804353.sHtMl

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://book.dyjdtcd.asia/blog/2167015.sHtMl

原标题：HTTPS 证书过期更新操作
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://book.dyjdtcd.asia/blog/2337297.sHtMl

原标题：WebSocket 聊天室实时通讯开发
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://book.dyjdtcd.asia/blog/1224116.sHtMl

原标题：实战：容器内执行调试排错完整实操流程
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://book.dyjdtcd.asia/blog/7475957.sHtMl

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://book.dyjdtcd.asia/blog/0870436.sHtMl

原标题：程序信号中断退出处理逻辑
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://book.dyjdtcd.asia/blog/5481310.sHtMl

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://book.dyjdtcd.asia/blog/7660266.sHtMl

原标题：跨平台换行符统一异常修复
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://book.dyjdtcd.asia/blog/2122106.sHtMl

原标题：Architecture：文件处理服务架构大文件内存规避
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.dyjdtcd.asia/blog/4872867.sHtMl

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://book.dyjdtcd.asia/blog/3403755.sHtMl

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://book.dyjdtcd.asia/blog/7834936.sHtMl

原标题：golang 熔断降级简易组件开发
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://book.dyjdtcd.asia/blog/0570906.sHtMl

原标题：Practice：实现数据库事务消息最终一致性demo
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://book.dyjdtcd.asia/blog/4914652.sHtMl

原标题：新手教程：本地环境变量配置全流程
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://book.dyjdtcd.asia/blog/5047247.sHtMl

原标题：golang mongodb 聚合管道实操案例
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://book.dyjdtcd.asia/blog/9728979.sHtMl

原标题：数据库主从延迟业务兼容处理
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://book.dyjdtcd.asia/blog/0527609.sHtMl

原标题：golang 数据库连接泄露排查
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://book.dyjdtcd.asia/blog/4316615.sHtMl

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://book.dyjdtcd.asia/blog/7716466.sHtMl

原标题：前端打包分包加载提速方案
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.dyjdtcd.asia/blog/2923909.sHtMl

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.dyjdtcd.asia/blog/2388273.sHtMl

原标题：Security：RPC调用身份认证安全加固
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.dyjdtcd.asia/blog/5015384.sHtMl

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://book.dyjdtcd.asia/blog/4810270.sHtMl

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://book.dyjdtcd.asia/blog/0766562.sHtMl

原标题：golang 系统设计海量数据分页查询
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://book.dyjdtcd.asia/blog/2052407.sHtMl

原标题：golang 优雅处理系统信号 SIGINT
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://book.dyjdtcd.asia/blog/0152125.sHtMl

原标题：golang 消息死信处理业务逻辑
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://book.dyjdtcd.asia/blog/8278544.sHtMl

原标题：golang 系统设计容器 OOM 故障完整排查
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.dyjdtcd.asia/blog/4476445.sHtMl

原标题：golang etcd 分布式锁实现原理
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://book.dyjdtcd.asia/blog/2915421.sHtMl

原标题：golang cron 定时任务防并发执行
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://book.dyjdtcd.asia/blog/2531788.sHtMl

原标题：golang redis 分布式计数器开发
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://book.dyjdtcd.asia/blog/7922062.sHtMl

原标题：Nginx 静态代理负载均衡全套配置
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.dyjdtcd.asia/blog/4144310.sHtMl

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://book.dyjdtcd.asia/blog/3757446.sHtMl

原标题：Practice：实现多数据源动态切换组件实践
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://book.dyjdtcd.asia/blog/3290677.sHtMl

原标题：golang 系统设计数据库慢查询治理方案
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.dyjdtcd.asia/blog/4571608.sHtMl

原标题：golang etcd 配置中心简单使用
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://book.dyjdtcd.asia/blog/2820539.sHtMl

四、架构设计｜Architecture
原标题：新手指南：如何读懂开源项目报错日志
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://book.dyjdtcd.asia/blog/8374681.sHtMl

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://book.dyjdtcd.asia/blog/2892033.sHtMl

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://book.dyjdtcd.asia/blog/7806123.sHtMl

原标题：golang 系统设计技术文档维护更新最佳实践
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://book.dyjdtcd.asia/blog/3661992.sHtMl

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://book.dyjdtcd.asia/blog/6247351.sHtMl

原标题：golang 系统设计 README 开源文档模板
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://book.dyjdtcd.asia/blog/5736594.sHtMl

原标题：nodejs 内存溢出问题排查修复
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.dyjdtcd.asia/blog/8689252.sHtMl

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://book.dyjdtcd.asia/blog/5354331.sHtMl

原标题：新手向：配置项目eslint/prettier代码格式化
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.dyjdtcd.asia/blog/0991098.sHtMl

原标题：从零搭建简单CLI命令行工具
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.dyjdtcd.asia/blog/2685383.sHtMl

原标题：golang 系统设计配置热更新不重启服务实现
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://book.dyjdtcd.asia/blog/8930295.sHtMl

原标题：大文件导出内存溢出防护
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://book.dyjdtcd.asia/blog/1648685.sHtMl

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://book.dyjdtcd.asia/blog/8461341.sHtMl

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://book.dyjdtcd.asia/blog/9366909.sHtMl

原标题：golang 系统设计技术方案评审关注点清单参考
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.dyjdtcd.asia/blog/4481799.sHtMl

原标题：golang 系统设计最小权限原则落地实践
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://book.dyjdtcd.asia/blog/3721538.sHtMl

原标题：方案对比：缓存更新策略Cache‑Aside读写模式
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://book.dyjdtcd.asia/blog/8476285.sHtMl

原标题：内存溢出问题现象识别排查
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://book.dyjdtcd.asia/blog/9367509.sHtMl

?
