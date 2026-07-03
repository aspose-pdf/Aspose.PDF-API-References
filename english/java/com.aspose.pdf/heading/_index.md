---
title: Heading
second_title: Aspose.PDF for Java API Reference
description: Represents heading.
type: docs
weight: 1890
url: /java/com.aspose.pdf/heading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.TextFragment, com.aspose.pdf.Heading

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Heading extends TextFragment
```

Represents heading.

## Constructors

| Constructor | Description |
| --- | --- |
| [Heading](#Heading--) | For internal usage only |
| [Heading](#Heading-int-) | Initializes a new instance of the Cell class. |

## Methods

| Method | Description |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | Clone the heading with all segments. |
| [deepClone](#deepClone--) | Clone the heading. |
| [getDestinationPage](#getDestinationPage--) | Gets the destination page. |
| [getLevel](#getLevel--) | Gets the level. |
| [getStartNumber](#getStartNumber--) | Gets the heading start number. |
| [getStyle](#getStyle--) | Gets or sets style. |
| [getTocPage](#getTocPage--) | Gets the page that contains this heading. |
| [getTop](#getTop--) | Gets the top Y of this headings(for internal use). |
| [getUserLabel](#getUserLabel--) | Gets or sets user label. |
| [isAutoSequence](#isAutoSequence--) | Gets the heading should be numered automatically. |
| [isInList](#isInList--) | Gets the heading should be in toc list. |
| [setAutoSequence](#setAutoSequence-boolean-) | sets the heading should be numered automatically. |
| [setDestinationPage](#setDestinationPage-com.aspose.pdf.Page-) | sets the destination page. |
| [setInList](#setInList-boolean-) | sets the heading should be in toc list. |
| [setLevel](#setLevel-int-) | sets the level. |
| [setStartNumber](#setStartNumber-int-) | Gets the heading start number. Value: The startNumber. |
| [setStyle](#setStyle-com.aspose.pdf.NumberingStyle-) | sets or sets style. |
| [setTocPage](#setTocPage-com.aspose.pdf.Page-) | Sets the page that contains this heading. |
| [setTop](#setTop-double-) | sets the top Y of this headings(for internal use). |
| [setUserLabel](#setUserLabel-com.aspose.pdf.TextSegment-) | Gets or sets user label. |

### Heading {#Heading--}
```
public Heading()
```

For internal usage only

### Heading {#Heading-int-}
```
public Heading(int level)
```

Initializes a new instance of the Cell class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| level |  | The headings level. |

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

Clone the heading with all segments.

**Returns:**
The cloned object

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clone the heading.

**Returns:**
The cloned object

### getDestinationPage {#getDestinationPage--}
```
public Page getDestinationPage()
```

Gets the destination page.

**Returns:**
The destination page.

### getLevel {#getLevel--}
```
public int getLevel()
```

Gets the level.

**Returns:**
The heading level.

### getStartNumber {#getStartNumber--}
```
public int getStartNumber()
```

Gets the heading start number.

**Returns:**
Value: The startNumber.

### getStyle {#getStyle--}
```
public NumberingStyle getStyle()
```

Gets or sets style.

**Returns:**
The heading style.

### getTocPage {#getTocPage--}
```
public Page getTocPage()
```

Gets the page that contains this heading.

**Returns:**
The page.

### getTop {#getTop--}
```
public double getTop()
```

Gets the top Y of this headings(for internal use).

**Returns:**
The top Y value

### getUserLabel {#getUserLabel--}
```
public TextSegment getUserLabel()
```

Gets or sets user label.

**Returns:**
TextSegment object

### isAutoSequence {#isAutoSequence--}
```
public boolean isAutoSequence()
```

Gets the heading should be numered automatically.

**Returns:**
The IsAutoSequens.

### isInList {#isInList--}
```
public boolean isInList()
```

Gets the heading should be in toc list.

**Returns:**
The IsInList.

### setAutoSequence {#setAutoSequence-boolean-}
```
public void setAutoSequence(boolean value)
```

sets the heading should be numered automatically.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | The IsAutoSequens. |

### setDestinationPage {#setDestinationPage-com.aspose.pdf.Page-}
sets the destination page.

### setInList {#setInList-boolean-}
```
public void setInList(boolean value)
```

sets the heading should be in toc list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | The IsInList. |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

sets the level.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | The heading level. |

### setStartNumber {#setStartNumber-int-}
```
public void setStartNumber(int value)
```

Gets the heading start number. Value: The startNumber.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | The startNumber. |

### setStyle {#setStyle-com.aspose.pdf.NumberingStyle-}
sets or sets style.

### setTocPage {#setTocPage-com.aspose.pdf.Page-}
Sets the page that contains this heading.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

sets the top Y of this headings(for internal use).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | The top Y value |

### setUserLabel {#setUserLabel-com.aspose.pdf.TextSegment-}
Gets or sets user label.
