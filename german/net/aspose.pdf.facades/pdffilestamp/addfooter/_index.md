---
title: PdfFileStamp.AddFooter
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp-Methode. Fügt Fußzeile zu den Seiten des Dokuments hinzu
type: docs
weight: 110
url: /de/net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AddFooter(FormattedText, float) {#addfooter}

Fügt Fußzeile zu den Seiten des Dokuments hinzu.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText-Objekt, das den Text der Fußzeile und Textattribute enthält. |
| bottomMargin | Single | Rand am oberen Rand der Seite. |

## Beispiele

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### Siehe auch

* Klasse [FormattedText](../../formattedtext/)
* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddFooter(FormattedText, float, float, float) {#addfooter_1}

Fügt Fußzeile zu den Seiten des Dokuments hinzu.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin, float leftMargin, 
    float rightMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText-Objekt, das den Fußzeilentext und Textattribute enthält. |
| bottomMargin | Single | Rand am unteren Rand der Seite. |
| leftMargin | Single | Rand am linken Rand der Seite. |
| rightMargin | Single | Rand am rechten Rand der Seite. |

## Beispiele

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### Siehe auch

* Klasse [FormattedText](../../formattedtext/)
* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float) {#addfooter_4}

Fügt ein Bild als Fußzeile zu den Seiten des Dokuments hinzu.

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageFile | String | Bilddateiname und -pfad. |
| bottomMargin | Single | Rand am unteren Rand der Seite. |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### Siehe auch

* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float, float, float) {#addfooter_5}

Fügt ein Bild als Fußzeile der Seiten hinzu.

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageFile | String | Bilddateiname und -pfad. |
| bottomMargin | Single | Rand am unteren Rand der Seite. |
| leftMargin | Single | Rand am linken Rand der Seite. |
| rightMargin | Single | Rand am rechten Rand der Seite. |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Siehe auch

* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float) {#addfooter_2}

Fügt ein Bild als Fußzeile der Seite hinzu.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageStream | Stream | Stream enthält Bilddaten. |
| bottomMargin | Single | Rand am unteren Rand der Seite. |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Siehe auch

* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float, float, float) {#addfooter_3}

Fügt ein Bild als Fußzeile der Seite hinzu.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageStream | Stream | Stream enthält Bilddaten. |
| bottomMargin | Single | Rand am unteren Rand der Seite. |
| leftMargin | Single | Rand am linken Rand der Seite. |
| rightMargin | Single | Rand am rechten Rand der Seite. |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### Siehe auch

* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)