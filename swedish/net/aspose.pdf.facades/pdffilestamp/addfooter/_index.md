---
title: PdfFileStamp.AddFooter
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp-metod. Lägger till sidfot på sidorna av dokumentet
type: docs
weight: 110
url: /sv/net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AddFooter(FormattedText, float) {#addfooter}

Lägger till sidfot på sidorna av dokumentet.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText-objekt som innehåller texten för sidfoten och textens egenskaper. |
| bottomMargin | Single | Marginalen längst ner på sidan. |

## Exempel

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### Se Även

* klass [FormattedText](../../formattedtext/)
* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(FormattedText, float, float, float) {#addfooter_1}

Lägger till sidfot på sidorna av dokumentet.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin, float leftMargin, 
    float rightMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText-objekt som innehåller sidfotstext och textens egenskaper. |
| bottomMargin | Single | Marginalen längst ner på sidan. |
| leftMargin | Single | Marginalen på vänster sida av sidan. |
| rightMargin | Single | Marginalen på höger sida av sidan. |

## Exempel

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### Se Även

* klass [FormattedText](../../formattedtext/)
* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float) {#addfooter_4}

Lägger till bild som sidfot på sidorna av dokumentet.

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageFile | String | Bildfilens namn och sökväg. |
| bottomMargin | Single | Marginalen längst ner på sidan. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### Se Även

* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float, float, float) {#addfooter_5}

Lägger till bild som sidfot på sidorna.

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageFile | String | Bildfilens namn och sökväg. |
| bottomMargin | Single | Marginalen längst ner på sidan. |
| leftMargin | Single | Marginalen på vänster sida av sidan. |
| rightMargin | Single | Marginalen på höger sida av sidan. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Se Även

* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float) {#addfooter_2}

Lägger till bild som sidfot på sidan.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | Stream | Stream som innehåller bilddata. |
| bottomMargin | Single | Marginalen längst ner på sidan. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Se Även

* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float, float, float) {#addfooter_3}

Lägger till bild som sidfot på sidan.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageStream | Stream | Stream som innehåller bilddata. |
| bottomMargin | Single | Marginalen längst ner på sidan. |
| leftMargin | Single | Marginalen på vänster sida av sidan. |
| rightMargin | Single | Marginalen på höger sida av sidan. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### Se Även

* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)