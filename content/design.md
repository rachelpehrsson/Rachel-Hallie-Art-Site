+++
author = ""
comments = true	# set false to hide Disqus
date = "2018-01-07T23:43:23-05:00"
draft = false
type = "page"
layout = "cover"
image = "images/gradiant background.png"
menu = "main"
weight = "-110"		# set "main" to add this content to the main menu
share = true	# set false to hide share buttons
slug = "design"

title = "Design and Animaton"
+++
<style>
.hvrbox,
.hvrbox * {
	box-sizing: border-box;
}
.hvrbox {
	position: relative;
	display: inline-block;
	overflow: hidden;
	max-width: 100%;
	height: auto;
}
.hvrbox img {
	max-width: 100%;
	max-height: 100%;
}
.hvrbox .hvrbox-layer_bottom {
	display: block;
}
.hvrbox .hvrbox-layer_top {
	opacity: 0;
	position: absolute;
	top: 0;
	left: 0;
	right: 0;
	bottom: 0;
	width: 100%;
	height: 100%;
	background: #2E86C1;
	color: #fff;
	padding: 15px;
	-moz-transition: all 0.4s ease-in-out 0s;
	-webkit-transition: all 0.4s ease-in-out 0s;
	-ms-transition: all 0.4s ease-in-out 0s;
	transition: all 0.4s ease-in-out 0s;
}
.hvrbox:hover .hvrbox-layer_top,
.hvrbox.active .hvrbox-layer_top {
	opacity: .9;
}
.hvrbox .hvrbox-text {
	text-align: center;
	font-size: 20px;
	font-style: bold;
	font-family: "Arial", Times, serif;
	display: inline-block;
	position: absolute;
	top: 50%;
	left: 50%;
	-moz-transform: translate(-50%, -50%);
	-webkit-transform: translate(-50%, -50%);
	-ms-transform: translate(-50%, -50%);
	transform: translate(-50%, -50%);
}
.hvrbox .hvrbox-text_mobile {
	font-size: 15px;
	border-top: 1px solid rgb(179, 179, 179); /* for old browsers */
	border-top: 1px solid rgba(179, 179, 179, 0.7);
	margin-top: 5px;
	padding-top: 2px;
	display: none;
}
.hvrbox.active .hvrbox-text_mobile {
	display: block;
}
</style>

<div class="hvrbox">
<a href="http://silatuva.wordpress.com">
	<img src="https://image.ibb.co/cdjV1w/image004.png" alt="Mountains" class="hvrbox-layer_bottom">
	<div class="hvrbox-layer_top">
		<div class="hvrbox-text">Designed the logo and created the Wordpress site for Students for Individual Liberty at UVA.</div>
	</div>
</div>


<hr>

<!-- The dots/circles 
<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
</div>-->

