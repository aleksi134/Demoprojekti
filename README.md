# Demoprojekti

Linked font families:
font-family: 'Arimo', sans-serif;
font-family: 'Hind', sans-serif;
font-family: 'Bitter', serif;
font-family: 'Lobster', cursive;
font-family: 'Noto Sans JP', sans-serif;
font-family: 'Mountains of Christmas', cursive;
font-family: 'Varela Round', sans-serif;
font-family: 'Acme', sans-serif;
font-family: 'Merriweather Sans', sans-serif;

font-family: 'Unlock', cursive;
font-family: 'Charm', cursive;
font-family: 'Major Mono Display', monospace;
font-family: 'Staatliches', cursive;
font-family: 'Abril Fatface', cursive;

$(document).ready(function(){
  $(".button a").click(function(){
      $(".overlay").fadeToggle(200);
     $(this).toggleClass('btn-open').toggleClass('btn-close');
  });
});
$('.overlay').on('click', function(){
  $(".overlay").fadeToggle(200);   
  $(".button a").toggleClass('btn-open').toggleClass('btn-close');
  open = false;
});

