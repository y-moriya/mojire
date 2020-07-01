# mojire
Mouse Dictionary というブラウザ拡張機能の辞書ファイル（ねじれ天国向け）です。

ねじれ天国の説明書を元に、全ての役職・サブ役職の説明が含まれています。

## インストール手順

1. [Mouse Dictionary](https://qiita.com/wtetsu/items/c43232c6c44918e977c9) をインストール（Chrome、Firefox のみに対応しているようです）
2. [Release](https://github.com/y-moriya/mojire/releases) から最新版の Source code をダウンロード
3. ダウンロードしたファイルを解凍（dict.tsvファイルのみ使用します）
4. Mouse Dictionary の設定画面を開き、以下の手順で辞書ファイルを追加します
    1. 辞書データの文字コード：UTF-8
    2. 辞書データの形式：TSV(タブ区切り)
    3. 辞書データの読み込み（解凍した dict.tsv を選択）
    4. LOAD ボタンをクリック

これでインストールは終わりです。

## 使い方

辞書データの登録後、Mouse Dictionary のアイコンをクリックすると、翻訳結果の表示領域が表示されます。

この状態で「人狼」や「恋人」などのねじれ天国に存在する役職・サブ役職名の**先頭の文字**にマウスオーバーすると、表示領域に説明が表示されます。

## 辞書データの不備について

Issue や @euro_s までご連絡ください。