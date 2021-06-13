# Collections Framework
### Interfaces in collection framework.
Collection, List, Set, Map, Queue, DeQueue, SortedMap, SortedSet.
### Which interfaces are used for sorting list of objects?
Comparator , Comparable
### Bulk Operations supported in collection.

* containsAll — returns true if the target Collection contains all of the elements in the specified Collection.
* addAll — adds all of the elements in the specified Collection to the target Collection.
* removeAll — removes from the target Collection all of its elements that are also contained in the specified Collection.
* retainAll — removes from the target Collection all its elements that are not also contained in the specified Collection. That is, it retains only those elements in the target Collection that are also contained in the specified Collection.
* clear — removes all elements from the Collection.

The addAll, removeAll, and retainAll methods all return true if the target Collection was modified in the process of executing the operation.

## ArrayList implementation of List
### Declaration of ArrayList class.
```java

public class ArrayList<E>
extends AbstractList<E>
implements List<E>, RandomAccess, Cloneable, Serializable

```
### Hierarchy of ArrayList class.
````java
java.lang.Object
java.util.AbstractCollection<E>
java.util.AbstractList<E>
java.util.ArrayList<E>
````
### Create Object of ArrayList.
````java
   List<String> list = new ArrayList<String>();
 // or if you are using JDK 7 or later — you can use the diamond operator:
   List<String> list = new ArrayList<>();
````
