---
title: PdfContentEditor.ReplaceText
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Ersetzt Text in der PDF-Datei auf der angegebenen Seite. Die Schriftfamilie und die Farbe des TextState-Objekts können für den ersetzten Text angegeben werden.
type: docs
weight: 450
url: /de/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Ersetzt Text in der PDF-Datei auf der angegebenen Seite. [`TextState`](../../../aspose.pdf.text/textstate/) Objekt (Schriftfamilie, Farbe) kann für den ersetzten Text angegeben werden.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcString | String | Der zu ersetzende String. |
| thePage | Int32 | Seitennummer (0 bedeutet "alle Seiten"). |
| destString | String | Der ersetzte String. |
| textState | TextState | Textzustand (Textfarbe, Schrift usw.). |

### Rückgabewert

Gibt true zurück, wenn eine Ersetzung vorgenommen wurde.

## Beispiele

Das Beispiel zeigt, wie man Text auf der ersten Seite des PDF-Dokuments ersetzt und [`TextState`](../../../aspose.pdf.text/textstate/) Text-Eigenschaften für den neuen Text festlegt.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// create textState object
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// change text with specified font
editor.ReplaceText("hello world", 1, "hi world", textState);

// save document
doc.Save(outFile);
```

### Siehe auch

* Klasse [TextState](../../../aspose.pdf.text/textstate/)
* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

Ersetzt Text in der PDF-Datei.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcString | String | Der zu ersetzende String. |
| destString | String | Ersetzender String. |

### Rückgabewert

Gibt true zurück, wenn eine Ersetzung vorgenommen wurde.

## Beispiele

Das Beispiel zeigt, wie man Text im PDF-Dokument ersetzt.

```csharp
// open document
Document doc = new Document(inFile);

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text 
editor.ReplaceText("hello world", "hi world");

// save document
doc.Save(outFile);
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

Ersetzt Text in der PDF-Datei auf der angegebenen Seite.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcString | String | Der zu ersetzende String. |
| thePage | Int32 | Seitennummer (0 für alle Seiten) |
| destString | String | Ersetzender String. |

### Rückgabewert

Gibt true zurück, wenn eine Ersetzung vorgenommen wurde.

## Beispiele

Das Beispiel zeigt, wie man Text im PDF-Dokument auf der angegebenen Seite ersetzt.

```csharp
// open document
Document doc = new Document(inFile);

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text 
editor.ReplaceText("hello world", 1, "hi world");

// save document
doc.Save(outFile);
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

Ersetzt Text in der PDF-Datei unter Verwendung des angegebenen [`TextState`](../../../aspose.pdf.text/textstate/) Objekts.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcString | String | Zu ersetzender String |
| destString | String | Ersetzender String |
| textState | TextState | Textzustand (Textfarbe, Schrift usw.) |

### Rückgabewert

Gibt true zurück, wenn eine Ersetzung vorgenommen wurde.

## Beispiele

Das Beispiel zeigt, wie man Text ersetzt und [`TextState`](../../../aspose.pdf.text/textstate/) Text-Eigenschaften für den neuen Text festlegt.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// create textState object
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// change text with specified font
editor.ReplaceText("hello world", "hi world", textState);

// save document
doc.Save(outFile);
```

### Siehe auch

* Klasse [TextState](../../../aspose.pdf.text/textstate/)
* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

Ersetzt Text in der PDF-Datei und setzt die Schriftgröße.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcString | String | Zu ersetzender String. |
| destString | String | Ersetzender String. |
| fontSize | Int32 | Schriftgröße. |

### Rückgabewert

Gibt true zurück, wenn eine Ersetzung vorgenommen wurde.

## Beispiele

Das Beispiel zeigt, wie man Text ersetzt und die Schriftgröße für den neuen Text festlegt.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text with specified font
editor.ReplaceText("hello world", "hi world", 14);

// save document
doc.Save(outFile);
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)