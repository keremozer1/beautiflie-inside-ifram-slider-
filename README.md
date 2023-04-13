# beautiflie-inside-iframe-slider-


<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>haber sitesi</title>
	<style type="text/css">
		#sliderust{width: 1060px; height: 600px; border: 1px solid #A4A4A4;}
	#slideralt{ width:1060px; height:49px; border: 1px solid #A4A4A4; border-top: 0px;background-color: #1CE882; overflow: hidden; }
		ul{list-style: none; margin: 0; padding: 0;}
		li{display: block; width: 50px; height: 50px; font: 20px bold normal; float: left; line-height: 50px; text-align: center; color: #151515; cursor: pointer;}
		li:hover{background:#626262;}
		#slideraltdiv{height: 50px; width: 500px; margin: 0 auto;}
	</style>
	<script type="text/javascript">
	
		var zaman;
var resimler = new Array("url(sliderresimler/1.resim)", "url(sliderresimler/2.resim)", "url(sliderresimler/3.resim)", "url(sliderresimler/4.resim)", "url(sliderresimler/1.resim)","url(sliderresimler/1.resim)","url(sliderresimler/1.resim)","url(sliderresimler/1.resim)");
		function degis(x)
{
	window.clearInterval(zaman);
	for(var i=1;i<=10;i++)
	  {
		if(x==i)
		{document.getElementById("sayi"+i).style.background="red";
		document.getElementById("sliderust").style.background=resimler[6];
		}
	  }
		
	</script>
	
	</head>

<body onLoad="basla()">
	<div id="sliderust"></div>
	<div id="slideralt">
		<div id="slideraltdiv">
	<ul id="list" >
	    <li id="sayi1" onMouseOver="degis(1)">1</li>
		<li id="sayi2" onMouseOver="degis(2)">2</li>
		<li id="sayi3" onMouseOver="degis(3)">3</li>
		<li id="sayi4" onMouseOver="degis(4)">4</li>
		<li id="sayi5" onMouseOver="degis(5)">5</li>
		<li id="sayi6" onMouseOver="degis(6)">6</li>
		<li id="sayi7" onMouseOver="degis(7)">7</li>
		<li id="sayi8" onMouseOver="degis(8)">8</li>
		<li id="sayi9" onMouseOver="degis(9)">9</li>
		<li id="sayi10" onMouseOver="degis(10)">10</li>
	</ul>
	    </div>
	</div>
	
</body>
</html>
