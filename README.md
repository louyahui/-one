<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title>个人博客测试</title>
    <style>
        #cube-con {
        width: 200px;
        height: 200px;
        position: relative;
        perspective: 1000px;
    }
    #cube {
        width: 100%;
        height: 100%;
        position: absolute;
        transform-style: preserve-3d;
    }
         #cube .front  { transform: rotateY(   0deg ) translateZ( 100px ); }
        #cube .back   { transform: rotateX( 180deg ) translateZ( 100px ); }
        #cube .right  { transform: rotateY(  90deg ) translateZ( 100px ); }
        #cube .left   { transform: rotateY( -90deg ) translateZ( 100px ); }
        #cube .top    { transform: rotateX(  90deg ) translateZ( 100px ); }
        #cube .bottom { transform: rotateX( -90deg ) translateZ( 100px ); }


    </style>
	</head>
	<body>
   <section id="cube-con">
      <div id="cube">
        <figure class="front">1</figure>
        <figure class="back">2</figure>
        <figure class="right">3</figure>
        <figure class="left">4</figure>
        <figure class="top">5</figure>
        <figure class="bottom">6</figure>
      </div>
    </section>
	</body>
</html>
