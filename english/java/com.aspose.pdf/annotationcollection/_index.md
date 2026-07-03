---
title: AnnotationCollection
linktitle: AnnotationCollection
second_title: Aspose.PDF for Java API Reference
description: Class representing annotation collection.
type: docs
weight: 80
url: /java/com.aspose.pdf/annotationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationCollection

**All Implemented Interfaces:**
Iterable < Annotation >

```
public final class AnnotationCollection extends Object implements Iterable < Annotation >
```

Class representing annotation collection.

## Constructors

| Constructor | Description |
| --- | --- |
| [AnnotationCollection](#AnnotationCollection-com.aspose.pdf.Page-) | Constructor of AnnotationCollection. Creates annotation collection for annotations on the given page. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor to process annotation. |
| [add](#add-com.aspose.pdf.Annotation-) | Adds annotation to the collection. |
| [add](#add-com.aspose.pdf.Annotation-boolean-) | Adds annotation to the collection. If page is rotated then annotation rectangle will be recalculated accordingly. |
| [clear](#clear--) | Deletes all annotations from the collection. |
| [contains](#contains-com.aspose.pdf.Annotation-) | Checks if specified annotation belong to collection. |
| [copyTo](#copyTo-com.aspose.pdf.Annotation:A-int-) | Copies array of annotations into collection. |
| [delete](#delete--) | Deletes all annotations from the collection. |
| [delete](#delete-com.aspose.pdf.Annotation-) | Deletes all annotations from the collection. |
| [delete](#delete-int-) | Deletes annotation from the collection by index. |
| [findByName](#findByName-java.lang.String-) | Returns annotation by its name. |
| [get_Item](#get_Item-int-) | The index of the element to get. |
| [getSyncRoot](#getSyncRoot--) | Gets an object that can be used to synchronize access to com.aspose.pdf.AnnotationCollection. |
| [isReadOnly](#isReadOnly--) | Gets a value indicating if collection is readonly. |
| [isSynchronized](#isSynchronized--) | Gets a value indicating whether access to the com.aspose.pdf.AnnotationCollection is synchronized (thread safe). |
| [iterator](#iterator--) | Returns collection enumerator. |
| [remove](#remove-com.aspose.pdf.Annotation-) | Deletes specified annotation from the collection. |
| [size](#size--) | Gets count of annotations in collection. |

### AnnotationCollection {#AnnotationCollection-com.aspose.pdf.Page-}
Constructor of AnnotationCollection. Creates annotation collection for annotations on the given page.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepts visitor to process annotation.

### add {#add-com.aspose.pdf.Annotation-}
Adds annotation to the collection.

### add {#add-com.aspose.pdf.Annotation-boolean-}
Adds annotation to the collection. If page is rotated then annotation rectangle will be recalculated accordingly.

### clear {#clear--}
```
public void clear()
```

Deletes all annotations from the collection.

### contains {#contains-com.aspose.pdf.Annotation-}
Checks if specified annotation belong to collection.

### copyTo {#copyTo-com.aspose.pdf.Annotation:A-int-}
Copies array of annotations into collection.

### delete {#delete--}
```
public void delete()
```

Deletes all annotations from the collection.

### delete {#delete-com.aspose.pdf.Annotation-}
Deletes all annotations from the collection.

### delete {#delete-int-}
```
public void delete(int index)
```

Deletes annotation from the collection by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index of annotation which shall be deleted. |

### findByName {#findByName-java.lang.String-}
Returns annotation by its name.

### get_Item {#get_Item-int-}
```
public Annotation get_Item(int index)
```

The index of the element to get.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | The index value started from one. |

**Returns:**
Annotation object

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Gets an object that can be used to synchronize access to com.aspose.pdf.AnnotationCollection.

**Returns:**
Object for sinchronization

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Gets a value indicating if collection is readonly.

**Returns:**
boolean value

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Gets a value indicating whether access to the com.aspose.pdf.AnnotationCollection is synchronized (thread safe).

**Returns:**
boolean value

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< Annotation > iterator()
```

Returns collection enumerator.

**Returns:**
Enumerator object

### remove {#remove-com.aspose.pdf.Annotation-}
Deletes specified annotation from the collection.

### size {#size--}
```
public int size()
```

Gets count of annotations in collection.

**Returns:**
int value
