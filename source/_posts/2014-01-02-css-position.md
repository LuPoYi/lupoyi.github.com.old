---
layout: post
title: '[CSS] 定位'
date: 2014-01-02 02:43
comments: true
categories: [css]
---
以前都是直接用現成的，或是抓別人的css來用
一堆語法都知道是幹麻的，但自己寫的時候就完全不行
尤其是layout的配置..明明感覺很簡單的卻要一直亂試喬半天...

趁著最近面試的機會來記一下CSS.... ~~不然平常都很懶得學~~

## Position
``` css position, 依top, left, right, bottom調整位置
position: absloute /* 絕對位置 */
position: relative /* 相對位置，以該元件所屬的左上角做基準點，移動位置仍會佔有原先位置的空間 */
position: fixed    /* 固定位置，定在視窗上 */
  
/* 當相對位置包住絕對位置時，絕對位置所基準就會為相對位置 */
```
## z-index
z-index 元件重疊時，值愈大，顯示愈上面


## overflow
``` css 控制轉軸
overflow: visible /* 內容完整呈現 */
overflow: hidden  /* 只顯示放得下的內容 */
overflow: scroll  /* 強制加右方下方捲軸 */
overflow: auto    /* 內容放不下時，加右方捲軸 */
```




Reference: 
http://my-web-design.blogspot.tw/2007/10/css-divposition.html
http://www.1keydata.com/css-tutorial/tw/position.php