---
title: AddFooter
second_title: Aspose.PDF för .NET API Referens
description: Lägger till sidfot på dokumentets sidor.
type: docs
weight: 150
url: /sv/net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AddFooter(FormattedText, float) {#addfooter}

Lägger till sidfot på dokumentets sidor.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText-objekt som innehåller text i sidfoten och textegenskaper. |
| bottomMargin | Single | Marginal överst på sidan. |

### Exempel

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### Se även

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilestamp)
* hopsättning [Aspose.PDF](../../../)

---

## AddFooter(FormattedText, float, float, float) {#addfooter_1}

Lägger till sidfot på dokumentets sidor.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin, float leftMargin, 
    float rightMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText-objekt som innehåller sidfotstext och textegenskaper. |
| bottomMargin | Single | Marginal längst ner på sidan. |
| leftMargin | Single | Marginal till vänster på sidan. |
| rightMargin | Single | Marginal till höger på sidan. |

### Exempel

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### Se även

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilestamp)
* hopsättning [Aspose.PDF](../../../)

---

## AddFooter(string, float) {#addfooter_4}

Lägger till bild som sidfot på dokumentets sidor.

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageFile | String | Bildfilens namn och sökväg. |
| bottomMargin | Single | Marginal längst ner på sidan. |

### Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### Se även

* class [PdfFileStamp](../../pdffilestamp)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilestamp)
* hopsättning [Aspose.PDF](../../../)

---

## AddFooter(string, float, float, float) {#addfooter_5}

Lägger till bild som sidfot på sidorna.

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageFile | String | Iamge filnamn och sökväg. |
| bottomMargin | Single | Marginal längst ner på sidan. |
| leftMargin | Single | Marginal till vänster på sidan. |
| rightMargin | Single | Marginal till höger på sidan. |

### Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Se även

* class [PdfFileStamp](../../pdffilestamp)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilestamp)
* hopsättning [Aspose.PDF](../../../)

---

## AddFooter(Stream, float) {#addfooter_2}

Lägger till bild som sidfot på sidan.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | Stream | Stream innehåller bilddata. |
| bottomMargin | Single | Marginal längst ner på sidan. |

### Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Se även

* class [PdfFileStamp](../../pdffilestamp)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilestamp)
* hopsättning [Aspose.PDF](../../../)

---

## AddFooter(Stream, float, float, float) {#addfooter_3}

Lägger till bild som sidfot på sidan.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | Stream | Stream innehåller bilddata. |
| bottomMargin | Single | Marginal längst ner på sidan. |
| leftMargin | Single | Marginal till vänster på sidan. |
| rightMargin | Single | Marginal till höger på sidan. |

### Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### Se även

* class [PdfFileStamp](../../pdffilestamp)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilestamp)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
