---
title: ReplaceText
second_title: Aspose.PDF för .NET API Referens
description: Ersätter text i PDF-filen på den angivna sidan.TextStateaspose.pdf.text/textstate objekt teckensnittsfamilj färg kan specificeras till ersatt text.
type: docs
weight: 450
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Ersätter text i PDF-filen på den angivna sidan.[`TextState`](../../../aspose.pdf.text/textstate) objekt (teckensnittsfamilj, färg) kan specificeras till ersatt text.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcString | String | Snöret som ska bytas ut. |
| thePage | Int32 | Sidnummer (0 betyder "alla sidor"). |
| destString | String | Den ersatta strängen. |
| textState | TextState | Texttillstånd (textfärg, teckensnitt etc). |

### Returvärde

Returnerar sant om byte gjordes.

### Exempel

Exemplet visar hur man ersätter text på första sidan i PDF-dokumentet och ställer in[`TextState`](../../../aspose.pdf.text/textstate) textegenskaper för den nya texten.

```csharp
// öppna dokument
Document doc = new Document(inFile);

// Skapa typsnitt och markera att det ska bäddas in
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// skapa PdfContentEditor-objekt för att redigera text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// skapa textState-objekt
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// ändra text med angivet typsnitt
editor.ReplaceText("hello world", 1, "hi world", textState);

// spara dokument
doc.Save(outFile);
```

### Se även

* class [TextState](../../../aspose.pdf.text/textstate)
* class [PdfContentEditor](../../pdfcontenteditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdfcontenteditor)
* hopsättning [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

Ersätter text i PDF-filen.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcString | String | Snöret som ska bytas ut. |
| destString | String | Ersätter sträng. |

### Returvärde

Returnerar sant om byte gjordes.

### Exempel

Exemplet visar hur man ersätter text i PDF-dokument.

```csharp
// öppna dokument
Document doc = new Document(inFile);

// skapa PdfContentEditor-objekt för att redigera text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// ändra text 
editor.ReplaceText("hello world", "hi world");

// spara dokument
doc.Save(outFile);
```

### Se även

* class [PdfContentEditor](../../pdfcontenteditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdfcontenteditor)
* hopsättning [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

Ersätter text i PDF-filen på den angivna sidan.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcString | String | Stinget som ska bytas ut. |
| thePage | Int32 | Sidnummer (0 för alla sidor) |
| destString | String | Ersätter sträng. |

### Returvärde

Returnerar sant om byte gjordes.

### Exempel

Exemplet visar hur man ersätter text i PDF-dokument på den angivna sidan.

```csharp
// öppna dokument
Document doc = new Document(inFile);

// skapa PdfContentEditor-objekt för att redigera text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// ändra text 
editor.ReplaceText("hello world", 1, "hi world");

// spara dokument
doc.Save(outFile);
```

### Se även

* class [PdfContentEditor](../../pdfcontenteditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdfcontenteditor)
* hopsättning [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

Ersätter text i PDF-filen med angivna[`TextState`](../../../aspose.pdf.text/textstate) objekt.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcString | String | Sträng som ska bytas ut |
| destString | String | Ersätter sträng |
| textState | TextState | Texttillstånd (textfärg, teckensnitt etc) |

### Returvärde

Returnerar sant om byte gjordes.

### Exempel

Exemplet visar hur man ersätter text och set[`TextState`](../../../aspose.pdf.text/textstate) textegenskaper för den nya texten.

```csharp
// öppna dokument
Document doc = new Document(inFile);

// Skapa typsnitt och markera att det ska bäddas in
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// skapa PdfContentEditor-objekt för att redigera text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// skapa textState-objekt
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// ändra text med angivet typsnitt
editor.ReplaceText("hello world", "hi world", textState);

// spara dokument
doc.Save(outFile);
```

### Se även

* class [TextState](../../../aspose.pdf.text/textstate)
* class [PdfContentEditor](../../pdfcontenteditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdfcontenteditor)
* hopsättning [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

Ersätter text i PDF-filen och anger teckenstorlek.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcString | String | Sträng som ska bytas ut. |
| destString | String | Ersätter sträng. |
| fontSize | Int32 | Textstorlek. |

### Returvärde

Returnerar sant om byte gjordes.

### Exempel

Exemplet visar hur man ersätter text och ställer in teckenstorlek för den nya texten.

```csharp
// öppna dokument
Document doc = new Document(inFile);

// Skapa typsnitt och markera att det ska bäddas in
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// skapa PdfContentEditor-objekt för att redigera text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// ändra text med angivet typsnitt
editor.ReplaceText("hello world", "hi world", 14);

// spara dokument
doc.Save(outFile);
```

### Se även

* class [PdfContentEditor](../../pdfcontenteditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdfcontenteditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
