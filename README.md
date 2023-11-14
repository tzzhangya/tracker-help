![](images/swoolee.png)

## 什么是 Swoole Tracker

[Swoole Tracker](https://business.swoole.com/tracker/index)是 Swoole 官方推出的一整套企业级包括 PHP 和  Swoole 分析调试工具以及应用性能管理（APM）平台，针对常规的 FPM 和 Swoole 常驻进程的业务，提供全面的性能监控、分析和调试的解决方案。

Swoole Tracker 能够帮助企业自动分析并汇总统计关键系统调用并智能准确的定位到具体的 PHP 业务代码，实现业务应用性能最优化、强大的调试工具链为企业业务保驾护航、提高 IT 生产效率。
* 时刻掌握应用架构模型111

>[success] 自动发现应用依赖拓扑结构和展示，时刻掌握应用的架构模型

* 分布式跨应用链路追踪

>[success] 支持无侵入的分布式跨应用链路追踪，让每个请求一目了然，全面支持协程/非协程环境，数据实时可视化

* 全面分析报告服务状况

>[success] 各种维度统计服务上报的调用信息， 比如总流量、平均耗时、超时率等，并全面分析报告服务状况

* 拥有强大的调试工具链

>[success] 本系统支持远程调试，可在系统后台远程开启检测内存泄漏、阻塞检测、代码性能分析和查看调用栈；也支持手动埋点进行调试，后台统一查看结果

* 同时支持FPM和Swoole

>[success] 完美支持PHP-FPM环境，不仅限于在Swoole中使用

* 完善的系统监控

>[success] 支持完善的系统监控，零成本部署，监控机器的CPU、内存、网络、磁盘等资源，可以很方便的集成到现有报警系统

* 一键安装和零成本接入

>[success] 规避与减小整体投资风险，本系统的客户端提供脚本可一键部署，服务端可在Docker环境中运行，简单快捷

* 提高各部门生产效率

>[success] 在复杂系统中追踪服务及代码层级性能瓶颈，帮助IT、开发等部门提升工作效率，将重点聚焦在核心工作中

## Swoole Tracker 特色

Swoole Tracker 针对常规的 FPM 和 Swoole 常驻进程的业务，提供全面的性能监控、分析和调试的解决方案，具有如下特点

* 聚焦业务

业务人员经常因为各种问题遭到用户投诉，如短信发送失败、登录缓慢、等待时间长……，实际上因为这些问题造成的损失仅仅是冰山一角，在更多的情况下，业务人员并不知晓哪些业务环节会对用户产生了影响，也无法准确评估这些业务环节对业务的影响程度。

Swoole Tracker 通过抓取 PHP 底层函数调用相关信息，能够自动发现应用中的各个函数调用、调用流程，实时记录调用流程的用户行为数据、体验数据及相关 IT 性能指标，帮助业务人员可视化诠释各种用户问题。

* 应用拓扑

现代应用系统是一个复杂的多技术栈整合环境，无论是网络层的复杂性还是更多第三方云服务的使用，都给系统的维护与性能管理造成了更大的挑战，从用户端到主机端的每一个层次的性能表现都会对最终的应用性能产生直接的影响，所以有必要实现每一个环节的性能管理。

Swoole Tracker 能够自动发现应用的请求目标（如数据库、第三方接口地址、Redis 地址等），实现应用端到端的关联监控、告警与分析并且生成应用拓扑图。

* 链路追踪准确到位

页面加载缓慢，接口响应时间长是业务人员经常遇到的问题，而 Swoole Tracker 自动在请求开始和结束自动统计执行耗时，自动计算各种调用耗时（如 SQL 执行、API 调用等），快速定位接口中各种耗时问题，确保快速构建与持续集成交付。

开发人员的苦恼是离开测试环境，在真实的生产系统中追踪代码问题困难并且耗时。通过 Swoole Tracker 实现对运行时代码、SQL执行、API调用过程的性能数据采集与分析，深入到代码层面定位性能瓶颈，分析性能下降的因素。

* 远程调试方便快捷

远程调试帮助开发者从大量的业务代码中抓取并分析代码执行逻辑关系与状态，如执行时间最长的函数调用、代码阻塞、内存泄漏、查看调用栈等等。

