<!doctype html>
<html>
 <head>
  <meta charset="UTF-8">
  <title>image sample</title>
  <script src=https://unpkg.com/vue@next></script>
 </head>

 <body>
  <button onclick="doBtn()">画像を表示</button>
   <div id="app">
    <img v-bind:src="imagename"></img>
   </div>

   <script>
    new Vue({
        el:'#app',
        date:{
            imagename:'sample.jpg'
        }   
    })
    </script>
  </body>
 </html>   