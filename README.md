# quine-python

## 環境
### 必要に応じてやること
1. pyenvがない場合 : 環境に合ったpyenvのインストール
1. 対応のpythonバージョンがない場合 : `pyenv install  $(cat .python-version)`
1. venvがない場合 : `python -m venv [venvname]`
1. remote repoのライブラリ変更時 : `pip install -r requirement.txt`
1. ライブラリ更新時 : `pip freeze > requirements.txt`
### 起動
1. `pyenv local`
1. `source [venvname]/bin/activate`
1. jupyter notebook もしくはVScode拡張でカーネルを選択
### 離脱
1. `deactivate`

## ルール
自身を出力するプログラムコード
### 禁止事項
* 自身のファイルを取得して展開する
* 空のスクリプト

## 参考資料
[プログラマの知的遊戯！自身を出力するプログラムQuineの作り方【東工大院生の日常会話切り抜き】#3](https://www.youtube.com/watch?v=KHdDVSpK2sY)