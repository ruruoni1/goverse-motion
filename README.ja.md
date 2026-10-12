# GULZA — 歌詞モーション動画メーカー

GULZA はブラウザーで歌詞や字幕のモーション動画を作り、MP4 に書き出すツールです。

このフォークでは、SRT 字幕ファイルを LRC に変換せず、そのまま読み込めます。

**[日本語版を開く](https://ruruoni1.github.io/gulza/ja/)** · [リポジトリのトップページ（韓国語）](README.md) · [元の JIZURA](https://github.com/852wa/JIZURA)

ほかの言語: [한국어](README.ko.md) · [English](README.en.md) · [繁體中文](README.zh-Hant.md) · [简体中文](README.zh-Hans.md) · [Bahasa Indonesia](README.id.md) · [Tiếng Việt](README.vi.md)

## はじめかた

1. SRT または LRC を読み込むか、歌詞を一行ずつ入力します。
2. 必要なら音声を読み込み、タイミングを調整します。
3. **おまかせ**でスタイルと構成を作ります。
4. プレビューを確認し、MP4 に書き出します。

SRT を読み込むと、字幕の開始・終了時刻と字幕間の空白を保持します。歌詞欄の時刻表記を編集することもできます。

## 画面と言語

画面上部のメニューで表示言語を変更できます。ルートの URL では韓国語が初期表示です。

**歌詞の言語**は別の設定です。歌詞に使う書体と文字の分割方法を選び、初期値は自動判定です。

手動タイミング調整、画面比率の選択、PNG 書き出し、プロジェクト JSON、After Effects 用 JSON にも対応しています。

GULZA は [JIZURA](https://github.com/852wa/JIZURA) のフォークです。ソースコードは [MIT ライセンス](LICENSE)で公開しています。
