---
title: "PdfContentEditor.ReplaceText"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfContentEditor. Sostituisce il testo nel file PDF sulla Page specificata. È possibile specificare la famiglia di caratteri e il colore dell'oggetto TextState per il testo sostituito."
type: docs
weight: 450
url: /it/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Sostituisce il testo nel file PDF sulla Page specificata. L'oggetto [`TextState`](../../../aspose.pdf.text/textstate/) (famiglia di caratteri, colore) può essere specificato per il testo sostituito.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcString | String | La stringa da sostituire. |
| thePage | Int32 | Numero Page (0 significa "tutte le pagine"). |
| destString | String | La stringa sostituita. |
| textState | TextState | Stato del testo (Colore del Testo, Font ecc). |

### Valore di ritorno

Restituisce true se la sostituzione è stata effettuata.

## Esempi

L'esempio dimostra come sostituire il testo sulla prima Page del Document PDF e impostare le proprietà del testo [`TextState`](../../../aspose.pdf.text/textstate/) per il nuovo testo.

```csharp
// apri documento
Document doc = new Document(inFile);

// Crea un font e contrassegnalo per l'incorporamento
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// crea l'oggetto PdfContentEditor per modificare il testo
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// crea l'oggetto textState
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// cambia il testo con il font specificato
editor.ReplaceText("hello world", 1, "hi world", textState);

// salva il Document
doc.Save(outFile);
```

### Vedi anche

* class [TextState](../../../aspose.pdf.text/textstate/)
* class [PdfContentEditor](../)
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
| destString | String | Sostituzione della stringa. |

### Valore di ritorno

Restituisce true se la sostituzione è stata effettuata.

## Esempi

L'esempio dimostra come sostituire il testo nel Document PDF.

```csharp
// apri documento
Document doc = new Document(inFile);

// crea l'oggetto PdfContentEditor per modificare il testo
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// cambia il testo 
editor.ReplaceText("hello world", "hi world");

// salva il Document
doc.Save(outFile);
```

### Vedi anche

* class [PdfContentEditor](../)
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
| thePage | Int32 | Numero Page (0 per tutte le pagine) |
| destString | String | Sostituzione della stringa. |

### Valore di ritorno

Restituisce true se la sostituzione è stata effettuata.

## Esempi

L'esempio dimostra come sostituire il testo nel Document PDF sulla Page specificata.

```csharp
// apri documento
Document doc = new Document(inFile);

// crea l'oggetto PdfContentEditor per modificare il testo
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// cambia il testo 
editor.ReplaceText("hello world", 1, "hi world");

// salva il Document
doc.Save(outFile);
```

### Vedi anche

* class [PdfContentEditor](../)
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
| textState | TextState | Stato del testo (colore del testo, carattere, ecc.) |

### Valore di ritorno

Restituisce true se la sostituzione è stata effettuata.

## Esempi

L'esempio dimostra come sostituire il testo e impostare le proprietà del testo [`TextState`](../../../aspose.pdf.text/textstate/) per il nuovo testo.

```csharp
// apri documento
Document doc = new Document(inFile);

// Crea un font e contrassegnalo per l'incorporamento
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// crea l'oggetto PdfContentEditor per modificare il testo
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// crea l'oggetto textState
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// cambia il testo con il font specificato
editor.ReplaceText("hello world", "hi world", textState);

// salva il Document
doc.Save(outFile);
```

### Vedi anche

* class [TextState](../../../aspose.pdf.text/textstate/)
* class [PdfContentEditor](../)
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
| destString | String | Sostituzione della stringa. |
| fontSize | Int32 | Dimensione del carattere. |

### Valore di ritorno

Restituisce true se la sostituzione è stata effettuata.

## Esempi

L'esempio dimostra come sostituire il testo e impostare la dimensione del carattere per il nuovo testo.

```csharp
// apri documento
Document doc = new Document(inFile);

// Crea un font e contrassegnalo per l'incorporamento
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// crea l'oggetto PdfContentEditor per modificare il testo
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// cambia il testo con il font specificato
editor.ReplaceText("hello world", "hi world", 14);

// salva il Document
doc.Save(outFile);
```

### Vedi anche

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


