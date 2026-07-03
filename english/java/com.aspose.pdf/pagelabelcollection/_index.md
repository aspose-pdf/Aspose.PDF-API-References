---
title: PageLabelCollection
linktitle: PageLabelCollection
second_title: Aspose.PDF for Java API Reference
description: Class represeingting page label collection.
type: docs
weight: 3400
url: /java/com.aspose.pdf/pagelabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageLabelCollection

```
public class PageLabelCollection extends Object
```

Class represeingting page label collection.

## Methods

| Method | Description |
| --- | --- |
| [getLabel](#getLabel-int-) | Gets page label by page index (page index is started from 0). |
| [getPages](#getPages--) | Gets page indexes in collection. |
| [removeLabel](#removeLabel-int-) | Remove label by page index (page index is started from 0). |
| [updateLabel](#updateLabel-int-com.aspose.pdf.PageLabel-) | Update label for given page index (page index is started from 0). |

### getLabel {#getLabel-int-}
```
public PageLabel getLabel(int pageIndex)
```

Gets page label by page index (page index is started from 0).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageIndex |  | Index of the page. |

**Returns:**
Page label for specified page index or null if page label does not exist.

### getPages {#getPages--}
```
public int[] getPages()
```

Gets page indexes in collection.

**Returns:**
Array of integers which contains indexes of the pages.

### removeLabel {#removeLabel-int-}
```
public boolean removeLabel(int pageIndex)
```

Remove label by page index (page index is started from 0).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageIndex |  | Index of page where label must be deleted. |

**Returns:**
true if operation was executed successfully.

### updateLabel {#updateLabel-int-com.aspose.pdf.PageLabel-}
Update label for given page index (page index is started from 0).
