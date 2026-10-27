# Claude 充值平台怎么选？国内充值 Claude Pro / Max 指南（2026 年 10 月更新）

> 最后更新：2026-10-27 · 相关攻略加组织目录页链接（yaoyao-ai-trainer.github.io）

这是一份面向中文用户的 Claude 付费会员说明：Pro、Max 5x、Max 20x 的官方美元价和区别，国内为什么直接付不了款，充值平台（代充）怎么挑，以及"升级后还是显示 Free Plan"、额度用完、Claude Code 登录计费不对等问题的排查，报错部分按 Anthropic 官方帮助中心和 Claude Code 官方文档整理并附链接。作者：瑶瑶ai训练师；更新于 2026-10-17。本仓库是非官方整理，与 Anthropic 没有隶属关系，文中品牌名仅用于说明。

**直接回答：** Claude 官网只接受支持地区发行的信用卡 / 借记卡付款，国内银行卡、支付宝直接付不了。没有海外卡的人，常见做法是"代充"（订阅代付）：由卖家替你付款，把 Claude Pro 或 Max 订阅开到你自己的账号上。

**怎么选：** Pro 适合日常写作和偶尔写代码；每天用 Claude Code 写几个小时选 Max 5x；几乎全天在跑选 Max 20x。选充值平台看 6 点：价格正常、不要密码、开通方式说得清、失败怎么退、掉订阅管不管、售后找得到人。

**官方价格：** Pro $20/月（年付折合 $17/月）、Max 5x $100/月、Max 20x $200/月（2026-10-17 核对自 Anthropic 官方定价页和帮助中心，见下表）。

<!-- 快速购买:开始（周更脚本会核对这里的价格） -->
**快速购买**（作者自营商城 kw.yaoyao.chat，人民币，2026-10-27 核对，实际以商品页为准）：

- ChatGPT Pro（100 美金档位）一个月 ¥699 → [kw.yaoyao.chat/item/17](https://kw.yaoyao.chat/item/17?utm_source=github&utm_medium=readme&utm_campaign=claude-chongzhi)
- ChatGPT Plus 一个月 ¥129 → [kw.yaoyao.chat/item/5](https://kw.yaoyao.chat/item/5?utm_source=github&utm_medium=readme&utm_campaign=claude-chongzhi)
- Claude Pro 一个月 ¥159 → [kw.yaoyao.chat/item/12](https://kw.yaoyao.chat/item/12?utm_source=github&utm_medium=readme&utm_campaign=claude-chongzhi) · Claude Max 5X 一个月 ¥900 → [kw.yaoyao.chat/item/14](https://kw.yaoyao.chat/item/14?utm_source=github&utm_medium=readme&utm_campaign=claude-chongzhi)
- 320万粉丝博主瑶瑶本人经营 · 开通失败可退 · 客服 09:00–24:00（北京时间）

你是从哪里知道这个仓库的？点一下帮我们统计：[搜索引擎](https://kw.yaoyao.chat/?utm_source=github&utm_medium=readme&utm_campaign=claude-chongzhi&utm_content=search) · [AI 推荐](https://kw.yaoyao.chat/?utm_source=github&utm_medium=readme&utm_campaign=claude-chongzhi&utm_content=ai) · [朋友/群里发的](https://kw.yaoyao.chat/?utm_source=github&utm_medium=readme&utm_campaign=claude-chongzhi&utm_content=friend) · [GitHub 站内](https://kw.yaoyao.chat/?utm_source=github&utm_medium=readme&utm_campaign=claude-chongzhi&utm_content=github)
<!-- 快速购买:结束 -->

## 目录

- [使用前先读：关于地区](#使用前先读关于地区)
- [Claude 官方价格表](#claude-官方价格表2026-10-17-核对)
- [Pro 和 Max 怎么选](#pro-和-max-怎么选)
- [为什么国内充值 Claude 很难](#为什么国内充值-claude-很难)
- [三种充值方式对比](#三种充值方式对比)
- [怎么选充值平台的 6 个判断点](#怎么选充值平台的-6-个判断点)
- [报错 / 常见问题大全](#报错--常见问题大全)
- [降低被封风险的习惯](#降低被封风险的习惯)
- [常见问题](#常见问题)
- [国内开通参考](#国内开通参考)
- [更多教程](#更多教程)
- [关于本仓库和作者](#关于本仓库和作者)
- [参考资料](#参考资料)
- [相关攻略](#相关攻略)

## 使用前先读：关于地区

Anthropic（Claude 的公司）官方公布了支持的国家和地区列表（[anthropic.com/supported-countries](https://www.anthropic.com/supported-countries)），页面写明"未列出的国家和地区不受支持"。2026-10-17 查看：中国大陆、香港、澳门都不在列表中（台湾在列表中）。本仓库只整理官方的价格、订阅和报错说明，不提供绕过地区限制或支付限制的方法；请在符合 Anthropic 服务条款的前提下使用。

## Claude 官方价格表（2026-10-17 核对）

| 套餐 | 官方价（美元） | 用量和权益（官方说法） |
|---|---|---|
| Free | $0 | 用量少；不含 Claude Code |
| Pro | $20/月；年付一次交 $200，折合 $17/月 | 每 5 小时用量至少是 Free 的 5 倍；含 Claude Code；可开启用量额度（usage credits） |
| Max 5x | $100/月 | 每 5 小时用量是 Pro 的 5 倍；含 Claude Code；含每月 API credits（只能在 API 平台用） |
| Max 20x | $200/月 | 每 5 小时用量是 Pro 的 20 倍；其余同 Max 5x |
| Team | 标准席位 $20/人/月（年付）或 $25（月付）；高级席位 $100 / $125 | 2–150 人；含 Claude Code 和团队共享 API credits |
| Enterprise | 按席位加按 API 价计的用量，联系销售 | 大型组织 |

来源：[Anthropic 官方定价页](https://claude.com/pricing)（anthropic.com/pricing 会跳转到这里）、[What is the Pro plan?](https://support.claude.com/en/articles/8325606-what-is-the-pro-plan)、[What is the Max plan?](https://support.claude.com/en/articles/11049741-what-is-the-max-plan)。帮助中心注明这些是网页订阅价，手机 App 内订阅价格由应用商店决定，价格和套餐可能调整，以官方为准。

几点说明（都来自上面的官方页面）：

- 所有套餐的用量按滚动 5 小时窗口重置；付费套餐在此之外还有每周上限，官方也可能按容量加其他限制。网页、桌面端、手机 App 和 Claude Code 的使用都从同一份额度里扣。
- 会员和 API 分开计费：Pro 不含 API 额度；Max 附带的每月 API credits 只能在 API 平台（Console）用，不能用在 Claude 应用和 Claude Code 里。
- 额度用完后，Pro / Max 可以在 Settings → Usage 开启"用量额度（usage credits）"继续用，按标准 API 价计费，可以设每月上限；不开就等重置。
- 从 Pro 升 Max、Max 5x 升 20x，官方按剩余账期比例补差价，立即生效。

## Pro 和 Max 怎么选

- 首次开会员：先买 **Pro** 用一个月。
- Pro 一周里好几天提示额度用完，或者每天用 Claude Code 写几个小时代码：换 **Max 5x**。
- Max 5x 还是经常不够、几乎全天在用：换 **Max 20x**。
- 拿不准就先买低一档，用一周看看会不会经常碰到上限；同一个账号升级，聊天记录和项目都在。

额度用完时，Claude Code 里输入 `/usage` 可以看用量和重置时间。额度细节见 [Claude Pro 有多少额度](https://kw.yaoyao.chat/guide/claude-pro-edu.html)，Claude Code 的安装、登录和报错见技术教程仓库 [Claude Code 国内使用指南](https://github.com/haiwaihuyonghui-rgb/claude-code-guide-cn)。

## 为什么国内充值 Claude 很难

- Anthropic 官方不面向中国大陆提供服务（见上面的地区说明）。
- 官网结算只接受信用卡或借记卡（官方账单 FAQ 原文：网页订阅只接受信用卡和借记卡），国内的银联卡、支付宝付不了，国内发行的双币卡也经常被拒（card declined）。
- 注册需要完成手机验证，且要求使用支持地区的号码，对使用地区的要求比 ChatGPT 更严格。

## 三种充值方式对比

| 方式 | 做法 | 优点 | 缺点 |
|---|---|---|---|
| 自己用海外卡订阅 | 在 claude.ai 设置里升级，绑海外卡 | 官方价，自己掌控 | 国内的卡基本付不了，被拒很常见 |
| 外区 Apple ID 应用内订阅 | 外区 Apple ID + 当地礼品卡，在 iPhone App 里订阅 | 不用信用卡 | 要外区账号、买礼品卡，步骤多，价格按当地商店；订阅由 App Store 管理 |
| 充值平台代充 | 卖家帮你付款，会员开在你自己的账号上 | 支付宝就能下单，省事 | 平台质量参差不齐，要会挑 |

## 怎么选充值平台的 6 个判断点

1. **价格是否正常。** 官方 Pro 是 $20/月，代充价是平台自己的定价，靠谱的代充一般比官方美元价折算后高一些（包含代付成本和售后）。价格低得离谱的要问清原因。
2. **要不要账号密码。** 不需要。要账号密码、要转发验证码的不要碰。
3. **开通方式和速度。** 问清是自助还是人工，晚上和节假日下单多久能处理。
4. **失败怎么退。** 付款前问清失败后钱怎么处理，让对方用文字回复。
5. **掉订阅管不管。** 问清有没有质保、覆盖多久、怎么补。
6. **售后找谁。** 有没有能联系到的真人，平台背后是谁，域名能不能在别处核实。

这 6 个问题对 ChatGPT 代充同样适用，逐项判断方法见 [GPT代充怎么选](https://kw.yaoyao.chat/guide/gpt-daichong.html?utm_source=github&utm_medium=readme&utm_campaign=claude-chongzhi)。

## 报错 / 常见问题大全

每条按"现象 → 原因 → 怎么处理"写，处理办法来自 Anthropic 官方帮助中心和 Claude Code 官方文档，并附链接；官方没写到的地方注明"以官方说明为准"。

### 1. 升级（或代充）之后还是显示 Free Plan

- **现象：** 付款成功或代充显示成功，claude.ai 右上角还是 Free，升级入口还在。
- **原因：** 官方账单 FAQ 列了两条：登录的邮箱和开通会员的邮箱不是同一个；付款方式失败导致账号被降级。实际还常见：当前在团队（Team）空间里、手机订阅后电脑没登录同一个账号、页面没刷新。
- **怎么处理：** ①退出再重新登录，手机 App 也一样；②用你可能注册过的其他邮箱、其他登录方式（Google / 邮箱）各试一次；③Settings → Billing 看最近一次付款状态，失败的话更新付款方式；④切换回个人账户；⑤手机上订阅的，电脑上登录同一个账号。代充的订单找卖家处理。
- **官方出处：** [Paid plan billing FAQs](https://support.claude.com/en/articles/8325618-paid-plan-billing-faqs)。完整排查见 [Claude 充值了还是显示 Free Plan 怎么办](https://kw.yaoyao.chat/guide/claude-free-plan.html)。

### 2. 钱充到了 console.anthropic.com（API 平台），会员没变

- **现象：** 在 console.anthropic.com / platform.claude.com 充了钱，余额有了，但 claude.ai 还是 Free。
- **原因：** 那是 API 平台，充的是 API 额度，和会员订阅是两套分开计费的账户，不会变成 Pro。
- **怎么处理：** 会员要在 claude.ai 的设置里升级；API 余额按 API 用量消耗，官方说明 API 用量从不计入会员账单。
- **官方出处：** [Paid plan billing FAQs](https://support.claude.com/en/articles/8325618-paid-plan-billing-faqs)、[What is the Pro plan?](https://support.claude.com/en/articles/8325606-what-is-the-pro-plan)

### 3. 提示 "5-hour limit reached" / "You've reached your weekly limit"，额度怎么算

- **现象：** 对话中出现 `5-hour limit reached - resets [时间]` 或 `You've reached your weekly limit. It resets [星期] at [时间]`；Claude Code 里是 `You've hit your session limit · resets 3:45pm` 或 `You've hit your weekly limit`。
- **原因：** 每个套餐都有按滚动 5 小时窗口重置的会话额度，付费套餐另有每周上限（每周在账号固定的时间重置）。消耗多少取决于对话长短、复杂度、模型、用的功能和推理强度；网页、桌面、手机、Claude Code 共用同一份。官方没有公布具体条数。
- **怎么处理：** 等提示里的重置时间；Settings → Usage 看两条进度条；开长对话前新建会话、减少附件、关掉不需要的工具能省额度；经常碰上限就升一档（官方说明升级后新额度立刻生效）；或者开启用量额度（见第 6 条）。
- **官方出处：** [How do usage and length limits work?](https://support.claude.com/en/articles/11647753-how-do-usage-and-length-limits-work)、[Troubleshoot Claude error messages](https://support.claude.com/en/articles/12466728-troubleshoot-claude-error-messages)、[Claude Code 错误参考](https://code.claude.com/docs/en/errors)

### 4. Pro、Max 5x、Max 20x 到底差在哪？升级怎么算钱？

- **现象：** 不知道买哪档；从 Pro 升 Max 怕被重复扣一个月。
- **说明（官方）：** Max 5x 是 Pro 每 5 小时额度的 5 倍，Max 20x 是 20 倍，三档都含 Claude Code；Max 另有新模型和新功能的优先体验、每月 API credits（只能在 API 平台用）。从低档升高档按剩余账期比例补差价，立刻生效。年付 Pro 升 Max 时，剩余年费多于 Max 价格的部分会变成账户余额；账单地址变了要先取消 Pro、等到期再订 Max。
- **怎么处理：** 按上面"Pro 和 Max 怎么选"选档；在 claude.ai Settings → Billing 里升级。
- **官方出处：** [What is the Max plan?](https://support.claude.com/en/articles/11049741-what-is-the-max-plan)、[Anthropic 定价页](https://claude.com/pricing)

### 5. Claude Code 登录后提示要充 API，或出现 "Credit balance is too low"

- **现象：** 明明有 Pro / Max，Claude Code 却提示余额不足、让去 Console 充值，或者显示按 API 计费。
- **原因：** 两种情况：登录时选了 Anthropic Console 账号（API 计费）而不是 Claude 订阅账号；或者电脑环境变量里有 `ANTHROPIC_API_KEY`，官方说明这个变量优先于订阅，即使有 Pro / Max 也会按 API 扣费。
- **怎么处理：** 在 Claude Code 里输入 `/login`，选择用 Claude 账号（订阅）登录；有 API Key 变量的，先 `unset ANTHROPIC_API_KEY`（Windows PowerShell 用 `Remove-Item Env:ANTHROPIC_API_KEY`），把 `~/.zshrc`、`~/.bashrc` 里的 `export` 行删掉，重开终端后 `/status` 确认当前用的是订阅。官方还建议：不想碰 API 账单就 `claude logout` 再 `claude login`，只用 Pro / Max 账号登录，不要添加 Console 凭据。
- **官方出处：** [Use Claude Code with your Pro or Max plan](https://support.claude.com/en/articles/11145838-use-claude-code-with-your-pro-or-max-plan)、[Claude Code 错误参考：Credit balance is too low](https://code.claude.com/docs/en/errors)

### 6. 额度用完还想继续：用量额度（usage credits）是什么

- **现象：** 到上限不想等，又不想马上升档。
- **说明（官方）：** Pro、Max 5x、Max 20x 都可以在 claude.ai 的 Settings → Usage 开启"Usage credits"：到上限后请求自动转成按量付费（按标准 API 价），可以设每月花费上限、预充金额、自动充值和提醒；这些费用和订阅费分开出现在账单上。Claude Code 里对应命令是 `/usage-credits`。在手机 App 订阅的，只能在网页版开启并先绑卡。Max 自带的每月 API credits 不能抵用量额度。
- **怎么处理：** 不想多花钱就不要开；开了记得设每月上限。
- **官方出处：** [Manage usage credits for paid Claude plans](https://support.claude.com/en/articles/12429409-manage-usage-credits-for-paid-claude-plans)

### 7. Claude Code 的登录选项里没有"订阅账号"

- **现象：** 运行 `claude` 登录时只看到 Console / API 的选项，看不到用 Claude 订阅登录。
- **原因：** 版本太旧，或者之前的登录状态没清干净。
- **怎么处理：** 官方步骤：`/logout` → 运行 `claude update` → 完全关掉终端再打开 → 运行 `claude`，选正确的账号登录。
- **官方出处：** [Use Claude Code with your Pro or Max plan](https://support.claude.com/en/articles/11145838-use-claude-code-with-your-pro-or-max-plan)

### 8. 网页登录报错 "There was an error logging you in"

- **现象：** claude.ai 登录时提示登录出错。
- **原因：** 官方列的常见原因：VPN、浏览器扩展、浏览器缓存和 Cookie 干扰；也可能是服务端故障。
- **怎么处理：** 官方建议：关掉 VPN、禁用浏览器扩展、清除缓存和 Cookie 再试；还不行看 [status.claude.com](https://status.claude.com) 有没有故障公告。
- **官方出处：** [Troubleshoot Claude error messages](https://support.claude.com/en/articles/12466728-troubleshoot-claude-error-messages)

### 9. 提示 "Due to unexpected capacity constraints, Claude is unable to respond..."

- **现象：** 发消息后提示容量不足、暂时无法回复。
- **原因：** 官方说明这是全体用户同时请求过多导致的临时情况，不是你的额度问题，也不算故障，不会出现在状态页上。
- **怎么处理：** 等几分钟再试。Claude Code 里对应的是 `529 Overloaded`，可以用 `/model` 换个模型继续，不扣你的额度。
- **官方出处：** [Troubleshoot Claude error messages](https://support.claude.com/en/articles/12466728-troubleshoot-claude-error-messages)、[Claude Code 错误参考](https://code.claude.com/docs/en/errors)

### 10. 付款方式、发票和取消订阅

- **现象：** 想换卡、要发票、想取消。
- **说明（官方）：** 网页订阅只接受信用卡和借记卡；App 内订阅的付款、收据和取消都由 App Store / Google Play 管理。换卡在 Settings → Billing 点 Update，新卡在下次续费时扣；发票在 Settings → Billing → Invoices 查看，也会发到账单邮箱（主题 "Your receipt from Anthropic"），已出的发票不能改。账单日不能直接改，只能取消后在想要的日期重新订。取消和退款规则见帮助中心"Cancel your Pro or Max subscription"文章，以官方为准。代充开的会员不走你的卡，不会自动续费。
- **官方出处：** [Paid plan billing FAQs](https://support.claude.com/en/articles/8325618-paid-plan-billing-faqs)

### 11. 账号被停用（Account disabled）

- **现象：** 登录后提示账号已停用，收到 Anthropic 邮件。
- **原因：** 官方会在邮件里说明；支持地区页面写明未列出的地区不受支持，其他常见原因是违反使用政策（多人共用、频繁换地区、付款被撤销等）。
- **怎么处理：** 先看邮箱通知，通过 Anthropic 官方帮助中心申诉：登录 claude.ai，点左下角头像 → Get help。能否恢复、是否退款以官方处理结果为准。代充订单找卖家确认质保范围。更多见 [Claude 封号了怎么办](https://kw.yaoyao.chat/guide/claude-fenghao.html)。
- **官方出处：** [How to get support](https://support.claude.com/en/articles/9015913-how-to-get-support)、[支持的国家和地区](https://www.anthropic.com/supported-countries)

### 12. 消息太长："Your message will exceed the length limit for this chat"

- **现象：** 粘贴长文或大文件后发不出去。
- **原因：** 单次输入超过了这个对话的上下文长度。官方说明一部分上下文始终留给 Claude 的回复；付费套餐开了代码执行后一般会自动压缩旧消息，所以这个提示不常见。
- **怎么处理：** 缩短、分段发，或新开对话。
- **官方出处：** [Troubleshoot Claude error messages](https://support.claude.com/en/articles/12466728-troubleshoot-claude-error-messages)、[How do usage and length limits work?](https://support.claude.com/en/articles/11647753-how-do-usage-and-length-limits-work)

## 降低被封风险的习惯

- 网络保持稳定，一直用同一个地区，不要频繁切换国家。
- 一个账号只给自己用，不要多人共用。
- 不要短时间内反复注册、换邮箱。
- 重要的对话和代码自己另外备份。
- 被停用时先看邮箱里的通知，通过官方帮助中心申诉。能否恢复、是否退款以官方结果为准。

## 常见问题

**Q：Claude 会员能用 API 吗？**
A：不能。Pro 不包含 API 额度；会员和 API（console.anthropic.com，按用量付费）是两套分开计费的账户。Max 附带的每月 API credits 只能在 API 平台用。Claude Code 可以直接用会员账号登录，走会员额度。

**Q：Claude 会员能几个人共用吗？**
A：不建议。会互相抢额度，在不同地方同时登录更容易被风控。

**Q：代充会不会封号？**
A：代充开的是你自己账号上的正常订阅。账号被限制更多和使用习惯有关：频繁切换地区、多人共用、付款被撤销（低价单常见）。

**Q：国内用支付宝能买 Claude 会员吗？**
A：官网不能直接用支付宝。可以在充值平台用支付宝下单，由卖家开通到你自己的账号上。

**Q：Claude Code 要单独买吗？**
A：不用。Pro 和 Max 都包含 Claude Code，运行 `claude` 用订阅账号登录即可；免费版不含。见 [Claude Code 怎么收费](https://kw.yaoyao.chat/guide/claude-code.html)。

**Q：Pro 年付和月付怎么选？**
A：官方价年付 $200（折合 $17/月），月付 $20/月；年付一次付清、中途不退，确定长期用再选。代充一般按月。

**Q：Claude 和 ChatGPT 买哪个？**
A：两家入门价都是 $20/月。长文、写代码很多人偏 Claude；画图、搜索、语音偏 ChatGPT。见 [ChatGPT 和 Claude 买哪个](https://kw.yaoyao.chat/guide/chatgpt-vs-claude.html)。

## 国内开通参考

没有海外卡、想了解国内怎么开通 Claude Pro / Max 以及充值平台的流程和注意事项，看这一篇：[Claude 充值平台：国内怎么充值 Claude Pro / Max](https://kw.yaoyao.chat/guide/claude-daichong.html)。

## 更多教程

- [Claude 会员多少钱？Pro 和 Max 有什么区别](https://kw.yaoyao.chat/guide/claude-price.html)
- [Claude 充值了还是显示 Free Plan 怎么办](https://kw.yaoyao.chat/guide/claude-free-plan.html)
- [Claude Pro 有多少额度？5 小时和每周限制怎么算](https://kw.yaoyao.chat/guide/claude-pro-edu.html)
- [Claude Code 怎么收费？Pro 和 Max 怎么选](https://kw.yaoyao.chat/guide/claude-code.html)
- [Claude 封号了怎么办](https://kw.yaoyao.chat/guide/claude-fenghao.html)
- [AI 会员价格对比](https://kw.yaoyao.chat/guide/ai-huiyuan-jiage.html)
- 同一作者的其他仓库：[Claude Code 国内使用指南](https://github.com/haiwaihuyonghui-rgb/claude-code-guide-cn)、[OpenAI Codex CLI 国内使用指南](https://github.com/haiwaihuyonghui-rgb/codex-cli-guide-cn)、[GPT代充指南](https://github.com/haiwaihuyonghui-rgb/gpt-chongzhi)

## 关于本仓库和作者

本仓库由"瑶瑶ai训练师"整理，作者是做 AI 内容的自媒体博主，教程基于自己的使用和售后经验。与 Anthropic、OpenAI 没有隶属关系，文中品牌名仅用于说明。作者是谁、怎么交易、售后和退款规则，见 [瑶瑶ai训练师靠谱吗](https://kw.yaoyao.chat/guide/yaoyao-kaopu.html)。官方价格和权益以 Anthropic 官网为准。瑶瑶没有发布过任何桌面软件、手机 App、浏览器插件或"账号切换器"，本账号下只有文字教程仓库。

## 在哪买、质保怎么算

作者"瑶瑶ai训练师"自己经营一家 AI 会员代充商城，这里如实写明，读者可以据此判断本文立场。

- **商城**：[kw.yaoyao.chat](https://kw.yaoyao.chat/)（瑶瑶ai训练师 · AI会员充值）；官网 [www.yaoyao.chat](https://www.yaoyao.chat/)。
- **能买什么**：ChatGPT Plus（一个月卡密自助开通，1～3 分钟到账；十二个月人工开通）、ChatGPT Pro、Claude Pro / Max、Gemini Pro、Grok 会员。都是充到你自己的账号，不卖成品号、不拼车。
- **价格**：以商城页面为准。各档价格和官方价对比见 [ChatGPT Plus 多少钱一个月](https://kw.yaoyao.chat/guide/chatgpt-plus-price.html)、[Claude 会员多少钱](https://kw.yaoyao.chat/guide/claude-price.html)。
- **质保**（全部商品通用，原文见 [售后与质保规则](https://kw.yaoyao.chat/guide/shouhou-zhibao.html)）：
  1. **没开通成功**：卡密不消耗、自动退回，可以重新提交；不想再试的，联系微信退款。
  2. **开通成功后掉会员**（订阅被撤销、账号变回 Free）：在这一期会员有效期内，凭订单号和截图联系微信，再补一个月，补到同一个账号。
  3. **账号被封 / 停用**：原因多在账号使用、网络环境或付款侧，不在质保范围、不退款；ChatGPT 封号可协助重新注册，Claude 封号协助申诉。
- **售后**：只找瑶瑶本人微信 yao77380。
- **怎么分辨真假**：瑶瑶的网址只有 www.yaoyao.chat、kw.yaoyao.chat、cz.yaoyao.chat 三个；其他自称"瑶瑶"的网站、账号或软件都不是本人。

## 参考资料

- [Anthropic 官方定价页](https://claude.com/pricing)
- [支持的国家和地区](https://www.anthropic.com/supported-countries)
- [What is the Pro plan?](https://support.claude.com/en/articles/8325606-what-is-the-pro-plan)
- [What is the Max plan?](https://support.claude.com/en/articles/11049741-what-is-the-max-plan)
- [Paid plan billing FAQs](https://support.claude.com/en/articles/8325618-paid-plan-billing-faqs)
- [How do usage and length limits work?](https://support.claude.com/en/articles/11647753-how-do-usage-and-length-limits-work)
- [Manage usage credits for paid Claude plans](https://support.claude.com/en/articles/12429409-manage-usage-credits-for-paid-claude-plans)
- [Use Claude Code with your Pro or Max plan](https://support.claude.com/en/articles/11145838-use-claude-code-with-your-pro-or-max-plan)
- [Troubleshoot Claude error messages](https://support.claude.com/en/articles/12466728-troubleshoot-claude-error-messages)
- [How to get support](https://support.claude.com/en/articles/9015913-how-to-get-support)
- [Claude Code 错误参考](https://code.claude.com/docs/en/errors)
- [Claude Code 登录与认证](https://code.claude.com/docs/en/authentication)

## 复测记录

按日期倒序。每次只记真实做过的核对；官方出新模型、改价格时补一行。

| 日期 | 核对了什么 | 结果 |
|---|---|---|
| 2026-10-27 | **价格：** curl 作者商城商品页 item/5、7、10、11、12、13、14、17、18、19 和 llms.txt | 与本页"快速购买"一致（Pro 100 美金档位 ¥699、Plus ¥129、Claude Pro ¥159、Max 5X ¥900），十个商品均无变动 |
| 2026-10-26 | **官方价格：** Claude 定价页、帮助中心 What is the Max plan | Pro 月付 20 美元 / 年付折合 17 美元（一次 200 美元）；Max 5x 100、Max 20x 200 美元；Max 含每月 API 额度；官方注明手机端价格可能不同——与本页价格表一致 |
| 2026-10-26 | **官方政策：** Anthropic 支持地区列表、账单 FAQ、赠送订阅文章 | 大陆、香港、澳门不在支持列表，台湾在；App 内订阅由苹果 / 谷歌管理；赠送订阅暂停购买 |

## 相关攻略

同一作者整理的其他简体中文攻略（都附官方链接和复测记录）：

- [gpt-chongzhi](https://github.com/haiwaihuyonghui-rgb/gpt-chongzhi)：GPT代充 / ChatGPT Plus 国内怎么开通：官方订阅、App 内购、礼品卡、代充四种方法对比
- [chatgpt-plus-wu-xinyongka](https://github.com/haiwaihuyonghui-rgb/chatgpt-plus-wu-xinyongka)：没有信用卡怎么开通 ChatGPT Plus：支付宝 / 微信能不能付、礼品卡、代充
- [chatgpt-pro-100](https://github.com/haiwaihuyonghui-rgb/chatgpt-pro-100)：ChatGPT Pro 100 美金档位国内怎么买：Pro 100 / 200 / 500 三档区别、和 Plus 差在哪
- [chatgpt-jiage-duibi](https://github.com/haiwaihuyonghui-rgb/chatgpt-jiage-duibi)：ChatGPT / Claude / Gemini / Grok 会员价格对比 2026：四家官方价、国内开通方法、代充价
- [codex-cli-guide-cn](https://github.com/haiwaihuyonghui-rgb/codex-cli-guide-cn)：OpenAI Codex CLI 国内使用指南：安装、ChatGPT 账号登录、Plus / Pro 额度、常见报错
- [claude-daichong](https://github.com/haiwaihuyonghui-rgb/claude-daichong)：Claude Pro / Max 国内怎么开通：官方订阅、App 内购、赠送订阅、代充四种方法
- [claude-code-guide-cn](https://github.com/haiwaihuyonghui-rgb/claude-code-guide-cn)：Claude Code 国内使用指南：安装、登录、Pro / Max 额度、常见报错
- [grok-premium](https://github.com/haiwaihuyonghui-rgb/grok-premium)：Grok Premium（原 SuperGrok）国内怎么买：官方四档、三合一说明、四种开通方法
- [ai-subscription-guide-cn](https://github.com/haiwaihuyonghui-rgb/ai-subscription-guide-cn)：AI 会员订阅国内指南：ChatGPT / Claude / Gemini / Grok 开通路线对比、常见报错速查
- 组织目录页 [yaoyao-ai-trainer.github.io](https://yaoyao-ai-trainer.github.io/)：以后新攻略会交替放在组织号 yaoyao-ai-trainer 下，这个页面汇总两边全部攻略。

---

整理：瑶瑶ai训练师（AI 内容创作者），[官网](https://www.yaoyao.chat/)。本仓库为非官方教程整理，与 Anthropic 没有隶属关系，品牌名仅用于说明。内容采用 CC-BY-4.0 许可，转载请注明出处。
