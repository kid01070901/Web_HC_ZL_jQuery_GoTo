# Web_HC_ZL_jQuery_GoTo
網頁 赫綵 中壢 jQuery 前往元素位置

# Web_HC_ZL_jQuery_GoTo
網頁 赫綵 中壢 jQuery 前往元素位置
# 範例網站
 https://kid01070901.github.io/Web_HC_ZL_jQuery_GoTo/
# CDN
放在 body 結束元素的上方，必須按造下方的順序
```
<!-- jQuery CDN -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<!-- 前往元素 js -->
<script src="https://github.com/kid01070901/Web_HC_ZL_jQuery_GoTo/blob/main/goTo.js"></script>
```

# 添加 ID
在要前往的元素上添加 ID

```
<section id="box1"></section>
```

# 屬性說明
屬性名稱            |屬性說明
--------------------|-----------------------------
data-gt-target      |要前往的目標元素，必須使用 ID
data-gt-duration    |持續時間，單位為毫秒
data-gt-offset      |位移，往上位移的值