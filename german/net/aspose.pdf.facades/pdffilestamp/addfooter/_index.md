---
title: AddFooter
second_title: Aspose.PDF für .NET-API-Referenz
description: Fügt den Seiten des Dokuments eine Fußzeile hinzu.
type: docs
weight: 150
url: /de/net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AddFooter(FormattedText, float) {#addfooter}

Fügt den Seiten des Dokuments eine Fußzeile hinzu.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText-Objekt, das Text der Fußzeile und Texteigenschaften enthält. |
| bottomMargin | Single | Rand oben auf der Seite. |

### Beispiele

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### Siehe auch

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* namensraum [Aspose.Pdf.Facades](../../pdffilestamp)
* Montage [Aspose.PDF](../../../)

---

## AddFooter(FormattedText, float, float, float) {#addfooter_1}

Fügt den Seiten des Dokuments eine Fußzeile hinzu.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin, float leftMargin, 
    float rightMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText-Objekt, das Fußzeilentext und Texteigenschaften enthält. |
| bottomMargin | Single | Rand unten auf der Seite. |
| leftMargin | Single | Rand am linken Seitenrand. |
| rightMargin | Single | Rand am rechten Seitenrand. |

### Beispiele

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### Siehe auch

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* namensraum [Aspose.Pdf.Facades](../../pdffilestamp)
* Montage [Aspose.PDF](../../../)

---

## AddFooter(string, float) {#addfooter_4}

Fügt den Seiten des Dokuments ein Bild als Fußzeile hinzu.

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageFile | String | Name und Pfad der Bilddatei. |
| bottomMargin | Single | Rand unten auf der Seite. |

### Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### Siehe auch

* class [PdfFileStamp](../../pdffilestamp)
* namensraum [Aspose.Pdf.Facades](../../pdffilestamp)
* Montage [Aspose.PDF](../../../)

---

## AddFooter(string, float, float, float) {#addfooter_5}

Fügt ein Bild als Fußzeile der Seiten hinzu.

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageFile | String | Name und Pfad der Bilddatei. |
| bottomMargin | Single | Rand unten auf der Seite. |
| leftMargin | Single | Rand am linken Seitenrand. |
| rightMargin | Single | Rand am rechten Seitenrand. |

### Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Siehe auch

* class [PdfFileStamp](../../pdffilestamp)
* namensraum [Aspose.Pdf.Facades](../../pdffilestamp)
* Montage [Aspose.PDF](../../../)

---

## AddFooter(Stream, float) {#addfooter_2}

Fügt ein Bild als Fußzeile der Seite hinzu.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageStream | Stream | Stream enthält Bilddaten. |
| bottomMargin | Single | Rand unten auf der Seite. |

### Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Siehe auch

* class [PdfFileStamp](../../pdffilestamp)
* namensraum [Aspose.Pdf.Facades](../../pdffilestamp)
* Montage [Aspose.PDF](../../../)

---

## AddFooter(Stream, float, float, float) {#addfooter_3}

Fügt ein Bild als Fußzeile der Seite hinzu.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageStream | Stream | Stream enthält Bilddaten. |
| bottomMargin | Single | Rand unten auf der Seite. |
| leftMargin | Single | Rand am linken Seitenrand. |
| rightMargin | Single | Rand am rechten Seitenrand. |

### Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### Siehe auch

* class [PdfFileStamp](../../pdffilestamp)
* namensraum [Aspose.Pdf.Facades](../../pdffilestamp)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
