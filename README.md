## Website Performance Optimization portfolio project



## Optimizations step 1

|Global|replaced all querySelector() with getElementById()|getElementById() is less costly to call than querySelector()|
|Global|replaced all querySelectorAll() with getEntriesByName()|getEntriesByName() is less costly to call than querySelectorAll()|
|Global|Set length to an object, and used that to compare every time the for loop would iterate|Avoids checking length every time loop iterates|
Removed jQuery statement outside of for loop|jQuery is expensive to call, so it needs to be saved in an object.  This object is then used in the for loop.|
Used dx and newwidth for first pizza to set widths on all pizzas| All pizzas are same size, so there is no use checking every single pizza width.|

## Optimizations step 2

try deiffrent font code 
use critical css inline 
image optimize 

## Optimizations step 3
for some funtion that has for loop
i use variable outside & fixed starting point

## Optimizations step 4

i used 000webhost for speed test 

yes thats all
