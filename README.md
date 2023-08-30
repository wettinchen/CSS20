## Chapter 20: Variables
It is my coding practice with the TUTORIAL of Dave Gray. 

## Source
### Dave Gray 的 CSS 資源
https://github.com/gitdagray/css_course

### Dave Gray 的 CSS 課程
https://youtube.com/playlist?list=PL0Zuz27SZ-6Mx9fd9elt80G1bPcySmWit

### Dave Gray 的 YouTube 頻道
https://www.youtube.com/@DaveGrayTeachesCode

## Quick Concept outline
###  1. Intro
        教學影片固定的開頭

###  2. Welcome
        歡迎觀眾，說明工具與資料位置

###  3. Why use CSS variables?
        說明使用 CSS 變數的原因

###  4. Starter Code
        初始設定說明

###  5. :root pseudo-class
        設定 :root，背景顏色 --BGCOLOR 為 #475569，並套用 --BGCOLOR 作為變數。

###  6. Apply colors with CSS variables
        (1)新增 --ALT-BGCOLOR 為 #1e293b，並套用至 header, footer 的 background-color。並修改 nav 的背景顏色為白煙色。
        (2)新增 --RADIAL-COLOR 和--LIGHT-COLOR 為 whitesmoke，將 background-image 漸層的白煙色套用 --RADIAL-COLOR。將 header, footer 的文字顏色和 nav 的 background-color 套用 --LIGHT-COLOR。
        (3)新增 --DARK-COLOR 為 #000，將 #000 修改為 var(--DARK-COLOR)

###  7. Apply font styles with CSS variables
        (1)設定 :root，fontfamily字型家族 --FF 為 "Nunito", sans-serif，並套用 --FF 作為變數。
        (2)新增 font-size字體大小 --FS 為 1.5rem，--FS-XL 為 3rem，並套用變數。

###  8. Nesting CSS variables
        (1)新增 :root，--PADDING 為 0.5rem，並套用變數。
        (2)設定 nav 中，box-shadow 為 0 6px 5px -5px var(--DARK-COLOR)
        (3)新增 --SHADOW 為 0 6px 5px -5px var(--DARK-COLOR)，並套用變數。
        (4)新增 --BORDERS 為 2px solid var(--DARK-COLOR)，並套用變數。

###  9. Adding more HTML content
        將 main 元素清空新增 12 個 div，
        class 為 square，並稍作修改。

### 10. Styling the main element
        (1)移除 main 的 css 切版樣式
        (2)設定 display 為 flex，justify-content 為 space-evenly，align-items 為 center
        (3)設定 flex-flow 為 row wrap，gap 為 min(4vw, 15px)，padding 為 10px 0

### 11. Order of operations

### 12. Styling the content with CSS variables
        (1)新增 :root，--SQUARE-BGCOLOR 為 papayawhip，----SQUARE-SIZE 為 max(150px, 20vw)。
        (2)設定 .square 的背景顏色、寬度、高度、border、border-radius 為 15px，display 為 grid，place-content 為 center
        (3)設定字體大小為 var(--FS-XL)
        (4)設定 box-shadow 為 var(--SHADOW)

### 13. Redefining CSS variables
        重新定義 .square--highlight 的 --SQUARE-BGCOLOR 為 cornflowerblue

### 14. Create and apply a Dark Mode
        使用 media query 修改深色模式。
        (1)修改 --BGCOLOR 為 #000，--ALT-BGCOLOR 為 #333，--RADIAL-COLOR 為 rgb(217, 217, 217)，--SQUARE-BGCOLOR 為 rgb(202, 174, 202)
        (2)修改深色模式為淺色模式

