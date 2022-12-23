---
title: PageLabelCollection
second_title: Aspose.PDF for Java API Reference
description: Class represeingting page label collection.
type: docs
weight: 264
url: /java/com.aspose.pdf/pagelabelcollection/
---
**Inheritance:**
java.lang.Object
```
public class PageLabelCollection
```

Class represeingting page label collection.
## Methods

| Method | Description |
| --- | --- |
| [getLabel(int pageIndex)](#getLabel-int-) | Gets page label by page index (page index is started from 0). |
| [updateLabel(int pageIndex, PageLabel pageLabel)](#updateLabel-int-com.aspose.pdf.PageLabel-) | Update label for given page index (page index is started from 0). |
| [removeLabel(int pageIndex)](#removeLabel-int-) | Remove label by page index (page index is started from 0). |
| [getPages()](#getPages--) | Gets page indexes in collection. |
### getLabel(int pageIndex) {#getLabel-int-}
```
public PageLabel getLabel(int pageIndex)
```


Gets page label by page index (page index is started from 0).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageIndex | int | Index of the page. |

**Returns:**
[PageLabel](../../com.aspose.pdf/pagelabel) - Page label for specified page index or null if page label does not exist.
### updateLabel(int pageIndex, PageLabel pageLabel) {#updateLabel-int-com.aspose.pdf.PageLabel-}
```
public void updateLabel(int pageIndex, PageLabel pageLabel)
```


Update label for given page index (page index is started from 0).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageIndex | int | Index of page to change lable of the page. |
| pageLabel | [PageLabel](../../com.aspose.pdf/pagelabel) | New label of the page. |

### removeLabel(int pageIndex) {#removeLabel-int-}
```
public boolean removeLabel(int pageIndex)
```


Remove label by page index (page index is started from 0).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageIndex | int | Index of page where label must be deleted. |

**Returns:**
boolean - true if operation was executed successfully.
### getPages() {#getPages--}
```
public int[] getPages()
```


Gets page indexes in collection.

**Returns:**
int[] - Array of integers which contains indexes of the pages.
