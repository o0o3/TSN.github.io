


<!DOCTYPE html>
<html xmlns='http://www.w3.org/1999/xhtml'>
  <head>
    <meta http-equiv="X-UA-Compatible" content="IE=Edge"/>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
    <title>TSN</title>
    <style type="text/css">
      body { -ms-touch-action: none; }
    </style>
    <script type="text/javascript" src="tsn.114/files/TSN.js"></script>
    <script type="text/javascript">
      var TSN;

      function initKeyShotXR() {
        var nameOfDiv = "TSN";
        var folderName = "tsn.114";
        var viewPortWidth = 801;
        var viewPortHeight = 558;
        var backgroundColor = "#FFFFFF";
        var uCount = 18;
        var vCount = 9;
        var uWrap = true;
        var vWrap = false;
        var uMouseSensitivity = -0.05;
        var vMouseSensitivity = 0.05625;
        var uStartIndex = 9;
        var vStartIndex = 5;
        var minZoom = 1;
        var maxZoom = 1;
        var rotationDamping = 0.96;
        var downScaleToBrowser = true;
        var addDownScaleGUIButton = false;
        var downloadOnInteraction = false;
        var imageExtension = "png";
        var showLoading = true;
		var loadingIcon = "logo.png"; // Set to empty string for default icon.
        var allowFullscreen = true; // Double-click in desktop browsers for fullscreen.
        var uReverse = false;
        var vReverse = false;
        var hotspots = {};
        var isIBooksWidget = false;
        
        TSN = new TSN(nameOfDiv,folderName,viewPortWidth,viewPortHeight,backgroundColor,uCount,vCount,uWrap,vWrap,uMouseSensitivity,vMouseSensitivity,uStartIndex,vStartIndex,minZoom,maxZoom,rotationDamping,downScaleToBrowser,addDownScaleGUIButton,downloadOnInteraction,imageExtension,showLoading,loadingIcon,allowFullscreen,uReverse,vReverse,hotspots,isIBooksWidget);
      }

      window.onload = initKeyShotXR;
    </script>
  </head>
  <body oncontextmenu="return false;">
    <div id="TSN"></div>
  </body>
</html>
