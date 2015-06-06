# リーダブルコードメモ

## リポジトリ
[https://github.com/S-Shimotori/S-Shimotori-sezemi-2015-readable-code](https://github.com/S-Shimotori/S-Shimotori-sezemi-2015-readable-code)

## 課題の説明
### spec1
#### ソースコード
* main.swift
#### リーダブルなところ
標準出力の関数の引数に直接レシピタイトルを記述しないで、グローバル定数としてタイトルを用意してそれを関数に与えた。また、その定数名は「k〜」とした。 
→何を出力しているのかがわかる。変数と違って値を後から変更できないので流れを追いやすくなる。グローバルであることがわかる。

### spec2
#### ソースコード
* README.md
