---
title: AnnotationCollection
second_title: Aspose.PDF for Java API Reference
description: Class representing annotation collection.
type: docs
weight: 16
url: /java/com.aspose.pdf/annotationcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.ICollection
```
public final class AnnotationCollection implements System.Collections.ICollection
```

Class representing annotation collection.
## Constructors

| Constructor | Description |
| --- | --- |
| [AnnotationCollection(Page page)](#AnnotationCollection-com.aspose.pdf.Page-) | Constructor of AnnotationCollection. |
## Methods

| Method | Description |
| --- | --- |
| [isSynchronized()](#isSynchronized--) | Gets a value indicating whether access to the com.aspose.pdf.AnnotationCollection is synchronized (thread safe). |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to com.aspose.pdf.AnnotationCollection. |
| [size()](#size--) | Gets count of annotations in collection. |
| [add(Annotation annotation, boolean considerRotation)](#add-com.aspose.pdf.Annotation-boolean-) | Adds annotation to the collection. |
| [add(Annotation annotation)](#add-com.aspose.pdf.Annotation-) | Adds annotation to the collection. |
| [delete(int index)](#delete-int-) | Deletes annotation from the collection by index. |
| [delete()](#delete--) | Deletes all annotations from the collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies array of annotations into collection. |
| [iterator()](#iterator--) | Returns collection enumerator. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor to process annotation. |
| [delete(Annotation annotation)](#delete-com.aspose.pdf.Annotation-) | Deletes specified annotation from the collection. |
| [get_Item(int index)](#get-Item-int-) | The index of the element to get. |
### AnnotationCollection(Page page) {#AnnotationCollection-com.aspose.pdf.Page-}
```
public AnnotationCollection(Page page)
```


Constructor of AnnotationCollection. Creates annotation collection for annotations on the given page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Parent page of annotations. |

### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Gets a value indicating whether access to the com.aspose.pdf.AnnotationCollection is synchronized (thread safe).

**Returns:**
boolean - boolean value
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets an object that can be used to synchronize access to com.aspose.pdf.AnnotationCollection.

**Returns:**
java.lang.Object - Object for sinchronization
### size() {#size--}
```
public int size()
```


Gets count of annotations in collection.

**Returns:**
int - int value
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

### add(Annotation annotation) {#add-com.aspose.pdf.Annotation-}
```
public void add(Annotation annotation)
```


Adds annotation to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Annotation which shall be added. |

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


Deletes annotation from the collection by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of annotation which shall be deleted. |

### delete() {#delete--}
```
public void delete()
```


Deletes all annotations from the collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array array, int index)
```


Copies array of annotations into collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array to copy into collection. |
| index | int | Starting index where colleciton wil lbe copied. |

### iterator() {#iterator--}
```
public System.Collections.IEnumerator iterator()
```


Returns collection enumerator.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - Enumerator object
### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor to process annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Annotation selector object. |

### delete(Annotation annotation) {#delete-com.aspose.pdf.Annotation-}
```
public void delete(Annotation annotation)
```


Deletes specified annotation from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Annotation which shall be deleted. |

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
