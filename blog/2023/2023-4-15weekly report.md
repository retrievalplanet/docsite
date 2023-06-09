# 2023-4-15检索星球周报

## 🪐saturn数据播报

全球节点数量达到1030

TTFB达到21.22ms

retrievals数量达到1234

空余空间为3565.34TB

![image-20230412163023542](../2023/img/saturn-data.png)



## 🚀项目进展

### 1️⃣saturn

1.saturn官方网址从https://strn.network/变为https://saturn.tech/

2.官网Node Requirements从**1TB SSD** (4TB+ SSD recommended)变为**2TB SSD** (16TB+ SSD recommended)

![image-20230412175729582](../2023/img/函数.png)

3.项目路线图更新：

更新前： 

2023.6---->私有L2测试版发布在主网上，L1节点不向L2节点进行缓存。

2023.9---->启动L2节点的公共网络。L2节点将不向Filecoin存储供应商（SP）进行缓存。



更新后： 

 2023.4 ----->为客户进行公开测试。

 2023.5------>Saturn节点运营商通过FVM智能合约获得报酬。

 2023.7------>Saturn L1节点将不向Filecoin存储提供商和IPFS进行缓存。



###  2️⃣boost工具

1.修复 测试新Http服务器的相关代码，增加waitServerUp方法，检查服务器是否有200状态代码的响应（即是否成功响应）

![image-20230412214119809](../2023/img/函数.png)

2.修复 创建阶段性遗留问题的目录

3.修复 显示验证离线交易的commp状态

4.修复 dagstore初始化所有参数

###  3️⃣storetheindex

1.从0.6.0版本更新为0.6.1版本

2.删除dev版本中旧的dhstore io2 volume

现在节点被转移到使用 "gp3 "volume，以前的 "io2 "volume不再需要。

3.在开发环境中部署最新版本

4.销毁prod上现在多余的r5b节点组群

因为现在所有的volumes都转移到了 "gp3"，所以不需要支持 "io2 "BlockExpress的实例类型,因此销毁了它们。

![image-20230413145228253](../2023/img/r5b.png)

5.跳过已经处理的广告

6.给予ber和cali对镜像的读取权限

### 4️⃣Station

1.将undici从5.21.0升级到5.21.2



##  📢一周资讯

- FEVM现在是Brave Wallet桌面版（v1.50）中的一个预装网络，开发者更容易开始构建和使用Filecoin虚拟机了。

- Hong Kong web3 Festival 2023 【web3嘉年华】在香港火热进行中

​       FIL Hong Kong现场：

KEN Labs FVM 早期构建者

![KEN Labs FVM 早期构建者](../2023/img/2023-4-15-1.jpg)

KEN Labs 成为数据经济联盟成员

![KEN Labs 成为数据经济联盟成员](../2023/img/2023-4-15-2.jpg)

- 2023年4月15日-19日,将在比利时、布鲁塞尔举行IPFS þing（IPFS代表大会）

IPFS þing是一个为期一周的IPFS实施者社区的聚会。从会谈、研讨会、讨论圈、黑客时间等等，所有这些都集中在推进IPFS的实施。

报名链接：[IPFS þing (ipfs-thing.io)](https://2023.ipfs-thing.io/)

