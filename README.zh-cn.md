## 懒得看，你给我讲一下这是什么玩意儿，我这就给你点⭐!
这是一个新的IM协议，并与基于联邦的治理的实施。

## 等等！我可以在我的AWS EC2 T或Azure B1系列机器上托管它吗？
内存使用和存储使用以及部署的方便性是这个项目的 **第0级** 关注点。
所以它应该是可以在1C1G的小鸡上运行的。

另外，这个产品对云计算基础设施非常友好，所有的数据库和指标都考虑到了用户可能在云计算SaaS上部署。

## ~~如果我超级有钱~~它在我的k8s集群上的扩展性好吗？
横向扩展是一个非常大的挑战，更不用说我必须考虑独立部署的困难。
不能自动化的水平扩展对Ops来说就更可怕了，所以当我做单机部署版本时，尽力让它能扩展的。
在这个阶段，我将尝试解耦这些组件，然后尝试以集群友好的方式开发它们。