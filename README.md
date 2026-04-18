# トレミツ — 公開ページ

V.P.Mトレーニング管理LINE公式サービス「トレミツ」の公開ページです。  
GitHub Pages で公開し、LINE Developers のプライバシーポリシー・利用規約URLとして登録します。

## ファイル構成

| ファイル | 内容 | LINE登録用URL |
|---|---|---|
| `index.html` | サービス紹介・トップページ | — |
| `privacy.html` | プライバシーポリシー | ✅ 登録する |
| `terms.html` | 利用規約 | ✅ 登録する |

## GitHub Pages の公開手順

1. このフォルダ（`legal-pages/`）の内容を**新しいGitHubリポジトリ**にプッシュ  
   例: `github.com/h1rakichi/toremitsu-legal`

2. GitHubリポジトリの **Settings → Pages** を開く

3. Source を **"Deploy from a branch"** → Branch: `main` / `/ (root)` に設定して Save

4. 数分後に以下のURLが有効になる  
   ```
   https://h1rakichi.github.io/toremitsu-legal/
   https://h1rakichi.github.io/toremitsu-legal/privacy.html
   https://h1rakichi.github.io/toremitsu-legal/terms.html
   ```

5. LINE Developers コンソール →「プライバシーポリシーと利用規約」に上記URLを登録

## index.html の友だち追加リンク

`index.html` 内の以下の箇所を、実際のLINE公式アカウントのURLに変更してください：

```html
<a class="btn" href="https://lin.ee/XXXXXXX" ...>
```

LINE Official Account Manager → アカウント設定 → 友だち追加リンク から取得できます。
