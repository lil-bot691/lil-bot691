- <!DOCTYPE html>

<html> 
<head> 

    <title>Exempel 1 navigation bar</title> 

    <meta charset = "utf-8" /> 

    <link href = "css/slider.css" rel="stylesheet" type="text/css" /> 

</head> 

<body> 

<!--wrapper börjar--> 

    <div class="wrapper"> 

    <header class="header"> 

        <h1>Min första hemsida</h1> 

    </header> 

    <header class="mainmenu"> 

        <ul> 

            <li><a href="home.html">Hem</a></li> 

            <li><a href="news.html">Nyheter</a></li> 

            <li><a href="contacts.html">kontakt</a></li> 

            <li><a href="about.html">Om</a></li> 

        </ul> 

    </header> 

    <div class="wrapper_2col"> 

    <div class="leftcol"> 

      <p> 

      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur id erat 

      et elit blandit lobortis a a neque. Fusce lacus nisi, vulputate quis vulputate 

      vel, aliquam vitae libero. Sed congue ligula quis turpis tincidunt ut 

      ultrices ante feugiat. Sed semper tortor fermentum ligula fringilla tristique. 

      Mauris lacinia venenatis commodo. Curabitur scelerisque pharetra facilisis. 

      Donec et iaculis nunc. Curabitur rhoncus iaculis diam, rutrum faucibus 

      magna cursus in. Vestibulum eu consectetur magna. 

      </p> 

      <p> 

        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed a augue id 

        leo scelerisque hendrerit non non dui. Integer condimentum quam sed tellus 

        ultricies a aliquam elit ornare. Curabitur ac libero et sapien feugiat 

        porta vitae sed lorem. In faucibus imperdiet neque, sit amet accumsan 

        ante elementum tincidunt. Proin tincidunt massa at leo tincidunt consectetur. 

        Sed consectetur ornare libero a sagittis. Pellentesque aliquet ipsum ante. 

        Sed eget tellus dui, eget sodales lectus. 

      </p> 

    </div><!--leftcol slutar--> 

    <div class="rightcol"> 

      <p> 

        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur id erat 

        et elit blandit lobortis a a neque. Fusce lacus nisi, vulputate quis vulputate 

        vel, aliquam vitae libero. Sed congue ligula quis turpis tincidunt ut 

        ultrices ante feugiat. Sed semper tortor fermentum ligula fringilla tristique. 

        Mauris lacinia venenatis commodo. Curabitur scelerisque pharetra facilisis. 

        Donec et iaculis nunc. Curabitur rhoncus iaculis diam, rutrum faucibus 

        magna cursus in. Vestibulum eu consectetur magna. 

      </p> 

      <p><img src="img/andreas.jpg" height="300" width="201" alt="Foto" /> 

        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed a augue id 

        leo scelerisque hendrerit non non dui. Integer condimentum quam sed tellus 

        ultricies a aliquam elit ornare. Curabitur ac libero et sapien feugiat 

        porta vitae sed lorem. In faucibus imperdiet neque, sit amet accumsan 

        ante elementum tincidunt. Proin tincidunt massa at leo tincidunt consectetur. 

        Sed consectetur ornare libero a sagittis. Pellentesque aliquet ipsum ante. 

        Sed eget tellus dui, eget sodales lectus. 

      </p> 

      <div class="push"></div> 

    </div><!--rightcol slutar--> 
       <img class="mySlides" src="Geg.jpg" alt="photo" style="width:100%">
       <img class="mySlides" src="Moja.jpg" alt="photo" style="width:100%">
       <img class="mySlides" src="Palla.jpg" alt="photo" style="width:100%">
       <img class="mySlides" src="Slime.jpg" alt="photo" style="width:100%">
       <img class="mySlides" src="Tugga.jpg" alt="photo" style="width:100%">
       <button class="slider-button display left"
   onclick="changeImage(-1)">&#129076;</button>
       <button class="slider-botton display-right"
   onclick="changeImage(-1)">&#129076;</button>
    </div><!--wrapper2col slutar-->

    <footer class="footer"> 

      <p>All rights reserved - &#169; Copyright</p> 

    </footer> 

    </div><!--wrapper slutar--> 
    

  </body> 

</html>
