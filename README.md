# Repositories with Latest Commits within 7 days

### 2024-11-20T04:40:31Z [**modstart-lib/aigcpanel**](https://github.com/modstart-lib/aigcpanel)

```
- 新增：数字人增加视频合成功能 - 优化：图表文件静态化 - 优化：Windows 系统下界面阴影问题，避免和白色背景冲突 - 优化：beta 打包版本号显示优化，方便区分不同 snapshot 版本 - 优化：Mac 系统下全屏不能退出问题 - 优化：Mac 系统下隐藏窗口自动隐藏图标 - 优化：默认禁用 GPU 加速功能 - 优化：获取可用端口逻辑功能优化 - 优化：Windows 系统下进程输出编码乱码问题 - 优化：软件图标尺寸 - 优化：模型重构，使用 server.js 方式启动 
```

### 2024-11-23T15:22:13Z [**richards199999/Thinking-Claude**](https://github.com/richards199999/Thinking-Claude)

```
## What's Changed * Add missing <anthropic_thinking_protocol> by @ruanyl in https://github.com/richards199999/Thinking-Claude/pull/27 * adding file structure, and rewriting the installation instruction by @salemon in https://github.com/richards199999/Thinking-Claude/pull/29 * structure reogranize by @salemon in https://github.com/richards199999/Thinking-Claude/pull/36 * BREAKING CHANGE: Reconstruct Chrome Extension Architecture for Production-Grade Scalability (v3.0.0) by @lumpinif in https://github.com/richards199999/Thinking-Claude/pull/39  ## New Contributors * @ruanyl made their first contribution in https://github.com/richards199999/Thinking-Claude/pull/27 * @salemon made their first contribution in https://github.com/richards199999/Thinking-Claude/pull/29  **Full Changelog**: https://github.com/richards199999/Thinking-Claude/compare/v2.1...v3.0.0 
```

### 2024-11-24T19:10:08Z [**Yaozhuwa/easy-typing-obsidian**](https://github.com/Yaozhuwa/easy-typing-obsidian)

```
- V5.5.9 2024-11-23   - 严格换行模式支持三种模式（两次换行，两次空格+换行，混合模式）     - 双空格模式：回车会变成两次空格+换行 #193     - 混合模式是在引用块中使用两次空格+换行，在其他地方使用两次换行   - 修复了列表中代码块结尾回车时，触发两次换行的问题   - 增加了选中当前文本块的快捷键命令 #256   - 修改了选中文本块的逻辑，目前不需要严格换行模式也把相邻的文本行作为同一文本块的内容 #255。   - Strict line break mode supports three modes (double line break, double space + line break, mixed mode) #193     - Double space mode: Enter will become double space + line break     - Mixed mode uses double space + line break in quote blocks, and double line break elsewhere   - Fixed the issue where pressing Enter at the end of a code block in a list triggered a double line break   - Added a shortcut command to select the current text block #256   - Modified the logic for selecting text blocks, now adjacent text lines are considered as the same text block even without strict line break mode #255. 
```

### 2024-11-26T16:13:02Z [**levkk/rwf**](https://github.com/levkk/rwf)

```
### What's Changed  - Fix bug in URL parsing and formatting - Fix leak in connection pool - Log connection age when closing it 
```

### 2024-11-26T04:42:51Z [**lejianwen/rustdesk-api**](https://github.com/lejianwen/rustdesk-api)

```
 
```

### 2024-11-26T07:27:48Z [**certd/certd**](https://github.com/certd/certd)

```
## [1.27.9](https://github.com/certd/certd/compare/v1.27.8...v1.27.9) (2024-11-26)   ### Performance Improvements  * 通知支持自定义webhook、anpush、iyuu、server酱 ([cbccd9e](https://github.com/certd/certd/commit/cbccd9e3d0a4c24aba772af62734666d40b22c57)) * 通知支持vocechat、bark、telegram、discord、slack ([642f57f](https://github.com/certd/certd/commit/642f57ff6d7152a9e14f59c7fc0e32a6b1751fb7)) 
```

### 2024-11-26T14:36:53Z [**PBH-BTN/PeerBanHelper**](https://github.com/PBH-BTN/PeerBanHelper)

```
7.1.5 是 7.1 系列的一个错误修复版本，不包含功能更新。与往常一样，我们持续更新 PeerBanHelper 以修复一些已知问题。  ## 错误修复  * 修复 PeerBanHelper 在 Windows 操作系统下，即使使用 NoGUI 运行依然加载 AWT 相关组件，并触发 AWT 的漏洞导致程序崩溃的问题 @Ghost-chu    * 现在使用 NoGUI 模式启动时，将阻止 AWT 注册   * GUI 崩溃的问题是 Java VM 的问题，我们仍在等待 Java 24 发布以解决此问题 * [WebUI] 修复不输入任何 IP 的情况下点击 IP 查询按钮引发 WebUI 页面错误的问题 @Gaojianli  * [WebUI] 修复编辑城市规则时在罕见情况下可能删除现有的城市规则的问题 @Gaojianli   ## 调整  * 新的 PeerBanHelper 安装在规则订阅中默认包含未启用的 Tor Exit Node 规则 @Ghost-chu  * 优化运行内存（Heap）占用 @Ghost-chu  ## 已知问题  * 在 Windows 平台上运行带有 GUI 版本的 PeerBanHelper 时如遇屏幕分辨率更改（如连接远程桌面 RDP 等）会导致崩溃   * 这是 Java VM 的 AWT 组件的故障，只能由 Java VM 团队修复，我们仍在等待修复   * 受影响的 Windows 用户在更新到 v7.1.5 后，使用 NoGUI 模式运行即可解决崩溃问题   * Linux 和 macOS 的 GUI 界面不受此问题的影响 * 在未完成/不完整/部分做种的种子上做种时，可能错误标记此种子上的其它 Peer 为吸血   * 通过 https://github.com/PBH-BTN/PeerBanHelper/pull/748 修复，将与 7.2 版本一同发布修复  ## Docker  DockerHub: `ghostchu/peerbanhelper:v7.1.5` 阿里云国内镜像加速: `registry.cn-hangzhou.aliyuncs.com/ghostchu/peerbanhelper:v7.1.5` 
```

### 2024-11-21T16:23:23Z [**go-acme/lego**](https://github.com/go-acme/lego)

```
## Changelog  Publish the Snap to the Snapcraft stable channel. 
```

### 2024-11-21T15:38:32Z [**ZGGSONG/STranslate**](https://github.com/ZGGSONG/STranslate)

```
## 更新  - 新增: 可选截图翻译识别文字后自动复制 - 优化: 翻译时取消显示提示信息 - 优化: 优化输入框选中后粘贴的文本 - 优化: AzureTTS EdgeTTS下拉框卡顿的问题 - 优化: 替换翻译添加服务打印 - 优化: 优化划词后焦点位置 - 优化: 移除显示、隐藏输入框时UI通知 - 修复: 鼠标划词 Adobe Acrobat Pro 取词失败的问题 - 修复: DeepL服务目标语种中文繁体失效的问题  **完整更新日志:** [1.2.10.1117...1.2.11.1121](https://github.com/ZGGSONG/STranslate/compare/1.2.10.1117...1.2.11.1121)  ## 离线数据  [123 网盘](https://www.123pan.com/s/AxlRjv-OuVmA.html) 
```

### 2024-11-21T21:47:57Z [**wavetermdev/waveterm**](https://github.com/wavetermdev/waveterm)

```
## What's Changed  New minor release that introduces Wave's connected computing extensions. We've introduced new `wsh` commands that allow you to store variables and files, and access them across terminal sessions (on both local and remote machines).  - `wsh setvar/getvar` to get and set variables -- [Docs](https://docs.waveterm.dev/wsh#getvarsetvar) - `wsh file` operations (cat, write, append, rm, info, cp, and ls) -- [Docs](https://docs.waveterm.dev/wsh#file) - Improved golang panic handling to prevent backend crashes - Improved SSH config logging and fixes a reused connection bug - Updated telemetry to track additional counters - New configuration settings (under "window:magnifiedblock") to control magnified block margins and display - New block/zone aliases (client, global, block, workspace, temp) - `wsh ai` file attachments are now rendered with special handling in the AI block - New ephemeral block type for creating modal widgets which will not disturb the underlying layout - Editing the AI presets file from the Wave AI block now brings up an ephemeral editor - Clicking outside of a magnified bglock will now un-magnify it - New button to clear the AI chat (also bound to Cmd-L) - New button to reset terminal commands in custom cmd widgets - [bugfix] Presets directory was not loading correctly on Windows - [bugfix] Magnified blocks were not showing correct on startup - [bugfix] Window opacity and background color was not getting applied properly in all cases - [bugfix] Fix terminal theming when applying global defaults [#1287](https://github.com/wavetermdev/waveterm/issues/1287) - MacOS 10.15 (Catalina) is no longer supported - Other bug fixes, docs improvements, and dependency bumps   **Full Changelog**: https://github.com/wavetermdev/waveterm/compare/v0.9.2...v0.9.3 
```

### 2024-11-24T07:45:27Z [**jonssonyan/h-ui**](https://github.com/jonssonyan/h-ui)

```
- Added custom sort ACL rules - Fixed the default value of insecure in Hysteria2 sharing links to 0 --- - 新增自定义排序 ACL 规则 - 修复 Hysteria2 分享链接中 insecure 默认值为0 
```

### 2024-11-26T07:47:25Z [**langgenius/dify**](https://github.com/langgenius/dify)

```
## Bug Fixes in v0.12.1  1. **Webapp Custom Icons**: Fixed display issues for custom icons in the webapp. #11094  2. **Start Form File Handling**: Addressed the inability to use files in the Start form. #11112  3. **LLM Memory Processing**: Corrected errors in LLM memory handling.  #11103 and #11106  4. **Conversation Deletion**: Fixed conversation removal issues. #11076  5. **App Creation and Template Import**: Resolved errors during app creation and template import. #11091, #11092 and #11108  These fixes ensure improved functionality and reliability across the platform.  ---  ## Upgrade Guide  ### Docker compose deployments  1. Back up your customized docker-compose YAML file (optional)     bash    cd docker    cp docker-compose.yaml docker-compose.yaml.$(date +%s).bak      2. Get the latest code from the main branch     bash    git checkout main    git pull origin main      3. Stop the service，Command, please execute in the docker directory     bash    docker compose down      4. Back up data     bash    tar -cvf volumes-$(date +%s).tgz volumes      5. Upgrade services     bash    docker compose up -d      ### Source Code deployments  1. Stop API server, Worker and Web frontend Server.  2. Get the latest code from the release branch:     bash    git checkout 0.12.1      3. Update Python dependencies:     bash    cd api    poetry install      7. Then, let's run the migration script:     bash    poetry run flask db upgrade      8. Finally, run API server, Worker and Web frontend Server again.  ---  ## What's Changed * fix: drop useless and wrong code for zhipu embedding by @yihong0618 in https://github.com/langgenius/dify/pull/11069 * fix: chart tool chinese font display and raise error by @hjlarry in https://github.com/langgenius/dify/pull/11058 * Add grok-vision-beta to xAI + Update grok-beta Features by @taowang1993 in https://github.com/langgenius/dify/pull/11004 * fix: timezone not imported in conversation service. by @laipz8200 in https://github.com/langgenius/dify/pull/11076 * fix: int None will cause error for context size by @yihong0618 in https://github.com/langgenius/dify/pull/11055 * fix: update the max tokens configuration for Azure GPT-4o (2024-08-06) to 16384 by @fengjiajie in https://github.com/langgenius/dify/pull/11074 * fix: import Explore Apps raise error by @hjlarry in https://github.com/langgenius/dify/pull/11091 * Add query_prefix + Return TED Transcript URL for Downstream Scraping Tasks by @taowang1993 in https://github.com/langgenius/dify/pull/11090 * SearchApi - Return error message instead of raising a ValueError by @SebastjanPrachovskij in https://github.com/langgenius/dify/pull/11083 * fix: site icon not showing by @xuzuodong in https://github.com/langgenius/dify/pull/11094 * fix #11091 raise redirect issue by @hjlarry in https://github.com/langgenius/dify/pull/11092 * fix: ops_trace_manager `from_end_user_id` by @horochx in https://github.com/langgenius/dify/pull/11077 * Fix regenerate themes by @douxc in https://github.com/langgenius/dify/pull/11101 * fix: user query be ignored if query_prompt_template is an empty string by @laipz8200 in https://github.com/langgenius/dify/pull/11103 * fix(llm_node): Ignore user query when memory is disabled. by @laipz8200 in https://github.com/langgenius/dify/pull/11106 * fix(anthropic_llm): Ignore non-text parts in the system prompt. by @laipz8200 in https://github.com/langgenius/dify/pull/11107 * fix: app copy raise error by @hjlarry in https://github.com/langgenius/dify/pull/11108 * fix: Cannot use files in the user inputs. by @laipz8200 in https://github.com/langgenius/dify/pull/11112 * feat: Allow to contains files in the system prompt even model not support. by @laipz8200 in https://github.com/langgenius/dify/pull/11111 * fix(llm_node): Ignore file if not supported. by @laipz8200 in https://github.com/langgenius/dify/pull/11114 * Add TTS to OpenAI_API_Compatible by @taowang1993 in https://github.com/langgenius/dify/pull/11071 * chore: bump to 0.12.1 by @laipz8200 in https://github.com/langgenius/dify/pull/11122  ## New Contributors * @fengjiajie made their first contribution in https://github.com/langgenius/dify/pull/11074  **Full Changelog**: https://github.com/langgenius/dify/compare/0.12.0...0.12.1 
```

### 2024-11-20T06:54:11Z [**Lips7/Matcher**](https://github.com/Lips7/Matcher)

```
**Full Changelog**: https://github.com/Lips7/Matcher/compare/v0.5.5...v0.5.6 
```

### 2024-11-26T17:44:06Z [**ast-grep/ast-grep**](https://github.com/ast-grep/ast-grep)

```
- fix: fix --config=config.yml arg parse [`#1617`](https://github.com/ast-grep/ast-grep/issues/1617) - fix: update python version [`#1614`](https://github.com/ast-grep/ast-grep/issues/1614) - fix(deps): update dependency @swc/core to v1.9.3 [`63c1c8d`](https://github.com/ast-grep/ast-grep/commit/63c1c8d01234da5747e0ade6162320a7edee3055) - chore: revert pyo3 [`2022f38`](https://github.com/ast-grep/ast-grep/commit/2022f387e4cbcc4c1763f06fad47bed024ca47c5) - feat: add rule entity inspection [`c569ec7`](https://github.com/ast-grep/ast-grep/commit/c569ec7b112f0d06a409258750a71cec3ad45722) 
```

### 2024-11-21T16:45:58Z [**yorukot/superfile**](https://github.com/yorukot/superfile)

```
## Install: [**Click me to know how to install**](https://github.com/yorukot/superfile?tab=readme-ov-file#installation)  > [!IMPORTANT]   > There are some problems with the configuration file of v1.1.5. > If you have any problem change file panel mode, You can manually change :  diff - change_panel_mode = ['ctrl+L', ''] + change_panel_mode = ['v', '']   ## Changelog  #### Update - Add sort case toggle [`#469`](https://github.com/yorukot/superfile/issues/469) - Add Sort options [`#420`](https://github.com/yorukot/superfile/pull/420) - Fix flashing when switching between panels [`#122`](https://github.com/yorukot/superfile/issues/122)  #### Bug fix - Fix some hotkey broken - Fix the searchbar to automatically put the open key into the searchbar [`ec9e256`](https://github.com/yorukot/superfile/commit/b20bc70fe9d4e0ee96931092a6522e8604cc017b)  ## New Contributors * @HuntTheSun made their first contribution in https://github.com/yorukot/superfile/pull/425 * @FahimAdib made their first contribution in https://github.com/yorukot/superfile/pull/448 * @brunoCCOS made their first contribution in https://github.com/yorukot/superfile/pull/462 * @knqti made their first contribution in https://github.com/yorukot/superfile/pull/458 * @emmanuel-ferdman made their first contribution in https://github.com/yorukot/superfile/pull/466  **Full Changelog**: https://github.com/yorukot/superfile/compare/v1.1.5...v1.1.6 
```

### 2024-11-23T05:40:01Z [**zhanglun/lettura**](https://github.com/zhanglun/lettura)

```
See the assets to download this version and install.  ## What's Changed * Feature/podcast by @zhanglun in https://github.com/zhanglun/lettura/pull/66 * feat: add styles by @zhanglun in https://github.com/zhanglun/lettura/pull/67 * Feature/podcast by @zhanglun in https://github.com/zhanglun/lettura/pull/68 * Feature/podcast by @zhanglun in https://github.com/zhanglun/lettura/pull/69   **Full Changelog**: https://github.com/zhanglun/lettura/compare/v0.1.19...v0.1.20 
```

### 2024-11-20T01:02:24Z [**dail8859/NotepadNext**](https://github.com/dail8859/NotepadNext)

```
## What's Changed * Add overtype toggling by @dail8859 in https://github.com/dail8859/NotepadNext/pull/589 * Search Box Positioning by @pydavem in https://github.com/dail8859/NotepadNext/pull/591 * Copy Search results #224 by @pydavem in https://github.com/dail8859/NotepadNext/pull/596 * Fix crashes with Qt 6.7.2 by @sandman7920 in https://github.com/dail8859/NotepadNext/pull/623 * Fix macro saving * Adjust JSON error colors * Add additional word chars by @dail8859 in https://github.com/dail8859/NotepadNext/pull/625 * Fix keywords for C by @dail8859 in https://github.com/dail8859/NotepadNext/pull/632 * Add backward direction to Find dialog by @accessv in https://github.com/dail8859/NotepadNext/pull/635 * Add loading of custom application styling by @dail8859 in https://github.com/dail8859/NotepadNext/pull/637 * Add option to sort file list by name by @dail8859 in https://github.com/dail8859/NotepadNext/pull/638 * Attempt to fix Win10 crash by @dail8859 in https://github.com/dail8859/NotepadNext/pull/639 * Update NotepadNext_sv_SE.ts by @eson57 in https://github.com/dail8859/NotepadNext/pull/606 * Updated Ukrainian translation by @YALdysse in https://github.com/dail8859/NotepadNext/pull/610 * Update Portuguese (Portugal) translation by @hugok79 in https://github.com/dail8859/NotepadNext/pull/579 * Update Traditional Chinese locale by @PeterDaveHello in https://github.com/dail8859/NotepadNext/pull/646 * Update Scintilla to v5.5.0 by @dail8859 in https://github.com/dail8859/NotepadNext/pull/587 * Update Lexilla to v5.3.2 by @dail8859 in https://github.com/dail8859/NotepadNext/pull/588  ## New Contributors * @pydavem made their first contribution in https://github.com/dail8859/NotepadNext/pull/591 * @sandman7920 made their first contribution in https://github.com/dail8859/NotepadNext/pull/623 * @accessv made their first contribution in https://github.com/dail8859/NotepadNext/pull/635  **Full Changelog**: https://github.com/dail8859/NotepadNext/compare/v0.8...v0.9 
```

### 2024-11-24T04:36:42Z [**KaringX/karing**](https://github.com/KaringX/karing)

```
1. Improved the current stack acquisition when the connection times out 2. Fixed the notification region matching logic error -------------------------------------------------------- 1. 改进连接超时时当前堆栈获取 2. 修复通知地区匹配逻辑错误 -------------------------------------------------------- android TV: android_armeabi-v7a.apk android mobile: android_arm64-v8a.apk android_arm.apk : contains android_armeabi-v7a.apk and android_arm64-v8a.apk windows : windows_x64.exe / windows_x64.zip 
```

### 2024-11-23T11:54:47Z [**babalae/better-genshin-impact**](https://github.com/babalae/better-genshin-impact)

```
## 5.2 适配性更新  * 七圣召唤更新@haokaiyang * 支持新角色数据 * 支持新地图数据 * Yap 模型更新 @Alex-Beng   ### 自动剧情  * **后台自动剧情模式不再会瞬移鼠标点击，直接使用5.2的F**，注意对话结束后鼠标仍会被吸附到游戏窗口内！  ### 自动秘境  * 修复 5.2 更新后点击跳过会点到锁定功能的问题  ## 全自动  * 联机情况下识别角色队伍时，修复错误识别房主的问题（会导致队伍识别出错） #777 * 修复脚本仓库订阅所有路径追踪脚本存在的一些问题 * JS脚本鼠标悬浮展示描述 * JS脚本在传入JS的 `settings` 对象为空时提示  ### 路径追踪 * 凌晨4点时候自动点击领取月卡 * 进入对话中时会自动选择选项并退出。 * 修复路径追踪部分变量写死的问题 * 小于 1920x1080 的游戏分辨率使用路径追踪会触发提示 * 新增了一些 `action`，具体功效见文档   ## 其他  * UI 优化 @Lightczx  
```

### 2024-11-26T06:58:23Z [**labring/FastGPT**](https://github.com/labring/FastGPT)

```
该 release 重新发布，修复一个 bug。  ## 新功能预览  ### 自动触发工作流  可以允许你配置用户加载对话时，自动触发一次工作流。可以用于一些 CRM 系统，可以快速的引导用户使用，无需等待用户主动触发。  | | | | --- | --- | | <img width="467" alt="image" src="https://github.com/user-attachments/assets/840d11c1-6337-40c1-a4a7-e68116584575"> | <img width="505" alt="image" src="https://github.com/user-attachments/assets/1dd58778-58ff-45ac-adc5-bf503a5b5f44"> |  ## 更新指南  ### 1. 做好数据备份  ### 2. 修改镜像  - 更新 FastGPT 镜像 tag: v4.8.14 - 更新 FastGPT 商业版镜像 tag: v4.8.14 （fastgpt-pro镜像） - Sandbox 镜像，可以不更新  ## 更新内容  1. 新增 - 工作流支持进入聊天框/点击开始对话后，自动触发一轮对话。 @newfish-cmyk  2. 新增 - 重写 chatContext，对话测试也会有日志，并且刷新后不会丢失对话。 @c121914yu  3. 新增 - 分享链接支持配置是否允许查看原文。 @c121914yu  4. 新增 - 新的 doc2x 插件。 by @Menghuan1918  5. 新增 - 繁体中文-台湾。 by @PeterDaveHello 6. 新增 - 分析链接和 chat api 支持传入自定义 uid。 7. 商业版新增 - 微软 oauth 登录 @newfish-cmyk  8. 优化 - 工作流 ui 细节。 @newfish-cmyk  9. 优化 - 应用编辑记录采用 diff 存储，避免浏览器溢出。 @newfish-cmyk  10. 优化 - 代码入口，增加 register 入口，无需等待首次访问才执行。 @c121914yu  11. 优化 - 工作流检查，增加更多缺失值检查。 @c121914yu  12. 优化 - 增加知识库训练最大重试次数限制。 @c121914yu  13. 优化 - 图片路径问题和示意图任务 by @Jiangween 14. 优化 - Milvus description by @JackLCL 15. 修复 - 分块策略，四级标题会被丢失。 同时新增了五级标题的支持。 @c121914yu  16. 修复 - MongoDB 知识库集合唯一索引。 @c121914yu  17. 修复 - 反选知识库引用后可能会报错。 @newfish-cmyk  18. 修复 - 简易模式转工作流，不是使用最新编辑记录进行转移。 @newfish-cmyk  19. 修复 - 表单输入的说明文字不显示。 @newfish-cmyk  20. 修复 - API 无法传递 base64 图片 @c121914yu   ## New Contributors * @JackLCL made their first contribution in https://github.com/labring/FastGPT/pull/3216  **Full Changelog**: https://github.com/labring/FastGPT/compare/v4.8.13...v4.8.14 
```

### 2024-11-25T11:32:59Z [**Calcium-Ion/new-api**](https://github.com/Calcium-Ion/new-api)

```
[fix: stt模型计费](https://github.com/Calcium-Ion/new-api/commit/7ebc1cfb6031ed8878d152d0f5d93abfbfdeb3b1) 
```

### 2024-11-24T21:01:40Z [**dockur/windows**](https://github.com/dockur/windows)

```
## What's Changed * docs: Readme by @kroese in https://github.com/dockur/windows/pull/920 * feat: Additional download mirrors by @kroese in https://github.com/dockur/windows/pull/923   **Full Changelog**: https://github.com/dockur/windows/compare/v4.04...v4.05 
```

### 2024-11-26T10:01:27Z [**open-webui/open-webui**](https://github.com/open-webui/open-webui)

```
## [0.4.5] - 2024-11-26  ### Added  - **🎨 Model Order/Defaults Reintroduced**: Brought back the ability to set model order and default models, now configurable via Admin Settings > Models > Configure (Gear Icon).  ### Fixed  - **🔍 Query Generation Issue**: Resolved an error in web search query generation, enhancing search accuracy and ensuring smoother search workflows. - **📏 Textarea Auto Height Bug**: Fixed a layout issue where textarea input height was shifting unpredictably, particularly when editing system prompts. - **🔑 Ollama Authentication**: Corrected an issue with Ollama’s authorization headers, guaranteeing reliable authentication across all endpoints. - **⚙️ Missing Min_P Save**: Resolved an issue where the 'min_p' parameter was not being saved in configurations. - **🛠️ Tools Description**: Fixed a key issue that omitted tool descriptions in tools payload. 
```

### 2024-11-26T17:18:15Z [**gitbutlerapp/gitbutler**](https://github.com/gitbutlerapp/gitbutler)

```
## New features - **Stacked Branches**: You can now split a lane into multiple, _dependent_ branches - **Stacked Pull Requests**: If your remote is GitHub, the app can create and manage stacks of PRs (where each PR targets its predecessor)  The stacking functionality allows you to split your work into smaller units (PRs) helping with the review process.  Files and diffs that are locked 🔒(depending on prior commits) can now be put in a separate branch within the same stack.  Here's a documentation page which describes in full how this works: https://docs.gitbutler.com/features/stacked-branches  ![GitButler_v0 14](https://github.com/user-attachments/assets/7fb88529-09a0-4f6b-8fa9-233c624704cf)  ## Fixes - Fixes a bug where the app does not prompt for ssh/https credentials when they are needed - Fixes a bug where the branch link was incorrect for some non-GitHub remotes - Fixes an issue where CI "neutral" status is not displayed as "passing" - Fixes a bug where commit message generation was not respecting the %{branch_name} placeholder - Adds a Cursor as an option to the "open in editor" config list  ## New Contributors * @evan-schott made their first contribution in https://github.com/gitbutlerapp/gitbutler/pull/5644  **Full Changelog**: https://github.com/gitbutlerapp/gitbutler/compare/release/0.13.17...release/0.14.0 
```

### 2024-11-23T22:09:50Z [**ImranR98/Obtainium**](https://github.com/ImranR98/Obtainium)

```
## What's Changed * Update hu.json by @summoner001 in https://github.com/ImranR98/Obtainium/pull/1977 * Update wiki links by @Hamster45105 in https://github.com/ImranR98/Obtainium/pull/1980 * Minor change to German translation (#1986) by @PrivacyAndSecurity in https://github.com/ImranR98/Obtainium/pull/1990 * By @ImranR98 in https://github.com/ImranR98/Obtainium/pull/1990   * Improved XAPK Support (#682)   * Custom user-agent for APKMirror (as per feedback in #1973)  **Full Changelog**: https://github.com/ImranR98/Obtainium/compare/v1.1.31...v1.1.32 
```

### 2024-11-25T16:12:59Z [**msgbyte/tianji**](https://github.com/msgbyte/tianji)

```
## [1.17.2](https://github.com/msgbyte/tianji/compare/v1.17.1...v1.17.2) (2024-11-25)   ### Features  * add free tier tip component ([1fc4d15](https://github.com/msgbyte/tianji/commit/1fc4d15c35e1c7b161aab968c4c8e595ef6c80b7)) * add workspace usage check which can update when tier has updated ([bf0598d](https://github.com/msgbyte/tianji/commit/bf0598dd25b8e1b868a5f3ea3fad53a58d8c9dd4))   ### Bug Fixes  * fix a bug that would accidentally pause the workspace ([420860f](https://github.com/msgbyte/tianji/commit/420860f1b6e25928d9444c9b64f7308dde83a472))   ### Others  * update translation ([df12949](https://github.com/msgbyte/tianji/commit/df1294977fcfd1e1005919d8d5cf8b9c926b0473)) 
```

### 2024-11-26T06:25:24Z [**reqable/reqable-app**](https://github.com/reqable/reqable-app)

```
### windows-macos-linux-android-ios - 🚀 [NEW] Fully support SSE real-time streaming. - 🚀 [NEW] API testing supports digest-auth authorization. - 🚀 [NEW] Add JSON tree viewer. - 💪 [OPT] Minor adjustments to the background colors of light and dark themes. - 💪 [OPT] MITM proxy server requests will display in the traffic list. - 💪 [OPT] The request body and response body will automatically save the state when switching between different views. - 💪 [OPT] The URL generated by the basic authorization request uses the `--basic` parameter instead of the `Authorization` request header. - 💪 [OPT] Payload with encoding errors will display the original data instead of the FormatException error. - 🐞 [FIX] The bug of infinite loop when sending requests to MITM server with LAN IP. ### windows-macos-linux - 🚀 [NEW] Python scripting can add the comment for a request. - 🚀 [NEW] The toolbox adds the UUID generator tool. - 🚀 [NEW] The toolbox adds the JSON escape tool. - 💪 [OPT] Create a folder according to the tag when importing OpenAPI file. - 💪 [OPT] Use `operationId` as the API alternative name when importing OpenAPI file. - 💪 [OPT] Automatically add `=` padding at the end of the input during Base64 decoding. - 💪 [OPT] Correct the label and the order of right-click menu options for selected text. - 💪 [OPT] Some search input boxes support using shortcut keys ⬆️ and ⬇️ to switch historical search records. - 💪 [OPT] Adjust other UI details. - 🐞 [FIX] The bug that the initial position of the subwindow is not displayed correctly under multiple screens. - 🐞 [FIX] The bug that shortcut keys will conflict between API request script editor and API save. - 🐞 [FIX] The bug that Postman API collections exported by third-party cannot be imported into Reqable. - 🐞 [FIX] The bug that JSON viewer option in right-click menu is unavailable. ### windows - 🐞 [FIX] The bug that some tips related to shortcut keys in the bottom bar are incomplete. - 🐞 [FIX] The bug that some text has an incorrect font display. 
```

### 2024-11-24T22:53:04Z [**clash-verge-rev/clash-verge-rev**](https://github.com/clash-verge-rev/clash-verge-rev)

```
Clash Verge Rev 2.0.1 版本发布（稳定版，推荐更新！）  ### Notice  - 强烈建议完全删除 1.x 老版本再安装此版本！ - 历时3个月的紧密开发与严格测试稳定版2.0.1终于发布了：巨量改进与性能、稳定性提升，目前Clash Verge Rev已经有了比肩cfw的健壮性；而且更强大易用！ - 由于更改了服务安装逻辑，Mac/Linux 首次安装需要输入系统密码卸载和安装服务，以后可以丝滑使用 tun(虚拟网卡)模式 - 因 Tauri 2.0 底层 bug，关闭窗口后保留webview进程，优点是再次打开面板更快，缺点是内存使用略有增加  ### 2.0.1相对于2.0.0改进了（强烈建议升级，上个版本2.0.0已删除）：  - 无法从 2.0rc和2.0.0 升级的问题（已经安装了2.0版本的需手动下载安装） - MacOS 系统下少有的无法安装服务，无法启动的问题，目前更健壮了 - 当系统中没有 yaml 编辑器的情况下，打开文件程序崩溃的问题 - Windows 应用内升级和覆盖安装不会删除老执行文件的问题 - 修改优化了 mac 下 fakeip 段和 dns - 测试菜单 svg 图标格式检查 - 应用内升级重复安装 vs runtime 的问题 - 修复外部控制下密码有特殊字符认证出错的问题 - 修复恢复 Webdav 备份设置后， Webdav 设置丢失的问题 - 代理页面增加快速回到顶部的按钮  ### Breaking changes  - 重大框架升级：使用 Tauri 2.0（巨量改进与性能提升） - 出现 bug 到 issues 中提出；以后不再接受1.x版本的bug反馈。 - 强烈建议完全删除 1.x 老版本再安装此版本  ### Features  - Meta(mihomo)内核升级 1.18.10 - Win 下的系统代理替换为 Shadowsocks/CFW/v2rayN 等成熟的 sysproxy.exe 方案，解决拨号/VPN 环境下无法设置系统代理的问题 - 服务模式改进为启动软件时自动安装，TUN 模式可自由开启不再限制于服务模式 - Mac 下可用 URL Scheme 导入订阅 - 可使用 Ctrl(cmd)+Q 快捷键退出程序 - 成功导入订阅的提示消息 - 能自动选中新导入的订阅 - 日志加入颜色区分 - 改进多处文本表述 - 加入图标 svg 格式检测 - 增加更多 app 调试日志 - 添加 MacOS 下白色桌面的 tray 黑色配色（但会代理系统代理、tun 模式图标失效的问题） - 增加 Webdav 备份功能 - 添加统一延迟的设置开关 - 添加 Windows 下自动检测并下载 vc runtime 的功能 - 支持显示 mux 和 mptcp 的节点标识 - 延迟测试连接更换 http 的 cp.cloudflare.com/generate_204 （关闭统一延迟的情况下延迟测试结果会有所增加） - 重构日志记录逻辑，可以收集和筛选所有日志类型了（之前无法记录debug的日志类型）  ### Performance  - 优化及重构内核启动管理逻辑 - 优化 TUN 启动逻辑 - 重构和优化 app_handle - 重构系统代理绕过逻辑 - 移除无用的 PID 创建逻辑 - 优化系统 DNS 设置逻辑 - 后端实现窗口控制 - 重构 MacOS 下的 DNS 设置逻辑  ### Bugs Fixes  - 修复已有多个订阅导入新订阅会跳选订阅的问题 - 修复多个 Linux 下的 bug, Tun 模式在 Linux 下目前工作正常 - 修复 Linux wayland 下任务栏图标缺失的问题 - 修复 Linux KDE 桌面环境无法启动的问题 - 移除多余退出变量和钩子 - 修复 MacOS 下 tray 菜单重启 app 失效的问题 - 修复某些特定配置文件载入失败的问题 - 修复 MacOS 下 tun 模式 fakeip 不生效的问题 - 修复 Linux 下 关闭 tun 模式文件报错的问题 - 修复快捷键设置的相关 bug - 修复 Win 下点左键菜单闪现的问题（Mac 下的操作逻辑相反，默认情况下不管点左/右键均会打开菜单，闪现不属于 bug）  ### Known issues  - Windows 下窗口大小无法记忆（等待上游修复） - Webdav 备份因为安全性和兼容性问题，暂不支持跨平台配置同步  ### 下载  Windows (不支持win7)： - 安装版：[64位，一般下载这个](https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.0.1/Clash.Verge_2.0.1_x64-setup.exe) | [Arm64看准了，这个不常用](https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.0.1/Clash.Verge_2.0.1_arm64-setup.exe) （因为便携版问题较多不再提供便携版）  macOS 11+： - DMG：[Intel](https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.0.1/Clash.Verge_2.0.1_x64.dmg) | [Apple Silicon M](https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.0.1/Clash.Verge_2.0.1_aarch64.dmg)  Linux： - DEB：[64位](https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.0.1/Clash.Verge_2.0.1_amd64.deb) | [Arm64](https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.0.1/Clash.Verge_2.0.1_arm64.deb) (Debian系) 使用 apt ./路径 安装 - RPM：[64位](https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.0.1/Clash.Verge-2.0.1-1.x86_64.rpm) | [Arm64](https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.0.1/Clash.Verge-2.0.1-1.aarch64.rpm) (Redhat系) 使用 dnf ./路径 安装  ### 快速上手 - [使用文档](https://clash-verge-rev.github.io)  ### 稳定机场VPN推荐 - [狗狗加速](https://verge.dginv.click/#/register?code=oaxsAGo6)  ### Clash Verge Rev TG频道： - [@clash_verge_re](https://t.me/clash_verge_re) 
```

### 2024-11-23T16:54:40Z [**jianchang512/pyvideotrans**](https://github.com/jianchang512/pyvideotrans)

```
> 预打包版仅适用于Windows10/11，MacOS和Linux请源码部署  - Fix: 音量调整对所有渠道均生效，数值代表增减百分比 - Fix: stt语音识别渠道提示不支持的格式错误 - Fix:  #639   #630 #636 - Fix: 克隆声音时对中文英文 文本规范化 - Fix: 试听配音报错提示 - Feat: 添加孟加拉语 - Fix: 单个视频翻译中途停止时清空字幕区 - Fix: 默认选中语音降噪 - Feat: Gemini语音识别时增加vad切割为小片段再挨个发送请求识别，以避免时间戳不准确问题，翻译设置Gemini pro中启用(免费Gemini账号勿启用，会导致大量429错误)   ## Win v3.19 完整包下载3.4G(含tiny/medium模型)  > 如果未安装过旧版本，请在此下载完整版，如需cuda加速，需有英伟达显卡并且安装cuda12.x及cudnn9  百度网盘下载地址:   https://pan.baidu.com/s/19AU6IhKtNeqUF-wXII4WKQ?pwd=bpdb  Huggingface(墙外地址):  https://huggingface.co/spaces/mortimerme/s4/resolve/main/win-videotrans-v3.19.7z?download=true     ## v3.23补丁包165MB  > 如果已安装过2.x版本，可下载补丁包后解压在sp.exe所在目录，覆盖已有sp.exe和文件夹  GitHub地址: https://github.com/jianchang512/pyvideotrans/releases/download/v3.19/win-PatchUpdate-3.23.7z  百度网盘下载地址:  https://pan.baidu.com/s/1DepDtG2hvzHBPD8-v-k_3w?pwd=1euf   > 若补丁覆盖后打开出错，请升级显卡驱动、升级cuda到12.x、升级cudnn到cudnn9，并重新下载完整包，然后再使用该补丁包覆盖。 >  > 或下载该压缩包 https://pan.baidu.com/s/1LOjr9ampzqp7eBrjNgSTHQ?pwd=wrkn   解压后(也可从此地址下载    https://github.com/jianchang512/pyvideotrans/releases/download/v3.15/cuda-torch-pathupdate.7z  )，复制其内的 `_internal`文件夹覆盖软件目录内的`_internal`文件夹   ----  > api.exe 下载，api.exe是用于通过http请求调用的文件，不可独立使用，需先下载完整包，然后下载api.exe和 sp.exe放在同一目录下 >  > api.exe下载地址：https://github.com/jianchang512/pyvideotrans/releases/download/v3.00/api.exe   ----  ### 所有模型下载地址  > 为避免压缩包体积过大，预打包版只内置最小模型 tiny，识别效果不佳，效果更好的模型请点击下载    https://github.com/jianchang512/stt/releases/tag/0.0 
```

### 2024-11-25T03:04:00Z [**gkd-kit/gkd**](https://github.com/gkd-kit/gkd)

```
# v1.9.2  以下是本次更新的主要内容  ## 优化和修复  - 优化关于界面布局 - 优化上传文件的逻辑 - 优化规则匹配逻辑 - 优化显示透明导航栏 - 修复HTTP服务启动失败的问题 - 其它优化和错误修复  ## 通过以下任意方式更新  - 打开 APP - 设置 - 检测更新 - 前往首页 <https://gkd.li/guide/> - 通过 github [releases](https://github.com/gkd-kit/gkd/releases) 
```

### 2024-11-24T15:51:08Z [**AstroNvim/AstroNvim**](https://github.com/AstroNvim/AstroNvim)

```
## [4.28.1](https://github.com/AstroNvim/AstroNvim/compare/v4.28.0...v4.28.1) (2024-11-24)   ### Bug Fixes  * **snapshot:** update dependencies ([9e5a0c9](https://github.com/AstroNvim/AstroNvim/commit/9e5a0c95a9ce28549784b9c00131bd652165159a)) 
```

### 2024-11-21T12:39:42Z [**klzgrad/naiveproxy**](https://github.com/klzgrad/naiveproxy)

```
Rebased to 131.0.6778.86. 
```

### 2024-11-20T05:48:10Z [**1Panel-dev/1Panel**](https://github.com/1Panel-dev/1Panel)

```
## What’s new  * Added support for CloudDNS as a DNS provider. by @igophper in https://github.com/1Panel-dev/1Panel/pull/7081 * Added support for Volcano Engine as a DNS provider. by @liuruibin in https://github.com/1Panel-dev/1Panel/pull/7006 * Added support for customizing theme colors. by @lan-yonghui * Added support for syncing proxy server configurations to Docker. by @lan-yonghui  ## Improvements  * Collapsed the status bar by default when there are too many disks displayed. by @YaKun9 in https://github.com/1Panel-dev/1Panel/pull/6918 * Prohibited deleting the 1Panel installation directory from the file list. by @lan-yonghui in https://github.com/1Panel-dev/1Panel/pull/7029 * Improved the notification message for unsupported nftables in firewall port forwarding. by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/6967 * Ignored application recovery failures during snapshot restoration. by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/7012 * Limited backup imports for websites, applications, and databases to single-file uploads. by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/7045 * Optimized the color scheme for the dark theme. by @lan-yonghui in https://github.com/1Panel-dev/1Panel/pull/6964  ## Bug fixes  * Fixed an issue where the installation status remained incomplete due to extended application image pull times. by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/6983 * Fixed an issue where editing container image repositories failed in certain scenarios. by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/6845 * Fixed an issue where container deletion failed when the orchestration path was empty. by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/6862 * Fixed an issue where switching remote databases failed. by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/6893 * Fixed an issue where saving port forwarding rules failed during editing. by @igophper in https://github.com/1Panel-dev/1Panel/pull/7100 * Fixed an issue where Pure-FTPd had slow upload speeds. by @bh1xaq in https://github.com/1Panel-dev/1Panel/pull/6994 * Fixed incorrect logging in some operation logs. by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/6899 * Fixed a flickering issue on the page when clearing website logs. by @igophper in https://github.com/1Panel-dev/1Panel/pull/6905 * Fixed an issue where SSL certificate information for the panel could not be retrieved in certain scenarios. by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/6962 * Fixed inconsistent status code responses for unauthorized settings. by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/7027 * Fixed an issue where the left menu disappeared after closing the browser directly in full-screen mode. by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/6894 
```

### 2024-11-22T08:41:56Z [**LazyVim/LazyVim**](https://github.com/LazyVim/LazyVim)

```
## [13.5.3](https://github.com/LazyVim/LazyVim/compare/v13.5.2...v13.5.3) (2024-11-22)   ### Bug Fixes  * **copilot:** remove tmp nightly fix ([30f556d](https://github.com/LazyVim/LazyVim/commit/30f556d17aaf7ac74f0553faebed2cf298b65820)) * **dial:** make sure defaults are part of every group. Fixes [#4868](https://github.com/LazyVim/LazyVim/issues/4868) ([2108028](https://github.com/LazyVim/LazyVim/commit/2108028cde19184bf8ea1a00065b5a099b1928e1)) 
```

### 2024-11-22T10:37:56Z [**nova-video-player/aos-AVP**](https://github.com/nova-video-player/aos-AVP)

```
- fix on pgs subtitles duration computation 
```

### 2024-11-26T22:46:08Z [**Loyalsoldier/clash-rules**](https://github.com/Loyalsoldier/clash-rules)

```
 
```

### 2024-11-25T09:39:02Z [**sigoden/aichat**](https://github.com/sigoden/aichat)

```
## REPL Changing  diff - .save agent-config       Save the current agent config to file + .edit rag-docs           Edit the RAG documents   ## New Features  - `.info role`/`.exit role` works for session role ([#958](https://github.com/sigoden/aichat/pull/958)) - support `.edit rag-docs` ([#964](https://github.com/sigoden/aichat/pull/964)) - change agent config/variables ([#967](https://github.com/sigoden/aichat/pull/967)) - support session-scoped agent variables ([#969](https://github.com/sigoden/aichat/pull/969)) - `.agent` accepts session name ([#970](https://github.com/sigoden/aichat/pull/970)) - add config `user_agent` ([#971](https://github.com/sigoden/aichat/pull/971)) - support overriding agent config with env vars ([#974](https://github.com/sigoden/aichat/pull/974)) - add hunyuan client ([#980](https://github.com/sigoden/aichat/pull/980)) - remove supports for huggingface ([#988](https://github.com/sigoden/aichat/pull/988)) - support env `<AGENT_NAME>_CONFIG_FILE` ([#990](https://github.com/sigoden/aichat/pull/990)) - save function calls in the session ([#994](https://github.com/sigoden/aichat/pull/994)) - support autonaming session ([#1001](https://github.com/sigoden/aichat/pull/1001))  ## Bug Fixes  - unexpected Ctrl-C/Ctrl-D handling in non-stream REPL Chat ([#957](https://github.com/sigoden/aichat/pull/957)) - WebUI unsupported value error when invoking o1-* models ([#983](https://github.com/sigoden/aichat/pull/983)) - invalid request on qianwen multi tool-calls ([#993](https://github.com/sigoden/aichat/pull/993)) 
```

### 2024-11-24T09:59:17Z [**Ashinch/ReadYou**](https://github.com/Ashinch/ReadYou)

```
## 0.11.1  ### Notable changes: 1. Custom font support for WebView reader 2. Add new visual styles to toolbars in flow page and reading page 3. UI improvements & fixes  **Full Changelog**: https://github.com/Ashinch/ReadYou/compare/0.11.0...0.11.1 
```

### 2024-11-25T14:53:46Z [**charmbracelet/bubbletea**](https://github.com/charmbracelet/bubbletea)

```
## Changelog ### Bug fixes * 4ad07926d7ff00bc21a05b2536d82a7cc629225e: fix: cursor position adjustment after exiting alt screen (#1241) (@semihbkgr) * ede8caa9d4f588a4a2c744d8e135a1b444bf2ce9: fix: renderer: keep a separate count of lines rendered in the alt screen (@aymanbagabas) ### Other work * 76b0f818b3174a3e9b77f93c19820d07855f13f4: ci: fix goreleaser config (#1238) (@caarlos0)  ---  <a href="https://charm.sh/"><img alt="The Charm logo" src="https://stuff.charm.sh/charm-badge.jpg" width="400"></a>  Thoughts? Questions? We love hearing from you. Feel free to reach out on [Twitter](https://twitter.com/charmcli), [The Fediverse](https://mastodon.technology/@charm), or on [Discord](https://charm.sh/chat). 
```

### 2024-11-20T23:32:47Z [**iiordanov/remote-desktop-clients**](https://github.com/iiordanov/remote-desktop-clients)

```
RELEASE-v5.6.1 
```

### 2024-11-20T10:39:23Z [**danielmiessler/SecLists**](https://github.com/danielmiessler/SecLists)

```
Fourth (and final) release of 2024! 🎉 This release includes [multiple updates](https://github.com/danielmiessler/SecLists/compare/2024.3...2024.4) from the community =) 🥇 Thank you everyone <3  Shout-out to: @Dec0y-jb, @BRAVO68WEB, @ItsIgnacioPortal, @newyork167, @domai-tb, @YouFoundAlpha, @ctflearner, @righettod, @pwnter, @josemlwdf, @StepSisStuck and @napz99 
```

### 2024-11-26T12:20:43Z [**xaboy/form-create**](https://github.com/xaboy/form-create)

```
**vue3** 20241126  - 新增 支持多语言. 增加`props.locale`配置项,选择多语言,通过`options.language`管理多语言配置,默认`zh-cn` - 新增 api增加`t`和`getLocale`方法 - 新增 `fetch`配置项增加`query`参数.支持配置GET参数 - 新增 增加`hook`配置项,监听规则的生命周期 - 新增 表单渲染的辅助组件增加class - 优化 上传组件 - 优化 配置合并逻辑 - 优化 提交按钮增加上边距 - 修复 `checkbox`和`radio`组件值的回显  [帮助文档](https://form-create.com/v3/guide/) 
```

### 2024-11-21T01:03:17Z [**theonedev/onedev**](https://github.com/theonedev/onedev)

```
## Installation Guide  https://docs.onedev.io/category/installation-guide  ## Change Log  https://code.onedev.io/onedev/server/~builds/5712/fixed-issues?query=%22State%22+is+%22Released%22+order+by+%22Type%22+asc+and+%22Priority%22+desc  ## Incompatibilities  https://code.onedev.io/onedev/server/~builds/5712/markdown/Incompatibilities/server-product/system/incompatibilities/incompatibilities.md 
```

### 2024-11-26T18:22:56Z [**ccxt/ccxt**](https://github.com/ccxt/ccxt)

```
## What's Changed * feat(bingx) - features by @ttodua in https://github.com/ccxt/ccxt/pull/24315 * fix(gate): return value when loadUnifiedStatus by @sc0Vu in https://github.com/ccxt/ccxt/pull/24327 * remove token_bucket by @ttodua in https://github.com/ccxt/ccxt/pull/24317 * fix(okx): adjust setLeverage by @carlosmiei in https://github.com/ccxt/ccxt/pull/24328 * fix(woo): old domain replaced with new domain woox.io by @woo686 in https://github.com/ccxt/ccxt/pull/24326 * cex change rateLimit by @ndubel in https://github.com/ccxt/ccxt/pull/24329 * cex order statuses by @ndubel in https://github.com/ccxt/ccxt/pull/24332 * fix(bybit): options tickers by @carlosmiei in https://github.com/ccxt/ccxt/pull/24334 * fix(krakenfuture): update error by @sc0Vu in https://github.com/ccxt/ccxt/pull/24340 * bingx: add apis by @sc0Vu in https://github.com/ccxt/ccxt/pull/24342 * bitbank: add apis by @sc0Vu in https://github.com/ccxt/ccxt/pull/24343 * bitfinex: add apis by @sc0Vu in https://github.com/ccxt/ccxt/pull/24344 * feat(bitget) - `.features` implementation by @ttodua in https://github.com/ccxt/ccxt/pull/24345 * feat(phemex) - trigger orders by @ttodua in https://github.com/ccxt/ccxt/pull/24300 * bybit.ts editing with safeValueN to safeListN by @AresArtemius in https://github.com/ccxt/ccxt/pull/24276 * feat(features) - marginMode by @ttodua in https://github.com/ccxt/ccxt/pull/24351 * fix: added missing createStopOrder/createTriggerOrder to exchange["has"] by @samgermain in https://github.com/ccxt/ccxt/pull/24350 * chore: update changelog by @carlosmiei in https://github.com/ccxt/ccxt/pull/24354 * idex pro docstring @see by @samgermain in https://github.com/ccxt/ccxt/pull/24356 * fix(okx) - currencies & fees & static tests by @ttodua in https://github.com/ccxt/ccxt/pull/24335 * fix(binance): testnet error handling by @carlosmiei in https://github.com/ccxt/ccxt/pull/24362 * fix(onetrading): fetchTradingFees - replace dynamic method call with explicit method call by @samgermain in https://github.com/ccxt/ccxt/pull/24361 * chore: bump ast-transpiler version by @carlosmiei in https://github.com/ccxt/ccxt/pull/24364 * bitrue error mapping by @ndubel in https://github.com/ccxt/ccxt/pull/24363 * refactor(static-tests-updaters) - reorg by @ttodua in https://github.com/ccxt/ccxt/pull/24349 * Coinone coinsph editing safe value by @AresArtemius in https://github.com/ccxt/ccxt/pull/24337 * Coinspot and cryptocom editing safe value by @AresArtemius in https://github.com/ccxt/ccxt/pull/24359 * fix(coinbase): increase max limit by @carlosmiei in https://github.com/ccxt/ccxt/pull/24367 * fix(probit): msg length in ws by @carlosmiei in https://github.com/ccxt/ccxt/pull/24378 * binance: update python examples by @sc0Vu in https://github.com/ccxt/ccxt/pull/24374 * feat(c#): add encoding and other fixes by @carlosmiei in https://github.com/ccxt/ccxt/pull/24381 * fix(filterByValueSinceLimit): handle since = 0 by @carlosmiei in https://github.com/ccxt/ccxt/pull/24380 * fix(php): array_slice handle strings by @carlosmiei in https://github.com/ccxt/ccxt/pull/24382 * New exchange: Ellipx by @nguyenhieuec in https://github.com/ccxt/ccxt/pull/24151 * build: skip-tests by @carlosmiei in https://github.com/ccxt/ccxt/pull/24383  ## New Contributors * @woo686 made their first contribution in https://github.com/ccxt/ccxt/pull/24326  **Full Changelog**: https://github.com/ccxt/ccxt/compare/4.4.33...4.4.34 
```

### 2024-11-23T10:03:18Z [**acmesh-official/acme.sh**](https://github.com/acmesh-official/acme.sh)

```
## What's Changed * refactor: Alibaba Cloud API by @PMExtra in https://github.com/acmesh-official/acme.sh/pull/5294 * Fix Timeweb Cloud DNS API pagination by @nikolaypronchev in https://github.com/acmesh-official/acme.sh/pull/5296 * Update dns_openprovider.sh for OpenProvider by @WinSCaP in https://github.com/acmesh-official/acme.sh/pull/5183 * update dns_doapi by @henrikalves in https://github.com/acmesh-official/acme.sh/pull/5158 * Add OpenContainers Annotations as Labels to Docker Image by @mpgirro in https://github.com/acmesh-official/acme.sh/pull/5305 * Add ali_dcdn deploy hook (Alibaba Cloud DCDN) by @PMExtra in https://github.com/acmesh-official/acme.sh/pull/5297 * on OpenBSD, add libiconv by @jschauma in https://github.com/acmesh-official/acme.sh/pull/5309 * Updated MS links, added wiki link, updated error messages, updated API limit comment by @abulgatz in https://github.com/acmesh-official/acme.sh/pull/5313 * Adding omg.lol DNS API by @as-kholin in https://github.com/acmesh-official/acme.sh/pull/5301 * Fix markdown issue in telegram notify hook by @fazelukario in https://github.com/acmesh-official/acme.sh/pull/5315 * Update Porkbun API URL by @allddd in https://github.com/acmesh-official/acme.sh/pull/5323 * Revert txt add update by @lifeboy in https://github.com/acmesh-official/acme.sh/pull/5331 * Fix POSIX shell portability by @ryoon in https://github.com/acmesh-official/acme.sh/pull/5374 * Fix dns_pdns.sh to use saved account conf by @sahsanu in https://github.com/acmesh-official/acme.sh/pull/5328 * Dns API: fix structural info by @stokito in https://github.com/acmesh-official/acme.sh/pull/6087 * Fixes issue 4956: 'Linode DNS Pagination Bug' by @vmmello in https://github.com/acmesh-official/acme.sh/pull/5172 * fix(truenas): broken script since 23.10 scale release by @M0NsTeRRR in https://github.com/acmesh-official/acme.sh/pull/6089 * StrongSwan deploy hook: swanctl support by @sergiustheblack in https://github.com/acmesh-official/acme.sh/pull/6094 * Add existing bearer token support to Azure DNS API by @stbeldarborge in https://github.com/acmesh-official/acme.sh/pull/5276 * fix: new version of fornex dns based on api version 2.3.1 by @CreatorHRS in https://github.com/acmesh-official/acme.sh/pull/6106   ## New Contributors * @WinSCaP made their first contribution in https://github.com/acmesh-official/acme.sh/pull/5183 * @henrikalves made their first contribution in https://github.com/acmesh-official/acme.sh/pull/5158 * @mpgirro made their first contribution in https://github.com/acmesh-official/acme.sh/pull/5305 * @jschauma made their first contribution in https://github.com/acmesh-official/acme.sh/pull/5309 * @abulgatz made their first contribution in https://github.com/acmesh-official/acme.sh/pull/5313 * @as-kholin made their first contribution in https://github.com/acmesh-official/acme.sh/pull/5301 * @fazelukario made their first contribution in https://github.com/acmesh-official/acme.sh/pull/5315 * @ryoon made their first contribution in https://github.com/acmesh-official/acme.sh/pull/5374 * @vmmello made their first contribution in https://github.com/acmesh-official/acme.sh/pull/5172 * @M0NsTeRRR made their first contribution in https://github.com/acmesh-official/acme.sh/pull/6089 * @sergiustheblack made their first contribution in https://github.com/acmesh-official/acme.sh/pull/6094 * @stbeldarborge made their first contribution in https://github.com/acmesh-official/acme.sh/pull/5276 * @CreatorHRS made their first contribution in https://github.com/acmesh-official/acme.sh/pull/6106  **Full Changelog**: https://github.com/acmesh-official/acme.sh/compare/3.0.9...3.1.0 
```

### 2024-11-21T08:32:51Z [**pingcap/tidb**](https://github.com/pingcap/tidb)

```
For new features, improvements, and bug fixes released in v7.1.6 for TiDB, see [TiDB v7.1.6 release notes](https://docs.pingcap.com/tidb/stable/release-7.1.6).  See the difference from the issue perspective: <details>  - pingcap/tidb#52902 - pingcap/tidb#52939 - pingcap/tidb#52777 - pingcap/tidb#40926 - pingcap/tidb#41918 - pingcap/tidb#50988 - pingcap/tidb#41052 - pingcap/tidb#53428 - pingcap/tidb#53558 - pingcap/tidb#41736 - pingcap/tidb#46005 - pingcap/tidb#52601 - pingcap/tidb#49109 - pingcap/tidb#54031 - pingcap/tidb#50051 - pingcap/tidb#54181 - pingcap/tidb#48756 - pingcap/tidb#53047 - pingcap/tidb#54068 - pingcap/tidb#54417 - pingcap/tidb#53561 - pingcap/tidb#54005 - pingcap/tidb#54379 - pingcap/tidb#54375 - pingcap/tidb#53767 - (#53690 - pingcap/tidb#55337 - pingcap/tidb#54908 - pingcap/tidb#53618 - pingcap/tidb#55561 - pingcap/tidb#55042 - pingcap/tidb#42587 - pingcap/tidb#52294 - pingcap/tidb#53867 - pingcap/tidb#53652 - pingcap/tidb#52657 - pingcap/tidb#52797 - pingcap/tidb#53752 - pingcap/tidb#52755 - pingcap/tidb#54538 - pingcap/tidb#55666 - pingcap/tidb#49692 - pingcap/tidb#52425 - pingcap/tidb#46475 - pingcap/tidb#50089 - pingcap/tidb#53726 - pingcap/tidb#56173 - pingcap/tidb#56511 - pingcap/tidb#56539 - pingcap/tidb#49826 - pingcap/tidb#54760 - pingcap/tidb#55808 - pingcap/tidb#56688 - pingcap/tidb#56422 - pingcap/tidb#47787 - pingcap/tidb#56408 - pingcap/tidb#54691 - pingcap/tidb#56476 - pingcap/tidb#55812 - pingcap/tidb#40997 - pingcap/tidb#53766 - pingcap/tidb#54829 - pingcap/tidb#55677 - pingcap/tidb#42093 - pingcap/tidb#55872 - pingcap/tidb#56629 - pingcap/tidb#56271 - pingcap/tidb#54324 - pingcap/tidb#45783 - pingcap/tidb#56458 - pingcap/tidb#56116 - pingcap/tidb#56456 - pingcap/tidb#54961 - pingcap/tidb#53580 - pingcap/tidb#54449 - pingcap/tidb#53984 - pingcap/tidb#46538 - pingcap/tidb#56402 - pingcap/tidb#53967 - pingcap/tidb#55384 - pingcap/tidb#54689 - pingcap/tidb#53026 - pingcap/tidb#37338 - pingcap/tidb#54688 - pingcap/tidb#50501 - pingcap/tidb#54017 - pingcap/tidb#55902 - pingcap/tidb#55138 - pingcap/tidb#55265 - pingcap/tidb#55126 - pingcap/tidb#56440 - pingcap/tidb#54343 - pingcap/tidb#54964 - (#55094 - pingcap/tidb#54969 - pingcap/tidb#48680 - pingcap/tidb#55113 - pingcap/tidb#55551 - pingcap/tidb#53009 - pingcap/tidb#50235 - pingcap/tidb#42093 - pingcap/tidb#56704 - pingcap/tidb#52680 - pingcap/tidb#52622 - pingcap/tidb#55965 - pingcap/tidb#53835 - pingcap/tidb#52088 - pingcap/tidb#53835 - pingcap/tidb#56582 - pingcap/tidb#53480 - pingcap/tidb#53592 - pingcap/tidb#55684 - pingcap/tidb#53730 - pingcap/tidb#53872 - pingcap/tidb#47115 - pingcap/tidb#54652 - pingcap/tidb#46962 - pingcap/tidb#53834 - pingcap/tidb#53951 - pingcap/tidb#55711 - pingcap/tidb#47694 - pingcap/tidb#47899 - pingcap/tidb#52914 - pingcap/tidb#52985 - pingcap/tidb#53029 - pingcap/tidb#52687 - pingcap/tidb#31778 - pingcap/tidb#53505 - pingcap/tidb#45551 - pingcap/tidb#37986 - pingcap/tidb#54053 - pingcap/tidb#54139 - pingcap/tidb#53600 - pingcap/tidb#49517 - pingcap/tidb#53746 - pingcap/tidb#53540 - pingcap/tidb#56114 - pingcap/tidb#41719 - pingcap/tidb#56217 - pingcap/tidb#54426 - pingcap/tidb#52805 - pingcap/tidb#56161 - pingcap/tidb#54870 - pingcap/tidb#54022 - pingcap/tidb#56053 - pingcap/tidb#52768 - pingcap/tidb#53724 - pingcap/tidb#53972 - pingcap/tidb#55273 - pingcap/tidb#53236 - pingcap/tidb#57134 - pingcap/tidb#50872 - pingcap/tidb#52933 - pingcap/tidb#51407 - pingcap/tidb#53133 - pingcap/tidb#54897 - pingcap/tidb#55126 - pingcap/tidb#53673 - pingcap/tidb#53682 - pingcap/tidb#47400 - pingcap/tidb#49721 - pingcap/tidb#53779 - pingcap/tidb#53634 - pingcap/tidb#57043 - pingcap/tidb#56809 - pingcap/tidb#54582 - pingcap/tidb#56930  </details> 
```

