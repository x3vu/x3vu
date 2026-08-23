<div align="center">

<!-- ═══════════════ header ═══════════════ -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b4b,50:7F00FF,100:E100FF&height=220&section=header&text=Blessed%20%E5%8D%83%E9%87%8C&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=32&desc=%E4%BB%A5%E7%A0%81%E4%B8%BA%E5%89%91%20%C2%B7%20%E4%BB%A5%E9%80%86%E4%B8%BA%E9%81%93&descAlignY=55&descSize=18" width="100%" alt="header"/>

<a href="https://github.com/x3vu">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=24&duration=3200&pause=800&color=E100FF&center=true&vCenter=true&width=760&lines=%E9%80%86%E5%90%91%E5%B7%A5%E7%A8%8B%E5%B8%88+%2F+Reverse+Engineer;%E6%8A%8A%E4%B8%8D%E5%8F%AF%E8%83%BD%E6%8B%86%E5%88%B0%E5%8F%AF%E8%83%BD;i+put+dylibs+where+they+don%27t+belong;%E7%AD%BE%E5%90%8D%E9%BB%91%E9%AD%94%E6%B3%95+%2F+codesign+sorcery;%E4%B8%80%E4%B8%AA%E4%BA%8C%E8%BF%9B%E5%88%B6%E8%B5%B0%E5%A4%A9%E4%B8%8B;yes,+the+snake+below+eats+my+commits" alt="typing"/>
</a>

[![followers](https://img.shields.io/github/followers/x3vu?style=flat-square&label=followers&color=purple)](https://github.com/x3vu?tab=followers)
[![visitors](https://komarev.com/ghpvc/?username=x3vu&style=flat-square&label=%E8%A7%82%E4%BC%97&color=ff69b4)](https://github.com/x3vu)
[![proton](https://img.shields.io/badge/proton-xscope%40proton.me-6D4AFF?style=flat-square&logo=protonmail&logoColor=white)](mailto:xscope@proton.me)

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:E100FF,100:7F00FF&animation=twinkling" width="100%" alt="divider"/>

<!-- ═══════════════ manifesto ═══════════════ -->

## 「侠客行」

> **十步杀一人，千里不留行。**
> *Ten paces, one binary slain. A thousand miles, no trace.*
>
> 李白写过刺客。我写加载命令。他把刀藏进诗里，我把 dylib 藏进 Mach-O。

```text
$ whoami
Blessed · indie dev, iOS RE nerd, Go purist

$ cat 道.md
· everything is a file: IPA is a zip, signatures are DER, firmware is tar. open them.
· one binary walks into any machine. no python env, no drama (idev does this).
· converters stay byte-faithful to upstream tools or the diff goes in the docs.
· behavior change means test first. network paths get fakes, always.
```

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:7F00FF,100:E100FF&animation=twinkling" width="100%" alt="divider"/>

<!-- ═══════════════ arsenal ═══════════════ -->

<img src="https://capsule-render.vercel.app/api?type=soft&height=90&color=0:1a1b4b,50:7F00FF,100:E100FF&text=%E5%85%B5%E5%99%A8%E8%B0%B1%20%C2%B7%20The%20Arsenal&fontSize=26&fontColor=ffffff&animation=twinkling" width="100%" alt="arsenal"/>

<table>
<tr><td valign="top" width="50%">

### idev · iPhone from the terminal

A single static Go binary that pairs your phone, installs apps, launches
them, streams syslog, grabs screenshots, forwards ports, reads your
pasteboard. On iOS 17 it spawns its own CoreDevice tunnel so you stop
babysitting Xcode's.

`Go` `usbmuxd` `CoreDevice`

</td><td valign="top" width="50%">

### xKVM · the tweak toolbox

Pure-Go rewrite of the cyan/pyzule-rw bloodline. Injects tweaks into IPAs,
extracts them back out, converts between jailbreak package layouts. Every
converter is pinned byte-for-byte against golden files, every Mach-O cut
done in Go. It ships without ldid and without insert_dylib.

`Mach-O` `codesign` `golden tests`

</td></tr>
</table>

<details>
<summary><b>more weapons in the forge（点开）</b></summary>
<br/>

| weapon | what it does | state |
|---|---|---|
| idev | pure-Go driver layer: backup / afc / recovery / ddi | active |
| xKVM | injector, extractor, jailbreak-pkg converter | active |
| legacy reach | driver support down to iOS 5–16 handsets | matrix building |
| backup2 port | M7: full backup/restore protocol port | planned |

</details>

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:E100FF,100:7F00FF&animation=twinkling" width="100%" alt="divider"/>

<!-- ═══════════════ craft ═══════════════ -->

## 技艺 · Craft

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=go,c,python,bash,apple,linux,windows,docker,git,githubactions,vscode,vim,md&perline=13" alt="stack"/>
</a>

```text
how deep does the Go go?
deep enough that I hand-rolled growing-rename over blacktop/go-macho:
every load command in LC_CODE_SIGNATURE realigns itself when strings grow,
and otool still can't find anything to complain about.
```

<img src="https://capsule-render.vercel.app/api?type=cylinder&height=70&color=0:1a1b4b,100:E100FF&text=GO%20%C2%B7%20MACH-O%20%C2%B7%20%E7%AD%BE%E5%90%8D%E9%BB%91%E9%AD%94%E6%B3%95&fontSize=20&fontColor=ffffff&animation=twinkling" width="100%" alt="ribbon"/>

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:7F00FF,100:E100FF&animation=twinkling" width="100%" alt="divider"/>

<!-- ═══════════════ mid banner ═══════════════ -->

<img src="https://capsule-render.vercel.app/api?type=slice&height=130&color=0:1a1b4b,50:7F00FF,100:E100FF&text=%E5%8D%81%E6%AD%A5%E6%9D%80%E4%B8%80%E4%BA%BA%20%C2%B7%20%E5%8D%83%E9%87%8C%E4%B8%8D%E7%95%99%E8%A1%8C&fontSize=28&fontColor=ffffff&animation=fadeIn&desc=Ten%20paces%2C%20one%20binary%20slain.&descAlignY=72&descSize=14" width="100%" alt="midbanner"/>

<!-- ═══════════════ numbers ═══════════════ -->

## 数字 · Numbers

Self-hosted cards, rebuilt daily by Actions here in this repo. They cannot
503 because they are files.

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

<!-- ═══════════════ snake ═══════════════ -->

## 贪吃蛇 · The Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="./snake.svg"/>
  <img alt="contribution snake" src="./snake.svg"/>
</picture>

Redrawn by cron just after UTC midnight. It eats my commits, and my sleep.

<!-- ═══════════════ zen ═══════════════ -->

## 禅 · One line of Zen

> **「工欲善其事，必先利其器。」**
> Confucius, basically explaining why I wrote idev.

<!-- ═══════════════ connect ═══════════════ -->

## 联络 · Reach me

Proton Mail above, or open an issue on anything public. I answer both,
eventually, usually at 2am.

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:E100FF,50:7F00FF,100:1a1b4b&height=140&section=footer" width="100%" alt="footer"/>

*此页由 GitHub Actions 自动供养 · fed by automation*

</div>
