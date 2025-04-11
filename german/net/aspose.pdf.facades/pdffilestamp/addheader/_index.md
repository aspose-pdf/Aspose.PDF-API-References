---
title: PdfFileStamp.AddHeader
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp-Methode. Fügt der Seite einen Header hinzu
type: docs
weight: 120
url: /de/net/aspose.pdf.facades/pdffilestamp/addheader/
---
## AddHeader(FormattedText, float) {#addheader}

Fügt der Seite einen Header hinzu.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formattedText | FormattedText | Text für den Header und Eigenschaften des Textes. |
| topMargin | Single | Rand oben auf der Seite. |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### Siehe auch

* Klasse [FormattedText](../../formattedtext/)
* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddHeader(FormattedText, float, float, float) {#addheader_1}

Fügt der Datei Header auf den Seiten hinzu.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formattedText | FormattedText | Formatiertes Textobjekt, das den Seiteninhalt und dessen Eigenschaften enthält. |
| topMargin | Single | Rand oben auf der Seite. |
| leftMargin | Single | Rand links auf der Seite. |
| rightMargin | Single | Rand rechts auf der Seite. |

## Beispiele

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### Siehe auch

* Klasse [FormattedText](../../formattedtext/)
* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float) {#addheader_4}

Fügt ein Bild als Header auf den Seiten der Datei hinzu.

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageFile | String | Pfad zur Bilddatei. |
| topMargin | Single | Rand oben auf der Seite. |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### Siehe auch

* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float, float, float) {#addheader_5}

Fügt ein Bild als Header auf den Seiten hinzu.

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageFile | String | Pfad zur Bilddatei. |
| topMargin | Single | Rand oben auf der Seite. |
| leftMargin | Single | Rand links auf der Seite. |
| rightMargin | Single | Rand rechts auf der Seite. |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Siehe auch

* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float) {#addheader_2}

Fügt ein Bild als Header auf den Seiten hinzu.

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageStream | Stream | Stream des Bildes. |
| topMargin | Single | Rand oben auf der Seite. |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Siehe auch

* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float, float, float) {#addheader_3}

Fügt ein Bild oben auf der Seite hinzu.

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Stream, der Bilddaten enthält. |
| topMargin | Single | Rand oben auf der Seite. |
| leftMargin | Single | Rand links auf der Seite. |
| rightMargin | Single | Rand rechts auf der Seite. |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### Siehe auch

* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)