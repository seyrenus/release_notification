# Repositories with Latest Commits within 7 days

### 2025-01-16T15:51:33Z [**astral-sh/ruff**](https://github.com/astral-sh/ruff)

```
## Release Notes  ### Preview features  - \[`airflow`\] Fix typo "security_managr" to "security_manager" (`AIR303`) ([#15463](https://github.com/astral-sh/ruff/pull/15463)) - \[`airflow`\] extend and fix AIR302 rules ([#15525](https://github.com/astral-sh/ruff/pull/15525)) - \[`fastapi`\] Handle parameters with `Depends` correctly (`FAST003`) ([#15364](https://github.com/astral-sh/ruff/pull/15364)) - \[`flake8-pytest-style`\] Implement pytest.warns diagnostics (`PT029`, `PT030`, `PT031`) ([#15444](https://github.com/astral-sh/ruff/pull/15444)) - \[`flake8-pytest-style`\] Test function parameters with default arguments (`PT028`) ([#15449](https://github.com/astral-sh/ruff/pull/15449)) - \[`flake8-type-checking`\] Avoid false positives for `|` in `TC008` ([#15201](https://github.com/astral-sh/ruff/pull/15201))  ### Rule changes  - \[`flake8-todos`\] Allow VSCode GitHub PR extension style links in `missing-todo-link` (`TD003`) ([#15519](https://github.com/astral-sh/ruff/pull/15519)) - \[`pyflakes`\] Show syntax error message for `F722` ([#15523](https://github.com/astral-sh/ruff/pull/15523))  ### Formatter  - Fix curly bracket spacing around f-string expressions containing curly braces ([#15471](https://github.com/astral-sh/ruff/pull/15471)) - Fix joining of f-strings with different quotes when using quote style `Preserve` ([#15524](https://github.com/astral-sh/ruff/pull/15524))  ### Server  - Avoid indexing the same workspace multiple times ([#15495](https://github.com/astral-sh/ruff/pull/15495)) - Display context for `ruff.configuration` errors ([#15452](https://github.com/astral-sh/ruff/pull/15452))  ### Configuration  - Remove `flatten` to improve deserialization error messages ([#15414](https://github.com/astral-sh/ruff/pull/15414))  ### Bug fixes  - Parse triple-quoted string annotations as if parenthesized ([#15387](https://github.com/astral-sh/ruff/pull/15387)) - \[`fastapi`\] Update `Annotated` fixes (`FAST002`) ([#15462](https://github.com/astral-sh/ruff/pull/15462)) - \[`flake8-bandit`\] Check for `builtins` instead of `builtin` (`S102`, `PTH123`) ([#15443](https://github.com/astral-sh/ruff/pull/15443)) - \[`flake8-pathlib`\] Fix `--select` for `os-path-dirname` (`PTH120`) ([#15446](https://github.com/astral-sh/ruff/pull/15446)) - \[`ruff`\] Fix false positive on global keyword (`RUF052`) ([#15235](https://github.com/astral-sh/ruff/pull/15235))   ## Contributors - [@AlexWaygood](https://github.com/AlexWaygood) - [@BurntSushi](https://github.com/BurntSushi) - [@Daverball](https://github.com/Daverball) - [@Garrett-R](https://github.com/Garrett-R) - [@Glyphack](https://github.com/Glyphack) - [@InSyncWithFoo](https://github.com/InSyncWithFoo) - [@Lee-W](https://github.com/Lee-W) - [@MichaReiser](https://github.com/MichaReiser) - [@cake-monotone](https://github.com/cake-monotone) - [@carljm](https://github.com/carljm) - [@charliermarsh](https://github.com/charliermarsh) - [@dhruvmanila](https://github.com/dhruvmanila) - [@dylwil3](https://github.com/dylwil3) - [@ntBre](https://github.com/ntBre) - [@renovate](https://github.com/renovate) - [@sharkdp](https://github.com/sharkdp) - [@tjkuson](https://github.com/tjkuson)  ## Install ruff 0.9.2  ### Install prebuilt binaries via shell script  sh curl --proto '=https' --tlsv1.2 -LsSf https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-installer.sh | sh   ### Install prebuilt binaries via powershell script  sh powershell -ExecutionPolicy ByPass -c "irm https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-installer.ps1 | iex"   ## Download ruff 0.9.2  |  File  | Platform | Checksum | |--------|----------|----------| | [ruff-aarch64-apple-darwin.tar.gz](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-aarch64-apple-darwin.tar.gz) | Apple Silicon macOS | [checksum](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-aarch64-apple-darwin.tar.gz.sha256) | | [ruff-x86_64-apple-darwin.tar.gz](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-x86_64-apple-darwin.tar.gz) | Intel macOS | [checksum](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-x86_64-apple-darwin.tar.gz.sha256) | | [ruff-aarch64-pc-windows-msvc.zip](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-aarch64-pc-windows-msvc.zip) | ARM64 Windows | [checksum](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-aarch64-pc-windows-msvc.zip.sha256) | | [ruff-i686-pc-windows-msvc.zip](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-i686-pc-windows-msvc.zip) | x86 Windows | [checksum](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-i686-pc-windows-msvc.zip.sha256) | | [ruff-x86_64-pc-windows-msvc.zip](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-x86_64-pc-windows-msvc.zip) | x64 Windows | [checksum](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-x86_64-pc-windows-msvc.zip.sha256) | | [ruff-aarch64-unknown-linux-gnu.tar.gz](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-aarch64-unknown-linux-gnu.tar.gz) | ARM64 Linux | [checksum](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-aarch64-unknown-linux-gnu.tar.gz.sha256) | | [ruff-i686-unknown-linux-gnu.tar.gz](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-i686-unknown-linux-gnu.tar.gz) | x86 Linux | [checksum](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-i686-unknown-linux-gnu.tar.gz.sha256) | | [ruff-powerpc64-unknown-linux-gnu.tar.gz](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-powerpc64-unknown-linux-gnu.tar.gz) | PPC64 Linux | [checksum](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-powerpc64-unknown-linux-gnu.tar.gz.sha256) | | [ruff-powerpc64le-unknown-linux-gnu.tar.gz](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-powerpc64le-unknown-linux-gnu.tar.gz) | PPC64LE Linux | [checksum](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-powerpc64le-unknown-linux-gnu.tar.gz.sha256) | | [ruff-s390x-unknown-linux-gnu.tar.gz](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-s390x-unknown-linux-gnu.tar.gz) | S390x Linux | [checksum](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-s390x-unknown-linux-gnu.tar.gz.sha256) | | [ruff-x86_64-unknown-linux-gnu.tar.gz](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-x86_64-unknown-linux-gnu.tar.gz) | x64 Linux | [checksum](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-x86_64-unknown-linux-gnu.tar.gz.sha256) | | [ruff-armv7-unknown-linux-gnueabihf.tar.gz](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-armv7-unknown-linux-gnueabihf.tar.gz) | ARMv7 Linux | [checksum](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-armv7-unknown-linux-gnueabihf.tar.gz.sha256) | | [ruff-aarch64-unknown-linux-musl.tar.gz](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-aarch64-unknown-linux-musl.tar.gz) | ARM64 MUSL Linux | [checksum](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-aarch64-unknown-linux-musl.tar.gz.sha256) | | [ruff-i686-unknown-linux-musl.tar.gz](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-i686-unknown-linux-musl.tar.gz) | x86 MUSL Linux | [checksum](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-i686-unknown-linux-musl.tar.gz.sha256) | | [ruff-x86_64-unknown-linux-musl.tar.gz](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-x86_64-unknown-linux-musl.tar.gz) | x64 MUSL Linux | [checksum](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-x86_64-unknown-linux-musl.tar.gz.sha256) | | [ruff-arm-unknown-linux-musleabihf.tar.gz](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-arm-unknown-linux-musleabihf.tar.gz) | ARMv6 MUSL Linux (Hardfloat) | [checksum](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-arm-unknown-linux-musleabihf.tar.gz.sha256) | | [ruff-armv7-unknown-linux-musleabihf.tar.gz](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-armv7-unknown-linux-musleabihf.tar.gz) | ARMv7 MUSL Linux | [checksum](https://github.com/astral-sh/ruff/releases/download/0.9.2/ruff-armv7-unknown-linux-musleabihf.tar.gz.sha256) |   
```

### 2025-01-15T05:26:15Z [**Heavrnl/UniversalForumBlock**](https://github.com/Heavrnl/UniversalForumBlock)

```
- 增加了基于论坛框架的自动URL匹配识别功能，现已支持所有基于Discuz!和Discourse框架的论坛。 
```

### 2025-01-15T06:51:14Z [**TermoraDev/termora**](https://github.com/TermoraDev/termora)

```
### 新功能/更新  - 支持 终端日志记录 (#7) - 支持 keyboard-interactive (#3) - 支持 OSC 52 指令 - 支持 自定义工具栏 (#36) - 支持 在工具栏快速打开 SFTP - 支持 vim 鼠标滚动 - 支持 Dracula 主题 (#45) - 支持 非 macOS 系统下的 复制/粘贴 快捷键 (#31) - 改进 SFTP 传输进度 (#35) - 改进 新窗口中打开标签页时的标题 (#41) - 改进 弹窗位置以父窗口为中心 (#55)  ### 问题修复  - 修复 在同步配置时 “宏” 没有禁用的问题 (#49) - 修复 ESC[?xm 私有模式导致不正常渲染的问题 (#23) - 修复 在开发环境 “设置 - 关于” 页面地址 404 问题 (#30) - 修复 Windows 切换标签页导致误输入的问题 (#52) - 修复 SFTP 拖拽单个文件上传失败的问题 (#60) 
```

### 2025-01-21T04:06:29Z [**liriliri/aya**](https://github.com/liriliri/aya)

```
* fix: main window cannot be opened on windows #5 
```

### 2025-01-21T16:11:36Z [**langfuse/langfuse**](https://github.com/langfuse/langfuse)

```
## What's Changed  ### Features  * feat(dataset-runs): add product analytics events by @marliessophie in https://github.com/langfuse/langfuse/pull/5145 * feat(ee): add audit log view to project settings by @marcklingen in https://github.com/langfuse/langfuse/pull/5150  ### Fixes  * fix: observation table type alignment by @maxdeichmann in https://github.com/langfuse/langfuse/pull/5146 * fix: correctly upgrade katex by @maxdeichmann in https://github.com/langfuse/langfuse/pull/5151 * fix: use unix timestamp for batch export file name to avoid invalid characters by @Haoping-Xiao in https://github.com/langfuse/langfuse/pull/5092  ### Chores  * chore: reduce default write interval for CH queue to 1000 by @Steffen911 in https://github.com/langfuse/langfuse/pull/5144 * chore: skip re-builds for same tree hash by @Steffen911 in https://github.com/langfuse/langfuse/pull/5135 * chore: remove legacy/batched ingestion pipeline code by @Steffen911 in https://github.com/langfuse/langfuse/pull/5121 * security: upgrade katex by @maxdeichmann in https://github.com/langfuse/langfuse/pull/5149 * chore: allow skipping ingestion CH reads for projects created after cutoff date by @Steffen911 in https://github.com/langfuse/langfuse/pull/5116 * chore(models-ui): move models into settings by @marliessophie in https://github.com/langfuse/langfuse/pull/5124  ## New Contributors * @Haoping-Xiao made their first contribution in https://github.com/langfuse/langfuse/pull/5092  **Full Changelog**: https://github.com/langfuse/langfuse/compare/v3.12.0...v3.13.0 
```

### 2025-01-17T20:48:30Z [**AvitalTamir/cyphernetes**](https://github.com/AvitalTamir/cyphernetes)

```
# Release Notes for Cyphernetes v0.15.3  This release addresses several issues and extends the core e2e suite with more edge case tests.  ## Bugfixes - Patch annotations and labels on resources where no annotations/labels exist - Fix ASCII graphs in shell - Error on nil queries + nil GVR lookups 
```

### 2025-01-21T11:18:23Z [**lejianwen/rustdesk-api**](https://github.com/lejianwen/rustdesk-api)

```
### &nbsp;&nbsp;&nbsp;🚀 Features  - **api**: Add api token expire &nbsp;-&nbsp; by @lejianwen [<samp>(d9e2e)</samp>](https://github.com/lejianwen/rustdesk-api/commit/d9e2e24) - **webclient**: Up to 1.3.7 &nbsp;-&nbsp; by @lejianwen [<samp>(f4945)</samp>](https://github.com/lejianwen/rustdesk-api/commit/f49457d)  ##### &nbsp;&nbsp;&nbsp;&nbsp;[View changes on GitHub](https://github.com/lejianwen/rustdesk-api/compare/v2.6.5...v2.6.6) 
```

### 2025-01-19T01:54:33Z [**zero-peak/ZeroOmega**](https://github.com/zero-peak/ZeroOmega)

```
# 3.3.19  1. Add right click options button (Firefox) #77 2. Condition type - show help not showing help #76 3. add PAC Profiles support on Firefox PC #74 4. i18n  # 3.3.20  1. cannot connect to SOCKS proxy with login/password auth #83 2. Opening the settings of a Socks5 Proxy with saved credentials deletes those credentials #67 3. Broken copyright notices in new version #82  
```

### 2025-01-20T15:37:35Z [**certd/certd**](https://github.com/certd/certd)

```
## [1.30.1](https://github.com/certd/certd/compare/v1.30.0...v1.30.1) (2025-01-20)   ### Bug Fixes  * 修复部署到阿里云ALB、NLB插件加载混乱的bug ([6ab83b6](https://github.com/certd/certd/commit/6ab83b662a2c5e715b9cb7eb1244de2ebb7f47b0)) * 修复腾讯clb重复执行会报错的bug ([e95d29f](https://github.com/certd/certd/commit/e95d29f446d06eced315a3087fc9e105a30b20bd)) * 修复tg消息内容中存在.和*就会发送失败的bug ([ae5dfc3](https://github.com/certd/certd/commit/ae5dfc3bee950267123ae2fbd1c11e7ce36626ea))   ### Performance Improvements  * 创建流水线时，默认成功时也发送通知 ([52ae690](https://github.com/certd/certd/commit/52ae6902d203ca56e0312692b50c55cb6ddd3e39)) * http方式校验，选择sftp时，支持修改文件访问权限比如777 ([15d6eaf](https://github.com/certd/certd/commit/15d6eaf5532ed25acd4f8d58c429353a2f44206c)) 
```

### 2025-01-16T07:43:53Z [**ufrisk/pcileech**](https://github.com/ufrisk/pcileech)

```
* Linux stability improvements and kernel module loading enhancements. * Linux clang compilation support. * macOS support. 
```

### 2025-01-21T08:52:51Z [**zhongyang219/TrafficMonitor**](https://github.com/zhongyang219/TrafficMonitor)

```
**功能更新：** * 任务栏窗口增加Direct2D的渲染方式，解决有时字体边缘有锯齿的问题 #1156 * 显卡监控功能增加对英特尔显卡的支持 * 右击插件项目时的右键菜单中增加插件菜单 * 插件管理界面增加插件图标的显示，右键菜单中增加插件命令 * 监控时间间隔的最大值调整为30s * 任务栏窗口设置中增加“窗口顶部边距”和“垂直边距”的选项 * 主窗口增加对png格式透明背景图片的支持 * 新增根据Windows深浅色模式自动切换皮肤的功能 #1013 * 新增在任务栏的插件项目中显示资源占用图的功能，并更新对应的插件接口 #1077 * 主窗口和任务栏窗口中新增今日总流量的显示 #1174 * 任务栏窗口设置中新增“使用彩色emoji”的选项（仅Direct2D渲染方式） * 常规设置中的温度通知上限调整为120度 #1814 * 新增Arm64EC的支持 #1703 * 新增Lite版显示CPU频率的功能 * 任务栏设置-预设方案中的方案2和方案3增加默认的文本颜色  **问题修正：** * LibreHardwareMonitorLib.dll更新到0.9.4版本，解决部分设备硬件监控信息无法正常显示的问题 * 修正Windows 11 build 22621版本后触屏设备任务栏窗口位置不正确的问题 * 修正Windows 11下小组件不存在时，任务栏窗口的位置不正确的问题的问题 #1582 * 修正Windows 11下，当任务栏窗口显示在右侧时，会和系统小组件重叠的问题 * 修正选项设置对话框中使用触摸板手势时滚动过快的问题 * 修正主窗口鼠标提示中CPU频率显示不正确的问题 * 修正皮肤文件中插件项目的显示文本无效的问题 #1813 * 修正如果隐藏了通知区图标，弹出通知后通知区图标再次出现的问题 #1814 #1812 #1811 
```

### 2025-01-19T17:08:41Z [**PBH-BTN/PeerBanHelper**](https://github.com/PBH-BTN/PeerBanHelper)

```
<img align="right" width="70" src="https://github.com/user-attachments/assets/28391a97-2647-435b-aaeb-9d39f7dfd9a5">  提前祝各位新年快乐~ 在接下来的春节假期和元宵佳节期间，PBH-BTN 将暂停一段时间的开发、技术支持工作。除非有严重错误，我们在未来一段时间内都不会发布的新的正式版本。  享受假期，快乐过年！下次见！  ---  > [!NOTE] > 对使用 BiglyBT 下载器的用户：PeerBanHelper 自本版本起需要 PBH-Adapter-BiglyBT 的 `1.2.9` 或者更高版本，请升级您的适配器插件版本。当版本过低时，WebUI 将显示 “需要采取行动” 提示，并在升级之前无法正常工作。有关 PBH-Adapter-BiglyBT 的相关更改，请[参见对应的版本发行说明](https://github.com/PBH-BTN/PBH-Adapter-BiglyBT/releases)。  ## 错误修复  * 修复 NoGUI 模式下，日志队列发生内存泄漏的问题，可能导致长时间运行崩溃的问题 @Ghost-chu  * 修复 BitComet 下载器的 “忽略私有种子” 功能不起作用的问题 @Ghost-chu  * 修复 BTN 提交历史记录能力在遇到单次提交超过 10,000 条的时候会导致除最近 10,000 条的数据外剩余数据被丢弃的问题。现在将会正确的进行分批提交，并丢弃 30 天前的历史数据 @Ghost-chu  * [WebUI] 修复更新日志在特定情况下内容区域背景颜色异常导致内容不可读的问题 @Gaojianli   ## 改进  * 降低提交历史记录时每批提交的数量（从 10,000 降低到 5,000），超过 5,000 的数据将拆分到下一个请求以降低生成提交数据时的 RAM 使用 @Ghost-chu  * 优化 GUI 日志记录速度过快时的内存占用峰值问题 @Ghost-chu  * 此前需要修改启动命令 `-D` 添加的自定义 Flags 现在支持通过环境变量传递 @Ghost-chu   * 如果过去的自定义 Flag 包含符号 `.` 或 `-`，则替换为 `_`   * 所有 ASCII 字符均大写  ## 安全改进  * 现在不再暴露 WebAPI 端点列表到 `/route-view` @Ghost-chu  * 现在将通过检查 User-Agent 的方式，屏蔽下列网络空间测绘引擎的请求，避免 PeerBanHelper 被如下测绘引擎或者端口扫描工具的端口扫描探测： @Ghost-chu    * Censys   * Shodan   * ZoomEye   * ThreatBook   * FOFA   * zmap (默认配置时)   * nmap (默认配置时)   * 所有以上 User-Agent 的请求都将返回 404 not found 提示信息和 404 状态码  ## BTN 更改  * 协议版本号从 `8` 提升到 `10` 以对应协议更新 @Ghost-chu   ## 实验室功能  * 使用已知数据填充缺失的记录 @Ghost-chu    * 使用上一个已知的数据记录填充查询的流量记录的空白条目以尝试修复流量统计不准确的问题。但当查询范围开头也无数据时，此功能不生效。需要手动开启实验。  ## 数据收集范围更改披露  @Ghost-chu   PeerBanHelper 严格遵守和执行 [PeerBanHelper 隐私政策](https://github.com/PBH-BTN/terms/blob/master/peerbanhelper-privacy-zh-CN.md)，并确保用户的知情权。当我们在隐私政策或者收集的内容范围作出更改时，将通过公告等形式向您告知。  以下是有关本次更新中 “BTN 网络” 收集数据的更改告知以及其用途说明：  影响范围：PeerBanHelper v7.3.3 或更高版本，且使用了由 PBH-BTN 官方维护的 Sparkle BTN 的 BTN 实例 (btn-prod.ghostchu-services.top, sparkle.ghostchu-services.top, btn-dev.ghostchu-services.top, sparkle.ghostchu.com) 并且打开了 设置-基础设置-BTN-启用提交 开关的用户    新增收集的数据列表如下所示:  ### 1. [新增] is_private_torrent  **作用：** 指示一个 torrent_identifier 对应的是否是一个私有种子   **适用范围：** 提交封禁列表和提交历史记录，包括之前的数据（如果被再次更新）   **收集条件：** 当对应下载器未启用 “忽略私有种子” 开关或者下载器不支持 “忽略私有种子”，并且连接到了 Sparkle BTN 实例，且打开了“启用提交”开关，并且产生了下列数据的情况下，新的数据可能会被收集 **数据用途：** 帮助 BTN 服务端程序识别对应 torrent_identifier 的 “私有种子” 类型，以便单独处理可能由 PT 站点等私有种子产生的数据，例如用于分析和统计用途。 **收集的数据能够：**  1. 能够识别一条数据是否由一个私有种子产生  **收集的数据无法：**  1. 无法在未提前得知 info_hash 的情况下推断数据对应的 info_hash 是什么，参见 [BTN-Spec info_hash 匿名化哈希算法](https://github.com/PBH-BTN/BTN-Spec#torrent-identifier-%E7%AE%97%E6%B3%95) 2. 无法推断出对应的数据是否来自某个具体的 Tracker  **数据示例：**  * is_private_torrent = true // 指示本条数据由一个私有种子产生 * is_private_torrent = false // 指示本条数据由一个公共种子产生  **术语解释:**  1. `torrent_identifier`: 使用 [BTN-Spec info_hash 匿名化哈希算法](https://github.com/PBH-BTN/BTN-Spec#torrent-identifier-%E7%AE%97%E6%B3%95) 将一个种子的 info_hash 转换为的匿名哈希值，以便在无需得知种子的实际 info_hash 的匿名情况下识别两个 torrent_identifier 对应的是否是同一个实际种子的技术 4. `提交封禁列表`: 向 BTN 提交自 PBH 启动/上次提交以来的新增封禁记录的过程 [技术资料](https://github.com/PBH-BTN/BTN-Spec#%E6%8F%90%E4%BA%A4%E5%B0%81%E7%A6%81%E5%88%97%E8%A1%A8-submit_bans) 5. `提交历史记录`:  向 BTN 提交自上次提交以来的新增 Peer 活动连接记录的过程 [技术资料](https://github.com/PBH-BTN/BTN-Spec#%E6%8F%90%E4%BA%A4-peers-%E7%B4%AF%E7%A7%AF%E6%95%B0%E6%8D%AE%E5%88%97%E8%A1%A8-submit_histories) 6. `私有种子`: 由 [BEP-0027 Private Torrents](http://bittorrent.org/beps/bep_0027.html) 中定义的一种种子类型，通常被 PT 站使用  ## 未实装的功能  以下功能因时间因素未在本版本中适配前端界面，但仍可通过 WebAPI 调用：  1. 批量替换下载器的种子的 Trackers (暂仅支持 qBittorrent, Transmission, BiglyBT)  ## Docker  DockerHub: `ghostchu/peerbanhelper:v7.3.3`   阿里云国内镜像加速: `registry.cn-hangzhou.aliyuncs.com/ghostchu/peerbanhelper:v7.3.3` 
```

### 2025-01-20T09:39:02Z [**ZGGSONG/STranslate**](https://github.com/ZGGSONG/STranslate)

```
## 更新  - 新增: 内置微软翻译 - 新增: 内置Yandex翻译 - 新增: 微软识别服务 - 优化: 截图时左下角添加功能提示信息 - 修复: 输出结果UI服务配置下拉列表鼠标穿透问题 - 修复: 无法打开的问题(C#获取`StartUp`目录为空的情况)  **完整更新日志:** [1.3.0.0107...1.3.1.120](https://github.com/ZGGSONG/STranslate/compare/1.3.0.0107...1.3.1.120)  ## 离线数据  [123 网盘](https://www.123pan.com/s/AxlRjv-OuVmA.html)  > 离线数据包含: [简明英汉词典数据包](https://github.com/skywind3000/ECDICT/releases/download/1.0.28/ecdict-sqlite-28.zip)  [PaddleOCR数据包(v4.3)](https://github.com/ZGGSONG/STranslate/releases/download/0.01/stranslate_paddleocr_data_v4.3.zip) 等  > 另: OCR部分软件内置`微信OCR`、词典部分软件内置了`必应`、`金山`词典，上述离线数据包配置较为繁琐，可直接使用软件内置服务 
```

### 2025-01-15T07:34:12Z [**ente-io/ente**](https://github.com/ente-io/ente)

```
## What's Changed * [mob][photos] Fix hidden file for face by @laurenspriem in https://github.com/ente-io/ente/pull/4718 * [mob] Update moments section for internal users by @ua741 in https://github.com/ente-io/ente/pull/4719 * [mob][photos] Fix regression with Persons by @laurenspriem in https://github.com/ente-io/ente/pull/4734 * [mob][photos] Bump for release by @laurenspriem in https://github.com/ente-io/ente/pull/4735   **Full Changelog**: https://github.com/ente-io/ente/compare/photos-v0.9.79...photos-v0.9.81 
```

### 2025-01-20T02:54:28Z [**0x2E/fusion**](https://github.com/0x2E/fusion)

```
## ⚠️ SECURITY UPDATE  - fix https://github.com/0x2E/fusion/issues/53  ## Changelog * 01cc024981cb125a52d82056c2c53bfd3a915537: Fix a session checking bug (@mtlynch) * c9102cf5c030ff9a7f6de62f77355a6b4b19029e: Merge pull request #54 from mtlynch/no-unauth-sess (@0x2E)  
```

### 2025-01-20T01:07:31Z [**WuKongIM/WuKongIM**](https://github.com/WuKongIM/WuKongIM)

```
## 更新内容  - perf: 大幅提升消息收发延迟和存储性能 - fix: 修复新的订阅者有时候收不到消息的问题 - fix: 修复在线用户统计不准确问题 - fix: 移除订阅者的时候有崩溃的概率 - feat: 优化管理后台，连接新增“断开”，“踢掉”功能 - fix: 修复离线cmd有时候收不到问题 - fix: 修复代理连接关闭了，领导连接还没关闭的问题 - perf: 优化channelClusterConfig存储的性能 - feat: 后台连接页面显示当前节点的所有连接包括逻辑连接 - feat: web后台适配黑暗模式 - feat: 日志增加控制台的输出配置 - perf: 优化后台启动时创建server的时机 - fix: 修复webhook消息队列里的消息负载过大导致webhook收不到推送问题 - fix:解决发送到指定人,指定人列表uid不在toUids中 - refactor: 移除webhook多余的创建操作 
```

### 2025-01-18T07:08:40Z [**dreamhunter2333/cloudflare_temp_email**](https://github.com/dreamhunter2333/cloudflare_temp_email)

```
## What's Changed  - feat: |Worker| 增加 `REMOVE_ALL_ATTACHMENT` 和 `REMOVE_EXCEED_SIZE_ATTACHMENT` 用于移除邮件附件，由于是解析邮件的一些信息会丢失，比如图片等.    移除附件可以减少D1 数据库的消耗，并且可以保存超过 2M 的邮件正文 - fix: |mail-parser-wasm-worker| 修复 `initSync` 函数调用时的 `deprecated` 参数警告 - fix: 修复 parsedEmailContext 仍然会重复解析 (#559) - fix: 触发其他 worker 时，请求头使用objectc传递（用 Map<string,string> 及 Header类，在JSON.stringify后会是{}） (#559) - fix: telegram 使用 iframe 展示 email (#561)  ### [更新或者部署网页不生效请如图勾选清理缓存](https://github.com/dreamhunter2333/cloudflare_temp_email/discussions/487)  ![image](https://github.com/user-attachments/assets/b6ec233d-ae77-4dfb-8124-2f9f98d4a110)  ### PRs  * feat: v0.8.5 && update dependencies && fix `deprecated` warning for `… by @dreamhunter2333 in https://github.com/dreamhunter2333/cloudflare_temp_email/pull/556 * feat: update doc by @dreamhunter2333 in https://github.com/dreamhunter2333/cloudflare_temp_email/pull/557 * fix: rpc headers covert & typo by @oneisall8955 in https://github.com/dreamhunter2333/cloudflare_temp_email/pull/559 * fix: mail-parser-wasm parsedEmailContext cache by @dreamhunter2333 in https://github.com/dreamhunter2333/cloudflare_temp_email/pull/560 * fix: telegram mail page use iframe show email by @dreamhunter2333 in https://github.com/dreamhunter2333/cloudflare_temp_email/pull/561 * feat: |Worker| add REMOVE_ALL_ATTACHMENT and REMOVE_EXCEED_SIZE_ATTAC… by @dreamhunter2333 in https://github.com/dreamhunter2333/cloudflare_temp_email/pull/562 * feat: |Worker| add REMOVE_ALL_ATTACHMENT and REMOVE_EXCEED_SIZE_ATTAC… by @dreamhunter2333 in https://github.com/dreamhunter2333/cloudflare_temp_email/pull/563 * fix: telegram mail page use iframe show email by @dreamhunter2333 in https://github.com/dreamhunter2333/cloudflare_temp_email/pull/564   **Full Changelog**: https://github.com/dreamhunter2333/cloudflare_temp_email/compare/v0.8.4...v0.8.5 
```

### 2025-01-15T02:55:56Z [**dail8859/NotepadNext**](https://github.com/dail8859/NotepadNext)

```
## What's Changed * Add more bookmark operations (cut/copy/delete) by @dail8859 in https://github.com/dail8859/NotepadNext/pull/679 * Add Debug Info dialog box * Allow overriding terminal command by @dail8859 in https://github.com/dail8859/NotepadNext/pull/685 * Update Scintilla and Lexilla by @dail8859 in https://github.com/dail8859/NotepadNext/pull/684 * Add Nix language by @dail8859 in https://github.com/dail8859/NotepadNext/pull/687 * Auto close HTML tags by @dail8859 in https://github.com/dail8859/NotepadNext/pull/690 * Add HTML highlighting in PHP files by @dail8859 in https://github.com/dail8859/NotepadNext/pull/691 * Add basic lua console history by @dail8859 in https://github.com/dail8859/NotepadNext/pull/692 * Auto detect EOL mode by @dail8859 in https://github.com/dail8859/NotepadNext/pull/693 * Add default EOL setting * Add default end of line setting by @dail8859 in https://github.com/dail8859/NotepadNext/pull/694 * Make Find/Replace Dialog resize-able by @dail8859 in https://github.com/dail8859/NotepadNext/pull/695 * Backup settings when running `--reset-settings` * Fix file loss when having a single temporary file by @dail8859 in https://github.com/dail8859/NotepadNext/pull/675 * Add Czech translation by @mkasik75 in https://github.com/dail8859/NotepadNext/pull/681 * Add Brazilian Portuguese translation by @lucasvmx in https://github.com/dail8859/NotepadNext/pull/665 * Update Swedish translation by @eson57 in https://github.com/dail8859/NotepadNext/pull/666 * Update Portuguese (Portugal) translation by @hugok79 in https://github.com/dail8859/NotepadNext/pull/686  ## New Contributors * @lucasvmx made their first contribution in https://github.com/dail8859/NotepadNext/pull/665 * @SigHunter made their first contribution in https://github.com/dail8859/NotepadNext/pull/670 * @mkasik75 made their first contribution in https://github.com/dail8859/NotepadNext/pull/681  **Full Changelog**: https://github.com/dail8859/NotepadNext/compare/v0.9...v0.10 
```

### 2025-01-21T19:42:41Z [**xtrime-ru/TelegramApiServer**](https://github.com/xtrime-ru/TelegramApiServer)

```
Upgrade php to 8.4 in docker   **Full Changelog**: https://github.com/xtrime-ru/TelegramApiServer/compare/v2.4.0...v2.4.1 
```

### 2025-01-18T11:13:48Z [**casibase/casibase**](https://github.com/casibase/casibase)

```
# [1.186.0](https://github.com/casibase/casibase/compare/v1.185.0...v1.186.0) (2025-01-18)   ### Features  * add Hunyuan embedding provider to Casibase ([#982](https://github.com/casibase/casibase/issues/982)) ([9a598d3](https://github.com/casibase/casibase/commit/9a598d3f0b8b596f2ef6c916d26dc3c8e6c6214f)) 
```

### 2025-01-15T04:12:42Z [**labring/FastGPT**](https://github.com/labring/FastGPT)

```
## 修复内容 1. 修复 HTTP 节点， {{}} 格式引用变量兼容问题。建议尽快替换 / 模式取变量， {{}} 语法已弃用。  ## 升级指南 **1. 更新镜像** - 更新 fastgpt 镜像 tag: v4.8.18-fix2 - 更新 fastgpt-pro 商业版镜像 tag: v4.8.18-fix2 - Sandbox 镜像无需更新  **Full Changelog**: https://github.com/labring/FastGPT/compare/v4.8.18...v4.8.18-fix2 
```

### 2025-01-21T04:21:57Z [**Calcium-Ion/new-api**](https://github.com/Calcium-Ion/new-api)

```
## What's Changed * feat: 更新模型和模型倍率 by @HynoR in https://github.com/Calcium-Ion/new-api/pull/709 * Feat: 日志查询增加渠道名称显示 by @detecti1 in https://github.com/Calcium-Ion/new-api/pull/699 * fix: incorrect whisper audio usage by @maranello-o in https://github.com/Calcium-Ion/new-api/pull/705  ## New Contributors * @detecti1 made their first contribution in https://github.com/Calcium-Ion/new-api/pull/699 * @maranello-o made their first contribution in https://github.com/Calcium-Ion/new-api/pull/705  **Full Changelog**: https://github.com/Calcium-Ion/new-api/compare/v0.4.6.1...v0.4.6.2 
```

### 2025-01-20T05:41:39Z [**coaidev/coai**](https://github.com/coaidev/coai)

```
## What's Changed * fix enter send message on macos by @yongman in https://github.com/coaidev/coai/pull/151 * claude sys msg adapt by @Lavanille777 in https://github.com/coaidev/coai/pull/152 * fix: skip the first claude system message by @Lavanille777 in https://github.com/coaidev/coai/pull/154 * 支持MySql tls连接 by @navee in https://github.com/coaidev/coai/pull/168 * feat: support model `gpt-4o` and `gpt-4o-2024-05-13` by @XiaomaiTX in https://github.com/coaidev/coai/pull/196 * feat: add `gpt-4-turbo` `gemini-1.5-pro-latest` `gemini-1.5-flash-latest` model by @XiaomaiTX in https://github.com/coaidev/coai/pull/198 * fix: remove repetitive quota refresh interval by @eddsi in https://github.com/coaidev/coai/pull/180 * bug report: revert pr #180 "fix: remove repetitive quota refresh interval" by @zmh-program in https://github.com/coaidev/coai/pull/203 * chore: Define sending defaults based on different device types (#204) by @Sh1n3zZ in https://github.com/coaidev/coai/pull/211 * chore: Synchronizing updates from the `main` branch by @Sh1n3zZ in https://github.com/coaidev/coai/pull/212 * feat: SMTP Compatibility Enhancement and SSL Protocol Support (#174) by @Sh1n3zZ in https://github.com/coaidev/coai/pull/213 * chore: Compatible with pre-modified SMTP sending method (#174) by @Sh1n3zZ in https://github.com/coaidev/coai/pull/214 * fix: fix used of network error on forced shutdown by @XiaomaiTX in https://github.com/coaidev/coai/pull/223 * feat: support the latest OpenAI model `chatgpt-4o-latest` by @PeterDaveHello in https://github.com/coaidev/coai/pull/245 * Simplify apk upgrade process in the Dockerfile by @PeterDaveHello in https://github.com/coaidev/coai/pull/246 * Add a basic zh-tw i18n locale by @PeterDaveHello in https://github.com/coaidev/coai/pull/244 * feat: support spark desk new model by @mercury7720 in https://github.com/coaidev/coai/pull/253 * feature: add Alibaba Cloud Computing Nest one-click deployment button by @workhardliuzheng in https://github.com/coaidev/coai/pull/283 * fix: smtp starttls compatibility issue by @Ogannesson in https://github.com/coaidev/coai/pull/292 * Fix SMTP compatibility issues to support office365 provider by @zmh-program in https://github.com/coaidev/coai/pull/301 * fix: watchtower retries causing service crash by @zmh-program in https://github.com/coaidev/coai/pull/309  ## New Contributors * @yongman made their first contribution in https://github.com/coaidev/coai/pull/151 * @Lavanille777 made their first contribution in https://github.com/coaidev/coai/pull/152 * @navee made their first contribution in https://github.com/coaidev/coai/pull/168 * @XiaomaiTX made their first contribution in https://github.com/coaidev/coai/pull/196 * @eddsi made their first contribution in https://github.com/coaidev/coai/pull/180 * @PeterDaveHello made their first contribution in https://github.com/coaidev/coai/pull/245 * @mercury7720 made their first contribution in https://github.com/coaidev/coai/pull/253 * @workhardliuzheng made their first contribution in https://github.com/coaidev/coai/pull/283 * @Ogannesson made their first contribution in https://github.com/coaidev/coai/pull/292  **Full Changelog**: https://github.com/coaidev/coai/compare/v3.10...v3.11.1 
```

### 2025-01-15T22:46:44Z [**dockur/windows**](https://github.com/dockur/windows)

```
## What's Changed * Update samba.sh to enable folders with symlinks by @james-nguyen-ai in https://github.com/dockur/windows/pull/1001 * feat: Support more shared directories by @ncheng89 in https://github.com/dockur/windows/pull/987 * build: Update qemu-docker to v6.13 by @kroese in https://github.com/dockur/windows/pull/1010  ## New Contributors * @james-nguyen-ai made their first contribution in https://github.com/dockur/windows/pull/1001 * @ncheng89 made their first contribution in https://github.com/dockur/windows/pull/987  **Full Changelog**: https://github.com/dockur/windows/compare/v4.08...v4.09 
```

### 2025-01-21T13:50:13Z [**gitbutlerapp/gitbutler**](https://github.com/gitbutlerapp/gitbutler)

```
## What's Changed - Fixes a regression from 0.14.5 which was preventing commit signing with 1Password under MacOS  **Full Changelog**: https://github.com/gitbutlerapp/gitbutler/compare/release/0.14.5...release/0.14.6  ### Downloads Download bins from https://gitbutler.com/ 
```

### 2025-01-21T16:33:03Z [**msgbyte/tianji**](https://github.com/msgbyte/tianji)

```
## [1.17.9](https://github.com/msgbyte/tianji/compare/v1.17.8...v1.17.9) (2025-01-21)  fix a bug which will make survey can not work.  ### Others  * fix trpc-to-openapi use incorrect middleware problem ([707d6fa](https://github.com/msgbyte/tianji/commit/707d6fa800dc917a8673927b973565995fdb398a)) 
```

### 2025-01-21T11:09:56Z [**reqable/reqable-app**](https://github.com/reqable/reqable-app)

```
### windows-macos-linux-android-ios - 🐞 [FIX] The bug that the exported raw data has no separator between request and response. - 🐞 [FIX] in API testing, the sent request body is not updated after replacing the content. ### windows-macos-linux - 💪 [OPT] Automatically remember the sidebar status and restore it after restarting the app. - 💪 [OPT] Traffic records related to applications and hosts can be deleted with one click in the traffic list explorer. - 💪 [OPT] JSON/XML/HEX tools support file dragging and file selector. - 💪 [OPT] JSON escape tool supports JSON formatting and compression. - 💪 [OPT] JSON escape tool no longer escapes line breaks. - 🐞 [FIX] The bug that ADB cannot discover Android devices in some cases. - 🐞 [FIX] A bug that the display position of the environment variable drop-down menu may be seriously offset. - 🐞 [FIX] The conflict between the search and replace `Enter` shortcut key and the IME input `Enter` key. 
```

### 2025-01-15T19:41:58Z [**clash-verge-rev/clash-verge-rev**](https://github.com/clash-verge-rev/clash-verge-rev)

```
Clash Verge Rev 2.0.3 版本发布！（稳定版，推荐更新）  ## v2.0.3  ### Notice  - !!使用出现异常的，打开设置-->配置目录 备份 后 删除所有文件 尝试是否正常!！ - 历时3个月的紧密开发与严格测试稳定版2.0.0终于发布了：巨量改进与性能、稳定性提升，目前Clash Verge Rev已经有了比肩cfw的健壮性；而且更强大易用！ - 由于更改了服务安装逻辑，每次更新安装需要输入系统密码卸载老版本服务和安装新版本服务，以后可以丝滑使用tun(虚拟网卡)模式  ### 2.0.3相对于2.0.2改进修复了：  1. 修复VLess-URL识别网络类型错误 f400f90 #2126 2. 新增系统代理绕过文本校验 c71e18e 3. 修复脚本编辑器UI显示不正确 6197249 #2267 4. 修复Shift热键无效 589324b #2278 5. 新增nushell环境变量复制 d233a84 6. 修复全局扩展脚本无法覆写DNS d22b37c #2235 7. 切换到系统代理相对于稳定的版本 38745d4 8. 修改fake-ip-range网段 0e3b631 9. 修复窗口隐藏后WebSocket未断开连接，减小内存风险 b42d13f 10. 改进系统代理绕过设置 c5c840d 11. 修复i18n翻译文本缺失 b149084 12. 修复双击托盘图标打开面板 f839d3b #2346 13. 修复Windows10窗口白色边框 4f6ca40 #2425 14. 修复Windows窗口状态恢复 4f6ca40 15. 改进保存配置文件自动重启Mihomo内核 0669f7a 16. 改进更新托盘图标性能 d9291d4 17. 修复保存配置后代理列表未更新 542baf9 #2460 18. 新增MacOS托盘显示实时速率，可在"界面设置"中关闭 1b2f1b6 19. 新增托盘菜单显示已设置的快捷键 eeff4d4 20. 新增重载配置文件错误响应"400"时显示更多错误信息 c5989d2 #2492 21. 修复GUI代理状态与菜单显示不一致 13b63b5 #2502 22. 新增默认语言跟随系统语言(无语言支持即为英语)，添加了阿拉伯语、印尼语、鞑靼语支持 9655f77 #2940  ### Features  - Meta(mihomo)内核升级 1.19.1 - 增加更多语言和托盘语言跟随 - MacOS增加状态栏速率显示 - 托盘显示快捷键 - 重载配置文件错误响应"400"时显示更多错误信息 - 改进保存配置文件自动重启Mihomo内核  ### Performance  - 改进更新托盘图标性能 - 窗口隐藏后WebSocket断开连接  ### 下载  Windows (不支持win7)： - 安装版：[64位，一般下载这个](https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.0.3/Clash.Verge_2.0.3_x64-setup.exe) | [Arm64看准了，这个不常用](https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.0.3/Clash.Verge_2.0.3_arm64-setup.exe) （因为便携版问题较多不再提供便携版）  macOS 11+： - DMG：[Intel](https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.0.3/Clash.Verge_2.0.3_x64.dmg) | [Apple Silicon M](https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.0.3/Clash.Verge_2.0.3_aarch64.dmg)  Linux： - DEB：[64位](https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.0.3/Clash.Verge_2.0.3_amd64.deb) | [Arm64](https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.0.3/Clash.Verge_2.0.3_arm64.deb) (Debian系) 使用 apt ./路径 安装 - RPM：[64位](https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.0.3/Clash.Verge-2.0.3-1.x86_64.rpm) | [Arm64](https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.0.3/Clash.Verge-2.0.3-1.aarch64.rpm) (Redhat系) 使用 dnf ./路径 安装  ### 快速上手 - [使用文档](https://clash-verge-rev.github.io)  ### 稳定机场VPN推荐 - [狗狗加速](https://verge.dginv.click/#/register?code=oaxsAGo6)  ### Clash Verge Rev TG频道： - [@clash_verge_re](https://t.me/clash_verge_re) 
```

### 2025-01-18T13:04:11Z [**lxgw/LxgwWenKai**](https://github.com/lxgw/LxgwWenKai)

```
- 在 OpenType Features 中删除除 `DFLT` 以外的所有语言标签，以试图解决在 Safari 中竖排变体等 OpenType 特性失效的问题。 - 调整以下符号：⒧ⓛ。 - 引入 `ccmp` 特性，新增汉语拼音、台罗拼音等拼音系统中未被 Unicode 收录的附标字母（如：ê̄ê̌m̄m̌m̀n̄）。 - 新增古代汉语标点符号：钩乙号「𖿢」`U+16FE2`、重文号「𖿣」`U+16FE3`。 - 新增算筹数字：𝍠𝍡𝍢𝍣𝍤𝍥𝍦𝍧𝍨𝍩𝍪𝍫𝍬𝍭𝍮𝍯𝍰𝍱。 - 新增符号：☐☑。 - 新增汉字：㲹圶垥攼疦胒薉蛈𦫸𦮴𫊥𬜨𰀅。 - 调整谚文字符，并增补 GB/T 12052-1989 中第 16～37 区谚文音节，以及朝鲜标准 KPS 9566 所收录的所有谚文音节。 - 调整符号细节：㉿。 - 增补「思源」字体中包含的大部分符号（古谚文字母、「〱」`U+3031`、「〲」`U+3032`除外）。  > [!WARNING] > Assets 里的 zip 格式压缩包仅为打包的字体文件，**非 Magisk 模块！**   > 如欲下载该字体的 Magisk 模块，请移步 [永硕Ｅ盘](http://lxgw.ysepan.com/)、[蓝奏云（密码：8ppk）](https://lxgw.lanzoui.com/b0cqwpt3i) ，或使用 [CJK 字体 Magisk 模块模板](https://github.com/lxgw/simple-cjk-font-magisk-module-template) 按照说明将该字体打包成 Magisk 模块。 > 永硕Ｅ盘、蓝奏云分流将在本次 Release 更新后 **72 小时**之内更新。 
```

### 2025-01-20T22:17:41Z [**OwO-Network/DeepLX**](https://github.com/OwO-Network/DeepLX)

```
## What's Changed * chore(deps): bump golang.org/x/crypto from 0.27.0 to 0.31.0 by @dependabot in https://github.com/OwO-Network/DeepLX/pull/166 * chore(deps): bump golang.org/x/net from 0.29.0 to 0.33.0 by @dependabot in https://github.com/OwO-Network/DeepLX/pull/173   **Full Changelog**: https://github.com/OwO-Network/DeepLX/compare/v1.0.1...v1.0.2 
```

### 2025-01-17T01:10:56Z [**seriousm4x/UpSnap**](https://github.com/seriousm4x/UpSnap)

```
## Changelog ### Features * 2d8fce32d39fd9bb0854b91bcb5b792c68f5cfdc: feat: allow non http/https links for ports and devices (@seriousm4x) ### Bug fixes * 62cb0e8f73fc6d8df43c9b6ff21816e3ef72af6e: fix: js eslint warning (@seriousm4x) ### Others * 3746d71c2d1e57bf8be32698a91154501d989fdf: formatting (@seriousm4x) ### Go dependencies * 22c16cc4552a0da2f4a395d28332687adb2daea4: go-dep: update (@seriousm4x) ### Npm dependencies * 3e7eb6cbf9d78fdd72b2dc8c749d3e32e03a2bdd: npm-dep: bump @sveltejs/kit from 2.15.2 to 2.15.3 in /frontend (@dependabot[bot]) * 71319f0497cdf5229153e8680fcd4151ab840fa1: npm-dep: bump eslint-config-prettier from 9.1.0 to 10.0.1 in /frontend (@dependabot[bot]) * 9da93677bf9e79f6072d0fce100bf49a96b476cc: npm-dep: bump postcss from 8.5.0 to 8.5.1 in /frontend (@dependabot[bot]) * 34a0ae5c658f4b8c48264907f4b29162f4e63681: npm-dep: bump prettier-plugin-tailwindcss in /frontend (@dependabot[bot]) * 7764ccc65fa6585d0a1cc1db0e00becfe482b5f4: npm-dep: update (@seriousm4x) 
```

### 2025-01-19T11:17:58Z [**klzgrad/naiveproxy**](https://github.com/klzgrad/naiveproxy)

```
Lowered Linux builds dependency on glibc from 2.27 to 2.17. 
```

### 2025-01-20T12:51:19Z [**LazyVim/LazyVim**](https://github.com/LazyVim/LazyVim)

```
## [14.8.0](https://github.com/LazyVim/LazyVim/compare/v14.7.0...v14.8.0) (2025-01-20)   ### Features  * **chezmoi:** add snacks picker integration for chezmoi files ([#5429](https://github.com/LazyVim/LazyVim/issues/5429)) ([970d1a0](https://github.com/LazyVim/LazyVim/commit/970d1a05da37554aa17b671c869431a7b387d8be)) * **dial:** add checkbox augend for markdown ([#5411](https://github.com/LazyVim/LazyVim/issues/5411)) ([b19f207](https://github.com/LazyVim/LazyVim/commit/b19f2070b847a3067436f4d16a0cc5b84a9f9819)) * **snacks.picker:** added leader-sS to search lsp workspace symbols ([8787ec1](https://github.com/LazyVim/LazyVim/commit/8787ec1227e10123ad7291cf916020d9a8626525)) * **snacks:** added git diff keymap to pick hunks with leader-gd ([62cb4a4](https://github.com/LazyVim/LazyVim/commit/62cb4a465c490c7d41f7a3bf52fb0e222f2cf83b))   ### Bug Fixes  * **markdown:** disable checkbox rendering since it's annoying to edit ([4f31bfa](https://github.com/LazyVim/LazyVim/commit/4f31bfab86402c819e5ea1e18b3c5d139628c864)) * **snacks.picker:** fix mapping for `Recent (cwd)` ([#5407](https://github.com/LazyVim/LazyVim/issues/5407)) ([8307b0f](https://github.com/LazyVim/LazyVim/commit/8307b0fe506a38417f3b7835e2c4b43d9a970946)) * **snacks.picker:** fix mapping for Projects for consistency ([#5433](https://github.com/LazyVim/LazyVim/issues/5433)) ([eb7b453](https://github.com/LazyVim/LazyVim/commit/eb7b453b48ab7e3008013e0edf2822f622111e97)) * **snacks.picker:** respect lazyvim.config.kind_filter ([#5415](https://github.com/LazyVim/LazyVim/issues/5415)) ([df7426e](https://github.com/LazyVim/LazyVim/commit/df7426eefa79d5dfa2fcbe2f381abfb2cca70bad))   ### Performance Improvements  * **java:** setting opts.dap_main to false to disable main class scan ([#5391](https://github.com/LazyVim/LazyVim/issues/5391)) ([66c3577](https://github.com/LazyVim/LazyVim/commit/66c3577bc779d31a7c2addd47de7cc6d215795ba)) 
```

### 2025-01-18T22:59:34Z [**nova-video-player/aos-AVP**](https://github.com/nova-video-player/aos-AVP)

```
- real regression fix for not scanning external usb storage devices when adding files to external storage - real fix for external & pgs subtitles stuck sometimes 
```

### 2025-01-21T22:39:26Z [**Loyalsoldier/clash-rules**](https://github.com/Loyalsoldier/clash-rules)

```
 
```

### 2025-01-17T03:06:01Z [**TBXark/ChatGPT-Telegram-Workers**](https://github.com/TBXark/ChatGPT-Telegram-Workers)

```
 - Add full support for `Telegram MarkdownV2` 
```

### 2025-01-18T13:52:20Z [**rfjakob/gocryptfs**](https://github.com/rfjakob/gocryptfs)

```
See https://github.com/rfjakob/gocryptfs/wiki/Release-Tarballs for what to download, how the verify the gpg signatures, where to find the changelog, and download statistics. 
```

### 2025-01-17T03:35:11Z [**nxtrace/NTrace-core**](https://github.com/nxtrace/NTrace-core)

```
## What's Changed * 解决网络不通时的卡死问题 in 6c49957 * 更新 Golang 到 v1.23.4 ,以及其他依赖更新到最新 in 69588b0  ⚠️ 由于 Golang 更新v1.23，须注意编译时需要加"-ldflags=-checklinkname=0"参数  **Full Changelog**: https://github.com/nxtrace/NTrace-core/compare/v1.3.6...v1.3.7 
```

### 2025-01-16T09:24:14Z [**alibaba/canal**](https://github.com/alibaba/canal)

```
# 功能新增 * 适配MySQL 8.4、Mariadb 11、Percona 8.0、PolarDB-X 2.0的版本 #4940 #5231 #5012 * 新增clickhouse的adapter #4957 * 深度适配PolarDB-X集中分布式一体化版的binlog解析，复用polardbx-parse的SQL解析工具包 #5097 * 新增helm chart支持，[使用说明](https://github.com/alibaba/canal/blob/master/charts/README.md)  # 重要优化 * canal默认admin.passwd风险说明 #4941 * spring读取远程配置文件触发RCE漏洞 #5154 * 支持SSL/TLS协议链接源端MySQL库 #5147 * 支持caching_sha2_password密码策略 #5301 * 支持rabbitmq SSL协议认证 #4965  * 支持es8证书认证 #5106 * 支持pulsar更多参数属性 #5191  # 小需求&bugfix * 修复docker启动，避免无用的高权限 #5337 * 兼容MariaDB GTID 为空的情况 #5352 * 优化集群模式的client的内存溢出风险 #5290 * 修复集群模式的mq消费，避免zk出现session time out时出现多消费者 #5270 * 修复client adapter同个instance配置多个group会共享CanalMsgConsumer，导致出现并发问题 #5175 * 修复spring读取远程配置文件触发RCE漏洞 #5154 * 修复部分json格式解析失败问题 #5130 #5018 * 修复TableMetaTSDB遇到的DDL关键字解析失败 #4899 
```

### 2025-01-20T16:30:20Z [**rustdesk/rustdesk**](https://github.com/rustdesk/rustdesk)

```
![image](https://github.com/rustdesk/rustdesk/assets/71636191/83754a64-31b8-47f0-8570-da22207759a9)  | Architecture | Windows | Ubuntu | Mac | Android | Flatpak | iOS | Web | |--------------|---------|--------|-----|----------|---------|---------|---------| | x86-64 (64-bit) | [EXE](https://github.com/rustdesk/rustdesk/releases/download/1.3.7/rustdesk-1.3.7-x86_64.exe) &nbsp; [MSI](https://github.com/rustdesk/rustdesk/releases/download/1.3.7/rustdesk-1.3.7-x86_64.msi) | [Download](https://github.com/rustdesk/rustdesk/releases/download/1.3.7/rustdesk-1.3.7-x86_64.deb) | [Download](https://github.com/rustdesk/rustdesk/releases/download/1.3.7/rustdesk-1.3.7-x86_64.dmg) | [Universal](https://github.com/rustdesk/rustdesk/releases/download/1.3.7/rustdesk-1.3.7-universal-signed.apk) | [Download](https://github.com/rustdesk/rustdesk/releases/download/1.3.7/rustdesk-1.3.7-x86_64.flatpak) |  | [Go](https://rustdesk.com/web) | | AArch64 (ARM64) |  | [Download](https://github.com/rustdesk/rustdesk/releases/download/1.3.7/rustdesk-1.3.7-aarch64.deb) | [Download](https://github.com/rustdesk/rustdesk/releases/download/1.3.7/rustdesk-1.3.7-aarch64.dmg) | [Download](https://github.com/rustdesk/rustdesk/releases/download/1.3.7/rustdesk-1.3.7-aarch64-signed.apk) | [Download](https://github.com/rustdesk/rustdesk/releases/download/1.3.7/rustdesk-1.3.7-aarch64.flatpak) |  [TestFlight](https://testflight.apple.com/join/KBG9EsZW) | | | ARMv7 (32-bit) |  | [Download](https://github.com/rustdesk/rustdesk/releases/download/1.3.7/rustdesk-1.3.7-armv7-sciter.deb) |  |  [Download](https://github.com/rustdesk/rustdesk/releases/download/1.3.7/rustdesk-1.3.7-armv7-signed.apk) |  |  | | x86-32 (32-bit) | [EXE](https://github.com/rustdesk/rustdesk/releases/download/1.3.7/rustdesk-1.3.7-x86-sciter.exe) |  |  |  |  |  |   ## For more downloads ([Fedora](https://github.com/rustdesk/rustdesk/releases/download/1.3.7/rustdesk-1.3.7-0.x86_64.rpm) / [Arch Linux](https://github.com/rustdesk/rustdesk/releases/download/1.3.7/rustdesk-1.3.7-0-x86_64.pkg.tar.zst) / [Suse](https://github.com/rustdesk/rustdesk/releases/download/1.3.7/rustdesk-1.3.7-0.x86_64-suse.rpm) / [AppImage](https://github.com/rustdesk/rustdesk/releases/download/1.3.7/rustdesk-1.3.7-x86_64.AppImage)): [check below please](#)  ## For the latest features: [check out the nightly build](https://github.com/rustdesk/rustdesk/releases/tag/nightly)  # Changelog   <details>  <summary>Changelog</summary>  # Changes - New qos ([#10459](https://github.com/rustdesk/rustdesk/pull/10459)) - Create seperate executable for `--service` to avoid "app not open any more" problem on mac completely ([#10210](https://github.com/rustdesk/rustdesk/discussions/10210))  # Fixes - Andriod update button cannot be clicked ([#9407](https://github.com/rustdesk/rustdesk/discussions/9407#discussioncomment-11690318)) - Image blur occurring at the moment of changing quality ([#10399](https://github.com/rustdesk/rustdesk/pull/10399)) - Lock the zoom when control on Android device ([#10426](https://github.com/rustdesk/rustdesk/issues/10426)) 
```

### 2025-01-20T17:34:51Z [**rustdesk/rustdesk-server**](https://github.com/rustdesk/rustdesk-server)

```
------ # This is the open-source version, not the [`Pro`](https://github.com/rustdesk/rustdesk-server-pro/releases/latest) version that you purchased a *`license`* for. <details>  # Das ist die Open-Source-Version, nicht die [`Pro`](https://github.com/rustdesk/rustdesk-server-pro/releases/latest)-Version, für die Sie eine Lizenz erworben haben.  # Voici la version open source, pas la version [`Pro`](https://github.com/rustdesk/rustdesk-server-pro/releases/latest) pour laquelle vous avez acheté une licence.  # Esta es la versión de código abierto, no la versión [`Pro`](https://github.com/rustdesk/rustdesk-server-pro/releases/latest) para la cual adquirió una licencia.  # 这是开源版本，不是您 *`购买`* 了许可证的[`专业版`](https://github.com/rustdesk/rustdesk-server-pro/releases/latest)。  </details>  -----    * Version check and refactor hbb_common to share with rustdesk client 
```

### 2025-01-16T02:20:07Z [**iiordanov/remote-desktop-clients**](https://github.com/iiordanov/remote-desktop-clients)

```
RELEASE-v5.7.5 
```

### 2025-01-16T04:34:31Z [**tongchengbin/ocean_ctf**](https://github.com/tongchengbin/ocean_ctf)

```
重构前端样式 
```

### 2025-01-15T14:45:43Z [**nikoksr/notify**](https://github.com/nikoksr/notify)

```
## What's Changed * Allows to set custom properties on a teams client by @firefart in https://github.com/nikoksr/notify/pull/927   **Full Changelog**: https://github.com/nikoksr/notify/compare/v1.2.0...v1.3.0 
```

### 2025-01-20T10:30:48Z [**pwndbg/pwndbg**](https://github.com/pwndbg/pwndbg)

```
**This release features LLDB support, improved performance, bug fixes and enhanced embedded systems experience. Pwndbg can now run on macOS (both Intel & Apple Silicon) and allows for debugging Mach-O binaries.**  Thanks to everyone who made it happen, especially (for most commits) to @patryk4815, @mbrla0, @peace-maker, and @fidgetingbits!  Want to support us or buy us a coffee? See our [Pwndbg sponsors page](https://github.com/sponsors/pwndbg)!  Also, want to split Pwndbg context displays with tmux? See [jcfg's blog post](https://blog.jcfg.re/posts/pwndbg-tmux/)!  ## Major changes * New features   * Added LLDB support. Most of Pwndbg functionality was ported to a debugger-agnostic library (`aglib`) that supports both GDB and LLDB. See also ["When to use GDB or LLDB"](https://github.com/pwndbg/pwndbg?tab=readme-ov-file#when-to-use-gdb-or-lldb) and [GDB vs LLDB commands](https://github.com/pwndbg/pwndbg/blob/dev/FEATURES.md#gdb-vs-lldb).   * Added macOS and Mach-O support via LLDB (Intel & Apple Silicon)     * pwndbg-gdb also works on macOS, but only for remote debugging (e.g., `target remote 0:1337`)   * Added support for text user interface (TUI) in GDB (set with `tui layout pwndbg` or `tui layout pwndbg_code`)   * Added context history. The displayed contexts are saved in history and can be re-seen with `contextprev` and `contextnext` commands * New commands added:   * `gdt <addr>` - dumps Global Descriptor Table entries from a given address   * `strings` - search memory for readable strings, like with the `strings` CLI utility   * `jemalloc_heap`, `jemalloc_extent_info`, `jemalloc_find_extent` - inspect jemalloc heap allocator structures   * `hijack-fd <fd> <newfile>` - modify the process file descriptor   * `kallsyms` and `klookup` - added Linux kernel debugging helpers for looking up symbol tables   * `profiler {start,stop}` - added a profiler command to benchmark Pwndbg performance/bottlenecks * Improvements   * Improved the experience with embedded systems debugging (better vmmap detection; improved `vmmap_add` and `vmmap_load` commands)   * The `ropgadget` command now dumps memory and finds gadgets in all executable regions   * `context <section[s]>` now has `--on|--off` toggle to temporarily disable sub-sections   * `plist` now supports `--offset` and `--count` to limit the linked list elements to be printed   * Added `vmmap -C <N> <filter>` command to display N pages before/after the filtered one   * Speed up syntax highlighting via pygments and Pwndbg startup time * Others   * Dropped Python 3.8 / Ubuntu 20.04 / Debian 11 support   * Lots and lots of bug fixes  ## Full changelog The full changelog can be found here: https://github.com/pwndbg/pwndbg/compare/2024.08.29...2025.01.20  ## New Contributors * @itaysnir made their first contribution in https://github.com/pwndbg/pwndbg/pull/2408 * @AadishJ made their first contribution in https://github.com/pwndbg/pwndbg/pull/2433 * @gfelber made their first contribution in https://github.com/pwndbg/pwndbg/pull/2431 * @MY7H404 made their first contribution in https://github.com/pwndbg/pwndbg/pull/2460 * @Polaris-Snowfall made their first contribution in https://github.com/pwndbg/pwndbg/pull/2466 * @jkub6 made their first contribution in https://github.com/pwndbg/pwndbg/pull/2482 * @giuseppelettieri made their first contribution in https://github.com/pwndbg/pwndbg/pull/2484 * @AndersFelde made their first contribution in https://github.com/pwndbg/pwndbg/pull/2478 * @kapiw04 made their first contribution in https://github.com/pwndbg/pwndbg/pull/2505 * @koalajoe23 made their first contribution in https://github.com/pwndbg/pwndbg/pull/2599 * @ksen-lin made their first contribution in https://github.com/pwndbg/pwndbg/pull/2595 * @JasonnnW3000 made their first contribution in https://github.com/pwndbg/pwndbg/pull/2660 * @beatweichsler made their first contribution in https://github.com/pwndbg/pwndbg/pull/2668 * @richyliu made their first contribution in https://github.com/pwndbg/pwndbg/pull/2670 
```

### 2025-01-17T14:32:20Z [**Eugeny/tabby**](https://github.com/Eugeny/tabby)

```
# Changes - f9dadf0: Set the application's dark mode to follow the app settings on macOS. (#10186) (fireblue) [#10186](https://github.com/Eugeny/tabby/pull/10186) - 66c173b: Keep the translucency effect even when the window loses focus on macOS. (#10196) (fireblue) [#10196](https://github.com/Eugeny/tabby/pull/10196)  # Fixes - 92c729d: fixed keyboard-interactive authentication and random session crashes  - 6ffeb61: fixed dropping files into the terminal not inserting the path - fixes #10221, fixes #10206  - d8d346c: fixed agent auth 
```

### 2025-01-17T01:53:36Z [**theonedev/onedev**](https://github.com/theonedev/onedev)

```
## Installation Guide  https://docs.onedev.io/category/installation-guide  ## Change Log  https://code.onedev.io/onedev/server/~builds/5855/fixed-issues?query=%22State%22+is+%22Released%22+order+by+%22Type%22+asc+and+%22Priority%22+desc  ## Incompatibilities  https://code.onedev.io/onedev/server/~builds/5855/markdown/Incompatibilities/server-product/system/incompatibilities/incompatibilities.md 
```

### 2025-01-21T14:38:31Z [**ccxt/ccxt**](https://github.com/ccxt/ccxt)

```
## What's Changed * fix(binance): fetchOpenOrder docs by @carlosmiei in https://github.com/ccxt/ccxt/pull/24939 * fix: docs build by @pcriadoperez in https://github.com/ccxt/ccxt/pull/24940 * fix: csharp action - upgrade to net 7.0 by @pcriadoperez in https://github.com/ccxt/ccxt/pull/24941 * feat(paymium) - features by @ttodua in https://github.com/ccxt/ccxt/pull/24931 * feat(tradeogre) - features by @ttodua in https://github.com/ccxt/ccxt/pull/24936 * feat(timex) - features by @ttodua in https://github.com/ccxt/ccxt/pull/24934 * feat(probit) - features by @ttodua in https://github.com/ccxt/ccxt/pull/24932 * withdraw with memo by @shenmush in https://github.com/ccxt/ccxt/pull/24938 * fix(mexc): inverse subType by @carlosmiei in https://github.com/ccxt/ccxt/pull/24945 * feat(tokocrypto) - features by @ttodua in https://github.com/ccxt/ccxt/pull/24935 * fix(coinex) - SOL network fix ^ by @ttodua in https://github.com/ccxt/ccxt/pull/24947 * Hollaex ohlcv by @samgermain in https://github.com/ccxt/ccxt/pull/24922 * feat(alpaca): add createMarketOrderWithCost by @carlosmiei in https://github.com/ccxt/ccxt/pull/24952 * fix(kucoin) - fetchCurrencies new data by @ttodua in https://github.com/ccxt/ccxt/pull/24055 * feat(binance): protect safeMarket call by @carlosmiei in https://github.com/ccxt/ccxt/pull/24958 * build: skip-tests by @carlosmiei in https://github.com/ccxt/ccxt/pull/24960 * fix(kucoin) - parsing networks & fees by @ttodua in https://github.com/ccxt/ccxt/pull/24956 * build: skip-tests by @carlosmiei in https://github.com/ccxt/ccxt/pull/24969 * okcoin, tokocrypto, whitebit updated fetchTime by @AresArtemius in https://github.com/ccxt/ccxt/pull/24954 * fix(blofin) - features ohlcv by @ttodua in https://github.com/ccxt/ccxt/pull/24957 * feat(binance): add portfolio/negative-balance-exchange-record by @carlosmiei in https://github.com/ccxt/ccxt/pull/24953 * fix(binance) - historical trades by @ttodua in https://github.com/ccxt/ccxt/pull/24955 * feat(transpiler): add OpenInterest type by @carlosmiei in https://github.com/ccxt/ccxt/pull/24973 * build: skip-tests by @carlosmiei in https://github.com/ccxt/ccxt/pull/24974  ## New Contributors * @shenmush made their first contribution in https://github.com/ccxt/ccxt/pull/24938  **Full Changelog**: https://github.com/ccxt/ccxt/compare/4.4.49...4.4.50 
```

### 2025-01-20T19:49:28Z [**miniflux/v2**](https://github.com/miniflux/v2)

```
* test(js): improve `.jshintrc` (strict comparison, etc...) * test(sanitizer): add a fuzzer * refactor(rewriter): use custom title case converter implementation instead of `golang.org/x/text/cases.Title()` * refactor(readingtime): replace `whatlanggo` package with an ad-hoc implementation * refactor(oauth2): no need to use `io.WriteString` when sha256 provides a way to obtain a sum in a single call * refactor(js): simplify a bit `keyboard_handler.js` * refactor(js): remove an outdated check for `{passive: true}` * refactor(js): minor refactoring of `touch_handler.js` * refactor(js): minor improvements in `app.js` * refactor(database): add special handling for PostgreSQL-specific migrations * fix(ui): reading preferences are reset if the form values are incorrect * fix(sanitizer): allow `<hr>` tags * fix(finder): do not add redirections to the list of subscriptions to avoid confusion * fix: update Wallabag URL label to avoid confusion * fix: improve pagination when having identical publication date * fix: do not strip tags in Atom entry title * feat(ntfy): Add option to use internal links * feat(locale): update Polish translation * feat(locale): update German translation * feat(integration): add Discord integration * feat(database): add optional build support for SQLite * feat: validate usernames upon creation * feat: replace `%{?systemd_requires}` with `%{?systemd_ordering}` * feat: bump linter and minifier from ECMAScript 2017 to 2020 (ES11) * feat: add `fix_ghost_cards` rewrite rule * ci: tighten the CodeQL rules * ci: run Docker tests only when the Dockerfiles are modified * ci: run `-race -cover` only on Ubuntu jobs * ci: don't specify languages for CodeQL * ci: don't run `go vet ./...` as it's run as part of `golangci-lint` * ci: checkout before installing Go to improve cache efficiency * ci: avoid building Linux packages for each pull-request * build(deps): bump `golang.org/x/oauth2` from `0.24.0` to `0.25.0` * build(deps): bump `golang.org/x/net` from `0.33.0` to `0.34.0` * build(deps): bump `golang.org/x/crypto` from `0.31.0` to `0.32.0` * build(deps): bump `github.com/tdewolff/minify/v2` from `2.21.2` to `2.21.3` * build(deps): bump `github.com/PuerkitoBio/goquery` from `1.10.0` to `1.10.1` * build(deps): bump `github.com/coreos/go-oidc/v3` from `3.11.0` to `3.12.0` 
```

### 2025-01-19T09:47:39Z [**davatorium/rofi**](https://github.com/davatorium/rofi)

```
## Fix drawing issue  In the last release we had some code that hit a bug in some graphics drivers. The fix that went in had a side-effect causing borders not to be drawn as expected. This release should fix that.  Issue: #2076  ## DBusActivatable  The previously introduced DBusActivatable seems to cause some issues and confusion. First if the application (dconf-editor looking at you) does not acknowledge it launched rofi stays open until it times out. By default this is 15 seconds. We reduced the timeout to 1.5 seconds and added an option to disable DBusActivatable.  The 2nd point is, that if you launch an application via DBusActivatable it is not launched by rofi and does not inherits rofi's environment, but the one systemd is configured to use for that user. The archlinux documentation explains this and how to fix this [here](https://wiki.archlinux.org/title/Systemd/User#Environment_variables).  Issue: #2077  ## CI Fixes  Because of some deprecation, the CI scripts are updated. It might be useful for people who want to help to test the latest rofi that for every commit an artifact is build with a 'source package' you can install.  You can find them [here](https://github.com/davatorium/rofi/actions/workflows/build.yml) by clicking on the commit you want and scrolling to the bottom of the page. This contains a zip with the two normal source tarballs.  ## Changelog  * Fix buffer overflow in rofi -e after reading from stdin (#2082) (Thanks to Faule Socke) * [DRun] Reduce DBus timeout to 1500ms add option to disable DBusActivatable.   Issue: #2077 * [CI] Do explicit compare with 'true'? * [CI] Fix typo in conditional. * [CI] Only make dist on one build. * [CI] Fix identical name? * [CI] Bump upload action to v4 * [Widget] Actually remove ADD operator from border drawing.   Issue: #2076 * [widget] Remove the ADD operator.   Issue: #2076 * Add 1.7.7 docs to README. * Mark as dev version 
```

### 2025-01-17T07:29:50Z [**pingcap/tidb**](https://github.com/pingcap/tidb)

```
For new features, improvements, and bug fixes released in v8.5.1 for TiDB, see [TiDB v8.5.1 release notes](https://docs.pingcap.com/tidb/stable/release-8.5.1).  See the difference from the issue perspective: <details>  - pingcap/tidb#57816 - pingcap/tidb#57698 - pingcap/tidb#57230 - pingcap/tidb#55632 - pingcap/tidb#57625 - pingcap/tidb#57871 - pingcap/tidb#56733 - pingcap/tidb#58378 - pingcap/tidb#58001 - pingcap/tidb#58004 - pingcap/tidb#56828 - pingcap/tidb#57609 - pingcap/tidb#58114 - pingcap/tidb#52742 - pingcap/tidb#58366 - pingcap/tidb#58476 - pingcap/tidb#57583 - pingcap/tidb#57889 - pingcap/tidb#57301 - pingcap/tidb#58452 - pingcap/tidb#57708 - pingcap/tidb#58430 - pingcap/tidb#57556 - pingcap/tidb#58480 - pingcap/tidb#58107 - pingcap/tidb#58510 - pingcap/tidb#52747 - pingcap/tidb#57784 - pingcap/tidb#57915 - pingcap/tidb#57990 - pingcap/tidb#58205 - pingcap/tidb#58305 - pingcap/tidb#58484 - pingcap/tidb#58738 - pingcap/tidb#58014 - pingcap/tidb#58226 - pingcap/tidb#58836 - pingcap/tidb#58837 - pingcap/tidb#51723 - pingcap/tidb#58843 - pingcap/tidb#57996 - pingcap/tidb#58870 - pingcap/tidb#58865 - pingcap/tidb#58875  </details> 
```

