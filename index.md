<!DOCTYPE html>
<html>
<head>
	<meta charset = "utf-8">
	<meta name = "viewport" content = "width=device-width, initial-scale=1">
	<title>Our Menu</title>
	<style>
		/************BASE STYLES**********/
		* { 
		box-sizing: border-box;
		}
		div {
			margin: 10px;
		}
		h1 {
		 	margin-bottom: 15px;
		}
		section {
			position: absolute;
			padding-left: 15px;
			padding-right: 15px;
			top: 0;
			right: 0;
			font-family: Roboto;
			background-color: #df0505;
			font-size: 25px;
			border: 1px black;
			text-align: center;

		}
		p { 
			padding-top: 30px;
			padding-bottom: 10px;
			margin: 10px;
			width: 90%;
			margin-right: auto;
			margin-left: auto;
			font-family: Helvetica;
			border: 1px black;
			text-align: left;
			color: #21a8e1;
		}
		div#container {
			background-color: #03374d;
			position: relative;
			top: 60px;
		}

		 /**Simple responsive frameowkrk. */
		.row{
		 	width: 100%;
		 	align-content: center;

		}
		/**Large devices only**/
		@media (min-width: 992px){
			.col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
				float: left;
				border: 1px solid green;
			}
			.col-lg-1 {
				width: 8.33%;
			}
			.col-lg-2{
				width: 16.66%;
			}
			.col-lg-3{
				width: 25%;
			}
			.col-lg-4 {
				width: 32%;
			}
			.col-lg-5 {
				width: 41.66%;
			}
			.col-lg-6 {
				width: 50%;
			}
			.col-lg-7 {
				width: 58.33%;
			}
			.col-lg-8 {
				width: 66.66%;
			}
			.col-lg-9 {
				width: 74.99%;
			}
			.col-lg-10 {
				width: 83.33%;
			}
			.col-lg-11 {
				width: 91.66%;
			}
			.col-lg-12 {
				width: 100%;
			}
		}
		/**Medium devices only**/
		@media (min-width: 768px) and (max-width: 991px){
			.col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
				float: left;
				border: 1px solid black;
			}
			.col-md-1 {
				width: 8.33%;
			}
			.col-md-2{
				width: 16.66%;
			}
			.col-md-3{
				width: 25%;
			}
			.col-md-4 {
				width: 33%;
			}
			.col-md-5 {
				width: 45%;
			}
			.col-md-6 {
				width: 50%;
			}
			.col-md-7 {
				width: 58.33%;
			}
			.col-md-8 {
				width: 66.66%;
			}
			.col-md-9 {
				width: 74.99%;
			}
			.col-md-10 {
				width: 83.33%;
			}
			.col-md-11 {
				width: 92.5%;
			}
			.col-md-12 {
				width: 100%;
			}
		}
				@media (max-width: 768px){
			.col-sm-1,{
				float: left;
				border: 1px solid black;
			}
			.col-sm-1 {
				width: 95%;
			}
		}
	</style>
</head>
<body>
	<h1 align = "center">Our Menu</h1>
	<div class = "row">
		<div id = "container" class = "col-lg-4 col-md-5 col-sm-1"><section>Chicken</section><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p></div>
		<div id = "container" class = "col-lg-4 col-md-5 col-sm-1"><section>Beef</section><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p></div>		
		<div id = "container" class = "col-lg-4 col-md-11 col-sm-1"><section>Sushi</section><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p></div>		
	</div>
</body>
</html>
