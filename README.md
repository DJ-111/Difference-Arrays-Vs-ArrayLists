# Difference-Arrays-Vs-ArrayLists
README

ArrayLists:
  ArrayLists are part of Java's "java.util" package and provide a resizable array implementation.
  Unlike arrays, ArrayLists can dynamically grow and shrink as elements are added or removed.
  They provide more flexibility than arrays but come with a bit more overhead. 
  Code example: "ArrayList<Integer> myArrayList = new ArrayList<>();"

Arrays:
  Arrays are a fundamental data structure in Java that store a fixed-size sequence of elements of the same type.
  Each element in the array is accessed by its numerical index, starting from 0.
  Arrays are efficient for storing and accessing a known number of elements.
  Syntax example: "int[] myArray = new int[10];"


 Differences:
   Size:
       Arrays have a fixed size, whereas ArrayLists are dynamic.
   Performance:
       Arrays are generally faster because they are of fixed size and have less overhead. ArrayLists, while more flexible, can be slower due to resizing and autoboxing/unboxing.
   Type: 
       Arrays can hold primitives and objects, but ArrayLists can only hold objects (though Java autoboxing makes it easy to use primitives in ArrayLists).
   Utility: 
       ArrayLists come with many utility methods like ( add(), remove(), contains() ) that are not available with plain arrays.  
