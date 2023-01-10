---
title: Heading
second_title: Aspose.PDF for Java API Reference
description: Represents heading.
type: docs
weight: 152
url: /java/com.aspose.pdf/heading/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.TextFragment](../../com.aspose.pdf/textfragment)
```
public final class Heading extends TextFragment
```

Represents heading.
## Constructors

| Constructor | Description |
| --- | --- |
| [Heading()](#Heading--) | For internal usage only |
| [Heading(int level)](#Heading-int-) | Initializes a new instance of the Cell class. |
## Methods

| Method | Description |
| --- | --- |
| [getTocPage()](#getTocPage--) | Gets the page that contains this heading. |
| [setTocPage(Page value)](#setTocPage-com.aspose.pdf.Page-) | Sets the page that contains this heading. |
| [getTop()](#getTop--) | Gets the top Y of this headings(for internal use). |
| [setTop(double value)](#setTop-double-) | sets the top Y of this headings(for internal use). |
| [getStartNumber()](#getStartNumber--) | Gets the heading start number. |
| [setStartNumber(int value)](#setStartNumber-int-) | Gets the heading start number. |
| [isAutoSequence()](#isAutoSequence--) | Gets the heading should be numered automatically. |
| [setAutoSequence(boolean value)](#setAutoSequence-boolean-) | sets the heading should be numered automatically. |
| [isInList()](#isInList--) | Gets the heading should be in toc list. |
| [setInList(boolean value)](#setInList-boolean-) | sets the heading should be in toc list. |
| [getDestinationPage()](#getDestinationPage--) | Gets the destination page. |
| [setDestinationPage(Page value)](#setDestinationPage-com.aspose.pdf.Page-) | sets the destination page. |
| [getLevel()](#getLevel--) | Gets the level. |
| [setLevel(int value)](#setLevel-int-) | sets the level. |
| [getStyle()](#getStyle--) | Gets or sets style. |
| [setStyle(int value)](#setStyle-int-) | sets or sets style. |
| [getUserLabel()](#getUserLabel--) | Gets or sets user label. |
| [setUserLabel(TextSegment value)](#setUserLabel-com.aspose.pdf.TextSegment-) | Gets or sets user label. |
| [deepClone()](#deepClone--) | Clone the heading. |
| [cloneWithSegments()](#cloneWithSegments--) | Clone the heading with all segments. |
### Heading() {#Heading--}
```
public Heading()
```


For internal usage only

### Heading(int level) {#Heading-int-}
```
public Heading(int level)
```


Initializes a new instance of the Cell class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int | The headings level. |

### getTocPage() {#getTocPage--}
```
public Page getTocPage()
```


Gets the page that contains this heading.

**Returns:**
[Page](../../com.aspose.pdf/page) - The page.
### setTocPage(Page value) {#setTocPage-com.aspose.pdf.Page-}
```
public void setTocPage(Page value)
```


Sets the page that contains this heading.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Page](../../com.aspose.pdf/page) | The page. |

### getTop() {#getTop--}
```
public double getTop()
```


Gets the top Y of this headings(for internal use).

**Returns:**
double - The top Y value
### setTop(double value) {#setTop-double-}
```
public void setTop(double value)
```


sets the top Y of this headings(for internal use).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The top Y value |

### getStartNumber() {#getStartNumber--}
```
public int getStartNumber()
```


Gets the heading start number.

**Returns:**
int - Value: The startNumber.
### setStartNumber(int value) {#setStartNumber-int-}
```
public void setStartNumber(int value)
```


Gets the heading start number.

Value: The startNumber.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The startNumber. |

### isAutoSequence() {#isAutoSequence--}
```
public boolean isAutoSequence()
```


Gets the heading should be numered automatically.

**Returns:**
boolean - The IsAutoSequens.
### setAutoSequence(boolean value) {#setAutoSequence-boolean-}
```
public void setAutoSequence(boolean value)
```


sets the heading should be numered automatically.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | The IsAutoSequens. |

### isInList() {#isInList--}
```
public boolean isInList()
```


Gets the heading should be in toc list.

**Returns:**
boolean - The IsInList.
### setInList(boolean value) {#setInList-boolean-}
```
public void setInList(boolean value)
```


sets the heading should be in toc list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | The IsInList. |

### getDestinationPage() {#getDestinationPage--}
```
public Page getDestinationPage()
```


Gets the destination page.

**Returns:**
[Page](../../com.aspose.pdf/page) - The destination page.
### setDestinationPage(Page value) {#setDestinationPage-com.aspose.pdf.Page-}
```
public void setDestinationPage(Page value)
```


sets the destination page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Page](../../com.aspose.pdf/page) | The destination page. |

### getLevel() {#getLevel--}
```
public int getLevel()
```


Gets the level.

**Returns:**
int - The heading level.
### setLevel(int value) {#setLevel-int-}
```
public void setLevel(int value)
```


sets the level.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The heading level. |

### getStyle() {#getStyle--}
```
public int getStyle()
```


Gets or sets style.

**Returns:**
int - The heading style.
### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


sets or sets style.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The heading style. |

### getUserLabel() {#getUserLabel--}
```
public TextSegment getUserLabel()
```


Gets or sets user label.

**Returns:**
[TextSegment](../../com.aspose.pdf/textsegment) - TextSegment object
### setUserLabel(TextSegment value) {#setUserLabel-com.aspose.pdf.TextSegment-}
```
public void setUserLabel(TextSegment value)
```


Gets or sets user label.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextSegment](../../com.aspose.pdf/textsegment) | TextSegment object |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone the heading.

**Returns:**
java.lang.Object - The cloned object
### cloneWithSegments() {#cloneWithSegments--}
```
public Object cloneWithSegments()
```


Clone the heading with all segments.

**Returns:**
java.lang.Object - The cloned object
