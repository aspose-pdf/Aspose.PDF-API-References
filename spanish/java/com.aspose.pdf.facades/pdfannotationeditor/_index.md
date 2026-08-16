---
title: "PdfAnnotationEditor"
linktitle: "PdfAnnotationEditor"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para trabajar con anotaciones (comentarios) de documentos PDF."
type: docs
weight: 360
url: /es/java/com.aspose.pdf.facades/pdfannotationeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfAnnotationEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfAnnotationEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfAnnotationEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfAnnotationEditor extends SaveableFacade
```

Representa una clase para trabajar con anotaciones (comentarios) de documentos PDF.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfAnnotationEditor](#PdfAnnotationEditor--) | Inicializa un nuevo objeto {@code PdfAnnotationEditor}. |
| [PdfAnnotationEditor](#PdfAnnotationEditor-com.aspose.pdf.IDocument-) | Inicializa un nuevo objeto {@code PdfAnnotationEditor}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [deleteAnnotation](#deleteAnnotation-java.lang.String-) | <p> Elimina la anotación con el nombre de anotación especificado. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38"); editor.save("example_out.pdf"); </pre> |
| [deleteAnnotations](#deleteAnnotations--) | <p> Elimina todas las anotaciones en el documento. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotations(); editor.save("example_out.pdf"); </pre> |
| [deleteAnnotations](#deleteAnnotations-java.lang.String-) | <p> Elimina todas las anotaciones en el documento. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotations(); editor.save("example_out.pdf"); </pre> |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | Exporta anotaciones a un flujo. |
| [exportAnnotationsXfdf](#exportAnnotationsXfdf-java.io.OutputStream-int-int-com.aspose.pdf.AnnotationType:A-) | <p> Exporta el contenido de los tipos de anotación especificados a XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; OutputStream stream = new FileOutputStream("example.xfdf"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre> |
| [exportAnnotationsXfdf](#exportAnnotationsXfdf-java.io.OutputStream-int-int-java.lang.String:A-) | <p> Exporta el contenido de los tipos de anotaciones especificados a XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); String[] annotTypes = new String[] {"Text", "Highlight"}; OutputStream stream = new FileOutputStream("example.xfdf"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre> |
| [extractAnnotations](#extractAnnotations-int-int-com.aspose.pdf.AnnotationType:A-) | <p> Obtiene la lista de anotaciones de los tipos especificados. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre> |
| [extractAnnotations](#extractAnnotations-int-int-java.lang.String:A-) | <p> Obtiene la lista de anotaciones de los tipos especificados. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); String[] annotTypes = new String[] {"Text", "Highlight"}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre> |
| [flatteningAnnotations](#flatteningAnnotations--) | <p> Aplana todas las anotaciones en el documento. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre> |
| [flatteningAnnotations](#flatteningAnnotations-com.aspose.pdf.Form.FlattenSettings-) | <p> Aplana todas las anotaciones en el documento. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre> |
| [flatteningAnnotations](#flatteningAnnotations-int-int-com.aspose.pdf.AnnotationType:A-) | <p> Aplana todas las anotaciones en el documento. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.io.InputStream-) | <p> Importa todas las anotaciones desde el flujo de datos XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf")); editor.save("example_out.pdf"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.io.InputStream-com.aspose.pdf.AnnotationType:A-) | <p> Importa las anotaciones especificadas desde el flujo de datos XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line }; editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf"), annotTypes); editor.save("example_out.pdf"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.lang.String-com.aspose.pdf.AnnotationType:A-) | <p> Importa las anotaciones especificadas desde el archivo XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotationFromXfdf("annots.xfdf", annotTypes); editor.save("example_out.pdf"); </pre> |
| [importAnnotations](#importAnnotations-java.io.InputStream:A-) | <p> Importa anotaciones al documento desde una matriz de flujos de otro documento PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream("with_annots1.pdf"); streams[1]= new FileInputStream("with_annots2.pdf"); editor.importAnnotations(streams); editor.save("example_out.pdf"); streams[0].Close(); streams[1].Close(); </pre> |
| [importAnnotations](#importAnnotations-java.io.InputStream:A-com.aspose.pdf.AnnotationType:A-) | <p> Importa las anotaciones especificadas al documento desde una matriz de flujos de otro documento PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream("with_annots1.pdf"); streams[1]= new FileInputStream("with_annots2.pdf"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(streams, annotTypes); editor.save("example_out.pdf"); streams[0].close(); streams[1].close(); </pre> |
| [importAnnotations](#importAnnotations-java.lang.String:A-) | <p> Importa anotaciones al documento desde una matriz de otros documentos PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"}; editor.importAnnotations(paths); editor.save("example_out.pdf"); </pre> |
| [importAnnotations](#importAnnotations-java.lang.String:A-com.aspose.pdf.AnnotationType:A-) | <p> Importa las anotaciones especificadas al documento desde una matriz de otros documentos PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"}; int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(paths, annotTypes); editor.save("example_out.pdf"); </pre> |
| [importAnnotationsFromFdf](#importAnnotationsFromFdf-java.lang.String-) | Importa todas las anotaciones desde un archivo FDF. PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationsFromFdf("annots.fdf"); editor.save("example_out.pdf"); |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | <p> Importa todas las anotaciones desde el flujo de datos XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf")); editor.save("example_out.pdf"); </pre> |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | <p> Importa todas las anotaciones desde el archivo XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationsFromXfdf("annots.xfdf"); editor.save("example_out.pdf"); </pre> |
| [modifyAnnotations](#modifyAnnotations-int-int-com.aspose.pdf.Annotation-) | <p> Modifica las anotaciones del tipo especificado en el rango de páginas especificado. Soporta modificar las siguientes propiedades de anotación: Modified, Title, Contents, Color, Subject y Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); TextAnnotation annot = new TextAnnotation(); annot.setModified ( new Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor ( Color.RED); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, annot); editor.save("example_out.pdf"); </pre> |
| [modifyAnnotations](#modifyAnnotations-int-int-int-com.aspose.pdf.Annotation-) | "Utilice modifyAnnotations(int start, int end, Annotation annotation) en su lugar." <p> Modifica las anotaciones del tipo especificado en el rango de páginas especificado. Soporta modificar las siguientes propiedades de anotación: Modified, Title, Contents, Color, Subject y Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); com.aspose.pdf.TextAnnotation annot = new com.aspose.pdf.TextAnnotation(); annot.setModified ( new java.util.Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor (com.aspose.pdf.Color.getRed()); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, com.aspose.pdf.AnnotationType.Text, annot); editor.save("example_out.pdf"); </pre> |
| [modifyAnnotationsAuthor](#modifyAnnotationsAuthor-int-int-java.lang.String-java.lang.String-) | <p> Modifica el autor de las anotaciones en el rango de páginas especificado. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.modifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR"); editor.save("example_out.pdf"); </pre> |
| [redactArea](#redactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-) | Redacta el área en la página especificada. |
| [redactExactArea](#redactExactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-) | Redacta el área en la página especificada. |
| [save](#save-java.io.OutputStream-) | Guarda el PDF resultante en un flujo. |
| [save](#save-java.lang.String-) | Guarda el PDF resultante en un archivo. |

### PdfAnnotationEditor {#PdfAnnotationEditor--}
```
public PdfAnnotationEditor()
```

Inicializa un nuevo objeto {@code PdfAnnotationEditor}.

### PdfAnnotationEditor {#PdfAnnotationEditor-com.aspose.pdf.IDocument-}
Inicializa un nuevo objeto {@code PdfAnnotationEditor}.

### deleteAnnotation {#deleteAnnotation-java.lang.String-}
<p> Elimina la anotación con el nombre de anotación especificado. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38"); editor.save("example_out.pdf"); </pre>

### deleteAnnotations {#deleteAnnotations--}
```
public void deleteAnnotations()
```

<p> Elimina todas las anotaciones en el documento. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotations(); editor.save("example_out.pdf"); </pre>

### deleteAnnotations {#deleteAnnotations-java.lang.String-}
<p> Elimina todas las anotaciones en el documento. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotations(); editor.save("example_out.pdf"); </pre>

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.io.OutputStream-}
Exporta anotaciones a un flujo.

### exportAnnotationsXfdf {#exportAnnotationsXfdf-java.io.OutputStream-int-int-com.aspose.pdf.AnnotationType:A-}
<p> Exporta el contenido de los tipos de anotación especificados a XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; OutputStream stream = new FileOutputStream("example.xfdf"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre>

### exportAnnotationsXfdf {#exportAnnotationsXfdf-java.io.OutputStream-int-int-java.lang.String:A-}
<p> Exporta el contenido de los tipos de anotaciones especificados a XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); String[] annotTypes = new String[] {"Text", "Highlight"}; OutputStream stream = new FileOutputStream("example.xfdf"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre>

### extractAnnotations {#extractAnnotations-int-int-com.aspose.pdf.AnnotationType:A-}
<p> Obtiene la lista de anotaciones de los tipos especificados. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre>

### extractAnnotations {#extractAnnotations-int-int-java.lang.String:A-}
<p> Obtiene la lista de anotaciones de los tipos especificados. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); String[] annotTypes = new String[] {"Text", "Highlight"}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre>

### flatteningAnnotations {#flatteningAnnotations--}
```
public void flatteningAnnotations()
```

<p> Aplana todas las anotaciones en el documento. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre>

### flatteningAnnotations {#flatteningAnnotations-com.aspose.pdf.Form.FlattenSettings-}
<p> Aplana todas las anotaciones en el documento. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre>

### flatteningAnnotations {#flatteningAnnotations-int-int-com.aspose.pdf.AnnotationType:A-}
<p> Aplana todas las anotaciones en el documento. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.io.InputStream-}
<p> Importa todas las anotaciones desde el flujo de datos XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf")); editor.save("example_out.pdf"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.io.InputStream-com.aspose.pdf.AnnotationType:A-}
<p> Importa las anotaciones especificadas desde el flujo de datos XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line }; editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf"), annotTypes); editor.save("example_out.pdf"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.lang.String-com.aspose.pdf.AnnotationType:A-}
<p> Importa las anotaciones especificadas desde el archivo XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotationFromXfdf("annots.xfdf", annotTypes); editor.save("example_out.pdf"); </pre>

### importAnnotations {#importAnnotations-java.io.InputStream:A-}
<p> Importa anotaciones al documento desde una matriz de flujos de otro documento PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream("with_annots1.pdf"); streams[1]= new FileInputStream("with_annots2.pdf"); editor.importAnnotations(streams); editor.save("example_out.pdf"); streams[0].Close(); streams[1].Close(); </pre>

### importAnnotations {#importAnnotations-java.io.InputStream:A-com.aspose.pdf.AnnotationType:A-}
<p> Importa las anotaciones especificadas al documento desde una matriz de flujos de otro documento PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream("with_annots1.pdf"); streams[1]= new FileInputStream("with_annots2.pdf"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(streams, annotTypes); editor.save("example_out.pdf"); streams[0].close(); streams[1].close(); </pre>

### importAnnotations {#importAnnotations-java.lang.String:A-}
<p> Importa anotaciones al documento desde una matriz de otros documentos PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"}; editor.importAnnotations(paths); editor.save("example_out.pdf"); </pre>

### importAnnotations {#importAnnotations-java.lang.String:A-com.aspose.pdf.AnnotationType:A-}
<p> Importa las anotaciones especificadas al documento desde una matriz de otros documentos PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"}; int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(paths, annotTypes); editor.save("example_out.pdf"); </pre>

### importAnnotationsFromFdf {#importAnnotationsFromFdf-java.lang.String-}
Importa todas las anotaciones desde un archivo FDF. PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationsFromFdf("annots.fdf"); editor.save("example_out.pdf");

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.io.InputStream-}
<p> Importa todas las anotaciones desde el flujo de datos XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf")); editor.save("example_out.pdf"); </pre>

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
<p> Importa todas las anotaciones desde el archivo XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationsFromXfdf("annots.xfdf"); editor.save("example_out.pdf"); </pre>

### modifyAnnotations {#modifyAnnotations-int-int-com.aspose.pdf.Annotation-}
<p> Modifica las anotaciones del tipo especificado en el rango de páginas especificado. Soporta modificar las siguientes propiedades de anotación: Modified, Title, Contents, Color, Subject y Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); TextAnnotation annot = new TextAnnotation(); annot.setModified ( new Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor ( Color.RED); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, annot); editor.save("example_out.pdf"); </pre>

### modifyAnnotations {#modifyAnnotations-int-int-int-com.aspose.pdf.Annotation-}
"Utilice modifyAnnotations(int start, int end, Annotation annotation) en su lugar." <p> Modifica las anotaciones del tipo especificado en el rango de páginas especificado. Soporta modificar las siguientes propiedades de anotación: Modified, Title, Contents, Color, Subject y Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); com.aspose.pdf.TextAnnotation annot = new com.aspose.pdf.TextAnnotation(); annot.setModified ( new java.util.Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor (com.aspose.pdf.Color.getRed()); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, com.aspose.pdf.AnnotationType.Text, annot); editor.save("example_out.pdf"); </pre>

### modifyAnnotationsAuthor {#modifyAnnotationsAuthor-int-int-java.lang.String-java.lang.String-}
<p> Modifica el autor de las anotaciones en el rango de páginas especificado. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.modifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR"); editor.save("example_out.pdf"); </pre>

### redactArea {#redactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-}
Redacta el área en la página especificada.

### redactExactArea {#redactExactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-}
Redacta el área en la página especificada.

### save {#save-java.io.OutputStream-}
Guarda el PDF resultante en un flujo.

### save {#save-java.lang.String-}
Guarda el PDF resultante en un archivo.
