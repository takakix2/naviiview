<div align="center">

# NaviiView

**Your scanned comics, two pages at a time.**  
**自炊した漫画を、見開きで軽快に。**

[![Website](https://img.shields.io/badge/Website-naviiview.navii.online-6366f1?style=flat-square)](https://naviiview.navii.online)
[![App Store](https://img.shields.io/badge/App_Store-¥500_/_$4.99-black?style=flat-square&logo=apple)](https://apps.apple.com/app/id6824969523)
[![Linux Release](https://img.shields.io/badge/Linux-Free_Download-green?style=flat-square&logo=linux)](https://github.com/takakix2/naviiview/releases)
[![Discord](https://img.shields.io/badge/Discord-Join_Community-5865F2?style=flat-square&logo=discord)](https://discord.gg/pxv9msDyJ)

<br>

**Language / 言語**: [English](#-english) · [日本語](#-日本語)

</div>

---

## 🌐 English

NaviiView is a fast, minimalist comic viewer tailored for scanned manga, comics, and artbooks. Built with **Tauri v2** and pure **Rust**, it delivers instant page turns, true two-page spreads that line up accurately, and zero-wait network streaming straight from your home NAS or cloud storage without downloading entire files.

### ⚡ Key Features

- **Spreads That Line Up Perfectly**:
  - Two-page spread, single page, or smooth vertical scroll.
  - Instant toggle between Right-to-Left (Manga standard) and Left-to-Right (Western comics).
  - Isolated cover view (page 1) and automatic detection of double-page wide art.
  - Misaligned spreads? One keypress switches to single-page, advances one page, and restores spreads—remembered per book.
- **No Waiting Between Pages**:
  - Aggressive read-ahead caching with background GPU decode—no black flashes or lagged halves.
  - Persistent disk-backed thumbnail cache for seekbars and page overviews.
- **Read Directly from Network (SMB / S3)**:
  - Native **SMB** (NAS / Windows shared folders) and **S3-compatible storage** (MinIO, R2, etc.) support.
  - Only fetches the exact byte ranges needed for the current pages. Giant multi-gigabyte archives and PDFs open in seconds.
- **Foldable & Dual-Screen Ready**:
  - Seamless layout on foldable devices (such as iPhone Duo), matching the center fold with the book's spine.
- **Wide Format Support**:
  - Archives: `ZIP`, `CBZ`, `RAR`, `CBR` (RAR4/5 via pure Rust `rars`), `7Z`, `CB7`, `TAR`, `CBT`, `LHA`, `LZH`, `EPUB`
  - Documents: Scanned image-only PDFs
  - Images: `JPEG`, `PNG`, `WebP`, `AVIF`, `GIF`, `BMP`

### 📱 Platforms & Download

| Platform | Channel | Price |
|---|---|---|
| **Apple (iOS / iPadOS / macOS)** | [Download on App Store](https://apps.apple.com/app/id6824969523) | ¥500 / $4.99 (Universal Purchase) |
| **Linux (x86_64)** | [Download on GitHub Releases](https://github.com/takakix2/naviiview/releases) | **Free** (`.AppImage`, `.deb`, `.rpm`) |
| **Windows** | Microsoft Store (Coming soon) | ¥500 / $4.99 |
| **Android** | In development | TBD |

---

## 🇯🇵 日本語

NaviiView は、自炊したコミック・漫画の閲覧に特化した高速・軽量なコミックビューアです。**Tauri v2** と純 **Rust** で構築され、待たせない軽快なページ送り、決してずれない美しい見開き表示、そして NAS やクラウドストレージから丸ごとダウンロードせずに直接開ける高速ストリーミング読書を提供します。

### ⚡ 主な特徴

- **破綻のない見開きレイアウト**:
  - 見開き（2ページ）/ 単ページ（1ページ）/ 縦スクロールの自由な切り替え。
  - 右開き（日本の漫画標準・RTL）と左開き（LTR）の瞬時切り替え。
  - 表紙（1ページ目）の単独表示、見開きぶち抜きイラストの自動検出。
  - 見開きの組みがずれている本も、単ページで1枚送って見開きに戻せば直る（本ごとに状態を自動記憶）。
- **待たないページ送り**:
  - 前後のページを先読みし、GPUデコードを裏で済ませてから一度に切り替えるため、黒飛びや片側遅延が発生しません。
  - シークバーとページ一覧のサムネイルはディスクにキャッシュ（次回以降瞬時に復元）。
- **ネットワークの本をそのままストリーミング (SMB / S3)**:
  - 純 Rust 製の **SMB**（NAS / 共有フォルダ）および **S3互換ストレージ**（MinIO, R2等）接続エンジンを内蔵。
  - ファイルを丸ごとダウンロードせず、読むページだけを取りに行く（Range リクエスト）ため、数GBの巨大な本も数秒で開きます。
- **折りたたみ端末対応**:
  - 折りたたみスマホ（iPhone Duo等）で見開き表示した際、端末中央の折り目がそのまま単行本の綴じ目にピタッと重なる快適な読書体験。
- **多彩な対応フォーマット**:
  - 書庫: `ZIP`, `CBZ`, `RAR`, `CBR`（RAR4/5対応）, `7Z`, `CB7`, `TAR`, `CBT`, `LHA`, `LZH`, `EPUB`
  - 文書: 画像のみで構成された自炊 PDF
  - 画像: `JPEG`, `PNG`, `WebP`, `AVIF`, `GIF`, `BMP`

### 📱 対応プラットフォームとダウンロード

| プラットフォーム | 提供場所 / リンク | 価格 |
|---|---|---|
| **Apple (iOS / iPadOS / macOS)** | [App Store でダウンロード](https://apps.apple.com/app/id6824969523) | ¥500 / $4.99 (買い切り・ユニバーサル購入) |
| **Linux (x86_64)** | [GitHub Releases からダウンロード](https://github.com/takakix2/naviiview/releases) | **無料** (`.AppImage`, `.deb`, `.rpm`) |
| **Windows** | Microsoft Store にて近日公開予定 | ¥500 / $4.99 (買い切り) |
| **Android** | 開発中 | 未定 |

---

<div align="center">

**NaviiView** — Built for comic lovers and scan enthusiasts.  
[公式サイト](https://naviiview.navii.online) · [Discord コミュニティ](https://discord.gg/pxv9msDyJ)

</div>
