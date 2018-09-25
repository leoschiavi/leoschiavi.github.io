<!DOCTYPE HTML>

<html>

   <head>

   <title>Challenge: Guess the password</title>

      

   </head>

   <body>
    
   function Modulo() {
   var password = document.modulo.password.value;
	    var conferma = document.modulo.conferma.value; 
	if (password != conferma) {
		alert("Password errata, riprova.");
		document.modulo.conferma.value = "";
		document.modulo.conferma.focus();
		return false;
		
else {
		document.modulo.action = "elabora_dati.asp";
		document.modulo.submit();
	}
}	
            </body>

</html>
