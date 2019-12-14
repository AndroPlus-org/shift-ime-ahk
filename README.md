# shift-ime-ahk

## 概要

左右 Shift キーの空打ちで IME を OFF/ON する AutoHotKey スクリプトです。

* 左 Shift キーの空打ちで IME を「英数」に切り替え
* 右 Shift キーの空打ちで IME を「かな」に切り替え
* Shift キーを押している間に他のキーを打つと通常の Shift キーとして動作

## 動作環境

* Windows10
* Windows7

Windows8 は試していませんが多分動きます

## 使い方

[releases](https://github.com/AndroPlus-org/shift-ime-ahk/releases) から shift-ime-ahk.exe をダウンロードして好きな場所に置き、起動してください。 タスクトレイに常駐します。

終了する場合はタスクトレイのアイコンを右クリックし、「終了」をクリックしてください。

アンインストールは shift-ime-ahk.exe を削除するだけで OK です。

## JetBrains 製の IDE で使う場合は Tool Buttons をオンに

IntelliJ IDEA, PhpStorm など JetBrains 製の IDE をお使いの方は「上部メニューバー　＞　View　＞　Tool Buttons」をオンにしてください。

オフのまま使うと Shift キーを離した際に shift-ime-ahk.exe がエラー終了します。

## ブログの紹介ページ

このツールは karakaram 氏の alt-ime-ahk を編集したものです。
[Altの空打ちで日本語入力(IME)を切り替えるツールを作った](http://www.karakaram.com/alt-ime-on-off)
