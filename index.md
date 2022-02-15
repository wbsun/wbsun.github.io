## 闲记

### TIL: It works most of time

因为整天跟outage打交道的关系，一直认为一个产品必须有足够的failure handling才能运营，尤其是各种卖东西收钱的产品，感觉特别需要这种reliability。

最近看多了各种系统的outage，惊奇的发现绝大多数系统根本不会关心failure handling。数据库挂了，用一天前的backup！系统有bug变500了，重启就完了！订单丢了，who cares。。。

大多数时间能工作就好了，而且这个大多数有时是真的“大多数”！一个小产品小app可能几年都不会碰到任何问题。虽然对customer来说碰到问题很烦心，对产品来说却节省了时间资源。
