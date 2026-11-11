# YouTube Manager OAuth用ページ

GitHub Pagesで公開するための簡易サイトです。

## 公開前に必ず変更する箇所
1. `index.html` と `privacy.html` の `[連絡先メールアドレス]` を実際の問い合わせ先に置き換える
2. アプリ名を変更する場合は両HTML内の `YouTube Manager` を変更する
3. `privacy.html` の「取得する情報」「保存と管理」を、実際のアプリの挙動に合わせて修正する
4. 実際に公開したURLをGoogle Cloud Consoleのブランディング設定に登録する

## GitHub Pagesでの公開
1. GitHubで新しい公開リポジトリ（例: `youtube-manager-site`）を作成
2. このフォルダ内の `index.html` `privacy.html` `style.css` `README.md` をリポジトリ直下へアップロード
3. GitHubのリポジトリで Settings → Pages を開く
4. Build and deployment を「Deploy from a branch」にし、Branchを `main`、フォルダを `/ (root)` にして保存
5. 数分後に表示される `https://ユーザー名.github.io/youtube-manager-site/` を確認
6. プライバシーポリシーURLは末尾を `privacy.html` にする

※ Googleの審査・ポリシー要件を満たすことを保証するものではありません。実際のデータ取扱いと一致させてください。
