IT-Terms-EN-CN
=============

English to Chinese Translation Table for Terminologies in Information Technology (IT) and Computer Science (CS)

IT術語及計算機科學術語中英文對照表

項目宗旨
=========

給出IT界英文術語的各種中文譯法，討論其優劣，並提出本社區推薦的譯法。

尊重**「習慣」**，但**決不盲從習慣**；**秉持學術立場**，敢於提出獨到見解，既**不避俗**，更**不媚俗**。

歡迎同好
========

歡迎**對IT術語翻譯感興趣**的各路朋友加入，尤其歡迎**不畏物議**的「書呆子」、「老頑固」、「外星人」、「學究」、「深宅」、「死理性派」等怪咖和稀有物種。當然，走常規路線的**各位譯者**也多多益善。有志加入者請提交[Issue](https://github.com/jeffreybaoshenlee/IT-Terms-EN-CN/issues)或與Jeffrey（eastarstormlee@gmail.com）聯繫。

編排形式
=======

總則：整個對照表分為28卷（volume），「A卷」至「Z卷」分別收錄首字母為「A/a」至首字母為「Z/z」的各個術語，「Number卷」收錄開頭為阿拉伯數字0至9的術語，「Symbol卷」收錄開頭為字符的術語。

以字母x開頭的詞條均位於volume-x-cht.md文件中，餘可類推。

貢獻方式
========

請通過Issue來提交英文術語的譯法，或表達自己對現存譯法之意見。

管理人員簡介
============

社區成員集體創作共用名：ITEC　（該詞是項目名稱IT-Terms-EN-CN的縮寫）

成員介紹

[jeffreybaoshenlee](https://github.com/jeffreybaoshenlee)

* 網名、筆名　愛飛翔
* 英文名　　　Jeffrey LEE
* 職業　　　　書生
* 研究方向　　代碼質量、代碼閱讀、代碼評審、圖書評論
* 電子郵箱　　eastarstormlee@gmail.com
* 個人網站　　http://www.agilemobiledev.com/
* 簡歷　　　　曾翻譯《NoSQL精粹》、《算法心得》（《Hacker's Delight》第2版）、《Effective Objective-C 2.0》、《Android遊戲開發實踐指南》、《HTML5 Canvas核心技術》等書

[Jraghajiva](https://github.com/Jraghajiva)

* 網名　　　　Asrakah Jraghajiva
* 英文名　　　jiva
* 研究方向　　二次元裡的動畫（Animation）、漫畫（Manga）、遊戲（Game）、科技（Technology），簡稱AMGT
* 簡歷　　　　母星伊茲坦已經在四百地球年前的時候廢棄了，如今定居在伊茲坦3和伊茲坦a-6441上，本人曾經在伊茲坦帝國聯合政治學院進修，取得Orih學位，後任伊茲坦常駐圖盧茲t-0083殖民地的特派外交隨從，在聖歷776940年伊茲坦加入泛銀河聯盟的時候任聯盟常駐見習參事，後泛銀河聯盟與伊爾提蘭特聯盟組合為泛奧爾塔聯盟後繼續任常駐見習參事，之後被委任為泛奧爾塔聯盟常駐地球觀察特派專員（實際上就是墾荒監視團），代表泛奧爾塔聯盟對地球的行為進行監視及必要管制，同時對該星球生命體進行分析調查，首次到達地球是地球儒略歷的1872年。

[ayame9joe](https://github.com/ayame9joe)

* 網名　　　　9節菖蒲
* 英文名　　　
* 職業　　　　遊戲設計師
* 研究方向　　遊戲敘事、遊戲情感體驗
* 電子郵箱　　ayame9joe@gmail.com
* 個人網站　　http://playfulthoughts.com/ayame9joe
* 簡歷　　　　

術語範圍
========

包括但不限於軟件設計、電子遊戲等領域裡出現的術語。

過長的通用句式，例如：「..., but otherwise something would be ignored」暫不考慮。

適用場合
========

建議在**正式出版物**（包含原創與譯作）及**面向大衆的通識文章**（包含新聞稿、大衆博文等）中使用。

口頭交流及過於專業的技術文檔暫且不在本項目討論範圍內。

考評標準
========

1. **確真性**（verity）。以正確為先。
  * 例如做遊戲名稱的《The Last of Us》,不宜翻譯為《美國末日》。
2. **協調性**（consistency）。由同一中心概念與其它概念搭配而成的一組詞語，應保持譯名一致。
  * 例如download如果譯為「下載」，那麼upload就應譯為「上載」；download如果譯為「下傳」，那麼upload就應譯為「上傳」。
3. **區隔性**（unambiguity）。即能夠與相關的其它專業概念區隔開。
  * 例如為了與typeface（字體）及glyph（字形）相區隔，font應該譯為「字型」。
  * 再如program與procedure，都是「程序」，如何區隔？
4. **同構性**（isomorphism）。概念相近或遞進的一組術語，其中文譯法的結構也要相仿。
  * 例如bit、byte、word三詞在頻繁出現時，建議譯為「位元」、「字節」、「字組」。三者均爲偏正式構詞法，且均爲兩個字。另外，從「元」到「節」再到「組」，有鮮明的遞進關係，符合「協調性」原則，同時又能與「位置」、「數位」等詞相區隔，還符合「區隔性」原則。
5. **對應性**（correspondence）。譯文語法結構應和原文儘量相似，不宜隨便增減字詞。
  * 例如「retain cycle」是偏正式名詞短語，中心詞是「cycle」，而現存中文譯法「循環引用」的中心詞卻是「引用」，原文的「retain」（保留）不見了，多出來了「引用」二字。
6. **對等性**（parity）。兩個相似但有微妙區別的英文術語，應分別有對等的中文術語。
  * 例如「circular reference」與「循環引用」對等，而「retain cycle」則與「保留環」對等。不宜「拉郎配」，也就是說，不宜將「retain cycle」與「循環引用」視為對等。

註：對各原則所舉的例子由jeffreybaoshenlee撰寫，不代表他人意見。（翔按：其中對第五、第六兩原則所舉的範例與大家的普遍認知不同，對此我深表抱歉，敬請大家原諒。目前依然堅持自己的看法，稍後也可能會修改。）

詞條格式
========

**「英文」**和**「本社區建議譯法」**為必填項，其餘選填：

##單詞或短語

* 英文　　　　　　　（**單詞或短語**）
* 語境　　　　　　　（填寫「技術文章」、「遊戲名稱」、「GUI編程」、「操作系統設計」等等）（翔按：由於同一術語在不同語境下意義可能不同，所以可能需要分成多個條目來寫。例如在「HTML5」語境下，context一詞應該怎麼翻譯，在「Python 3.x 編程」語境下，context一詞又應該怎麼翻譯……）
* 常見譯法　　　　　（可給出多種常見譯法）
* 其它譯法　　　　　（可給出多種其它譯法）
* 本社區建議譯法　　（**建議的譯法**）
* 提議人　　　　　　（原則上填寫提議人的ID）
* 示例
  * 例句　　　　　　（英文原句）（翔按：例句不一定非要取到句點為止，也可以只取其中一部分。）
  * 譯文　　　　　　（翻譯後的中文句子）
  * 出處　　　　　　（哪本書，第幾章，第幾節，第幾頁，第幾行；或哪篇文章第幾段，第幾行）
* 舉證與考辨　　　　（提議人可以陳述下列內容：）
  * 為何覺得自己所提的譯法比常見譯法或其它譯法更優秀？
  * 有何證據（如文章、論文、書籍、百科全書中的條目等）能證明這一點？
  * 從語言學角度講，所提的譯法有何來歷？有何優點？
  * 它如何能把當前這一術語同其它含義相近的術語區隔開？
* 反對意見　　　　　（提議人所提譯法遭到哪些人的反對，為什麼反對？）
* 提議人答辯　　　　（提議人對於反對意見有何辯駁？）

註：還可以有第二輪反對與第二輪答辯，其後依此類推。

行為準則
========

* 請勿討論本項目範圍之外的話題
* 請勿在討論中進行人身攻擊

授權方式
========

本項目所有內容均以Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)協議授權，具體文本錄於 http://creativecommons.org/licenses/by-nc-nd/4.0/
