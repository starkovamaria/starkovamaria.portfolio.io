# starkovamaria.portfolio.io
<!--
  KeyShotXR
  (c) Copyright 2012-2017 Luxion ApS - All Rights Reserved.
-->
<html>
<body>
<h1>return 360</h1>
</body>
</html>
<html xmlns='http://www.w3.org/1999/xhtml'>
  <head>
    <meta http-equiv="X-UA-Compatible" content="IE=Edge"/>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
    <title>KeyShotXR</title>
    <style type="text/css">
      body { -ms-touch-action: none; }
    </style>
    <script type="text/javascript" src="tungsten extruder.63/files/KeyShotXR.js"></script>
    <script type="text/javascript">
      var keyshotXR;

      function initKeyShotXR() {
        var nameOfDiv = "KeyShotXR";
        var folderName = "tungsten extruder.63";
        var viewPortWidth = 784;
        var viewPortHeight = 588;
        var backgroundColor = "#FFFFFF";
        var uCount = 20;
        var vCount = 1;
        var uWrap = true;
        var vWrap = false;
        var uMouseSensitivity = -0.0555556;
        var vMouseSensitivity = 1;
        var uStartIndex = 10;
        var vStartIndex = 0;
        var minZoom = 1;
        var maxZoom = 2;
        var rotationDamping = 0.96;
        var downScaleToBrowser = true;
        var addDownScaleGUIButton = false;
        var downloadOnInteraction = false;
        var imageExtension = "png";
        var showLoading = true;
        var loadingIcon = "ks_logo.png"; // Set to empty string for default icon.
        var allowFullscreen = true; // Double-click in desktop browsers for fullscreen.
        var uReverse = false;
        var vReverse = false;
        var hotspots = {};
        var isIBooksWidget = false;
        
        keyshotXR = new keyshotXR(nameOfDiv,folderName,viewPortWidth,viewPortHeight,backgroundColor,uCount,vCount,uWrap,vWrap,uMouseSensitivity,vMouseSensitivity,uStartIndex,vStartIndex,minZoom,maxZoom,rotationDamping,downScaleToBrowser,addDownScaleGUIButton,downloadOnInteraction,imageExtension,showLoading,loadingIcon,allowFullscreen,uReverse,vReverse,hotspots,isIBooksWidget);
      }

      window.onload = initKeyShotXR;
    </script>
  </head>
  <body oncontextmenu="return false;">
    <div id="KeyShotXR"></div>
  </body>
</html>
