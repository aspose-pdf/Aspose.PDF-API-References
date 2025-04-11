---
title: PdfContentEditor.ReplaceText
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metod. Ersätter text i PDF-filen på den angivna sidan. TextState-objektets typsnitt, familj och färg kan specificeras för den ersatta texten
type: docs
weight: 450
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Ersätter text i PDF-filen på den angivna sidan. [`TextState`](../../../aspose.pdf.text/textstate/) objekt (typsnitt, färg) kan specificeras för den ersatta texten.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcString | Sträng | Den sträng som ska ersättas. |
| thePage | Int32 | Sidnummer (0 betyder "alla sidor"). |
| destString | Sträng | Den ersatta strängen. |
| textState | TextState | Texttillstånd (Textfärg, Typsnitt etc). |

### Returvärde

Returnerar true om ersättningen gjordes.

## Exempel

Exemplet visar hur man ersätter text på den första sidan av PDF-dokumentet och ställer in [`TextState`](../../../aspose.pdf.text/textstate/) textegenskaper för den nya texten.

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

### Se Även

* klass [TextState](../../../aspose.pdf.text/textstate/)
* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

Ersätter text i PDF-filen.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcString | Sträng | Den sträng som ska ersättas. |
| destString | Sträng | Ersättande sträng. |

### Returvärde

Returnerar true om ersättningen gjordes.

## Exempel

Exemplet visar hur man ersätter text i PDF-dokumentet.

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

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

Ersätter text i PDF-filen på den angivna sidan.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcString | Sträng | Den sträng som ska ersättas. |
| thePage | Int32 | Sidnummer (0 för alla sidor) |
| destString | Sträng | Ersättande sträng. |

### Returvärde

Returnerar true om ersättningen gjordes.

## Exempel

Exemplet visar hur man ersätter text i PDF-dokumentet på den angivna sidan.

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

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

Ersätter text i PDF-filen med det angivna [`TextState`](../../../aspose.pdf.text/textstate/) objektet.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcString | Sträng | Sträng som ska ersättas |
| destString | Sträng | Ersättande sträng |
| textState | TextState | Texttillstånd (Textfärg, Typsnitt etc) |

### Returvärde

Returnerar true om ersättningen gjordes.

## Exempel

Exemplet visar hur man ersätter text och ställer in [`TextState`](../../../aspose.pdf.text/textstate/) textegenskaper för den nya texten.

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

### Se Även

* klass [TextState](../../../aspose.pdf.text/textstate/)
* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

Ersätter text i PDF-filen och ställer in teckenstorlek.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcString | Sträng | Sträng som ska ersättas. |
| destString | Sträng | Ersättande sträng. |
| fontSize | Int32 | Teckenstorlek. |

### Returvärde

Returnerar true om ersättningen gjordes.

## Exempel

Exemplet visar hur man ersätter text och ställer in teckenstorlek för den nya texten.

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

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)