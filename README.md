# misskey-game-lore-css

ゲームすきーのカスタム CSS
https://misskey.gamelore.fun/
※新規受付停止やフォロー承認制度が採用されている場合があります

## 注意事項

Misskey ではカスタム CSS を推奨している訳ではなく、UI 破損の原因となる場合もあるため、十分に注意してください。
当リポジトリのコードは Luminus が動作確認済みですが、カスタムした場合の動作は保証しません。

## 設定方法

Misskey への適用方法
※PC、スマホのブラウザで利用している場合

### Misskey のカスタム CSS 入力欄を開く

設定 → クライアント設定（全般） → カスタム CSS
![スクリーンショット 2023-03-02 024044](https://i.imgur.com/F8FvWRx.png)

### ソースをコピペする

下記のソースをコピペして貼り付けて保存する。
https://github.com/luminus-xd/misskey-game-lore-css/blob/main/style.css

```bash
│  .gitignore
│  .prettierrc
│  .stylelintrc.json
│  LICENSE.md
│  package.json
│  README.md
│  style.css ← これを使う
│  yarn.lock
│
└─.vscode
        settings.json
```
