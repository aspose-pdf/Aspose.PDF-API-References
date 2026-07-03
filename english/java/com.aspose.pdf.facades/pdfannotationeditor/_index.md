---
title: PdfAnnotationEditor
second_title: Aspose.PDF for Java API Reference
description: Represents a class for work with PDF document annotations (comments).
type: docs
weight: 360
url: /java/com.aspose.pdf.facades/pdfannotationeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfAnnotationEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfAnnotationEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfAnnotationEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfAnnotationEditor extends SaveableFacade
```

Represents a class for work with PDF document annotations (comments).

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfAnnotationEditor](#PdfAnnotationEditor--) | Initializes new {@code PdfAnnotationEditor} object. |
| [PdfAnnotationEditor](#PdfAnnotationEditor-com.aspose.pdf.IDocument-) | Initializes new {@code PdfAnnotationEditor} object. |

## Methods

| Method | Description |
| --- | --- |
| [deleteAnnotation](#deleteAnnotation-java.lang.String-) | <p> Deletes the annotation with specified annotation name. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38"); editor.save("example_out.pdf"); </pre> |
| [deleteAnnotations](#deleteAnnotations--) | <p> Deletes all annotations in the document. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotations(); editor.save("example_out.pdf"); </pre> |
| [deleteAnnotations](#deleteAnnotations-java.lang.String-) | <p> Deletes all annotations in the document. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotations(); editor.save("example_out.pdf"); </pre> |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | Exports annotations to stream. |
| [exportAnnotationsXfdf](#exportAnnotationsXfdf-java.io.OutputStream-int-int-com.aspose.pdf.AnnotationType:A-) | <p> Exports the content of the specified annotation types into XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; OutputStream stream = new FileOutputStream("example.xfdf"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre> |
| [exportAnnotationsXfdf](#exportAnnotationsXfdf-java.io.OutputStream-int-int-java.lang.String:A-) | <p> Exports the content of the specified annotations types into XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); String[] annotTypes = new String[] {"Text", "Highlight"}; OutputStream stream = new FileOutputStream("example.xfdf"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre> |
| [extractAnnotations](#extractAnnotations-int-int-com.aspose.pdf.AnnotationType:A-) | <p> Gets the list of annotations of the specified types. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre> |
| [extractAnnotations](#extractAnnotations-int-int-java.lang.String:A-) | <p> Gets the list of annotations of the specified types. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); String[] annotTypes = new String[] {"Text", "Highlight"}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre> |
| [flatteningAnnotations](#flatteningAnnotations--) | <p> Flattens all annotations in the document. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre> |
| [flatteningAnnotations](#flatteningAnnotations-com.aspose.pdf.Form.FlattenSettings-) | <p> Flattens all annotations in the document. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre> |
| [flatteningAnnotations](#flatteningAnnotations-int-int-com.aspose.pdf.AnnotationType:A-) | <p> Flattens all annotations in the document. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.io.InputStream-) | <p> Imports all annotations from XFDF data stream. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf")); editor.save("example_out.pdf"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.io.InputStream-com.aspose.pdf.AnnotationType:A-) | <p> Imports the specified annotations from XFDF data stream. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line }; editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf"), annotTypes); editor.save("example_out.pdf"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.lang.String-com.aspose.pdf.AnnotationType:A-) | <p> Imports the specified annotations from XFDF file. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotationFromXfdf("annots.xfdf", annotTypes); editor.save("example_out.pdf"); </pre> |
| [importAnnotations](#importAnnotations-java.io.InputStream:A-) | <p> Imports annotations into document from array of another PDF document streams. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream("with_annots1.pdf"); streams[1]= new FileInputStream("with_annots2.pdf"); editor.importAnnotations(streams); editor.save("example_out.pdf"); streams[0].Close(); streams[1].Close(); </pre> |
| [importAnnotations](#importAnnotations-java.io.InputStream:A-com.aspose.pdf.AnnotationType:A-) | <p> Imports the specified annotations into document from array of another PDF document streams. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream("with_annots1.pdf"); streams[1]= new FileInputStream("with_annots2.pdf"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(streams, annotTypes); editor.save("example_out.pdf"); streams[0].close(); streams[1].close(); </pre> |
| [importAnnotations](#importAnnotations-java.lang.String:A-) | <p> Imports annotations into document from array of another PDF documents. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"}; editor.importAnnotations(paths); editor.save("example_out.pdf"); </pre> |
| [importAnnotations](#importAnnotations-java.lang.String:A-com.aspose.pdf.AnnotationType:A-) | <p> Imports the specified annotations into document from array of another PDF documents. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"}; int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(paths, annotTypes); editor.save("example_out.pdf"); </pre> |
| [importAnnotationsFromFdf](#importAnnotationsFromFdf-java.lang.String-) | Imports all annotations from FDF file. PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationsFromFdf("annots.fdf"); editor.save("example_out.pdf"); |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | <p> Imports all annotations from XFDF data stream. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf")); editor.save("example_out.pdf"); </pre> |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | <p> Imports all annotations from XFDF file. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationsFromXfdf("annots.xfdf"); editor.save("example_out.pdf"); </pre> |
| [modifyAnnotations](#modifyAnnotations-int-int-com.aspose.pdf.Annotation-) | <p> Modifies the annotations of the specifed type on the specified page range. It supports to modify next annotation properties: Modified, Title, Contents, Color, Subject and Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); TextAnnotation annot = new TextAnnotation(); annot.setModified ( new Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor ( Color.RED); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, annot); editor.save("example_out.pdf"); </pre> |
| [modifyAnnotations](#modifyAnnotations-int-int-int-com.aspose.pdf.Annotation-) | "Use modifyAnnotations(int start, int end, Annotation annotation) instead." <p> Modifies the annotations of the specifed type on the specified page range. It supports to modify next annotation properties: Modified, Title, Contents, Color, Subject and Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); com.aspose.pdf.TextAnnotation annot = new com.aspose.pdf.TextAnnotation(); annot.setModified ( new java.util.Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor (com.aspose.pdf.Color.getRed()); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, com.aspose.pdf.AnnotationType.Text, annot); editor.save("example_out.pdf"); </pre> |
| [modifyAnnotationsAuthor](#modifyAnnotationsAuthor-int-int-java.lang.String-java.lang.String-) | <p> Modifies the author of annotations on the specified page range. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.modifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR"); editor.save("example_out.pdf"); </pre> |
| [redactArea](#redactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-) | Redacts area on the specified page. |
| [redactExactArea](#redactExactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-) | Redacts area on the specified page. |
| [save](#save-java.io.OutputStream-) | Saves the result PDF to stream. |
| [save](#save-java.lang.String-) | Saves the result PDF to file. |

### PdfAnnotationEditor {#PdfAnnotationEditor--}
```
public PdfAnnotationEditor()
```

Initializes new {@code PdfAnnotationEditor} object.

### PdfAnnotationEditor {#PdfAnnotationEditor-com.aspose.pdf.IDocument-}
Initializes new {@code PdfAnnotationEditor} object.

### deleteAnnotation {#deleteAnnotation-java.lang.String-}
<p> Deletes the annotation with specified annotation name. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38"); editor.save("example_out.pdf"); </pre>

### deleteAnnotations {#deleteAnnotations--}
```
public void deleteAnnotations()
```

<p> Deletes all annotations in the document. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotations(); editor.save("example_out.pdf"); </pre>

### deleteAnnotations {#deleteAnnotations-java.lang.String-}
<p> Deletes all annotations in the document. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotations(); editor.save("example_out.pdf"); </pre>

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.io.OutputStream-}
Exports annotations to stream.

### exportAnnotationsXfdf {#exportAnnotationsXfdf-java.io.OutputStream-int-int-com.aspose.pdf.AnnotationType:A-}
<p> Exports the content of the specified annotation types into XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; OutputStream stream = new FileOutputStream("example.xfdf"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre>

### exportAnnotationsXfdf {#exportAnnotationsXfdf-java.io.OutputStream-int-int-java.lang.String:A-}
<p> Exports the content of the specified annotations types into XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); String[] annotTypes = new String[] {"Text", "Highlight"}; OutputStream stream = new FileOutputStream("example.xfdf"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre>

### extractAnnotations {#extractAnnotations-int-int-com.aspose.pdf.AnnotationType:A-}
<p> Gets the list of annotations of the specified types. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre>

### extractAnnotations {#extractAnnotations-int-int-java.lang.String:A-}
<p> Gets the list of annotations of the specified types. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); String[] annotTypes = new String[] {"Text", "Highlight"}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre>

### flatteningAnnotations {#flatteningAnnotations--}
```
public void flatteningAnnotations()
```

<p> Flattens all annotations in the document. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre>

### flatteningAnnotations {#flatteningAnnotations-com.aspose.pdf.Form.FlattenSettings-}
<p> Flattens all annotations in the document. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre>

### flatteningAnnotations {#flatteningAnnotations-int-int-com.aspose.pdf.AnnotationType:A-}
<p> Flattens all annotations in the document. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.io.InputStream-}
<p> Imports all annotations from XFDF data stream. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf")); editor.save("example_out.pdf"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.io.InputStream-com.aspose.pdf.AnnotationType:A-}
<p> Imports the specified annotations from XFDF data stream. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line }; editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf"), annotTypes); editor.save("example_out.pdf"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.lang.String-com.aspose.pdf.AnnotationType:A-}
<p> Imports the specified annotations from XFDF file. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotationFromXfdf("annots.xfdf", annotTypes); editor.save("example_out.pdf"); </pre>

### importAnnotations {#importAnnotations-java.io.InputStream:A-}
<p> Imports annotations into document from array of another PDF document streams. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream("with_annots1.pdf"); streams[1]= new FileInputStream("with_annots2.pdf"); editor.importAnnotations(streams); editor.save("example_out.pdf"); streams[0].Close(); streams[1].Close(); </pre>

### importAnnotations {#importAnnotations-java.io.InputStream:A-com.aspose.pdf.AnnotationType:A-}
<p> Imports the specified annotations into document from array of another PDF document streams. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream("with_annots1.pdf"); streams[1]= new FileInputStream("with_annots2.pdf"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(streams, annotTypes); editor.save("example_out.pdf"); streams[0].close(); streams[1].close(); </pre>

### importAnnotations {#importAnnotations-java.lang.String:A-}
<p> Imports annotations into document from array of another PDF documents. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"}; editor.importAnnotations(paths); editor.save("example_out.pdf"); </pre>

### importAnnotations {#importAnnotations-java.lang.String:A-com.aspose.pdf.AnnotationType:A-}
<p> Imports the specified annotations into document from array of another PDF documents. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"}; int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(paths, annotTypes); editor.save("example_out.pdf"); </pre>

### importAnnotationsFromFdf {#importAnnotationsFromFdf-java.lang.String-}
Imports all annotations from FDF file. PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationsFromFdf("annots.fdf"); editor.save("example_out.pdf");

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.io.InputStream-}
<p> Imports all annotations from XFDF data stream. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf")); editor.save("example_out.pdf"); </pre>

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
<p> Imports all annotations from XFDF file. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationsFromXfdf("annots.xfdf"); editor.save("example_out.pdf"); </pre>

### modifyAnnotations {#modifyAnnotations-int-int-com.aspose.pdf.Annotation-}
<p> Modifies the annotations of the specifed type on the specified page range. It supports to modify next annotation properties: Modified, Title, Contents, Color, Subject and Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); TextAnnotation annot = new TextAnnotation(); annot.setModified ( new Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor ( Color.RED); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, annot); editor.save("example_out.pdf"); </pre>

### modifyAnnotations {#modifyAnnotations-int-int-int-com.aspose.pdf.Annotation-}
"Use modifyAnnotations(int start, int end, Annotation annotation) instead." <p> Modifies the annotations of the specifed type on the specified page range. It supports to modify next annotation properties: Modified, Title, Contents, Color, Subject and Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); com.aspose.pdf.TextAnnotation annot = new com.aspose.pdf.TextAnnotation(); annot.setModified ( new java.util.Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor (com.aspose.pdf.Color.getRed()); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, com.aspose.pdf.AnnotationType.Text, annot); editor.save("example_out.pdf"); </pre>

### modifyAnnotationsAuthor {#modifyAnnotationsAuthor-int-int-java.lang.String-java.lang.String-}
<p> Modifies the author of annotations on the specified page range. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.modifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR"); editor.save("example_out.pdf"); </pre>

### redactArea {#redactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-}
Redacts area on the specified page.

### redactExactArea {#redactExactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-}
Redacts area on the specified page.

### save {#save-java.io.OutputStream-}
Saves the result PDF to stream.

### save {#save-java.lang.String-}
Saves the result PDF to file.
