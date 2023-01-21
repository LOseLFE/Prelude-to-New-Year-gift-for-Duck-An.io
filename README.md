# Prelude-to-New-Year-gift-for-Duck-An.io
<!DOCTYPE HTML>
<html>
<head>
	<title>Nice to meet you!</title>
	<meta http-equiv="content-type" content="text/html; charset=UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
	<style type="text/css">
		@font-face {
			font-family: digit;
			src: url('digital.ttf') format("truetype");
		}
	</style>
	<link href="css/default.css" type="text/css" rel="stylesheet">
	<script type="text/javascript" src="js/jquery.js"></script>
	<script type="text/javascript" src="js/garden.js"></script>
	<script type="text/javascript" src="js/functions.js"></script>
</head>

<body>
<div id="mainDiv">
	<div id="content">
		<div id="code">
			<span class="comments">##</span><br/>
			<span class="comments"># We learnt Python together</span><br/>
			<span class="comments"># so I write code to celebrate New Year in coder's way.</span><br/>
			<span class="comments">##</span><br/>
			i = Boy(<span class="string">"Hu Jie kai"</span>);<br/>
			u = Girl(<span class="string">"Dai Ke an"</span>);<br/>
			<span class="comments"># Aug 15, 2021,military training should be our first encounter. </span><br/>
			i.met(u)<br/>
			<span class="comments"># Barely we communicated until the assignments for technical subjects lighting up the world.</span><br/>
			began_chat(u,i)<br/>
			<span class="comments"># I'v enjoy the time during the epidemic online class cause you watched First Love with me.</span><br/>
			delighted(u,i)<br/>
			<span class="comments"># We immersed in Cloud Music together.</span><br/>
			listening(u,i)<br/>
			<span class="comments"># Dec 24, 2022,I witnessed an immaculate Christmas tree I've ever seen, but unfortunately messed up mine.</span><br/>
			i.overhead(u)<br/>
			<span class="comments"># Afterwards, I confessed to you. </span><br/>
			i.confess(u)<br/>
			<span class="comments"># As a result,you turned me down, but it was exactly a best choice.</span><br/>
			u.reject(i)<br/>
			<span class="comments"># We prepared arduously for Academic Level Examination and final exams.</span><br/>
			study(u, i)<br/>
			<span class="comments"># Moreover,when Ms. Wang praised you, I felt sincerely pleased from the bottom of my heart as if you are my daughter who were the only one deserved the title of Civilized Scholar.</span><br/>
			i.proud(u)<br/>
			<span class="comments"># Wish you a happy and prosperous new year!</span><br/>
			i.wish(u)<br/>
			<span class="comments"># You filled the world with +∞-bit colors in my eyes.</span><br/>
			while <span class="keyword">True</span>:<br/>
			<span class="placeholder"></span><span class="keyword">if</span> i.with(u):<br/>
			<span class="placeholder"></span><span class="placeholder"></span>life+=1<br/>
			<span class="placeholder"></span><span class="keyword">else</span>:<br/>
			<span class="placeholder"></span><span class="placeholder"></span>life-=1<br/>
			
		</div>
		<div id="loveHeart">
			<canvas id="garden"></canvas>
			<div id="words">
				<div id="messages">
					Duck An, I'v met you for:
					<div id="elapseClock"></div>
				</div>
				<div id="loveu">
					I will haunt you forever and ever.<br/>
					<div class="signature">Hu JK|2023.1.21 </div>
				</div>
			</div>
		</div>
	</div>
	<div id="copyright">
		A Tip for your New Year's gift:<a href='https://pan.baidu.com/s/1jxksJPNETLGlERlYQf4h-Q?pwd=2333'> A song!</a>
	</div>
</div>
<script type="text/javascript">
	var offsetX = $("#loveHeart").width() / 2;
	var offsetY = $("#loveHeart").height() / 2 - 55;
	var together = new Date();
	together.setFullYear(2021, 7, 15);
	together.setHours(9);
	together.setMinutes(0);
	together.setSeconds(0);
	together.setMilliseconds(0);

	if (!document.createElement('canvas').getContext) {
		var msg = document.createElement("div");
		msg.id = "errorMsg";
		msg.innerHTML = "Your browser doesn't support HTML5!<br/>Recommend use Chrome 14+/IE 9+/Firefox 7+/Safari 4+";
		document.body.appendChild(msg);
		$("#code").css("display", "none")
		$("#copyright").css("position", "absolute");
		$("#copyright").css("bottom", "10px");
		document.execCommand("stop");
	} else {
		setTimeout(function () {
			startHeartAnimation();
		}, 5000);

		timeElapse(together);
		setInterval(function () {
			timeElapse(together);
		}, 500);

		adjustCodePosition();
		$("#code").typewriter();
	}
</script>
</body>
</html>
