Recall: The main goal is verify that the address from the main provider repository is correct. 
So, we want to compare its address with several other pilot datasets.
However, we cannot directly compare the address Strings as the same address can have slightly different format in two different datasets. 
Thus we need some method for address matching

Google Places API has the geolocation data (longtitude and latitude)
Google Places API: Give an address as String -> returns the geolocation
Rounding the geolocation to 3 digits after decimals. 
If they are the same, the addresses are for the same business/provider address. Thus, address is consistent. Vice Versa

