---
title: PageCollection
second_title: Aspose.PDF for Java API Reference
description: Collection of PDF document pages.
type: docs
weight: 262
url: /java/com.aspose.pdf/pagecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable, com.aspose.pdf.ISupportsMemoryCleanup
```
public final class PageCollection implements Iterable<Page>, ISupportsMemoryCleanup
```

Collection of PDF document pages.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Gets count of pages in the document. |
| [isEmpty()](#isEmpty--) | Returns TRUE if the collection is empty. |
| [isSynchronized()](#isSynchronized--) | Returns true of object is synchorinzed. |
| [getSyncRoot()](#getSyncRoot--) | Gets synchronization object of the collection. |
| [isReadOnly()](#isReadOnly--) | Gets value indicating of collection is readonly. |
| [add(Page entity)](#add-com.aspose.pdf.Page-) | Adds page to collection. |
| [clear()](#clear--) | Clear page collection. |
| [delete(int index)](#delete-int-) | Delete specified page. |
| [delete()](#delete--) | Deletes all pages from collection. |
| [indexOf(Page entity)](#indexOf-com.aspose.pdf.Page-) | Returns index of the specified page. |
| [getUnrestricted(int index)](#getUnrestricted-int-) | Returns page by its index. |
| [copyTo(Page[] array, int index)](#copyTo-com.aspose.pdf.Page---int-) | Copyies pages into document. |
| [iterator()](#iterator--) | Returns enumerator of pages. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts  AnnotationSelector  visitor object that provides functionality to work with annotations. |
| [delete(Integer[] pages)](#delete-java.lang.Integer---) | Delete pages specified which numbers are specified in array. |
| [insert(int pageNumber)](#insert-int-) | Insert empty apge into collection at the specified position. |
| [add()](#add--) | Adds empty page |
| [add(List<Page> pages)](#add-java.util.List-com.aspose.pdf.Page--) | Adds to collection all pages from list. |
| [add(Iterable<Page> pages)](#add-java.lang.Iterable-com.aspose.pdf.Page--) | Adds to collection all pages from list. |
| [insert(int pageNumber, Page entity)](#insert-int-com.aspose.pdf.Page-) | Inserts page into page collection at specified place. |
| [get_Item(int index)](#get-Item-int-) | Gets page by index. |
| [accept(ImagePlacementAbsorber visitor)](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Accepts  ImagePlacementAbsorber  visitor object that provides functionality to work with image placement objects. |
| [accept(TextFragmentAbsorber visitor)](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Accepts  TextFragmentAbsorber  visitor object that provides functionality to work with text objects. |
| [accept(TextAbsorber visitor)](#accept-com.aspose.pdf.TextAbsorber-) | Accepts  TextAbsorber  visitor object that provides functionality to work with text objects. |
| [add(Page[] pages)](#add-com.aspose.pdf.Page---) | Adds to collection all pages from array. |
| [insert(int pageNumber, Iterable<Page> pages)](#insert-int-java.lang.Iterable-com.aspose.pdf.Page--) | Inserts pages from the collection into document. |
| [insert(int pageNumber, List<Page> pages)](#insert-int-java.util.List-com.aspose.pdf.Page--) | Inserts pages from the collection into document. |
| [insert(int pageNumber, Page[] pages)](#insert-int-com.aspose.pdf.Page---) | Inserts pages of the array into document. |
| [flatten()](#flatten--) | Removes all fields located on the pages and place their values instead. |
| [freeMemory()](#freeMemory--) | Clears cached data |
| [add_Rename_Namesake(Page entity)](#add-Rename-Namesake-com.aspose.pdf.Page-) | Adds page to collection. |
| [contains(Page item)](#contains-com.aspose.pdf.Page-) | Determines whether this instance contains the object. |
| [remove(Page item)](#remove-com.aspose.pdf.Page-) | Removes the specified item, throws exception. |
| [findByPdfObject(IPdfObject pdfObject)](#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-) |  |
### size() {#size--}
```
public int size()
```


Gets count of pages in the document.

**Returns:**
int - int value
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Returns TRUE if the collection is empty.

**Returns:**
boolean - boolean value
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Returns true of object is synchorinzed.

**Returns:**
boolean - boolean value
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets synchronization object of the collection.

**Returns:**
java.lang.Object - Object for synchronization
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets value indicating of collection is readonly. Always returns false.

**Returns:**
boolean - boolean value
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
[Page](../../com.aspose.pdf/page) - Added page.
### clear() {#clear--}
```
public void clear()
```


Clear page collection.

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

### indexOf(Page entity) {#indexOf-com.aspose.pdf.Page-}
```
public int indexOf(Page entity)
```


Returns index of the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entity | [Page](../../com.aspose.pdf/page) | Page object. Pages numbers start from 1.

--------------------

Pages numbers start from 1. Returns 0 in case collection doesn't contain the page. |

**Returns:**
int - Index of the page in collection.
### getUnrestricted(int index) {#getUnrestricted-int-}
```
public Page getUnrestricted(int index)
```


Returns page by its index.  Page 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of requested page. Pages are numbered from 1. |

**Returns:**
[Page](../../com.aspose.pdf/page) - Requested page
### copyTo(Page[] array, int index) {#copyTo-com.aspose.pdf.Page---int-}
```
public void copyTo(Page[] array, int index)
```


Copyies pages into document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [Page\[\]](../../com.aspose.pdf/page) | Array containing Pages object to insert into document. It must be Object[] or Page[]. |
| index | int | Starting index where pages will be inserted |

### iterator() {#iterator--}
```
public Iterator<Page> iterator()
```


Returns enumerator of pages.

**Returns:**
java.util.Iterator<com.aspose.pdf.Page> - Enumerator of pages
### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts  AnnotationSelector  visitor object that provides functionality to work with annotations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | AnnotationSelector Visitor |

### delete(Integer[] pages) {#delete-java.lang.Integer---}
```
public void delete(Integer[] pages)
```


Delete pages specified which numbers are specified in array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pages | java.lang.Integer[] | Array of pages to be deleted. |

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
[Page](../../com.aspose.pdf/page) - Inserted page.
### add() {#add--}
```
public Page add()
```


Adds empty page

**Returns:**
[Page](../../com.aspose.pdf/page) - Added page.
### add(List<Page> pages) {#add-java.util.List-com.aspose.pdf.Page--}
```
public void add(List<Page> pages)
```


Adds to collection all pages from list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pages | java.util.List<com.aspose.pdf.Page> | List which contains all pages which must be added. |

### add(Iterable<Page> pages) {#add-java.lang.Iterable-com.aspose.pdf.Page--}
```
public void add(Iterable<Page> pages)
```


Adds to collection all pages from list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pages | java.lang.Iterable<com.aspose.pdf.Page> | List which contains all pages which must be added. |

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
[Page](../../com.aspose.pdf/page) - Inserted page.
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
| visitor | [ImagePlacementAbsorber](../../com.aspose.pdf/imageplacementabsorber) | Image placement object. |

### accept(TextFragmentAbsorber visitor) {#accept-com.aspose.pdf.TextFragmentAbsorber-}
```
public void accept(TextFragmentAbsorber visitor)
```


Accepts  TextFragmentAbsorber  visitor object that provides functionality to work with text objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) | Text fragment absorber object. |

### accept(TextAbsorber visitor) {#accept-com.aspose.pdf.TextAbsorber-}
```
public void accept(TextAbsorber visitor)
```


Accepts  TextAbsorber  visitor object that provides functionality to work with text objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [TextAbsorber](../../com.aspose.pdf/textabsorber) | Text absorber object. |

### add(Page[] pages) {#add-com.aspose.pdf.Page---}
```
public void add(Page[] pages)
```


Adds to collection all pages from array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pages | [Page\[\]](../../com.aspose.pdf/page) | Array of pages which will be added. |

### insert(int pageNumber, Iterable<Page> pages) {#insert-int-java.lang.Iterable-com.aspose.pdf.Page--}
```
public void insert(int pageNumber, Iterable<Page> pages)
```


Inserts pages from the collection into document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Starting position of the new pages. |
| pages | java.lang.Iterable<com.aspose.pdf.Page> | Pages collection. |

### insert(int pageNumber, List<Page> pages) {#insert-int-java.util.List-com.aspose.pdf.Page--}
```
public void insert(int pageNumber, List<Page> pages)
```


Inserts pages from the collection into document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Starting position of the new pages. |
| pages | java.util.List<com.aspose.pdf.Page> | Pages collection. |

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

### add_Rename_Namesake(Page entity) {#add-Rename-Namesake-com.aspose.pdf.Page-}
```
public void add_Rename_Namesake(Page entity)
```


Adds page to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entity | [Page](../../com.aspose.pdf/page) | Page which should be added. |

### contains(Page item) {#contains-com.aspose.pdf.Page-}
```
public boolean contains(Page item)
```


Determines whether this instance contains the object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [Page](../../com.aspose.pdf/page) | Page instance |

**Returns:**
boolean - boolean value  true  if [contains] [the specified item]; otherwise,  false .
### remove(Page item) {#remove-com.aspose.pdf.Page-}
```
public boolean remove(Page item)
```


Removes the specified item, throws exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [Page](../../com.aspose.pdf/page) | Page instance |

**Returns:**
boolean - boolean value
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
