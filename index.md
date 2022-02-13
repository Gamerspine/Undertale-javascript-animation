<html>
  <head>
    <meta charset="UTF-8">
    <title>UNDERTALE</title>
	 <!--favicon*-->
	<link rel="apple-touch-icon" sizes="57x57" href="img/favicon/apple-icon-57x57.png">
	<link rel="apple-touch-icon" sizes="60x60" href="img/favicon/apple-icon-60x60.png">
	<link rel="apple-touch-icon" sizes="72x72" href="img/favicon/apple-icon-72x72.png">
	<link rel="apple-touch-icon" sizes="76x76" href="img/favicon/apple-icon-76x76.png">
	<link rel="apple-touch-icon" sizes="114x114" href="img/favicon/apple-icon-114x114.png">
	<link rel="apple-touch-icon" sizes="120x120" href="img/favicon/apple-icon-120x120.png">
	<link rel="apple-touch-icon" sizes="144x144" href="img/favicon/apple-icon-144x144.png">
	<link rel="apple-touch-icon" sizes="152x152" href="img/favicon/apple-icon-152x152.png">
	<link rel="apple-touch-icon" sizes="180x180" href="img/favicon/apple-icon-180x180.png">
	<link rel="icon" type="image/png" sizes="192x192"  href="img/favicon/android-icon-192x192.png">
	<link rel="icon" type="image/png" sizes="32x32" href="img/favicon/favicon-32x32.png">
	<link rel="icon" type="image/png" sizes="96x96" href="img/favicon/favicon-96x96.png">
	<link rel="icon" type="image/png" sizes="16x16" href="img/favicon/favicon-16x16.png">
	<link rel="manifest" href="/manifest.json">
	<meta name="msapplication-TileColor" content="#ffffff">
	<meta name="msapplication-TileImage" content="/ms-icon-144x144.png">
	<meta name="theme-color" content="#ffffff">
	 <!-------------------------------------------------------------------------->
	
	<script type="text/javascript" src="js/jquery-3.5.0.js"></script>
	<script type="text/javascript" src="js/jquery.animateSprite.min.js"></script>
    
	<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
	<link rel="stylesheet" type="text/css" href="css/style.css">
	
  </head>
  <body>
	  
	 <audio id="bgm">
		  <source src="audio/mus_toriel.ogg" type="audio/ogg">
		  Your browser does not support the audio element.
	  </audio>
	  
	  <audio id="bgm2">
		  <source src="audio/mus_story.ogg" type="audio/ogg">
		  Your browser does not support the audio element.
	  </audio>
	  
	  <audio id="bgm3">
		  <source src="audio/mus_menu.ogg" type="audio/ogg">
		  Your browser does not support the audio element.
	  </audio>
 <img src="img/muteoff.png" id="mute">	  
<div id="down">-</div>
<div id="up">+</div>
<div id="sfx">sfx</div>
 <div id="splashscreen">FOR A BETTER EXPERIENCE PLEASE TURN ON THE AUDIO<br></div>
 <div id="loading">LOADING<div id="dot"></div></div>
 <a id="play">START</a>
 <div id="wait">.<b id="punti"></b></div>
	
	<div class="row box" id="speak">
			<div class="col-3 char">
				<div id="port"></div>
			</div>
			<div class="col-1">*</div>
		<div class="col-7" id="narration"></div>
		<div id="blinkclick">click</div>
	  </div>
	  		
	  
	   <img src="img/flower.png" id="flower1" class="flower">
	   <img src="img/flower.png" id="flower2" class="flower">
	   <img src="img/flower.png" id="flower3" class="flower">
	   <div id="prot"></div>
	  
<div id="ruin">	
	<div id="prot2"></div>
</div>
	  
<div id="lab">
	<div id="sci"></div>
	<div id="robot"></div>
</div>
	 	  
<img src="img/narration/backstory/1.png" id="past">

<div id="mountain">
	<div id="soldier"></div>
</div>
	 
<div id="throne">
	<img src="img/throneroom/throne.png" id="chair">
	<img src="img/throneroom/asgore.png" id="king">
</div>

<img src="img/narration/good.png" id="friend">
<img src="img/narration/bad.png" id="foe">

<img src="img/fight/enemy1.png" id="man" class="">
<img src="img/fight/fight.png" id="attack">
<img src="img/fight/att/attbar.png" id="attackbar">
<img src="img/fight/att/f1.png" id="fight">
<img src="img/fight/att/m1.png" id="spare">
<img src="img/fight/cloud.png" id="cloud1">
<img src="img/fight/cloud.png" id="cloud2">
<img src="img/fight/cloud.png" id="cloud3">
<div id="slash"></div>
<div id="slash2"></div>
	  
<img src="img/sans/sans.png" id="sans">
<div id="spcb"></div>
<div id="blinkclick2">click</div>
<img src="img/fight/torielfight/torfight1.png" id="toriel">
<div id="cover"></div>
	  
<img src="img/logo.png" id="title">

<div id="floweysp"></div>
<div id="flowey"></div>

<div id="end">
<a id="reset">Reset</a><br>
and make a new choice<br>
or<br>
Buy the game
<ul>
<li><a href="https://store.steampowered.com/app/391540"><img src="img/logo/steam.png"></a></li>
<li><a href="https://www.nintendo.com/games/detail/undertale-switch"><img src="img/logo/switch.png"></a></li>
<li><a href="https://store.playstation.com/product/EP3746-CUSA09415_00-CB00000000000084"><img src="img/logo/ps.png"></a></li>
<li><a href="https://www.microsoft.com/en-us/p/undertale/9n046hwgq4j2"><img src="img/logo/microsoft.png"></a></li>
</ul>
</div>

<div id="white"></div>
	  


	
	 
	  
<script type="text/javascript">
				
			document.getElementById("mute").style.position = "absolute";
			document.getElementById("mute").style.top = "7px";
			document.getElementById("mute").style.left = "1621px";
			document.getElementById("mute").style.zIndex = "999999999999";
	        document.getElementById("mute").style.visibility = "hidden";
	
			document.getElementById("up").style.position = "absolute";
			document.getElementById("up").style.top = "-37px";
			document.getElementById("up").style.left = "1497px";
			document.getElementById("up").style.zIndex = "999999999999";
	        document.getElementById("up").style.visibility = "hidden";
	
			document.getElementById("down").style.position = "absolute";
			document.getElementById("down").style.top = "-37px";
			document.getElementById("down").style.left = "1568px";
			document.getElementById("down").style.zIndex = "999999999999";
	        document.getElementById("down").style.visibility = "hidden";
	
			document.getElementById("sfx").style.position = "absolute";
			document.getElementById("sfx").style.top = "-3px";
			document.getElementById("sfx").style.left = "1696px";
			document.getElementById("sfx").style.zIndex = "999999999999";
	        document.getElementById("sfx").style.visibility = "hidden";
	
			document.getElementById("loading").style.position = "absolute";
			document.getElementById("loading").style.top = "407px";
			document.getElementById("loading").style.left = "530px";
	        document.getElementById("loading").style.visibility = "hidden";
	
			document.getElementById("wait").style.position = "absolute";
			document.getElementById("wait").style.top = "783px";
			document.getElementById("wait").style.left = "55px";
	        document.getElementById("wait").style.visibility = "hidden";

			document.getElementById("play").style.visibility = "hidden";
			document.getElementById("play").style.position = "absolute";
			document.getElementById("play").style.top = "380px";
			document.getElementById("play").style.left = "612px";
	/*Initial placement*/	
			document.getElementById("speak").style.position = "absolute";
			document.getElementById("speak").style.top = "650px";
			document.getElementById("speak").style.left = "510px";
			document.getElementById("speak").style.visibility = "hidden";
		    document.getElementById("speak").style.zIndex = "999";
	
			document.getElementById("blinkclick").style.position = "relative";
			document.getElementById("blinkclick").style.top = "168px";
			document.getElementById("blinkclick").style.left = "-2px";
			document.getElementById("blinkclick").style.visibility = "";
		/*Fall*/
			document.getElementById("flower1").style.position = "absolute";
				document.getElementById("flower1").style.top = "-200px";
				document.getElementById("flower1").style.left = "100px";
	
			document.getElementById("flower2").style.position = "absolute";
				document.getElementById("flower2").style.top = "-200px";
				document.getElementById("flower2").style.left = "860px";
				document.getElementById("flower2").style.zIndex = "99";
	
			document.getElementById("flower3").style.position = "absolute";
				document.getElementById("flower3").style.top = "-200px";
				document.getElementById("flower3").style.left = "1620px";
	
		    document.getElementById("prot").style.position = "absolute";
				document.getElementById("prot").style.top = "-260px";
				document.getElementById("prot").style.left = "620px";
		        document.getElementById("prot").style.transform = "rotate(-90deg)";
				document.getElementById("prot").style.zIndex = "95";
				
		
			var f1= $('#flower1');
			var f2= $('#flower2');
			var f3= $('#flower3');
			var p1= $('#prot');
			var bob1 = 0;
			var bob2 = 0;
			var bob3 = 0;
			var bob4 = 0;

		/*Ruin*/
			document.getElementById("ruin").style.position = "absolute";
			document.getElementById("ruin").style.top = "1580px";
			document.getElementById("ruin").style.left = "0px";
	
			document.getElementById("prot2").style.position = "relative";
			document.getElementById("prot2").style.top = "474px";
			document.getElementById("prot2").style.left = "1958px";
			var s1 = $('#ruin');
			var p2 = $('#prot2');
			var bob0= 0;
	
			var tor = new Audio('audio/snd_txttor.wav');
		
		/*Past*/
			document.getElementById("past").style.position = "absolute";
			document.getElementById("past").style.top = "105px";
			document.getElementById("past").style.left = "497px";
			document.getElementById("past").style.visibility = "hidden";
		
		/*Lab*/
			document.getElementById("lab").style.position = "absolute";
			document.getElementById("lab").style.top = "-1463px";
			document.getElementById("lab").style.left = "2000px";
			document.getElementById("lab").style.zIndex = "99";
	
			document.getElementById("sci").style.position = "relative";
			document.getElementById("sci").style.top = "1743px";
			document.getElementById("sci").style.left = "200px";
	
			document.getElementById("robot").style.position = "relative";
			document.getElementById("robot").style.top = "1373px";
			document.getElementById("robot").style.left = "1000px";
		
		/*Mountain*/
			document.getElementById("mountain").style.position = "absolute";
			document.getElementById("mountain").style.top = "1200px";
			document.getElementById("mountain").style.left = "0px";
	
			document.getElementById("soldier").style.position = "relative";
			document.getElementById("soldier").style.top = "833px";
			document.getElementById("soldier").style.left = "940px";
		
		/*Throne*/
			document.getElementById("throne").style.position = "absolute";
			document.getElementById("throne").style.top = "-1600px";
			document.getElementById("throne").style.left = "-339px";
			$('#throne').fadeOut(1);
	
			document.getElementById("chair").style.position = "relative";
			document.getElementById("chair").style.top = "1212px";
			document.getElementById("chair").style.left = "1186px";
			document.getElementById("chair").style.zIndex = "98";
	
			document.getElementById("king").style.position = "relative";
			document.getElementById("king").style.top = "1656px";
			document.getElementById("king").style.left = "780px";
			document.getElementById("king").style.zIndex = "99";
		
		/*Friend or foe*/
			document.getElementById("friend").style.position = "absolute";
			document.getElementById("friend").style.top = "117px";
			document.getElementById("friend").style.left = "600px";
			$('#friend').fadeOut(1);
	
			document.getElementById("foe").style.position = "absolute";
			document.getElementById("foe").style.top = "52px";
			document.getElementById("foe").style.left = "1000px";
			$('#foe').fadeOut(1);
		
		/*First fight*/
			document.getElementById("man").style.position = "absolute";
			document.getElementById("man").style.top = "100px";
			document.getElementById("man").style.left = "733px";
			$('#man').fadeOut(1);
	
			document.getElementById("cloud1").style.position = "absolute";
			document.getElementById("cloud1").style.top = "260px";
			document.getElementById("cloud1").style.left = "880px";
	
	        document.getElementById("cloud2").style.position = "absolute";
			document.getElementById("cloud2").style.top = "260px";
			document.getElementById("cloud2").style.left = "880px";
	
	        document.getElementById("cloud3").style.position = "absolute";
			document.getElementById("cloud3").style.top = "260px";
			document.getElementById("cloud3").style.left = "880px";
	
	        document.getElementById("cloud1").style.visibility = "hidden";
			document.getElementById("cloud2").style.visibility = "hidden";
			document.getElementById("cloud3").style.visibility = "hidden";
	
			document.getElementById("cloud1").style.opacity = "0.5";
			document.getElementById("cloud2").style.opacity = "0.5";
			document.getElementById("cloud3").style.opacity = "0.5";
	
			document.getElementById("fight").style.position = "absolute";
			document.getElementById("fight").style.top = "522px";
			document.getElementById("fight").style.left = "468px";
			$('#fight').fadeOut(1);
	
			document.getElementById("attack").style.position = "absolute";
			document.getElementById("attack").style.top = "440px";
			document.getElementById("attack").style.left = "420px";
	        document.getElementById("attack").style.zIndex = "99";
			document.getElementById("attack").style.visibility = "hidden";
	
			document.getElementById("attackbar").style.position = "absolute";
			document.getElementById("attackbar").style.top = "448px";
			document.getElementById("attackbar").style.left = "390px";
	        document.getElementById("attackbar").style.zIndex = "100";
	
			document.getElementById("attackbar").style.visibility = "hidden";
			document.getElementById("spare").style.position = "absolute";
			document.getElementById("spare").style.top = "520.4px";
			document.getElementById("spare").style.left = "1047px";
	
			document.getElementById("slash").style.position = "absolute";
			document.getElementById("slash").style.top = "134px";
			document.getElementById("slash").style.left = "864px";
			document.getElementById("slash").style.visibility = "hidden";
			$('#spare').fadeOut(1);
			
			var blink = new Audio('audio/snd_select.wav');
			var attack = new Audio ('audio/snd_laz.wav');
			var endfight = new Audio ('audio/snd_vaporized.wav');
			var damage = new Audio ('audio/snd_damage.wav');
			var bDamage = new Audio ('audio/snd_heavydamage.ogg');
			var end = new Audio ('audio/mus_intronoise.ogg');
			
			var pacific = 0;
			var genocide = 0;
	
			/*Sans*/
	        document.getElementById("sans").style.position = "absolute";
			document.getElementById("sans").style.top = "116px";
			document.getElementById("sans").style.left = "729px";
			document.getElementById("sans").style.visibility = "hidden";
	
	        document.getElementById("spcb").style.position = "absolute";
			document.getElementById("spcb").style.top = "105px";
			document.getElementById("spcb").style.left = "1020px";
			document.getElementById("spcb").style.visibility = "hidden";
	
			document.getElementById("cover").style.position = "absolute";
			document.getElementById("cover").style.top = "105px";
			document.getElementById("cover").style.left = "1020px";
			document.getElementById("cover").style.display = "none";
	
	        document.getElementById("blinkclick2").style.position = "absolute";
			document.getElementById("blinkclick2").style.top = "412px";
			document.getElementById("blinkclick2").style.left = "1437px";
			document.getElementById("blinkclick2").style.visibility = "hidden";
	
			document.getElementById("toriel").style.position = "absolute";
			document.getElementById("toriel").style.top = "19px";
			document.getElementById("toriel").style.left = "768px";
			document.getElementById("toriel").style.visibility = "hidden";
	 		
			document.getElementById("slash2").style.position = "absolute";
			document.getElementById("slash2").style.top = "134px";
			document.getElementById("slash2").style.left = "864px";
			document.getElementById("slash2").style.visibility = "hidden";
	        document.getElementById("slash2").style.zIndex = "100";
			
			var trans = new Audio ('audio/snd_noise.wav');
			var chara = new Audio ('audio/mus_f_laugh.wav');
	
			
			/*End*/
			document.getElementById("title").style.position = "absolute";
			document.getElementById("title").style.top = "347px";
			document.getElementById("title").style.left = "40px";
			document.getElementById("title").style.visibility = "hidden";
	
			/*Callto*/
	
			document.getElementById("flowey").style.position = "absolute";
			document.getElementById("flowey").style.top = "149px";
			document.getElementById("flowey").style.left = "739px";
			document.getElementById("flowey").style.visibility = "hidden";
			
			document.getElementById("floweysp").style.position = "absolute";
			document.getElementById("floweysp").style.top = "59px";
			document.getElementById("floweysp").style.left = "510px";
			document.getElementById("floweysp").style.visibility = "hidden";
	
			document.getElementById("end").style.visibility="hidden";
	
			document.getElementById("white").style.position = "absolute";
			document.getElementById("white").style.top = "0px";
			document.getElementById("white").style.left = "0px";
	        $('#white').fadeOut(1);
		
			var flowey1 = new Audio ('audio/snd_floweytalk1.wav');
			var flowey2 = new Audio ('audio/snd_floweytalk2.wav');
			
			var back = new Audio ('audio/mus_cymbal.ogg');
			
			var first = "";
	
			var change = 0;
	
	
		/*Sprite Animation*/
		
		$("#prot").animateSprite({
    	 fps: 4,
    	 animations: {
		 walkRight: [1, 0],
		 walkDown:[5, 6, 7, 8],
		 evil:[10,11,12,13,14]
		
		},
		autoplay:false,
		loop: true,
		complete: function(){
			// use complete only when you set animations with 'loop: false'
			alert("animation End");
		}
		});
	
	
		$("#prot2").animateSprite({
    	 fps: 4,
    	 animations: {
         walkLeft: [0, 1, 2, 3],
         walkUp: [4, 5, 6, 7],
		 walkRight: [11, 10, 9, 8],
		 walkDown:[12, 13, 14, 15],
		 speak:[16]
		
		},
		autoplay:false,
		loop: true,
		complete: function(){
			// use complete only when you set animations with 'loop: false'
			alert("animation End");
		}
		});

		$('#port').animateSprite({
		fps: 2,
		animations: {
		normal: [6,7],
		end: [8,9],
		preoccupied: [12,13],
		longend: [0,1,2,3,4,5]


		},
		autoplay:false,
		loop: true,
		complete: function(){
			// use complete only when you set animations with 'loop: false'
			alert("animation End");
		}
		});
		
		
		$('#robot').animateSprite({
		fps: 2,
		animations: {
		eLaugh: [0,1],
		},
		autoplay:false,
		loop: true,
		complete: function(){
			// use complete only when you set animations with 'loop: false'
			alert("animation End");
		}
		});
		
		
		$("#sci").animateSprite({
    	 fps: 4,
    	 animations: {
         walkRight: [0, 1, 2, 3],
         walkLeft: [7, 6, 5, 4]
		
		},
		autoplay:false,
		loop: true,
		complete: function(){
			// use complete only when you set animations with 'loop: false'
			alert("animation End");
		}
		});
		
		$("#soldier").animateSprite({
    	 fps: 9,
    	 animations: {
         glare: [0,1,2,3,4,5,6,7,8]
		},
		autoplay:false,
		loop: false,
		complete: function(){
			// use complete only when you set animations with 'loop: false'
		}
		});
	 
        $("#slash, #slash2").animateSprite({
    	 fps: 6,
    	 animations: {
         hit: [0,1,2,3,4,5]
		},
		autoplay:false,
		loop: false,
		complete: function(){
			// use complete only when you set animations with 'loop: false'
		}
		});
	
		$('#flowey').animateSprite({
    	 fps: 8,
    	 animations: {
		 burst: [0,1,2,3,4,5,6,7],
		 speak:[8, 9],
		 evil:[16,17],
		 evil2:[24,25],
		 reverse:[7,6,5,4,3,2,1,0]
		},
		autoplay:false,
		loop: false,
		complete: function(){
			// use complete only when you set animations with 'loop: false'
			
		}
		});


	
		
		
		
		
/*-------------------------------------------------------------------------------------------------------*/		
		setTimeout(function(){
			$('#splashscreen').fadeOut();
            setTimeout(function(){
			document.getElementById("loading").style.visibility = "";
		    load();
			},2000)},2000)
		
	
	
	
	
	
		$(document).ready(function(){ 
			setTimeout(function(){
				$('#loading').fadeOut();
				setTimeout(function(){
					document.getElementById("play").style.visibility = "";
				},1000)},9000)
			
			setInterval(function(){$("#blinkclick").fadeOut(100).fadeIn(100)},1000);
			setInterval(function(){$("#blinkclick2").fadeOut(100).fadeIn(100)},1000);
			
		
	  $('#play').on('click', function() {
		document.getElementById("mute").style.visibility = "";
		document.getElementById("up").style.visibility = "";
		document.getElementById("down").style.visibility = "";
		document.getElementById("sfx").style.visibility = "";
		document.getElementById("wait").style.visibility = "";
		setTimeout(wait,1000);
		p2.animateSprite('stop');
		$("#prot").animateSprite('frame', 1);
		musicstart("bgm");
		$('#play').fadeOut();
	/*Flower1 Fall*/
		upDown(f1,bob1,620,625,40);
		  /*Flower2 Fall*/
		setTimeout(function(){upDown(f2,bob2,720,725,30);
				/*Flower3 Fall*/
	    	setTimeout(function(){upDown(f3,bob3,620,625,20);
					/*Frisk Fall*/
		  		setTimeout(function(){upDown(p1,bob4,413,418,28);
							/*Flower3 Rise*/
					setTimeout(function(){upDown(f3,bob3,-300,-300,0);
								/*Flower2 Rise*/
	    				setTimeout(function(){upDown(f2,bob2,-300,-300,0);
									/*Flower1 Rise*/
	    					setTimeout(function(){upDown(f1,bob1,-300,-300,0);
											/*Ruin Rise*/			  
											setTimeout(function(){upDown(s1,bob0,0,0,0);
												/*Toriel Walk*/		 
													setTimeout(function(){
															p2.animateSprite('play', 'walkLeft');
														    p2.animate({left:1150},7000);
														setTimeout(function(){
															p2.animateSprite('stop')
															p2.animateSprite('play', 'walkUp'); 
															p2.animate({top:240},7000);
													      setTimeout(function(){
															p2.animateSprite('stop')
															p2.animateSprite('play', 'walkLeft'); 
															p2.animate({left:920},7000);
														/*Frisk get up*/
														setTimeout(function(){
																document.getElementById("prot").style.top = "296px";
																document.getElementById("prot").style.left = "755px";
																document.getElementById("prot").style.transform = "rotate(0deg)";
																setTimeout(function(){
																	document.getElementById("wait").style.visibility = "hidden";
																	p2.animateSprite('stop');
																	torSpeak("Don't be afraid, my child I will not hurt you.",'normal');	
																			},6500)},1000)},6700)},6500)},6000)},30000)},10000)},10000)},10000)},10000)},10000)},10000);
	  });
	
	});
/*-------------------------------------------------------------------------------------------------------------------------*/

	var nar = 0;
		
	function torNarration(){
		
		switch (nar) {
		  case 0:
			torSpeak('I am Toriel caretaker of the RUINS.','normal');
			nar++;
			break;
		  case 1:
			torSpeak('I pass throught this place every day to see if anyone has fallen down.','normal');
			nar++;
			break;
		  case 2:
			 torSpeak('You are the first human to come here in a long time.','normal');
			 nar++;
			break;
		  case 3:
			torSpeak('You may wonder where you are and why I am here.','normal');
			nar++;
			break;
		  case 4:
			torSpeak("Well, that's because of an event that happened a long time ago.",'normal');
			setTimeout(function(){
				document.getElementById("speak").style.visibility = "hidden";
				document.getElementById("blinkclick").style.visibility = "hidden";
				$('#ruin').fadeOut();
				$('#prot').fadeOut();
				$('#past').fadeOut();
				musicstop("bgm");
			setTimeout(function(){
				musicstart("bgm2");
				$("#narration").empty();
				document.getElementById("speak").style.visibility = "";
				document.getElementById("past").style.visibility = "";
				document.getElementById("blinkclick").style.visibility = "hidden";
				$('#past').fadeIn();
				$('#speak').off('click');
			setTimeout(function(){
				torSpeak('Long ago, two races ruled over Earth: Human and Monsters.','normal');
			},2000)
			},2000);
			},7800);
			nar++;
			break;
		  case 5:
			document.getElementById("past").src = "img/narration/backstory/2.png";
			torSpeak('One day, war broke out between the two races.','normal');
			nar++;
			break;
		  case 6:
			document.getElementById("past").src = "img/narration/backstory/3.png";
			torSpeak('After a long battle, the human where victoriuous.','normal');
			nar++;
			break;
		  case 7:
			document.getElementById("past").src = "img/narration/backstory/4.png";
			torSpeak('They sealed us underground with a magic spell.','normal');
			nar++;
			break;
		  case 8:
			document.getElementById("past").src = "img/narration/backstory/5.png";
			torSpeak('Here under Mt. Ebott.','normal');
			nar++;
			break;
		  case 9:
			document.getElementById("past").style.visibility = "hidden";
			torSpeak('My child, before you is a long journey.','normal');
			nar++;
			break;
		  case 10:
			torSpeak('On your journey you may encounter a weird scientist and her murderous robot.','normal');
			nar++;
			$("#lab").animate({left:-80},3000);
			$('#robot').animateSprite('play', 'eLaugh'); 
					$("#sci").animateSprite('play', 'walkRight');
						$("#sci").animate({left:800},10000);
						setTimeout(function(){ $("#sci").animateSprite('stop');},9000);
			break;
			case 11:
			document.getElementById("lab").style.visibility = "hidden";
			$("#soldier").animateSprite('stop')
			$("#soldier").animateSprite('frame', 0);
			$("#mountain").animate({top:-731},3000);
			torSpeak('A proud knight in her armor.','normal');
			setTimeout(function(){$('#soldier').animateSprite('play', 'glare');setTimeout(function(){$('#soldier').animateSprite('stop');$("#soldier").animateSprite('frame', 0);},1000)},3000) 
			nar++;
			break;
			case 12:
			document.getElementById("mountain").style.visibility = "hidden";
			document.getElementById("throne").style.visibility = "";
			$('#throne').fadeIn(2000);
			torSpeak('And it may end in a throne room with a worried king.','normal'); 
			nar++;
			break;
			case 13:
			document.getElementById("throne").style.visibility = "hidden";
			torSpeak('You will have to make choices.','normal'); 
			nar++;
			break;
			case 14:
			$('#friend').fadeIn(2000);
			torSpeak('Based on which some people could become good friends.','normal'); 
			nar++;
			break;
			case 15:
			$('#foe').fadeIn(2000);
			torSpeak('Or fierce enemies.','normal'); 
			nar++;
			break;
			case 16:
			document.getElementById("friend").style.visibility = "hidden";
			document.getElementById("foe").style.visibility = "hidden";
			torSpeak('When you will find yourself in danger, you will have to make the most difficult one.','normal'); 
			nar++;
			break;
			case 17:
			$('#man').fadeIn(2000);
			torSpeak('When your life will be put on the line.','normal'); 
			nar++;
			break;
			case 18:
			$('#fight').fadeIn(2000);
			$('#spare').fadeIn(2000);
			torSpeak('What will you do?','normal'); 
			nar++;
			break;
			case 19:
			document.getElementById("speak").style.visibility = "hidden";
			musicstop("bgm2");
			$('#fight').fadeIn(2000);
			$('#spare').fadeIn(2000);
			$('#fight').mouseenter(function () {
				blink.play();
				document.getElementById("fight").src = "img/fight/att/f2.png";
			})
			$('#spare').mouseenter(function (){
				blink.play();
				document.getElementById("spare").src = "img/fight/att/m2.png";
			})
			
			$('#fight').mouseleave(function () {
				document.getElementById("fight").src = "img/fight/att/f1.png";
			})
			$('#spare').mouseleave(function (){
				document.getElementById("spare").src = "img/fight/att/m1.png";
			})
				
			$('#fight').on('click',function(){
				$('#fight').off('click');
				$('#spare').off('click');
				$('#fight').mouseenter(function () {})
				$('#fight').mouseleave(function () {})
				$('#spare').mouseenter(function () {})
				$('#spare').mouseleave(function () {})
				genocide++;
				document.getElementById("fight").style.visibility = "hidden";
				document.getElementById("spare").style.visibility = "hidden";
				document.getElementById("attack").style.visibility = "";
				document.getElementById("attackbar").style.visibility = "";
				 $("#attackbar").animate({left:890},1000);
				setTimeout(function(){
					blink.play();
					document.getElementById("attackbar").src = "img/fight/att/attbar2.png";
					setTimeout(function(){
					document.getElementById("attack").style.visibility = "hidden";
					document.getElementById("attackbar").style.visibility = "hidden";
					document.getElementById("slash").style.visibility = "";
					$("#slash").animateSprite('restart');	
					attack.play();
					setTimeout(function(){
					 document.getElementById("fight").style.left = "756px";
					 document.getElementById("attackbar").src = "img/fight/att/attbar.png";
					 document.getElementById("slash").style.visibility = "hidden";
					 document.getElementById("man").src = "img/fight/enemy2.png";
					 damage.play();
					 death("man","#man",3);
					 setTimeout(function(){
					 $("#man").addClass("vanishOut");
					 endfight.play();
					setTimeout(function(){
						$('#man').fadeOut(1);
						document.getElementById("sans").style.visibility = "";
					setTimeout(function(){
						 $("#man").removeClass("vanishOut");
						sansSpeak("hey, kiddo");
					},1500)},1500)},5000)},1000)},100)},1200)});

			$('#spare').on('click',function(){
				$('#fight').off('click');
				$('#spare').off('click');
				$('#fight').mouseenter(function () {})
				$('#fight').mouseleave(function () {})
				$('#spare').mouseenter(function () {})
				$('#spare').mouseleave(function () {})
				pacific++;
				document.getElementById("fight").style.visibility = "hidden";
				document.getElementById("spare").style.visibility = "hidden";
				document.getElementById("man").style.opacity = "0.5";
				 document.getElementById("cloud1").style.visibility = "";
				 document.getElementById("cloud2").style.visibility = "";
				 document.getElementById("cloud3").style.visibility = "";
				 $("#cloud1").animate({top:195},1000);
				 $("#cloud2").animate({left:800},1000);
				 $("#cloud3").animate({left:950},1000);
				 $("#cloud1").fadeOut();
				 $("#cloud2").fadeOut();
				 $("#cloud3").fadeOut();
				endfight.play();
				setTimeout(function(){
					musicstart("bgm");
					$('#man').fadeOut();
					$('#ruin').fadeIn();
					$('#prot').fadeIn();
					document.getElementById("cloud1").style.top = "260px";
					document.getElementById("cloud1").style.left = "880px";
					document.getElementById("cloud2").style.top = "260px";
					document.getElementById("cloud2").style.left = "880px";
					document.getElementById("cloud3").style.top = "260px";
					document.getElementById("cloud3").style.left = "880px";
					$('#fight').fadeOut(1);
					$('#spare').fadeOut(1);
					document.getElementById("fight").style.visibility = "";
				    document.getElementById("spare").style.visibility = "";
					document.getElementById("cloud1").style.visibility = "hidden";
				    document.getElementById("cloud2").style.visibility = "hidden";
				    document.getElementById("cloud3").style.visibility = "hidden";
					$("#cloud1").fadeIn(1);
				 	$("#cloud2").fadeIn(1);
				 	$("#cloud3").fadeIn(1);
					setTimeout(function(){
					  $("#port").animateSprite('frame', 9);
					  torSpeak('Oh my, did I space out?','preoccupied'); 
					  nar = 21;
					},2000)
				},3000)
			})	
			break;
			case 20:
			break;
			case 21:
			torSpeak("Why don't you come to my house? I have a freshly baked Butterscotch Pie.",'normal');
			nar = 23;
			break;
			case 22:
			torSpeak("Why don't you come to my house? I have a freshly baked Snail Pie.",'normal');
			nar = 24;
			break;
			case 23:
			document.getElementById("speak").style.visibility = "hidden";
			setTimeout(function(){
			p2.animateSprite('play', 'walkRight');
			 p2.animate({left:1150},7000);
				setTimeout(function(){
					p2.animateSprite('stop')
					p2.animateSprite('play', 'walkDown'); 
					p2.animate({top:474},7000);
					 setTimeout(function(){
						p2.animateSprite('stop')
						p2.animateSprite('play', 'walkRight'); 
						p2.animate({left:1958},7000);
						 p1.animateSprite('play', 'walkRight');
						 p1.animate({left:1150},7000);
							setTimeout(function(){
								p1.animateSprite('stop')
								p1.animateSprite('fps', 4)
								p1.animateSprite('play', 'walkDown'); 
								p1.animate({top:474},7000);
					 		setTimeout(function(){
								p1.animateSprite('stop')
								p1.animateSprite('fps', 2)
								p1.animateSprite('play', 'walkRight'); 
								p1.animate({left:1958},7000);
								setTimeout(function(){
								musicstop("bgm");
								document.getElementById("title").style.visibility = "";	
								document.getElementById("ruin").style.visibility = "hidden";	
								end.play();
								setTimeout(function(){
									document.getElementById("title").style.visibility = "hidden";
									finale();
								},3000)},7000)},6500)},6700)},6500)},6700)},1000);
			break;
			case 24:
			document.getElementById("speak").style.visibility = "hidden";
			setTimeout(function(){
			p2.animateSprite('play', 'walkRight');
			 p2.animate({left:1150},7000);
				setTimeout(function(){
					p2.animateSprite('stop')
					p2.animateSprite('play', 'walkDown'); 
					p2.animate({top:474},7000);
					 setTimeout(function(){
						p2.animateSprite('stop')
						p2.animateSprite('play', 'walkRight'); 
						p2.animate({left:1958},7000);
						 p1.animateSprite('play', 'walkRight');
						 p1.animate({left:1150},7000);
							setTimeout(function(){
								p1.animateSprite('stop')
								p1.animateSprite('fps', 4)
								p1.animateSprite('play', 'walkDown'); 
								p1.animate({top:474},7000);
					 		setTimeout(function(){
								p1.animateSprite('stop')
								p1.animateSprite('fps', 2)
								p1.animateSprite('play', 'walkRight'); 
								p1.animate({left:1600},7000);
							setTimeout(function(){
								p1.animateSprite('stop');
								p1.animateSprite('frame', 4);
								p1.animateSprite('frame', 10); 
							setTimeout(function(){
								p1.animateSprite('fps', 5)
								chara.play();
								p1.animateSprite('play', 'evil'); 
								setTimeout(function(){
								chara.pause();
							    chara.currentTime = 0;
								document.getElementById("title").style.visibility = "";	
								document.getElementById("ruin").style.visibility = "hidden";
								document.getElementById("prot").style.visibility = "hidden";
								end.play();
								p1.animateSprite('fps', 2)
								setTimeout(function(){
									document.getElementById("title").style.visibility = "hidden";
									finale();
								},3000)},3000)},2000)},7000)},6500)},6700)},6500)},6700)},1000);	
			break;
		}
	}
		
/*-------------------------------------------------------------------------------------------------------------------------*/	
var san = 0;
		
	function sansNarration(){
		
		switch (san) {
		  case 0:
			document.getElementById("sans").src = "img/sans/sansside.png";
			sansSpeak('you may wonder who i am?');
			san++;
			break;
		  case 1:
			document.getElementById("sans").src = "img/sans/sansblink.png";
			sansSpeak("but i don't care");
			san++;
			break;
	      case 2:
			document.getElementById("sans").src = "img/sans/sansag.png";
			sansSpeak("so shut up and listen");
			san++;
			break;
	      case 3:
			document.getElementById("sans").src = "img/sans/sanscl.png";
			sansSpeak("what you just did wasn't very nice");
			san++;
			break;
	      case 4:
			document.getElementById("sans").src = "img/sans/sansblink.png";
			sansSpeak("i know that mannequin was very threatening");
			san++;
			break;
		  case 5:
			document.getElementById("sans").src = "img/sans/sansag.png";
			sansSpeak("but you better stop your killing desire here");
			san++;
			break;
		  case 6:
			document.getElementById("sans").src = "img/sans/sans.png";
			sansSpeak("because in the real thing you may cause more problem than you think");
			san++;
			break;
		  case 7:
			document.getElementById("cover").style.display = "block";
			document.getElementById("blinkclick2").style.color = "white";
			document.getElementById("sans").src = "img/sans/sans.png";
			sansSpeak("why don't i show you what i'm talking about");
			setTimeout(function(){
			document.getElementById("cover").style.display = "none";
			document.getElementById("blinkclick2").style.visibility = "hidden";
			document.getElementById("blinkclick2").style.color = "black";
			trans.play();
			setTimeout(function(){trans.play();},10);
			document.getElementById("attackbar").style.top = "448px";
			document.getElementById("attackbar").style.left = "390px";
			document.getElementById("spcb").style.visibility = "hidden";
			document.getElementById("sans").style.visibility = "hidden";
			setTimeout(function(){trans.play();
			setTimeout(function(){trans.play();},10);
			document.getElementById("toriel").style.visibility = "";
			document.getElementById("fight").style.visibility = "";
			$('#fight').mouseenter(function () {
				blink.play();
				document.getElementById("fight").src = "img/fight/att/f2.png";
			})
			$('#fight').mouseleave(function () {
				document.getElementById("fight").src = "img/fight/att/f1.png";
			})},500);
			$('#fight').on('click',function(){
				$('#fight').off('click');
				$('#spare').off('click');
				$('#fight').mouseenter(function () {})
				$('#fight').mouseleave(function () {})
				$('#spare').mouseenter(function () {})
				$('#spare').mouseleave(function () {})
				document.getElementById("fight").style.visibility = "hidden";
				document.getElementById("attack").style.visibility = "";
				document.getElementById("attackbar").style.visibility = "";
				 $("#attackbar").animate({left:890},1000);
				setTimeout(function(){
					blink.play();
					document.getElementById("attackbar").src = "img/fight/att/attbar2.png";
					setTimeout(function(){
					document.getElementById("attack").style.visibility = "hidden";
					document.getElementById("attackbar").style.visibility = "hidden";
					document.getElementById("slash2").style.visibility = "";
					$("#slash2").animateSprite('restart');	
					attack.play();
					setTimeout(function(){
					 document.getElementById("attackbar").style.top = "448px";
					 document.getElementById("attackbar").style.left = "390px";
					 document.getElementById("attackbar").src = "img/fight/att/attbar.png";
					 document.getElementById("slash2").style.visibility = "hidden";
					 document.getElementById("toriel").src = "img/fight/torielfight/torfight2.png";
					 bDamage.play();
					 death("toriel","#toriel",3);
					 setTimeout(function(){
					 document.getElementById("toriel").src = "img/fight/torielfight/torfight3.png";
					setTimeout(function(){
						document.getElementById("toriel").style.visibility = "hidden";
						document.getElementById("sans").style.visibility = "";
					setTimeout(function(){
						sansSpeak("see what i meant");
						san = 8;
					},1500)},1500)},4000)},1000)},100)},1200)});},5000);
			break;
			case 8:
			document.getElementById("sans").src = "img/sans/sansblink.png";
			sansSpeak("hope you learned a good lesson");
			san++;
			break;
			case 9:
			document.getElementById("sans").src = "img/sans/sansblink.png";
			sansSpeak("because if you try to kill any of us for real");
			san++;
			break;
			case 10:
			document.getElementById("cover").style.display = "block";
			document.getElementById("sans").src = "img/sans/sansb.png";
			document.getElementById("blinkclick2").style.color = "white";
			sansSpeak("you are gonna have a bad time");
			setTimeout(function(){
				    document.getElementById("cover").style.display = "none";
				    document.getElementById("blinkclick2").style.visibility = "hidden";
					document.getElementById("spcb").style.visibility = "hidden";
					document.getElementById("sans").style.visibility = "hidden";
				    document.getElementById("blinkclick2").style.color = "black";
					$('#ruin').fadeIn();
					$('#prot').fadeIn();
					setTimeout(function(){
					  san=0;
					  $("#port").animateSprite('frame', 9);
					  torSpeak('Oh my, did I space out?','preoccupied'); 
					  nar = 22;
					},2000)
				},5500)
		}};
	
	
	
	
	
/*-------------------------------------------------------------------------------------------------------------------------*/	
	
	
 function finale(){
	  document.getElementById("flowey").style.visibility = "";
	  document.getElementById("floweysp").style.visibility = "";
	 $("#flowey").animateSprite('play', 'burst'); 
	 setTimeout(
		 function(){
		 if (pacific == 1 && genocide == 0){
		   first = "pacific";
		   floweySpeak("I hope you liked it.","speak"); 
		   setTimeout(function(){
		   floweySpeak("Now you can reset and re-experience the choice.","speak"); 
		   setTimeout(function(){
		   floweySpeak("See you soon.","speak"); 
		  setTimeout(function(){
		  $("#floweysp").empty();
		  $("#flowey").animateSprite('play', 'reverse');
		  setTimeout(function(){
		  document.getElementById("flowey").style.visibility = "hidden";
	      document.getElementById("floweysp").style.visibility = "hidden";  
		  musicstart("bgm3");
		  document.getElementById("end").style.visibility = "";  
		     $('#reset').on('click', function() {
			   callto();
		   });
		  },1500)},2600)},5900)},3000)
		 }
			 	 
		 if (pacific == 0 && genocide == 1){
		  first = "genocide";	
		  floweySpeak("So you did it.","speak"); 
		  setTimeout(function(){
		  floweySpeak("You killed the goat.","evil"); 
		  setTimeout(function(){
		  floweySpeak("But here you don't suffer repercussion.","evil"); 
		  setTimeout(function(){
		  floweySpeak("If you do this in our world...","evil");
		  setTimeout(function(){
		  floweySpeak("then the fun will start.","evil2");
		  setTimeout(function(){
		  $("#floweysp").empty();
		  $("#flowey").animateSprite('play', 'reverse');
		  setTimeout(function(){
		  document.getElementById("flowey").style.visibility = "hidden";
	      document.getElementById("floweysp").style.visibility = "hidden"; 
		  musicstart("bgm3");
		  document.getElementById("end").style.visibility = ""; 
		     $('#reset').on('click', function() {
			   callto();
		   });
		  },1500)},3400)},4000)},4900)},3000)},2400)
         			 
		 } 
			 
			 
		 if (pacific >= 2 && genocide == 0){
		  floweySpeak("Aren't you tired of being the good guy.","speak"); 
		  setTimeout(function(){
		  floweySpeak("Why don't you try changing path.","speak"); 
		  setTimeout(function(){
		  floweySpeak("You won't be disappointed.","speak"); 
		  setTimeout(function(){
		  $("#floweysp").empty();
		  $("#flowey").animateSprite('play', 'reverse');
		  setTimeout(function(){
		  document.getElementById("flowey").style.visibility = "hidden";
	      document.getElementById("floweysp").style.visibility = "hidden"; 
		  musicstart("bgm3");
		  document.getElementById("end").style.visibility = "";  
		     $('#reset').on('click', function() {
			   callto();
		   });
		  },1500)},3600)},4200)},4900)
		 }
			 
			 
		 if (pacific == 0 && genocide >= 2){
		  floweySpeak("You haven't had enough.","evil"); 
	      setTimeout(function(){
		  floweySpeak("Here you can only fight a goat and a puppet.","evil"); 
		  setTimeout(function(){
		  floweySpeak("In our world you have many monster to make suffer.","evil"); 
		  setTimeout(function(){
		  floweySpeak("Stay here if you want but don't expect much change.","evil2");
		  setTimeout(function(){
		  $("#floweysp").empty();
		  $("#flowey").animateSprite('play', 'reverse');
		  setTimeout(function(){
		  document.getElementById("flowey").style.visibility = "hidden";
	      document.getElementById("floweysp").style.visibility = "hidden";  
		  musicstart("bgm3");
		  document.getElementById("end").style.visibility = "";  
		     $('#reset').on('click', function() {
			   callto();
		   });
		  },1500)},6100)},6000)},5400)},3300)
		 }
			 
			 
		 if (pacific >= 1 && genocide == 1 && first == "pacific"){
		  change=1;
		  floweySpeak("You couldn't resist didn't you.","evil"); 
		  setTimeout(function(){
		  floweySpeak("Now that you smelled the scent of blood.","evil"); 
		  setTimeout(function(){
		  floweySpeak("Why stop here.","evil");	
		  setTimeout(function(){
		  $("#floweysp").empty();
		  $("#flowey").animateSprite('play', 'reverse');
		  setTimeout(function(){
		  document.getElementById("flowey").style.visibility = "hidden";
	      document.getElementById("floweysp").style.visibility = "hidden";  
		  musicstart("bgm3");
		  document.getElementById("end").style.visibility = "";  
		     $('#reset').on('click', function() {
			   callto();
		   });
		  },1500)},2400)},5100)},4100)
		 }
			 
			 
		 if (pacific == 1 && genocide >= 1 && first == "genocide"){
		  change = 1;
		  floweySpeak("Fill better know.","speak"); 
		  setTimeout(function(){
		  floweySpeak("Well, you shouldn't.","evil"); 
		  setTimeout(function(){
		  floweySpeak("You must never forget what you did.","evil2");	
		  setTimeout(function(){
		  $("#floweysp").empty();
		  $("#flowey").animateSprite('play', 'reverse');
		  setTimeout(function(){
		  document.getElementById("flowey").style.visibility = "hidden";
	      document.getElementById("floweysp").style.visibility = "hidden";
		  musicstart("bgm3");
		  document.getElementById("end").style.visibility = "";  
		     $('#reset').on('click', function() {
			   callto();
		   });
		  },1500)},4500)},3000)},2700)
		 }
			 
			 
		 if (pacific >= 1 && genocide >= 1 && first == "n"){
		  floweySpeak("No matter what you choose.","evil"); 
		  setTimeout(function(){
		  floweySpeak("You can't escape from your choice.","evil"); 
		  setTimeout(function(){
		  floweySpeak("If you refresh the page I might forget.","evil"); 
		  setTimeout(function(){
		  floweySpeak("But you will always fell the sin crawling on your back.","evil2");
		  setTimeout(function(){
		  $("#floweysp").empty();
		  $("#flowey").animateSprite('play', 'reverse');
		  setTimeout(function(){
		  document.getElementById("flowey").style.visibility = "hidden";
	      document.getElementById("floweysp").style.visibility = "hidden";  
		  musicstart("bgm3");
		  document.getElementById("end").style.visibility = ""; 
		   $('#reset').on('click', function() {
			   callto();
		   });
		  },1500)},6500)},4900)},4400)},3700)
		 }		  	   
	},4000);
 }
 
 function callto(){
	 $('#reset').off('click');
	 
	 
	 document.getElementById("man").style.opacity = 1;
	 musicstop("bgm3");
	 $('#ruin').fadeOut(1);
	 $('#prot').fadeOut(1);
	 document.getElementById("ruin").style.visibility = "";
	 document.getElementById("prot").style.visibility = "";
	 $("#prot").animateSprite('stop');
	 $("#prot").animateSprite('frame', 1);
	 document.getElementById("prot").style.top = "296px";
	 document.getElementById("prot").style.left = "755px";
	 document.getElementById("prot2").style.top = "240px";
	 document.getElementById("prot2").style.left = "920px";
	 document.getElementById("fight").style.top = "522px";
	 document.getElementById("fight").style.left = "468px";
	 $('#fight').fadeOut(1);
	 $('#spare').fadeOut(1);
	 document.getElementById("fight").style.visibility = "";
	 document.getElementById("spare").style.visibility = "";
	 document.getElementById("toriel").src = "img/fight/torielfight/torfight1.png";
	 document.getElementById("man").src = "img/fight/enemy1.png";
	 document.getElementById("sans").src = "img/sans/sans.png";
	 $("#slash").animateSprite('stop');
	 $("#slash").animateSprite('frame', 0);
	 $("#slash2").animateSprite('stop');
	 $("#slash2").animateSprite('frame', 0);
	 if (change==1){
		 first = "n";
		 change=2;
	 }
	 
	 back.play();
	 $('#white').fadeIn(5000);
	 setTimeout(function(){ 
	 document.getElementById("end").style.visibility = "hidden"; 
	 $('#white').fadeOut(1);
	 nar=17;
	 torNarration();
	 },5000)
	 
 }
	
/*-------------------------------------------------------------------------------------------------------------------------*/
	
	var punto=0;
	
		function load(){

			if (punto==3){
			  $("#dot").empty();
			  punto=0;
			 setTimeout(load, 1000);
			}else{
			  $("#dot").append(".");
			  punto++;
			  setTimeout(load, 1000);
			}
		}
	
	var punto2=0;
	
		function wait(){

			if (punto2==2){
			  $("#punti").empty();
			  punto2=0;
			 setTimeout(wait, 1000);
			}else{
			  $("#punti").append(".");
			  punto2++;
			  setTimeout(wait, 1000);
			}
		}
	
	
		function upDown(x,i,t,b,mov,ftime){
			var stop = 0;
			setTimeout(function(){x.animate({top: t}, 6000);},ftime)
			var i = setInterval(function() {
				if (stop == mov){
					clearInterval(i)
				}else{
				  x.animate({top: b}, 1000);
				  x.animate({top: t}, 1000);
				  stop++;
				 }
				},1);		
		}
		function musicstop(id){

				var x = document.getElementById(id);
				x.pause();
				x.currentTime = 0;
		}
		function musicstart(id){

				var x = document.getElementById(id);
				x.currentTime = 0;
				x.play();
				x.loop = true;

		}	

		function torSpeak(testo,emotion){
			var i=0;
			$('#speak').off('click');
			$("#narration").empty();
			$('#port').animateSprite('play', emotion);
			$("#prot2").animateSprite('stop');
			$("#prot2").animateSprite('frame', 16);
			document.getElementById("speak").style.visibility = "";
			document.getElementById("blinkclick").style.visibility = "hidden";
			var txt = testo;
			typeWriter()
		function typeWriter() {
			if (i < txt.length) {
			$("#narration").append(txt.charAt(i));
			i++;
			tor.play();
			setTimeout(typeWriter, 100);
		  }else{
			$("#prot2").animateSprite('stop')
			$("#prot2").animateSprite('frame', 0);
			$('#port').animateSprite('play', 'end');
			setTimeout(function(){
			$("#port").animateSprite('stop')
			$("#port").animateSprite('frame', 0);
			$('#speak').on('click');
			;},2000)
			setTimeout(function(){
				document.getElementById("blinkclick").style.visibility = "";
		  			$('#speak').on('click', function() {
		  
		            torNarration();
						
	                });
			},2000);
			
		  }
		}
	};
	
	
		function death(id,idj,mov){
		var bump = 0;
		var stop = 0;
		var posizione = $(idj).position();
		var mr = posizione.left;
		var i = setInterval(function(){  
		if (stop == mov){
			clearInterval(i);
			document.getElementById(id).style.left = mr +"px";
		}else{
		  if (bump == 0){
			document.getElementById(id).style.left = mr + 100 +"px";
			bump = 1;
		}else{
			document.getElementById(id).style.left = mr - 100 +"px";
			bump = 0;
			stop++;
		}}}, 500);

	};	
	
		function sansSpeak(testo){
			var i=0;
			var sans = new Audio ('audio/snd_txtsans.wav');
			$('#spcb').off('click');
			$("#spcb").empty();
			document.getElementById("spcb").style.visibility = "";
			document.getElementById("blinkclick2").style.visibility = "hidden";
			var txt = testo;
			typeWriter()
		function typeWriter() {
			if (i < txt.length) {
			$("#spcb").append(txt.charAt(i));
			i++;
			sans.play();
			setTimeout(typeWriter, 100);
		  }else{
				document.getElementById("blinkclick2").style.visibility = "";
		  			$('#spcb').on('click', function() {
		  
		            sansNarration();
						
	                });
		  
		  }}};
	
		function floweySpeak(testo,emotion){
			var i=0;
			if (emotion == "speak"){
				var fbase = 8;
				var fspeak = 9;
			} else if (emotion == "evil"){
				var fbase = 16;
				var fspeak = 17;
			}  else if (emotion == "evil2"){
				var fbase = 24;
				var fspeak = 25;
			} 
			$("#flowey").animateSprite('frame', fbase);
			$("#floweysp").empty();
			document.getElementById("floweysp").style.visibility = "";
			var txt = testo;
			typeWriter()
		function typeWriter() {
			if (i < txt.length) {
			$("#floweysp").append(txt.charAt(i));
			i++;
			if (emotion == "speak"){
			 flowey1.play();
			} else{
			 flowey2.play();	
			}
			$("#flowey").animateSprite('frame', fspeak);
			setTimeout(typeWriter, 100);
		  }else{
			$("#flowey").animateSprite('stop')
			$("#flowey").animateSprite('frame', fbase);
	                };
		  
		  }};
	
		var a1 = document.getElementById("bgm");
		var a2 = document.getElementById("bgm2");
		var a3 = document.getElementById("bgm3");
		
		a1.volume = 1.0;
		a2.volume = 1.0;
		a3.volume = 1.0;
	
		var voln = 1.0
	
		$('#up').on('click', function() {
			voln=voln+0.1;
			if (voln>=1.0){
				voln=1.0;
			}
			
			a1.volume = voln;
			a2.volume = voln;
			a3.volume = voln;
		
		})
		
		$('#down').on('click', function() {
			voln=voln-0.1;
			if (voln<=0.0){
				voln=0.0;
			}
			
			a1.volume = voln;
			a2.volume = voln;
			a3.volume = voln;
		 
		})
	
		var audioonoff=1;
		
		
		$('#mute').on('click', function() {
			if (audioonoff==1){
				a1.volume = 0;
				a2.volume = 0;
				a3.volume = 0;
				audioonoff=0;
				document.getElementById("mute").src = "img/mute.png";
			} else if (audioonoff==0){
				a1.volume = voln;
				a2.volume = voln;
				a3.volume = voln;
				audioonoff=1;
				document.getElementById("mute").src = "img/muteoff.png";
			}
		});
	
	
		var sfxonoff=1;
		
		
		$('#sfx').on('click', function() {
			if (sfxonoff==1){
				attack.volume = 0.0;
				endfight.volume = 0.0;
				damage.volume = 0.0;
				bDamage.volume = 0.0;
				end.volume = 0.0;
				trans.volume = 0.0;
				chara.volume = 0.0;
				flowey1.volume = 0.0;
				flowey2.volume = 0.0;
				back.volume = 0.0;
				tor.volume = 0.0;
				sans.volume = 0.0;
				sfxonoff=0;
				document.getElementById("sfx").style.textDecoration = "line-through";
			} else if (sfxonoff==0){
				attack.volume = 1.0;
				endfight.volume = 1.0;
				damage.volume = 1.0;
				bDamage.volume = 1.0;
				end.volume = 1.0;
				trans.volume = 1.0;
				chara.volume = 1.0;
				flowey1.volume = 1.0;
				flowey2.volume = 1.0;
				back.volume = 1.0;
				tor.volume = 1.0;
				sans.volume = 1.0;
				sfxonoff=1;
				document.getElementById("sfx").style.textDecoration = "none";
			}
		});
	
	  </script>
	<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
	<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
  </body>
</html>
