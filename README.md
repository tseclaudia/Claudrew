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
