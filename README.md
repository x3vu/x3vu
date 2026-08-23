<div align="center">

<!-- ═══════════════ 封面 · HEADER ═══════════════ -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b4b,50:7F00FF,100:E100FF&height=220&section=header&text=Blessed%20%E5%8D%83%E9%87%8C&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=32&desc=%E4%BB%A5%E7%A0%81%E4%B8%BA%E5%89%91%20%C2%B7%20%E4%BB%A5%E9%80%86%E4%B8%BA%E9%81%93&descAlignY=55&descSize=18" width="100%" alt="header"/>

<a href="https://github.com/x3vu">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=24&duration=3200&pause=800&color=E100FF&center=true&vCenter=true&multiline=true&repeat=true&width=760&lines=%E9%80%86%E5%90%91%E5%B7%A5%E7%A8%8B%E5%B8%88+%2F+Reverse+Engineer;%E6%8A%8A%E4%B8%8D%E5%8F%AF%E8%83%BD%E6%8B%86%E5%88%B0%E5%8F%AF%E8%83%BD;Turning+impossible+into+possible,+one+binary+at+a+time;iOS+%C2%B7+Mach-O+%C2%B7+%E7%BA%AF%E5%87%BD%E6%95%B0Go;%E7%AD%BE%E5%90%8D%E9%BB%91%E9%AD%94%E6%B3%95+%2F+codesign+sorcery;%E4%B8%80%E4%B8%AA%E4%BA%8C%E8%BF%9B%E5%88%B6%E8%B5%B0%E5%A4%A9%E4%B8%8B" alt="typing"/>
</a>

<!-- ═══════════════ 徽章 · BADGES ═══════════════ -->

[![ 追随者](https://img.shields.io/github/followers/x3vu?style=for-the-badge&logo=github&label=%E8%BF%BD%E9%9A%8F%E8%80%85&color=purple)](https://github.com/x3vu?tab=followers)
[![ 星标](https://img.shields.io/github/stars/x3vu?affiliations=OWNER&style=for-the-badge&label=%E6%98%9F%E6%A0%87&color=blue)](https://github.com/x3vu?tab=repositories)
[![ 观众](https://komarev.com/ghpvc/?username=x3vu&style=for-the-badge&label=%E8%A7%82%E4%BC%97&color=ff69b4)](https://github.com/x3vu)

<img src="https://img.shields.io/badge/%E9%98%B5%E8%90%A5-macOS_arm64-black?style=flat-square&logo=apple"/>
<img src="https://img.shields.io/badge/%E4%B8%BB%E4%BF%AE-Go_(%E7%BA%AF%E5%87%BD%E6%95%B0)-00ADD8?style=flat-square&logo=go"/>
<img src="https://img.shields.io/badge/%E5%89%AF%E4%BF%AE-C_%C2%B7_Python_%C2%B7_ObjC-3776AB?style=flat-square&logo=c"/>
<img src="https://img.shields.io/badge/%E7%A0%94%E7%A9%B6%E6%96%B9%E5%90%91-iOS%E9%80%86%E5%90%91_%E2%80%A2_Mach-O-E100FF?style=flat-square"/>

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:E100FF,100:7F00FF&animation=twinkling" width="100%" alt="divider"/>

<!-- ═══════════════ 侠客行 · MANIFESTO ═══════════════ -->

## 「侠客行」 · The Manifesto

> **十步杀一人，千里不留行。**
> *Ten paces, one binary slain — a thousand miles, no trace left behind.*
>
> 李白写过刺客，我写加载命令。他把刀藏进诗里，我把 dylib 藏进 Mach-O。

```text
$ whoami
Blessed — 独立开发者 / iOS 逆向研究者 / 纯函数 Go 信徒

$ cat 道.md
· 一切皆文件：IPA 是 zip，签名是 DER，固件是 tar —— 拆开看。
· 纯净即正义：一个二进制走天下（idev），不装 Python，不求虚拟环境。
· 忠实于上游：转换器逐字节对齐生态工具，偏差必须写进文档。
· 测试先行：行为改动必带测试；网络路径一律 hermetic。
```

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:7F00FF,100:E100FF&animation=twinkling" width="100%" alt="divider"/>

<!-- ═══════════════ 兵器谱 · ARSENAL ═══════════════ -->

<img src="https://capsule-render.vercel.app/api?type=soft&height=90&color=0:1a1b4b,50:7F00FF,100:E100FF&text=%E2%9A%94%EF%B8%8F%20%E5%85%B5%E5%99%A8%E8%B0%B1%20%C2%B7%20The%20Arsenal&fontSize=26&fontColor=ffffff&animation=twinkling" width="100%" alt="arsenal"/>

<table>
<tr><td valign="top" width="50%">

### 🐉 idev — iPhone, from the terminal
**纯 Go 的 pymobiledevice3 替代品**

One static binary that pairs, installs, launches, streams logs, takes
screenshots, forwards ports and reads the clipboard. On iOS 17+ it spawns
its own CoreDevice tunnel instead of asking you to babysit one.

`Go` `usbmuxd` `CoreDevice`

</td><td valign="top" width="50%">

### 🜲 xKVM — iOS tweak toolbox
**cyan/pyzule-rw 血统的纯 Go 重写**

Inject tweaks into IPAs, extract them back out, convert packages between
jailbreak layouts — byte-faithful converters pinned by golden tests, all
Mach-O surgery done in pure Go. No ldid, no insert_dylib.

`Mach-O` `codesign` `golden-tests`

</td></tr>
</table>

<details>
<summary>📜 <b>更多兵器 · more weapons in the forge（点开查看）</b></summary>
<br/>

| 兵器 | 道 | status |
|---|---|---|
| idev | 纯 Go 设备驱动层：backup/afc/recovery/ddi | 🔥 active |
| xKVM | 注入器 · 提取器 · 越狱包转换器 | 🔥 active |
| legacy reach | iOS 5–16 老设备驱动支持 | 🧪 matrix building |
| backup2 port | M7：完整备份/恢复协议移植 | 📋 planned |

</details>

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:E100FF,100:7F00FF&animation=twinkling" width="100%" alt="divider"/>

<!-- ═══════════════ 技艺 · CRAFT ═══════════════ -->

## 🧠 技艺 · Craft

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=go,c,python,bash,apple,linux,windows,docker,git,githubactions,vscode,vim,md&perline=13" alt="stack"/>
</a>

```text
精通 Go 到什么程度？—— 我用 blacktop/go-macho 手写了 growing-rename，
让链接编辑段的每一条加载命令在字符串变长后重新对齐。otool 都挑不出毛病。
```

<img src="https://capsule-render.vercel.app/api?type=cylinder&height=70&color=0:1a1b4b,100:E100FF&text=GO%20%C2%B7%20MACH-O%20%C2%B7%20%E7%AD%BE%E5%90%8D%E9%BB%91%E9%AD%94%E6%B3%95&fontSize=20&fontColor=ffffff&animation=twinkling" width="100%" alt="ribbon"/>

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:7F00FF,100:E100FF&animation=twinkling" width="100%" alt="divider"/>

<!-- ═══════════════ 十步杀一人 · MID BANNER ═══════════════ -->

<img src="https://capsule-render.vercel.app/api?type=slice&height=130&color=0:1a1b4b,50:7F00FF,100:E100FF&text=%E5%8D%81%E6%AD%A5%E6%9D%80%E4%B8%80%E4%BA%BA%20%C2%B7%20%E5%8D%83%E9%87%8C%E4%B8%8D%E7%95%99%E8%A1%8C&fontSize=28&fontColor=ffffff&animation=fadeIn&desc=Ten%20paces%2C%20one%20binary%20slain.&descAlignY=72&descSize=14" width="100%" alt="midbanner"/>

<!-- ═══════════════ 战绩 · BATTLE RECORD (self-hosted, never 503) ═══════════════ -->

## 📊 战绩 · Battle Record

<table>
<tr>
<td><img src="./profile-summary-card-output/github_dark/0-profile-details.svg" alt="details"/></td>
<td><img src="./profile-summary-card-output/github_dark/1-repos-per-language.svg" alt="repos per language"/></td>
</tr>
<tr>
<td><img src="./profile-summary-card-output/github_dark/3-stats.svg" alt="stats"/></td>
<td><img src="./profile-summary-card-output/github_dark/4-productive-time.svg" alt="productive time"/></td>
</tr>
</table>

<img src="https://streak-stats.demolab.com?user=x3vu&hide_border=true" height="165" alt="streak"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=x3vu&bg_color=0d1117&color=c9d1d9&line=E100FF&point=9C27B0&area=true&area_color=1a1b4b&hide_border=true" width="100%" alt="activity graph"/>

<br/>

<!-- ═══════════════ 贪吃蛇 · SNAKE ═══════════════ -->

## 🐍 贪吃蛇 · It eats my commits

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="./snake.svg"/>
  <img alt="contribution snake" src="./snake.svg"/>
</picture>

*每天零点后自动重绘 —— 它吃的是我的睡眠。*
*(redrawn by GitHub Actions after midnight UTC — it eats my sleep.)*

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:E100FF,100:7F00FF&animation=twinkling" width="100%" alt="divider"/>

<!-- ═══════════════ 禅 · ZEN ═══════════════ -->

## 🍵 禅 · One line of Zen

> **「工欲善其事，必先利其器。」**
> *— 孔子 · Confucius, roughly describing why I wrote idev*

<!-- ═══════════════ 联络 · CONNECT ═══════════════ -->

## 📮 联络 · Reach me

<a href="mailto:xscope@proton.me"><img src="https://img.shields.io/badge/Proton_Mail-xscope%40proton.me-6D4AFF?style=for-the-badge&logo=protonmail&logoColor=white"/></a>
<a href="https://github.com/x3vu"><img src="https://img.shields.io/badge/GitHub-x3vu-181717?style=for-the-badge&logo=github"/></a>

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:E100FF,50:7F00FF,100:1a1b4b&height=140&section=footer" width="100%" alt="footer"/>

*此页由 GitHub Actions 自动供养 · fed by automation · 最后构建见 [Actions](https://github.com/x3vu/x3vu/actions)*

</div>
