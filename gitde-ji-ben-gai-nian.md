# Git的基本概念

---

## Repositories

Repository 為 Git 版本控制中的程式庫， 其中**存放了專案中所有需要被管理及記錄的修改資訊以及使用的歷史紀錄**，舉凡專案所建立的程式檔、文字檔都會由respository保存起來。而較特別的是，Git的respository除了保存專案中的資訊以外，也記錄了本身 repository的資訊，如此的做法讓未來若要clone\(複製\)該repository至其他裝置上更加方便。

每一個repository都會有自身的變數配置，如使用者信箱、使用者名稱等，這些配置在複製時不會被拷貝到其他裝置上，Git也是使用這些配置管理每個檔案、提交的資料，區分不同使用者、不同的repository。

Repository之中保有了兩種資料：

1. **物件\(Objects\)**：使在建立副本時能夠更有效率
2. **索引\(indexes\)**：為在該repository中暫存的訊息

以上兩種資料都是被存放於隱藏目錄.git/底下。

## Git Objects

Git objects 總共為四種：

1. 二元大型物件\(Blobs\)
2. 樹\(Trees\)
3. 提交\(Commits\)
4. 標籤\(Tags\)

利用這些物件，Git儲存了原始的檔案資料、歷史修改記錄、作者訊息、日期以及不同版本的訊息。





