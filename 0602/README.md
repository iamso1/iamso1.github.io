# 6/2 小筆記

## 腳手架

https://gist.githubusercontent.com/maylogger/62cb9bd1fbe44ae822fd1f689ea6ebb6/raw/8c4324d1212610863390644eaf50c8b37d9b0cc0/content.txt

## vscode 小技巧

- option + z 可以折行
- option + 點段落 可以同時有多個游標

## css 觀念

- css 樣式後蓋前，像是貼標籤，越後面貼的越上面
- margin 是會重疊的; border 是皮膚; padding 就像內部脂肪厚度; margin 是跟外界的距離
- margin, padding 順序是順時針, 上右下左; 也可以寫縮寫，少寫會複製對面的。只寫一個就全部複製。
- css 直接用 tag 很危險，所以可以用 class 前面一定要有點
- width 如果用 ch 可以維持字數, 透過 max-width 搭配使用可以做到 rwd 效果
- width: 100% 無論內容多小，元素都會撐滿整個 container。 缺點：會導致內容放大，甚至失真 max-width: 100% 如果內容比容器寬，則縮小內容；如果內容本來就比較小，不會強制放大。 常用在圖片，可以避免圖片超出範圍。

## 其他資源

- 配色調色盤 https://ui.shadcn.com/colors，選定一行配色後，盡量都用同一行
- https://www.htmldog.com 學習資源

## 美學觀念

- 一行英文不超過 5、65 個字，所以使用 width 去限制每行可以呈現的文字數量，可以先使用 div 包起來再設定
