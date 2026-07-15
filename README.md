# 搬瓦工 THE PLAN 限量版套餐深度解析：99美元一年的传家宝值不值？配置、机房、价格、抢购补货全攻略（含 THE PLAN v2 对比与替代方案整理）

很多人搜"搬瓦工 THE PLAN"的时候，其实心里已经有个模糊的念头——这玩意儿号称"传家宝"，是不是真的有那么神？99 美元一年能买到 2 核 2G、40G SSD、每月 1TB 流量，还能在十几个 CN2 GIA 机房之间随便切，这种配置放常规套餐要 299.99 美元一年，差了整整三倍。说实话，第一次看到这个数字我也有点不敢信。

但问题也跟着来了：THE PLAN 现在还能买到吗？它和 THE PLAN v2 到底差在哪？售罄了怎么办？有没有同价位的替代方案？这篇文章就把这些问题一次说清楚，顺带把当前还能入手的搬瓦工限量版套餐整理成一张表，方便你对照着挑。

## THE PLAN 到底是个什么东西

THE PLAN 是搬瓦工（BandwagonHost）从 2023 年 1 月开始推出的限量版 KVM VPS 套餐，定位非常明确——用接近常规套餐的配置，以三分之一的价格卖给你，而且让你在一个套餐里就能自由切换多个高端机房。这种"一票玩全场"的玩法，是它在中文 VPS 圈子里被叫做"传家宝"的主要原因。

它最让人心动的不是某一项参数，而是**机房的自由度**。常规 CN2 GIA-E 套餐你买的时候就得选好机房，后续想换只能走付费迁移；THE PLAN 这种限量版则是把洛杉矶 DC6 CN2 GIA-E、DC9 CN2 GIA、香港 CMI、日本大阪软银、阿姆斯特丹联通精品线路这些平时单独要花高价才能用上的机房，全部打包进一个套餐，在 KiwiVM 后台一键切换，不收迁移费。

> 简单算一笔账：同配置（2 核 / 2GB / 40GB SSD / 1TB 流量 / 2.5Gbps）的常规 CN2 GIA-E 40G 套餐官网价是 $299.99/年，THE PLAN 2024 是 $99/年，差价 $200.99，相当于每年省下 67%。这就是为什么每次补货都是几分钟内被抢光。

## THE PLAN 系列三代成员对比

THE PLAN 不是单一产品，而是一个系列。从 2023 年到 2024 年，搬瓦工先后上线过三个版本，配置大致相同，主要在流量和机房数量上做差异化。下面这张表把三代成员放在一起，方便你直观对比。

| 套餐版本 | 商品 PID | 上线时间 | 年付价格 | 季付价格 | CPU | 内存 | SSD | 月流量 | 带宽上限 | 可选机房数 | 当前状态 | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| THE PLAN（初代） | 129 | 2023-01 | $99 | $29 | 2 核 | 2 GB | 40 GB | 1 TB | 2.5 Gbps | 17 | 已下架 | [查看 THE PLAN 初代](https://bwh81.net/aff.php?aff=79616&pid=129) |
| THE PLAN v2 | 131 | 2023-06 | $119 | $35 | 2 核 | 2 GB | 40 GB | 2 TB | 2.5 Gbps | 17 | 官网已移除专题页，可通过直达链接尝试 | [购买 THE PLAN v2](https://bwh81.net/aff.php?aff=79616&pid=131) |
| THE PLAN 2024 | 147 | 2024-02 | $99 | $29 | 2 核 | 2 GB | 40 GB | 1 TB | 2.5 Gbps | 18（新增 FMT8） | 官网显示 Out of Stock，等待补货 | [购买 THE PLAN 2024](https://bwh81.net/aff.php?aff=79616&pid=147) |

三代之间最关键的差异是两点：

- **流量**：THE PLAN v2 把月流量从 1TB 翻倍到 2TB，代价是年付价格涨了 20 美元。如果你每月跑不满 1TB，多花 20 美元意义不大；但如果你跑代理、做中转、挂下载，那 2TB 就值回来。
- **机房**：THE PLAN 2024 在 v2 的 17 个机房基础上新增了 FMT8（Fremont 第二机房），达到 18 个。CPU、内存、硬盘、带宽三项硬配置三代完全一致。

需要注意的是，截至撰写时，THE PLAN 2024 在官网商品页面显示为 "Out of Stock"（缺货），THE PLAN v2 的官方专题页也已被移除，但仍可通过直达链接尝试下单。搬瓦工的限量版套餐一向是"售罄即下架、补货才回归"的节奏，所以能不能买到，很大程度看你下手的时间点。

## THE PLAN 2024 的 18 个机房都覆盖哪些线路

很多人买 THE PLAN 看中的就是机房多样性。THE PLAN 2024 的 18 个机房大致可以这样归类：

**美国机房（10 个）**：洛杉矶 DC2 AO、DC3 CN2、DC4 MCOM、DC6 CN2 GIA-E、DC8 ZNET、DC9 CN2 GIA、Fremont FMT、Fremont FMT8、New Jersey USNJ、New York USNY_2、New York Coresite NY1（USNY_6）。

**加拿大机房（2 个）**：温哥华 CABC_1、温哥华 CN2GIA（CABC_6）。

**欧洲机房（2 个）**：阿姆斯特丹 DC2（EUNL_2）、阿姆斯特丹 DC9 联通精品（EUNL_9）。

**亚太机房（3 个）**：香港 CMI（HKHK_3）、日本大阪软银（JPOS_1）、阿联酋迪拜（AEDXB_1）。

**大洋洲机房（1 个）**：悉尼 AUSYD_1。

这里面最值得拎出来说的是 **DC6 CN2 GIA-E** 和 **DC9 CN2 GIA**——这两条是搬瓦工的看家线路，电信回程走 CN2 GIA，联通和移动也有对应优化，国内访问延迟普遍在 150ms 以内，晚高峰丢包率也比普通线路低一个量级。香港 CMI 适合移动用户，日本大阪软银适合联通用户，欧洲两个机房则适合有海外业务或中转需求的场景。

> THE PLAN 系列机房切换是免费的，在 KiwiVM 面板里点一下 "Migrate to another datacenter" 就行，通常几分钟内完成，数据不会丢。这一点比常规套餐灵活太多了。

## THE PLAN 真实使用体验：哪些场景适合，哪些场景劝退

光看参数表是没用的，真正决定你买不买的是"能不能干你想干的活"。结合社区里长期流传的使用反馈，THE PLAN 的适用和不适用的场景大致是这样：

**适合的场景**：

- **个人博客或小型建站**：2 核 2GB 跑 WordPress 绰绰有余，配合 DC6 CN2 GIA-E 线路，国内访客打开速度稳定。
- **自用代理或科学上网**：1TB 月流量对个人日常使用基本够，香港 CMI 或日本软银线路延迟低。
- **学习 Linux / 部署小工具**：40GB SSD 装 Docker、跑点轻量服务都行，KiwiVM 后台一键重装系统很方便。
- **跨地域中转节点**：18 个机房自由切换，可以把它当成一个"机房试验场"，哪里好就用哪里。

**劝退的场景**：

- **大流量下载站或视频中转**：1TB 月流量很快会被吃光，超量后会被限速到 1Mbps，这种需求建议直接上 THE PLAN v2 的 2TB 版本。
- **高并发商业站点**：THE PLAN 的 CPU 分配比例略低于同配置的常规 CN2 GIA-E 套餐（官方在 TOS 里写明限量版 CPU 占比相对低），扛突发流量不如常规版稳。
- **有 DDoS 防御需求**：搬瓦工所有套餐都不带 DDoS 防御，遇到大流量攻击会直接空路由（Nullrouted），建站被打了只能换 IP 或上 Cloudflare。
- **追求极致延迟**：如果你做的是游戏服务器或实时性极强的应用，CN2 GIA 的延迟相比香港本地机房还是有差距，不如直接上搬瓦工香港 CN2 GIA 顶级套餐。

一句话总结：THE PLAN 是"什么都有一点点，但什么都不极致"的全能型选手，适合绝大多数个人玩家和小站长，不适合有明确瓶颈需求的商业场景。

## THE PLAN 售罄了怎么办：当前可买的同价位替代方案

由于 THE PLAN 2024 目前官网显示缺货，THE PLAN v2 也比较难抢，这里把当前还在售、且和 THE PLAN 价位或定位接近的搬瓦工限量版套餐整理成一张表，方便你在抢不到 THE PLAN 的时候有 Plan B 可选。

| 套餐名称 | 商品 PID | 年付价格 | CPU | 内存 | SSD | 月流量 | 带宽 | 线路/机房 | 适合人群 | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| MINICHICKEN | 158 | $19 | 1 核 | 1 GB | 20 GB | 1 TB | 1 Gbps | HE（Fremont FMT2） | 极致低价入门、练手 | [购买 MINICHICKEN](https://bwh81.net/aff.php?aff=79616&pid=158) |
| MINIBOX | 151 | $29 | 1 核 | 512 MB | 10 GB | 500 GB | 1 Gbps | DC99 CN2 GIA | 想用 CN2 GIA 但预算极低 | [购买 MINIBOX](https://bwh81.net/aff.php?aff=79616&pid=151) |
| BIGGERBOX | 152 | $37 | 1 核 | 1 GB | 20 GB | 1 TB | 1 Gbps | DC99 CN2 GIA | 入门 CN2 GIA 建站 | [购买 BIGGERBOX](https://bwh81.net/aff.php?aff=79616&pid=152) |
| The DC9 Plan | 145 | $38 | 1 核 | 768 MB | 15 GB | 750 GB | 1.5 Gbps | DC9 CN2 GIA | 想专门用 DC9 CN2 GIA 线路 | [购买 The DC9 Plan](https://bwh81.net/aff.php?aff=79616&pid=145) |
| The Amsterdam Plan | 159 | $39 | 1 AMD | 1 GB | 20 GB | 1 TB | 2.5 Gbps | 荷兰 CN2 GIA / CMIN2 | 欧洲节点 + 三网优化 | [购买 The Amsterdam Plan](https://bwh81.net/aff.php?aff=79616&pid=159) |
| BIGGERBOX-PRO | 156 | $39 | 1 AMD | 1 GB | 20 GB | 1 TB | 2.5 Gbps | DC1 CN2 GIA+CMIN2 | 想要 AMD + CN2 GIA + 2.5G 带宽 | [购买 BIGGERBOX-PRO](https://bwh81.net/aff.php?aff=79616&pid=156) |
| THE CHICKEN | 130 | $39.99 | 1 核 | 1 GB | 20 GB | 1 TB | 2.5 Gbps | AS4837（Fremont FMT8） | 美西大带宽、不挑线路 | [购买 THE CHICKEN](https://bwh81.net/aff.php?aff=79616&pid=130) |
| POWERBOX | 153 | $45 | 1 核 | 1.5 GB | 30 GB | 1.5 TB | 1 Gbps | DC99 CN2 GIA | 想要稍大内存和流量 | [购买 POWERBOX](https://bwh81.net/aff.php?aff=79616&pid=153) |
| MEGABOX-PRO | 157 | $49 | 2 AMD | 2 GB | 40 GB | 2 TB | 2.5 Gbps | DC1 CN2 GIA+CMIN2 | **THE PLAN 平替首选**：同 2 核 2G，多 1TB 流量 | [购买 MEGABOX-PRO](https://bwh81.net/aff.php?aff=79616&pid=157) |
| CN2 GIA-E 10G | 94 | $49.99 | 1 核 | 512 MB | 10 GB | 500 GB | 2.5 Gbps | 14 机房 CN2 GIA-E | 想要灵活切换 14 个 CN2 GIA-E 机房 | [购买 CN2 GIA-E 10G](https://bwh81.net/aff.php?aff=79616&pid=94) |
| The DC6 Plan | 149 | $53 | 1 核 | 1 GB | 20 GB | 1 TB | 2.5 Gbps | DC6 CN2 GIA-E | 专门用 DC6 CN2 GIA-E 线路 | [购买 The DC6 Plan](https://bwh81.net/aff.php?aff=79616&pid=149) |
| OSAKA LE 40G | 146 | $79.99 | 1 核 | 2 GB | 40 GB | 2 TB | 2.5 Gbps | 日本大阪软银 JPOS_1 | 日本节点 + 大内存大流量 | [购买 OSAKA LE 40G](https://bwh81.net/aff.php?aff=79616&pid=146) |
| The Tokyo Plan v2 | 163 | $99 | 2 AMD | 2 GB | 40 GB | 1 TB | 5 Gbps | 东京 DC39v2 CMI | **THE PLAN 同价位日本版**：5Gbps 超大带宽 | [购买 The Tokyo Plan v2](https://bwh81.net/aff.php?aff=79616&pid=163) |
| HK85 LE | 121 | $79.99 | 1 核 | 1 GB | 20 GB | 500 GB | 1 Gbps | 香港 CMI | 移动用户首选香港节点 | [购买 HK85 LE](https://bwh81.net/aff.php?aff=79616&pid=121) |
| CN2 GIA-E 40G（常规版） | 132 | $89.90 | 2 核 | 2 GB | 40 GB | 1 TB | 2.5 Gbps | 14 机房 CN2 GIA-E | THE PLAN 抢不到时的"原版"同配置方案 | [购买 CN2 GIA-E 40G](https://bwh81.net/aff.php?aff=79616&pid=132) |
| FREEDOM PLAN | 133 | $89 | 2 核 | 2 GB | 40 GB | 2 TB | 2.5 Gbps | 14 个独立 IP（DC2） | 需要 14 个独立 IP 的特殊场景 | [购买 FREEDOM PLAN](https://bwh81.net/aff.php?aff=79616&pid=133) |
| Sydney LE | 126 | $99.99 | 1 核 | 1 GB | 20 GB | 500 GB | 1 Gbps | 悉尼 AS9929 | 大洋洲节点 + 9929 回程 | [购买 Sydney LE](https://bwh81.net/aff.php?aff=79616&pid=126) |

挑两个最值得重点说的：

**MEGABOX-PRO（PID 157，$49/年）是 THE PLAN 当前最接近的平替**。同样是 2 核 2GB / 40GB SSD，但流量给到 2TB（比 THE PLAN 2024 还多 1TB），用的是 AMD CPU + DC1 机房 + CN2 GIA + CMIN2 双线，带宽 2.5Gbps。唯一短板是机房只有 DC1 一个，没法像 THE PLAN 那样十八般机房随便切。如果你不需要机房切换、只想要一台稳定的三网优化 VPS，MEGABOX-PRO 性价比甚至比 THE PLAN 还高——同样 2 核 2G，便宜一半。

**The Tokyo Plan v2（PID 163，$99/年）是 THE PLAN 同价位的"日本特化版"**。配置也是 2 核 2GB / 40GB SSD / 1TB 流量，但带宽飙到 5Gbps，机房锁定东京 DC39v2 走 CMI 线路。如果你主要面向移动用户或者想跑大带宽应用，这台比 THE PLAN 的 2.5Gbps 更猛，但代价是只能在东京，不能切到美西 CN2 GIA-E。

## THE PLAN 与常规 CN2 GIA-E 套餐的本质区别

很多人会问：既然 THE PLAN 配置和 CN2 GIA-E 40G 常规版（$299.99/年）一样，那为什么不直接买常规版？答案藏在搬瓦工官方 TOS（服务条款）里。

> 限量版套餐（包括 THE PLAN、Box 系列、THE CHICKEN 等）的 CPU 分配规则是按比例限定的：5G Plan 限制为单核的 20%，10G Plan 限制为 25%，20G Plan 限制为 50%。常规 CN2 GIA-E 套餐则是全天候无限制使用所有可用核心。

翻译成人话就是：THE PLAN 在突发负载下没有常规版能扛，平时跑轻量任务感受不到差异，但一旦你跑编译、跑满 CPU 的脚本，常规版会更稳。这就是为什么 THE PLAN 便宜——它在 CPU 上做了点让步，换来了机房自由度和价格优势。

所以如果你是建站、跑代理、做日常开发，THE PLAN 完全够用，省下的 200 美元/年可以再买两台。但如果你跑高 CPU 负载的服务，建议直接上 CN2 GIA-E 40G 常规版，省心。

## 当前有效的搬瓦工优惠码整理

THE PLAN 系列本身是限量版套餐，通常不参与优惠码折扣，但如果你买的是常规套餐或部分限量版套餐，叠加优惠码可以再省一笔。以下是目前社区仍在流传的有效优惠码：

- **BWHCGLUKKB**：6.77% 循环折扣，目前最常用，购买、续费、升级都可用
- **BWH1ZBPVK**：6% 折扣，历史最稳定的码之一
- **BWH1XZOBK**：5.5% 折扣
- **ireallyreadtheterms8**：5.5% 折扣
- **BWH1NJJHL**：4.5% 折扣
- **ireadtheterms8**：4.4% 折扣
- **BWHCCNCXVV**：THE PLAN v2 专属优惠码，叠加后年付可降至 $110.90

按 6.77% 折扣算，THE PLAN v2 的 $119/年可以降到约 $110.94/年，THE PLAN 2024 的 $99/年降到约 $92.29/年（如果重新补货且支持优惠码的话）。优惠码是循环生效的，续费时同样打折，这一点很良心。

> 优惠码的使用方法：在结算页面的 "Promotional Code" 输入框填入，点击 Validate Code 即可看到折扣后的价格。建议下单前先试几个码，哪个折扣大用哪个。

## 怎么第一时间抢到 THE PLAN 补货

THE PLAN 的难买是出了名的，每次补货基本几分钟内售罄。如果你确实想入手，可以参考下面这套抢购流程：

1. **加入搬瓦工补货通知群**：搬瓦工中文网维护了几个补货通知 QQ 群和 Telegram 频道，官方补货的第一时间会推送。Telegram 频道是 @BandwagonHostNews，QQ 群号包括 200475672、280724862、852461608。
2. **关注 stock.bwg.net**：这是搬瓦工官方的库存监控页面，会实时显示哪些限量版套餐在售。
3. **提前注册账号并登录**：补货时下单速度很关键，提前注册好账号、绑好支付方式（PayPal 或信用卡），可以省掉几分钟注册时间。
4. **保存直达链接**：THE PLAN 系列即使官网下架了专题页，往往通过 PID 直达链接还是能下单（只要库存还在）。把 THE PLAN 2024（PID 147）和 THE PLAN v2（PID 131）的直达链接收藏起来，补货时直接点。
5. **季付比年付好抢**：很多人只抢年付，季付的名额往往更宽裕。如果你不确定是否长期使用，先买季付试用，后续在 KiwiVM 里升级到年付即可。

## 写在最后：THE PLAN 适合你吗

回到最初的问题——99 美元一年的 THE PLAN 值不值？

如果你的需求是个人建站、自用代理、Linux 学习、跨机房试验，且月流量在 1TB 以内，**THE PLAN 是目前市场上性价比最高的方案之一，没有之一**。同配置常规版要 299.99 美元，省下的钱够你再开两台。

如果你的需求是大流量下载、高并发商业服务、或对 CPU 稳定性有硬要求，那 THE PLAN 不是最佳选择——直接上 CN2 GIA-E 40G 常规版（PID 132，$89.90/年），或者考虑 MEGABOX-PRO（PID 157，$49/年）这种同价位但流量更大的平替。

至于现在 THE PLAN 2024 售罄的问题，要么等补货，要么先上 MEGABOX-PRO 顶替，要么直接买 THE PLAN v2（如果还能抢到）。VPS 这东西，早买早享受，等是等不出更好的价格的，限量版套餐从来都是越等越难抢。

> 想第一时间入手 THE PLAN 系列，或者已经在考虑替代方案，可以直接通过上面的直达链接下单，所有套餐都走搬瓦工官方 AFF 通道，价格不变，售后同样享受搬瓦工官方 30 天退款政策。买之前建议先在 [stock.bwg.net](https://stock.bwg.net/) 查一下实时库存，避免白跑一趟。
