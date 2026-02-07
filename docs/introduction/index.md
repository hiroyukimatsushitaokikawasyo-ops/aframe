<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>スイミー・ビュー：いせえびの場面</title>
    <script src="https://aframe.io/releases/1.4.0/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-assets>
        <img id="iseebi-image" src="ここにコピーしたURLを貼り付け">
      </a-assets>

      <a-sky src="#iseebi-image" rotation="0 -90 0"></a-sky>

      <a-entity 
        text="value: すいちゅうブルドーザーみたいな　いせえび……; align: center; color: white; width: 5; font: https://raw.githubusercontent.com/etiennepinchon/aframe-fonts/master/fonts/notosansjp/NotoSansJP-Bold.json; shader: msdf" 
        position="-2 1.8 -4">
      </a-entity>

      <a-entity 
        text="value: おもしろいものが　いっぱいだ！; align: center; color: #FFCC00; width: 4; font: https://raw.githubusercontent.com/etiennepinchon/aframe-fonts/master/fonts/notosansjp/NotoSansJP-Bold.json; shader: msdf" 
        position="4 1.5 -3">
      </a-entity>

      <a-camera>
        <a-cursor color="red"></a-cursor>
      </a-camera>
    </a-scene>
  </body>
</html>
