# Claudrew

**Purpose:** To allow users to search for the nearest grocery store that contains a specific product in their inventory.

**Game Plan:**
- use the StoresByCityState method to get a list of stores within a certain distance. 
  - StoresByCityState returns the name of the store, the address, and store id
- use the GetGroceries method to find the exact name of the item the user is looking for. the user can choose their item from the list of item names returned by GetGroceries. this will narrorw down the search results hopefully.
  - GetGroceries returns the initial 10 items for autocomplete
- use the SearchForItem method to find out which stores carry the item we're looking for. and then pick the closest store that has our item

**Things to figure out:**
- How to get location of user
- Learn how to get information returned by the methods in XML format
- Should we try to make a mobile app version?
- basically how to do anything. halp. 

**Helpful links:**
- [Calculate distance between latitude longitude pairs with Python] (https://gist.github.com/rochacbruno/2883505)
  - maybe we can use the Python Geocoding Toolbox to do that ^ instead
- [Python Geocoding Toolbox] (https://geopy.readthedocs.io/en/1.10.0/)
  - [get latitude and longitude of supermarket based on its address] (https://geopy.readthedocs.io/en/1.10.0/#module-geopy.geocoders)
  - [calculate distance between two points] (https://geopy.readthedocs.io/en/1.10.0/#module-geopy.distance)
 - [An Introduction to using APIs] (https://www.dataquest.io/blog/python-api-tutorial/)
  - [the tutorial uses the HTTP Python library called 'Requests'] (http://www.python-requests.org/en/latest/)
 - [Another tutorial on 'How to use APIs with Python'] (https://www.codecademy.com/courses/python-intermediate-en-6zbLp/0/1) 
  
