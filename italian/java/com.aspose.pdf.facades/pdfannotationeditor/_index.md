---
title: "PdfAnnotationEditor"
linktitle: "PdfAnnotationEditor"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe per lavorare con le annotazioni (commenti) dei documenti PDF."
type: docs
weight: 360
url: /it/java/com.aspose.pdf.facades/pdfannotationeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfAnnotationEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfAnnotationEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfAnnotationEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfAnnotationEditor extends SaveableFacade
```

Rappresenta una classe per lavorare con le annotazioni (commenti) dei documenti PDF.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfAnnotationEditor](#PdfAnnotationEditor--) | Inizializza un nuovo oggetto {@code PdfAnnotationEditor}. |
| [PdfAnnotationEditor](#PdfAnnotationEditor-com.aspose.pdf.IDocument-) | Inizializza un nuovo oggetto {@code PdfAnnotationEditor}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deleteAnnotation](#deleteAnnotation-java.lang.String-) | <p> Elimina l'annotazione con il nome di annotazione specificato. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.deleteAnnotation(\"4cfa69cd-9bff-49e0-9005-e22a77cebf38\"); editor.save(\"example_out.pdf\"); </pre> |
| [deleteAnnotations](#deleteAnnotations--) | <p> Elimina tutte le annotazioni nel documento. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.deleteAnnotations(); editor.save(\"example_out.pdf\"); </pre> |
| [deleteAnnotations](#deleteAnnotations-java.lang.String-) | <p> Elimina tutte le annotazioni nel documento. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.deleteAnnotations(); editor.save(\"example_out.pdf\"); </pre> |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | Esporta le annotazioni su stream. |
| [exportAnnotationsXfdf](#exportAnnotationsXfdf-java.io.OutputStream-int-int-com.aspose.pdf.AnnotationType:A-) | <p> Esporta il contenuto dei tipi di annotazione specificati in XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; OutputStream stream = new FileOutputStream(\"example.xfdf\"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre> |
| [exportAnnotationsXfdf](#exportAnnotationsXfdf-java.io.OutputStream-int-int-java.lang.String:A-) | <p> Esporta il contenuto dei tipi di annotazione specificati in XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); String[] annotTypes = new String[] {\"Text\", \"Highlight\"}; OutputStream stream = new FileOutputStream(\"example.xfdf\"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre> |
| [extractAnnotations](#extractAnnotations-int-int-com.aspose.pdf.AnnotationType:A-) | <p> Ottiene l'elenco delle annotazioni dei tipi specificati. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre> |
| [extractAnnotations](#extractAnnotations-int-int-java.lang.String:A-) | <p> Ottiene l'elenco delle annotazioni dei tipi specificati. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); String[] annotTypes = new String[] {\"Text\", \"Highlight\"}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre> |
| [flatteningAnnotations](#flatteningAnnotations--) | <p> Appiattisce tutte le annotazioni nel documento. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.flatteningAnnotations(); editor.save(example_out.pdf\"); </pre> |
| [flatteningAnnotations](#flatteningAnnotations-com.aspose.pdf.Form.FlattenSettings-) | <p> Appiattisce tutte le annotazioni nel documento. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.flatteningAnnotations(); editor.save(example_out.pdf\"); </pre> |
| [flatteningAnnotations](#flatteningAnnotations-int-int-com.aspose.pdf.AnnotationType:A-) | <p> Appiattisce tutte le annotazioni nel documento. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.flatteningAnnotations(); editor.save(example_out.pdf\"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.io.InputStream-) | <p> Importa tutte le annotazioni dal flusso di dati XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.importAnnotationFromXfdf(new FileInputStream(\"annots.xfdf\")); editor.save(\"example_out.pdf\"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.io.InputStream-com.aspose.pdf.AnnotationType:A-) | <p> Importa le annotazioni specificate dal flusso di dati XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); int[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line }; editor.importAnnotationFromXfdf(new FileInputStream(\"annots.xfdf\"), annotTypes); editor.save(\"example_out.pdf\"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.lang.String-com.aspose.pdf.AnnotationType:A-) | <p> Importa le annotazioni specificate dal file XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotationFromXfdf(\"annots.xfdf\", annotTypes); editor.save(\"example_out.pdf\"); </pre> |
| [importAnnotations](#importAnnotations-java.io.InputStream:A-) | <p> Importa le annotazioni nel documento da un array di flussi di altri documenti PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream(\"with_annots1.pdf\"); streams[1]= new FileInputStream(\"with_annots2.pdf\"); editor.importAnnotations(streams); editor.save(\"example_out.pdf\"); streams[0].Close(); streams[1].Close(); </pre> |
| [importAnnotations](#importAnnotations-java.io.InputStream:A-com.aspose.pdf.AnnotationType:A-) | <p> Importa le annotazioni specificate nel documento da un array di flussi di altri documenti PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream(\"with_annots1.pdf\"); streams[1]= new FileInputStream(\"with_annots2.pdf\"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(streams, annotTypes); editor.save(\"example_out.pdf\"); streams[0].close(); streams[1].close(); </pre> |
| [importAnnotations](#importAnnotations-java.lang.String:A-) | <p> Importa le annotazioni nel documento da un array di altri documenti PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); string[] paths = new string[2] {\"with_annots1.pdf\", \"with_annots2.pdf\"}; editor.importAnnotations(paths); editor.save(\"example_out.pdf\"); </pre> |
| [importAnnotations](#importAnnotations-java.lang.String:A-com.aspose.pdf.AnnotationType:A-) | <p> Importa le annotazioni specificate nel documento da un array di altri documenti PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); string[] paths = new string[2] {\"with_annots1.pdf\", \"with_annots2.pdf\"}; int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(paths, annotTypes); editor.save(\"example_out.pdf\"); </pre> |
| [importAnnotationsFromFdf](#importAnnotationsFromFdf-java.lang.String-) | Importa tutte le annotazioni dal file FDF. PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.importAnnotationsFromFdf(\"annots.fdf\"); editor.save(\"example_out.pdf\"); |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | <p> Importa tutte le annotazioni dal flusso di dati XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.importAnnotationFromXfdf(new FileInputStream(\"annots.xfdf\")); editor.save(\"example_out.pdf\"); </pre> |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | <p> Importa tutte le annotazioni dal file XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.importAnnotationsFromXfdf(\"annots.xfdf\"); editor.save(\"example_out.pdf\"); </pre> |
| [modifyAnnotations](#modifyAnnotations-int-int-com.aspose.pdf.Annotation-) | <p> Modifica le annotazioni del tipo specificato nell'intervallo di pagine specificato. Supporta la modifica delle seguenti proprietà dell'annotazione: Modified, Title, Contents, Color, Subject e Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); TextAnnotation annot = new TextAnnotation(); annot.setModified ( new Date()); annot.setTitle ( \"NEW AUTHOR\"); annot.setContents ( \"NEW CONTENTS\"); annot.setColor ( Color.RED); annot.setSubject ( \"NEW SUBJECT\"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, annot); editor.save(\"example_out.pdf\"); </pre> |
| [modifyAnnotations](#modifyAnnotations-int-int-int-com.aspose.pdf.Annotation-) | \"Usa modifyAnnotations(int start, int end, Annotation annotation) invece.\" <p> Modifica le annotazioni del tipo specificato nell'intervallo di pagine specificato. Supporta la modifica delle seguenti proprietà dell'annotazione: Modified, Title, Contents, Color, Subject e Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); com.aspose.pdf.TextAnnotation annot = new com.aspose.pdf.TextAnnotation(); annot.setModified ( new java.util.Date()); annot.setTitle ( \"NEW AUTHOR\"); annot.setContents ( \"NEW CONTENTS\"); annot.setColor (com.aspose.pdf.Color.getRed()); annot.setSubject ( \"NEW SUBJECT\"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, com.aspose.pdf.AnnotationType.Text, annot); editor.save(\"example_out.pdf\"); </pre> |
| [modifyAnnotationsAuthor](#modifyAnnotationsAuthor-int-int-java.lang.String-java.lang.String-) | <p> Modifica l'autore delle annotazioni nell'intervallo di pagine specificato. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.modifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR"); editor.save("example_out.pdf"); </pre> |
| [redactArea](#redactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-) | Cancella l'area nella pagina specificata. |
| [redactExactArea](#redactExactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-) | Cancella l'area nella pagina specificata. |
| [save](#save-java.io.OutputStream-) | Salva il PDF risultante nello stream. |
| [save](#save-java.lang.String-) | Salva il PDF risultante su file. |

### PdfAnnotationEditor {#PdfAnnotationEditor--}
```
public PdfAnnotationEditor()
```

Inizializza un nuovo oggetto {@code PdfAnnotationEditor}.

### PdfAnnotationEditor {#PdfAnnotationEditor-com.aspose.pdf.IDocument-}
Inizializza un nuovo oggetto {@code PdfAnnotationEditor}.

### deleteAnnotation {#deleteAnnotation-java.lang.String-}
<p> Elimina l'annotazione con il nome di annotazione specificato. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.deleteAnnotation(\"4cfa69cd-9bff-49e0-9005-e22a77cebf38\"); editor.save(\"example_out.pdf\"); </pre>

### deleteAnnotations {#deleteAnnotations--}
```
public void deleteAnnotations()
```

<p> Elimina tutte le annotazioni nel documento. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.deleteAnnotations(); editor.save(\"example_out.pdf\"); </pre>

### deleteAnnotations {#deleteAnnotations-java.lang.String-}
<p> Elimina tutte le annotazioni nel documento. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.deleteAnnotations(); editor.save(\"example_out.pdf\"); </pre>

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.io.OutputStream-}
Esporta le annotazioni su stream.

### exportAnnotationsXfdf {#exportAnnotationsXfdf-java.io.OutputStream-int-int-com.aspose.pdf.AnnotationType:A-}
<p> Esporta il contenuto dei tipi di annotazione specificati in XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; OutputStream stream = new FileOutputStream(\"example.xfdf\"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre>

### exportAnnotationsXfdf {#exportAnnotationsXfdf-java.io.OutputStream-int-int-java.lang.String:A-}
<p> Esporta il contenuto dei tipi di annotazione specificati in XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); String[] annotTypes = new String[] {\"Text\", \"Highlight\"}; OutputStream stream = new FileOutputStream(\"example.xfdf\"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre>

### extractAnnotations {#extractAnnotations-int-int-com.aspose.pdf.AnnotationType:A-}
<p> Ottiene l'elenco delle annotazioni dei tipi specificati. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre>

### extractAnnotations {#extractAnnotations-int-int-java.lang.String:A-}
<p> Ottiene l'elenco delle annotazioni dei tipi specificati. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); String[] annotTypes = new String[] {\"Text\", \"Highlight\"}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre>

### flatteningAnnotations {#flatteningAnnotations--}
```
public void flatteningAnnotations()
```

<p> Appiattisce tutte le annotazioni nel documento. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.flatteningAnnotations(); editor.save(example_out.pdf\"); </pre>

### flatteningAnnotations {#flatteningAnnotations-com.aspose.pdf.Form.FlattenSettings-}
<p> Appiattisce tutte le annotazioni nel documento. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.flatteningAnnotations(); editor.save(example_out.pdf\"); </pre>

### flatteningAnnotations {#flatteningAnnotations-int-int-com.aspose.pdf.AnnotationType:A-}
<p> Appiattisce tutte le annotazioni nel documento. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.flatteningAnnotations(); editor.save(example_out.pdf\"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.io.InputStream-}
<p> Importa tutte le annotazioni dal flusso di dati XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.importAnnotationFromXfdf(new FileInputStream(\"annots.xfdf\")); editor.save(\"example_out.pdf\"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.io.InputStream-com.aspose.pdf.AnnotationType:A-}
<p> Importa le annotazioni specificate dal flusso di dati XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); int[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line }; editor.importAnnotationFromXfdf(new FileInputStream(\"annots.xfdf\"), annotTypes); editor.save(\"example_out.pdf\"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.lang.String-com.aspose.pdf.AnnotationType:A-}
<p> Importa le annotazioni specificate dal file XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotationFromXfdf(\"annots.xfdf\", annotTypes); editor.save(\"example_out.pdf\"); </pre>

### importAnnotations {#importAnnotations-java.io.InputStream:A-}
<p> Importa le annotazioni nel documento da un array di flussi di altri documenti PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream(\"with_annots1.pdf\"); streams[1]= new FileInputStream(\"with_annots2.pdf\"); editor.importAnnotations(streams); editor.save(\"example_out.pdf\"); streams[0].Close(); streams[1].Close(); </pre>

### importAnnotations {#importAnnotations-java.io.InputStream:A-com.aspose.pdf.AnnotationType:A-}
<p> Importa le annotazioni specificate nel documento da un array di flussi di altri documenti PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream(\"with_annots1.pdf\"); streams[1]= new FileInputStream(\"with_annots2.pdf\"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(streams, annotTypes); editor.save(\"example_out.pdf\"); streams[0].close(); streams[1].close(); </pre>

### importAnnotations {#importAnnotations-java.lang.String:A-}
<p> Importa le annotazioni nel documento da un array di altri documenti PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); string[] paths = new string[2] {\"with_annots1.pdf\", \"with_annots2.pdf\"}; editor.importAnnotations(paths); editor.save(\"example_out.pdf\"); </pre>

### importAnnotations {#importAnnotations-java.lang.String:A-com.aspose.pdf.AnnotationType:A-}
<p> Importa le annotazioni specificate nel documento da un array di altri documenti PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); string[] paths = new string[2] {\"with_annots1.pdf\", \"with_annots2.pdf\"}; int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(paths, annotTypes); editor.save(\"example_out.pdf\"); </pre>

### importAnnotationsFromFdf {#importAnnotationsFromFdf-java.lang.String-}
Importa tutte le annotazioni dal file FDF. PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.importAnnotationsFromFdf(\"annots.fdf\"); editor.save(\"example_out.pdf\");

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.io.InputStream-}
<p> Importa tutte le annotazioni dal flusso di dati XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.importAnnotationFromXfdf(new FileInputStream(\"annots.xfdf\")); editor.save(\"example_out.pdf\"); </pre>

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
<p> Importa tutte le annotazioni dal file XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); editor.importAnnotationsFromXfdf(\"annots.xfdf\"); editor.save(\"example_out.pdf\"); </pre>

### modifyAnnotations {#modifyAnnotations-int-int-com.aspose.pdf.Annotation-}
<p> Modifica le annotazioni del tipo specificato nell'intervallo di pagine specificato. Supporta la modifica delle seguenti proprietà dell'annotazione: Modified, Title, Contents, Color, Subject e Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); TextAnnotation annot = new TextAnnotation(); annot.setModified ( new Date()); annot.setTitle ( \"NEW AUTHOR\"); annot.setContents ( \"NEW CONTENTS\"); annot.setColor ( Color.RED); annot.setSubject ( \"NEW SUBJECT\"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, annot); editor.save(\"example_out.pdf\"); </pre>

### modifyAnnotations {#modifyAnnotations-int-int-int-com.aspose.pdf.Annotation-}
\"Usa modifyAnnotations(int start, int end, Annotation annotation) invece.\" <p> Modifica le annotazioni del tipo specificato nell'intervallo di pagine specificato. Supporta la modifica delle seguenti proprietà dell'annotazione: Modified, Title, Contents, Color, Subject e Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf(\"example.pdf\"); com.aspose.pdf.TextAnnotation annot = new com.aspose.pdf.TextAnnotation(); annot.setModified ( new java.util.Date()); annot.setTitle ( \"NEW AUTHOR\"); annot.setContents ( \"NEW CONTENTS\"); annot.setColor (com.aspose.pdf.Color.getRed()); annot.setSubject ( \"NEW SUBJECT\"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, com.aspose.pdf.AnnotationType.Text, annot); editor.save(\"example_out.pdf\"); </pre>

### modifyAnnotationsAuthor {#modifyAnnotationsAuthor-int-int-java.lang.String-java.lang.String-}
<p> Modifica l'autore delle annotazioni nell'intervallo di pagine specificato. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.modifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR"); editor.save("example_out.pdf"); </pre>

### redactArea {#redactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-}
Cancella l'area nella pagina specificata.

### redactExactArea {#redactExactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-}
Cancella l'area nella pagina specificata.

### save {#save-java.io.OutputStream-}
Salva il PDF risultante nello stream.

### save {#save-java.lang.String-}
Salva il PDF risultante su file.
