---
title: PdfFileStamp.AddPageNumber
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp-Methode. Seitenzahl zur Datei hinzufügen. Der Text der Seitenzahl kann das Zeichen # enthalten, das durch die Seitenzahl ersetzt wird. Die Seitenzahl wird am unteren Rand der Seite zentriert platziert.
type: docs
weight: 130
url: /de/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

Fügt die Seitenzahl zur Datei hinzu. Der Text der Seitenzahl kann das Zeichen # enthalten, das durch die Seitenzahl ersetzt wird. Die Seitenzahl wird am unteren Rand der Seite zentriert platziert.

```csharp
public void AddPageNumber(string formatString)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formatString | String | Text der Seitenzahl |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Siehe auch

* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

Fügt die Seitenzahl zur Seite hinzu. Die Seitenzahl kann das Zeichen # enthalten, das durch die Seitenzahl ersetzt wird. Die Seitenzahl wird am unteren Rand der Seite zentriert platziert.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formattedText | FormattedText | Formatzeichenfolge für die Seitenzahl, dargestellt als FormattedText. |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### Siehe auch

* Klasse [FormattedText](../../formattedtext/)
* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

Fügt die Seitenzahl zu den Seiten des Dokuments hinzu.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formatString | String | Formatzeichenfolge für die Seitenzahl. |
| position | Int32 | Position, an der die Seitenzahl auf der Seite platziert wird. 0-unten Mitte, 1-unten rechts, 2-oben rechts, 3 - Seiten rechts, 4 - oben Mitte, 5 - unten links, 6 - Seiten links, 7 - oben links. Sie können die folgenden Konstanten verwenden: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Rand am linken Rand der Seite. |
| rightMargin | Single | Rand am rechten Rand der Seite. |
| topMargin | Single | Rand am oberen Rand der Seite. |
| bottomMargin | Single | Rand am unteren Rand der Seite. |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Siehe auch

* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

Fügt die Seitenzahl an der angegebenen Position auf der Seite hinzu.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formatString | String | Formatzeichenfolge. Die Formatzeichenfolge kann das Zeichen # enthalten, das durch die Seitenzahl ersetzt wird. |
| x | Single | X-Koordinate der Seitenzahl. |
| y | Single | Y-Koordinate der Seitenzahl. |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Siehe auch

* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

Fügt die Seitenzahl zu den Seiten des Dokuments hinzu.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText-Objekt, das das Format der Seitenzahl und die Eigenschaften des Textes darstellt. |
| position | Int32 | Position, an der die Seitenzahl auf der Seite platziert wird. 0-unten Mitte, 1-unten rechts, 2-oben rechts, 3 - Seiten rechts, 4 - oben Mitte, 5 - unten links, 6 - Seiten links, 7 - oben links. Sie können die folgenden Konstanten verwenden: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Rand am linken Rand der Seite. |
| rightMargin | Single | Rand am rechten Rand der Seite. |
| topMargin | Single | Rand am oberen Rand der Seite. |
| bottomMargin | Single | Rand am unteren Rand der Seite. |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Siehe auch

* Klasse [FormattedText](../../formattedtext/)
* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

Fügt die Seitenzahl an der angegebenen Position auf der Seite hinzu.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formattedText | FormattedText | Formatierter Text, der das Format der Seitenzahl und die Eigenschaften des Textes darstellt. Die Formatzeichenfolge kann das Zeichen # enthalten, das durch die Seitenzahl ersetzt wird. |
| x | Single | X-Koordinate der Seitenzahl. |
| y | Single | Y-Koordinate der Seitenzahl. |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Siehe auch

* Klasse [FormattedText](../../formattedtext/)
* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

Fügt die Seitenzahl zu den Seiten hinzu.

```csharp
public void AddPageNumber(string formatString, int position)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formatString | String | Format der Seitenzahl. Dieser Text kann das Zeichen # enthalten, das durch die Seitenzahl ersetzt wird. |
| position | Int32 | Position, an der die Seitenzahl auf der Seite platziert wird. 0-unten Mitte, 1-unten rechts, 2-oben rechts, 3 - Seiten rechts, 4 - oben Mitte, 5 - unten links, 6 - Seiten links, 7 - oben links. Sie können die folgenden Konstanten verwenden: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Siehe auch

* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

Fügt die Seitenzahl zu den Seiten hinzu.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText-Objekt, das das Format der Seitenzahl und die Texteigenschaften enthält. Dieser Text kann das Zeichen # enthalten, das durch die Seitenzahl ersetzt wird. |
| position | Int32 | Position, an der die Seitenzahl auf der Seite platziert wird. 0-unten Mitte, 1-unten rechts, 2-oben rechts, 3 - Seiten rechts, 4 - oben Mitte, 5 - unten links, 6 - Seiten links, 7 - oben links. Sie können die folgenden Konstanten verwenden: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Siehe auch

* Klasse [FormattedText](../../formattedtext/)
* Klasse [PdfFileStamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)