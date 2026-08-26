最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计技术方案评审关注点清单参考
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://book.i03xcj.asia/blog/690304.Doc

原标题：golang 系统设计内网外网服务隔离方案
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://book.i03xcj.asia/blog/067381.Doc

原标题：nodejs 集群模式多核利用实现
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.i03xcj.asia/blog/351979.Doc

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://book.i03xcj.asia/blog/287119.Doc

原标题：本地简易配置中心动态管理
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://book.i03xcj.asia/blog/134776.Doc

原标题：golang 系统设计配置多环境隔离方案落地
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://book.i03xcj.asia/blog/546947.Doc

原标题：本地运行正常线上报错排查
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://book.i03xcj.asia/blog/344106.Doc

原标题：实战：WebSocket断线重连完整业务处理实践
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://book.i03xcj.asia/blog/449903.Doc

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://book.i03xcj.asia/blog/516640.Doc

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://book.i03xcj.asia/blog/265308.Doc

原标题：nodejs 项目 pm2 部署运维指南
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://book.i03xcj.asia/blog/914791.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.i03xcj.asia/blog/267582.Doc

原标题：Docker 容器时区错误修复方案
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.i03xcj.asia/blog/948955.Doc

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://book.i03xcj.asia/blog/390409.Doc

原标题：Architecture：监控告警架构避免告警风暴设计
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://book.i03xcj.asia/blog/261969.Doc

原标题：Git 误提交撤销回退实操教程
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://book.i03xcj.asia/blog/905310.Doc

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://book.i03xcj.asia/blog/342429.Doc

原标题：实战：对象存储断点续传下载实践
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://book.i03xcj.asia/blog/963901.Doc

原标题：golang 系统设计内部服务链路 trace 传递实现
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://book.i03xcj.asia/blog/777991.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://book.i03xcj.asia/blog/075162.Doc

原标题：golang 分页查询封装通用工具
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://book.i03xcj.asia/blog/847966.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://book.i03xcj.asia/blog/299569.Doc

原标题：golang es 分词器选型业务适配
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://book.i03xcj.asia/blog/426029.Doc

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.i03xcj.asia/blog/278788.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.i03xcj.asia/blog/930682.Doc

原标题：SSH 密钥配置 GitHub 免密登录
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.i03xcj.asia/blog/276948.Doc

原标题：RPC 报文大小上限调优大请求
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://book.i03xcj.asia/blog/341923.Doc

原标题：部署实践：DockerCompose管理多服务环境
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.i03xcj.asia/blog/598428.Doc

原标题：golang 优雅处理系统信号 SIGINT
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://book.i03xcj.asia/blog/960357.Doc

原标题：游标分页大数据查询性能提升
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://book.i03xcj.asia/blog/125387.Doc

原标题：设计思考：容器化业务应用架构改造要点
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://book.i03xcj.asia/blog/458899.Doc

原标题：golang prometheus counter gauge 使用
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.i03xcj.asia/blog/303592.Doc

原标题：架构复盘：热点数据防护架构防止节点过载
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://book.i03xcj.asia/blog/041951.Doc

原标题：golang 优雅处理系统信号 SIGINT
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://book.i03xcj.asia/blog/900969.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://book.i03xcj.asia/blog/607837.Doc

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://book.i03xcj.asia/blog/258165.Doc

原标题：golang 文件上传下载接口开发
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://book.i03xcj.asia/blog/694314.Doc

原标题：golang 系统设计创建更新时间自动维护方案
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://book.i03xcj.asia/blog/920726.Doc

原标题：golang mysql 存储过程简单使用
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.i03xcj.asia/blog/290763.Doc

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://book.i03xcj.asia/blog/619119.Doc


二、踩坑排错｜Troubleshooting
原标题：CORS 跨域问题多种解决方案
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://book.i03xcj.asia/blog/349810.Doc

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.i03xcj.asia/blog/858694.Doc

原标题：Performance：数据库join优化，大表join规避
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://book.i03xcj.asia/blog/993225.Doc

原标题：golang 系统设计链路数据存储选型对比讲解
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://book.i03xcj.asia/blog/931522.Doc

原标题：golang 系统设计数据脱敏架构实现
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://book.i03xcj.asia/blog/118095.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://book.i03xcj.asia/blog/125325.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://book.i03xcj.asia/blog/339165.Doc

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://book.i03xcj.asia/blog/858405.Doc

原标题：游标分页大数据查询性能提升
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.i03xcj.asia/blog/766276.Doc

原标题：Security：RPC调用身份认证安全加固
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://book.i03xcj.asia/blog/485697.Doc

原标题：golang mysql 存储过程简单使用
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://book.i03xcj.asia/blog/275494.Doc

原标题：运维笔记：CI流水线缓存策略加速构建速度
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://book.i03xcj.asia/blog/300492.Doc

原标题：golang 限流熔断降级完整示例
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://book.i03xcj.asia/blog/900246.Doc

原标题：设计思考：业务系统如何设计优雅失败架构
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://book.i03xcj.asia/blog/965216.Doc

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.i03xcj.asia/blog/932237.Doc

原标题：OAuth2 第三方登录服务搭建
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://book.i03xcj.asia/blog/781102.Doc

原标题：golang 系统设计短链接服务实现思路
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://book.i03xcj.asia/blog/201138.Doc

原标题：golang 系统设计限流算法原理代码实现
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://book.i03xcj.asia/blog/203122.Doc

原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://book.i03xcj.asia/blog/041926.Doc

原标题：多线程线程安全脏数据规避
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://book.i03xcj.asia/blog/120020.Doc

原标题：配置外部化线上部署防错误
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://book.i03xcj.asia/blog/511653.Doc

原标题：从零学习简单分页逻辑实现思路
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://book.i03xcj.asia/blog/828356.Doc

原标题：golang mysql 读写分离简单实现
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.i03xcj.asia/blog/429707.Doc

原标题：golang 系统设计单元测试编写原则最佳实践
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://book.i03xcj.asia/blog/586284.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://book.i03xcj.asia/blog/016238.Doc

原标题：golang 系统设计缓存基准测试对比方案
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.i03xcj.asia/blog/841559.Doc

原标题：nodejs 集成测试业务流程编写
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://book.i03xcj.asia/blog/120945.Doc

原标题：golang k8s job 一次性任务执行
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://book.i03xcj.asia/blog/276882.Doc

原标题：service‑worker 离线缓存实践
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://book.i03xcj.asia/blog/682853.Doc

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://book.i03xcj.asia/blog/959832.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://book.i03xcj.asia/blog/230057.Doc

原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://book.i03xcj.asia/blog/033672.Doc

原标题：安全笔记：Cookie安全属性SecureHttpOnly
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://book.i03xcj.asia/blog/182172.Doc

原标题：golang 系统设计 changelog 变更日志维护
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://book.i03xcj.asia/blog/683757.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.i03xcj.asia/blog/926205.Doc

原标题：golang 系统设计 git 分支流程 gitflow 实操
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.i03xcj.asia/blog/508673.Doc

原标题：OOMKilled 容器被杀完整排查
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://book.i03xcj.asia/blog/401618.Doc

原标题：用户敏感数据脱敏代码实现
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://book.i03xcj.asia/blog/873753.Doc

原标题：golang excel 简单读写操作示例
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://book.i03xcj.asia/blog/764892.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://book.i03xcj.asia/blog/209324.Doc

三、实战开发｜Practice
原标题：异步异常捕获避免进程崩溃
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.i03xcj.asia/blog/674977.Doc

原标题：Architecture：监控告警架构避免告警风暴设计
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://book.i03xcj.asia/blog/394519.Doc

原标题：golang 系统设计告警规则阈值设置方法论
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://book.i03xcj.asia/blog/628540.Doc

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://book.i03xcj.asia/blog/320753.Doc

原标题：golang csv 读写批量数据处理
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://book.i03xcj.asia/blog/221134.Doc

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://book.i03xcj.asia/blog/249817.Doc

原标题：静态博客部署 GitHub Pages 教程
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://book.i03xcj.asia/blog/259607.Doc

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://book.i03xcj.asia/blog/377563.Doc

原标题：安全复盘：业务登录暴力破解防护完整方案
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://book.i03xcj.asia/blog/224091.Doc

原标题：golang 速率限制令牌桶实现
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://book.i03xcj.asia/blog/774214.Doc

原标题：零基础理解JSON、XML数据格式处理
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://book.i03xcj.asia/blog/517653.Doc

原标题：数据库索引重建提升查询速度
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.i03xcj.asia/blog/954243.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.i03xcj.asia/blog/079051.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://book.i03xcj.asia/blog/175816.Doc

原标题：热更新开发环境配置教程
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.i03xcj.asia/blog/089592.Doc

原标题：从零搭建简单CLI命令行工具
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.i03xcj.asia/blog/160512.Doc

原标题：前端大文件分片上传完整方案
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://book.i03xcj.asia/blog/004629.Doc

原标题：异步异常捕获避免进程崩溃
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.i03xcj.asia/blog/739692.Doc

原标题：服务健康检查监控接口开发
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.i03xcj.asia/blog/240732.Doc

原标题：设计思考：分布式会话架构选型对比
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://book.i03xcj.asia/blog/017294.Doc

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://book.i03xcj.asia/blog/986537.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://book.i03xcj.asia/blog/689360.Doc

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://book.i03xcj.asia/blog/022100.Doc

原标题：golang 系统设计缓存一致性方案对比
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://book.i03xcj.asia/blog/794668.Doc

原标题：代码模块化组件化拆分思路
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.i03xcj.asia/blog/656780.Doc

原标题：golang excel 简单读写操作示例
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://book.i03xcj.asia/blog/394699.Doc

原标题：golang 系统设计分库分表本地测试调试技巧
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://book.i03xcj.asia/blog/022665.Doc

原标题：golang 系统设计接口向前兼容改造实操
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://book.i03xcj.asia/blog/306171.Doc

原标题：日志敏感信息脱敏泄露防护
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://book.i03xcj.asia/blog/330893.Doc

原标题：golang 系统设计 README 开源文档模板
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://book.i03xcj.asia/blog/686600.Doc

原标题：golang 系统设计灰度发布实现思路
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://book.i03xcj.asia/blog/504718.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://book.i03xcj.asia/blog/663540.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.i03xcj.asia/blog/729527.Doc

原标题：零基础理解模块化与组件化基础思想
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://book.i03xcj.asia/blog/823222.Doc

原标题：golang mysql 长连接短连接对比
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://book.i03xcj.asia/blog/946931.Doc

原标题：nodejs 进程间通信 IPC 实操
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://book.i03xcj.asia/blog/957484.Doc

原标题：浏览器本地存储安全使用技巧
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://book.i03xcj.asia/blog/167873.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://book.i03xcj.asia/blog/979431.Doc

原标题：磁盘占满服务不可用清理方案
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.i03xcj.asia/blog/474961.Doc

原标题：golang 系统设计开源项目依赖版本升级维护
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.i03xcj.asia/blog/651935.Doc

四、架构设计｜Architecture
原标题：TCP 心跳检测清理僵死连接
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://book.i03xcj.asia/blog/944519.Doc

原标题：数值 key 浮点匹配异常规避
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://book.i03xcj.asia/blog/419664.Doc

原标题：Git 代码冲突正确处理方式
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://book.i03xcj.asia/blog/497115.Doc

原标题：文件读写与异常捕获代码示例
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://book.i03xcj.asia/blog/252897.Doc

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://book.i03xcj.asia/blog/541489.Doc

原标题：Security：Web常见安全漏洞原理与修复清单
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://book.i03xcj.asia/blog/613775.Doc

原标题：架构笔记：业务操作审计日志系统架构设计
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://book.i03xcj.asia/blog/548717.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.i03xcj.asia/blog/252495.Doc

原标题：安全复盘：消息队列未授权访问安全加固
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://book.i03xcj.asia/blog/300487.Doc

原标题：内存广播本地进程消息通知
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://book.i03xcj.asia/blog/798117.Doc

原标题：动态定时任务业务调度实现
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.i03xcj.asia/blog/213635.Doc

原标题：golang 系统设计告警风暴抑制方案实现
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://book.i03xcj.asia/blog/588792.Doc

原标题：提交第一个开源 PR 完整流程
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://book.i03xcj.asia/blog/656584.Doc

原标题：golang 系统设计埋点数据上报方案
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://book.i03xcj.asia/blog/366460.Doc

原标题：golang k8s 基础概念 pod deployment
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://book.i03xcj.asia/blog/170551.Doc

原标题：缓存过期打散防止缓存雪崩
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://book.i03xcj.asia/blog/579335.Doc

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://book.i03xcj.asia/blog/408669.Doc

原标题：golang dockerfile 多阶段构建详解
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://book.i03xcj.asia/blog/064822.Doc

?
