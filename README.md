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


var marker;

function initMap() {
  var map = new google.maps.Map(document.getElementById('map'), {
    zoom: 13,
    center: {lat: 59.325, lng: 18.070}
  });

  marker = new google.maps.Marker({
    map: map,
    draggable: true,
    animation: google.maps.Animation.DROP,
    position: {lat: 59.327, lng: 18.067}
  });
  marker.addListener('click', toggleBounce);
}

function toggleBounce() {
  if (marker.getAnimation() !== null) {
    marker.setAnimation(null);
  } else {
    marker.setAnimation(google.maps.Animation.BOUNCE);
  }
}

    /*main code*/
        function initMap() {
          
          var Visio4= {lat: 62.598719, lng: 29.761152 };
          var map = new google.maps.Map(
              document.getElementById('map'), {zoom: 18, center: Visio4})
          var marker = new google.maps.Marker({position: Visio4, map: map});
        }
            </script>
            
            <script async defer
            src="https://maps.googleapis.com/maps/api/js?key=AIzaSyCQFtj_XwLrDeXg4JyTddNs7l2rASszcLY&callback=initMap">

        marker = new google.maps.Marker({
        map: map,
        draggable: true,
        animation: google.maps.Animation.DROP,
        position: {lat: 62.598719, lng: 29.761152}
  });
            marker.addListener('click', toggleBounce);
}

        function toggleBounce() {
            if (marker.getAnimation() !== null) {
            marker.setAnimation(null);
  }         else {
            marker.setAnimation(google.maps.Animation.BOUNCE);
  }
}


<div>
    <script>
        var marker;
    
        
    
    function initMap() {
      var map = new google.maps.Map(document.getElementById('map'), {
        zoom: 18,
        center: {lat: 62.598719, lng: 29.761152}
      });
    
      marker = new google.maps.Marker({
        map: map,
        draggable: true,
        animation: google.maps.Animation.DROP,
        position: {lat: 62.598719, lng: 29.761152}
      });
      marker.addListener('click', toggleBounce);
    }
    
    function toggleBounce() {
      if (marker.getAnimation() !== null) {
        marker.setAnimation(null);
      } else {
        marker.setAnimation(google.maps.Animation.BOUNCE);
      }
    }
    
    </script>
</div>

AIzaSyCQFtj_XwLrDeXg4JyTddNs7l2rASszcLY