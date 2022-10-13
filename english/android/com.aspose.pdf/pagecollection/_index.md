---
title: PageCollection
second_title: Aspose.PDF for Java API Reference
description: Collection of PDF document pages.
type: docs
weight: 210
url: /java/com.aspose.pdf/pagecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.ICollection
```
public final class PageCollection implements System.Collections.ICollection
```

Collection of PDF document pages.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Gets count of pages in the document. |
| [isSynchronized()](#isSynchronized--) | Returns true of object is synchorinzed. |
| [getSyncRoot()](#getSyncRoot--) | Gets synchronization object of the collection. |
| [add(Page entity)](#add-com.aspose.pdf.Page-) | Adds page to collection. |
| [delete(int index)](#delete-int-) | Delete specified page. |
| [delete()](#delete--) | Deletes all pages from collection. |
| [getUnrestricted(int index)](#getUnrestricted-int-) | Returns page by its index. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copyies pages into document. |
| [iterator()](#iterator--) | Returns enumerator of pages. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts  AnnotationSelector  visitor object that provides functionality to work with annotations. |
| [delete(int[] pages)](#delete-int---) | Delete pages specified which numbers are specified in array. |
| [insert(int pageNumber)](#insert-int-) | Insert empty apge into collection at the specified position. |
| [add()](#add--) | Adds empty page |
| [add(System.Collections.ICollection pages)](#add-com.aspose.ms.System.Collections.ICollection-) | Adds to collection all pages from list. |
| [insert(int pageNumber, Page entity)](#insert-int-com.aspose.pdf.Page-) | Inserts page into page collection at specified place. |
| [get_Item(int index)](#get-Item-int-) | Gets page by index. |
| [accept(ImagePlacementAbsorber visitor)](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Accepts  ImagePlacementAbsorber  visitor object that provides functionality to work with image placement objects. |
| [accept(TextFragmentAbsorber visitor)](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Accepts  TextFragmentAbsorber  visitor object that provides functionality to work with text objects. |
| [accept(TextAbsorber visitor)](#accept-com.aspose.pdf.TextAbsorber-) | Accepts  TextAbsorber  visitor object that provides functionality to work with text objects. |
| [add(Page[] pages)](#add-com.aspose.pdf.Page---) | Adds to collection all pages from array. |
| [insert(int pageNumber, System.Collections.ICollection pages)](#insert-int-com.aspose.ms.System.Collections.ICollection-) | Inserts pages from the collection into document. |
| [insert(int pageNumber, Page[] pages)](#insert-int-com.aspose.pdf.Page---) | Inserts pages of the array into document. |
| [flatten()](#flatten--) | Removes all fields located on the pages and place their values instead. |
| [freeMemory()](#freeMemory--) | Clears cached data |
| [findByPdfObject(IPdfObject pdfObject)](#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-) |  |
### size() {#size--}
```
public int size()
```


Gets count of pages in the document.

**Returns:**
int
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Returns true of object is synchorinzed.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets synchronization object of the collection.

**Returns:**
java.lang.Object
### add(Page entity) {#add-com.aspose.pdf.Page-}
```
public Page add(Page entity)
```


Adds page to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entity | [Page](../../com.aspose.pdf/page) | Page which should be added. |

**Returns:**
[Page](../../com.aspose.pdf/page)
### delete(int index) {#delete-int-}
```
public void delete(int index)
```


Delete specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Number of page that will be deleted. Pages numbers start from 1. |

### delete() {#delete--}
```
public void delete()
```


Deletes all pages from collection.

### getUnrestricted(int index) {#getUnrestricted-int-}
```
public Page getUnrestricted(int index)
```


Returns page by its index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of requested page. Pages are numbered from 1. |

**Returns:**
[Page](../../com.aspose.pdf/page) - Requested page
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array array, int index)
```


Copyies pages into document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array containing Pages object to insert into document. It must be Object[] or Page[]. |
| index | int | Starting index where pages will be inserted |

### iterator() {#iterator--}
```
public System.Collections.IEnumerator iterator()
```


Returns enumerator of pages.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - Enumerator of pages
### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts  AnnotationSelector  visitor object that provides functionality to work with annotations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | AnnotationSelector Visitor |

### delete(int[] pages) {#delete-int---}
```
public void delete(int[] pages)
```


Delete pages specified which numbers are specified in array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pages | int[] | Array of pages to be deleted. |

### insert(int pageNumber) {#insert-int-}
```
public Page insert(int pageNumber)
```


Insert empty apge into collection at the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Position of the new page. |

**Returns:**
[Page](../../com.aspose.pdf/page)
### add() {#add--}
```
public Page add()
```


Adds empty page

**Returns:**
[Page](../../com.aspose.pdf/page)
### add(System.Collections.ICollection pages) {#add-com.aspose.ms.System.Collections.ICollection-}
```
public void add(System.Collections.ICollection pages)
```


Adds to collection all pages from list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pages | com.aspose.ms.System.Collections.ICollection | List which contains all pages which must be added. |

### insert(int pageNumber, Page entity) {#insert-int-com.aspose.pdf.Page-}
```
public Page insert(int pageNumber, Page entity)
```


Inserts page into page collection at specified place.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Required page index in collection. |
| entity | [Page](../../com.aspose.pdf/page) | Page to be inserted. |

**Returns:**
[Page](../../com.aspose.pdf/page)
### get_Item(int index) {#get-Item-int-}
```
public Page get_Item(int index)
```


Gets page by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of page. |

**Returns:**
[Page](../../com.aspose.pdf/page) - Retreived page.
### accept(ImagePlacementAbsorber visitor) {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
```
public void accept(ImagePlacementAbsorber visitor)
```


Accepts  ImagePlacementAbsorber  visitor object that provides functionality to work with image placement objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [ImagePlacementAbsorber](../../com.aspose.pdf/imageplacementabsorber) |  |

### accept(TextFragmentAbsorber visitor) {#accept-com.aspose.pdf.TextFragmentAbsorber-}
```
public void accept(TextFragmentAbsorber visitor)
```


Accepts  TextFragmentAbsorber  visitor object that provides functionality to work with text objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) |  |

### accept(TextAbsorber visitor) {#accept-com.aspose.pdf.TextAbsorber-}
```
public void accept(TextAbsorber visitor)
```


Accepts  TextAbsorber  visitor object that provides functionality to work with text objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [TextAbsorber](../../com.aspose.pdf/textabsorber) |  |

### add(Page[] pages) {#add-com.aspose.pdf.Page---}
```
public void add(Page[] pages)
```


Adds to collection all pages from array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pages | [Page\[\]](../../com.aspose.pdf/page) | Array of pages which will be added. |

### insert(int pageNumber, System.Collections.ICollection pages) {#insert-int-com.aspose.ms.System.Collections.ICollection-}
```
public void insert(int pageNumber, System.Collections.ICollection pages)
```


Inserts pages from the collection into document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Starting position of the new pages. |
| pages | com.aspose.ms.System.Collections.ICollection | Pages collection. |

### insert(int pageNumber, Page[] pages) {#insert-int-com.aspose.pdf.Page---}
```
public void insert(int pageNumber, Page[] pages)
```


Inserts pages of the array into document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Starting number of the new pages. |
| pages | [Page\[\]](../../com.aspose.pdf/page) | Array of pages which will be inserted. |

### flatten() {#flatten--}
```
public void flatten()
```


Removes all fields located on the pages and place their values instead.

### freeMemory() {#freeMemory--}
```
public void freeMemory()
```


Clears cached data

### findByPdfObject(IPdfObject pdfObject) {#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-}
```
public final Page findByPdfObject(IPdfObject pdfObject)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfObject | [IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) |  |

**Returns:**
[Page](../../com.aspose.pdf/page)
