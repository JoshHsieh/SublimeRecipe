Sublime Recipe
=========================
## Document Information
     Version : 1.01
     Author : josh@octalord.com
     Created Date: 2014-04-16
     PS. 以Mac OS環境編寫，如在其他OS，cmd or ⌘請以ctrl鍵代替


## Package 的 快速鍵 (**粗體表示經常使用**)

### ctags [...link](https://github.com/SublimeText/CTags)
 > 1. 建議在每次加入新的 gem的時候重新rebuild
 > 2. navigate to : shift + ctrl + .
 > 3. back : shift + ctrl + ,

### markdown preview [...link](https://github.com/revolunet/sublimetext-markdown-preview)
 > 1. preview in browser : alt + m

### sublime alignment [...link](http://wbond.net/sublime_packages/alignment)
 > 1. Sublime_Alignment -> 對齊程式碼 ⌘ + ctrl + a (會針對 = , : 兩個符號)原本預設只有針對 =
所以要去Preferences > Packages Settings > Alignment > Settings - User 增加以下
```
{
    "alignment_chars": ["=", ":"]
}
```

### BeautifyRuby [...link](https://github.com/CraigWilliams/BeautifyRuby)
 > 1. formatting code : ctrl + ⌘ + k


## sublime 操作shortcut

### sublime 本身行為 :
 > 1. 再打開另外一個新的window -> ⌘ + shift + n
 > 2. 關閉新的window -> ⌘ + shift + w
 > 3. **切換window -> ⌘ + `**
 > 4. 關閉或顯示side bar -> ⌘+k+b
 > 5. 全螢幕 -> F11 or shift + F11
 > 8. open console(輸入python 指令) -> ⌃+`
 > 9. switch project -> ⌘ + ctrl + p
 > 10. 切换到第N个标签页去 -> command + n
 > 11. 順序切換頁籤 -> alt + ⌘ + 左右箭頭

### 視窗操作
 > 10. split window -> 只會作用於同一個project 的文件 ⌘ + alt + n(要分成幾個區域)要回復原狀的話 ⌘ + alt + 1
 > 11. 將文件移到分割出的視窗 -> ctrl + shift + n(哪一個視窗)
 > 12. 將游標移到相對應的視窗 -> ctrl + n(哪一個視窗)
 > 13. summary:有時候我時常左邊放HTML檔，右邊放CSS檔，一邊看一邊編輯，這時候就要分割畫面。輸入：⌘+alt+數量就可以把視窗分割成你要的數量。

### 游標操作
 > 1. **區塊選取 : 按住option+按著滑鼠左鍵直行往下拖曳選取**
 > 2. 同時多個游標 - 按住⌘+點選你要的位置
 > 3. 讓游標消失 -> ⌘ + shift + k
 > 4. 讓游標消失但是光棒還在只是亮度變暗 -> ctrl + 0 (*好無聊的功能*)
 > 5. **選擇一整行 ⌘ + l(重複按就可以將下一行加入選擇)**
 > 6. **選擇詞 ⌘+d 選擇詞(重複按下時多重選擇相同的詞進行多重編輯) **
 > 7. **選擇括號內容ctrl + shift + m, ex. ()**

### edit操作
 > 1. 修改多行 -> 先把要修改的行mark起來，接著按下⌘ + shift + L (按esc可以回到原本單行模式)或是直接按住⌘ 再案要修改的行列，在這種模式下滑鼠的游標可以指到不同的地方
 > 2. 文字轉大小寫 -> ⌘ +k + u (大寫) ⌘ +k + l (小寫)
 > 3. **刪除游標到行頭 -> ⌘ +del (⌘⌫)**
 > 4. **刪除游標到行尾 -> ⌘ + k + k**
 > 5. **刪除目前行 -> ctrl+shift+k or ⌘+x**
 > 6. **交換上下兩行 -> ctrl + shift + 上下箭頭**
 > 7. **將目前行上下移動 -> ctrl + ⌘ + 上下箭頭**
 > 8. **增加縮排 -> ⌘ + ]**
 > 9. **減少縮排 -> ⌘ + [**
 > 10. **貼上符合縮排** :
     有時候從網站上複製一段code，常常貼上的部份本身就有縮排，貼完卻只有第一行有縮排，其他跑到前面。複製完後，輸入：**shift+⌘+v**也就是在原本的貼上加上shift就可以解決！
 > 11. 全部保存 -> alt+⌘+s
 > 12. 在没有选择区域时，复制当前行 -> ⌘ + c
 > 13. 向上复制当前行 -> shift+⌘+d（即在当前行的上面插入同样的一行内容，光标还在当前行）
 > 14. 註釋 -> ⌘ + /
 > 15. 多行注釋 -> ⌘ + alt + / (不好用)
 > 16. **前後字元互換 -> ctrl + t**
 > 17. **合併多行 : 將兩(多)行選取按下 ⌘ + J 就會合併成一行**
 > 18. **自動提示auto complete : ⌃ + space(重複按下選擇下一個提示)**


### navigate 相關
 > 1. **⌘+t 前往文件**
 > 2. **快速找文件 -> ⌘ + p or ⌘ + t, 在對話匡裡面直接打文件名稱就可以模糊搜尋**
 > 3. **跳至相對應括號 ctrl + m (大括號 中括號 小括號)**
 > 4. **快速找function or method -> ⌘ + p, 在對話匡裡面直接打@ 會列出當前文件的 function或是直接 ⌘ + r**
 > 5. **當編輯html 時 -> ⌘ + p, 在對話匡裡面直接打@ 會列出 id 關鍵字**
 > 6. **跳到指定行數 ctrl+g(⌃G)**
 > 7. **前往method : ⌘+r**
 > 8. 前往 project : ⌘+⌃+p  前往項目
 > 9. search & replace
     1. **find 這一份文件 : ⌘+F**
     2. **在當前文件尋找與取代 : ⌥+⌘+f**
     3. ⌘+⌥+g  跳到下一個符合查詢的內容
     4. ⌘+⌃+G  將所有符合當前所選的內容mark起來進行多重編輯
     5. ⌘+⇧+F  在所有打開的文件中進行查找
 > 10. bookmark
     1. ⌘+F2  添加/去除書籤(bookmark)
     2. F2   下一個書籤
     3. ⇧+F2  前一個書籤
     4. ⌘+⇧+F2   清除書籤

### for html & xml useage
 > 1. **⌘+⇧+a  選擇標籤內的內容, ex. <div></div>之間的內容**
 > 2. **輸入標簽，產生結尾標簽 ⌘ + alt + . ex. 輸入<body>產生</body>**





