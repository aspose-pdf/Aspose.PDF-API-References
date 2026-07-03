---
title: PageNumber
second_title: Aspose.PDF for Java API Reference
description: Represents a page number format that includes an index, total number of pages, and a delimiter.
type: docs
weight: 150
url: /java/com.aspose.pdf.artifacts.pagination/pagenumber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.artifacts.pagination.PageNumber

```
public final class PageNumber extends Object
```

Represents a page number format that includes an index, total number of pages, and a delimiter.

## Constructors

| Constructor | Description |
| --- | --- |
| [PageNumber](#PageNumber--) |  |

## Methods

| Method | Description |
| --- | --- |
| [getDelimiter](#getDelimiter--) | Gets or sets the delimiter used in the page number format. The formatted string will be updated based on the specified delimiter. |
| [getIndex](#getIndex--) | Gets or sets the page index component of the page number format. The formatted string will include a placeholder for the page index. |
| [getOffset](#getOffset--) | Gets or sets the offset to be added to the page index. |
| [getPageNumberString](#getPageNumberString-int-int-) | Returns a formatted string representing the page number based on the current settings. |
| [getTotalNum](#getTotalNum--) | Gets or sets the total number of pages component of the page number format. The formatted string will include a placeholder for the total number of pages. |
| [setDelimiter](#setDelimiter-java.lang.String-) | Gets or sets the delimiter used in the page number format. The formatted string will be updated based on the specified delimiter. |
| [setIndex](#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-) | Gets or sets the page index component of the page number format. |
| [setOffset](#setOffset-int-) | Gets or sets the offset to be added to the page index. |
| [setTotalNum](#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-) | Gets or sets the total number of pages component of the page number format. |

### PageNumber {#PageNumber--}
```
public PageNumber()
```



### getDelimiter {#getDelimiter--}
```
public final String getDelimiter()
```

Gets or sets the delimiter used in the page number format. The formatted string will be updated based on the specified delimiter.

**Returns:**
String value

### getIndex {#getIndex--}
```
public final PageNumber.PageIndex getIndex()
```

Gets or sets the page index component of the page number format. The formatted string will include a placeholder for the page index.

**Returns:**
PageIndex instance

### getOffset {#getOffset--}
```
public final int getOffset()
```

Gets or sets the offset to be added to the page index.

**Returns:**
int value

### getPageNumberString {#getPageNumberString-int-int-}
```
public final String getPageNumberString(int pageNumber, int count)
```

Returns a formatted string representing the page number based on the current settings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber |  | The current page number. |
| count |  | The total number of pages. |

**Returns:**
A formatted page number string.

### getTotalNum {#getTotalNum--}
```
public final PageNumber.PageTotalNum getTotalNum()
```

Gets or sets the total number of pages component of the page number format. The formatted string will include a placeholder for the total number of pages.

**Returns:**
PageTotalNum instance

### setDelimiter {#setDelimiter-java.lang.String-}
Gets or sets the delimiter used in the page number format. The formatted string will be updated based on the specified delimiter.

### setIndex {#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-}
Gets or sets the page index component of the page number format.

### setOffset {#setOffset-int-}
```
public final void setOffset(int value)
```

Gets or sets the offset to be added to the page index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setTotalNum {#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-}
Gets or sets the total number of pages component of the page number format.
