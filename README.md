# Explore-Differences-Between-the-var-and-let-Keywords

var Keyword and let Keyword

One of the biggest problems with declaring variables with the var keyword is that you can easily overwrite variable declarations:

var camper = "James";
var camper = "David";
console.log(camper);


In the code above, the camper variable is originally declared as James, and is then overridden to be David. The console then displays the string David.
