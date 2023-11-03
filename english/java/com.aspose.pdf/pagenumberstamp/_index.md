---
title: PageNumberStamp
second_title: Aspose.PDF for Java API Reference
description: Represents page number stamp and used to number pages.
type: docs
weight: 267
url: /java/com.aspose.pdf/pagenumberstamp/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Stamp](../../com.aspose.pdf/stamp), [com.aspose.pdf.TextStamp](../../com.aspose.pdf/textstamp)
```
public final class PageNumberStamp extends TextStamp
```

Represents page number stamp and used to number pages.
## Constructors

| Constructor | Description |
| --- | --- |
| [PageNumberStamp(String format)](#PageNumberStamp-java.lang.String-) | Initializes a new instance of the  PageNumberStamp  class. |
| [PageNumberStamp()](#PageNumberStamp--) | Initializes a new instance of the  PageNumberStamp  class. |
| [PageNumberStamp(FormattedText formattedText)](#PageNumberStamp-com.aspose.pdf.facades.FormattedText-) | Creates PageNumberStamp by formatted text. |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Gets String value for stamping page numbers. |
| [setFormat(String value)](#setFormat-java.lang.String-) | Sets String value for stamping page numbers. |
| [getStartingNumber()](#getStartingNumber--) | Gets value of the number of starting page. |
| [setStartingNumber(int value)](#setStartingNumber-int-) | Sets value of the number of starting page. |
| [put(Page page)](#put-com.aspose.pdf.Page-) | Adds page number. |
| [getNumberingStyle()](#getNumberingStyle--) | Numbering style which used by this stamp. |
| [setNumberingStyle(int value)](#setNumberingStyle-int-) | Numbering style which used by this stamp. |
### PageNumberStamp(String format) {#PageNumberStamp-java.lang.String-}
```
public PageNumberStamp(String format)
```


Initializes a new instance of the  PageNumberStamp  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | java.lang.String | String value used for stamping. See  Format  property for details. |

### PageNumberStamp() {#PageNumberStamp--}
```
public PageNumberStamp()
```


Initializes a new instance of the  PageNumberStamp  class. Format is set to "\#".

### PageNumberStamp(FormattedText formattedText) {#PageNumberStamp-com.aspose.pdf.facades.FormattedText-}
```
public PageNumberStamp(FormattedText formattedText)
```


Creates PageNumberStamp by formatted text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Formatted text which used to create Page Number Stamp. |

### getFormat() {#getFormat--}
```
public String getFormat()
```


Gets String value for stamping page numbers. Value must include char '\#' which is replaced with the page number in the process of stamping.

**Returns:**
java.lang.String - String value
### setFormat(String value) {#setFormat-java.lang.String-}
```
public void setFormat(String value)
```


Sets String value for stamping page numbers. Value must include char '\#' which is replaced with the page number in the process of stamping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getStartingNumber() {#getStartingNumber--}
```
public int getStartingNumber()
```


Gets value of the number of starting page. Other pages will be numbered starting from this value.

**Returns:**
int - int value
### setStartingNumber(int value) {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```


Sets value of the number of starting page. Other pages will be numbered starting from this value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### put(Page page) {#put-com.aspose.pdf.Page-}
```
public void put(Page page)
```


Adds page number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page for stamping. |

### getNumberingStyle() {#getNumberingStyle--}
```
public int getNumberingStyle()
```


Numbering style which used by this stamp.

**Returns:**
int - NumberingStyle value
### setNumberingStyle(int value) {#setNumberingStyle-int-}
```
public void setNumberingStyle(int value)
```


Numbering style which used by this stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | NumberingStyle value |

