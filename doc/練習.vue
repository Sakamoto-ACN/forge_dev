<!doctype html>
<html>
 <head>
  <meta charset="UTF-8">
  <title>image sample</title>
  <script src=https://unpkg.com/vue@3/dist/vue.global.js></script>
 </head>

 <body>
  <h2>画像を表示</h2>
   <div id="app">
    <img v-bind:src="imagename">練習</img>
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