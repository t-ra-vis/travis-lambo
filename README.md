[README.md](https://github.com/user-attachments/files/29593657/README.md)
# TRAVIS LP

トラヴィスのLINE導線用ランディングページです。

## 公開前に必ず変更する項目

site/index.html 内の仮LINE URLを、本番URLへ置換してください。

検索する文字列：

https://example.com/line

ヘッダーを含めて4箇所あります。

## GitHubへアップロードする手順

1. GitHubで新しいリポジトリを作成します。
2. リポジトリ名は travis-lp など任意の名前にします。
3. このフォルダの中身を、リポジトリ直下へアップロードします。
4. main ブランチへコミットします。
5. GitHubの Settings → Pages を開きます。
6. Build and deployment の Source を GitHub Actions にします。
7. Actions タブで Deploy GitHub Pages が完了するのを待ちます。
8. Settings → Pages に表示されるURLから公開ページを確認します。

## ファイル構成

- site/index.html：公開ページ本体
- site/style.css：デザイン
- site/favicon.svg：ブラウザアイコン
- .github/workflows/deploy-pages.yml：GitHub Pages自動公開設定
- docs/TRAVIS_LP_SPEC.md：制作仕様書

## ローカル確認

site/index.html をブラウザで開くと確認できます。

## 更新方法

site 内のファイルを変更して main ブランチへ反映すると、GitHub Pagesが自動で再公開されます。

## 公開前チェック

- [ ] 仮LINE URLを本番URLへ変更した
- [ ] PCで表示を確認した
- [ ] スマートフォンで表示を確認した
- [ ] LINE CTAを3箇所すべてタップした
- [ ] ヘッダーのLINEリンクを確認した
- [ ] 誤字・金額・プロフィールを確認した
- [ ] 必要に応じてOGP画像とアクセス解析を追加した

## 未設定

以下は本番情報が確定してから追加してください。

- 本番LINE URL
- 独自ドメイン
- OGP画像
- アクセス解析タグ
- プライバシーポリシー等の法務ページ
