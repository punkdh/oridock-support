Privacy

# 隐私政策

生效日期：2026 年 10 月 9 日 · 发布者：Denghao
适用于 OriDock Mac App Store 版本及本支持网站。

你的文件夹由你授权。部分功能在本机处理；使用技能市场或 Git 同步时，会向相应服务发送请求和必要内容。

## 1. 我们是谁

OriDock 帮助你整理本地技能文档、连接外部 Agent 目录，并同步你选择的 Git 仓库。应用无需新建 OriDock 账户，不包含广告，也不提供由发布者托管的技能存储或云端大模型翻译服务。

隐私与支持联系：[dh@denghao.org](mailto:dh@denghao.org)。本政策固定地址为 [OriDock 隐私政策](https://github.com/punkdh/oridock-support/blob/main/PRIVACY.md)。

## 2. 你授权的本地文件

你选择 OriDock 能访问的共享技能库、Agent 技能目录、项目目录和同步仓库。应用会读取文档、附件、路径与文件信息，展示技能、检查连接，并在你使用对应管理功能时修改文件或链接。

可选的 Codex 使用情况功能只读扫描你授权的本地会话历史，从中计算匹配的技能路径、时间和次数，并保留本地派生缓存与文件指纹。它不是完整的活动跟踪；未经授权或扫描不完整的结果不代表没有使用。该扫描流程不上传原始会话历史。

目录授权记录、设置、缓存、连接记录与诊断记录存储在你的 Mac 上。主程序与自带后台模块为相应功能共享部分记录。断开目录停止 OriDock 后续访问，不删除原文件，也不会撤销其他应用已有的访问权。

## 3. Git 同步与登录信息

配置并使用 Git 同步时，仓库文件内容、历史、提交作者姓名和邮箱、分支以及必要的认证请求会发送到你选择的 HTTPS Git 服务。启用后台同步后，自带后台模块也会按配置执行同步。你配置的网络代理可能处理这些连接。

远端服务控制数据保留、仓库可见性和删除方式；公开仓库可能让内容公开。发布者不提供或管理你的 Git 远端。请阅读你选择服务的政策，并在同步前检查仓库内容。

同步用户名、令牌或密码，以及代理密码使用 macOS 钥匙串保存。后台模块为相应同步功能使用已保存的凭据。应用按设计避免把令牌写入远端 URL、普通设置或诊断日志。移除已存凭据与在 Git 服务撤销令牌是两项不同操作。

## 4. 技能市场与外部服务

浏览、搜索或下载技能时，应用会联系 [skills.sh](https://skills.sh/)、[ClawHub](https://clawhub.ai/) 或 GitHub 的 API 与原始内容服务。搜索词、所选技能或仓库标识、分支、文件路径及普通网络信息会传递给对应服务；服务可看到 IP 地址等请求信息。本地网络缓存或临时文件可能保存响应内容。

这些服务是独立运营的第三方。OriDock 没有广告跟踪集成，但这不代表第三方没有日志或自己的数据处理。我们不为其保留期限作承诺；其政策、条款和实际配置决定其处理方式。GitHub 的说明见其 [隐私声明](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)；skills.sh 的说明见其 [隐私政策](https://www.skills.sh/privacy)；ClawHub 的最新说明请在其网站核对。

## 5. 系统翻译

当前翻译功能使用受支持 macOS 上 Apple 已安装的 Translation 能力。OriDock 不通过这个功能把文档发送给云端大模型。语言包下载及 Apple 系统服务有自己的条款和隐私做法，请参阅 [Apple 隐私说明](https://www.apple.com/legal/privacy/)。

## 6. 迁移、备份与诊断

你确认的迁移在本机复制所选文件，保留原件、建立应用私有备份，并记录路径、文件哈希和事务状态。迁移本身不会上传到 Git 远端，不自动启用目录权限、凭据、链接或后台服务。

单独确认的设置导入只复制允许的语言、字体和非秘密代理字段，并保留先前设置用于恢复；账号、安全字段、凭据、目录书签和启用状态不在自动导入范围内。

备份、中断副本、迁移记录与恢复目录没有自动删除期限。回滚仍保留导入副本供恢复。请检查内容后自行清理，而不要把回滚当作擦除。

同步诊断记录保留时间、简短状态、提交标识和错误信息。应用不自动上传诊断；尽管会遮盖凭据，路径、技能名与仓库信息仍可能属于私人内容。

## 7. 网站与支持邮件

发布者提供的文档内容未嵌入分析或广告代码。本文由 GitHub 托管；GitHub 页面、Cookie 和访问信息处理适用 [GitHub 隐私声明](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)。

主动给我们发邮件时，我们会收到你提供的邮箱、正文和附件，用于回复、解决问题及保留必要的支持往来。请不要发送密码、令牌、原始会话历史或完整私人库。我们不将支持邮件用于广告画像。你可联系支持邮箱请求删除或更正由发布者持有的信息；依法需要保留或处理尚未完成的记录可能暂时保留。

## 8. 你的选择与删除

你可以拒绝或断开目录访问、不使用技能市场、停用后台同步，以及移除或重新连接支持的凭据。相应功能可能因此不可用。

卸载应用不保证删除外部技能库、迁移备份、恢复副本、钥匙串记录或 Git 远端数据。请分别检查本机和远端；远端删除与历史清理由相应服务处理。发现令牌泄露时应在该服务立即撤销它。

有关发布者实际持有信息的访问、更正或删除请求，请联系 [dh@denghao.org](mailto:dh@denghao.org)。第三方服务持有的信息应向其提出请求。你也可以向适用地区的隐私监管机构寻求帮助。

## 9. 政策更新

本政策适用于 OriDock 提供服务的地区。法律规定的权利不受本政策限制。功能或数据处理有变化时，我们会在本页面更新说明和生效日期；需要重新取得许可的操作会按适用要求处理。

## English summary

OriDock is published by Denghao. Contact [dh@denghao.org](mailto:dh@denghao.org) for support or privacy requests. You choose local folders the app may access. Optional local usage analysis and migration operate on your Mac. Git synchronization sends repository content, commit information and authentication requests to the HTTPS host you select; market features contact skills.sh, ClawHub and GitHub. Those services control their own retention and privacy practices.

Credentials use macOS Keychain. There is no OriDock account, advertising integration or automatic diagnostics upload. The translation feature uses Apple's system Translation capability. Local backups and recovery copies do not have an automatic deletion deadline. Disconnecting or uninstalling does not erase external files, Keychain records or remote repositories. Support email is used to respond to your request and keep necessary correspondence. The publisher’s documentation content embeds no analytics or advertising code. GitHub hosts this document; its pages, cookies and processing of visitor requests are governed by the GitHub Privacy Statement linked above. See the Chinese policy above for the full details.

## 社区内容处理

隐藏技能、屏蔽作者以及已解析条目的公开作者关系保存在本机应用设置中，用于在刷新、重启后继续隐藏内容。可从市场的屏蔽列表解除屏蔽。应用不会把这些记录自动上传给发布者。举报功能生成含公开条目标识、来源链接及你主动填写的说明的邮件草稿；需由你确认发送。邮件由所选邮件服务处理，发布者收到的举报仅用于核查和回复，不自动附带本地文件、日志或凭据。
