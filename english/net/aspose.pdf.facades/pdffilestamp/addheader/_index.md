---
title: AddHeader
second_title: Aspose.PDF for .NET API Reference
description: Adds header to the page.
type: docs
weight: 120
url: /net/aspose.pdf.facades/pdffilestamp/addheader/
---
## AddHeader(FormattedText, float) {#addheader}

Adds header to the page.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | Text for header and properties of the text. |
| topMargin | Single | Margin on the top of page. |

### Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### See Also

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* namespace [Aspose.Pdf.Facades](../../pdffilestamp)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(FormattedText, float, float, float) {#addheader_1}

Adds header to the pages of file.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | Formatted text object which contains page text and its properties. |
| topMargin | Single | Margin on the top of the page. |
| leftMargin | Single | Margin on the left of the page. |
| rightMargin | Single | Margin on the right of the page. |

### Examples

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### See Also

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* namespace [Aspose.Pdf.Facades](../../pdffilestamp)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float) {#addheader_4}

Adds image as header to the pages of the file.

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | String | Path to the image file. |
| topMargin | Single | Margin at top of the page. |

### Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../../pdffilestamp)
* namespace [Aspose.Pdf.Facades](../../pdffilestamp)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float, float, float) {#addheader_5}

Adds image as header on the pages.

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | String | Path to the image file. |
| topMargin | Single | Margin at top of the page. |
| leftMargin | Single | Margin at left side of the page. |
| rightMargin | Single | Margin at right side of the page. |

### Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../../pdffilestamp)
* namespace [Aspose.Pdf.Facades](../../pdffilestamp)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float) {#addheader_2}

Adds image as header on the pages.

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | Stream | Stream of the image. |
| topMargin | Single | Margin at top of the page. |

### Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../../pdffilestamp)
* namespace [Aspose.Pdf.Facades](../../pdffilestamp)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float, float, float) {#addheader_3}

Adds image at the top of the page.

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream which contains image data. |
| topMargin | Single | Margin at top of the page. |
| leftMargin | Single | Margin at left side of the page. |
| rightMargin | Single | Margin at right side of the page. |

### Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../../pdffilestamp)
* namespace [Aspose.Pdf.Facades](../../pdffilestamp)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
