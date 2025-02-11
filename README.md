## **Middle Earth's Best Routes**
---
In this project, data representing fictitious geographical features of Middle-earth, a portion of J.R.R Tolkien's universe, was collected. These datasets, crafted by the [ME-DEM](https://github.com/jvangeld/ME-GIS) project team and amalgamated with a map by [bburns](https://github.com/bburns/Arda), encompass information on roads, rivers, contour lines, coastlines, terrain classifications, cities, and various other diverse elements.
<p>
The project's ultimate goal is to analyze the optimal routes for two expeditions. The first pertaining to Thorin Oakenshield's company, which took Bilbo from the Shire to Rivendell and then from Rivendell to the Lonely Mountain of Erebor. The second expedition involved Frodo's mission to destroy the ring, leading from the Shire to Rivendell and then from Rivendell to Mount Doom in Mordor.
<p>
Two analyses were conducted to determine the best path for each scenario. One considered only the roadways, trying to find the Shortest Path via roads. The other calculated the path of least elevation cost, essentially finding the flattest and most navigable route(in sum).

---

### **Images**

Paths for Bilbo -     Green: Path of least cost/Pink: Shortest path via roads.
<p>
  
![bilboRoutes(1)](https://github.com/Lorenzovagliano/GeoMiddleEarth/assets/111889654/31996a2e-e707-4e88-a6ed-6dd4053a9ba3)
<p>
Paths for Frodo -     Blue: Path of least cost/Red: Shortest path via roads.
<p>
  
![FrodoRoutes(1)](https://github.com/Lorenzovagliano/GeoMiddleEarth/assets/111889654/b2411aa4-142c-4a11-86bb-2f7f92c1e130)

---
  
### **Conclusions**
Ultimately, the paths of least cost closely mirrored the routes actually taken by the characters, which can be referenced on the interactive map available on the [Lotrproject](http://lotrproject.com/map/) website.
<p>
Since both expeditions were looking to avoid roads at one point or another, we can also conclude that the path of least cost is more appropriate.
