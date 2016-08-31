# PanoramaPlayer.js
Make Panorama Video Lighter

###Usage

①、引入 Three.min.js 和 PanoramaPlayer.min.js。

    <script src="Three.min.js"></script>
    <script src="PanoramaPlayer.min.js"></script>


②、new 一个 Panorama对象，传入全景视频的video Dom元素和宽高。

    var player = new PanoramaPlayer({
      video: document.getElementById("video"),
      videoWidth: 900,
      videoHeight: 506
    });

![](http://i2.buimg.com/567571/8c21b51a3f15c182.gif)

![](http://i2.buimg.com/567571/4d0f8aeb733a3c01.png)
