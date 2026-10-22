# ナチュラル・キーチェンジャー（スマホ版）

YouTube / YouTube Music / TikTok の動画のキーを、声質を保ったまま変えます。YouTube では歌詞も出ます。
インストールするのは `natural-key-changer.user.js` という 1 ファイルだけです（自動で最新版に更新されます）。

**インストール用リンク（スマホで開く）**

https://raw.githubusercontent.com/kanzakideath/natural-key-changer-updates/main/mobile/natural-key-changer.user.js

## iPhone / iPad（Safari）

1. App Store で **Userscripts**（無料・作者 Justin Wasack）をインストールして、一度アプリを開く
2. 設定 → Safari → 機能拡張 → **Userscripts** をオン → 「すべてのウェブサイト」を **許可**
3. アプリの指示どおり、スクリプトを保存するフォルダを選ぶ（「Open Save Location」→ iCloud/このiPhone内のフォルダ）
4. Safari で上のリンクを開く → 「Userscripts」のアイコン（Aa の中）→ **インストール**
5. YouTube（m.youtube.com）を開き、右下の **♪** ボタン → ＋／− でキー変更

## Android（Firefox）

1. **Firefox** をインストール → メニュー → アドオン → **Violentmonkey** を追加
2. Firefox で上のリンクを開く → 「インストール」を押す
3. YouTube を開き、右下の **♪** ボタン → ＋／− でキー変更

（Chrome for Android は拡張機能が使えないため、Firefox を使ってください。Kiwi Browser でも Violentmonkey / Tampermonkey で動きます。）

## 使い方・仕様

- ＋／− …… キーを 1 半音ずつ変更（−12〜＋12）。「元のキーに戻す」で戻ります。動画ごとにキーを覚えます（次に開いたとき、画面を 1 回タップすると反映）。
- 歌詞 …… LRCLIB から取得（時間つき）。LRCLIB に無い曲や LRCLIB が混雑しているときは NetEase Cloud Music / QQ Music の時間つき歌詞から探します。ずれたら「タイミング調整」の「早く／遅く」か、今歌っている行をタップ。
- スマホ版では AI による歌声の聞き取り・自動タイミング合わせ・高音質（歌声分離）モードは使えません。
- キーを 0 にしている間は何も処理せず、動画本来の音のままです。
- 音声は端末内で処理され、どこにも送られません（歌詞の検索で曲名・歌手名を歌詞データベースに送るだけです）。
