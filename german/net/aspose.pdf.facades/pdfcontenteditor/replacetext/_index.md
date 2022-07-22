---
title: ReplaceText
second_title: Aspose.PDF für .NET-API-Referenz
description: Ersetzt Text in der PDF-Datei auf der angegebenen Seite.TextStateaspose.pdf.text/textstate Objekt Schriftfamilie Farbe kann angegeben werden um Text zu ersetzen.
type: docs
weight: 450
url: /de/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Ersetzt Text in der PDF-Datei auf der angegebenen Seite.[`TextState`](../../../aspose.pdf.text/textstate) Objekt (Schriftfamilie, Farbe) kann angegeben werden, um Text zu ersetzen.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcString | String | Die zu ersetzende Zeichenfolge. |
| thePage | Int32 | Seitennummer (0 bedeutet „alle Seiten“). |
| destString | String | Die ersetzte Zeichenfolge. |
| textState | TextState | Textstatus (Textfarbe, Schriftart usw.). |

### Rückgabewert

Gibt true zurück, wenn eine Ersetzung vorgenommen wurde.

### Beispiele

Das Beispiel zeigt, wie Sie Text auf der ersten Seite des PDF-Dokuments ersetzen und festlegen[`TextState`](../../../aspose.pdf.text/textstate) Texteigenschaften für den neuen Text.

```csharp
// Dokument öffnen
Document doc = new Document(inFile);

// Schriftart erstellen und zum Einbetten markieren
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// PdfContentEditor-Objekt erstellen, um Text zu bearbeiten
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// TextState-Objekt erstellen
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// Text mit angegebener Schriftart ändern
editor.ReplaceText("hello world", 1, "hi world", textState);

// Dokument speichern
doc.Save(outFile);
```

### Siehe auch

* class [TextState](../../../aspose.pdf.text/textstate)
* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

Ersetzt Text in der PDF-Datei.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcString | String | Die zu ersetzende Zeichenfolge. |
| destString | String | Saite ersetzen. |

### Rückgabewert

Gibt true zurück, wenn eine Ersetzung vorgenommen wurde.

### Beispiele

Das Beispiel zeigt, wie Text in einem PDF-Dokument ersetzt wird.

```csharp
// Dokument öffnen
Document doc = new Document(inFile);

// PdfContentEditor-Objekt erstellen, um Text zu bearbeiten
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// Text ändern 
editor.ReplaceText("hello world", "hi world");

// Dokument speichern
doc.Save(outFile);
```

### Siehe auch

* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

Ersetzt Text in der PDF-Datei auf der angegebenen Seite.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcString | String | Der Stich ersetzt werden. |
| thePage | Int32 | Seitennummer (0 für alle Seiten) |
| destString | String | Saite ersetzen. |

### Rückgabewert

Gibt true zurück, wenn eine Ersetzung vorgenommen wurde.

### Beispiele

Das Beispiel zeigt, wie Text in einem PDF-Dokument auf der angegebenen Seite ersetzt wird.

```csharp
// Dokument öffnen
Document doc = new Document(inFile);

// PdfContentEditor-Objekt erstellen, um Text zu bearbeiten
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// Text ändern 
editor.ReplaceText("hello world", 1, "hi world");

// Dokument speichern
doc.Save(outFile);
```

### Siehe auch

* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

Ersetzt Text in der PDF-Datei mit angegebenem[`TextState`](../../../aspose.pdf.text/textstate) Objekt.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcString | String | Zu ersetzende Zeichenfolge |
| destString | String | Saite ersetzen |
| textState | TextState | Textstatus (Textfarbe, Schriftart usw.) |

### Rückgabewert

Gibt true zurück, wenn eine Ersetzung vorgenommen wurde.

### Beispiele

Das Beispiel zeigt, wie Text und Set ersetzt werden[`TextState`](../../../aspose.pdf.text/textstate) Texteigenschaften für den neuen Text.

```csharp
// Dokument öffnen
Document doc = new Document(inFile);

// Schriftart erstellen und zum Einbetten markieren
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// PdfContentEditor-Objekt erstellen, um Text zu bearbeiten
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// TextState-Objekt erstellen
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// Text mit angegebener Schriftart ändern
editor.ReplaceText("hello world", "hi world", textState);

// Dokument speichern
doc.Save(outFile);
```

### Siehe auch

* class [TextState](../../../aspose.pdf.text/textstate)
* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

Ersetzt Text in der PDF-Datei und legt die Schriftgröße fest.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcString | String | Zu ersetzende Zeichenfolge. |
| destString | String | Saite ersetzen. |
| fontSize | Int32 | Schriftgröße. |

### Rückgabewert

Gibt true zurück, wenn eine Ersetzung vorgenommen wurde.

### Beispiele

Das Beispiel zeigt, wie Text ersetzt und die Schriftgröße für den neuen Text festgelegt wird.

```csharp
// Dokument öffnen
Document doc = new Document(inFile);

// Schriftart erstellen und zum Einbetten markieren
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// PdfContentEditor-Objekt erstellen, um Text zu bearbeiten
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// Text mit angegebener Schriftart ändern
editor.ReplaceText("hello world", "hi world", 14);

// Dokument speichern
doc.Save(outFile);
```

### Siehe auch

* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
