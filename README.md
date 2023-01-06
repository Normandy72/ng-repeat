* `ng-repeat` is a directive that extends the functionality of HTML elements it's applied to. 
* `ng-repeat` behaves very similarly to for-each construct in other languages. The way it works is, ng-repeat is an attribute on some element, and then you specify some item, which is a variable, in some collection, and collection should be some kind of a property. Usually the scope service and each item can now be used in interpolation as an item in the collection at a particular index of iteration.
* `ng-repeat`also exposes a special $index property to the body of its host tag. And what it does, is that $index holds the numeric index of the current item in the loop. And you're able to then use it in your interpolation or in some calculations inside of the HTML template.