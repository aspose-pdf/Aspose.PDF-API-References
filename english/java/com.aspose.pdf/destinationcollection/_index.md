---
title: DestinationCollection
second_title: Aspose.PDF for Java API Reference
description: Class represents the collection of all destinations a name tree mapping name strings to destinations see 12.3.2.3 Named Destinations and see 7.7.4 Name Dictionary in the pdf document.
type: docs
weight: 85
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
| [size()](#size--) | Gets the number of elements contained in the collection. |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the collection is read-only. |
| [get_Item(int index)](#get-Item-int-) | Gets the destination object by index. |
| [getPageNumber(String destinameName, boolean useCache)](#getPageNumber-java.lang.String-boolean-) | Returns the page number of destination by the name. |
| [getExplicitDestination(String destinameName, boolean useCache)](#getExplicitDestination-java.lang.String-boolean-) | Returns the explicit destination by the name. |
| [iterator()](#iterator--) | Returns the enumerator. |
| [indexOf(System.Collections.Generic.KeyValuePair<String,Object> value)](#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--) | Returns the index of destination in collection. |
| [contains(System.Collections.Generic.KeyValuePair<String,Object> value)](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--) | Determines whether this instance contains the object. |
| [copyTo(System.Collections.Generic.KeyValuePair<String,Object>[] array, int arrayIndex)](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object----int-) | Copies the elements of the collection to an Array, starting at a particular Array index. |
| [add(System.Collections.Generic.KeyValuePair<String,Object> item)](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--) | Adds the specified item. |
| [clear()](#clear--) | Collection is read-only. |
| [remove(System.Collections.Generic.KeyValuePair<String,Object> item)](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--) | Removes the specified item. |
### size() {#size--}
```
public int size()
```


Gets the number of elements contained in the collection.

**Returns:**
int - int value
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets a value indicating whether the collection is read-only.

**Returns:**
boolean - boolean value
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
### iterator() {#iterator--}
```
public System.Collections.IEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


Returns the enumerator.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - The enumerator.
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
