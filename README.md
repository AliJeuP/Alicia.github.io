<!DOCTYPE html>

<html>
	<head>
		<meta charset="utf-8" />
		<title>plan_mine</title>
		<style>
			body {background-color: #322410;}
			button {background-color: #322410;}
		</style>
	</head>

	<body>
		<img src="image/titre_mine.png" width=90% />
		<br /> <br /> <br /> <br /> <br /> <br /> <br /> <br />
		<button onclick="showImage('image/rdc_mine.png')"> <img src="image/rdc_button.png" width=30% /> </button>
		<button onclick="showImage('image/-1_mine.png')"> <img src="image/-1_button.png" width=30% /> </button>
		<button onclick="showImage('image/-2_mine.png')"> <img src="image/-2_button.png" width=30% /> </button>
		<button onclick="showImage('image/-3_mine.png')"> <img src="image/-3_button.png" width=30% /> </button>
		<br /> <br />
		<button onclick="showImage('image/-4_mine.png')"> <img src="image/-4_button.png" width=30% /> </button>
		<button onclick="showImage('image/-5_-6_-7_mine.png')"> <img src="image/-5_-6_-7_button.png" width=30% /> </button>
		<button onclick="showImage('image/-8_-9_mine.png')"> <img src="image/-8_-9_button.png" width=30% /> </button>
		<br />
		<img src="image/legende_mine.png" width=20% />
		<img id="image" src="image/rdc_mine.png" width=60% align="center" />
		<img src="image/legende_speciale_mine.png" width=90% />
		
		<script>
			function showImage(image){
				var imageElement = document.getElementById("image")
				imageElement.src = image;
			}
		</script>
	</body>
</html>
