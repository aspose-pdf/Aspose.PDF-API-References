---
title: AddHeader
second_title: Aspose.PDF för .NET API Referens
description: Lägger till sidhuvud på sidan.
type: docs
weight: 160
url: /sv/net/aspose.pdf.facades/pdffilestamp/addheader/
---
## AddHeader(FormattedText, float) {#addheader}

Lägger till sidhuvud på sidan.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | FormattedText | Text för rubrik och egenskaper för texten. |
| topMargin | Single | Marginal överst på sidan. |

### Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### Se även

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilestamp)
* hopsättning [Aspose.PDF](../../../)

---

## AddHeader(FormattedText, float, float, float) {#addheader_1}

Lägger till sidhuvud till filsidorna.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | FormattedText | Formaterat textobjekt som innehåller sidtext och dess egenskaper. |
| topMargin | Single | Marginal överst på sidan. |
| leftMargin | Single | Marginal till vänster på sidan. |
| rightMargin | Single | Marginal till höger på sidan. |

### Exempel

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### Se även

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilestamp)
* hopsättning [Aspose.PDF](../../../)

---

## AddHeader(string, float) {#addheader_4}

Lägger till bild som rubrik på filens sidor.

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageFile | String | Sökväg till bildfilen. |
| topMargin | Single | Marginal överst på sidan. |

### Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### Se även

* class [PdfFileStamp](../../pdffilestamp)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilestamp)
* hopsättning [Aspose.PDF](../../../)

---

## AddHeader(string, float, float, float) {#addheader_5}

Lägger till bild som rubrik på sidorna.

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageFile | String | Sökväg till bildfilen. |
| topMargin | Single | Marginal överst på sidan. |
| leftMargin | Single | Marginal till vänster på sidan. |
| rightMargin | Single | Marginal till höger på sidan. |

### Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Se även

* class [PdfFileStamp](../../pdffilestamp)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilestamp)
* hopsättning [Aspose.PDF](../../../)

---

## AddHeader(Stream, float) {#addheader_2}

Lägger till bild som rubrik på sidorna.

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | Stream | Stream av bilden. |
| topMargin | Single | Marginal överst på sidan. |

### Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Se även

* class [PdfFileStamp](../../pdffilestamp)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilestamp)
* hopsättning [Aspose.PDF](../../../)

---

## AddHeader(Stream, float, float, float) {#addheader_3}

Lägger till bild överst på sidan.

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Stream som innehåller bilddata. |
| topMargin | Single | Marginal överst på sidan. |
| leftMargin | Single | Marginal till vänster på sidan. |
| rightMargin | Single | Marginal till höger på sidan. |

### Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### Se även

* class [PdfFileStamp](../../pdffilestamp)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilestamp)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
