---
title: "PdfFileStamp.AddPageNumber"
linktitle: "AddPageNumber"
articleTitle: "AddPageNumber"
second_title: "Aspose.PDF for .NET"
description: "Add page number to file. Page number text may contain # sign which will be replaced with number of the page. Page number is placed in the bottom of the page ..."
type: docs
weight: 130
url: "/net/aspose.pdf.facades/pdffilestamp/addpagenumber/"
product_version: "26.9.0"
---
## AddPageNumber(string) {#addpagenumber}

Add page number to file. Page number text may contain # sign which will be replaced with number of the page. 
 Page number is placed in the bottom of the page centered horizontally.

```csharp
public void AddPageNumber(string formatString)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formatString | string | Text of page number |

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber([FormattedText](../../../aspose.pdf.facades/formattedtext/)) {#addpagenumber_1}

Adds page number to the page. Page number may contain # sign which will be replaced with page number.
 Page number is placed in the bottom of the page centered horizontally.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | Format string for page number representes as FormattedText. |

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_2}

Adds page number to the pages of document.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formatString | string | Format string for page number. |
| position | int | Position where page number will be placed on the page. 0-bottom middle, 1-bottom right, 2-upper right, 
 3 - sides right, 4 - upper middle,5 - bottom left,6 - sides left,7 - upper left.
 You can use the following constants: 
 PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, 
 PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | float | Margin on the left edge of the page. |
| rightMargin | float | Margin on the right edge of the page. |
| topMargin | float | Margin on the top edge of the page. |
| bottomMargin | float | Margin on the bottom edge of the page. |

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_3}

Adds page number at the specified position on the page.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formatString | string | Format string. Format string can contain # sign which will be replaced with page number. |
| x | float | X coordinate of page number. |
| y | float | Y coordinate of page number. |

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber([FormattedText](../../../aspose.pdf.facades/formattedtext/), int, float, float, float, float) {#addpagenumber_4}

Adds page number to the pages of document.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText object which represents page number format and properties iof the text. |
| position | int | Position where page number will be placed on the page. 0-bottom middle, 1-bottom right, 2-upper right, 
 3 - sides right, 4 - upper middle,5 - bottom left,6 - sides left,7 - upper left.
 You can use the following constants: 
 PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, 
 PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | float | Margin on the left edge of the page. |
| rightMargin | float | Margin on the right edge of the page. |
| topMargin | float | Margin on the top edge of the page. |
| bottomMargin | float | Margin on the bottom edge of the page. |

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber([FormattedText](../../../aspose.pdf.facades/formattedtext/), float, float) {#addpagenumber_5}

Adds page number at the specified position on the page.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | Formatted text which represents page number format and properties of the text.
 Format string can contain # sign which will be replaced with page number. |
| x | float | X coordinate of page number. |
| y | float | Y coordinate of page number. |

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_6}

Adds page number to the pages.

```csharp
public void AddPageNumber(string formatString, int position)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formatString | string | Format of the page number. This text may contain # which will be replaced with page number. |
| position | int | Position where page number will be placed on the page. 0-bottom middle, 1-bottom right, 2-upper right, 
 3 - sides right, 4 - upper middle,5 - bottom left,6 - sides left,7 - upper left.
 You can use the following constants: 
 PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, 
 PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber([FormattedText](../../../aspose.pdf.facades/formattedtext/), int) {#addpagenumber_7}

Adds page number to the pages.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText object which contains format of the page number and text properties. 
 This text may contain # which will be replaced with page number. |
| position | int | Position where page number will be placed on the page. 0-bottom middle, 1-bottom right, 2-upper right, 
 3 - sides right, 4 - upper middle,5 - bottom left,6 - sides left,7 - upper left.
 You can use the following constants: 
 PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, 
 PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

