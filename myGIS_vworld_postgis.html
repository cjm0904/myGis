<!doctype html>
<html lang="en">
  <head>

 	<script src="https://cdn.jsdelivr.net/gh/openlayers/openlayers.github.io@master/en/v6.5.0/build/ol.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/openlayers/openlayers.github.io@master/en/v6.5.0/css/ol.css" type="text/css">

    <style>
      .map {
        height: 800px;
        width: 100%;
      }
    </style>
    <title>OpenLayers example</title>
  </head>
    <body>
    <h2>My Map</h2>
    <div id="map" class="map"></div>
    <script type="text/javascript">

   	var format = 'image/png';
   	var layers = [

   		new ol.layer.Tile({
   			source : new ol.source.XYZ({
           url: 'http://xdworld.vworld.kr:8080/2d/Base/202002/{z}/{x}/{y}.png'
        }),
   		}),
   	
   		new ol.layer.Tile({
   			source: new ol.source.TileWMS({
  				url : 'http://localhost:8600/geoserver/cjmLayer/wms',
          params: {'FORMAT': format,
                   'VERSION': '1.1.1',  
                "STYLES": 'cjmPolygon',
                "LAYERS": 'cjmLayer:cjmPostGis',
                "exceptions": 'application/vnd.ogc.se_inimage',
                tilesOrigin: 746110.2515145557 + "," + 1458754.0441563274
          },
   				serverType: 'geoserver',
   				transition: 0,
   			}),
   		})
   	];
  
   	var projection = new ol.proj.Projection({
   		code: 'EPSG:4326', //지도의 좌표
   		units: 'degree',
   		global: false
   	});

   	var map = new ol.Map({
   		layers: layers,
   		target: 'map',
   		view: new ol.View({
//   			center:[14157148, 4509099], //(x, y) 동쪽으로 가려면 x를 크게, 북쪽으로 가려면 y를 크게
			center:[127,36],
  			zoom: 6,
  			projection: 'EPSG:4326'
   		}),
   	});


    </script>
  </body>
</html>
