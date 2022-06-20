---
title: AddPageNumber
second_title: Aspose.PDF for .NET API Reference
description: Add page number to file. Page number text may contain  sign which will be replaced with number of the page. Page number is placed in the bottom of the page centered horizontally.
type: docs
weight: 170
url: /net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

Add page number to file. Page number text may contain # sign which will be replaced with number of the page. Page number is placed in the bottom of the page centered horizontally.

```csharp
public void AddPageNumber(string formatString)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formatString | String | Text of page number |

### Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../../pdffilestamp)
* namespace [Aspose.Pdf.Facades](../../pdffilestamp)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

Adds page number to the page. Page number may contain # sign which will be replaced with page number. Page number is placed in the bottom of the page centered horizontally.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | Format string for page number representes as FormattedText. |

### Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### See Also

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* namespace [Aspose.Pdf.Facades](../../pdffilestamp)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

Adds page number to the pages of document.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formatString | String | Format string for page number. |
| position | Int32 | Position where page number will be placed on the page. 0-bottom middle, 1-bottom right, 2-upper right, 3 - sides right, 4 - upper middle,5 - bottom left,6 - sides left,7 - upper left. You can use the following constants: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Margin on the left edge of the page. |
| rightMargin | Single | Margin on the right edge of the page. |
| topMargin | Single | Margin on the top edge of the page. |
| bottomMargin | Single | Margin on the bottom edge of the page. |

### Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../../pdffilestamp)
* namespace [Aspose.Pdf.Facades](../../pdffilestamp)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

Adds page number at the specified position on the page.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formatString | String | Format string. Format string can contain # sign which will be replaced with page number. |
| x | Single | X coordinate of page number. |
| y | Single | Y coordinate of page number. |

### Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../../pdffilestamp)
* namespace [Aspose.Pdf.Facades](../../pdffilestamp)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

Adds page number to the pages of document.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText object which represents page number format and properties iof the text. |
| position | Int32 | Position where page number will be placed on the page. 0-bottom middle, 1-bottom right, 2-upper right, 3 - sides right, 4 - upper middle,5 - bottom left,6 - sides left,7 - upper left. You can use the following constants: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Margin on the left edge of the page. |
| rightMargin | Single | Margin on the right edge of the page. |
| topMargin | Single | Margin on the top edge of the page. |
| bottomMargin | Single | Margin on the bottom edge of the page. |

### Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### See Also

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* namespace [Aspose.Pdf.Facades](../../pdffilestamp)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

Adds page number at the specified position on the page.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | Formatted text which represents page number format and properties of the text. Format string can contain # sign which will be replaced with page number. |
| x | Single | X coordinate of page number. |
| y | Single | Y coordinate of page number. |

### Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### See Also

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* namespace [Aspose.Pdf.Facades](../../pdffilestamp)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

Adds page number to the pages.

```csharp
public void AddPageNumber(string formatString, int position)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formatString | String | Format of the page number. This text may contain # which will be replaced with page number. |
| position | Int32 | Position where page number will be placed on the page. 0-bottom middle, 1-bottom right, 2-upper right, 3 - sides right, 4 - upper middle,5 - bottom left,6 - sides left,7 - upper left. You can use the following constants: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../../pdffilestamp)
* namespace [Aspose.Pdf.Facades](../../pdffilestamp)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

Adds page number to the pages.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText object which contains format of the page number and text properties. This text may contain # which will be replaced with page number. |
| position | Int32 | Position where page number will be placed on the page. 0-bottom middle, 1-bottom right, 2-upper right, 3 - sides right, 4 - upper middle,5 - bottom left,6 - sides left,7 - upper left. You can use the following constants: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### See Also

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* namespace [Aspose.Pdf.Facades](../../pdffilestamp)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
