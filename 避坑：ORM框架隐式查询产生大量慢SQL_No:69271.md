最新前沿技术资讯

一、入门教程｜Getting Started
原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://wiki.h1nihn.asia/arts/032313.Doc

原标题：golang redis pipeline 原子性说明
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.h1nihn.asia/arts/413695.Doc

原标题：Git 代码冲突正确处理方式
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.h1nihn.asia/arts/334077.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.h1nihn.asia/arts/184999.Doc

原标题：并发数据覆盖加锁安全处理
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.h1nihn.asia/arts/170649.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://wiki.h1nihn.asia/arts/060501.Doc

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.h1nihn.asia/arts/462878.Doc

原标题：Hands‑on：简易代理服务器开发实践
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.h1nihn.asia/arts/441123.Doc

原标题：golang 跨域处理中间件编写
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.h1nihn.asia/arts/227799.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://wiki.h1nihn.asia/arts/711948.Doc

原标题：实践：灰度流量切分简易实现方案
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.h1nihn.asia/arts/444379.Doc

原标题：动态定时任务业务调度实现
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.h1nihn.asia/arts/829116.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.h1nihn.asia/arts/108464.Doc

原标题：golang 系统设计开发环境本地调试最佳实践
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.h1nihn.asia/arts/609874.Doc

原标题：Practice：实现请求大小限制中间件防护大报文
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.h1nihn.asia/arts/923935.Doc

原标题：golang redis lua 脚本原子操作
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.h1nihn.asia/arts/250561.Doc

原标题：避坑：正则回溯引发CPU占满DoS风险
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.h1nihn.asia/arts/628627.Doc

原标题：OpenSource：开源项目README高质量编写指南
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.h1nihn.asia/arts/754382.Doc

原标题：程序性能指标 CPU 内存监控
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.h1nihn.asia/arts/997289.Doc

原标题：DevOps：容器网络模式选型与坑点总结
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.h1nihn.asia/arts/851404.Doc

原标题：golang 系统设计 rest 状态码合理使用指南
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.h1nihn.asia/arts/483051.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://wiki.h1nihn.asia/arts/419916.Doc

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://wiki.h1nihn.asia/arts/291612.Doc

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.h1nihn.asia/arts/380807.Doc

原标题：本地简易配置中心动态管理
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.h1nihn.asia/arts/366460.Doc

原标题：Redis 大 key 拆分集群卡顿解决
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.h1nihn.asia/arts/514844.Doc

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://wiki.h1nihn.asia/arts/883585.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.h1nihn.asia/arts/872435.Doc

原标题：实践：前后端分离项目登录状态保持完整方案
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.h1nihn.asia/arts/021705.Doc

原标题：golang jaeger 链路追踪 go 接入
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.h1nihn.asia/arts/661380.Doc

原标题：golang 日志与链路 ID 关联打印
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.h1nihn.asia/arts/061688.Doc

原标题：golang docker compose 完整语法
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.h1nihn.asia/arts/366755.Doc

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.h1nihn.asia/arts/007401.Doc

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.h1nihn.asia/arts/444105.Doc

原标题：线上接口超时故障排查思路
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.h1nihn.asia/arts/054853.Doc

原标题：项目目录结构规范化最佳实践
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://wiki.h1nihn.asia/arts/852770.Doc

原标题：入门实践：简单图片上传预览本地demo
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.h1nihn.asia/arts/004156.Doc

原标题：部署实践：告警收敛避免告警风暴配置
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.h1nihn.asia/arts/634179.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.h1nihn.asia/arts/619667.Doc

原标题：golang kafka 重试机制配置实操
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.h1nihn.asia/arts/048175.Doc


二、踩坑排错｜Troubleshooting
原标题：读懂开源项目 README 实用技巧
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.h1nihn.asia/arts/724065.Doc

原标题：零基础理解跨域问题产生原因与基础方案
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.h1nihn.asia/arts/460448.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://wiki.h1nihn.asia/arts/196216.Doc

原标题：golang mysql 读写分离简单实现
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.h1nihn.asia/arts/495069.Doc

原标题：YAML 配置文件语法快速上手
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.h1nihn.asia/arts/372457.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.h1nihn.asia/arts/855887.Doc

原标题：部署实践：容器优雅停机配置处理信号
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.h1nihn.asia/arts/239437.Doc

原标题：新手向：开源项目fork与同步上游代码
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.h1nihn.asia/arts/647261.Doc

原标题：本地简易配置中心动态管理
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.h1nihn.asia/arts/029806.Doc

原标题：开发复盘：超时参数统一治理线上服务实践
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://wiki.h1nihn.asia/arts/851803.Doc

原标题：golang base64 编码解码实操
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.h1nihn.asia/arts/679273.Doc

原标题：golang proto 默认值坑点梳理
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.h1nihn.asia/arts/631446.Doc

原标题：golang 系统设计 csrf 接口防护实现
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.h1nihn.asia/arts/100097.Doc

原标题：golang 工具函数库封装思路
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.h1nihn.asia/arts/123270.Doc

原标题：部署复盘：服务启动顺序依赖处理方案
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.h1nihn.asia/arts/343813.Doc

原标题：golang prometheus metrics 埋点开发
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.h1nihn.asia/arts/744101.Doc

原标题：全平台系统环境变量配置
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.h1nihn.asia/arts/047981.Doc

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.h1nihn.asia/arts/278395.Doc

原标题：一次JWT令牌过期时间异常问题复盘
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.h1nihn.asia/arts/604954.Doc

原标题：快速入门异步编程基础模型
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://wiki.h1nihn.asia/arts/474958.Doc

原标题：golang 系统设计消息队列降级业务开关实现
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.h1nihn.asia/arts/829818.Doc

原标题：开发记录：接口请求日志记录完整中间件实现
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.h1nihn.asia/arts/425796.Doc

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.h1nihn.asia/arts/844446.Doc

原标题：前端水印防信息泄露实现
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.h1nihn.asia/arts/315362.Doc

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.h1nihn.asia/arts/923877.Doc

原标题：上传接口跨域配置特殊适配
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://wiki.h1nihn.asia/arts/832183.Doc

原标题：golang 系统设计告警渠道钉钉邮件企业微信集成
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.h1nihn.asia/arts/425446.Doc

原标题：实战：Redis集群本地搭建与功能验证
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.h1nihn.asia/arts/458169.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://wiki.h1nihn.asia/arts/859640.Doc

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.h1nihn.asia/arts/044232.Doc

原标题：DevOps：多环境镜像标签版本管理规范
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.h1nihn.asia/arts/352101.Doc

原标题：线上异常：线程池队列拒绝策略配置错误丢任务
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.h1nihn.asia/arts/158169.Doc

原标题：从零学习简单分布式ID生成思路
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://wiki.h1nihn.asia/arts/777388.Doc

原标题：golang 系统设计高可用服务架构梳理
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.h1nihn.asia/arts/994645.Doc

原标题：架构笔记：高并发系统核心设计思路总结
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.h1nihn.asia/arts/018050.Doc

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.h1nihn.asia/arts/194384.Doc

原标题：Redis 热点 key 拆分降低集群压力
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.h1nihn.asia/arts/085000.Doc

原标题：优化实践：内存池思想减少频繁分配释放
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.h1nihn.asia/arts/758710.Doc

原标题：开源实践：开源项目本地调试构建排坑经验
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.h1nihn.asia/arts/966111.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://wiki.h1nihn.asia/arts/331422.Doc

三、实战开发｜Practice
原标题：golang 系统设计内存瓶颈定位优化思路
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.h1nihn.asia/arts/201106.Doc

原标题：快速上手简单性能监控指标查看
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://wiki.h1nihn.asia/arts/782799.Doc

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.h1nihn.asia/arts/195069.Doc

原标题：golang 系统设计配置敏感信息加密存储方案
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.h1nihn.asia/arts/140221.Doc

原标题：程序性能指标 CPU 内存监控
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.h1nihn.asia/arts/044355.Doc

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.h1nihn.asia/arts/592477.Doc

原标题：golang 系统设计缓存与数据库一致性权衡
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.h1nihn.asia/arts/750918.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.h1nihn.asia/arts/007666.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.h1nihn.asia/arts/136858.Doc

原标题：golang redis stream 消息队列实践
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.h1nihn.asia/arts/592032.Doc

原标题：开源实践：开源项目本地调试构建排坑经验
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.h1nihn.asia/arts/174226.Doc

原标题：golang 系统设计 api 文档 swagger redoc 落地
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.h1nihn.asia/arts/992211.Doc

原标题：避坑：批量操作未分批次，一次性内存打爆
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.h1nihn.asia/arts/751043.Doc

原标题：golang mysql 读写分离简单实现
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.h1nihn.asia/arts/995998.Doc

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://wiki.h1nihn.asia/arts/285711.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.h1nihn.asia/arts/412269.Doc

原标题：golang 系统设计监控告警阈值设置思路
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://wiki.h1nihn.asia/arts/607017.Doc

原标题：优化实践：分页查询性能优化解决offset问题
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.h1nihn.asia/arts/759092.Doc

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.h1nihn.asia/arts/303922.Doc

原标题：内存泄漏定位分析完整流程
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://wiki.h1nihn.asia/arts/820820.Doc

原标题：序列化版本不一致解析失败
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.h1nihn.asia/arts/870956.Doc

原标题：优化实践：分页查询性能优化解决offset问题
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.h1nihn.asia/arts/492524.Doc

原标题：Practice：实现简单信号处理优雅停机实践
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://wiki.h1nihn.asia/arts/017252.Doc

原标题：golang 系统设计 api 接口兼容性设计原则
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.h1nihn.asia/arts/791873.Doc

原标题：golang redis 发布订阅简单示例
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.h1nihn.asia/arts/671060.Doc

原标题：架构笔记：分库分表中间件选型业务约束
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.h1nihn.asia/arts/662032.Doc

原标题：服务器 Swap 关闭提升响应速度
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.h1nihn.asia/arts/151400.Doc

原标题：调优方案：Web服务内核socket参数调优
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.h1nihn.asia/arts/133763.Doc

原标题：架构笔记：业务系统反模式架构踩坑总结
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.h1nihn.asia/arts/833652.Doc

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.h1nihn.asia/arts/342857.Doc

原标题：排错：CI流水线构建失败，日志无明确报错
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.h1nihn.asia/arts/269278.Doc

原标题：golang 系统设计缓存大 key 拆分优化实操
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.h1nihn.asia/arts/718325.Doc

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.h1nihn.asia/arts/737609.Doc

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.h1nihn.asia/arts/299101.Doc

原标题：用户敏感数据脱敏代码实现
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://wiki.h1nihn.asia/arts/576335.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.h1nihn.asia/arts/769577.Doc

原标题：nodejs 全局异常捕获进程防护
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://wiki.h1nihn.asia/arts/578539.Doc

原标题：Shell 运维脚本服务器效率提升
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.h1nihn.asia/arts/192772.Doc

原标题：内网测试服务搭建团队调试
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://wiki.h1nihn.asia/arts/672574.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.h1nihn.asia/arts/606936.Doc

四、架构设计｜Architecture
原标题：golang 文件上传下载接口开发
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.h1nihn.asia/arts/916310.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.h1nihn.asia/arts/553811.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.h1nihn.asia/arts/281400.Doc

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.h1nihn.asia/arts/307714.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.h1nihn.asia/arts/974362.Doc

原标题：golang 系统设计本地缓存与分布式缓存
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.h1nihn.asia/arts/532217.Doc

原标题：golang 系统设计开源项目依赖版本升级维护
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.h1nihn.asia/arts/933015.Doc

原标题：调优方案：Nginx性能参数调优高并发配置
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.h1nihn.asia/arts/121871.Doc

原标题：golang 系统设计唯一索引业务使用场景
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.h1nihn.asia/arts/936536.Doc

原标题：架构复盘：消息死信处理架构避免消息丢失
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://wiki.h1nihn.asia/arts/741317.Doc

原标题：golang 简单爬虫请求防封禁
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.h1nihn.asia/arts/939454.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://wiki.h1nihn.asia/arts/561554.Doc

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://wiki.h1nihn.asia/arts/892869.Doc

原标题：golang 系统设计熔断算法 hystrix 思路
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.h1nihn.asia/arts/795407.Doc

原标题：CI/CD 流水线自动构建部署落地
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.h1nihn.asia/arts/374093.Doc

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://wiki.h1nihn.asia/arts/529446.Doc

原标题：golang 系统设计 changelog 变更日志维护
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.h1nihn.asia/arts/163931.Doc

原标题：golang 系统设计 lru 缓存算法实现思路
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.h1nihn.asia/arts/333253.Doc

?
