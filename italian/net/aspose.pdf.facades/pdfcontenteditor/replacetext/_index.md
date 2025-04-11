---
title: PdfContentEditor.ReplaceText
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfContentEditor. Sostituisce il testo nel file PDF nella pagina specificata. La famiglia di caratteri del colore dell'oggetto TextState può essere specificata per il testo sostituito
type: docs
weight: 450
url: /it/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Sostituisce il testo nel file PDF nella pagina specificata. L'oggetto [`TextState`](../../../aspose.pdf.text/textstate/) (famiglia di caratteri, colore) può essere specificato per il testo sostituito.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcString | String | La stringa da sostituire. |
| thePage | Int32 | Numero di pagina (0 significa "tutte le pagine"). |
| destString | String | La stringa sostituita. |
| textState | TextState | Stato del testo (Colore del testo, Font, ecc.). |

### Valore di ritorno

Restituisce true se la sostituzione è stata effettuata.

## Esempi

L'esempio dimostra come sostituire il testo nella prima pagina del documento PDF e impostare le proprietà del testo [`TextState`](../../../aspose.pdf.text/textstate/) per il nuovo testo.

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

### Vedi anche

* classe [TextState](../../../aspose.pdf.text/textstate/)
* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

Sostituisce il testo nel file PDF.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcString | String | La stringa da sostituire. |
| destString | String | Stringa di sostituzione. |

### Valore di ritorno

Restituisce true se la sostituzione è stata effettuata.

## Esempi

L'esempio dimostra come sostituire il testo nel documento PDF.

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

### Vedi anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

Sostituisce il testo nel file PDF nella pagina specificata.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcString | String | La stringa da sostituire. |
| thePage | Int32 | Numero di pagina (0 per tutte le pagine) |
| destString | String | Stringa di sostituzione. |

### Valore di ritorno

Restituisce true se la sostituzione è stata effettuata.

## Esempi

L'esempio dimostra come sostituire il testo nel documento PDF nella pagina specificata.

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

### Vedi anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

Sostituisce il testo nel file PDF utilizzando l'oggetto [`TextState`](../../../aspose.pdf.text/textstate/) specificato.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcString | String | Stringa da sostituire |
| destString | String | Stringa di sostituzione |
| textState | TextState | Stato del testo (Colore del testo, Font, ecc.) |

### Valore di ritorno

Restituisce true se la sostituzione è stata effettuata.

## Esempi

L'esempio dimostra come sostituire il testo e impostare le proprietà del testo [`TextState`](../../../aspose.pdf.text/textstate/) per il nuovo testo.

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

### Vedi anche

* classe [TextState](../../../aspose.pdf.text/textstate/)
* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

Sostituisce il testo nel file PDF e imposta la dimensione del carattere.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcString | String | Stringa da sostituire. |
| destString | String | Stringa di sostituzione. |
| fontSize | Int32 | Dimensione del carattere. |

### Valore di ritorno

Restituisce true se la sostituzione è stata effettuata.

## Esempi

L'esempio dimostra come sostituire il testo e impostare la dimensione del carattere per il nuovo testo.

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

### Vedi anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)