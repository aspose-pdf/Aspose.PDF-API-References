---
title: PdfFileStamp.AddHeader
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp-metod. Lägger till header på sidan
type: docs
weight: 120
url: /sv/net/aspose.pdf.facades/pdffilestamp/addheader/
---
## AddHeader(FormattedText, float) {#addheader}

Lägger till header på sidan.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | FormattedText | Text för header och egenskaper för texten. |
| topMargin | Single | Marginal på toppen av sidan. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### Se Även

* klass [FormattedText](../../formattedtext/)
* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(FormattedText, float, float, float) {#addheader_1}

Lägger till header på sidorna i filen.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | FormattedText | Formaterad textobjekt som innehåller sidtext och dess egenskaper. |
| topMargin | Single | Marginal på toppen av sidan. |
| leftMargin | Single | Marginal på vänster sida av sidan. |
| rightMargin | Single | Marginal på höger sida av sidan. |

## Exempel

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### Se Även

* klass [FormattedText](../../formattedtext/)
* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float) {#addheader_4}

Lägger till bild som header på sidorna i filen.

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageFile | String | Sökväg till bildfilen. |
| topMargin | Single | Marginal högst upp på sidan. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### Se Även

* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float, float, float) {#addheader_5}

Lägger till bild som header på sidorna.

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageFile | String | Sökväg till bildfilen. |
| topMargin | Single | Marginal högst upp på sidan. |
| leftMargin | Single | Marginal på vänster sida av sidan. |
| rightMargin | Single | Marginal på höger sida av sidan. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Se Även

* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float) {#addheader_2}

Lägger till bild som header på sidorna.

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | Stream | Ström av bilden. |
| topMargin | Single | Marginal högst upp på sidan. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Se Även

* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float, float, float) {#addheader_3}

Lägger till bild högst upp på sidan.

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Ström som innehåller bilddata. |
| topMargin | Single | Marginal högst upp på sidan. |
| leftMargin | Single | Marginal på vänster sida av sidan. |
| rightMargin | Single | Marginal på höger sida av sidan. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### Se Även

* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)