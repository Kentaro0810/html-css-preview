# HTML・CSS・JavaScriptプレビュー

HTML、CSS、JavaScriptの表示と動作を制限付きiframe内で確認する開発補助ツールです。

## v1.1.0の変更点
- JavaScript入力欄を追加
- JavaScript実行のオン・オフを追加
- console.log、info、warn、errorの表示に対応
- 実行時エラーと未処理Promise rejectionの表示に対応
- 実行停止ボタンを追加
- HTML・CSS・JavaScriptの下書き保存に対応
- プレビューHTMLへのJavaScript埋め込みに対応
- Content Security Policyで外部通信・外部リソースを禁止

## 安全上の制限
- JavaScriptは初期状態でオフ
- sandbox付きiframe内で実行
- 外部通信、外部スクリプト、外部CSS、外部フレームを禁止
- 親ページと同一オリジンにしない
- 新しいウィンドウ、トップページ移動、カメラ、マイク、位置情報を許可しない

## 公開方法
GitHubの `html-css-preview` リポジトリで4ファイルを上書きし、GitHub Pagesから公開します。
