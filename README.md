# 搬瓦工价格：全系列套餐配置与年付月付对比，附最新优惠码和购买避坑要点

搬瓦工（BandwagonHost）这几年被问得最多的问题其实就一个：到底多少钱能拿下，贵的那些套餐贵在哪。这篇直接把官网当前在售的几条产品线价格、配置、付款周期和折扣情况一次讲清楚，最后按不同需求给个对号入座的建议。

## 先说结论：最低多少钱能上车

搬瓦工官网目前公开的最便宜套餐是 **20G KVM VPS，年付 $49.99**，配置为 2 核 CPU、1GB 内存、20GB SSD、每月 1TB 流量、1Gbps 带宽。这是普通国际线路，机房在美国洛杉矶、弗里蒙特、纽约等地可选。

再往上，如果你要对中国大陆访问友好的线路，CN2 GIA-E 系列常规套餐季付 $49.99 起；限量版系列不定期补货时，年付 $49.99 到 $99.99 之间能买到配置更好的机器。价格梯度大致就是这样：入门 50 美元一年，主流线路 100 到 300 美元一年，香港和东京的低延迟线路则从每月 89.99 美元起步。

## 官网在售套餐价格总览

搬瓦工的产品线按线路和机房分成几个系列，价格差异主要来自线路质量。下面按系列列出当前官网及官方渠道展示的全部在售配置。

### KVM 常规套餐（普通国际线路）

| 套餐名称 | CPU | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 计费周期 | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 20G KVM VPS | 2核 | 1GB | 20GB | 1TB | 1Gbps | $49.99 | 年付 | [ 查看入门套餐](https://bit.ly/BandwagonHost) |
| 40G KVM VPS | 3核 | 2GB | 40GB | 2TB | 1Gbps | $52.99 | 半年付 | [ 查看半年付套餐](https://bit.ly/BandwagonHost) |
| 80G KVM VPS | 4核 | 4GB | 80GB | 3TB | 1Gbps | $19.99 | 月付 | [ 查看月付套餐](https://bit.ly/BandwagonHost) |
| 160G KVM VPS | 5核 | 8GB | 160GB | 4TB | 1Gbps | $39.99 | 月付 | [ 查看160G套餐](https://bit.ly/BandwagonHost) |
| 320G KVM VPS | 6核 | 16GB | 320GB | 5TB | 1Gbps | $79.99 | 月付 | [ 查看320G套餐](https://bit.ly/BandwagonHost) |
| 480G KVM VPS | 7核 | 24GB | 480GB | 6TB | 1Gbps | $119.99 | 月付 | [ 查看480G套餐](https://bit.ly/BandwagonHost) |

这一档走的是普通国际线路，电信用户晚高峰可能会觉得堵，但拿来跑测试环境、学 Linux、做面向海外用户的外贸站完全够用。所有套餐都跑在 KVM 虚拟化平台上，用官方自研的 KiwiVM 面板管理，支持快照、机房切换、API 等功能，系统模板有 20 多种可选。

### CN2 GIA-E 套餐（主力产品线）

这是搬瓦工最有代表性的系列，三网双向 CN2 GIA 优化，购买后可以在 12 个以上机房之间自由切换，包括洛杉矶 DC6/DC9、日本大阪软银 JPOS_1、荷兰 EUNL_9 等。

| 套餐名称 | CPU | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 计费周期 | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CN2 GIA-E | 2核 | 1GB | 20GB | 1TB | 2.5Gbps | $49.99 | 季付（年付约$169.99） | [ 查看GIA-E入门款](https://bit.ly/BandwagonHost) |
| CN2 GIA-E | 3核 | 2GB | 40GB | 2TB | 2.5Gbps | $89.99 | 季付（年付约$299.99） | [ 查看2G内存款](https://bit.ly/BandwagonHost) |
| CN2 GIA-E | 4核 | 4GB | 80GB | 3TB | 2.5Gbps | $56.99 | 月付 | [ 查看4G内存款](https://bit.ly/BandwagonHost) |
| CN2 GIA-E | 6核 | 8GB | 160GB | 5TB | 5Gbps | $86.99 | 月付 | [ 查看8G内存款](https://bit.ly/BandwagonHost) |
| CN2 GIA-E | 8核 | 16GB | 320GB | 8TB | 5Gbps | $159.99 | 月付 | [ 查看16G内存款](https://bit.ly/BandwagonHost) |
| CN2 GIA-E | 10核 | 32GB | 640GB | 10TB | 10Gbps | $289.99 | 月付 | [ 查看32G内存款](https://bit.ly/BandwagonHost) |
| CN2 GIA-E | 12核 | 64GB | 1280GB | 12TB | 10Gbps | $549.99 | 月付 | [ 查看12核款](https://bit.ly/BandwagonHost) |
| CN2 GIA-E | 12核 | 64GB | 1280GB | 15TB | 10Gbps | $679.00 | 月付 | [ 查看15TB流量款](https://bit.ly/BandwagonHost) |
| CN2 GIA-E | 12核 | 64GB | 1280GB | 20TB | 10Gbps | $899.00 | 月付 | [ 查看20TB流量款](https://bit.ly/BandwagonHost) |
| CN2 GIA-E | 24核 | 64GB | 1280GB | 12TB | 10Gbps | $749.99 | 月付 | [ 查看24核款](https://bit.ly/BandwagonHost) |

绝大多数建站需求盯着前两档就够了。2GB 内存那款季付 $89.99，是这个系列里配置和价格平衡得比较好的一档。

### SLA PLAN（企业电商专属）

较新的产品线，机房在洛杉矶 DC5，线路为电信 CN2 GIA + 联通 AS10099 + 移动 CMIN2 三网直连，官方承诺 99.99% 在线率，达不到按约定赔付时长，另外支持每两周免费更换一次 IP。

| 套餐名称 | CPU | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 计费周期 | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SLA PLAN | 2核独享 | 1GB | 20GB | 1TB | 2.5Gbps | $65.89 | 季付 | [ 查看SLA入门款](https://bit.ly/BandwagonHost) |
| SLA PLAN | 3核独享 | 2GB | 40GB | 2TB | 2.5Gbps | $116.99 | 季付 | [ 查看SLA 2G款](https://bit.ly/BandwagonHost) |
| SLA PLAN | 4核独享 | 4GB | 80GB | 3TB | 2.5Gbps | $69.99 | 月付 | [ 查看SLA 4G款](https://bit.ly/BandwagonHost) |
| SLA PLAN | 6核独享 | 8GB | 160GB | 5TB | 5Gbps | $109.99 | 月付 | [ 查看SLA 8G款](https://bit.ly/BandwagonHost) |
| SLA PLAN | 8核独享 | 16GB | 320GB | 8TB | 5Gbps | $199.99 | 月付 | [ 查看SLA 16G款](https://bit.ly/BandwagonHost) |
| SLA PLAN | 10核独享 | 32GB | 640GB | 10TB | 10Gbps | $369.99 | 月付 | [ 查看SLA 32G款](https://bit.ly/BandwagonHost) |
| SLA PLAN | 12核独享 | 64GB | 1280GB | 12TB | 10Gbps | $699.99 | 月付 | [ 查看SLA 12核款](https://bit.ly/BandwagonHost) |
| SLA PLAN | 12核独享 | 64GB | 1280GB | 15TB | 10Gbps | $879.99 | 月付 | [ 查看SLA 15TB款](https://bit.ly/BandwagonHost) |
| SLA PLAN | 12核独享 | 64GB | 1280GB | 20TB | 10Gbps | $1159.99 | 月付 | [ 查看SLA 20TB款](https://bit.ly/BandwagonHost) |

CPU 标的是独享核，入门款虽然只给 1GB 内存，但底层是 AMD EPYC 服务器。适合掉线一分钟就影响收入的跨境电商类业务，纯个人博客用这个有点浪费。

### 香港与日本 CN2 GIA（低延迟高端线路）

| 套餐名称 | CPU | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 计费周期 | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 香港 CN2 GIA | 2核 | 2GB | 40GB | 0.5TB | 1Gbps | $89.99 | 月付（年付$899.99） | [ 查看香港入门款](https://bit.ly/BandwagonHost) |
| 香港 CN2 GIA | 4核 | 4GB | 80GB | 1TB | 1Gbps | $155.99 | 月付 | [ 查看香港4G款](https://bit.ly/BandwagonHost) |
| 香港 CN2 GIA | 6核 | 8GB | 160GB | 2TB | 1Gbps | $299.99 | 月付 | [ 查看香港8G款](https://bit.ly/BandwagonHost) |
| 香港 CN2 GIA | 8核 | 16GB | 320GB | 4TB | 1Gbps | $589.99 | 月付 | [ 查看香港16G款](https://bit.ly/BandwagonHost) |
| 香港 CN2 GIA | 10核 | 32GB | 640GB | 6TB | 1Gbps | $989.99 | 月付 | [ 查看香港32G款](https://bit.ly/BandwagonHost) |
| 香港 CN2 GIA | 12核 | 64GB | 1280GB | 8TB | 1Gbps | $1889.99 | 月付 | [ 查看香港顶配](https://bit.ly/BandwagonHost) |
| 东京 CN2 GIA | 2核 | 2GB | 40GB | 0.5TB | 1.2Gbps | $89.99 | 月付（年付$899.99） | [ 查看东京入门款](https://bit.ly/BandwagonHost) |
| 东京 CN2 GIA | 4核 | 4GB | 80GB | 1TB | 1.2Gbps | $155.99 | 月付 | [ 查看东京4G款](https://bit.ly/BandwagonHost) |
| 东京 CN2 GIA | 6核 | 8GB | 160GB | 2TB | 1.2Gbps | $299.99 | 月付 | [ 查看东京8G款](https://bit.ly/BandwagonHost) |
| 东京 CN2 GIA | 8核 | 16GB | 320GB | 4TB | 1.2Gbps | $589.99 | 月付 | [ 查看东京16G款](https://bit.ly/BandwagonHost) |
| 东京 CN2 GIA | 10核 | 32GB | 640GB | 6TB | 1.2Gbps | $989.99 | 月付 | [ 查看东京32G款](https://bit.ly/BandwagonHost) |
| 东京 CN2 GIA | 12核 | 64GB | 1280GB | 8TB | 1.2Gbps | $1889.99 | 月付 | [ 查看东京顶配](https://bit.ly/BandwagonHost) |
| 大阪 CN2 GIA | 2核 | 2GB | 40GB | 0.5TB | 1.5Gbps | $49.99 | 月付（年付$499.99） | [ 查看大阪入门款](https://bit.ly/BandwagonHost) |
| 大阪 CN2 GIA | 4核 | 4GB | 80GB | 1TB | 1.5Gbps | $86.99 | 月付 | [ 查看大阪4G款](https://bit.ly/BandwagonHost) |
| 大阪 CN2 GIA | 6核 | 8GB | 160GB | 2TB | 1.5Gbps | $165.99 | 月付 | [ 查看大阪8G款](https://bit.ly/BandwagonHost) |
| 大阪 CN2 GIA | 8核 | 16GB | 320GB | 4TB | 1.5Gbps | $329.99 | 月付 | [ 查看大阪16G款](https://bit.ly/BandwagonHost) |
| 大阪 CN2 GIA | 10核 | 32GB | 640GB | 6TB | 1.5Gbps | $549.99 | 月付 | [ 查看大阪32G款](https://bit.ly/BandwagonHost) |
| 大阪 CN2 GIA | 12核 | 64GB | 1280GB | 8TB | 1.5Gbps | $1059.99 | 月付 | [ 查看大阪顶配](https://bit.ly/BandwagonHost) |

香港和东京的入门款价格一样，都是月付 $89.99、年付 $899.99，主要差别在带宽（东京 1.2Gbps 略高于香港 1Gbps）。大阪系列要便宜不少，年付 $499.99 起，常被当作这两个系列的平替。注意这三条线的套餐都不能迁移机房。

### 迪拜方案（特殊区域）

| 套餐名称 | CPU | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 计费周期 | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 迪拜 | 2核 | 1GB | 20GB | 0.5TB | 1Gbps | $19.99 | 月付 | [ 查看迪拜入门款](https://bit.ly/BandwagonHost) |
| 迪拜 | 3核 | 2GB | 40GB | 1TB | 1Gbps | $32.99 | 月付 | [ 查看迪拜2G款](https://bit.ly/BandwagonHost) |
| 迪拜 | 4核 | 4GB | 80GB | 2TB | 1Gbps | $56.99 | 月付 | [ 查看迪拜4G款](https://bit.ly/BandwagonHost) |
| 迪拜 | 6核 | 8GB | 160GB | 3TB | 1Gbps | $86.99 | 月付 | [ 查看迪拜8G款](https://bit.ly/BandwagonHost) |
| 迪拜 | 8核 | 16GB | 320GB | 4TB | 1Gbps | $159.99 | 月付 | [ 查看迪拜16G款](https://bit.ly/BandwagonHost) |
| 迪拜 | 10核 | 32GB | 640GB | 5TB | 1Gbps | $289.99 | 月付 | [ 查看迪拜32G款](https://bit.ly/BandwagonHost) |
| 迪拜 | 12核 | 64GB | 1280GB | 6TB | 1Gbps | $549.99 | 月付 | [ 查看迪拜顶配](https://bit.ly/BandwagonHost) |

业务覆盖中东才需要考虑它，国内用户访问延迟很高，基本可以忽略这个系列。

## 限量版套餐：搬瓦工价格里最值得蹲的部分

除了常规在售套餐，搬瓦工会不定期放出一批限量版，售完即止，性价比往往远高于常规款。常见的几款：

- **CN2 GIA-E 10G 限量版**：年付 $49.99，用普通套餐的钱买到 CN2 GIA-E 机房，是圈内知名的“传家宝”，补货经常秒没。
- **CN2 GIA-E 20G 限量版**：年付 $89.99，1 核 1GB、20GB SSD、1TB 月流量，2.5Gbps 带宽。
- **CN2 GIA-E 40G 限量版**：年付 $89.99（上线初期定价 $79.99，后有调整），2 核 2GB、40GB SSD、2TB 月流量，可选机房数量多。
- **THE PLAN 限量版**：季付 $29、半年付 $55、年付 $99，2 核 2GB、40GB SSD、1TB 月流量，可选机房 17 个以上；后续推出的 v2 款流量翻倍到 2TB，年付 $119。
- **香港限量版**：1 核 1GB、20GB SSD，年付 $79.99，是目前用最低成本拿到香港机房的途径。
- **日本大阪软银限量版（JPOS_1）**：年付 $69.99 起，老款配置为 512MB 内存、10GB SSD、500GB 月流量，新款升级到 1 核 2GB、40GB SSD、2000GB 月流量，年付 $79.99。

限量版的风险在于不稳定：有货的时候要抢，没货的时候只能等。官方有专门的库存页面（stock.bwg.net 可以实时查），想蹲限量版的话建议先看库存再决定。目前想直接买 CN2 GIA 常规套餐的话，可以从这里进：[👉 查看CN2 GIA套餐与当前库存](https://bit.ly/BandwagonHost)

## 优惠码：能省多少，怎么用

搬瓦工的优惠码是**循环折扣**，续费同样生效，这一点比很多主机商良心。根据近期多方整理的信息：

- 常年有效的优惠码折扣力度在 **6% 左右**，常用的 BWHCGLUKKB 约 6.58%，可在下单时填写验证。
- 2026 年 2 月曾短暂出现过与 NodeSeek 合作的 NODESEEK2026（6.77%），但两天左右就失效了，别拿旧文章里的码直接当有效。
- 每年有两个固定促销节点：**双十一和黑色星期五**，这两个时间段通常会放出力度更大的全场折扣码。

以年付 $169.99 的 CN2 GIA-E 入门款为例，用 6.58% 的码之后大约是 $158.8，一年省 11 美元出头。金额不大，但填优惠码只需要三秒，没理由不填。

## 年付、季付、半年付差多少

搬瓦工支持月付、季付、半年付、年付四种周期，但**不同套餐支持的周期不一样**，下单页面会显示当前套餐可选的选项。几条规律：

- **年付最划算**，一般年付价格约等于月付的 10 倍，相当于一年只付 10 个月。
- 最便宜的入门套餐（如年付 $49.99 的 KVM 款）只提供年付，没有月付选项。
- CN2 GIA-E 主力款以季付和月付为主，限量版多为年付。
- 最长账单周期是年付，没有两年付或三年付。
- 购买之后可以在后台修改续费周期，比如先月付试用，确认线路满意再改成年付续费。

一个稳妥的买法：第一次买支持月付或季付的套餐先付一个短周期，测完路由和延迟再决定续费周期。毕竟年付的钱是一次性交出去的。

## 支付方式和退款政策

付款方面对国内用户很友好，支持**支付宝、微信支付、PayPal、信用卡和银联**，支付宝扫码后人民币结算，系统自动按汇率换算成美元，不需要任何外币支付工具。

退款政策要单独提醒，条件比想象中严：

> 账户注册后 30 天内可以申请全额退款，但同时要求：账户下 VPS 总数少于 3 个、历史总支付金额少于 100 美元、总支付次数少于 10 次、此前没有用过退款资格、没有发起过支付争议，且 VPS 的 IP 未被封禁。

换句话说，30 天是从**注册账户**算起，不是从购买算起。打算先注册观望一段时间的，建议想买的时候再注册，别浪费这个窗口。

## 按需求对号入座

- **预算 50 美元/年，跑测试或纯海外业务**：20G KVM 常规款。
- **主力建站、需要大陆访问质量**：CN2 GIA-E 系列，季付 $49.99 起的入门款或季付 $89.99 的 2G 内存款。
- **跨境电商等高价值业务**：SLA PLAN，99.99% 在线率加每两周免费换 IP。
- **对延迟有刚需且预算充足**：香港或东京 CN2 GIA，月付 $89.99 起；预算减半可以考虑大阪系列。
- **愿意蹲优惠**：限量版系列，年付 $49.99 到 $119.99 之间，盯库存页，看到补货尽快下单。

下单前最后确认三件事：机房是否可选、付款周期能否匹配你的预算节奏、优惠码是否已经填上。搬瓦工的套餐配置一旦开通，流量和配置不能中途降级退款，选之前把表格再对一遍比事后纠结省事得多。
