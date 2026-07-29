---
title: "PdfAnnotationEditor"
linktitle: "PdfAnnotationEditor"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Klasse zur Arbeit mit PDF‑Dokumentannotationen (Kommentare) dar."
type: docs
weight: 360
url: /de/java/com.aspose.pdf.facades/pdfannotationeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfAnnotationEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfAnnotationEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfAnnotationEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfAnnotationEditor extends SaveableFacade
```

Stellt eine Klasse zur Arbeit mit PDF‑Dokumentannotationen (Kommentare) dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfAnnotationEditor](#PdfAnnotationEditor--) | Initialisiert ein neues {@code PdfAnnotationEditor}-Objekt. |
| [PdfAnnotationEditor](#PdfAnnotationEditor-com.aspose.pdf.IDocument-) | Initialisiert ein neues {@code PdfAnnotationEditor}-Objekt. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deleteAnnotation](#deleteAnnotation-java.lang.String-) | <p> Löscht die Annotation mit dem angegebenen Annotationsnamen. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38"); editor.save("example_out.pdf"); </pre> |
| [deleteAnnotations](#deleteAnnotations--) | <p> Löscht alle Annotationen im Dokument. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotations(); editor.save("example_out.pdf"); </pre> |
| [deleteAnnotations](#deleteAnnotations-java.lang.String-) | <p> Löscht alle Annotationen im Dokument. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotations(); editor.save("example_out.pdf"); </pre> |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | Exportiert Annotationen in einen Stream. |
| [exportAnnotationsXfdf](#exportAnnotationsXfdf-java.io.OutputStream-int-int-com.aspose.pdf.AnnotationType:A-) | <p> Exportiert den Inhalt der angegebenen Annotationsarten in XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; OutputStream stream = new FileOutputStream("example.xfdf"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre> |
| [exportAnnotationsXfdf](#exportAnnotationsXfdf-java.io.OutputStream-int-int-java.lang.String:A-) | <p> Exportiert den Inhalt der angegebenen Annotationsarten in XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); String[] annotTypes = new String[] {"Text", "Highlight"}; OutputStream stream = new FileOutputStream("example.xfdf"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre> |
| [extractAnnotations](#extractAnnotations-int-int-com.aspose.pdf.AnnotationType:A-) | <p> Gibt die Liste der Annotationen der angegebenen Typen zurück. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre> |
| [extractAnnotations](#extractAnnotations-int-int-java.lang.String:A-) | <p> Gibt die Liste der Annotationen der angegebenen Typen zurück. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); String[] annotTypes = new String[] {"Text", "Highlight"}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre> |
| [flatteningAnnotations](#flatteningAnnotations--) | <p> Flacht alle Annotationen im Dokument ab. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre> |
| [flatteningAnnotations](#flatteningAnnotations-com.aspose.pdf.Form.FlattenSettings-) | <p> Flacht alle Annotationen im Dokument ab. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre> |
| [flatteningAnnotations](#flatteningAnnotations-int-int-com.aspose.pdf.AnnotationType:A-) | <p> Flacht alle Annotationen im Dokument ab. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.io.InputStream-) | <p> Importiert alle Annotationen aus dem XFDF-Datenstrom. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf")); editor.save("example_out.pdf"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.io.InputStream-com.aspose.pdf.AnnotationType:A-) | <p> Importiert die angegebenen Anmerkungen aus dem XFDF-Datenstrom. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line }; editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf"), annotTypes); editor.save("example_out.pdf"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.lang.String-com.aspose.pdf.AnnotationType:A-) | <p> Importiert die angegebenen Anmerkungen aus der XFDF-Datei. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotationFromXfdf("annots.xfdf", annotTypes); editor.save("example_out.pdf"); </pre> |
| [importAnnotations](#importAnnotations-java.io.InputStream:A-) | <p> Importiert Anmerkungen in das Dokument aus einem Array von anderen PDF-Dokument-Streams. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream("with_annots1.pdf"); streams[1]= new FileInputStream("with_annots2.pdf"); editor.importAnnotations(streams); editor.save("example_out.pdf"); streams[0].Close(); streams[1].Close(); </pre> |
| [importAnnotations](#importAnnotations-java.io.InputStream:A-com.aspose.pdf.AnnotationType:A-) | <p> Importiert die angegebenen Anmerkungen in das Dokument aus einem Array von anderen PDF-Dokument-Streams. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream("with_annots1.pdf"); streams[1]= new FileInputStream("with_annots2.pdf"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(streams, annotTypes); editor.save("example_out.pdf"); streams[0].close(); streams[1].close(); </pre> |
| [importAnnotations](#importAnnotations-java.lang.String:A-) | <p> Importiert Anmerkungen in das Dokument aus einem Array anderer PDF-Dokumente. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"}; editor.importAnnotations(paths); editor.save("example_out.pdf"); </pre> |
| [importAnnotations](#importAnnotations-java.lang.String:A-com.aspose.pdf.AnnotationType:A-) | <p> Importiert die angegebenen Anmerkungen in das Dokument aus einem Array anderer PDF-Dokumente. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"}; int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(paths, annotTypes); editor.save("example_out.pdf"); </pre> |
| [importAnnotationsFromFdf](#importAnnotationsFromFdf-java.lang.String-) | Importiert alle Anmerkungen aus einer FDF-Datei. PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationsFromFdf("annots.fdf"); editor.save("example_out.pdf"); |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | <p> Importiert alle Annotationen aus dem XFDF-Datenstrom. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf")); editor.save("example_out.pdf"); </pre> |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | <p> Importiert alle Anmerkungen aus der XFDF-Datei. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationsFromXfdf("annots.xfdf"); editor.save("example_out.pdf"); </pre> |
| [modifyAnnotations](#modifyAnnotations-int-int-com.aspose.pdf.Annotation-) | <p> Modifiziert die Anmerkungen des angegebenen Typs im angegebenen Seitenbereich. Es unterstützt die Änderung folgender Anmerkungseigenschaften: Modified, Title, Contents, Color, Subject und Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); TextAnnotation annot = new TextAnnotation(); annot.setModified ( new Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor ( Color.RED); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, annot); editor.save("example_out.pdf"); </pre> |
| [modifyAnnotations](#modifyAnnotations-int-int-int-com.aspose.pdf.Annotation-) | "Verwenden Sie stattdessen modifyAnnotations(int start, int end, Annotation annotation)." <p> Modifiziert die Anmerkungen des angegebenen Typs im angegebenen Seitenbereich. Es unterstützt die Änderung folgender Anmerkungseigenschaften: Modified, Title, Contents, Color, Subject und Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); com.aspose.pdf.TextAnnotation annot = new com.aspose.pdf.TextAnnotation(); annot.setModified ( new java.util.Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor (com.aspose.pdf.Color.getRed()); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, com.aspose.pdf.AnnotationType.Text, annot); editor.save("example_out.pdf"); </pre> |
| [modifyAnnotationsAuthor](#modifyAnnotationsAuthor-int-int-java.lang.String-java.lang.String-) | <p> Modifiziert den Autor der Anmerkungen im angegebenen Seitenbereich. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.modifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR"); editor.save("example_out.pdf"); </pre> |
| [redactArea](#redactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-) | Schwärzt einen Bereich auf der angegebenen Seite. |
| [redactExactArea](#redactExactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-) | Schwärzt einen Bereich auf der angegebenen Seite. |
| [save](#save-java.io.OutputStream-) | Speichert das Ergebnis-PDF in einen Stream. |
| [save](#save-java.lang.String-) | Speichert das Ergebnis-PDF in einer Datei. |

### PdfAnnotationEditor {#PdfAnnotationEditor--}
```
public PdfAnnotationEditor()
```

Initialisiert ein neues {@code PdfAnnotationEditor}-Objekt.

### PdfAnnotationEditor {#PdfAnnotationEditor-com.aspose.pdf.IDocument-}
Initialisiert ein neues {@code PdfAnnotationEditor}-Objekt.

### deleteAnnotation {#deleteAnnotation-java.lang.String-}
<p> Löscht die Annotation mit dem angegebenen Annotationsnamen. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38"); editor.save("example_out.pdf"); </pre>

### deleteAnnotations {#deleteAnnotations--}
```
public void deleteAnnotations()
```

<p> Löscht alle Annotationen im Dokument. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotations(); editor.save("example_out.pdf"); </pre>

### deleteAnnotations {#deleteAnnotations-java.lang.String-}
<p> Löscht alle Annotationen im Dokument. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotations(); editor.save("example_out.pdf"); </pre>

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.io.OutputStream-}
Exportiert Annotationen in einen Stream.

### exportAnnotationsXfdf {#exportAnnotationsXfdf-java.io.OutputStream-int-int-com.aspose.pdf.AnnotationType:A-}
<p> Exportiert den Inhalt der angegebenen Annotationsarten in XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; OutputStream stream = new FileOutputStream("example.xfdf"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre>

### exportAnnotationsXfdf {#exportAnnotationsXfdf-java.io.OutputStream-int-int-java.lang.String:A-}
<p> Exportiert den Inhalt der angegebenen Annotationsarten in XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); String[] annotTypes = new String[] {"Text", "Highlight"}; OutputStream stream = new FileOutputStream("example.xfdf"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre>

### extractAnnotations {#extractAnnotations-int-int-com.aspose.pdf.AnnotationType:A-}
<p> Gibt die Liste der Annotationen der angegebenen Typen zurück. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre>

### extractAnnotations {#extractAnnotations-int-int-java.lang.String:A-}
<p> Gibt die Liste der Annotationen der angegebenen Typen zurück. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); String[] annotTypes = new String[] {"Text", "Highlight"}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre>

### flatteningAnnotations {#flatteningAnnotations--}
```
public void flatteningAnnotations()
```

<p> Flacht alle Annotationen im Dokument ab. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre>

### flatteningAnnotations {#flatteningAnnotations-com.aspose.pdf.Form.FlattenSettings-}
<p> Flacht alle Annotationen im Dokument ab. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre>

### flatteningAnnotations {#flatteningAnnotations-int-int-com.aspose.pdf.AnnotationType:A-}
<p> Flacht alle Annotationen im Dokument ab. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.io.InputStream-}
<p> Importiert alle Annotationen aus dem XFDF-Datenstrom. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf")); editor.save("example_out.pdf"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.io.InputStream-com.aspose.pdf.AnnotationType:A-}
<p> Importiert die angegebenen Anmerkungen aus dem XFDF-Datenstrom. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line }; editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf"), annotTypes); editor.save("example_out.pdf"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.lang.String-com.aspose.pdf.AnnotationType:A-}
<p> Importiert die angegebenen Anmerkungen aus der XFDF-Datei. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotationFromXfdf("annots.xfdf", annotTypes); editor.save("example_out.pdf"); </pre>

### importAnnotations {#importAnnotations-java.io.InputStream:A-}
<p> Importiert Anmerkungen in das Dokument aus einem Array von anderen PDF-Dokument-Streams. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream("with_annots1.pdf"); streams[1]= new FileInputStream("with_annots2.pdf"); editor.importAnnotations(streams); editor.save("example_out.pdf"); streams[0].Close(); streams[1].Close(); </pre>

### importAnnotations {#importAnnotations-java.io.InputStream:A-com.aspose.pdf.AnnotationType:A-}
<p> Importiert die angegebenen Anmerkungen in das Dokument aus einem Array von anderen PDF-Dokument-Streams. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream("with_annots1.pdf"); streams[1]= new FileInputStream("with_annots2.pdf"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(streams, annotTypes); editor.save("example_out.pdf"); streams[0].close(); streams[1].close(); </pre>

### importAnnotations {#importAnnotations-java.lang.String:A-}
<p> Importiert Anmerkungen in das Dokument aus einem Array anderer PDF-Dokumente. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"}; editor.importAnnotations(paths); editor.save("example_out.pdf"); </pre>

### importAnnotations {#importAnnotations-java.lang.String:A-com.aspose.pdf.AnnotationType:A-}
<p> Importiert die angegebenen Anmerkungen in das Dokument aus einem Array anderer PDF-Dokumente. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"}; int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(paths, annotTypes); editor.save("example_out.pdf"); </pre>

### importAnnotationsFromFdf {#importAnnotationsFromFdf-java.lang.String-}
Importiert alle Anmerkungen aus einer FDF-Datei. PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationsFromFdf("annots.fdf"); editor.save("example_out.pdf");

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.io.InputStream-}
<p> Importiert alle Annotationen aus dem XFDF-Datenstrom. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf")); editor.save("example_out.pdf"); </pre>

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
<p> Importiert alle Anmerkungen aus der XFDF-Datei. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationsFromXfdf("annots.xfdf"); editor.save("example_out.pdf"); </pre>

### modifyAnnotations {#modifyAnnotations-int-int-com.aspose.pdf.Annotation-}
<p> Modifiziert die Anmerkungen des angegebenen Typs im angegebenen Seitenbereich. Es unterstützt die Änderung folgender Anmerkungseigenschaften: Modified, Title, Contents, Color, Subject und Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); TextAnnotation annot = new TextAnnotation(); annot.setModified ( new Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor ( Color.RED); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, annot); editor.save("example_out.pdf"); </pre>

### modifyAnnotations {#modifyAnnotations-int-int-int-com.aspose.pdf.Annotation-}
"Verwenden Sie stattdessen modifyAnnotations(int start, int end, Annotation annotation)." <p> Modifiziert die Anmerkungen des angegebenen Typs im angegebenen Seitenbereich. Es unterstützt die Änderung folgender Anmerkungseigenschaften: Modified, Title, Contents, Color, Subject und Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); com.aspose.pdf.TextAnnotation annot = new com.aspose.pdf.TextAnnotation(); annot.setModified ( new java.util.Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor (com.aspose.pdf.Color.getRed()); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, com.aspose.pdf.AnnotationType.Text, annot); editor.save("example_out.pdf"); </pre>

### modifyAnnotationsAuthor {#modifyAnnotationsAuthor-int-int-java.lang.String-java.lang.String-}
<p> Modifiziert den Autor der Anmerkungen im angegebenen Seitenbereich. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.modifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR"); editor.save("example_out.pdf"); </pre>

### redactArea {#redactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-}
Schwärzt einen Bereich auf der angegebenen Seite.

### redactExactArea {#redactExactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-}
Schwärzt einen Bereich auf der angegebenen Seite.

### save {#save-java.io.OutputStream-}
Speichert das Ergebnis-PDF in einen Stream.

### save {#save-java.lang.String-}
Speichert das Ergebnis-PDF in einer Datei.
