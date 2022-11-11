---
title: AnnotationCollection
second_title: Aspose.PDF for Java API Reference
description: Class representing annotation collection.
type: docs
weight: 17
url: /java/com.aspose.pdf/annotationcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class AnnotationCollection implements Iterable<Annotation>
```

Class representing annotation collection.
## Constructors

| Constructor | Description |
| --- | --- |
| [AnnotationCollection(Page page)](#AnnotationCollection-com.aspose.pdf.Page-) | Constructor of AnnotationCollection. |
## Methods

| Method | Description |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor to process annotation. |
| [add(Annotation annotation)](#add-com.aspose.pdf.Annotation-) | Adds annotation to the collection. |
| [add(Annotation annotation, boolean considerRotation)](#add-com.aspose.pdf.Annotation-boolean-) | Adds annotation to the collection. |
| [clear()](#clear--) | Deletes all annotations from the collection. |
| [contains(Annotation annotation)](#contains-com.aspose.pdf.Annotation-) | Checks if specified annotation belong to collection. |
| [copyTo(Annotation[] array, int index)](#copyTo-com.aspose.pdf.Annotation---int-) | Copies array of annotations into collection. |
| [delete()](#delete--) | Deletes all annotations from the collection. |
| [delete(Annotation annotation)](#delete-com.aspose.pdf.Annotation-) | Deletes specified annotation from the collection. |
| [delete(int index)](#delete-int-) | Deletes annotation from the collection by index. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findByName(String name)](#findByName-java.lang.String-) | Returns annotation by its name. |
| [getClass()](#getClass--) |  |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to com.aspose.pdf.AnnotationCollection. |
| [get_Item(int index)](#get-Item-int-) | The index of the element to get. |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating if collection is readonly. |
| [isSynchronized()](#isSynchronized--) | Gets a value indicating whether access to the com.aspose.pdf.AnnotationCollection is synchronized (thread safe). |
| [iterator()](#iterator--) | Returns collection enumerator. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Annotation annotation)](#remove-com.aspose.pdf.Annotation-) | Deletes specified annotation from the collection. |
| [size()](#size--) | Gets count of annotations in collection. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnnotationCollection(Page page) {#AnnotationCollection-com.aspose.pdf.Page-}
```
public AnnotationCollection(Page page)
```


Constructor of AnnotationCollection. Creates annotation collection for annotations on the given page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Parent page of annotations. |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor to process annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Annotation selector object. |

### add(Annotation annotation) {#add-com.aspose.pdf.Annotation-}
```
public void add(Annotation annotation)
```


Adds annotation to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Annotation which shall be added. |

### add(Annotation annotation, boolean considerRotation) {#add-com.aspose.pdf.Annotation-boolean-}
```
public void add(Annotation annotation, boolean considerRotation)
```


Adds annotation to the collection. If page is rotated then annotation rectangle will be recalculated accordingly.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Annotation which shall be added. |
| considerRotation | boolean | If true and if page is rotated then annotation position will be recaculated accroding to page rotation. |

### clear() {#clear--}
```
public void clear()
```


Deletes all annotations from the collection.

### contains(Annotation annotation) {#contains-com.aspose.pdf.Annotation-}
```
public boolean contains(Annotation annotation)
```


Checks if specified annotation belong to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Annotation to be searched. |

**Returns:**
boolean - boolean value True - if annotation found; otherwise, false.
### copyTo(Annotation[] array, int index) {#copyTo-com.aspose.pdf.Annotation---int-}
```
public void copyTo(Annotation[] array, int index)
```


Copies array of annotations into collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [Annotation\[\]](../../com.aspose.pdf/annotation) | Array to copy into collection. |
| index | int | Starting index where colleciton wil lbe copied. |

### delete() {#delete--}
```
public void delete()
```


Deletes all annotations from the collection.

### delete(Annotation annotation) {#delete-com.aspose.pdf.Annotation-}
```
public void delete(Annotation annotation)
```


Deletes specified annotation from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Annotation which shall be deleted. |

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


Deletes annotation from the collection by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of annotation which shall be deleted. |

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
### findByName(String name) {#findByName-java.lang.String-}
```
public final Annotation findByName(String name)
```


Returns annotation by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the annotation |

**Returns:**
[Annotation](../../com.aspose.pdf/annotation) - Annotation object if found; otherwise, null.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets an object that can be used to synchronize access to com.aspose.pdf.AnnotationCollection.

**Returns:**
java.lang.Object - Object for sinchronization
### get_Item(int index) {#get-Item-int-}
```
public Annotation get_Item(int index)
```


The index of the element to get.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index value started from one. |

**Returns:**
[Annotation](../../com.aspose.pdf/annotation) - Annotation object
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets a value indicating if collection is readonly.

**Returns:**
boolean - boolean value
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Gets a value indicating whether access to the com.aspose.pdf.AnnotationCollection is synchronized (thread safe).

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
public System.Collections.IEnumerator<Annotation> iterator()
```


Returns collection enumerator.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.pdf.Annotation> - Enumerator object
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(Annotation annotation) {#remove-com.aspose.pdf.Annotation-}
```
public boolean remove(Annotation annotation)
```


Deletes specified annotation from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Annotation which shall be deleted. |

**Returns:**
boolean - boolean value True - if annotation found; otherwise, false.
### size() {#size--}
```
public int size()
```


Gets count of annotations in collection.

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

