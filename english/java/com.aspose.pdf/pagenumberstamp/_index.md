---
title: PageNumberStamp
linktitle: PageNumberStamp
second_title: Aspose.PDF for Java API Reference
description: Represents page number stamp and used to number pages.
type: docs
weight: 3440
url: /java/com.aspose.pdf/pagenumberstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.TextStamp, com.aspose.pdf.PageNumberStamp

```
public final class PageNumberStamp extends TextStamp
```

Represents page number stamp and used to number pages.

## Constructors

| Constructor | Description |
| --- | --- |
| [PageNumberStamp](#PageNumberStamp--) | Initializes a new instance of the {@code PageNumberStamp} class. Format is set to "#". |
| [PageNumberStamp](#PageNumberStamp-com.aspose.pdf.facades.FormattedText-) | Initializes a new instance of the {@code PageNumberStamp} class. Format is set to "#". |
| [PageNumberStamp](#PageNumberStamp-java.lang.String-) | Initializes a new instance of the {@code PageNumberStamp} class. Format is set to "#". |

## Methods

| Method | Description |
| --- | --- |
| [getFormat](#getFormat--) | Gets String value for stamping page numbers. Value must include char '#' which is replaced with the page number in the process of stamping. |
| [getNumberingStyle](#getNumberingStyle--) | Numbering style which used by this stamp. |
| [getStartingNumber](#getStartingNumber--) | Gets value of the number of starting page. Other pages will be numbered starting from this value. |
| [put](#put-com.aspose.pdf.Page-) | Adds page number. |
| [setFormat](#setFormat-java.lang.String-) | Sets String value for stamping page numbers. Value must include char '#' which is replaced with the page number in the process of stamping. |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | Numbering style which used by this stamp. |
| [setStartingNumber](#setStartingNumber-int-) | Sets value of the number of starting page. Other pages will be numbered starting from this value. |

### PageNumberStamp {#PageNumberStamp--}
```
public PageNumberStamp()
```

Initializes a new instance of the {@code PageNumberStamp} class. Format is set to "#".

### PageNumberStamp {#PageNumberStamp-com.aspose.pdf.facades.FormattedText-}
Initializes a new instance of the {@code PageNumberStamp} class. Format is set to "#".

### PageNumberStamp {#PageNumberStamp-java.lang.String-}
Initializes a new instance of the {@code PageNumberStamp} class. Format is set to "#".

### getFormat {#getFormat--}
```
public String getFormat()
```

Gets String value for stamping page numbers. Value must include char '#' which is replaced with the page number in the process of stamping.

**Returns:**
String value

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

Numbering style which used by this stamp.

**Returns:**
NumberingStyle value @see NumberingStyle

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

Gets value of the number of starting page. Other pages will be numbered starting from this value.

**Returns:**
int value

### put {#put-com.aspose.pdf.Page-}
Adds page number.

### setFormat {#setFormat-java.lang.String-}
Sets String value for stamping page numbers. Value must include char '#' which is replaced with the page number in the process of stamping.

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
Numbering style which used by this stamp.

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

Sets value of the number of starting page. Other pages will be numbered starting from this value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |
