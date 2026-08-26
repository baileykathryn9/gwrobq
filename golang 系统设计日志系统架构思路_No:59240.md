最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计日志系统架构思路
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.2dk0mf.asia/arts/571205.Doc

原标题：安全笔记：Git仓库密钥硬编码泄露处理方案
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.2dk0mf.asia/arts/878586.Doc

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.2dk0mf.asia/arts/185543.Doc

原标题：golang 系统设计数据库慢查询治理方案
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.2dk0mf.asia/arts/004806.Doc

原标题：rebase 操作防止代码丢失
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.2dk0mf.asia/arts/548688.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://wiki.2dk0mf.asia/arts/536520.Doc

原标题：golang jwt 过期刷新 token 实现
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.2dk0mf.asia/arts/028199.Doc

原标题：实践：多配置文件合并加载组件实现
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.2dk0mf.asia/arts/061507.Doc

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.2dk0mf.asia/arts/596684.Doc

原标题：入门实践：简单批量处理脚本编写
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.2dk0mf.asia/arts/975834.Doc

原标题：不必要字符转义关闭业务异常
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.2dk0mf.asia/arts/484679.Doc

原标题：golang 错误处理最佳实践汇总
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.2dk0mf.asia/arts/400400.Doc

原标题：部署实践：服务器SSH安全加固配置实践
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.2dk0mf.asia/arts/374397.Doc

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.2dk0mf.asia/arts/399857.Doc

原标题：golang 系统设计 mq 消息重复消费处理
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.2dk0mf.asia/arts/257951.Doc

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.2dk0mf.asia/arts/983260.Doc

原标题：复盘总结：数据库迁移升级风险评估清单
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.2dk0mf.asia/arts/038874.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.2dk0mf.asia/arts/459585.Doc

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.2dk0mf.asia/arts/403402.Doc

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.2dk0mf.asia/arts/874593.Doc

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.2dk0mf.asia/arts/086208.Doc

原标题：效率笔记：终端开发工具提升日常调试效率
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.2dk0mf.asia/arts/437435.Doc

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.2dk0mf.asia/arts/174206.Doc

原标题：跨平台换行符统一异常修复
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.2dk0mf.asia/arts/508376.Doc

原标题：CI/CD 流水线自动构建部署落地
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.2dk0mf.asia/arts/962690.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://wiki.2dk0mf.asia/arts/691970.Doc

原标题：快速入门消息通知简单实现方案
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.2dk0mf.asia/arts/852409.Doc

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.2dk0mf.asia/arts/480435.Doc

原标题：golang prometheus 指标暴露实现
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.2dk0mf.asia/arts/389981.Doc

原标题：OpenSource：开源项目许可证License选型指南
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.2dk0mf.asia/arts/235676.Doc

原标题：golang redis 五种数据结构实战
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.2dk0mf.asia/arts/648125.Doc

原标题：golang 系统设计开源项目安全漏洞处理流程
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.2dk0mf.asia/arts/866192.Doc

原标题：golang 信号量控制并发数量
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.2dk0mf.asia/arts/741457.Doc

原标题：OpenSource：如何高效阅读大型开源项目源码
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.2dk0mf.asia/arts/641496.Doc

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://wiki.2dk0mf.asia/arts/944484.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.2dk0mf.asia/arts/186604.Doc

原标题：数据库分表存储大表优化方案
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.2dk0mf.asia/arts/387306.Doc

原标题：配置与镜像分离防止信息泄露
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.2dk0mf.asia/arts/784531.Doc

原标题：golang dockerfile 多阶段构建详解
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.2dk0mf.asia/arts/353628.Doc

原标题：新手教程：如何给开源项目提交第一个PR
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://wiki.2dk0mf.asia/arts/787798.Doc


二、踩坑排错｜Troubleshooting
原标题：Spring 事务传播机制配置生效
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.2dk0mf.asia/arts/843027.Doc

原标题：golang context 上下文传参讲解
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.2dk0mf.asia/arts/049024.Doc

原标题：HTTPS 证书过期更新操作
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.2dk0mf.asia/arts/959359.Doc

原标题：golang 空接口 interface 使用技巧
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.2dk0mf.asia/arts/133257.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.2dk0mf.asia/arts/293235.Doc

原标题：golang 灰度权重流量分发简单实现
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.2dk0mf.asia/arts/427257.Doc

原标题：实战：WebSocket断线重连完整业务处理实践
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.2dk0mf.asia/arts/904234.Doc

原标题：golang etcd 租约 lease 过期机制
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.2dk0mf.asia/arts/054456.Doc

原标题：golang mysql 时间类型选型避坑
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://wiki.2dk0mf.asia/arts/544226.Doc

原标题：Nginx 请求头大小上限调整
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://wiki.2dk0mf.asia/arts/489211.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.2dk0mf.asia/arts/100275.Doc

原标题：golang 参数校验业务接口处理
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.2dk0mf.asia/arts/952813.Doc

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.2dk0mf.asia/arts/877335.Doc

原标题：golang 系统设计网关 websocket 转发配置要点
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://wiki.2dk0mf.asia/arts/813420.Doc

原标题：代码格式化工具团队统一风格
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.2dk0mf.asia/arts/611691.Doc

原标题：Practice：实现文件监控自动重启开发服务工具
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.2dk0mf.asia/arts/519443.Doc

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.2dk0mf.asia/arts/747882.Doc

原标题：nodejs 进程间通信 IPC 实操
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.2dk0mf.asia/arts/838875.Doc

原标题：golang docker compose 环境变量
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.2dk0mf.asia/arts/079435.Doc

原标题：前端防抖节流高频事件处理
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.2dk0mf.asia/arts/311820.Doc

原标题：零基础理解幂等性基础概念与场景
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.2dk0mf.asia/arts/824709.Doc

原标题：golang 系统设计技术债务识别登记治理思路
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.2dk0mf.asia/arts/772289.Doc

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://wiki.2dk0mf.asia/arts/752555.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.2dk0mf.asia/arts/851633.Doc

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.2dk0mf.asia/arts/228978.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://wiki.2dk0mf.asia/arts/574017.Doc

原标题：golang kafka 生产者参数调优
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.2dk0mf.asia/arts/177317.Doc

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.2dk0mf.asia/arts/825805.Doc

原标题：golang redis bitmap 位图统计实现
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.2dk0mf.asia/arts/366336.Doc

原标题：日志输出规范防止磁盘爆满
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.2dk0mf.asia/arts/668836.Doc

原标题：实战：基于内存实现简单消息广播组件
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.2dk0mf.asia/arts/992772.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.2dk0mf.asia/arts/643139.Doc

原标题：golang 系统设计定时任务失败重试告警实现
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.2dk0mf.asia/arts/427258.Doc

原标题：golang 系统设计内部 rpc 接口设计原则梳理
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.2dk0mf.asia/arts/853283.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://wiki.2dk0mf.asia/arts/226425.Doc

原标题：实战：Redis集群本地搭建与功能验证
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.2dk0mf.asia/arts/554713.Doc

原标题：golang minio 对象存储接口开发
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.2dk0mf.asia/arts/467414.Doc

原标题：API 接口调试与异常处理实战
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.2dk0mf.asia/arts/202449.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://wiki.2dk0mf.asia/arts/742141.Doc

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.2dk0mf.asia/arts/207897.Doc

三、实战开发｜Practice
原标题：Practice：实现请求ID透传全链路日志实践
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.2dk0mf.asia/arts/522561.Doc

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.2dk0mf.asia/arts/403148.Doc

原标题：实践：数据库备份脚本自动化编写实践
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.2dk0mf.asia/arts/203163.Doc

原标题：golang 系统信号信号量处理
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.2dk0mf.asia/arts/975488.Doc

原标题：golang 系统设计分表分页排序业务实现难点
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.2dk0mf.asia/arts/976704.Doc

原标题：架构笔记：OAuth2授权服务架构模式拆解
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.2dk0mf.asia/arts/479619.Doc

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.2dk0mf.asia/arts/197341.Doc

原标题：golang 系统设计读写分离延迟业务兼容
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.2dk0mf.asia/arts/680110.Doc

原标题：golang 系统设计分布式锁超时业务防死锁处理
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://wiki.2dk0mf.asia/arts/917041.Doc

原标题：golang 系统设计监控缺失指标补全完整流程
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.2dk0mf.asia/arts/333620.Doc

原标题：方案设计：短链接系统完整架构方案拆解
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.2dk0mf.asia/arts/888769.Doc

原标题：Security：反序列化漏洞风险识别与规避
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://wiki.2dk0mf.asia/arts/394387.Doc

原标题：API 大版本不兼容平滑迁移
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.2dk0mf.asia/arts/704559.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://wiki.2dk0mf.asia/arts/032779.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://wiki.2dk0mf.asia/arts/190867.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.2dk0mf.asia/arts/345662.Doc

原标题：方案对比：几种任务队列架构选型优缺点
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.2dk0mf.asia/arts/854302.Doc

原标题：Architecture：监控告警架构避免告警风暴设计
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.2dk0mf.asia/arts/500834.Doc

原标题：Performance：批量导入数据性能优化实践
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.2dk0mf.asia/arts/462703.Doc

原标题：golang minio 预签名 url 临时访问
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://wiki.2dk0mf.asia/arts/396914.Doc

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.2dk0mf.asia/arts/586023.Doc

原标题：golang 系统设计技术文档维护更新最佳实践
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.2dk0mf.asia/arts/695591.Doc

原标题：golang 系统设计 id 生成器选型对比
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.2dk0mf.asia/arts/264558.Doc

原标题：新手向：看懂项目README的正确阅读姿势
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.2dk0mf.asia/arts/885574.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.2dk0mf.asia/arts/680897.Doc

原标题：golang 优雅处理数据库事务
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.2dk0mf.asia/arts/776217.Doc

原标题：项目实践：消息队列消息确认机制业务实践
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://wiki.2dk0mf.asia/arts/654716.Doc

原标题：记一次升级操作系统内核引发服务不稳定
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.2dk0mf.asia/arts/840167.Doc

原标题：站内邮件消息通知功能开发
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.2dk0mf.asia/arts/860861.Doc

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.2dk0mf.asia/arts/039381.Doc

原标题：调优方案：前端静态资源打包性能体积优化
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.2dk0mf.asia/arts/573082.Doc

原标题：golang 系统设计延迟消息实现几种方案对比
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.2dk0mf.asia/arts/409773.Doc

原标题：golang redis pipeline 批量操作
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.2dk0mf.asia/arts/758041.Doc

原标题：golang context 上下文传参讲解
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.2dk0mf.asia/arts/970451.Doc

原标题：golang k8s cronjob 定时任务配置
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.2dk0mf.asia/arts/564560.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.2dk0mf.asia/arts/730745.Doc

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.2dk0mf.asia/arts/660217.Doc

原标题：项目脚手架模板生成工具
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://wiki.2dk0mf.asia/arts/555416.Doc

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.2dk0mf.asia/arts/515180.Doc

原标题：WebSocket 断线重连稳定优化
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.2dk0mf.asia/arts/092205.Doc

四、架构设计｜Architecture
原标题：设计思考：消息顺序性架构保证与业务妥协
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://wiki.2dk0mf.asia/arts/614273.Doc

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://wiki.2dk0mf.asia/arts/009673.Doc

原标题：快速入门容器基础概念，理解镜像与容器
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.2dk0mf.asia/arts/215412.Doc

原标题：方案对比：缓存更新策略Cache‑Aside读写模式
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.2dk0mf.asia/arts/209524.Doc

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.2dk0mf.asia/arts/315258.Doc

原标题：webpack chunk 分包策略详解
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://wiki.2dk0mf.asia/arts/981159.Doc

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.2dk0mf.asia/arts/581871.Doc

原标题：golang mysql 分表自增 id 方案
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.2dk0mf.asia/arts/509693.Doc

原标题：开发复盘：大数据量分页避免offset性能问题
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.2dk0mf.asia/arts/837327.Doc

原标题：golang 系统设计消息队列降级业务开关实现
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.2dk0mf.asia/arts/484565.Doc

原标题：golang docker compose 完整语法
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://wiki.2dk0mf.asia/arts/411408.Doc

原标题：golang mysql 长连接短连接对比
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.2dk0mf.asia/arts/570146.Doc

原标题：golang 单例模式实现几种方式
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.2dk0mf.asia/arts/483235.Doc

原标题：Shell 脚本自动化命令编写
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.2dk0mf.asia/arts/848540.Doc

原标题：nodejs 读取大文件 csv 处理方案
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.2dk0mf.asia/arts/624009.Doc

原标题：golang 系统设计数据库死锁分析规避
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.2dk0mf.asia/arts/287180.Doc

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.2dk0mf.asia/arts/889307.Doc

原标题：集成测试业务流程编写示例
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.2dk0mf.asia/arts/381361.Doc

?
