---
title: "PdfAnnotationEditor"
linktitle: "PdfAnnotationEditor"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe pour travailler avec les annotations (commentaires) de documents PDF."
type: docs
weight: 360
url: /fr/java/com.aspose.pdf.facades/pdfannotationeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfAnnotationEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfAnnotationEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfAnnotationEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfAnnotationEditor extends SaveableFacade
```

Représente une classe pour travailler avec les annotations (commentaires) de documents PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfAnnotationEditor](#PdfAnnotationEditor--) | Initialise un nouvel objet {@code PdfAnnotationEditor}. |
| [PdfAnnotationEditor](#PdfAnnotationEditor-com.aspose.pdf.IDocument-) | Initialise un nouvel objet {@code PdfAnnotationEditor}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [deleteAnnotation](#deleteAnnotation-java.lang.String-) | <p> Supprime l'annotation avec le nom d'annotation spécifié. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38"); editor.save("example_out.pdf"); </pre> |
| [deleteAnnotations](#deleteAnnotations--) | <p> Supprime toutes les annotations du document. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotations(); editor.save("example_out.pdf"); </pre> |
| [deleteAnnotations](#deleteAnnotations-java.lang.String-) | <p> Supprime toutes les annotations du document. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotations(); editor.save("example_out.pdf"); </pre> |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | Exporte les annotations vers un flux. |
| [exportAnnotationsXfdf](#exportAnnotationsXfdf-java.io.OutputStream-int-int-com.aspose.pdf.AnnotationType:A-) | <p> Exporte le contenu des types d'annotation spécifiés au format XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; OutputStream stream = new FileOutputStream("example.xfdf"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre> |
| [exportAnnotationsXfdf](#exportAnnotationsXfdf-java.io.OutputStream-int-int-java.lang.String:A-) | <p> Exporte le contenu des types d'annotation spécifiés au format XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); String[] annotTypes = new String[] {"Text", "Highlight"}; OutputStream stream = new FileOutputStream("example.xfdf"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre> |
| [extractAnnotations](#extractAnnotations-int-int-com.aspose.pdf.AnnotationType:A-) | <p> Obtient la liste des annotations des types spécifiés. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre> |
| [extractAnnotations](#extractAnnotations-int-int-java.lang.String:A-) | <p> Obtient la liste des annotations des types spécifiés. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); String[] annotTypes = new String[] {"Text", "Highlight"}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre> |
| [flatteningAnnotations](#flatteningAnnotations--) | <p> Aplati toutes les annotations du document. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre> |
| [flatteningAnnotations](#flatteningAnnotations-com.aspose.pdf.Form.FlattenSettings-) | <p> Aplati toutes les annotations du document. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre> |
| [flatteningAnnotations](#flatteningAnnotations-int-int-com.aspose.pdf.AnnotationType:A-) | <p> Aplati toutes les annotations du document. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.io.InputStream-) | <p> Importe toutes les annotations depuis le flux de données XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf")); editor.save("example_out.pdf"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.io.InputStream-com.aspose.pdf.AnnotationType:A-) | <p> Importe les annotations spécifiées depuis le flux de données XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line }; editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf"), annotTypes); editor.save("example_out.pdf"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.lang.String-com.aspose.pdf.AnnotationType:A-) | <p> Importe les annotations spécifiées depuis le fichier XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotationFromXfdf("annots.xfdf", annotTypes); editor.save("example_out.pdf"); </pre> |
| [importAnnotations](#importAnnotations-java.io.InputStream:A-) | <p> Importe les annotations dans le document à partir d'un tableau de flux d'autres documents PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream("with_annots1.pdf"); streams[1]= new FileInputStream("with_annots2.pdf"); editor.importAnnotations(streams); editor.save("example_out.pdf"); streams[0].Close(); streams[1].Close(); </pre> |
| [importAnnotations](#importAnnotations-java.io.InputStream:A-com.aspose.pdf.AnnotationType:A-) | <p> Importe les annotations spécifiées dans le document à partir d'un tableau de flux d'autres documents PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream("with_annots1.pdf"); streams[1]= new FileInputStream("with_annots2.pdf"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(streams, annotTypes); editor.save("example_out.pdf"); streams[0].close(); streams[1].close(); </pre> |
| [importAnnotations](#importAnnotations-java.lang.String:A-) | <p> Importe les annotations dans le document à partir d'un tableau d'autres documents PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"}; editor.importAnnotations(paths); editor.save("example_out.pdf"); </pre> |
| [importAnnotations](#importAnnotations-java.lang.String:A-com.aspose.pdf.AnnotationType:A-) | <p> Importe les annotations spécifiées dans le document à partir d'un tableau d'autres documents PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"}; int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(paths, annotTypes); editor.save("example_out.pdf"); </pre> |
| [importAnnotationsFromFdf](#importAnnotationsFromFdf-java.lang.String-) | Importe toutes les annotations depuis le fichier FDF. PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationsFromFdf("annots.fdf"); editor.save("example_out.pdf"); |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | <p> Importe toutes les annotations depuis le flux de données XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf")); editor.save("example_out.pdf"); </pre> |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | <p> Importe toutes les annotations depuis le fichier XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationsFromXfdf("annots.xfdf"); editor.save("example_out.pdf"); </pre> |
| [modifyAnnotations](#modifyAnnotations-int-int-com.aspose.pdf.Annotation-) | <p> Modifie les annotations du type spécifié sur la plage de pages spécifiée. Il prend en charge la modification des propriétés d'annotation suivantes : Modified, Title, Contents, Color, Subject et Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); TextAnnotation annot = new TextAnnotation(); annot.setModified ( new Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor ( Color.RED); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, annot); editor.save("example_out.pdf"); </pre> |
| [modifyAnnotations](#modifyAnnotations-int-int-int-com.aspose.pdf.Annotation-) | "Utilisez modifyAnnotations(int start, int end, Annotation annotation) à la place." <p> Modifie les annotations du type spécifié sur la plage de pages spécifiée. Il prend en charge la modification des propriétés d'annotation suivantes : Modified, Title, Contents, Color, Subject et Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); com.aspose.pdf.TextAnnotation annot = new com.aspose.pdf.TextAnnotation(); annot.setModified ( new java.util.Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor (com.aspose.pdf.Color.getRed()); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, com.aspose.pdf.AnnotationType.Text, annot); editor.save("example_out.pdf"); </pre> |
| [modifyAnnotationsAuthor](#modifyAnnotationsAuthor-int-int-java.lang.String-java.lang.String-) | <p> Modifie l'auteur des annotations sur la plage de pages spécifiée. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.modifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR"); editor.save("example_out.pdf"); </pre> |
| [redactArea](#redactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-) | Masque la zone sur la page spécifiée. |
| [redactExactArea](#redactExactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-) | Masque la zone sur la page spécifiée. |
| [save](#save-java.io.OutputStream-) | Enregistre le PDF résultant dans le flux. |
| [save](#save-java.lang.String-) | Enregistre le PDF résultant dans un fichier. |

### PdfAnnotationEditor {#PdfAnnotationEditor--}
```
public PdfAnnotationEditor()
```

Initialise un nouvel objet {@code PdfAnnotationEditor}.

### PdfAnnotationEditor {#PdfAnnotationEditor-com.aspose.pdf.IDocument-}
Initialise un nouvel objet {@code PdfAnnotationEditor}.

### deleteAnnotation {#deleteAnnotation-java.lang.String-}
<p> Supprime l'annotation avec le nom d'annotation spécifié. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38"); editor.save("example_out.pdf"); </pre>

### deleteAnnotations {#deleteAnnotations--}
```
public void deleteAnnotations()
```

<p> Supprime toutes les annotations du document. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotations(); editor.save("example_out.pdf"); </pre>

### deleteAnnotations {#deleteAnnotations-java.lang.String-}
<p> Supprime toutes les annotations du document. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotations(); editor.save("example_out.pdf"); </pre>

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.io.OutputStream-}
Exporte les annotations vers un flux.

### exportAnnotationsXfdf {#exportAnnotationsXfdf-java.io.OutputStream-int-int-com.aspose.pdf.AnnotationType:A-}
<p> Exporte le contenu des types d'annotation spécifiés au format XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; OutputStream stream = new FileOutputStream("example.xfdf"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre>

### exportAnnotationsXfdf {#exportAnnotationsXfdf-java.io.OutputStream-int-int-java.lang.String:A-}
<p> Exporte le contenu des types d'annotation spécifiés au format XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); String[] annotTypes = new String[] {"Text", "Highlight"}; OutputStream stream = new FileOutputStream("example.xfdf"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre>

### extractAnnotations {#extractAnnotations-int-int-com.aspose.pdf.AnnotationType:A-}
<p> Obtient la liste des annotations des types spécifiés. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre>

### extractAnnotations {#extractAnnotations-int-int-java.lang.String:A-}
<p> Obtient la liste des annotations des types spécifiés. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); String[] annotTypes = new String[] {"Text", "Highlight"}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre>

### flatteningAnnotations {#flatteningAnnotations--}
```
public void flatteningAnnotations()
```

<p> Aplati toutes les annotations du document. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre>

### flatteningAnnotations {#flatteningAnnotations-com.aspose.pdf.Form.FlattenSettings-}
<p> Aplati toutes les annotations du document. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre>

### flatteningAnnotations {#flatteningAnnotations-int-int-com.aspose.pdf.AnnotationType:A-}
<p> Aplati toutes les annotations du document. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.io.InputStream-}
<p> Importe toutes les annotations depuis le flux de données XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf")); editor.save("example_out.pdf"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.io.InputStream-com.aspose.pdf.AnnotationType:A-}
<p> Importe les annotations spécifiées depuis le flux de données XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line }; editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf"), annotTypes); editor.save("example_out.pdf"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.lang.String-com.aspose.pdf.AnnotationType:A-}
<p> Importe les annotations spécifiées depuis le fichier XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotationFromXfdf("annots.xfdf", annotTypes); editor.save("example_out.pdf"); </pre>

### importAnnotations {#importAnnotations-java.io.InputStream:A-}
<p> Importe les annotations dans le document à partir d'un tableau de flux d'autres documents PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream("with_annots1.pdf"); streams[1]= new FileInputStream("with_annots2.pdf"); editor.importAnnotations(streams); editor.save("example_out.pdf"); streams[0].Close(); streams[1].Close(); </pre>

### importAnnotations {#importAnnotations-java.io.InputStream:A-com.aspose.pdf.AnnotationType:A-}
<p> Importe les annotations spécifiées dans le document à partir d'un tableau de flux d'autres documents PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream("with_annots1.pdf"); streams[1]= new FileInputStream("with_annots2.pdf"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(streams, annotTypes); editor.save("example_out.pdf"); streams[0].close(); streams[1].close(); </pre>

### importAnnotations {#importAnnotations-java.lang.String:A-}
<p> Importe les annotations dans le document à partir d'un tableau d'autres documents PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"}; editor.importAnnotations(paths); editor.save("example_out.pdf"); </pre>

### importAnnotations {#importAnnotations-java.lang.String:A-com.aspose.pdf.AnnotationType:A-}
<p> Importe les annotations spécifiées dans le document à partir d'un tableau d'autres documents PDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"}; int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(paths, annotTypes); editor.save("example_out.pdf"); </pre>

### importAnnotationsFromFdf {#importAnnotationsFromFdf-java.lang.String-}
Importe toutes les annotations depuis le fichier FDF. PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationsFromFdf("annots.fdf"); editor.save("example_out.pdf");

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.io.InputStream-}
<p> Importe toutes les annotations depuis le flux de données XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf")); editor.save("example_out.pdf"); </pre>

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
<p> Importe toutes les annotations depuis le fichier XFDF. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationsFromXfdf("annots.xfdf"); editor.save("example_out.pdf"); </pre>

### modifyAnnotations {#modifyAnnotations-int-int-com.aspose.pdf.Annotation-}
<p> Modifie les annotations du type spécifié sur la plage de pages spécifiée. Il prend en charge la modification des propriétés d'annotation suivantes : Modified, Title, Contents, Color, Subject et Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); TextAnnotation annot = new TextAnnotation(); annot.setModified ( new Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor ( Color.RED); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, annot); editor.save("example_out.pdf"); </pre>

### modifyAnnotations {#modifyAnnotations-int-int-int-com.aspose.pdf.Annotation-}
"Utilisez modifyAnnotations(int start, int end, Annotation annotation) à la place." <p> Modifie les annotations du type spécifié sur la plage de pages spécifiée. Il prend en charge la modification des propriétés d'annotation suivantes : Modified, Title, Contents, Color, Subject et Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); com.aspose.pdf.TextAnnotation annot = new com.aspose.pdf.TextAnnotation(); annot.setModified ( new java.util.Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor (com.aspose.pdf.Color.getRed()); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, com.aspose.pdf.AnnotationType.Text, annot); editor.save("example_out.pdf"); </pre>

### modifyAnnotationsAuthor {#modifyAnnotationsAuthor-int-int-java.lang.String-java.lang.String-}
<p> Modifie l'auteur des annotations sur la plage de pages spécifiée. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.modifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR"); editor.save("example_out.pdf"); </pre>

### redactArea {#redactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-}
Masque la zone sur la page spécifiée.

### redactExactArea {#redactExactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-}
Masque la zone sur la page spécifiée.

### save {#save-java.io.OutputStream-}
Enregistre le PDF résultant dans le flux.

### save {#save-java.lang.String-}
Enregistre le PDF résultant dans un fichier.
