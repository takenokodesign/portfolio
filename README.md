# TAKEBON Portfolio

**竹中 明教 / Akinori Takenaka — Design Strategist × AI Innovator × Co-Creator**

> *"Design is not decoration. It is strategy made visible."*

---

## 🌐 Site URL

**GitHub Pages で公開後のURL:**
```
https://takenokodesign.github.io/takebon-portfolio/
```

---

## 📄 Pages

| File | Description |
|------|-------------|
| `index.html` | トップページ（Hero / Philosophy / Profile概要 / Projects概要 / Contact） |
| `takebon_portfolio.html` | index.html と同内容（直接アクセス用） |
| `takebon_profile.html` | プロフィール詳細（職務経歴書・スキル・受賞歴・学歴） |
| `takebon_works.html` | 作品一覧（13プロジェクト / カテゴリーフィルター付き） |

---

## ✨ Features

- **完全スタンドアロン** — 外部サーバー不要。画像はすべてBase64埋め込み済み
- **カスタムカーソル** — アクセントカラーのドット＋トレイル
- **ハンバーガーメニュー** — 左上固定のスライドインサイドナビ
- **アクセントカラー切り替え** — 右下の5色ドットでリアルタイム変更
- **スクロールリビール** — IntersectionObserver による滑らかなフェードアップ
- **スキルバーアニメーション** — スクロールイン時にバーが伸びる
- **ライトボックス** — Worksページで作品画像を拡大表示
- **Projects Coming Soon** — Worksページは整理中のため非公開。indexに "Coming Soon" 表示
- **プログレスバー** — スクロール進捗を上部に表示
- **フォント** — Cormorant Garamond / DM Mono / Noto Sans JP（Google Fonts）

---

## 🎨 Design Concept

```
キーワード: 螺旋、非線形
カラー: 黒 × 白 × アクセント（デフォルト #E8FF47）

参考:
  - takram.com  — ミニマルなタイポグラフィー
  - nosigner.com — 余白とグリッド
  - apple.com   — プロダクトサイトのスクロール演出
```

---

## 🗂 Site Structure

```
takebon-portfolio/
├── index.html              ← GitHub Pages エントリーポイント
├── takebon_portfolio.html  ← Home (index と同内容)
├── takebon_profile.html    ← Profile 詳細ページ
│   # takebon_works.html   ← Works 一覧（非公開・アップロード不要）
└── README.md               ← このファイル
```

---

## 🚀 GitHub Pages への公開手順

### Step 1 — リポジトリを作成

1. [github.com/new](https://github.com/new) を開く
2. Repository name: `takebon-portfolio`
3. **Public** を選択
4. "Create repository" をクリック

### Step 2 — ファイルをアップロード

**方法A：ブラウザからドラッグ&ドロップ（推奨）**

1. 作成したリポジトリページを開く
2. "uploading an existing file" リンクをクリック
3. 以下の4ファイルをドラッグ&ドロップ:
   - `index.html`
   - `takebon_portfolio.html`
   - `takebon_profile.html`
   - `takebon_works.html`
4. `README.md` も追加
5. "Commit changes" をクリック

**方法B：Git CLI**

```bash
git clone https://github.com/<your-username>/takebon-portfolio.git
cd takebon-portfolio
# ダウンロードしたファイルをこのフォルダにコピー
git add .
git commit -m "Initial portfolio launch"
git push origin main
```

### Step 3 — GitHub Pages を有効化

1. リポジトリの **Settings** タブを開く
2. 左メニュー "Pages" をクリック
3. Source: **Deploy from a branch**
4. Branch: `main` / `/ (root)` を選択
5. **Save** をクリック
6. 数分後に以下のURLで公開される:

```
https://<your-username>.github.io/takebon-portfolio/
```

---

## 🔧 カスタマイズ

### アクセントカラーのデフォルト変更

各HTMLファイルの `:root` 内を編集:

```css
:root {
  --accent: #E8FF47;  /* ← ここを変更 */
}
```

プリセットカラー例:
| 名前 | コード |
|------|--------|
| Lime（デフォルト） | `#E8FF47` |
| Orange | `#FF6B35` |
| Cyan | `#00F5FF` |
| Green | `#B8FF8C` |
| Pink | `#FF8EFF` |

### Contact メールアドレス変更

`index.html` / `takebon_portfolio.html` の Contact セクション:

```html
<a href="mailto:takenoko.design@mac.com">takenoko.design@mac.com</a>
```

---

## 📬 Contact

**TAKEBON**
- Email: [takenoko.design@mac.com](mailto:takenoko.design@mac.com)
- Location: Nagoya, Japan

---

## 📝 License

© 2026 Akinori Takenaka (TAKEBON). All rights reserved.  
ポートフォリオに使用されている画像・テキストの無断転載を禁じます。
