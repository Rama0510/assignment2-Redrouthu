# ramadevi redrouthu
###### Favourite museum to visit is Louvre museum.

**Mona Lisa** painting by the artist **Leonardo Da Vinci** is a must see exhibit in the museum.

**The Louvre’s painting collection is one of the richest in the world, representing all periods of European art up to the Revolutions of 1848.**

***

### Ordered List Section :

The nearest airport to The Louvre Museum is Paris Orly (ORY) Airport.

1. Two ways to reach museum from airport :
    1. Taxi
    2. Bus

2. Taxi will take around 18mins and will cost 30-40€.
3. The bus (68 bus) from will take around 1hr and will cost 9€.

* Other locations to visit :
    * Seine River
    * Right Bank
    * Palais Royal
    * City Cafe

    The Louvre’s painting collection is one of the richest in the world, representing all periods of **European art up to the Revolutions of 1848.**

    ***[AboutMe.md](AboutMe.md)***

   ***4 Cities I highly recommend visiting :***


|  Name of City  | Place to Visit | Time to Spend |
| :------------ | :------------: | :-----------: |
| 1. New Zealand    | South Island   | 5 hours       |
| 2. Paris          | Eiffel Tower   | 3 hours       |
| 3. Arizona        | Grand Canyon   | 1 day         |
| 4. Italy          |  Rome          | 3 days        |

---
<br>

## Motivational Quotes

> ***"Discipline is the bridge between goal and accomplishment."***

~ Emilia Earhart

<br>

>***"Difficult roads often lead to beautiful destinations."***

~ Abraham Lincoln

--- 

## Code Fencing Section: <br>

>What is it in SVG file?


Stackoverflow link<https://stackoverflow.com/questions/50537363/what-is-it-in-svg-file>

```
<svg width="100%" height="100%">
  
  <!-- Create mask that we'll use to define a slight gradient -->
  <mask maskUnits="userSpaceOnUse" id="fade">
    <!-- Here's that slight gradient -->
     	<linearGradient id="gradient" x1="0" y1="0" x2="0" y2="100%">
      <stop offset="0" style="stop-color: #FFFFFF"></stop>
      <stop offset="1" style="stop-color: #000000"></stop>
    </linearGradient>
    <!-- The canvas for our mask -->
    <rect fill="url(#gradient)" width="100%" height="100%"></rect>
  </mask>
    
  <!-- Let's define the pattern -->
  <!-- The width and height should be double the circle radius we plan to use -->
  <pattern id="pattern-circles" x="0" y="0" width="40" height="40" patternUnits="userSpaceOnUse">
    <!-- Now let's draw the circle -->
    <!-- We're going to define the `fill` in the CSS for flexible use -->
    <circle mask="url(#fade)" cx="20" cy="20" r="20"></circle>
  </pattern>
  <!-- The canvas with our applied pattern -->
  <rect x="0" y="0" width="100%" height="100%" fill="url(#pattern-circles)"></rect>
  
</svg>

```
snippet source<https://css-tricks.com/snippets/svg/svg-patterns/#aa-circle-pattern>


