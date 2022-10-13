---
title: DestinationCollection
second_title: Aspose.PDF for Java API Reference
description: Class represents the collection of all destinations a name tree mapping name strings to destinations see 12.3.2.3 Named Destinations and see 7.7.4 Name Dictionary in the pdf document.
type: docs
weight: 74
url: /java/com.aspose.pdf/destinationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.ReadOnlyCollectionBase
```
public final class DestinationCollection extends System.Collections.ReadOnlyCollectionBase
```

Class represents the collection of all destinations (a name tree mapping name strings to destinations (see 12.3.2.3, "Named Destinations") and (see 7.7.4, "Name Dictionary")) in the pdf document.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the destination object by index. |
| [getPageNumber(String destinameName, boolean useCache)](#getPageNumber-java.lang.String-boolean-) | Returns the page number of destination by the name. |
| [getExplicitDestination(String destinameName, boolean useCache)](#getExplicitDestination-java.lang.String-boolean-) | Returns the explicit destination by the name. |
| [iterator()](#iterator--) | Returns the enumerator. |
| [indexOf(Object value)](#indexOf-java.lang.Object-) | Returns the index of destination in collection. |
| [contains(Object value)](#contains-java.lang.Object-) | Determines whether a destination is in collection or not. |
| [size()](#size--) | Destinations count |
### get_Item(int index) {#get-Item-int-}
```
public Object get_Item(int index)
```


Gets the destination object by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index of destination to get. |

**Returns:**
java.lang.Object - Destination.
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
public System.Collections.IEnumerator iterator()
```


Returns the enumerator.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - The enumerator.
### indexOf(Object value) {#indexOf-java.lang.Object-}
```
public int indexOf(Object value)
```


Returns the index of destination in collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | The value to find. |

**Returns:**
int - The index of destination in collection.
### contains(Object value) {#contains-java.lang.Object-}
```
public boolean contains(Object value)
```


Determines whether a destination is in collection or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | The value to find. |

**Returns:**
boolean - True if a destination is in collection; otherwise, false.
### size() {#size--}
```
public int size()
```


Destinations count

**Returns:**
int - int value
