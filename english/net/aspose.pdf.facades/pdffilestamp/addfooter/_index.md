---
title: PdfFileStamp.AddFooter
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp method. Adds footer to the pages of the document
type: docs
weight: 110
url: /net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AddFooter(FormattedText, float) {#addfooter}

Adds footer to the pages of the document.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText object which contains text of the footer and text properties. |
| bottomMargin | Single | Margin at the top of page. |

## Examples

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### See Also

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(FormattedText, float, float, float) {#addfooter_1}

Adds footer to the pages of the document.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin, float leftMargin, 
    float rightMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText object which contains footer text and text properties. |
| bottomMargin | Single | Margin at the bottom of the page. |
| leftMargin | Single | Margin at the left side of the page. |
| rightMargin | Single | Margin at the right side of the page. |

## Examples

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### See Also

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float) {#addfooter_4}

Adds image as footer to the pages of the document.

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | String | Image file name and path. |
| bottomMargin | Single | Margin at the bottom of the page. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float, float, float) {#addfooter_5}

Adds image as footer of the pages.

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | String | Iamge file name and path. |
| bottomMargin | Single | Margin at the bottom of the page. |
| leftMargin | Single | Margin at the left side of the page. |
| rightMargin | Single | Margin at the right side of the page. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float) {#addfooter_2}

Adds image as footer of the page.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | Stream | Stream contains image data. |
| bottomMargin | Single | Margin at the bottom of the page. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float, float, float) {#addfooter_3}

Adds image as footer of the page.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | Stream | Stream contains image data. |
| bottomMargin | Single | Margin at the bottom of the page. |
| leftMargin | Single | Margin at the left side of the page. |
| rightMargin | Single | Margin at the right side of the page. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


