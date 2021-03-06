# 产品优势

| 产品优势 | 负载均衡 | 传统硬件负载均衡 |
| :- | :- | :- |
|弹性扩容| 京东云负载均衡绑定高可用组后，可根据业务负载情况自动调整后端服务器数量，实现资源合理配置，保证业务正常运行 |	业务增长达到硬件瓶颈时，需重新采购更高性能的设备，安装繁琐，甚至需中断业务进行|
|高可用性|京东云负载均衡服务可自动配置冗余、多可用区部署，支持高可用；绑定高可用组即可支持后端服务同机房跨机架、跨可用区的多维度高可用部署，消除后端服务实例由于单点设备故障造成的影响|采用传统双机热备，需人工配置，可用性一般|
|节约成本|无需采购硬件设备，可根据业务使用灵活选择计费方式，大幅降低硬件成本、免运维|需要昂贵的硬件设备、专业的运维人员，投入的物资和人力成本高 |
|服务丰富| 京东云负载均衡可同时注册云主机、容器实例以支持业务后端分发服务，服务类型丰富 |	用物理服务器支持后端分发服务|
|安全保障|提供基于公网IP的DDoS防护，保障业务安全|需单独采购、部署安全防护模块，操作繁杂，性价比不高|
|操作简单| 京东云负载均衡实现后端服务、虚拟服务器组、高可用组的模块化解耦，可高度复用，简化配置。例如不同协议的监听器（同时提供HTTP、HTTPS服务的业务）可复用相同后端服务 |	配置相对繁琐|
|易于维护|提供可视化界面，操作便捷；关联高可用组后直接与监控联动，实现伸缩自动化|需要专业的运维人员进行复杂的组合部署，增加人力成本|

## 相关参考

- [产品概述](../Introduction/Product-Overview.md)
- [产品规格](../Introduction/Specification.md)
- [价格总览](../Pricing/Price-Overview.md)
- [创建实例](../Getting-Started/Create-Instance.md)
- [创建虚拟服务器组](../Operation-Guide/TargetGroup-Management.md)
- [配置侦听策略](../Operation-Guide/Listener-Management.md)
- [管理后端服务与查看服务实例健康状态](../Operation-Guide/Backend-Management.md)
- [查看监控信息](../Operation-Guide/Monitoring.md)

