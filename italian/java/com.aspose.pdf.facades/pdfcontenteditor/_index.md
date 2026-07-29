---
title: "PdfContentEditor"
linktitle: "PdfContentEditor"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe per modificare il contenuto dei file PDF."
type: docs
weight: 380
url: /it/java/com.aspose.pdf.facades/pdfcontenteditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfContentEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfContentEditor extends SaveableFacade
```

Rappresenta una classe per modificare il contenuto dei file PDF.

## Campi

| Campo | Descrizione |
| --- | --- |
| [DOCUMENT_CLOSE](#DOCUMENT_CLOSE) | Un tipo di evento documento. Chiude un documento. |
| [DOCUMENT_OPEN](#DOCUMENT_OPEN) | Un tipo di evento documento. Apre un documento. |
| [DOCUMENT_PRINTED](#DOCUMENT_PRINTED) | Un tipo di evento documento. Esegue un'azione dopo la stampa. |
| [DOCUMENT_SAVED](#DOCUMENT_SAVED) | Un tipo di evento documento. Esegue un'azione dopo il salvataggio. |
| [DOCUMENT_WILL_PRINT](#DOCUMENT_WILL_PRINT) | Un tipo di evento documento. Esegue un'azione prima della stampa. |
| [DOCUMENT_WILL_SAVE](#DOCUMENT_WILL_SAVE) | Un tipo di evento documento. Esegue un'azione prima del salvataggio. |

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfContentEditor](#PdfContentEditor--) | Il costruttore dell'oggetto PdfContentEditor. |
| [PdfContentEditor](#PdfContentEditor-com.aspose.pdf.IDocument-) | Il costruttore dell'oggetto PdfContentEditor. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addDocumentAdditionalAction](#addDocumentAdditionalAction-java.lang.String-java.lang.String-) | <p> Aggiunge un'azione aggiuntiva per l'evento del documento. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-) | <p> Aggiunge un allegato al documento senza annotazione. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.lang.String-java.lang.String-) | <p> Aggiunge un allegato al documento senza annotazione. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [bindPdf](#bindPdf-java.io.InputStream-) | Associa un flusso PDF per la modifica. |
| [bindPdf](#bindPdf-java.lang.String-) | Associa un file PDF per la modifica. |
| [changeViewerPreference](#changeViewerPreference-int-) | <p> Modifica le preferenze di visualizzazione. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre> |
| [close](#close--) | Chiude il documento aperto. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-) | Crea un collegamento per avviare un'applicazione nel documento PDF. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | Crea un collegamento per avviare un'applicazione nel documento PDF. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Crea un collegamento per avviare un'applicazione nel documento PDF. |
| [createBookmarksAction](#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-) | Crea un segnalibro con l'azione specificata. |
| [createCaret](#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Crea un'annotazione cursore. |
| [createCustomActionLink](#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Crea un collegamento per azioni personalizzate nel documento PDF. |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-) | Crea un'annotazione di allegato file. |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) | Crea un'annotazione di allegato file. |
| [createFreeText](#createFreeText-java.awt.Rectangle-java.lang.String-int-) | Crea un'annotazione di testo libero nel documento PDF |
| [createJavaScriptLink](#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-) | Crea un collegamento a JavaScript nel documento PDF. |
| [createLine](#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-) | Crea un'annotazione di linea. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-) | Crea un collegamento locale nel documento PDF. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-) | Crea un collegamento locale nel documento PDF. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Crea un collegamento locale nel documento PDF. |
| [createMarkup](#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Crea un'annotazione di markup nel documento PDF. |
| [createMovie](#createMovie-java.awt.Rectangle-java.lang.String-int-) |  |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-) | Crea un collegamento a un'altra pagina di documento PDF. |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Crea un collegamento a un'altra pagina di documento PDF. |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Crea un collegamento a un'altra pagina di documento PDF. |
| [createPolygon](#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Crea un'annotazione di poligono. |
| [createPolyLine](#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Crea un'annotazione di polilinea. |
| [createPopup](#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-) | Crea un'annotazione popup nel documento PDF. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-) | Crea un'annotazione di timbro di gomma. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-) | Crea un'annotazione di timbro di gomma. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Crea un'annotazione di timbro di gomma. |
| [createSound](#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) |  |
| [createSquareCircle](#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-) | Crea un'annotazione quadrato-circolare. |
| [createText](#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-) | Crea un'annotazione di testo nel documento PDF |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-) | Crea un collegamento web in un documento PDF. |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | Crea un collegamento web in un documento PDF. |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Crea un collegamento web in un documento PDF. |
| [deleteAttachments](#deleteAttachments--) | <p> Elimina tutti gli allegati nel documento PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage--) | <p> Elimina tutte le immagini dal documento PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage-int-int:A-) | <p> Elimina le immagini specificate nella pagina specificata. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre> |
| [deleteStamp](#deleteStamp-int-int:A-) | <p> Elimina più timbri nella pagina specificata per indice del timbro. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-) | <p> Elimina il timbro per ID da tutte le pagine del documento. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-int-) | <p> Elimina il timbro nella pagina specificata per ID del timbro. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int:A-) | <p> Elimina i timbri con ID specificati da tutte le pagine del documento. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int-int:A-) | <p> Elimina i timbri nella pagina specificata per più ID di timbro. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre> |
| [drawCurve](#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Crea un'annotazione curva. |
| [extractLink](#extractLink--) | <p> Estrae la collezione di istanze Link contenute nel documento PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // lavora con l'istanza Link } </pre> |
| [getReplaceTextStrategy](#getReplaceTextStrategy--) | Ottieni un insieme di parametri per l'operazione di sostituzione del testo |
| [getStamps](#getStamps-int-) | Restituisce un array di timbri nella pagina. |
| [getTextEditOptions](#getTextEditOptions--) | Ottiene le opzioni di modifica del testo. |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Ottiene le opzioni di sostituzione del testo. |
| [getTextSearchOptions](#getTextSearchOptions--) | Ottiene le opzioni di ricerca del testo. |
| [getViewerPreference](#getViewerPreference--) | <p> Restituisce la preferenza di visualizzazione. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre> |
| [hideStampById](#hideStampById-int-int-) | Nasconde il timbro. Dopo la nasconditura, la visibilità del timbro può essere ripristinata con il metodo ShowStampById. |
| [moveStamp](#moveStamp-int-int-double-double-) | Cambia la posizione del timbro nella pagina. |
| [moveStampById](#moveStampById-int-int-double-double-) | Cambia la posizione del timbro nella pagina. |
| [removeDocumentOpenAction](#removeDocumentOpenAction--) | <p> Rimuove l'azione di apertura dal documento. Questa operazione è utile quando si concatenano più documenti che utilizzano un'azione 'GoTo' esplicita all'avvio. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre> |
| [replaceImage](#replaceImage-int-int-java.lang.String-) | <p> Sostituisce l'immagine specificata nella pagina specificata del documento PDF con un'altra immagine. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-) | <p> Sostituisce il testo nel file PDF nella pagina specificata. </p> <hr> <pre> L'esempio dimostra come sostituire il testo in un documento PDF nella pagina specificata. // apri il documento Document doc = new Document(inFile); // crea l'oggetto PdfContentEditor per modificare il testo PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // modifica il testo editor.replaceText("hello world", 1, "hi world"); // salva il documento doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file on the specified page. {@code TextState} object (font family, color) can be specified to replaced text. </p> <hr> <pre> The example demonstrates how to replace text on the first page of the PDF document and set {@code TextState} text properties for the new text. // open document Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // cambia il testo con il font specificato editor.replaceText(\"hello world\", 1, \"hi world\", textState); // salva il documento doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-) | <p> Sostituisce il testo nel file PDF. </p> <hr> <pre> L'esempio dimostra come sostituire il testo in un documento PDF. Per impostazione predefinita, sostituisce il primo testo trovato. // apri il documento Document doc = new Document(inFile); // crea l'oggetto PdfContentEditor per modificare il testo PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // cambia il testo editor.replaceText(\"hello world\", \"hi world\"); // salva il documento doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-int-) | <p> Sostituisce il testo nel file PDF e imposta la dimensione del font. </p> <hr> <pre> L'esempio dimostra come sostituire il testo e impostare la dimensione del font per il nuovo testo. // apri il documento Document doc = new Document(inFile); // Crea il font e contrassegnalo per l'incorporamento com.aspose.pdf.Font font = FontRepository.FindFont(\"Courier New\"); font.isEmbedded ( true); // crea l'oggetto PdfContentEditor per modificare il testo PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // cambia il testo con il font specificato editor.replaceText(\"hello world\", \"hi world\", 14); // salva il documento doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file using specified {@code TextState} object. </p> <hr> <pre> The example demonstrates how to replace text and set {@code TextState} text properties for the new text. Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); // cambia il testo con il font specificato editor.replaceText(\"hello world\", \"hi world\", textState); // salva il documento doc.save(outFile); </pre> |
| [setReplaceTextStrategy](#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-) | Imposta un insieme di parametri per l'operazione di sostituzione del testo |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Imposta le opzioni di modifica del testo. |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Imposta le opzioni di sostituzione del testo. |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Imposta le opzioni di ricerca del testo. |
| [showStampById](#showStampById-int-int-) | Mostra il timbro che era stato nascosto da HiddenStampById. |

### DOCUMENT_CLOSE {#DOCUMENT_CLOSE}
```
public static final String DOCUMENT_CLOSE
```

Un tipo di evento documento. Chiude un documento.

### DOCUMENT_OPEN {#DOCUMENT_OPEN}
```
public static final String DOCUMENT_OPEN
```

Un tipo di evento documento. Apre un documento.

### DOCUMENT_PRINTED {#DOCUMENT_PRINTED}
```
public static final String DOCUMENT_PRINTED
```

Un tipo di evento documento. Esegue un'azione dopo la stampa.

### DOCUMENT_SAVED {#DOCUMENT_SAVED}
```
public static final String DOCUMENT_SAVED
```

Un tipo di evento documento. Esegue un'azione dopo il salvataggio.

### DOCUMENT_WILL_PRINT {#DOCUMENT_WILL_PRINT}
```
public static final String DOCUMENT_WILL_PRINT
```

Un tipo di evento documento. Esegue un'azione prima della stampa.

### DOCUMENT_WILL_SAVE {#DOCUMENT_WILL_SAVE}
```
public static final String DOCUMENT_WILL_SAVE
```

Un tipo di evento documento. Esegue un'azione prima del salvataggio.

### PdfContentEditor {#PdfContentEditor--}
```
public PdfContentEditor()
```

Il costruttore dell'oggetto PdfContentEditor.

### PdfContentEditor {#PdfContentEditor-com.aspose.pdf.IDocument-}
Il costruttore dell'oggetto PdfContentEditor.

### addDocumentAdditionalAction {#addDocumentAdditionalAction-java.lang.String-java.lang.String-}
<p> Aggiunge un'azione aggiuntiva per l'evento del documento. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-}
<p> Aggiunge un allegato al documento senza annotazione. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.lang.String-java.lang.String-}
<p> Aggiunge un allegato al documento senza annotazione. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-}
Associa un flusso PDF per la modifica.

### bindPdf {#bindPdf-java.lang.String-}
Associa un file PDF per la modifica.

### changeViewerPreference {#changeViewerPreference-int-}
```
public void changeViewerPreference(int viewerAttribution)
```

<p> Modifica le preferenze di visualizzazione. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| viewerAttribution |  | L'attribuzione della vista definita nella classe ViewerPreference. |

### close {#close--}
```
public void close()
```

Chiude il documento aperto.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-}
Crea un collegamento per avviare un'applicazione nel documento PDF.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
Crea un collegamento per avviare un'applicazione nel documento PDF.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Crea un collegamento per avviare un'applicazione nel documento PDF.

### createBookmarksAction {#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-}
Crea un segnalibro con l'azione specificata.

### createCaret {#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
Crea un'annotazione cursore.

### createCustomActionLink {#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Crea un collegamento per azioni personalizzate nel documento PDF.

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-}
Crea un'annotazione di allegato file.

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}
Crea un'annotazione di allegato file.

### createFreeText {#createFreeText-java.awt.Rectangle-java.lang.String-int-}
Crea un'annotazione di testo libero nel documento PDF

### createJavaScriptLink {#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-}
Crea un collegamento a JavaScript nel documento PDF.

### createLine {#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-}
Crea un'annotazione di linea.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-}
Crea un collegamento locale nel documento PDF.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-}
Crea un collegamento locale nel documento PDF.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Crea un collegamento locale nel documento PDF.

### createMarkup {#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
Crea un'annotazione di markup nel documento PDF.

### createMovie {#createMovie-java.awt.Rectangle-java.lang.String-int-}


### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-}
Crea un collegamento a un'altra pagina di documento PDF.

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
Crea un collegamento a un'altra pagina di documento PDF.

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Crea un collegamento a un'altra pagina di documento PDF.

### createPolygon {#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Crea un'annotazione di poligono.

### createPolyLine {#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Crea un'annotazione di polilinea.

### createPopup {#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-}
Crea un'annotazione popup nel documento PDF.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-}
Crea un'annotazione di timbro di gomma.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-}
Crea un'annotazione di timbro di gomma.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
Crea un'annotazione di timbro di gomma.

### createSound {#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}


### createSquareCircle {#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-}
Crea un'annotazione quadrato-circolare.

### createText {#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-}
Crea un'annotazione di testo nel documento PDF

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-}
Crea un collegamento web in un documento PDF.

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
Crea un collegamento web in un documento PDF.

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Crea un collegamento web in un documento PDF.

### deleteAttachments {#deleteAttachments--}
```
public void deleteAttachments()
```

<p> Elimina tutti gli allegati nel documento PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage--}
```
public void deleteImage()
```

<p> Elimina tutte le immagini dal documento PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage-int-int:A-}
```
public void deleteImage(int pageNumber, int[] index)
```

<p> Elimina le immagini specificate nella pagina specificata. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber |  | Il numero di pagina su cui le immagini devono essere eliminate. |
| index |  | Un array che rappresenta gli indici delle immagini. |

### deleteStamp {#deleteStamp-int-int:A-}
```
public void deleteStamp(int pageNumber, int[] index)
```

<p> Elimina più timbri nella pagina specificata per indice del timbro. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber |  | Numero di pagina dove il timbro sarà eliminato. |
| index |  | Indici dei timbri. |

### deleteStampById {#deleteStampById-int-}
```
public void deleteStampById(int stampId)
```

<p> Elimina il timbro per ID da tutte le pagine del documento. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stampId |  | Identificatore del timbro che deve essere eliminato. |

### deleteStampById {#deleteStampById-int-int-}
```
public void deleteStampById(int pageNumber, int stampId)
```

<p> Elimina il timbro nella pagina specificata per ID del timbro. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber |  | Numero di pagina dove il timbro sarà eliminato. |
| stampId |  | Identificatore del timbro che deve essere eliminato. |

### deleteStampByIds {#deleteStampByIds-int:A-}
```
public void deleteStampByIds(int[] stampIds)
```

<p> Elimina i timbri con ID specificati da tutte le pagine del documento. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stampIds |  | Array di ID timbro. |

### deleteStampByIds {#deleteStampByIds-int-int:A-}
```
public void deleteStampByIds(int pageNumber, int[] stampIds)
```

<p> Elimina i timbri nella pagina specificata per più ID di timbro. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber |  | Numero di pagina dove i timbri saranno eliminati. |
| stampIds |  | Array di ID timbro. |

### drawCurve {#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Crea un'annotazione curva.

### extractLink {#extractLink--}
```
public List < Annotation > extractLink()
```

<p> Estrae la collezione di istanze Link contenute nel documento PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // lavora con l'istanza Link } </pre>

**Returns:**
La collezione di oggetti Link

### getReplaceTextStrategy {#getReplaceTextStrategy--}
```
public ReplaceTextStrategy getReplaceTextStrategy()
```

Ottieni un insieme di parametri per l'operazione di sostituzione del testo

**Returns:**
Elemento ReplaceTextStrategy

### getStamps {#getStamps-int-}
```
public StampInfo [] getStamps(int pageNumber)
```

Restituisce un array di timbri nella pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber |  | Numero di pagina dove i timbri saranno cercati. |

**Returns:**
Array di timbri.

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Ottiene le opzioni di modifica del testo.

**Returns:**
Elemento TextEditOptions

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

Ottiene le opzioni di sostituzione del testo.

**Returns:**
Elemento TextReplaceOptions

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Ottiene le opzioni di ricerca del testo.

**Returns:**
Elemento TextSearchOptions

### getViewerPreference {#getViewerPreference--}
```
public int getViewerPreference()
```

<p> Restituisce la preferenza di visualizzazione. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre>

**Returns:**
Restituisce l'insieme di flag ViewerPrefernece

### hideStampById {#hideStampById-int-int-}
```
public void hideStampById(int pageNumber, int stampId)
```

Nasconde il timbro. Dopo la nasconditura, la visibilità del timbro può essere ripristinata con il metodo ShowStampById.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber |  | Numero della pagina. |
| stampId |  | Identificatore del timbro che dovrebbe essere nascosto. |

### moveStamp {#moveStamp-int-int-double-double-}
```
public void moveStamp(int pageNumber, int stampIndex, double x, double y)
```

Cambia la posizione del timbro nella pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber |  | Numero della pagina. |
| stampIndex |  | Indice del timbro nella pagina. |
| x |  | Nuova posizione orizzontale del timbro. |
| y |  | Nuova posizione verticale del timbro. |

### moveStampById {#moveStampById-int-int-double-double-}
```
public void moveStampById(int pageNumber, int stampId, double x, double y)
```

Cambia la posizione del timbro nella pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber |  | Numero della pagina. |
| stampId |  | Identificatore del timbro che dovrebbe essere spostato. |
| x |  | Nuova posizione orizzontale del timbro nella pagina. |
| y |  | Nuova posizione verticale del timbro nella pagina. |

### removeDocumentOpenAction {#removeDocumentOpenAction--}
```
public void removeDocumentOpenAction()
```

<p> Rimuove l'azione di apertura dal documento. Questa operazione è utile quando si concatenano più documenti che utilizzano un'azione 'GoTo' esplicita all'avvio. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre>

### replaceImage {#replaceImage-int-int-java.lang.String-}
<p> Sostituisce l'immagine specificata nella pagina specificata del documento PDF con un'altra immagine. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-}
<p> Sostituisce il testo nel file PDF nella pagina specificata. </p> <hr> <pre> L'esempio dimostra come sostituire il testo in un documento PDF nella pagina specificata. // apri il documento Document doc = new Document(inFile); // crea l'oggetto PdfContentEditor per modificare il testo PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // modifica il testo editor.replaceText("hello world", 1, "hi world"); // salva il documento doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-}
<p> Sostituisce il testo nel file PDF nella pagina specificata. L'oggetto {@code TextState} (famiglia di caratteri, colore) può essere specificato per il testo sostituito. </p> <hr> <pre> L'esempio dimostra come sostituire il testo nella prima pagina del documento PDF e impostare le proprietà di testo {@code TextState} per il nuovo testo. // open document Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // change text with specified font editor.replaceText("hello world", 1, "hi world", textState); // save document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-}
<p> Sostituisce il testo nel file PDF. </p> <hr> <pre> L'esempio dimostra come sostituire il testo in un documento PDF. Per impostazione predefinita, sostituisce il primo testo trovato. // apri il documento Document doc = new Document(inFile); // crea l'oggetto PdfContentEditor per modificare il testo PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // cambia il testo editor.replaceText(\"hello world\", \"hi world\"); // salva il documento doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-int-}
<p> Sostituisce il testo nel file PDF e imposta la dimensione del font. </p> <hr> <pre> L'esempio dimostra come sostituire il testo e impostare la dimensione del font per il nuovo testo. // apri il documento Document doc = new Document(inFile); // Crea il font e contrassegnalo per l'incorporamento com.aspose.pdf.Font font = FontRepository.FindFont(\"Courier New\"); font.isEmbedded ( true); // crea l'oggetto PdfContentEditor per modificare il testo PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // cambia il testo con il font specificato editor.replaceText(\"hello world\", \"hi world\", 14); // salva il documento doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-}
<p> Sostituisce il testo nel file PDF utilizzando l'oggetto {@code TextState} specificato. </p> <hr> <pre> L'esempio dimostra come sostituire il testo e impostare le proprietà di testo {@code TextState} per il nuovo testo. Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); // change text with specified font editor.replaceText("hello world", "hi world", textState); // save document doc.save(outFile); </pre>

### setReplaceTextStrategy {#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-}
Imposta un insieme di parametri per l'operazione di sostituzione del testo

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Imposta le opzioni di modifica del testo.

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Imposta le opzioni di sostituzione del testo.

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Imposta le opzioni di ricerca del testo.

### showStampById {#showStampById-int-int-}
```
public void showStampById(int pageNumber, int stampId)
```

Mostra il timbro che era stato nascosto da HiddenStampById.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber |  | Numero della pagina. |
| stampId |  | Identificatore del timbro che dovrebbe essere mostrato. |
