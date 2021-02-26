# Name
Strategy

# Problem
* We have a class the contains a collection of other objects.

* The clients or users of the class need to iterate over this collection of objects for different purposes, such as changing or removing a specific item in the collection.

* For this purpose, the class containing the collection should allow the clients to access the collection of objects.

# Solution
* The class containing the collection should implement the "Iterable <T>" interface, and specifically one method: Iterator<T> iterator() which returns back an object of type Iterator.

* The class containing the collection should have an internal class that implements "Iterator <T>" Interface, and specifically three methods: (a) T next(), (b) boolean hasNext (), and (c) void remove (). next () returns back the next element while iterating over the collection. hasNext () identifies whether the collection contains further elements to be iterated over or not. remove () removes the current element while iterating over the collection.


