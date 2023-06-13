<!DOCTYPE html>
<html lang="en-us">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <title>Unity WebGL Player | Demiurge Alpha</title>
    <link rel="shortcut icon" href="TemplateData/favicon.ico">
    <link rel="stylesheet" href="TemplateData/style.css">
    <script src="TemplateData/UnityProgress.js"></script>
    <script src="Build/UnityLoader.js"></script>
    <script>
      var unityInstance = UnityLoader.instantiate("unityContainer", "Build/ultimate2d webbuild.json", {onProgress: UnityProgress});
    </script>
  </head>
  <body>
  <h2>2D Top-Down Action Game</h2>
	<h3>Major Features</h3>
	Ability system
	<p>Hit enemies to fill up the charge meter. When the icon lights up, press spacebar to use the ability.</p>
	<iframe src="https://giphy.com/embed/FVmd1KWe56W2fJVR2r" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/FVmd1KWe56W2fJVR2r"></a></p>

	Win screen:
	<iframe src="https://giphy.com/embed/JVs4wZt8cRZrFEWKsp" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/JVs4wZt8cRZrFEWKsp"></a></p>
	<p>Make it to the end of the dungeon and defeat all enemies in the fastest time!</p>
    <div class="webgl-content">
      <div id="unityContainer" style="width: 960px; height: 600px"></div>
      <div class="footer">
        <div class="webgl-logo"></div>
        <div class="fullscreen" onclick="unityInstance.SetFullscreen(1)"></div>
        <div class="title">Demiurge Alpha</div>
      </div>
    </div>
  </body>
</html>


