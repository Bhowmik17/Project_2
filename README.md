# Project_2
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Coffee Leaflet</title>

   <!-- Leaflet CSS & JS -->
   <link rel="stylesheet" href="https://unpkg.com/leaflet@1.3.3/dist/leaflet.css"
   integrity="sha512-Rksm5RenBEKSKFjgI3a41vrjkw4EVPlJ3+OiI65vTjIdo9brlAacEuKOiQ5OFh7cOI1bkDwLqdLw3Zg0cRJAAQ=="
   crossorigin=""/>

   <script src="https://unpkg.com/leaflet@1.3.3/dist/leaflet.js"
   integrity="sha512-tAGcCfR4Sc5ZP5ZoVz0quoZDYX5aCtEm/eu1KhSLj2c9eFrylXZknQYmxUssFaVJKvvc0dJQixhGjG2yXWiV9Q=="
   crossorigin=""></script>
  <!-- Our CSS -->
  <link rel="stylesheet" type="text/css" href="styles/style.css">
</head>

<body>

    <!-- header -->
    <div class="jumbotron">
        <div class="container">
            <h1>The Coffee Belt: A World Map of the Major Coffee Producers</h1>
            <p>The map below consists of two years of historical data gathered by the International Coffee Organization for 56 of its member
                nations. The size of the circles is proportional to the quantity of coffee produced. Export values are represented by a color 
                scale in which lighter-colored countries export more coffee than darker-colored countries. The plot also depicts
                 the coffee belt, a region of the world comprised of the major coffee growing countries, all of which are tucked 
                between the Tropics of Cancer and Capricorn. From Africa where it originated, the cultivation of coffee has expanded to 
                the East and to the West to form what is known as The Bean Belt. Click the circles for additional information.  
            </p>
        </div>
    </div>
  
    </div class="container-fluid">
        <!-- map -->
        <div class="panel panel-default">
            <div class="panel-body">
                <div style="text-align: center"></div>
            </div>
        </div>
    </div>

  <!-- The div that holds our map -->
  <div id="map"></div>


  <!-- D3 JavaScript -->
  <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/d3/4.2.3/d3.min.js"></script>
  <!-- Our JavaScript -->
  <script type="text/javascript" src="js/config.js"></script>
  <script type="text/javascript" src="js/logic.js"></script>

</body>

  </html>
