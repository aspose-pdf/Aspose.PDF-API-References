---
title: ReplaceText
second_title: Aspose.PDF per .NET API Reference
description: Sostituisce il testo nel file PDF nella pagina specificata.TextStateaspose.pdf.text/textstate loggetto famiglia di caratteri colore può essere specificato per sostituire il testo.
type: docs
weight: 450
url: /it/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Sostituisce il testo nel file PDF nella pagina specificata.[`TextState`](../../../aspose.pdf.text/textstate) l'oggetto (famiglia di caratteri, colore) può essere specificato per sostituire il testo.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcString | String | La stringa da sostituire. |
| thePage | Int32 | Numero di pagina (0 significa "tutte le pagine"). |
| destString | String | La stringa sostituita. |
| textState | TextState | Stato del testo (colore del testo, carattere, ecc.). |

### Valore di ritorno

Restituisce vero se è stata effettuata la sostituzione.

### Esempi

L'esempio mostra come sostituire il testo sulla prima pagina del documento PDF e impostare[`TextState`](../../../aspose.pdf.text/textstate) proprietà del testo per il nuovo testo.

```csharp
//www.aspose.com", 1, System.Drawing.Color.Red });
Document doc = new Document(inFile);

//www.aspose.com", 1 });
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

//x1, y1, x2, y2, .. xn, yn
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// ... }
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// apri il documento
editor.ReplaceText("hello world", 1, "hi world", textState);

// Crea il carattere e contrassegnalo da incorporare
doc.Save(outFile);
```

### Guarda anche

* class [TextState](../../../aspose.pdf.text/textstate)
* class [PdfContentEditor](../../pdfcontenteditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assemblea [Aspose.PDF](../../../)

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

Restituisce vero se è stata effettuata la sostituzione.

### Esempi

L'esempio mostra come sostituire il testo nel documento PDF.

```csharp
// crea un oggetto textState
Document doc = new Document(inFile);

// crea un oggetto textState
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// cambia il testo con il carattere specificato 
editor.ReplaceText("hello world", "hi world");

// salva il documento
doc.Save(outFile);
```

### Guarda anche

* class [PdfContentEditor](../../pdfcontenteditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assemblea [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

Sostituisce il testo nel file PDF nella pagina specificata.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcString | String | Il pungiglione da sostituire. |
| thePage | Int32 | Numero di pagina (0 per tutte le pagine) |
| destString | String | Sostituzione della stringa. |

### Valore di ritorno

Restituisce vero se è stata effettuata la sostituzione.

### Esempi

L'esempio mostra come sostituire il testo nel documento PDF nella pagina specificata.

```csharp
// apri il documento
Document doc = new Document(inFile);

// crea un oggetto PdfContentEditor per modificare il testo
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// cambia il testo 
editor.ReplaceText("hello world", 1, "hi world");

// salva il documento
doc.Save(outFile);
```

### Guarda anche

* class [PdfContentEditor](../../pdfcontenteditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assemblea [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

Sostituisce il testo nel file PDF utilizzando specificato[`TextState`](../../../aspose.pdf.text/textstate) oggetto.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcString | String | Stringa da sostituire |
| destString | String | Sostituzione della stringa |
| textState | TextState | Stato del testo (colore del testo, carattere, ecc.) |

### Valore di ritorno

Restituisce vero se è stata effettuata la sostituzione.

### Esempi

L'esempio mostra come sostituire il testo e impostare[`TextState`](../../../aspose.pdf.text/textstate) proprietà del testo per il nuovo testo.

```csharp
// apri il documento
Document doc = new Document(inFile);

// cambia il testo
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// cambia il testo
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// Crea il carattere e contrassegnalo da incorporare
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// apri il documento
editor.ReplaceText("hello world", "hi world", textState);

// Crea il carattere e contrassegnalo da incorporare
doc.Save(outFile);
```

### Guarda anche

* class [TextState](../../../aspose.pdf.text/textstate)
* class [PdfContentEditor](../../pdfcontenteditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assemblea [Aspose.PDF](../../../)

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
| fontSize | Int32 | Dimensione del font. |

### Valore di ritorno

Restituisce vero se è stata effettuata la sostituzione.

### Esempi

L'esempio mostra come sostituire il testo e impostare la dimensione del carattere per il nuovo testo.

```csharp
// apri il documento
Document doc = new Document(inFile);

// crea un oggetto textState
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// apri il documento
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// apri il documento
editor.ReplaceText("hello world", "hi world", 14);

// apri il documento
doc.Save(outFile);
```

### Guarda anche

* class [PdfContentEditor](../../pdfcontenteditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
