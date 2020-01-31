# sfomuseum-data-faa-2019

2019 data from the FAA's Airport Status Web Service for SFO.

## Important

This is highly experiental work right now. If you are planning to try using it, for anything at all, understand that everything is in flux and subject to change and may still break along the way.

## Example

```
$> cat data/152/798/162/1/1527981621.geojson

{
  "id": 1527981621,
  "type": "Feature",
  "properties": {
    "date:cessation_lower":"2019-05-29",
    "date:cessation_upper":"2019-05-29",
    "date:inception_lower":"2019-05-29",
    "date:inception_upper":"2019-05-29",
    "edtf:cessation":"2019-05-29T01:22:53",
    "edtf:inception":"2019-05-29T01:22:53",
    "faa:credit":"http://weather.gov/",
    "faa:delay":false,
    "faa:delay_count":0,
    "faa:last_update":"Last Updated on May 29 2019, 12:56 am PDT",
    "faa:temperature_c":12.8,
    "faa:temperature_f":55,
    "faa:temperature_raw":"55.0 F (12.8 C)",
    "faa:visibility":6,
    "faa:wind_direction":"Southwest",
    "faa:wind_raw":"Southwest at 4.6",
    "faa:wind_speed":4.6,
    "geom:area":0.0,
    "geom:bbox":"-122.37,37.62,-122.37,37.62",
    "geom:latitude":37.62,
    "geom:longitude":-122.37,
    "iso:country":"US",
    "mz:hierarchy_label":1,
    "mz:is_current":0,
    "sfomuseum:placetype":"weather",
    "sfomuseum:uri":"2019/05/29/20190529T012253.json",
    "src:geom":"flysfo",
    "wof:belongsto":[
        102527513,
        85688637,
        102191575,
        85633793,
        85922583,
        102087579,
        554784711,
        102085387
    ],
    "wof:breaches":[],
    "wof:concordances":{
        "iata:code":"SFO",
        "icao:code":"KSFO"
    },
    "wof:country":"US",
    "wof:created":1559092973,
    "wof:geomhash":"6e11b039d229c1f441fd06b875619d83",
    "wof:hierarchy":[
        {
            "campus_id":102527513,
            "continent_id":102191575,
            "country_id":85633793,
            "county_id":102087579,
            "custom_id":1527981621,
            "locality_id":85922583,
            "postalcode_id":554784711,
            "region_id":85688637
        },
        {
            "campus_id":102527513,
            "continent_id":102191575,
            "country_id":85633793,
            "county_id":102085387,
            "custom_id":1527981621,
            "region_id":85688637
        }
    ],
    "wof:id":1527981621,
    "wof:lastmodified":1580494138,
    "wof:name":"FAA status for SFO, 2019-05-29T01:22:53",
    "wof:parent_id":102527513,
    "wof:placetype":"custom",
    "wof:repo":"sfomuseum-data-faa-2019",
    "wof:superseded_by":[],
    "wof:supersedes":[],
    "wof:tags":[]
},
  "bbox": [
    -122.37,
    37.62,
    -122.37,
    37.62
],
  "geometry": {"coordinates":[-122.37,37.62],"type":"Point"}
}
```

## License

This data is published under the [Community Data License Agreement – Permissive – Version 1.0](LICENSE) license, but we'd love a [shout-out](https://twitter.com/flysfo) and generally to hear what you're doing if you use the data.

## See also

* https://services.faa.gov/
* https://github.com/Federal-Aviation-Administration/ASWS