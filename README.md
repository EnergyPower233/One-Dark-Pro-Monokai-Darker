# One Dark Pro Monokai Darker — iTerm2

源主题：https://github.com/eser/vscode-one-dark-pro-monokai-darker
版本：1.1.0。原始 JSON 与 LICENSE 随附。

`.itermcolors` 是 iTerm2 可导入的 XML plist；同名 `.json` 保存等价结构。`palette.json` 提供十六进制颜色及原文件校验值。

背景 #121212、前景 #bbbbbb、光标 #f8f8f0、选区 #3e4451 来自原主题。上游没有 terminal.ansi* 配置，因此将关键词红、函数绿、字符串黄、类名蓝、数字紫、常量青映射到 ANSI 颜色。亮色保持相同色相；亮黑取注释色 #5c6370，亮白取 #f8f8f0。粗体色和光标文字色分别使用亮白与背景色。

字体：JetBrains Maple Mono（Nerd Font 版本），PostScript 名 JetBrainsMapleMono-Regular，保留原字号。

重新导入：iTerm2 Settings → Profiles → Colors → Color Presets → Import，选择 .itermcolors 文件，再选同名预设。
