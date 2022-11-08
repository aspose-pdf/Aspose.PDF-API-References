---
title: DestinationCollection
second_title: Aspose.PDF for Java API Reference
description: Class represents the collection of all destinations a name tree mapping name strings to destinations see 12.3.2.3 Named Destinations and see 7.7.4 Name Dictionary in the pdf document.
type: docs
weight: 84
url: /java/com.aspose.pdf/destinationcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class DestinationCollection implements Iterable<System.Collections.Generic.KeyValuePair<String,Object>>
```

Class represents the collection of all destinations (a name tree mapping name strings to destinations (see 12.3.2.3, "Named Destinations") and (see 7.7.4, "Name Dictionary")) in the pdf document.
## Methods

| Method | Description |
| --- | --- |
| [add(System.Collections.Generic.KeyValuePair<String,Object> item)](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--) | Adds the specified item. |
| [clear()](#clear--) | Collection is read-only. |
| [contains(System.Collections.Generic.KeyValuePair<String,Object> value)](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--) | Determines whether this instance contains the object. |
| [copyTo(System.Collections.Generic.KeyValuePair<String,Object>[] array, int arrayIndex)](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object----int-) | Copies the elements of the collection to an Array, starting at a particular Array index. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExplicitDestination(String destinameName, boolean useCache)](#getExplicitDestination-java.lang.String-boolean-) | Returns the explicit destination by the name. |
| [getPageNumber(String destinameName, boolean useCache)](#getPageNumber-java.lang.String-boolean-) | Returns the page number of destination by the name. |
| [get_Item(int index)](#get-Item-int-) | Gets the destination object by index. |
| [hashCode()](#hashCode--) |  |
| [indexOf(System.Collections.Generic.KeyValuePair<String,Object> value)](#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--) | Returns the index of destination in collection. |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the collection is read-only. |
| [iterator()](#iterator--) | Returns the enumerator. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(System.Collections.Generic.KeyValuePair<String,Object> item)](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--) | Removes the specified item. |
| [size()](#size--) | Gets the number of elements contained in the collection. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(System.Collections.Generic.KeyValuePair<String,Object> item) {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--}
```
public void add(System.Collections.Generic.KeyValuePair<String,Object> item)
```


Adds the specified item. Collection is read-only. Always throws NotSupportedException exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object> | The item. |

### clear() {#clear--}
```
public void clear()
```


Collection is read-only. Always throws NotSupportedException exception.

### contains(System.Collections.Generic.KeyValuePair<String,Object> value) {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--}
```
public boolean contains(System.Collections.Generic.KeyValuePair<String,Object> value)
```


Determines whether this instance contains the object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object> | The value to find. |

**Returns:**
boolean -  true  if [contains] [the specified value]; otherwise,  false .
### copyTo(System.Collections.Generic.KeyValuePair<String,Object>[] array, int arrayIndex) {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object----int-}
```
public void copyTo(System.Collections.Generic.KeyValuePair<String,Object>[] array, int arrayIndex)
```


Copies the elements of the collection to an Array, starting at a particular Array index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>[] | The one-dimensional Array that is the destination of the elements copied from collection |
| arrayIndex | int | The zero-based index in array at which copying begins. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExplicitDestination(String destinameName, boolean useCache) {#getExplicitDestination-java.lang.String-boolean-}
```
public ExplicitDestination getExplicitDestination(String destinameName, boolean useCache)
```


Returns the explicit destination by the name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destinameName | java.lang.String | The name of destination. |
| useCache | boolean | Determines whether cached version of collection is used or not. |

**Returns:**
[ExplicitDestination](../../com.aspose.pdf/explicitdestination) - The ExplicitDestination object for destination found; otherwise, null.
### getPageNumber(String destinameName, boolean useCache) {#getPageNumber-java.lang.String-boolean-}
```
public int getPageNumber(String destinameName, boolean useCache)
```


Returns the page number of destination by the name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destinameName | java.lang.String | The name of destination. |
| useCache | boolean | Determines whether cached version of collection is used or not. |

**Returns:**
int - The page number if destination was found; otherwise, -1.
### get_Item(int index) {#get-Item-int-}
```
public System.Collections.Generic.KeyValuePair<String,Object> get_Item(int index)
```


Gets the destination object by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index of destination to get. |

**Returns:**
[KeyValuePair](../../com.aspose.ms.system.collections.generic/keyvaluepair) - Destination.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indexOf(System.Collections.Generic.KeyValuePair<String,Object> value) {#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--}
```
public int indexOf(System.Collections.Generic.KeyValuePair<String,Object> value)
```


Returns the index of destination in collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object> | The value to find. |

**Returns:**
int - The index of destination in collection.
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets a value indicating whether the collection is read-only.

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
public System.Collections.IEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


Returns the enumerator.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - The enumerator.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(System.Collections.Generic.KeyValuePair<String,Object> item) {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--}
```
public boolean remove(System.Collections.Generic.KeyValuePair<String,Object> item)
```


Removes the specified item. Collection is read-only. Always throws NotSupportedException exception.

not supportd yet.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object> | The item. |

**Returns:**
boolean - boolean value
### size() {#size--}
```
public int size()
```


Gets the number of elements contained in the collection.

**Returns:**
int - int value
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

