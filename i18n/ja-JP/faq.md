## Genshin Wishesとは?
Genshin Wishesはオープンソース(https://github.com/genshin-wishes)の祈願履歴ビューワーです。[Colin Auberger](https://www.linkedin.com/in/colin-auberger/)と[Jimmy Vergerolle](https://vergerolle.fr)等有志によりメンテナンスされています。

できること:
- 祈願履歴のバックアップ
- 通常・イベント祈願別の天井カウンタ
- 祈願履歴の絞り込み検索
- 詳細な統計データの表示

## どのように祈願データを取得しているのですか?
単純に祈願履歴を取得しているだけです。原神のゲーム内で閲覧できる履歴はゲーム内ブラウザで表示しているだけで、リンクがあれば通常のブラウザからも閲覧可能になっています。必要なのはゲームから提供される一時的なキーのみで、その一時キーは報告ページのURLより取得することができるものです。

## 必要なURLはどこで入手できますか?
### PC
こちらの[動画](https://www.youtube.com/watch?v=a16X0R_rSZc)を参照するか、以下のガイドに従って入手できます。
1) パイモンメニューより「報告」を選択するとウェブブラウザが開きます
2) 表示されたページのURLをコピーし、Genshin Wishesに貼り付けます

### Android
こちらの[動画](https://www.youtube.com/watch?v=hok0jCjSrjo)を参照するか、以下のガイドに従って入手できます。
1) パイモンメニューより「報告」を選択します
2) Wi-Fiおよびデータ通信を切断します
3) 右上の再読み込みボタンをタッチします
4) ページにバグが発生し、URLを表示します
5) URLをコピーし、Genshin Wishesに貼り付けます

### iOS
こちらの[動画](https://www.youtube.com/watch?v=HW8nywx9Tio)を参照するか、以下のガイドに従って入手できます。
1) パイモンメニューより「報告」を選択します
2) サポートページより「アカウント」を選択します
3) 「miHoYo通行証のパスワードの変更方法を教えて下さい」を選択します
4) 青文字で表示された「アカウント管理」をクリックすると、ウェブブラウザが開きます
5) 表示されたページのURLをコピーし、Genshin Wishesに貼り付けます
   重要: このURLでパスワードを変更されることはありません。


### Consoles
1) Open your mail in-game during an event
2) Open the event related mail
3) There should be a QR code, scan it with your phone
4) Copy the URL and paste it on Genshin Wishes.

## セキュリティ的に安全ですか?
もちろん、安全です。原神プレイヤーとして、アカウントセキュリティには非常に注意を払っています。
- コンピューターやスマートフォンなどの**パスワードは一切要求しません**。
- **原神アカウントのパスワードも一切要求しません**。
- 取得する一時キーはサーバーではなく**端末のみ**に保存されます。
- 一時キーの保存期限は24時間だけで、期限が切れた後は同期のため新しいリンクを利用する必要があります。
- この一時キーはアカウント認証をGenshin Wishesに許可するものではありません。
- 祈願データを含め、いつでも全データの削除が可能です。
- SSL通信を行っていますので、安全にサイトの利用ができます。

## Genshin Wishesの使用によるアカウントBANの心配はありませんか?
絶対にありません。 ゲーム内で閲覧できる履歴と同様の方法でデータの読み込みを行っており(Mihoyo APIにより公開されています)、BANの危険性はありません。また、開発者もGenshin Wishesを使用していますが、これまでにBANされたことはありません。miHoYoは[サードパーティ製ツールの使用について](https://genshin.mihoyo.com/en/news/detail/5763)のページを公開しており、Genshin Wishesはここで示された指標に従っています。

## 何言語に対応していますか?
このサイトは英語・フランス語でメンテナンスされており、他の言語については[このプロジェクト](https://github.com/genshin-wishes/genshin-wishes-i18n)の[コントリビューター](https://github.com/genshin-wishes/genshin-wishes-i18n/blob/main/CONTRIBUTORS.md)によって翻訳されています。

## 統計の公開はできますか?
現在、アルファバージョンに取り組んでいます。できるだけ早く公開する予定です。