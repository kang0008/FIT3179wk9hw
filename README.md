<!DOCTYPE html>
<html>
<head>
  <!-- Import Vega & Vega-Lite (does not have to be from CDN) -->
  <script src="https://cdn.jsdelivr.net/npm/vega@5.20.2"></script>
  <script src="https://cdn.jsdelivr.net/npm/vega-lite@5.1.0"></script>
  <script src="https://cdn.jsdelivr.net/npm/vega-embed@6.17.0"></script>
  
  <!-- CSS file -->
  <link rel="stylesheet" type="text/css" href="css/styles.css" media="all">


</head>
<body>
  
<div id="choropleth_map"></div>

<script type="text/javascript">

  var spec2 = "js/choropleth_map.vg.json";
  vegaEmbed('#choropleth_map', spec2).then(function(result) {
    // Access the Vega view instance (https://vega.github.io/vega/docs/api/view/) as result.view
  }).catch(console.error);
</script>

</body>
</html>

