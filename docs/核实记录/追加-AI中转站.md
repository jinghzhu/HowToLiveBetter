# AI 中转站两条核实记录

## 同日第三轮：AI 中转站两条（第 11 节第 19 条、第 14 节第 10 条）

| URL | 复核 | 原文引句 |
|---|---|---|
| <https://www.szzg.gov.cn/2026/xwzx/szkx/202606/t20260608_5331487.htm>（数字中国建设峰会官网，2026-06-08，「文章来源：国家安全部微信公众号」；mss.gov.cn 本机握手失败） | 是 | 「部分『AI中转站』运营资质缺失、安全防护薄弱，用户隐私泄露与数据倒卖问题时有发生」「『AI中转站』是介于用户和AI模型厂商官方服务之间的代理层」「绕过使用限制。用户甚至可以借此绕过网络访问、官方授权、跨境传输等限制」「有的甚至私自截留用户数据，倒卖给其他大模型厂商用于系统训练」「部分『AI中转站』暗藏后门。不法分子可能通过『后门』向用户设备植入恶意代码，借此窃取账号密钥、云端凭证等，甚至植入远程控制程序」「部分『AI中转站』未取得数据出境相关合规资质，未履行安全评估的法定流程，擅自将用户输入数据传输至境外服务器」「选择官方直连、正规授权、安全合规的平台，不使用无明确来源、无运营资质、无安全保障的『三无』平台」「提前对个人隐私、项目资料等敏感数据进行脱敏处理，同时做好密钥管理，定期更换凭证」「如遇到异常扣费、无故封号、数据异常等问题，应立即停止使用、修改密钥、查杀病毒、留存证据」 |
| <https://www.chinanews.com/cj/2026/06-22/10644787.shtml>（中国新闻周刊记者孟倩，发于 2026.6.22 总第 1240 期；存档 <https://web.archive.org/web/20261005042903/https://www.chinanews.com/cj/2026/06-22/10644787.shtml>，已复核存档含正文） | 是 | 「2026年5月，网名为『瓜皮』的上海AI中转站站长在技术社区发布了一份关停声明，透露自己因非法获取API模型，被上海警方刑事拘留37天，目前处于取保候审状态，『将来肯定会被判刑』，他已经退赔退赃，还要缴纳罚金」「批量注册或购买ChatGPT、Claude等境外大模型的订阅账号，攒成一个『号池』；在海外架一台服务器做跳板，把接口封装成标准API，再以远低于官方的价格转卖给国内用户」。同文「1个站点直接侵入研究者的ETH钱包，损失高达50万美元」与论文原文不符，没用；律师「3 到 7 年」的说法没用 |
| <https://arxiv.org/abs/2604.08407>（arXiv 预印本，2026-04-09；正文页眉标 CCS 2026） | 是 | 摘要：「Across 28 paid routers purchased from Taobao, Xianyu, and Shopify-hosted storefronts and 400 free routers collected from public communities, we find 1 paid and 8 free routers actively injecting malicious code, 2 deploying adaptive evasion triggers, 17 touching researcher-owned AWS canary credentials, and 1 draining ETH from a researcher-owned private key」。正文：「restricting payload delivery to autonomous 『YOLO mode』 sessions」「For the single on-chain drain reported in Section 5.3, the value lost was below US$50 at the time of transfer」「python -m pip install reqeusts flask pyyaml」；第一作者单位 University of California, Santa Barbara |

没有找到的：上海案的警方通报或判决；中央网信办「清朗·整治AI应用乱象」两阶段 14 类问题原文（cac.gov.cn 2026-04-30）里没有点名中转站，没引。

定级与标签：
- 第 11 节第 19 条 C。法律后果只有媒体报道和当事人自述。口径自由，按「避免刑责」定大，刑事拘留本身已是刑事程序。钱=0，时间=少，毅力=些。
- 第 14 节第 10 条 B。官方提示加一项测量研究，研究是预印本。口径按本节「个人信息」归自由；没有金额可套，后果凭判断定中。钱=少（官方直连更贵）。
