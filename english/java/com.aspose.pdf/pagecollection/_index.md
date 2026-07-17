---
title: PageCollection
linktitle: PageCollection
second_title: Aspose.PDF for Java API Reference
description: Collection of PDF document pages.
type: docs
weight: 3340
url: /java/com.aspose.pdf/pagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageCollection

**All Implemented Interfaces:**
Iterable < Page >

```
public final class PageCollection extends Object implements Iterable < Page >
```

Collection of PDF document pages.

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts {@code AnnotationSelector} visitor object that provides functionality to work with annotations. |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Accepts {@code ImagePlacementAbsorber} visitor object that provides functionality to work with image placement objects. |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | Accepts {@code TextAbsorber} visitor object that provides functionality to work with text objects. |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Accepts {@code TextFragmentAbsorber} visitor object that provides functionality to work with text objects. |
| [add_Rename_Namesake](#add_Rename_Namesake-com.aspose.pdf.Page-) | Adds page to collection. |
| [add](#add--) | Adds an empty page. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used. |
| [add](#add-java.lang.Iterable-) | Adds an empty page. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used. |
| [add](#add-java.util.List-) | Adds an empty page. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used. |
| [add](#add-com.aspose.pdf.Page-) | Adds an empty page. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used. |
| [add](#add-com.aspose.pdf.Page:A-) | Adds an empty page. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used. |
| [beginUpdate](#beginUpdate--) | Updates when group changes begin. |
| [clear](#clear--) | Clear page collection. |
| [contains](#contains-com.aspose.pdf.Page-) | Determines whether this instance contains the object. |
| [copyTo](#copyTo-com.aspose.pdf.Page:A-int-) | Copyies pages into document. |
| [delete](#delete--) | Deletes all pages from collection. |
| [delete](#delete-int-) | Delete specified page. |
| [delete](#delete-java.lang.Integer:A-) | Deletes all pages from collection. |
| [endUpdate](#endUpdate--) | Updates when group changes are complete. |
| [findByPdfObject](#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-) |  |
| [flatten](#flatten--) | Removes all fields located on the pages and place their values instead. |
| [freeMemory](#freeMemory--) | Clears cached data |
| [get_Item](#get_Item-int-) | Gets page by index. |
| [getSyncRoot](#getSyncRoot--) | Gets synchronization object of the collection. |
| [getUnrestricted](#getUnrestricted-int-) | Returns page by its index. {@code Page} |
| [indexOf](#indexOf-com.aspose.pdf.Page-) | <p> Returns index of the specified page. </p> |
| [insert](#insert-int-) | Insert an empty page into the collection at the specified position. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used. |
| [insert](#insert-int-java.lang.Iterable-) | Inserts pages from the collection into document. |
| [insert](#insert-int-java.util.List-) | Inserts pages from the collection into document. |
| [insert](#insert-int-com.aspose.pdf.Page-) | Inserts page into page collection at specified place. |
| [insert](#insert-int-com.aspose.pdf.Page:A-) | Inserts pages of the array into document. |
| [isEmpty](#isEmpty--) | Returns TRUE if the collection is empty. |
| [isReadOnly](#isReadOnly--) | Gets value indicating of collection is readonly. Always returns false. |
| [isSynchronized](#isSynchronized--) | Returns true of object is synchorinzed. |
| [iterator](#iterator--) | Returns enumerator of pages. |
| [remove](#remove-com.aspose.pdf.Page-) | Removes the specified item, throws exception. |
| [size](#size--) | Gets count of pages in the document. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepts {@code AnnotationSelector} visitor object that provides functionality to work with annotations.

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
Accepts {@code ImagePlacementAbsorber} visitor object that provides functionality to work with image placement objects.

### accept {#accept-com.aspose.pdf.TextAbsorber-}
Accepts {@code TextAbsorber} visitor object that provides functionality to work with text objects.

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
Accepts {@code TextFragmentAbsorber} visitor object that provides functionality to work with text objects.

### add_Rename_Namesake {#add_Rename_Namesake-com.aspose.pdf.Page-}
Adds page to collection.

### add {#add--}
```
public Page add()
```

Adds an empty page. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used.

**Returns:**
Added page.

### add {#add-java.lang.Iterable-}
Adds an empty page. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used.

**Returns:**
Added page.

### add {#add-java.util.List-}
Adds an empty page. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used.

**Returns:**
Added page.

### add {#add-com.aspose.pdf.Page-}
Adds an empty page. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used.

**Returns:**
Added page.

### add {#add-com.aspose.pdf.Page:A-}
Adds an empty page. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used.

**Returns:**
Added page.

### beginUpdate {#beginUpdate--}
```
public final void beginUpdate()
```

Updates when group changes begin.

### clear {#clear--}
```
public void clear()
```

Clear page collection.

### contains {#contains-com.aspose.pdf.Page-}
Determines whether this instance contains the object.

### copyTo {#copyTo-com.aspose.pdf.Page:A-int-}
Copyies pages into document.

### delete {#delete--}
```
public void delete()
```

Deletes all pages from collection.

### delete {#delete-int-}
```
public void delete(int index)
```

Delete specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Number of page that will be deleted. Pages numbers start from 1. |

### delete {#delete-java.lang.Integer:A-}
Deletes all pages from collection.

### endUpdate {#endUpdate--}
```
public final void endUpdate()
```

Updates when group changes are complete.

### findByPdfObject {#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-}


### flatten {#flatten--}
```
public void flatten()
```

Removes all fields located on the pages and place their values instead.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Clears cached data

### get_Item {#get_Item-int-}
```
public Page get_Item(int index)
```

Gets page by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index of page. |

**Returns:**
Retrieved page.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Gets synchronization object of the collection.

**Returns:**
Object for synchronization

### getUnrestricted {#getUnrestricted-int-}
```
public Page getUnrestricted(int index)
```

Returns page by its index. {@code Page}

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index of requested page. Pages are numbered from 1. |

**Returns:**
Requested page

### indexOf {#indexOf-com.aspose.pdf.Page-}
<p> Returns index of the specified page. </p>

### insert {#insert-int-}
```
public Page insert(int pageNumber)
```

Insert an empty page into the collection at the specified position. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber |  | Position of the new page. |

**Returns:**
Inserted page.

### insert {#insert-int-java.lang.Iterable-}
Inserts pages from the collection into document.

### insert {#insert-int-java.util.List-}
Inserts pages from the collection into document.

### insert {#insert-int-com.aspose.pdf.Page-}
Inserts page into page collection at specified place.

### insert {#insert-int-com.aspose.pdf.Page:A-}
Inserts pages of the array into document.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Returns TRUE if the collection is empty.

**Returns:**
boolean value

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Gets value indicating of collection is readonly. Always returns false.

**Returns:**
boolean value

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Returns true of object is synchorinzed.

**Returns:**
boolean value

### iterator {#iterator--}
```
public Iterator < Page > iterator()
```

Returns enumerator of pages.

**Returns:**
Enumerator of pages

### remove {#remove-com.aspose.pdf.Page-}
Removes the specified item, throws exception.

### size {#size--}
```
public int size()
```

Gets count of pages in the document.

**Returns:**
int value
