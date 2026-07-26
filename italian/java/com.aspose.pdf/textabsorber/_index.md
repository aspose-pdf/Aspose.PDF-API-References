---
title: "TextAbsorber"
linktitle: "TextAbsorber"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Rappresenta un oggetto assorbitore di testo. Esegue l'estrazione del testo e fornisce l'accesso al risultato tramite l'oggetto {@code TextAbsorber.Text}. </p> <hr> <pre> L'esempio."
type: docs
weight: 4900
url: /it/java/com.aspose.pdf/textabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber

```
public class TextAbsorber extends Object
```

<p> Rappresenta un oggetto assorbitore di testo. Esegue l'estrazione del testo e fornisce l'accesso al risultato tramite l'oggetto {@code TextAbsorber.Text}. </p> <hr> <pre> L'esempio dimostra come estrarre il testo nella prima pagina del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for first page doc.getPages().get(1).accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> L'oggetto {@code TextAbsorber} è usato per estrarre il testo da un documento Pdf o dalla pagina del documento. </p>

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextAbsorber](#TextAbsorber--) | <p> Inizializza una nuova istanza di {@code TextAbsorber}. </p> <hr> <pre> L'esempio dimostra come estrarre il testo da tutte le pagine del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Esegue l'estrazione del testo e fornisce l'accesso al testo estratto tramite l'oggetto {@code TextAbsorber.Text}. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-) | <p> Inizializza una nuova istanza di {@code TextAbsorber}. </p> <hr> <pre> L'esempio dimostra come estrarre il testo da tutte le pagine del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Esegue l'estrazione del testo e fornisce l'accesso al testo estratto tramite l'oggetto {@code TextAbsorber.Text}. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-) | <p> Inizializza una nuova istanza di {@code TextAbsorber}. </p> <hr> <pre> L'esempio dimostra come estrarre il testo da tutte le pagine del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Esegue l'estrazione del testo e fornisce l'accesso al testo estratto tramite l'oggetto {@code TextAbsorber.Text}. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> Inizializza una nuova istanza di {@code TextAbsorber}. </p> <hr> <pre> L'esempio dimostra come estrarre il testo da tutte le pagine del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Esegue l'estrazione del testo e fornisce l'accesso al testo estratto tramite l'oggetto {@code TextAbsorber.Text}. </p> |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getErrors](#getErrors--) | Elenco di oggetti {@code TextExtractionError}. Contiene informazioni sugli errori trovati durante l'estrazione del testo. La ricerca degli errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; e può ridurre le prestazioni. |
| [getExtractionOptions](#getExtractionOptions--) | <p> Ottiene le opzioni di estrazione del testo. </p> <hr> <pre> L'esempio dimostra come impostare la modalità di formattazione del testo Pure e eseguire l'estrazione del testo. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Consente di definire la modalità di formattazione del testo {@code TextExtractionOptions} durante l'estrazione. La modalità predefinita è {@code TextExtractionOptions.TextFormattingMode.Pure} </p> |
| [getText](#getText--) | <p> Ottiene il testo estratto che il {@code TextAbsorber} estrae dal documento PDF o dalla pagina. </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | Ottiene le opzioni di ricerca del testo. Consente di definire un rettangolo che delimita il testo estratto. Per impostazione predefinita il rettangolo è vuoto. Ciò significa che solo i bordi della pagina definiscono la regione di estrazione del testo. |
| [hasErrors](#hasErrors--) | Il valore indica se sono stati trovati errori durante l'estrazione del testo. La ricerca degli errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; e può ridurre le prestazioni. |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> Imposta le opzioni di estrazione del testo. </p> <hr> <pre> L'esempio dimostra come impostare la modalità di formattazione del testo Pure e eseguire l'estrazione del testo. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Consente di definire la modalità di formattazione del testo {@code TextExtractionOptions} durante l'estrazione. La modalità predefinita è {@code TextExtractionOptions.TextFormattingMode.Pure} </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Imposta le opzioni di ricerca del testo. Consente di definire un rettangolo che delimita il testo estratto. Per impostazione predefinita il rettangolo è vuoto. Ciò significa che solo i bordi della pagina definiscono la regione di estrazione del testo. |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Estrae testo dal documento specificato </p> <hr> <pre> L'esempio dimostra come estrarre testo dal documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc); // get the extracted text String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Estrae testo dalla pagina specificata </p> <hr> <pre> L'esempio dimostra come estrarre testo dalla prima pagina del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.getPages(1)); // get the extracted text String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | <p> Estrae testo dallo XForm specificato. </p> <hr> <pre> L'esempio dimostra come estrarre testo dalla prima pagina del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.Pages().get(1).getResources().getForms().get(\"Xform1\")); // get the extracted text String extractedText = absorber.getText(); </pre> |

### TextAbsorber {#TextAbsorber--}
```
public TextAbsorber()
```

<p> Inizializza una nuova istanza di {@code TextAbsorber}. </p> <hr> <pre> L'esempio dimostra come estrarre il testo da tutte le pagine del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Esegue l'estrazione del testo e fornisce l'accesso al testo estratto tramite l'oggetto {@code TextAbsorber.Text}. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-}
<p> Inizializza una nuova istanza di {@code TextAbsorber}. </p> <hr> <pre> L'esempio dimostra come estrarre il testo da tutte le pagine del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Esegue l'estrazione del testo e fornisce l'accesso al testo estratto tramite l'oggetto {@code TextAbsorber.Text}. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-}
<p> Inizializza una nuova istanza di {@code TextAbsorber}. </p> <hr> <pre> L'esempio dimostra come estrarre il testo da tutte le pagine del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Esegue l'estrazione del testo e fornisce l'accesso al testo estratto tramite l'oggetto {@code TextAbsorber.Text}. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> Inizializza una nuova istanza di {@code TextAbsorber}. </p> <hr> <pre> L'esempio dimostra come estrarre il testo da tutte le pagine del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Esegue l'estrazione del testo e fornisce l'accesso al testo estratto tramite l'oggetto {@code TextAbsorber.Text}. </p>

### getErrors {#getErrors--}
```
public List < TextExtractionError > getErrors()
```

Elenco di oggetti {@code TextExtractionError}. Contiene informazioni sugli errori trovati durante l'estrazione del testo. La ricerca degli errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; e può ridurre le prestazioni.

**Returns:**
Elenco di oggetti TextExtractionError

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> Ottiene le opzioni di estrazione del testo. </p> <hr> <pre> L'esempio dimostra come impostare la modalità di formattazione del testo Pure e eseguire l'estrazione del testo. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Consente di definire la modalità di formattazione del testo {@code TextExtractionOptions} durante l'estrazione. La modalità predefinita è {@code TextExtractionOptions.TextFormattingMode.Pure} </p>

**Returns:**
TextExtractionOptions valore

### getText {#getText--}
```
public String getText()
```

<p> Ottiene il testo estratto che il {@code TextAbsorber} estrae dal documento PDF o dalla pagina. </p>

**Returns:**
String valore <hr> <pre> L'esempio dimostra come estrarre testo da tutte le pagine del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre>

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Ottiene le opzioni di ricerca del testo. Consente di definire un rettangolo che delimita il testo estratto. Per impostazione predefinita il rettangolo è vuoto. Ciò significa che solo i bordi della pagina definiscono la regione di estrazione del testo.

**Returns:**
TextSearchOptions valore

### hasErrors {#hasErrors--}
```
public boolean hasErrors()
```

Il valore indica se sono stati trovati errori durante l'estrazione del testo. La ricerca degli errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; e può ridurre le prestazioni.

**Returns:**
valore booleano

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> Imposta le opzioni di estrazione del testo. </p> <hr> <pre> L'esempio dimostra come impostare la modalità di formattazione del testo Pure e eseguire l'estrazione del testo. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Consente di definire la modalità di formattazione del testo {@code TextExtractionOptions} durante l'estrazione. La modalità predefinita è {@code TextExtractionOptions.TextFormattingMode.Pure} </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Imposta le opzioni di ricerca del testo. Consente di definire un rettangolo che delimita il testo estratto. Per impostazione predefinita il rettangolo è vuoto. Ciò significa che solo i bordi della pagina definiscono la regione di estrazione del testo.

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Estrae testo dal documento specificato </p> <hr> <pre> L'esempio dimostra come estrarre testo dal documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc); // get the extracted text String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Estrae testo dalla pagina specificata </p> <hr> <pre> L'esempio dimostra come estrarre testo dalla prima pagina del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.getPages(1)); // get the extracted text String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
<p> Estrae testo dallo XForm specificato. </p> <hr> <pre> L'esempio dimostra come estrarre testo dalla prima pagina del documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.Pages().get(1).getResources().getForms().get(\"Xform1\")); // get the extracted text String extractedText = absorber.getText(); </pre>
