# 自分用のメモ
- forkしたバージョンを作業用に使っている。
- forkをせずに、dockerファイルの書き換えなどの少しの差分で動作させたい。

## 手順
- sudo make build-image
- sudo make run

## original との差分
- Makefile 中 "$${PWD}" への修正
- 
