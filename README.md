# keyconfig
Autohotkey および かえうち用の設定ファイル

## 経緯
USキーボードを職場の日本語PCで使うにあたって、Windowsではキーボード配列の変更に管理者権限が必要なため、設定を変更せず使えるようかえうちを導入した。
せっかくキーボードをいろいろ設定できるようになったため、他にも不便なところを解消すべく模索中

## つかっているもの
### かえうち
[かえうち2 – かえうち](https://kaeuchi.jp/summary/)
キーボードのコードを別のコードに変換してくれるドングル。
USキーボードの入力をJISキーボードとして認識させるために導入
ついでに他にもショートカットを設定

### Autohotkey
[AutoHotkey](https://www.autohotkey.com/)
自宅用
かえうちとちがい、JISキーボードへの変換は行っていない。

## やりたいこと

### IMEのOn/Offをデフォルトのトグル式ではなく、onとOffを別々のキーに割り当てる。
左シフトに無変換、右シフトに変換キーを割り当て、IMEの設定で変換をIME ONに、無変換をOFFに設定。

### 矢印キー、home, pgUpなどをホームポジションから入力しやすくする。
具体的には独自の修飾キーとそれを利用したショートカットを作る
修飾キーとしては暫定的にCapslockを使っているが、これだとShiftやコントロールと同時に押すのが難しいため、問題がなければスペースを単押はそのまま、長押しで修飾キー扱いにしたい。スペース長押しで画面を動かすソフトもあるので、アプリにもよるだろうが…

hjkl 矢印キー
yuio Home, pgUp PgDn end
; bs
' Delete
