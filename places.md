# places json return for Eiffel Tower
https://maps.googleapis.com/maps/api/place/findplacefromtext/json?input=Eiffel%20Tower&inputtype=textquery&fields=photos,
formatted_address,name,rating,opening_hours,geometry&key=AIzaSyAUK9DsZZGaTMMpTshAtchs0St92GpjN7M

# valid response
{
   "candidates" : [
      {
         "formatted_address" : "Champ de Mars, 5 Avenue Anatole France, 75007 Paris, France",
         "geometry" : {
            "location" : {
               "lat" : 48.85837009999999,
               "lng" : 2.2944813
            },
            "viewport" : {
               "northeast" : {
                  "lat" : 48.85974697989273,
                  "lng" : 2.29610765
               },
               "southwest" : {
                  "lat" : 48.85704732010728,
                  "lng" : 2.29251745
               }
            }
         },
         "name" : "Eiffel Tower",
         "opening_hours" : {
            "open_now" : true
         },
         "photos" : [
            {
               "height" : 3173,
               "html_attributions" : [
                  "\u003ca href=\"https://maps.google.com/maps/contrib/105545434653517780666\"\u003eMd. Zarif Ahammed\u003c/a\u003e"
               ],
               "photo_reference" : "ATtYBwKnf-z9RjOXSIZn4OfAtKcEEUhElL1rdnOFBkweCAYl7Pix1Z4Y6TDmcUYWdOhtvFDy7iC0BTqNdIfS3YDba5rN5Ts-lka-cwcfxrybUsW2uV62DSB5QLhWiMKpggXIkgCLVAegUOyoheSJlSu_5xzzbJsEC2Yxfj8LPc0JByaL8QND",
               "width" : 4381
            }
         ],
         "rating" : 4.6
      }
   ],
   "status" : "OK"
}
