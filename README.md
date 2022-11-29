# Javascipt--Clock
Javascript programming language to build Clock
Javascript clock code:
<!DOCTYPE html>
	<html lang="en">
	  <head>
	    <meta charset="UTF-8" />
	    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
	    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
	    <link rel="stylesheet" href="style.css" />
	    <title>Clock</title>
	  </head>
	  <body>
	    <div class="clock">
	      <div class="numbers">
	        <div class="twelve">12</div>
	        <div class="three">3</div>
	        <div class="six">6</div>
	        <div class="nine">9</div>
	      </div>
	      <div class="arrows">
	        <div class="hour"></div>
	        <div class="minute"></div>
	        <div class="second"></div>
	      </div>
	      <img
	        src="https://upload.wikimedia.org/wikipedia/en/thumb/9/95/Rolex_logo.svg/1200px-Rolex_logo.svg.png"
	        alt=""
	      />
	    </div>
	    <script src="index.js"></script>
	  </body>
	</html>



body {
	  margin: 0;
	  padding: 0;
	  font-family: 'Courier New', Courier, monospace;
	  height: 100vh;
	  display: flex;
	  justify-content: center;
	  align-items: center;
	  background-color: salmon;
	}
	

	img {
	  position: absolute;
	  top: 60px;
	  left: 50%;
	  transform: translateX(-50%);
	  width: 70px;
	  z-index: 2;
	}
	

	.clock {
	  width: 350px;
	  height: 350px;
	  background-color: lightgray;
	  border-radius: 100%;
	  border: 5px solid darkgrey;
	  box-shadow: 1px 1px 4px rgba(0,0,0,.7);
	  position: relative;
	}
	

	

	

	.numbers div {
	  position: absolute;
	  font-size: 27px;
	  font-weight: bold;
	  color: lightgoldenrodyellow;
	  text-shadow: 1px 1px 2px rgba(0,0,0,.7);
	}
	

	.twelve {
	  top: 6px;
	  left: 50%;
	  transform: translateX(-50%);
	}
	

	.three {
	  right: 6px;
	  top: 50%;
	  transform: translateY(-50%);
	}
	

