---
title: "PdfContentEditor.ReplaceText"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor‑metod. Ersätter text i PDF‑filen på den angivna sidan. TextState‑objektets teckensnittsfamilj och färg kan specificeras för den ersatta texten."
type: docs
weight: 450
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Ersätter text i PDF‑filen på den angivna sidan. [`TextState`](../../../aspose.pdf.text/textstate/)‑objektet (teckensnittsfamilj, färg) kan specificeras för den ersatta texten.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcString | String | Strängen som ska ersättas. |
| thePage | Int32 | Sidnummer (0 betyder "alla sidor"). |
| destString | String | Den ersatta strängen. |
| textState | TextState | Texttillstånd (Textfärg, teckensnitt osv). |

### Returvärde

Returnerar true om ersättningen har gjorts.

## Exempel

Exemplet visar hur man ersätter text på den första sidan av PDF-dokumentet och ställer in [`TextState`](../../../aspose.pdf.text/textstate/) textegenskaper för den nya texten.

```csharp
// öppna dokument
Document doc = new Document(inFile);

// Skapa teckensnitt och markera det för inbäddning
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

// ändra text med angivet teckensnitt
editor.ReplaceText("hello world", 1, "hi world", textState);

// spara dokumentet
doc.Save(outFile);
```

### Se även

* class [TextState](../../../aspose.pdf.text/textstate/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

Ersätter text i PDF-filen.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcString | String | Strängen som ska ersättas. |
| destString | String | Ersätter sträng. |

### Returvärde

Returnerar true om ersättningen har gjorts.

## Exempel

Exemplet visar hur man ersätter text i PDF-dokumentet.

```csharp
// öppna dokument
Document doc = new Document(inFile);

// skapa PdfContentEditor-objekt för att redigera text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// ändra text
editor.ReplaceText("hello world", "hi world");

// spara dokumentet
doc.Save(outFile);
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

Ersätter text i PDF-filen på den angivna sidan.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcString | String | Strängen som ska ersättas. |
| thePage | Int32 | Sidnummer (0 för alla sidor) |
| destString | String | Ersätter sträng. |

### Returvärde

Returnerar true om ersättningen har gjorts.

## Exempel

Exemplet visar hur man ersätter text i PDF-dokumentet på den angivna sidan.

```csharp
// öppna dokument
Document doc = new Document(inFile);

// skapa PdfContentEditor-objekt för att redigera text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// ändra text
editor.ReplaceText("hello world", 1, "hi world");

// spara dokumentet
doc.Save(outFile);
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

Ersätter text i PDF-filen med hjälp av angivet [`TextState`](../../../aspose.pdf.text/textstate/) objekt.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcString | String | Sträng som ska ersättas |
| destString | String | Ersätter sträng |
| textState | TextState | Texttillstånd (textfärg, teckensnitt osv) |

### Returvärde

Returnerar true om ersättningen har gjorts.

## Exempel

Exemplet visar hur man ersätter text och ställer in [`TextState`](../../../aspose.pdf.text/textstate/) textegenskaper för den nya texten.

```csharp
// öppna dokument
Document doc = new Document(inFile);

// Skapa teckensnitt och markera det för inbäddning
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// skapa PdfContentEditor-objekt för att redigera text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// skapa textState-objekt
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// ändra text med angivet teckensnitt
editor.ReplaceText("hello world", "hi world", textState);

// spara dokumentet
doc.Save(outFile);
```

### Se även

* class [TextState](../../../aspose.pdf.text/textstate/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

Ersätter text i PDF-filen och anger teckenstorlek.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcString | String | Sträng som ska ersättas. |
| destString | String | Ersätter sträng. |
| fontSize | Int32 | Teckensnittsstorlek. |

### Returvärde

Returnerar true om ersättningen har gjorts.

## Exempel

Exemplet visar hur man ersätter text och ställer in teckensnittsstorlek för den nya texten.

```csharp
// öppna dokument
Document doc = new Document(inFile);

// Skapa teckensnitt och markera det för inbäddning
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// skapa PdfContentEditor-objekt för att redigera text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// ändra text med angivet teckensnitt
editor.ReplaceText("hello world", "hi world", 14);

// spara dokumentet
doc.Save(outFile);
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


