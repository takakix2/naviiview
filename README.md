<div align="center">

# NaviiView

**Your scans, two pages at a time.**  
**画像を、見開きで軽快に。**

A comic viewer for the books you scanned yourself. / 自炊した漫画や画像の本を見開きで読むコミックビューア。

[![Website](https://img.shields.io/badge/Website-naviiview.navii.online-6366f1?style=flat-square)](https://naviiview.navii.online)
[![App Store](https://img.shields.io/badge/App_Store-iPhone_·_iPad_·_Mac-black?style=flat-square&logo=apple)](https://apps.apple.com/app/id6824969523)
[![Linux](https://img.shields.io/badge/Linux-Free-green?style=flat-square&logo=linux)](https://github.com/takakix2/naviiview/releases/latest)
[![Discord](https://img.shields.io/badge/Discord-Join-5865F2?style=flat-square&logo=discord)](https://discord.gg/pxv9msDyJ)

<img src="https://naviiview.navii.online/img/naviiview-shelf-mac.jpg" width="720" alt="The shelf: your favorites, by cover">

**Language / 言語**: [English](#english) · [日本語](#日本語)

</div>

---

## English

NaviiView reads comics and image books in two-page spreads. Open PDF, zip, rar, 7z, epub and image folders straight from your computer, your NAS or S3. Your favorites sit on a shelf, by cover.

**The Linux build is free.** It is freeware, not open source: this repository holds the releases, the license and the packaging files. The source code is not published.

### Download

| Platform | Where | Price |
|---|---|---|
| **Linux** (x86_64) | [GitHub Releases](https://github.com/takakix2/naviiview/releases/latest) — `.AppImage`, `.deb`, `.rpm` | **Free** |
| **iPhone / iPad / Mac** | [App Store](https://apps.apple.com/app/id6824969523) | One purchase for all three |
| **Android** | Google Play | Coming |
| **Windows** | Microsoft Store | Coming |

Linux: Ubuntu 22.04 or later (glibc 2.34+, WebKitGTK 4.1). Flathub and AUR packages are being prepared; the files are under `packaging/linux/`.

```sh
# AppImage
chmod +x NaviiView_*_amd64.AppImage && ./NaviiView_*_amd64.AppImage
# Debian / Ubuntu / Mint
sudo apt install ./NaviiView_*_amd64.deb
# Fedora / openSUSE
sudo dnf install ./NaviiView-*.x86_64.rpm
```

### What it does

- **Your favorites, by cover** — put a book or a folder of volumes on the shelf from the toolbar or from Book Locations. Sort by date added or by name.
- **Reading in spreads** — two-page spread, single page or vertical scroll. Right-to-left and left-to-right. The cover shows on its own; wide two-page artwork is shown as one image. Pages paired the wrong way? Step one page in single-page mode and go back; the book remembers it.
- **Swipe, keys and zoom** — swipe, arrow keys, pinch or Ctrl/⌘-scroll to zoom.
- **Books on the network, as they are** — connects directly to SMB (shared folders, NAS) and S3-compatible storage. Only the parts you read are fetched, so large books open in seconds. With S3 on the internet, the same shelf away from home.
- **Formats** — PDF (scanned images), ZIP / CBZ, RAR / CBR, 7Z / CB7, TAR / CBT, LHA / LZH, EPUB, and folders of JPEG / PNG / WebP / GIF / AVIF / BMP.
- **Pick up where you left off** — remembers your page in every book and moves on to the next volume in the same folder.
- **And more** — reading history, page overview, slideshow, brightness and contrast, grayscale. Nine languages.

No data is collected and there are no ads.

<p align="center">
<img src="https://naviiview.navii.online/img/mac-spread-ui-en.jpg" width="48%" alt="Two-page spread with the floating toolbar and seekbar">
<img src="https://naviiview.navii.online/img/mac-grid-en.jpg" width="48%" alt="The page overview">
</p>

### Questions, bugs, "this book won't open"

[Discord](https://discord.gg/pxv9msDyJ) · [Support](https://naviiview.navii.online/support) · [Privacy](https://naviiview.navii.online/privacy)

---

## 日本語

NaviiView は、漫画や画像の本を見開きで読むためのコミックビューアです。PDF・zip・rar・7z・epub・画像フォルダを、パソコンの中からも、NAS や S3 からも、そのまま開けます。お気に入りは本棚に表紙で並びます。

**Linux 版は無料です。** フリーウェアであってオープンソースではありません。このリポジトリにあるのはリリース・ライセンス・パッケージの定義で、ソースコードは公開していません。

### ダウンロード

| 面 | 場所 | 価格 |
|---|---|---|
| **Linux**（x86_64） | [GitHub Releases](https://github.com/takakix2/naviiview/releases/latest) — `.AppImage`・`.deb`・`.rpm` | **無料** |
| **iPhone / iPad / Mac** | [App Store](https://apps.apple.com/app/id6824969523) | 1 回の購入で 3 つとも |
| **Android** | Google Play | 準備中 |
| **Windows** | Microsoft Store | 準備中 |

Linux は Ubuntu 22.04 以降（glibc 2.34 以上・WebKitGTK 4.1）。Flathub と AUR は準備中で、定義は `packaging/linux/` にあります。

### できること

- **お気に入りを、表紙で** — 読んでいる本のツールバーや本の場所から本棚へ。入れた順・名前順で並べ替え。巻ごとのフォルダもそのまま。
- **見開きで読む** — 見開き / 単ページ / 縦スクロール。右開きと左開き。表紙は 1 ページ目だけで、横長の見開きイラストは 1 枚で。組みがずれた本も、単ページで 1 枚送って見開きに戻せば直ります（本ごとに記憶）。
- **スワイプも、キーも、拡大も** — スワイプ、矢印キー、ピンチや Ctrl / ⌘＋スクロールでの拡大。
- **ネットワークの本をそのまま** — SMB（共有フォルダ・NAS）と S3 互換のストレージに直接つなぎます。読む所だけを取りに行くので、大きな本も数秒で開きます。インターネット上の S3 なら、外出先からも同じ本棚を開けます。
- **対応ファイル形式** — PDF（スキャンした画像の PDF）・ZIP / CBZ・RAR / CBR・7Z / CB7・TAR / CBT・LHA / LZH・EPUB・画像のフォルダ（JPEG / PNG / WebP / GIF / AVIF / BMP）。
- **続きから読める** — 本ごとに読んだ位置を覚え、同じフォルダの前の巻・次の巻へそのまま移れます。
- **ほかにも** — 読書履歴、ページの一覧、スライドショー、明るさとコントラスト、モノクロ表示。9 つの言語。

データを集めません。広告もありません。

### 質問・不具合・「この本が開けない」

[Discord](https://discord.gg/pxv9msDyJ) · [サポート](https://naviiview.navii.online/support) · [プライバシー](https://naviiview.navii.online/privacy)

---

<div align="center">

Comic in the screenshots: Give My Regards to Black Jack, SHUHO SATO ／ 画面の作品: ブラックジャックによろしく　佐藤秀峰

</div>
