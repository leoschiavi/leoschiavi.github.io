	<script>
	<!--
function Modulo() {
var password = document.modulo.password.value;
    var conferma = document.modulo.conferma.value;
   
   if ((password == "") || (password == "undefined")) {
        alert("Il campo Password è obbligatorio.");
        document.modulo.password.focus();
        return false;
    }
    
  else if ((conferma == "") || (conferma == "undefined")) {
        alert("Il campo Conferma password è obbligatorio.");
        document.modulo.conferma.focus();
        return false;
    }
    
   else if (password != conferma) {
        alert("La password confermata è diversa da quella scelta, controllare.");
        document.modulo.conferma.value = "";
        document.modulo.conferma.focus();
        return false;
    }
    
   else {
        document.modulo.action = "elabora_dati.asp";
        document.modulo.submit();
    }
}
</script>
