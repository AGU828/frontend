網頁設計

## 文字的顏色
1. 使用RGB
 - 16 進制 #RRGGBB (#00 - #FF) 
      例：#FF0000 純紅色
- 10 進制
      例：rgb(0,255,0) 純綠色
- 百分比
      例：rgb(0%,0%,255%) 純藍色
      
2. 使用RGBA
- rgba(255,0,0,0.5)半透明紅
- rgba(100%,0%,0%, .5)


3.使用HSL
'HSL'即色相、飽和度、亮度（英語：Hue, Saturation, Lightness）。HSV即色相、飽和度、明度（英語：Hue, Saturation, Value），又稱HSB，其中B即英語：Brightness。

- 色相：如紅色:0度、綠色:120度、藍色：240度
- 飽和度(s)是指色彩的純度，越高色彩越純，低則逐漸變灰，取0-100%
  無色：0%,純色：100%
- 亮度：取0-100%,黑色：0% 白色：100%,純色：50% 
  
HSL
4. 使用HSLA
5. 使用英文單字

---

## 文字的對齊
屬性：text align
 - left/
 - right/
 - center/
 - justify

## 文字的裝飾
屬性：text decoration
 - underline 底線
 - overline 上方線
 - line-throught 穿越線
 - none         取消裝飾線

## 文字的字體
屬性：font-family
- 英文字體
  sans-serif(非襯線字),serif(襯線字),arial,tahoma,helvetica,

- 中文字體
  微軟正黑體．

- 網路字體
  - [google fonts](https://fonts.google.com) 
  - [typekit](https://fonts.adobe.com/?ref=tk.com)
  - [fontsquirrel](https://www.fontsquirrel.com)
  - [justfont](https://justfont.com)
  - [文頂雲字庫](https://www.ifontcloud.com/index/index.jsp)
  - [華康威](https://dfo.dynacw.com.tw)

- 嵌入字體
  支援的檔案格式：
 - .woff ()
 - .ttf ()
 - .otf ()


- 字型大小
  樣式名稱： `font-size` 
 - 預設大小: `16px`
 - 值可以分兩大類
  1. 絕對單位： 16px
  2. 相對單位：
     - em `1em 表示 1*16px`
     - rem `1rem = 1em = 1*16px`
     - 100% 
- `em`與`rem`的差異？
 - `em`單位，參考的是父元素的字體大小。
 - `rem`單位參考的是root元素的字體大小。

## 文字的樣式

樣式名稱:`font-style`
ex:`font-style:italic`

## 文字的間距
字體與字體間的距離
- letter-spacing
  指的是文字與文字之間的距離，對中英文皆有用。
- word-spacing
  指的是單字與單字之間的距離，只對英文有用。

- 結論：
  中文字體之間的間距可以使用：letter-spacing來設定。
  英文字體之間的間距可以使用：letter-spacing與word-spacing來設定。

## 行高的設定

樣式名稱：line-height
例：line-height:10px;

## 背景處理
