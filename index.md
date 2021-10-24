<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<link rel="preconnect" href="https://fonts.gstatic.com/">
<link href="./liamnash.github.io_files/css2" rel="stylesheet">

<style>

	a:link {color: black; 		text-decoration: none;}
    a:visited {color: black;}
    a:hover {color: #4a4a4a;}
    a:active {color: black;}    /* selected link */
	
h1 {
		font-size: 150;
		font-family: 'Dosis', sans-serif;
		text-align: center;
	}
p {
		font-family: 'Roboto', sans-serif;
		text-align: center
	}
div {
		font-size: 21;
		font-family: 'Roboto', sans-serif;
		text-align: center;
	}
		
</style>
</head>
<body>

<!-- pls stop looking at my crappy code TIMOTHY. I stole the countdown timer from w3schools and repurposed a portfolio website I made ages ago OKAY. there are no more passwords here!-->


<div>&nbsp;</div>


<h1 id="countdown"></h1>

<p class="sub">you will recieve a message. the time loop will be fixed.</p><script>
var countDownDate = new Date("Oct 24, 2021 20:07:25").getTime();

var x = setInterval(function() {

  var now = new Date().getTime();
    
  var distance = countDownDate - now;
    
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);
    
  document.getElementById("countdown").innerHTML = hours + "h "
  + minutes + "m " + seconds + "s ";
    
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("countdown").innerHTML = "EXPIRED";
  }
}, 1000);
</script><div>&nbsp;</div>

<div>&nbsp;</div>
<div>&nbsp;</div>
<div>&nbsp;</div>

<div>&nbsp;</div><div>&nbsp;</div><div>&nbsp;</div><div>&nbsp;</div><div>&nbsp;</div><div>&nbsp;</div><div>&nbsp;</div><div>&nbsp;</div><div>&nbsp;</div><div>&nbsp;</div><div>&nbsp;</div>
<div>&nbsp;</div>
<p>copyright</p>
<p style="margin-top: -15px;">block facts</p>



</body></html>
