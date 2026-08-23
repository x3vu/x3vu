<div align="center">

<!-- ═══════════════════════ 封面 · HEADER ═══════════════════════ -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b4b,50:7F00FF,100:E100FF&height=220&section=header&text=Blessed%20%E5%8D%83%E9%87%8C&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=32&desc=%E4%BB%A5%E7%A0%81%E4%B8%BA%E5%89%91%20%C2%B7%20%E4%BB%A5%E9%80%86%E4%B8%BA%E9%81%93&descAlignY=55&descSize=18" width="100%" alt="header"/>

<a href="https://github.com/x3vu">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=24&duration=3500&pause=900&color=9C27B0¤tLine=true&center=true&vCenter=true&width=720&lines=%E9%80%86%E5%90%91%E5%B7%A5%E7%A8%8B%E5%B8%88+%2F+Reverse+Engineer;%E6%8A%8A%E4%B8%8D%E5%8F%AF%E8%83%BD%E6%8B%86%E5%88%B0%E5%8F%AF%E8%83%BD;Turning+impossible+into+possible,+one+binary+at+a_time;iOS+%C2%B7+Mach-O+%C2%B7+%E7%BA%AF%E5%87%BD%E6%95%B0Go+%C2%B7+%E7%AD%BE%E5%90%8D%E9%BB%91%E9%AD%94%E6%B3%95" alt="typing"/>
</a>

<!-- ═══════════════════════ 徽章 · BADGES ═══════════════════════ -->

[![ followers](https://img.shields.io/github/followers/x3vu?style=for-the-badge&logo=github&label=%E8%BF%BD%E9%9A%8F%E8%80%85&color=purple)](https://github.com/x3vu?tab=followers)
[![ stars](https://img.shields.io/github/stars/x3vu?affiliations=OWNER&style=for-the-badge&label=%E6%98%9F%E6%A0%87&color=blue)](https://github.com/x3vu?tab=repositories)
[![ visits](https://komarev.com/ghpvc/?username=x3vu&style=for-the-badge&label=%E8%A7%82%E4%BC%97&color=ff69b4)](https://github.com/x3vu)

<img src="https://img.shields.io/badge/%E9%98%B5%E8%90%A5-macOS_arm64-black?style=flat-square&logo=apple"/>
<img src="https://img.shields.io/badge/%E4%B8%BB%E4%BF%AE-Go_(%E7%BA%AF%E5%87%BD%E6%95%B0)-00ADD8?style=flat-square&logo=go"/>
<img src="https://img.shields.io/badge/%E5%89%AF%E4%BF%AE-C_%C2%B7_Python_%C2%B7_ObjC-3776AB?style=flat-square&logo=c"/>
<img src="https://img.shields.io/badge/%E7%A0%94%E7%A9%B6%E6%96%B9%E5%90%91-iOS%E9%80%86%E5%90%91_%E2%80%A2_Mach-O_%E2%80%A2_%E7%AD%BE%E5%90%8D-E100FF?style=flat-square"/>

---

<!-- ═══════════════════════ 侠客行 · MANIFESTO ═══════════════════════ -->

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

<br/>

<!-- ═══════════════════════ 兵器谱 · PROJECTS ═══════════════════════ -->

## ⚔️ 兵器谱 · The Arsenal

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

<br/>

<!-- ═══════════════════════ 技艺 · STACK ═══════════════════════ -->

## 🧠 技艺 · Craft

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=go,c,python,bash,apple,linux,windows,docker,git,githubactions,vscode,vim,md&perline=13" alt="stack"/>
</a>

```text
精通 Go 到什么程度？—— 我用 blacktop/go-macho 手写了 growing-rename，
让链接编辑段的每一条加载命令在字符串变长后重新对齐。otool 都挑不出毛病。
```

<br/>

<!-- ═══════════════════════ 战绩 · STATS ═══════════════════════ -->

## 📊 战绩 · Battle Record

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=x3vu&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117&title_color=E100FF&icon_color=9C27B0&text_color=c9d1d9&include_all_commits=true&count_private=true"/>
  <img src="https://github-readme-stats.vercel.app/api?username=x3vu&show_icons=true&theme=default&hide_border=true&include_all_commits=true&count_private=true" height="165"/>
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=x3vu&theme=radical&hide_border=true&background=0d1117&ring=E100FF&fire=FF6D00&currStreakLabel=9C27B0"/>
  <img src="https://streak-stats.demolab.com?user=x3vu&hide_border=true" height="165"/>
</picture>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=x3vu&layout=compact&theme=radical&hide_border=true&bg_color=0d1117&title_color=E100FF&text_color=c9d1d9&langs_count=10" width="49%" alt="langs"/>

[![trophy](https://github-profile-trophy.vercel.app/?username=x3vu&theme=purple&no-frame=true&row=1&column=7&margin-w=8)](https://github.com/x3vu)

<table>
<tr>
<td><img src="./profile-summary-card-output/github_dark/0-profile-details.svg" alt="details"/></td>
<td><img src="./profile-summary-card-output/github_dark/1-repos-per-language.svg" alt="repos per language"/></td>
<td><img src="./profile-summary-card-output/github_dark/3-stats.svg" alt="stats"/></td>
<td><img src="./profile-summary-card-output/github_dark/4-productive-time.svg" alt="productive time"/></td>
</tr>
</table>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=x3vu&bg_color=0d1117&color=c9d1d9&line=E100FF&point=9C27B0&area=true&area_color=1a1b4b&hide_border=true" width="100%" alt="activity graph"/>

<br/>

<!-- ═══════════════════════ 贪吃蛇 · THE SNAKE ═══════════════════════ -->

## 🐍 贪吃蛇 · It eats my commits

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="./snake.svg"/>
  <img alt="contribution snake" src="./snake.svg"/>
</picture>

*每天零点后自动重绘 —— 它吃的是我的睡眠。*
*(redrawn by GitHub Actions after midnight UTC — it eats my sleep.)*

<br/>

<!-- ═══════════════════════ 禅 · ZEN ═══════════════════════ -->

## 🍵 禅 · One line of Zen

<!-- zen-quote:start -->
> **「工欲善其事，必先利其器。」**
> *— 孔子 · Confucius, roughly describing why I wrote idev*
<!-- zen-quote:end -->

<br/>

<!-- ═══════════════════════ 联络 · CONNECT ═══════════════════════ -->

## 📮 联络 · Reach me

<a href="mailto:zeeforeal.l@gmail.com"><img src="https://img.shields.io/badge/Gmail-%E9%A3%9E%E9%B8%BD%E4%BC%A0%E4%B9%A6-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/x3vu"><img src="https://img.shields.io/badge/GitHub-x3vu-181717?style=for-the-badge&logo=github"/></a>

<br/>

---

<!-- ═══════════════════════ 尾声 · FOOTER ═══════════════════════ -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:E100FF,50:7F00FF,100:1a1b4b&height=140&section=footer" width="100%" alt="footer"/>

*此页由 GitHub Actions 自动供养 · fed by automation · 最后构建见 [Actions](https://github.com/x3vu/x3vu/actions)*

</div>
