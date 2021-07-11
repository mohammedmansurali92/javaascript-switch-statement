# javaascript-switch-statement
JavaScript Multipool case switch statement 

		<body>
		<p id="demo"></p>
	<script>
		//digit spelling
		//0-zero, one-1...9-nine, 10 not a valid digit
		//switch, case, break, default
		var letter= prompt("Enter any letter :");
		letter= letter.toLowerCase();
		switch(letter){
			case "a":
			case "e":
			case "i":
			case "o":
			case "u":
			document.write("Vowel");
			break;
			
			default:
			document.write("Consonent");
		};
		</script>
	</body>
		
