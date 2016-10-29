# clone

要下載遠端數據庫需要進行複製（Clone）的操作。

執行複製後，可以把遠端數據庫裡的內容全部下載下來，之後您可以在另一台機器的本地數據庫上進行操作。

## 取出遠端專案

> 以 bitbucket 上代管的遠端數據庫為例

#### 取的遠端數據庫網址

![clone example](./clone.png)

1. 點擊 bitbucket 側邊選單上的 Clone
2. 複製指令

#### 開啟 SourceTree 進行 Clone 操作

![clone example](./clone2.png)

3. 點擊 SourceTree 工具攔上的 Clone/New
4. 貼上剛剛複製之指令
5. 設定本地數據庫放置資料夾（Optional）
6. 點擊 Clone 按鈕

## 本章節操作對應之 git 指令

`git clone /path/to/repository`

`git clone username@host:/path/to/repository`


## 練習

1. 進入網址 <https://github.com/agileworks-tw/git-hello-world>
2. 取得 https git url
3. 執行 `git clone <https git url>`
4. 確認專案以複製完成
