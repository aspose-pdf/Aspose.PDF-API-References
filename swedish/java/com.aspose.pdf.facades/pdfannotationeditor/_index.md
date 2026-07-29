---
title: "PdfAnnotationEditor"
linktitle: "PdfAnnotationEditor"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en klass för arbete med PDF-dokumentanteckningar (kommentarer)."
type: docs
weight: 360
url: /sv/java/com.aspose.pdf.facades/pdfannotationeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfAnnotationEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfAnnotationEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfAnnotationEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfAnnotationEditor extends SaveableFacade
```

Representerar en klass för arbete med PDF-dokumentanteckningar (kommentarer).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfAnnotationEditor](#PdfAnnotationEditor--) | Initierar ett nytt {@code PdfAnnotationEditor} objekt. |
| [PdfAnnotationEditor](#PdfAnnotationEditor-com.aspose.pdf.IDocument-) | Initierar ett nytt {@code PdfAnnotationEditor} objekt. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deleteAnnotation](#deleteAnnotation-java.lang.String-) | <p> Tar bort annoteringen med angivet annoteringsnamn. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38"); editor.save("example_out.pdf"); </pre> |
| [deleteAnnotations](#deleteAnnotations--) | <p> Tar bort alla annoteringar i dokumentet. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotations(); editor.save("example_out.pdf"); </pre> |
| [deleteAnnotations](#deleteAnnotations-java.lang.String-) | <p> Tar bort alla annoteringar i dokumentet. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotations(); editor.save("example_out.pdf"); </pre> |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | Exporterar annoteringar till ström. |
| [exportAnnotationsXfdf](#exportAnnotationsXfdf-java.io.OutputStream-int-int-com.aspose.pdf.AnnotationType:A-) | <p> Exporterar innehållet för de angivna annoteringstyperna till XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; OutputStream stream = new FileOutputStream("example.xfdf"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre> |
| [exportAnnotationsXfdf](#exportAnnotationsXfdf-java.io.OutputStream-int-int-java.lang.String:A-) | <p> Exporterar innehållet för de angivna annoteringstyperna till XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); String[] annotTypes = new String[] {"Text", "Highlight"}; OutputStream stream = new FileOutputStream("example.xfdf"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre> |
| [extractAnnotations](#extractAnnotations-int-int-com.aspose.pdf.AnnotationType:A-) | <p> Hämtar listan över annoteringar av de angivna typerna. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre> |
| [extractAnnotations](#extractAnnotations-int-int-java.lang.String:A-) | <p> Hämtar listan över annoteringar av de angivna typerna. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); String[] annotTypes = new String[] {"Text", "Highlight"}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre> |
| [flatteningAnnotations](#flatteningAnnotations--) | <p> Plattar till alla annoteringar i dokumentet. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre> |
| [flatteningAnnotations](#flatteningAnnotations-com.aspose.pdf.Form.FlattenSettings-) | <p> Plattar till alla annoteringar i dokumentet. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre> |
| [flatteningAnnotations](#flatteningAnnotations-int-int-com.aspose.pdf.AnnotationType:A-) | <p> Plattar till alla annoteringar i dokumentet. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.io.InputStream-) | <p> Importerar alla annoteringar från XFDF-datastream. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf")); editor.save("example_out.pdf"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.io.InputStream-com.aspose.pdf.AnnotationType:A-) | <p> Importerar de angivna annoteringarna från XFDF-datastream. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line }; editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf"), annotTypes); editor.save("example_out.pdf"); </pre> |
| [importAnnotationFromXfdf](#importAnnotationFromXfdf-java.lang.String-com.aspose.pdf.AnnotationType:A-) | <p> Importerar de specificerade annotationerna från XFDF-fil. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotationFromXfdf("annots.xfdf", annotTypes); editor.save("example_out.pdf"); </pre> |
| [importAnnotations](#importAnnotations-java.io.InputStream:A-) | <p> Importerar annotationer till dokumentet från en array av andra PDF-dokumentströmmar. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream("with_annots1.pdf"); streams[1]= new FileInputStream("with_annots2.pdf"); editor.importAnnotations(streams); editor.save("example_out.pdf"); streams[0].Close(); streams[1].Close(); </pre> |
| [importAnnotations](#importAnnotations-java.io.InputStream:A-com.aspose.pdf.AnnotationType:A-) | <p> Importerar de specificerade annotationerna till dokumentet från en array av andra PDF-dokumentströmmar. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream("with_annots1.pdf"); streams[1]= new FileInputStream("with_annots2.pdf"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(streams, annotTypes); editor.save("example_out.pdf"); streams[0].close(); streams[1].close(); </pre> |
| [importAnnotations](#importAnnotations-java.lang.String:A-) | <p> Importerar annotationer till dokumentet från en array av andra PDF-dokument. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"}; editor.importAnnotations(paths); editor.save("example_out.pdf"); </pre> |
| [importAnnotations](#importAnnotations-java.lang.String:A-com.aspose.pdf.AnnotationType:A-) | <p> Importerar de specificerade annotationerna till dokumentet från en array av andra PDF-dokument. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"}; int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(paths, annotTypes); editor.save("example_out.pdf"); </pre> |
| [importAnnotationsFromFdf](#importAnnotationsFromFdf-java.lang.String-) | Importerar alla annotationer från FDF-fil. PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationsFromFdf("annots.fdf"); editor.save("example_out.pdf"); |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | <p> Importerar alla annoteringar från XFDF-datastream. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf")); editor.save("example_out.pdf"); </pre> |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | <p> Importerar alla annotationer från XFDF-fil. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationsFromXfdf("annots.xfdf"); editor.save("example_out.pdf"); </pre> |
| [modifyAnnotations](#modifyAnnotations-int-int-com.aspose.pdf.Annotation-) | <p> Modifierar annotationerna av den specificerade typen på det specificerade sidintervallet. Det stöder att ändra följande annoteringsegenskaper: Modified, Title, Contents, Color, Subject och Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); TextAnnotation annot = new TextAnnotation(); annot.setModified ( new Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor ( Color.RED); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, annot); editor.save("example_out.pdf"); </pre> |
| [modifyAnnotations](#modifyAnnotations-int-int-int-com.aspose.pdf.Annotation-) | "Använd modifyAnnotations(int start, int end, Annotation annotation) istället." <p> Modifierar annotationerna av den angivna typen på det angivna sidintervallet. Den stöder att modifiera följande annoteringsegenskaper: Modified, Title, Contents, Color, Subject och Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); com.aspose.pdf.TextAnnotation annot = new com.aspose.pdf.TextAnnotation(); annot.setModified ( new java.util.Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor (com.aspose.pdf.Color.getRed()); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, com.aspose.pdf.AnnotationType.Text, annot); editor.save("example_out.pdf"); </pre> |
| [modifyAnnotationsAuthor](#modifyAnnotationsAuthor-int-int-java.lang.String-java.lang.String-) | <p> Modifierar författaren till annotationer på det angivna sidintervallet. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.modifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR"); editor.save("example_out.pdf"); </pre> |
| [redactArea](#redactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-) | Raderar område på den angivna sidan. |
| [redactExactArea](#redactExactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-) | Raderar område på den angivna sidan. |
| [save](#save-java.io.OutputStream-) | Sparar resultat-PDF till ström. |
| [save](#save-java.lang.String-) | Sparar resultat-PDF till fil. |

### PdfAnnotationEditor {#PdfAnnotationEditor--}
```
public PdfAnnotationEditor()
```

Initierar ett nytt {@code PdfAnnotationEditor} objekt.

### PdfAnnotationEditor {#PdfAnnotationEditor-com.aspose.pdf.IDocument-}
Initierar ett nytt {@code PdfAnnotationEditor} objekt.

### deleteAnnotation {#deleteAnnotation-java.lang.String-}
<p> Tar bort annoteringen med angivet annoteringsnamn. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38"); editor.save("example_out.pdf"); </pre>

### deleteAnnotations {#deleteAnnotations--}
```
public void deleteAnnotations()
```

<p> Tar bort alla annoteringar i dokumentet. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotations(); editor.save("example_out.pdf"); </pre>

### deleteAnnotations {#deleteAnnotations-java.lang.String-}
<p> Tar bort alla annoteringar i dokumentet. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.deleteAnnotations(); editor.save("example_out.pdf"); </pre>

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.io.OutputStream-}
Exporterar annoteringar till ström.

### exportAnnotationsXfdf {#exportAnnotationsXfdf-java.io.OutputStream-int-int-com.aspose.pdf.AnnotationType:A-}
<p> Exporterar innehållet för de angivna annoteringstyperna till XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; OutputStream stream = new FileOutputStream("example.xfdf"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre>

### exportAnnotationsXfdf {#exportAnnotationsXfdf-java.io.OutputStream-int-int-java.lang.String:A-}
<p> Exporterar innehållet för de angivna annoteringstyperna till XFDF </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); String[] annotTypes = new String[] {"Text", "Highlight"}; OutputStream stream = new FileOutputStream("example.xfdf"); editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes); stream.close(); </pre>

### extractAnnotations {#extractAnnotations-int-int-com.aspose.pdf.AnnotationType:A-}
<p> Hämtar listan över annoteringar av de angivna typerna. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre>

### extractAnnotations {#extractAnnotations-int-int-java.lang.String:A-}
<p> Hämtar listan över annoteringar av de angivna typerna. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); String[] annotTypes = new String[] {"Text", "Highlight"}; List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes); </pre>

### flatteningAnnotations {#flatteningAnnotations--}
```
public void flatteningAnnotations()
```

<p> Plattar till alla annoteringar i dokumentet. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre>

### flatteningAnnotations {#flatteningAnnotations-com.aspose.pdf.Form.FlattenSettings-}
<p> Plattar till alla annoteringar i dokumentet. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre>

### flatteningAnnotations {#flatteningAnnotations-int-int-com.aspose.pdf.AnnotationType:A-}
<p> Plattar till alla annoteringar i dokumentet. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.flatteningAnnotations(); editor.save(example_out.pdf"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.io.InputStream-}
<p> Importerar alla annoteringar från XFDF-datastream. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf")); editor.save("example_out.pdf"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.io.InputStream-com.aspose.pdf.AnnotationType:A-}
<p> Importerar de angivna annoteringarna från XFDF-datastream. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line }; editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf"), annotTypes); editor.save("example_out.pdf"); </pre>

### importAnnotationFromXfdf {#importAnnotationFromXfdf-java.lang.String-com.aspose.pdf.AnnotationType:A-}
<p> Importerar de specificerade annotationerna från XFDF-fil. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotationFromXfdf("annots.xfdf", annotTypes); editor.save("example_out.pdf"); </pre>

### importAnnotations {#importAnnotations-java.io.InputStream:A-}
<p> Importerar annotationer till dokumentet från en array av andra PDF-dokumentströmmar. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream("with_annots1.pdf"); streams[1]= new FileInputStream("with_annots2.pdf"); editor.importAnnotations(streams); editor.save("example_out.pdf"); streams[0].Close(); streams[1].Close(); </pre>

### importAnnotations {#importAnnotations-java.io.InputStream:A-com.aspose.pdf.AnnotationType:A-}
<p> Importerar de specificerade annotationerna till dokumentet från en array av andra PDF-dokumentströmmar. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); InputStream[] streams = new FileInputStream[2]; streams[0]= new FileInputStream("with_annots1.pdf"); streams[1]= new FileInputStream("with_annots2.pdf"); int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(streams, annotTypes); editor.save("example_out.pdf"); streams[0].close(); streams[1].close(); </pre>

### importAnnotations {#importAnnotations-java.lang.String:A-}
<p> Importerar annotationer till dokumentet från en array av andra PDF-dokument. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"}; editor.importAnnotations(paths); editor.save("example_out.pdf"); </pre>

### importAnnotations {#importAnnotations-java.lang.String:A-com.aspose.pdf.AnnotationType:A-}
<p> Importerar de specificerade annotationerna till dokumentet från en array av andra PDF-dokument. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"}; int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text}; editor.importAnnotations(paths, annotTypes); editor.save("example_out.pdf"); </pre>

### importAnnotationsFromFdf {#importAnnotationsFromFdf-java.lang.String-}
Importerar alla annotationer från FDF-fil. PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationsFromFdf("annots.fdf"); editor.save("example_out.pdf");

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.io.InputStream-}
<p> Importerar alla annoteringar från XFDF-datastream. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf")); editor.save("example_out.pdf"); </pre>

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
<p> Importerar alla annotationer från XFDF-fil. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.importAnnotationsFromXfdf("annots.xfdf"); editor.save("example_out.pdf"); </pre>

### modifyAnnotations {#modifyAnnotations-int-int-com.aspose.pdf.Annotation-}
<p> Modifierar annotationerna av den specificerade typen på det specificerade sidintervallet. Det stöder att ändra följande annoteringsegenskaper: Modified, Title, Contents, Color, Subject och Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); TextAnnotation annot = new TextAnnotation(); annot.setModified ( new Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor ( Color.RED); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, annot); editor.save("example_out.pdf"); </pre>

### modifyAnnotations {#modifyAnnotations-int-int-int-com.aspose.pdf.Annotation-}
"Använd modifyAnnotations(int start, int end, Annotation annotation) istället." <p> Modifierar annotationerna av den angivna typen på det angivna sidintervallet. Den stöder att modifiera följande annoteringsegenskaper: Modified, Title, Contents, Color, Subject och Open. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); com.aspose.pdf.TextAnnotation annot = new com.aspose.pdf.TextAnnotation(); annot.setModified ( new java.util.Date()); annot.setTitle ( "NEW AUTHOR"); annot.setContents ( "NEW CONTENTS"); annot.setColor (com.aspose.pdf.Color.getRed()); annot.setSubject ( "NEW SUBJECT"); annot.setOpen ( true); editor.modifyAnnotations(1, 2, com.aspose.pdf.AnnotationType.Text, annot); editor.save("example_out.pdf"); </pre>

### modifyAnnotationsAuthor {#modifyAnnotationsAuthor-int-int-java.lang.String-java.lang.String-}
<p> Modifierar författaren till annotationer på det angivna sidintervallet. </p> <hr> <pre> PdfAnnotationEditor editor = new PdfAnnotationEditor(); editor.bindPdf("example.pdf"); editor.modifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR"); editor.save("example_out.pdf"); </pre>

### redactArea {#redactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-}
Raderar område på den angivna sidan.

### redactExactArea {#redactExactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-}
Raderar område på den angivna sidan.

### save {#save-java.io.OutputStream-}
Sparar resultat-PDF till ström.

### save {#save-java.lang.String-}
Sparar resultat-PDF till fil.
