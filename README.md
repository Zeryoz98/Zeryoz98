<html> 


<head> 

  <script type="text/javascript" src="https://code.jquery.com/jquery-3.7.1.min.js"></script>

  <!--codice jquery-->
 <script type="text/javascript">
   
   jQuery(document).ready(function (){

      function scrollWin(anc){
      target = jQuery(anc);
        jQuery('html, body').animate({
          scrollTop: target.offset().top 
        }, 1000);
     }    

      jQuery(".menu1").click(function() {
        scrollWin("#section1");

      });


      jQuery(".menu2").click(function() {
        scrollWin("#section2");

      });


      jQuery(".menu3").click(function() {
        scrollWin("#section3");

      });

      jQuery(".menu4").click(function() {
        scrollWin("#section4");

      });

      jQuery(".menu5").click(function() {
        scrollWin("#section5");

      });



   });


 </script>
<!--codice jquery-->

<style>
  /* Stile per il menu di navigazione */
  nav {
      background-color: #333;
      overflow: hidden;
  }

  nav a {
      float: left;
      display: block;
      color: white;
      text-align: center;
      padding: 14px 20px;
      text-decoration: none;
  }

  nav a:hover {
      background-color: #ddd;
      color: black;
  }


 /*Footer*/
  
  footer {
            background-color: #333; /* Colore grigio scuro */
            color: #fff; /* Testo bianco */
            padding: 10px 0;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }


 /* Stili per i link */
 a {
            color: #d88430; /* Colore verde */
            text-decoration: none;
            transition: color 0.3s ease;
        }

        a:hover {
            color: #2e7d32; /* Cambia il colore al passaggio del mouse */
        }


</style>

  <title> AlfreCommunity </title>
  
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@200..700&display=swap" rel="stylesheet">

  <style type="text/css">
  body{ padding: 0px; margin: 0px;}

  .section{ width: 100%; height: 600px; }
 
  #section1{background-color: #ccc; text-align: center;}
  #section2{background-color: #ddd;}
  #section3{background-color: #ccc;}
  #section4{background-color: #ddd;}
  #section5{background-color: #ccc;}
 
  .flex{ display: flex; align-items: center; justify-content: center;}
  

  #menu{ width: 100%; height: 50px; background-color: #333; position: fixed;}
  #menu ul{ margin: 0px;}
  #menu li{ display: initial; margin: 0px 50px 0px 50px;}
  #menu{cursor: pointer; text-decoration: underline;}
  </style>



</head>

<body>    

<!--menu-->
  <div id="menu">
<nav>
  <a class="menu1">Home</a>
  <a class="menu2">Progetti</a>
  <a class="menu3">Collaborati</a>
  <a class="menu4">Contatti</a>
</nav>
 </div>
<!--menu-->


<!--contenuto-->
  <div id="section1" class="section flex" class="section"> 
  <div class="section-indoor">
    <img src="c:\Users\greco\OneDrive\Desktop\2012-06-02_155841_2480765.jpg";  style="height: 50%;"> 
    <h1 style="font-family: 'Oswald';">Benvenuto sul sito di Zeryoz98!</h1>
    <p> In questo sito troverete informazioni importantissime riguardanti il mio canale e dei miei progetti!</p>
    <p><a href="https://www.youtube.com/channel/UChpPq-BunNa_i2eYhVH00wg"> ecco qui il mio canale</a></p>
  </div>
  </div>
  
  <div id="section2" class="section"></div>
   
  <div id="section3" class="section"></div>

  <div id="section4" class="section"></div>

  <div id="section5" class="section"></div>

<!--contenuto-->



<footer>
  <p>&copy; 2024 Il Mondo del Gaming - AdventureCraft in corso</p>
</footer>




</body>



</html>

