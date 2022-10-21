**Block of Code Example**

<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 0; i <= 100; i++) {
		for (i = 0; i <= 100; i++){
		//Multiple of 3 and 5 = "Fizzbuzz"
			if (i % 3 === 0 && i % 5 ===0){
					result = "Fizzbuzz";
		//Multiple of 3 = "Fizz"
	}	else if (i % 3 === 0){
					result = "Fizz" ;
		//Multiple of 5 = "Buzz"
	}	else if (i % 5 === 0){
					result = "Buzz" ;
		//Not multiple of 3 and 5 = i
	}	else {
				result = i ;
			}
		displayHTML += "<p>" + result + "</p>";
	}
}
display.innerHTML = displayHTML
}

</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>


[Home](https://github.com/corinnees/corinnestevens/blob/main/README.md)
