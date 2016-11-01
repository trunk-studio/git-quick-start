# checkout

checkout 可用於將特定版本檔案取出，無論是資料夾或檔案皆可

## 取出特定檔案

> 將 test.txt 內容做修改

![checkout example](./checkout.png)

1. 於 SourceTree 左側的專案列表上找到您欲取出檔案的專案
2. 點擊 Working Copy 查看你目前對專案的變更
3. 點擊 test.txt 便可以於右邊面板查看該檔案詳細變更
4. 點擊 Discard hunk 按鈕，便可以捨棄對 test.txt 的變更，此範例中 test.txt 內容會還原成 123

## 本章節操作對應之 git 指令

`git checkout <file path>`
