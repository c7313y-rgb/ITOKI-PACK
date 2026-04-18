# イトーキパッケージ LP

GitHub Pages 用の静的サイトです。

## 構成
- `index.html` : LP 本体
- `assets/` : 画像アセット

## 公開手順
1. このフォルダ一式を GitHub リポジトリ直下へアップロード
2. `Settings` → `Pages` を開く
3. `Build and deployment` で `Source: Deploy from a branch` を選択
4. `Branch: main` / `/ (root)` を選択して保存
5. 数分待つと公開URLが発行されます

## 補足
- GitHub Pages で画像が出ない場合は、ファイル名の大文字小文字差異を確認してください
- Jekyll の影響を避けたい場合は、空ファイル `.nojekyll` をリポジトリ直下に置いてください
