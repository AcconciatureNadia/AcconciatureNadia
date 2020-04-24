# AcconciatureNadia
 
<!DOCTYPE html>
<html lang="it">
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1"/>
  <title>Parallax Template - Materialize</title>

  <!-- CSS  -->
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
  <link href="css/materialize.css" type="text/css" rel="stylesheet" media="screen,projection"/>
  <link href="css/style.css" type="text/css" rel="stylesheet" media="screen,projection"/>

  <!-- CAMBIO CARATTERE DEL BODY HTML, DA COPIARE DA FONTS ANCHE IN CSS --> 
  <link href="https://fonts.googleapis.com/css2?family=Raleway:wght@800&display=swap" rel="stylesheet">
  <!-- FONT AWESOME -->
  <link rel="stylesheet" href="font-awesome/css/font-awesome.min.css">
<!--Sharethis con nbanchini -->
  <script async src="https://platform-api.sharethis.com/js/sharethis.js#property=5e9dadc90ba0f9001938d54c&product=sticky-share-buttons"></script>
<head/>

<body>
	<!-- NAVBAR FISSA -->

  <div class="navbar-fixed">
    <nav>
      <div class="nav-wrapper white">
        <a href="#" class="brand-logo">Nadia Parrucchiera</a>
        <a href="#" data-target="mobile-demo" class="sidenav-trigger"><i class="material-icons">menu</i></a>
        <ul class="right hide-on-med-and-down">
          <li><a href="#servizio">Servizio</a></li>
          <li><a href="#registrazione">Perchè sceglierci?</a></li>
          <li><a href="#Ospita">Contattaci</a></li>
        </ul>
        <ul class="sidenav" id="mobile-demo">
    	  <li><a href="#servizio">Servizio</a></li>
          <li><a href="#registrazione">Perchè sceglierci?</a></li>
          <li><a href="#Ospita">Contattaci</a></li>
  		</ul>
      </div>
    </nav>
  </div>
   <!-- INTRO -->

  <div id="index-banner" class="parallax-container">
     <div class="section-intro no-pad-bot">
      <div class="container">
        <br><br>
        <h1 class="header center white-text">Diamoci un Taglio!.</h1>
        <div class="row center">
          <h5 class=" header-subtitle col s12 light">L'estate è alle porte, cosa aspetti a cambiare il tuo look</h5>
        </div>
        <div class="row center">
          <a href="#servizio" class="btn-large waves-effect waves-light red lighten1">Prenota un appuntamento</a>
        </div>
        <br><br>

      </div>
     </div>
     <div class="parallax"><img src="background1.jpg" alt="Unsplashed background img 1"></div>
  </div>

<!--   Servizio   -->

  <div id="servizio" class="container">
    <div class="section">
    	<div class= "col-servizio">

	      <!--   Icon Section   -->
	      <div class="row">
	        <div class="col s12 m4">
	          <div class="icon-block">
	            <h2 class="center red-text lighten1-text"><i class="material-icons">face</i></h2>
	            <h5 class="center">Cambiamo il tuo look</h5>
	            <br>

	            <h5 class="center light">Da noi potrai ricevere un trattamento esclusivo:
	            Taglio, colore, piega e colpi di sole che faranno di te una persona nuova.</h5>
	          </div>
	        </div>

	        <div class="col s12 m4">
	          <div class="icon-block">
	            <h2 class="center red-text lighten1-text"><i class="material-icons">map</i></h2>
	            <h5 class="center">Ecco dove puoi trovarci</h5>
	            <br>
	            <h5 class="center light">Ci trovi nel piccolo paesino di Brenta (VA) Piazza Garibaldi 6/A.
	            Non è difficile arivare, vieni a trovarci!.</h5>
	          </div>
	        </div>

	        <div class="col s12 m4">
	          <div class="icon-block">
	            <h2 class="center red-text lighten1-text"><i class="material-icons">attach_file</i></h2>
	            <h5 class="center">Esperienza ventennale</h5>
	            <br>
	            <h5 class="center light">Serviamo i nostri clienti dal lontano 1988 con i prodotti di migliore qualità presenti dul mercato.</h5>
	          </div>
	        </div>
	      </div> 
	      </div> 

    </div>
  </div>
<!--   Registrati  -->

  <div id="registrazione" class= "parallax-container valign-wrapper">
	    <div class="section-registrazione no-pad-bot">
	      <div class="container">
	        <div class="row center">
	          <i class="material-icons registrazione-icon">flight</i>
	          <h3 class=" col s12 light">Affidati a Nadia e Alberto e non ne rimarrai deluso!</h3>
	          <h5 class= " col s12">Cerchiamo sempre di accontentarti</h5>
	          <!--   inserire email in registrati -->
	          <div class="row">
	          		<!--   l6 è la largezza della colonna della mail... ofset-l3 sono 3 spostamenti di offset -->
	          		<div class="input-field col s12 l6 offset-l3">
	          		<!--   class ho aggiunto white per fare lo sfondo bianco e center per scrivere al centro e black-text per il colore del testo in cui si scriverà la mail...placeholder è per mettere una scritta nel box -->
	          			<input id="email" type="email" class="validate white center black-text" placeholder= "Inserisci qui la tua e-mail">
	          			<button class="btn btn-registrazione waves-effect waves-light red lighten-1" type="submit" name="action">Voglio registrarmi</button>
	    		   		<!--<i class="material-icons right">send</i> mette 
	    				l'icona vicino a voglio registrarmi dentroal riquadro -->
	    				<!--   la classe btn-registrazione regola la larghezza della colonna mail e la devo definire in CSS... in CSS 100% in modo che sia uguale a larghezza mail.... viene larga come mail perchè sopra ho messo l6 offeset-l3 -->
	      			</div>
	      		</div>
	       	</div>
	    </div>
   </div>
    <div class="parallax"><img src="background2.jpg" alt="Unsplashed background img 2"></div>
  </div>

  <!--Perchè sceglierci -->
  <div id="Perchè sceglierci" class="container">
	  <div class="section">

	     <div class="row">
	       		<div class="col s12 center">
		        	<i class="material-icons ospita-icon red-text 	lighten-1-text">place</i>
		         	<h3>Perchè sceglierci?</h3>
		         	<h5 class="col 12 ospita-subtitle">Siamo da anni leader nel settore. Siamo conosciuti per i nostri tagli e tinte superlative.<br>
		         	Il nostro obiettivo è quello di cambiare il tuo look e farti sentire a casa tua!<br>
		            Nadia è esperta nell'accapigliatura femminile, mentre Alberto si prende quotidianamente cura delle chiome e barbe della sua giovane clientela maschile! </h5>
		         	<button class="btn btn-recensione waves-effect waves-light red lighten-1" type="submit" name="action">Cosa pensi di noi?</button>
	       	 		</div>
	   		</div>
	  </div>
  </div>
 <!-- Footer -->
	<footer class="page-footer">
	  <!-- Footer cambio colore di fondo lovado a definire nel CSS però devo cancellare teal (qui sopra nella class) che è il colore verde predefinito da materialize -->
	   <div class="container">
	   	<div class="row">
	    	<div class="col12 l12 s12 center">
	       		<h5 class="white-text">Contattaci</h5>
	       		<a href="mailto:nbanchini@gmail.com" class="social-icon"><i class="fa fa-envelope"></i></a>
	       		<a href="https://www.facebook.com/vittorio.leonardi.3" target="_blank" class="social-icon"><i class="fa fa-facebook-official" aria-hidden="true"></i></a>
	       		<a href="https://www.facebook.com/vittorio.leonardi.3" target="_blank" class="social-icon"><i class="fa fa-instagram"></i></a>
	       		<!-- Taget fa aprire link in una nuova pagina -->
	     	</div>
	     </div>
	</div>
	<div class="footer-copyright">
	 	<div class="container">
	    	2019&copy <a class="brown-text text-lighten-3" target="_blank" href="https://www.facebook.com/vittorio.leonardi.3">VittorioLeonardi</a>
	    	</div>
	  </div>
	</footer>


  <!--  Scripts-->
  <script src="https://code.jquery.com/jquery-2.1.1.min.js"></script>
  <script src="js/materialize.js"></script>
  <script src="js/init.js"></script>

  </body>
</html>
