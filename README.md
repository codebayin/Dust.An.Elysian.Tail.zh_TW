# Dust.An.Elysian.Tail.zh_TW
《塵埃：幸福的軌跡》公開中文化項目，CodeBay.in 第一個公開項目，順便藉此找出潛力股。
不會 git 的人但有意見可以發 Issue，只要有 github 帳號就可以發了。

# 標點符號準則
符號一律使用全形符號，請參考[標點符號手冊](http://www.edu.tw/files/site_content/M0001/hau/haushou.htm)，
打不出來的符號，就直接複製此網頁上的符號，不要找相似的貼，有時樣子一樣但編碼不一樣，
套上字型後的呈現就會不同。

* 夾注號一律採用甲式。
* 書名號使用乙式第一種。
* 英文的單引號'、雙引號"一律改用中文引號「」，『』視情況使用。
* 英文的破折號-，中文是──，是兩個全形字，不是一個。
* 刪節號……也是兩個全形，不是英文的六個點......。
* 英文和中文之間不需留空白，符號跟英文和中文之間也不需留空白。
* 遇到特殊變數(遊戲中會取代成圖案、標誌之類的)，變數前後要留空白，鄰接標點符號則不用。
* 遇到 1 of 5 這種顯示數量的地方，可以用 1/5，/是英文半形斜線，不需要用全形的。
* 其它待補充。

# 翻譯準則
* 遇到名詞先查看之前是否有已經翻的，直接採用之前的，要改留到最後，用工具一次取代才不會出錯。
* 請先找沒人翻的開始，還沒翻完不進行潤飾別人的翻譯，只潤飾自己正在翻的。
* 盡可能從對話開始，介面部分(Strings 開頭的)我會統一處理。

# 協作流程
以下直接是寫執行命令，如果是用其它工具的人，UI上都會有對應的功能。

1. 點選 fork 將專案複製至自已的帳號底下。
2. 將你 fork 過去的專案，也就是你自己的專案 clone 到你的本地端。
3. 在 clone 的專案下新建分支（branch），並切換到你的分支上，名稱取為「trans」，命令為`git branch trans` + `git checkout trans`
4. 執行 `git remote add upstream https://github.com/codebayin/Dust.An.Elysian.Tail.zh_TW.git` 將本庫加為遠端庫。
5. 執行 `git remote update` 更新
6. 執行 `git fetch upstream master` 拉取本庫更新到你的本地
7. 執行 `git rebase upstream/master` 將更新內容整併到你的分支

以上為初始化流程，如果 upstream 有更新請執行 5~7 即可，平時請在自己的分支上作業。
最後發 pull-request 將翻譯內容加回至本專案，每次發之前請務必確認是否更新同步了最新版。
儘量以一個檔為單位推送。

# 推薦工具
以下是會用到的工具，你有順手的也可以用自己順手的。

* 翻譯工具：[Zeta Resource Editor](http://www.zeta-resource-editor.com/)。
* 協作工具：[SourceTree](https://www.sourcetreeapp.com/)。
