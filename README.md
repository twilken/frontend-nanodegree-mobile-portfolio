### Getting started

* Clone the repository
* Open index.html in your browser


### Optimizations

* Made pizzeria image smaller
* Made analytics.js script load async
* Embedded print stylesheet into screen stylesheet
* Removed google font
* Inline style.css
* Refactor pizza scroll position movement
* Refactor pizza resizing to not trigger forced layout
* Changed number of floating pizzas
* Don't recalculate dx and newwidth for every pizza
* Try out strict mode for changePizzaSizes function
* Replace querySelector with getElementById in changeSliderLabel function
* Set windowWidth variable using getElementById instead of querySelector
* Only query #randomPizzas once when creating pizzas
* Use getElementsByClassName insdead of querySelectorAll to get items in updatePositions function
* Only calculate 5 phases for pizzas
* Batch style updates for pizza positions
* Move elem variable declaration out of loop when generating the sliding pizzas on page load
* When generating sliding pizzas only query #movingPizzas1 once outside the loop with getElementById
