[Uploading mapa_entr<!DOCTYPE html>
<html>
<head>
    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_4bf28ac2f381a100a01358cb0faa971e {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
            </style>
        
    <script src="https://cdn.jsdelivr.net/gh/marslan390/BeautifyMarker/leaflet-beautify-marker-icon.min.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/marslan390/BeautifyMarker/leaflet-beautify-marker-icon.min.css"/>
</head>
<body>
    
    
            <div class="folium-map" id="map_4bf28ac2f381a100a01358cb0faa971e" ></div>
        
</body>
<script>
    
    
            var map_4bf28ac2f381a100a01358cb0faa971e = L.map(
                "map_4bf28ac2f381a100a01358cb0faa971e",
                {
                    center: [25.721956, -100.356569],
                    crs: L.CRS.EPSG3857,
                    zoom: 13,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_b1b97411bb001a33e230550e7f7e2195 = L.tileLayer(
                "https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",
                {"attribution": "Data by \u0026copy; \u003ca href=\"http://openstreetmap.org\"\u003eOpenStreetMap\u003c/a\u003e, under \u003ca href=\"http://www.openstreetmap.org/copyright\"\u003eODbL\u003c/a\u003e.", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_4bf28ac2f381a100a01358cb0faa971e);
        
    
            var marker_0bb9ca916d462cc7ce0d2a89bc37cf4d = L.marker(
                [25.721956, -100.356569],
                {}
            ).addTo(map_4bf28ac2f381a100a01358cb0faa971e);
        
    
            var beautify_icon_35be3be2e030cb672cb0af34931fd07c = new L.BeautifyIcon.icon(
                {"backgroundColor": "#FFF", "borderColor": "#2A81CB", "borderWidth": 3, "icon": "map-marker", "innerIconStyle": "", "isAlphaNumericIcon": false, "spin": false, "textColor": "#2A81CB"}
            )
            marker_0bb9ca916d462cc7ce0d2a89bc37cf4d.setIcon(beautify_icon_35be3be2e030cb672cb0af34931fd07c);
        
    
            marker_0bb9ca916d462cc7ce0d2a89bc37cf4d.bindTooltip(
                `<div>
                     Punto ATM (Ubicación exacta)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_b185c754504aafb9881784f2ea3bfa74 = L.circle(
                [25.721956, -100.356569],
                {"bubblingMouseEvents": true, "color": "#4CAF50", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#4CAF50", "fillOpacity": 0.1, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3000, "stroke": true, "weight": 3}
            ).addTo(map_4bf28ac2f381a100a01358cb0faa971e);
        
    
        var popup_b8aa55e5b67dab0e8a9502e6edfee638 = L.popup({"maxWidth": "100%"});

        
            var html_e45ec335070d2137c437f3be4745f618 = $(`<div id="html_e45ec335070d2137c437f3be4745f618" style="width: 100.0%; height: 100.0%;">3.0 km</div>`)[0];
            popup_b8aa55e5b67dab0e8a9502e6edfee638.setContent(html_e45ec335070d2137c437f3be4745f618);
        

        circle_b185c754504aafb9881784f2ea3bfa74.bindPopup(popup_b8aa55e5b67dab0e8a9502e6edfee638)
        ;

        
    
    
            var circle_28a2a8e4ff0e984aa904243b50282a18 = L.circle(
                [25.721956, -100.356569],
                {"bubblingMouseEvents": true, "color": "#FFC107", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FFC107", "fillOpacity": 0.1, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4000, "stroke": true, "weight": 3}
            ).addTo(map_4bf28ac2f381a100a01358cb0faa971e);
        
    
        var popup_e6f5a8945dd95129a403111b8ed19fec = L.popup({"maxWidth": "100%"});

        
            var html_165e1190b132930d28c224d48b607e68 = $(`<div id="html_165e1190b132930d28c224d48b607e68" style="width: 100.0%; height: 100.0%;">4.0 km</div>`)[0];
            popup_e6f5a8945dd95129a403111b8ed19fec.setContent(html_165e1190b132930d28c224d48b607e68);
        

        circle_28a2a8e4ff0e984aa904243b50282a18.bindPopup(popup_e6f5a8945dd95129a403111b8ed19fec)
        ;

        
    
    
            var circle_03d9a56ba9cfabe7283dd4f634f9d7d2 = L.circle(
                [25.721956, -100.356569],
                {"bubblingMouseEvents": true, "color": "#F44336", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#F44336", "fillOpacity": 0.1, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5000, "stroke": true, "weight": 3}
            ).addTo(map_4bf28ac2f381a100a01358cb0faa971e);
        
    
        var popup_a1d8a50101804c4ac1f6f842ed9a124a = L.popup({"maxWidth": "100%"});

        
            var html_fc2fe661ca81192f0d4a91813e16f709 = $(`<div id="html_fc2fe661ca81192f0d4a91813e16f709" style="width: 100.0%; height: 100.0%;">5.0 km</div>`)[0];
            popup_a1d8a50101804c4ac1f6f842ed9a124a.setContent(html_fc2fe661ca81192f0d4a91813e16f709);
        

        circle_03d9a56ba9cfabe7283dd4f634f9d7d2.bindPopup(popup_a1d8a50101804c4ac1f6f842ed9a124a)
        ;

        
    
</script>
</html>ega_actualizado.html…]()
