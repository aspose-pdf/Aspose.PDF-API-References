---
title: ArtifactCollection
second_title: Aspose.PDF for Java API Reference
description: Class represents artifact collection.
type: docs
weight: 27
url: /java/com.aspose.pdf/artifactcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.ICollection
```
public class ArtifactCollection implements System.Collections.ICollection
```

Class represents artifact collection.
## Methods

| Method | Description |
| --- | --- |
| [isSynchronized()](#isSynchronized--) |  |
| [size()](#size--) | Gets count of artifacts in collection. |
| [getSyncRoot()](#getSyncRoot--) | Gets synchronization object of the collection. |
| [copyTo(System.Array dest, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies colection into an array. |
| [iterator()](#iterator--) | Gets enumerator for the collection. |
| [getItem(int index)](#getItem-int-) | Gets artifact by index. |
| [add(Artifact artifact)](#add-com.aspose.pdf.Artifact-) | Adds artifacts to the collection. |
| [findByValue(String name, String expectedValue)](#findByValue-java.lang.String-java.lang.String-) | Finds artifacts by custom value. |
| [delete(Artifact artifact)](#delete-com.aspose.pdf.Artifact-) | Deletes specified artifact. |
| [update(Artifact artifact)](#update-com.aspose.pdf.Artifact-) |  |
| [delete(int index)](#delete-int-) | Removes artifact with specified index. |
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```




**Returns:**
boolean
### size() {#size--}
```
public int size()
```


Gets count of artifacts in collection.

**Returns:**
int
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets synchronization object of the collection.

**Returns:**
java.lang.Object
### copyTo(System.Array dest, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array dest, int index)
```


Copies colection into an array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dest | com.aspose.ms.System.Array |  |
| index | int |  |

### iterator() {#iterator--}
```
public System.Collections.IEnumerator iterator()
```


Gets enumerator for the collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator
### getItem(int index) {#getItem-int-}
```
public Artifact getItem(int index)
```


Gets artifact by index. Index is started from 1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of the artifact. |

**Returns:**
[Artifact](../../com.aspose.pdf/artifact) - Artifact on the page.
### add(Artifact artifact) {#add-com.aspose.pdf.Artifact-}
```
public void add(Artifact artifact)
```


Adds artifacts to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| artifact | [Artifact](../../com.aspose.pdf/artifact) | Artifact which sould be added to collection. |

### findByValue(String name, String expectedValue) {#findByValue-java.lang.String-java.lang.String-}
```
public System.Collections.IList findByValue(String name, String expectedValue)
```


Finds artifacts by custom value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of custom value. |
| expectedValue | java.lang.String | Value to find. |

**Returns:**
com.aspose.ms.System.Collections.IList - List of artifacts with requried value.
### delete(Artifact artifact) {#delete-com.aspose.pdf.Artifact-}
```
public void delete(Artifact artifact)
```


Deletes specified artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| artifact | [Artifact](../../com.aspose.pdf/artifact) | Artifact Object |

### update(Artifact artifact) {#update-com.aspose.pdf.Artifact-}
```
public void update(Artifact artifact)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| artifact | [Artifact](../../com.aspose.pdf/artifact) |  |

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


Removes artifact with specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of artifactg which must be removed. |

