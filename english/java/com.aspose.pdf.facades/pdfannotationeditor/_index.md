---
title: PdfAnnotationEditor
second_title: Aspose.PDF for Java API Reference
description: Represents a class for work with PDF document annotations comments.
type: docs
weight: 34
url: /java/com.aspose.pdf.facades/pdfannotationeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfAnnotationEditor extends SaveableFacade
```

Represents a class for work with PDF document annotations (comments).
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfAnnotationEditor()](#PdfAnnotationEditor--) | Initializes new  PdfAnnotationEditor  object. |
| [PdfAnnotationEditor(IDocument document)](#PdfAnnotationEditor-com.aspose.pdf.IDocument-) | Initializes new  PdfAnnotationEditor  object on base of the  document . |
## Methods

| Method | Description |
| --- | --- |
| [importAnnotationsFromXfdf(String xfdfFile)](#importAnnotationsFromXfdf-java.lang.String-) | Imports all annotations from XFDF file. |
| [importAnnotationFromXfdf(String xfdfFile)](#importAnnotationFromXfdf-java.lang.String-) | Imports all annotations from XFDF file. |
| [importAnnotationsFromXfdf(String xfdfFile, int[] annotType)](#importAnnotationsFromXfdf-java.lang.String-int---) | Imports the specified annotations from XFDF file. |
| [importAnnotationsFromXfdf(InputStream xfdfStream, int[] annotType)](#importAnnotationsFromXfdf-java.io.InputStream-int---) | Imports the specified annotations from XFDF data stream. |
| [importAnnotationsFromXfdf(InputStream xfdfSteam)](#importAnnotationsFromXfdf-java.io.InputStream-) | Imports all annotations from XFDF data stream. |
| [importAnnotationFromXfdf(InputStream xfdfStream)](#importAnnotationFromXfdf-java.io.InputStream-) | Imports all annotations from XFDF data stream. |
| [importAnnotations(String[] annotFile, int[] annotType)](#importAnnotations-java.lang.String---int---) | Imports the specified annotations into document from array of another PDF documents. |
| [importAnnotations(String[] annotFile)](#importAnnotations-java.lang.String---) | Imports annotations into document from array of another PDF documents. |
| [importAnnotations(InputStream[] annotFileInputStream, int[] annotType)](#importAnnotations-java.io.InputStream---int---) | Imports the specified annotations into document from array of another PDF document streams. |
| [importAnnotations(InputStream[] annotFileInputStream)](#importAnnotations-java.io.InputStream---) | Imports annotations into document from array of another PDF document streams. |
| [modifyAnnotations(int start, int end, int annotType, Annotation annotation)](#modifyAnnotations-int-int-int-com.aspose.pdf.Annotation-) | "Use modifyAnnotations(int start, int end, Annotation annotation) instead." |
| [modifyAnnotationsAuthor(int start, int end, String srcAuthor, String desAuthor)](#modifyAnnotationsAuthor-int-int-java.lang.String-java.lang.String-) | Modifies the author of annotations on the specified page range. |
| [flatteningAnnotations()](#flatteningAnnotations--) | Flattens all annotations in the document. |
| [flatteningAnnotations(Form.FlattenSettings flattenSettings)](#flatteningAnnotations-com.aspose.pdf.Form.FlattenSettings-) | Flattens all annotations in the document. |
| [flatteningAnnotations(int start, int end, int[] annotType)](#flatteningAnnotations-int-int-int---) | Flattens the annotations of the specified types. |
| [deleteAnnotations()](#deleteAnnotations--) | Deletes all annotations in the document. |
| [deleteAnnotations(String annotType)](#deleteAnnotations-java.lang.String-) | Deletes all annotations of the specified type in the document. |
| [deleteAnnotation(String annotName)](#deleteAnnotation-java.lang.String-) | Deletes the annotation with specified annotation name. |
| [exportAnnotationsXfdf(OutputStream xmlOutputStream, int start, int end, String[] annotTypes)](#exportAnnotationsXfdf-java.io.OutputStream-int-int-java.lang.String---) | Exports the content of the specified annotations types into XFDF |
| [exportAnnotationsToXfdf(OutputStream xmlOutputStream)](#exportAnnotationsToXfdf-java.io.OutputStream-) | Exports annotations to stream. |
| [exportAnnotationsXfdf(OutputStream xmlOutputStream, int start, int end, int[] annotTypes)](#exportAnnotationsXfdf-java.io.OutputStream-int-int-int---) | Exports the content of the specified annotation types into XFDF |
| [extractAnnotations(int start, int end, String[] annotTypes)](#extractAnnotations-int-int-java.lang.String---) | Gets the list of annotations of the specified types. |
| [extractAnnotations(int start, int end, int[] annotTypes)](#extractAnnotations-int-int-int---) | Gets the list of annotations of the specified types. |
| [save(String outputFile)](#save-java.lang.String-) | Saves the result PDF to file. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Saves the result PDF to stream. |
| [modifyAnnotations(int start, int end, Annotation annotation)](#modifyAnnotations-int-int-com.aspose.pdf.Annotation-) | Modifies the annotations of the specifed type on the specified page range. |
| [redactArea(int pageIndex, Rectangle rect, Color color)](#redactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-) | Redacts area on the specified page. |
| [redactExactArea(int pageIndex, Rectangle rect, Color color)](#redactExactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-) | Redacts area on the specified page. |
### PdfAnnotationEditor() {#PdfAnnotationEditor--}
```
public PdfAnnotationEditor()
```


Initializes new  PdfAnnotationEditor  object.

### PdfAnnotationEditor(IDocument document) {#PdfAnnotationEditor-com.aspose.pdf.IDocument-}
```
public PdfAnnotationEditor(IDocument document)
```


Initializes new  PdfAnnotationEditor  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |

### importAnnotationsFromXfdf(String xfdfFile) {#importAnnotationsFromXfdf-java.lang.String-}
```
public void importAnnotationsFromXfdf(String xfdfFile)
```


Imports all annotations from XFDF file.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.importAnnotationsFromXfdf("annots.xfdf");
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xfdfFile | java.lang.String | The input XFDF file. |

### importAnnotationFromXfdf(String xfdfFile) {#importAnnotationFromXfdf-java.lang.String-}
```
public final void importAnnotationFromXfdf(String xfdfFile)
```


Imports all annotations from XFDF file.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.importAnnotationFromXfdf("annots.xfdf");
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xfdfFile | java.lang.String | The input XFDF file. |

### importAnnotationsFromXfdf(String xfdfFile, int[] annotType) {#importAnnotationsFromXfdf-java.lang.String-int---}
```
public void importAnnotationsFromXfdf(String xfdfFile, int[] annotType)
```


Imports the specified annotations from XFDF file.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
 editor.importAnnotationFromXfdf("annots.xfdf", annotTypes);
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xfdfFile | java.lang.String | The input XFDF file. |
| annotType | int[] | The annotations array to be imported. |

### importAnnotationsFromXfdf(InputStream xfdfStream, int[] annotType) {#importAnnotationsFromXfdf-java.io.InputStream-int---}
```
public void importAnnotationsFromXfdf(InputStream xfdfStream, int[] annotType)
```


Imports the specified annotations from XFDF data stream.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 int[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line };
 editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf"), annotTypes);
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xfdfStream | java.io.InputStream | The input XFDF data stream. |
| annotType | int[] | The array of annotation types to be imported. |

### importAnnotationsFromXfdf(InputStream xfdfSteam) {#importAnnotationsFromXfdf-java.io.InputStream-}
```
public void importAnnotationsFromXfdf(InputStream xfdfSteam)
```


Imports all annotations from XFDF data stream.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.importAnnotationsFromXfdf(new FileInputStream("annots.xfdf"));
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xfdfSteam | java.io.InputStream | The input XFDF data stream. |

### importAnnotationFromXfdf(InputStream xfdfStream) {#importAnnotationFromXfdf-java.io.InputStream-}
```
public final void importAnnotationFromXfdf(InputStream xfdfStream)
```


Imports all annotations from XFDF data stream.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.importAnnotationFromXfdf(new FileInputStream("annots.xfdf"));
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xfdfStream | java.io.InputStream | The input XFDF data stream. |

### importAnnotations(String[] annotFile, int[] annotType) {#importAnnotations-java.lang.String---int---}
```
public void importAnnotations(String[] annotFile, int[] annotType)
```


Imports the specified annotations into document from array of another PDF documents.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
 int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
 editor.importAnnotations(paths, annotTypes);
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotFile | java.lang.String[] | The array of paths of PDF documents that contain source annotations. |
| annotType | int[] | The array of annotation types to be imported. |

### importAnnotations(String[] annotFile) {#importAnnotations-java.lang.String---}
```
public void importAnnotations(String[] annotFile)
```


Imports annotations into document from array of another PDF documents.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
 editor.importAnnotations(paths);
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotFile | java.lang.String[] | The array of paths of PDF documents that contain source annotations. |

### importAnnotations(InputStream[] annotFileInputStream, int[] annotType) {#importAnnotations-java.io.InputStream---int---}
```
public void importAnnotations(InputStream[] annotFileInputStream, int[] annotType)
```


Imports the specified annotations into document from array of another PDF document streams.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 InputStream[] streams = new FileInputStream[2];
 streams[0]= new FileInputStream("with_annots1.pdf");
 streams[1]= new FileInputStream("with_annots2.pdf");
 int[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
 editor.importAnnotations(streams, annotTypes);
 editor.save("example_out.pdf");
 streams[0].close();
 streams[1].close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotFileInputStream | java.io.InputStream[] | The array of streams of PDF documents that contain source annotations. |
| annotType | int[] | The annotation types to be imported. |

### importAnnotations(InputStream[] annotFileInputStream) {#importAnnotations-java.io.InputStream---}
```
public void importAnnotations(InputStream[] annotFileInputStream)
```


Imports annotations into document from array of another PDF document streams.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 InputStream[] streams = new FileInputStream[2];
 streams[0]= new FileInputStream("with_annots1.pdf");
 streams[1]= new FileInputStream("with_annots2.pdf");
 editor.importAnnotations(streams);
 editor.save("example_out.pdf");
 streams[0].Close();
 streams[1].Close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotFileInputStream | java.io.InputStream[] | The array of streams of PDF documents that contain source annotations. |

### modifyAnnotations(int start, int end, int annotType, Annotation annotation) {#modifyAnnotations-int-int-int-com.aspose.pdf.Annotation-}
```
public void modifyAnnotations(int start, int end, int annotType, Annotation annotation)
```


"Use modifyAnnotations(int start, int end, Annotation annotation) instead."

Modifies the annotations of the specifed type on the specified page range. It supports to modify next annotation properties: Modified, Title, Contents, Color, Subject and Open.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 com.aspose.pdf.TextAnnotation annot = new com.aspose.pdf.TextAnnotation();
 annot.setModified ( new java.util.Date());
 annot.setTitle ( "NEW AUTHOR");
 annot.setContents ( "NEW CONTENTS");
 annot.setColor (com.aspose.pdf.Color.getRed());
 annot.setSubject ( "NEW SUBJECT");
 annot.setOpen ( true);
 editor.modifyAnnotations(1, 2, com.aspose.pdf.AnnotationType.Text, annot);
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| start | int | The start page number. |
| end | int | The end page number. |
| annotType | int | The annotation type. |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | The annotation object contains new properties. |

### modifyAnnotationsAuthor(int start, int end, String srcAuthor, String desAuthor) {#modifyAnnotationsAuthor-int-int-java.lang.String-java.lang.String-}
```
public void modifyAnnotationsAuthor(int start, int end, String srcAuthor, String desAuthor)
```


Modifies the author of annotations on the specified page range.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.modifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| start | int | The start page number. |
| end | int | The end page number. |
| srcAuthor | java.lang.String | The author that must be modified. |
| desAuthor | java.lang.String | The new author. |

### flatteningAnnotations() {#flatteningAnnotations--}
```
public void flatteningAnnotations()
```


Flattens all annotations in the document.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.flatteningAnnotations();
 editor.save(example_out.pdf");
```

### flatteningAnnotations(Form.FlattenSettings flattenSettings) {#flatteningAnnotations-com.aspose.pdf.Form.FlattenSettings-}
```
public final void flatteningAnnotations(Form.FlattenSettings flattenSettings)
```


Flattens all annotations in the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flattenSettings | [FlattenSettings](../../com.aspose.pdf/flattensettings) | Specifies modes of flattening. |

### flatteningAnnotations(int start, int end, int[] annotType) {#flatteningAnnotations-int-int-int---}
```
public void flatteningAnnotations(int start, int end, int[] annotType)
```


Flattens the annotations of the specified types.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 int[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
 editor.flatteningAnnotations(1, 2, annotTypes);
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| start | int | The start page. |
| end | int | Then end page. |
| annotType | int[] | The annotation types should be flattened. |

### deleteAnnotations() {#deleteAnnotations--}
```
public void deleteAnnotations()
```


Deletes all annotations in the document.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.deleteAnnotations();
 editor.save("example_out.pdf");
```

### deleteAnnotations(String annotType) {#deleteAnnotations-java.lang.String-}
```
public void deleteAnnotations(String annotType)
```


Deletes all annotations of the specified type in the document.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.deleteAnnotations("Text");
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotType | java.lang.String | The type of annotation will be deleted. |

### deleteAnnotation(String annotName) {#deleteAnnotation-java.lang.String-}
```
public void deleteAnnotation(String annotName)
```


Deletes the annotation with specified annotation name.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 editor.deleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotName | java.lang.String | The annotation name |

### exportAnnotationsXfdf(OutputStream xmlOutputStream, int start, int end, String[] annotTypes) {#exportAnnotationsXfdf-java.io.OutputStream-int-int-java.lang.String---}
```
public void exportAnnotationsXfdf(OutputStream xmlOutputStream, int start, int end, String[] annotTypes)
```


Exports the content of the specified annotations types into XFDF

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 String[] annotTypes = new String[] {"Text", "Highlight"};
 OutputStream stream = new FileOutputStream("example.xfdf");
 editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes);
 stream.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlOutputStream | java.io.OutputStream | The output XFDF stream. |
| start | int | Start page from which the annotations of the document will be exported. |
| end | int | End page to which the annotations of the document will be exported. |
| annotTypes | java.lang.String[] | The array of annotation types need be exported. |

### exportAnnotationsToXfdf(OutputStream xmlOutputStream) {#exportAnnotationsToXfdf-java.io.OutputStream-}
```
public final void exportAnnotationsToXfdf(OutputStream xmlOutputStream)
```


Exports annotations to stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlOutputStream | java.io.OutputStream | OutputStream instance (Output stream) |

### exportAnnotationsXfdf(OutputStream xmlOutputStream, int start, int end, int[] annotTypes) {#exportAnnotationsXfdf-java.io.OutputStream-int-int-int---}
```
public void exportAnnotationsXfdf(OutputStream xmlOutputStream, int start, int end, int[] annotTypes)
```


Exports the content of the specified annotation types into XFDF

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight};
 OutputStream stream = new FileOutputStream("example.xfdf");
     editor.exportAnnotationsXfdf(stream, 1, 2, annotTypes);
 stream.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlOutputStream | java.io.OutputStream | The output XFDF stream. |
| start | int | Start page from which the annotations of the document will be exported. |
| end | int | End page to which the annotations of the document will be exported. |
| annotTypes | int[] | The array of annotation types need be exported. |

### extractAnnotations(int start, int end, String[] annotTypes) {#extractAnnotations-int-int-java.lang.String---}
```
public List<Annotation> extractAnnotations(int start, int end, String[] annotTypes)
```


Gets the list of annotations of the specified types.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 String[] annotTypes = new String[] {"Text", "Highlight"};
 List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| start | int | Start page from which the annotations will be selected. |
| end | int | End page to which the annotations will be selected. |
| annotTypes | java.lang.String[] | The array of needed annotation types. |

**Returns:**
java.util.List<com.aspose.pdf.Annotation> - Annotations list.
### extractAnnotations(int start, int end, int[] annotTypes) {#extractAnnotations-int-int-int---}
```
public List<Annotation> extractAnnotations(int start, int end, int[] annotTypes)
```


Gets the list of annotations of the specified types.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 int[] annotTypes = new int[] {AnnotationType.Text, AnnotationType.Highlight};
 List annotList = (List)editor.extractAnnotations(1, 2 , annotTypes);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| start | int | Start page from which the annotations will be selected. |
| end | int | End page to which the annotations will be selected. |
| annotTypes | int[] | The array of needed annotation types. |

**Returns:**
java.util.List<com.aspose.pdf.Annotation> - Annotations list.
### save(String outputFile) {#save-java.lang.String-}
```
public void save(String outputFile)
```


Saves the result PDF to file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | Output PDF file |

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Saves the result PDF to stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Output PDF stream |

### modifyAnnotations(int start, int end, Annotation annotation) {#modifyAnnotations-int-int-com.aspose.pdf.Annotation-}
```
public void modifyAnnotations(int start, int end, Annotation annotation)
```


Modifies the annotations of the specifed type on the specified page range. It supports to modify next annotation properties: Modified, Title, Contents, Color, Subject and Open.

--------------------

```
PdfAnnotationEditor editor = new PdfAnnotationEditor();
 editor.bindPdf("example.pdf");
 TextAnnotation annot = new TextAnnotation();
 annot.setModified ( new Date());
 annot.setTitle ( "NEW AUTHOR");
 annot.setContents ( "NEW CONTENTS");
 annot.setColor ( Color.RED);
 annot.setSubject ( "NEW SUBJECT");
 annot.setOpen ( true);
 editor.modifyAnnotations(1, 2, annot);
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| start | int | The start page number. |
| end | int | The end page number. |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | The annotation object contains new properties. |

### redactArea(int pageIndex, Rectangle rect, Color color) {#redactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-}
```
public void redactArea(int pageIndex, Rectangle rect, Color color)
```


Redacts area on the specified page. All contents is removed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageIndex | int | Index of the page. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Area rectangle. |
| color | java.awt.Color | Filling color. |

### redactExactArea(int pageIndex, Rectangle rect, Color color) {#redactExactArea-int-com.aspose.pdf.Rectangle-java.awt.Color-}
```
public void redactExactArea(int pageIndex, Rectangle rect, Color color)
```


Redacts area on the specified page. All contents is removed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageIndex | int | Index of the page. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Area rectangle. |
| color | java.awt.Color | Filling color. |

