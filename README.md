# __Loading Effect__
這是一個的Loading視覺效果，使用了CSS來實現。當使用者在等待網頁載入或資料處理時，這個Loading效果可以提供一個等待提示，此效果包含一個旋轉的圓圈、進度條效果，帶有科技感的Loading效果。

## __代碼介紹__
在HTML代碼中，我們可以看到一個class為"loading"的div，其中包含三個子div，分別是class為"loading__circle"、"loading__text"、"loading__bar"的元素。這些元素可以通過CSS進行樣式設置，以創建漂亮的效果。

在CSS代碼中，我們可以看到對於整個網頁的樣式設置，包括背景顏色、邊距和填充。"loading"元素的樣式設置包括居中顯示和高度設置為整個視口高度。"__loading__circle"元素使用了border和box-shadow屬性來創建圓形邊框和陰影效果。"loading__text"元素設置了文字的樣式和位置。"loading__bar__"元素創建了一個進度條，其中:before為元素定義了一個藍色的圓形，它可以根據進度條的寬度移動。

最後，CSS代碼中的兩個關鍵幀（@keyframes）創建了動畫效果。"rotate"關鍵幀定義了loading__circle元素的旋轉動畫，使其繞著中心旋轉。"progress"關鍵幀定義了loading__bar元素的進度條動畫，讓圓形:before偽元素在進度條上移動。

## __開發者__
- fantasywings123 
