# Data
In the creating usuful data for Toronto cities I obtained postal-code datas from wikipedia page (scrapping) - https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M - after getting data I made some modifications such as grouping by post codes and remove all duplicates. And also replace 'not assigned' type boroughs with neighbourhoods for more accuracy. Later on I got geospatial data (latitude and longtude of locations). Then I merge both data sheets aqccording to postal codes. After all I created maps via geographical coordinates. Now time to get foursquare data for finding top ten common venues. Then making clusters with post codes and the most common venues. Then showing all of them in mutual map.