---
title: PageLabelCollection
second_title: Aspose.PDF for Java API Reference
description: Class represeingting page label collection.
type: docs
weight: 214
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
| [UpdateLabel(int pageIndex, PageLabel pageLabel)](#UpdateLabel-int-com.aspose.pdf.PageLabel-) | Update label for given page index (page index is started from 0). |
| [RemoveLabel(int pageIndex)](#RemoveLabel-int-) | Remove label by page index (page index is started from 0). |
| [GetPages()](#GetPages--) | Gets page indexes in collection. |
### getLabel(int pageIndex) {#getLabel-int-}
```
public PageLabel getLabel(int pageIndex)
```


Gets page label by page index (page index is started from 0).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageIndex | int |  |

**Returns:**
[PageLabel](../../com.aspose.pdf/pagelabel) - 
### UpdateLabel(int pageIndex, PageLabel pageLabel) {#UpdateLabel-int-com.aspose.pdf.PageLabel-}
```
public void UpdateLabel(int pageIndex, PageLabel pageLabel)
```


Update label for given page index (page index is started from 0).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageIndex | int |  |
| pageLabel | [PageLabel](../../com.aspose.pdf/pagelabel) |  |

### RemoveLabel(int pageIndex) {#RemoveLabel-int-}
```
public boolean RemoveLabel(int pageIndex)
```


Remove label by page index (page index is started from 0).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageIndex | int |  |

**Returns:**
boolean - 
### GetPages() {#GetPages--}
```
public int[] GetPages()
```


Gets page indexes in collection.

**Returns:**
int[] - 
