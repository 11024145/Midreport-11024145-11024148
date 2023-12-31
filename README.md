# 類圖與關聯圖
11024145 黃品翔 
11024148 張進豐
# UML基本概念
UML，全稱Unified Modeling Language，統一建模語言。而UML圖分為用例圖、類圖、物件圖、狀態圖、活動圖、時序圖、協作圖、構件圖、部署圖等9種圖。

# 類圖中六種關係及符號
UML類圖中有六種關係，分別是依賴關係，關聯關係，聚合關係，組合關係，實現關係，泛化關係。

六種關係的示例圖。類的成員變數和方法前面的修飾符有public, private, protected, default，在UML類圖中分別用 +, -, #, ~表示。

# 一、依賴關係
依賴關係是一種使用關係，表示某個類依賴於另外一個類，通常表現為，某個類的方法的參數使用了另外一個類的對象。

在UML類圖中，依賴關係用帶箭頭的虛線表示，箭頭從使用類指向被依賴的類。下圖中表示，程序員依賴于電腦來編寫代碼。

![img](https://github.com/11024145/Midreport-11024145-11024148/blob/main/1.jpg)


# 二、關聯關係

關聯關係是物件之間的一種引用關係，表示一個類和另外一個類之間的聯繫，如老師和學生，丈夫和妻子等。

關聯關係有單向和雙向的。在UML類圖中，單向關聯用一個帶箭頭的實線表示，箭頭從使用類指向被關聯的類，雙向關聯用帶箭頭或者沒有箭頭的實線來表示。

![img](https://github.com/11024145/Midreport-11024145-11024148/blob/main/2.jpg)

# 三、聚合關係

聚合關係是關聯關係的一種，表示整體和部分之間的關係，如學校和老師，車子和輪胎。

聚合關係在類中是通過成員物件來體現的，成員是整體的一部分，成員也可以脫離整體而存在。如老師是學校的一部分，同時老師也是獨立的個體，可以單獨存在。

在UML類圖中，用帶空心菱形的實線來表示聚合關係，菱形指向整體。
![img](https://github.com/11024145/Midreport-11024145-11024148/blob/main/3.jpg)
# 四、組合關係

組合關係是整體和部分之間的關係，也是關聯關係的一種，是一種比聚合關係還要強的關係。部分物件不能脫離整體物件而單獨存在，如人的身體和大腦之間的關係，大腦不能脫離身體而單獨存在。

在UML類圖中，用帶實心菱形的實線來表示組合關係，菱形指向整體。

![img](https://github.com/11024145/Midreport-11024145-11024148/blob/main/4.jpg)
# 五、實現關係

實現關係就是介面和實現類之間的關係。類實現了介面中的抽象方法。

在UML類圖中，用帶空心三角箭頭的虛線來表示實現關係，箭頭從實現類指向介面。

![img](https://github.com/11024145/Midreport-11024145-11024148/blob/main/5.jpg)

# 六、泛化關係

泛化關係其實就是父子類之間的繼承關係，表示一般與特殊的關係，指定子類如何特殊化父類的特徵和行為。

在UML類圖中，用帶空心三角箭頭的實線來表示泛化關係，箭頭從子類指向父類。

![img](https://github.com/11024145/Midreport-11024145-11024148/blob/main/6.jpg)

如上圖，父類動物有一個吃的方法，小鳥和獅子都繼承於動物類，小鳥有它特有的方法飛行，而獅子有特有的方法奔跑。

六種關係中，從弱到強依次是：
依賴關係 < 關聯關係 < 聚合關係 < 組合關係 < 實現關係 = 泛化關係

# 參考資料

https://segmentfault.com/a/1190000021317534

# UML設計圖原檔

https://drive.google.com/file/d/171SLozwgdrN-8Amfwf8lyFvwQSey9589/view?usp=sharing
