# Git的基本概念

---

## Repositories

Repository 為 Git 版本控制中的程式庫， 其中存放了專案中所有需要被管理及記錄的修改資訊以及使用的歷史紀錄，舉凡專案所建立的程式檔、文字檔都會由respository保存起來。而較特別的是，Git的respository除了保存專案中的資訊以外，也記錄了本身 repository的資訊，如此的做法讓未來若要clone\(複製\)該repository至其他裝置上更加方便。

每一個repository都會有自身的變數配置，如使用者信箱、使用者名稱等，這些配置在複製時不會被拷貝到其他裝置上，Git也是使用這些配置管理每個檔案、提交的資料區分不同使用者、不同的repository。

