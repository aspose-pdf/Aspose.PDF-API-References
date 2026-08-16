---
title: "PdfContentEditor"
linktitle: "PdfContentEditor"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para editar el contenido de archivos PDF."
type: docs
weight: 380
url: /es/java/com.aspose.pdf.facades/pdfcontenteditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfContentEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfContentEditor extends SaveableFacade
```

Representa una clase para editar el contenido de archivos PDF.

## Campos

| Campo | Descripción |
| --- | --- |
| [DOCUMENT_CLOSE](#DOCUMENT_CLOSE) | Un tipo de evento de documento. Cierra un documento. |
| [DOCUMENT_OPEN](#DOCUMENT_OPEN) | Un tipo de evento de documento. Abre un documento. |
| [DOCUMENT_PRINTED](#DOCUMENT_PRINTED) | Un tipo de evento de documento. Ejecuta una acción después de imprimir. |
| [DOCUMENT_SAVED](#DOCUMENT_SAVED) | Un tipo de evento de documento. Ejecuta una acción después de guardar. |
| [DOCUMENT_WILL_PRINT](#DOCUMENT_WILL_PRINT) | Un tipo de evento de documento. Ejecuta una acción antes de imprimir. |
| [DOCUMENT_WILL_SAVE](#DOCUMENT_WILL_SAVE) | Un tipo de evento de documento. Ejecuta una acción antes de guardar. |

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfContentEditor](#PdfContentEditor--) | El constructor del objeto PdfContentEditor. |
| [PdfContentEditor](#PdfContentEditor-com.aspose.pdf.IDocument-) | El constructor del objeto PdfContentEditor. |

## Métodos

| Método | Descripción |
| --- | --- |
| [addDocumentAdditionalAction](#addDocumentAdditionalAction-java.lang.String-java.lang.String-) | <p> Agrega una acción adicional para el evento del documento. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-) | <p> Agrega un adjunto de documento sin anotación. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.lang.String-java.lang.String-) | <p> Agrega un adjunto de documento sin anotación. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [bindPdf](#bindPdf-java.io.InputStream-) | Vincula una secuencia PDF para editar. |
| [bindPdf](#bindPdf-java.lang.String-) | Vincula un archivo PDF para editar. |
| [changeViewerPreference](#changeViewerPreference-int-) | <p> Cambia la preferencia de vista. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre> |
| [close](#close--) | Cierra el documento abierto. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-) | Crea un enlace para lanzar una aplicación en el documento PDF. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | Crea un enlace para lanzar una aplicación en el documento PDF. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Crea un enlace para lanzar una aplicación en el documento PDF. |
| [createBookmarksAction](#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-) | Crea un marcador con la acción especificada. |
| [createCaret](#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Crea una anotación de cursor. |
| [createCustomActionLink](#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Crea un enlace a acciones personalizadas en el documento PDF. |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-) | Crea una anotación de adjunto de archivo. |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) | Crea una anotación de adjunto de archivo. |
| [createFreeText](#createFreeText-java.awt.Rectangle-java.lang.String-int-) | Crea una anotación de texto libre en el documento PDF |
| [createJavaScriptLink](#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-) | Crea un enlace a JavaScript en el documento PDF. |
| [createLine](#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-) | Crea una anotación de línea. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-) | Crea un enlace local en el documento PDF. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-) | Crea un enlace local en el documento PDF. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Crea un enlace local en el documento PDF. |
| [createMarkup](#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Crea una anotación de marcado en el documento PDF. |
| [createMovie](#createMovie-java.awt.Rectangle-java.lang.String-int-) |  |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-) | Crea un enlace a otra página de documento PDF. |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Crea un enlace a otra página de documento PDF. |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Crea un enlace a otra página de documento PDF. |
| [createPolygon](#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Crea una anotación de polígono. |
| [createPolyLine](#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Crea una anotación de polilínea. |
| [createPopup](#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-) | Crea una anotación emergente en el documento PDF. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-) | Crea una anotación de sello de goma. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-) | Crea una anotación de sello de goma. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Crea una anotación de sello de goma. |
| [createSound](#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) |  |
| [createSquareCircle](#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-) | Crea una anotación de cuadrado-círculo. |
| [createText](#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-) | Crea una anotación de texto en el documento PDF |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-) | Crea un enlace web en el documento PDF. |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | Crea un enlace web en el documento PDF. |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Crea un enlace web en el documento PDF. |
| [deleteAttachments](#deleteAttachments--) | <p> Elimina todos los archivos adjuntos en el documento PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage--) | <p> Elimina todas las imágenes del documento PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage-int-int:A-) | <p> Elimina las imágenes especificadas en la página especificada. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre> |
| [deleteStamp](#deleteStamp-int-int:A-) | <p> Elimina varios sellos en la página especificada por índices de sello. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-) | <p> Elimina el sello por ID de todas las páginas del documento. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-int-) | <p> Elimina el sello en la página especificada por ID de sello. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int:A-) | <p> Elimina los sellos con IDs especificados de todas las páginas del documento. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int-int:A-) | <p> Elimina los sellos en la página especificada por varios IDs de sello. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre> |
| [drawCurve](#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Crea una anotación de curva. |
| [extractLink](#extractLink--) | <p> Extrae la colección de instancias Link contenidas en el documento PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // work with Link instance } </pre> |
| [getReplaceTextStrategy](#getReplaceTextStrategy--) | Obtén un conjunto de parámetros para la operación de reemplazo de texto |
| [getStamps](#getStamps-int-) | Devuelve una matriz de sellos en la página. |
| [getTextEditOptions](#getTextEditOptions--) | Obtiene opciones de edición de texto. |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Obtiene opciones de reemplazo de texto. |
| [getTextSearchOptions](#getTextSearchOptions--) | Obtiene opciones de búsqueda de texto. |
| [getViewerPreference](#getViewerPreference--) | <p> Devuelve la preferencia de vista. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre> |
| [hideStampById](#hideStampById-int-int-) | Oculta el sello. Después de ocultarlo, la visibilidad del sello puede restaurarse con el método ShowStampById. |
| [moveStamp](#moveStamp-int-int-double-double-) | Cambia la posición del sello en la página. |
| [moveStampById](#moveStampById-int-int-double-double-) | Cambia la posición del sello en la página. |
| [removeDocumentOpenAction](#removeDocumentOpenAction--) | <p> Elimina la acción de apertura del documento. Esta operación es útil al concatenar varios documentos que utilizan una acción explícita 'GoTo' al iniciar. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre> |
| [replaceImage](#replaceImage-int-int-java.lang.String-) | <p> Reemplaza la imagen especificada en la página especificada del documento PDF con otra imagen. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-) | <p> Reemplaza texto en el archivo PDF en la página especificada. </p> <hr> <pre> El ejemplo muestra cómo reemplazar texto en el documento PDF en la página especificada. // abre el documento Document doc = new Document(inFile); // crea un objeto PdfContentEditor para editar texto PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // cambia el texto editor.replaceText("hello world", 1, "hi world"); // guarda el documento doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file on the specified page. {@code TextState} object (font family, color) can be specified to replaced text. </p> <hr> <pre> The example demonstrates how to replace text on the first page of the PDF document and set {@code TextState} text properties for the new text. // open document Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // cambiar texto con la fuente especificada editor.replaceText("hello world", 1, "hi world", textState); // guardar documento doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-) | <p> Reemplaza texto en el archivo PDF. </p> <hr> <pre> El ejemplo muestra cómo reemplazar texto en un documento PDF. Por defecto, reemplaza el primer texto encontrado. // abrir documento Document doc = new Document(inFile); // crear objeto PdfContentEditor para editar texto PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // cambiar texto editor.replaceText("hello world", "hi world"); // guardar documento doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-int-) | <p> Reemplaza texto en el archivo PDF y establece el tamaño de fuente. </p> <hr> <pre> El ejemplo muestra cómo reemplazar texto y establecer el tamaño de fuente para el nuevo texto. // abrir documento Document doc = new Document(inFile); // crear fuente y marcarla para incrustarse com.aspose.pdf.Font font = FontRepository.FindFont("Courier New"); font.isEmbedded ( true); // crear objeto PdfContentEditor para editar texto PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // cambiar texto con la fuente especificada editor.replaceText("hello world", "hi world", 14); // guardar documento doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file using specified {@code TextState} object. </p> <hr> <pre> The example demonstrates how to replace text and set {@code TextState} text properties for the new text. Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); // cambiar texto con la fuente especificada editor.replaceText("hello world", "hi world", textState); // guardar documento doc.save(outFile); </pre> |
| [setReplaceTextStrategy](#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-) | Establecer un conjunto de parámetros para la operación de reemplazo de texto |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Establece opciones de edición de texto. |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Establece opciones de reemplazo de texto. |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Establece opciones de búsqueda de texto. |
| [showStampById](#showStampById-int-int-) | Muestra el sello que fue ocultado por HiddenStampById. |

### DOCUMENT_CLOSE {#DOCUMENT_CLOSE}
```
public static final String DOCUMENT_CLOSE
```

Un tipo de evento de documento. Cierra un documento.

### DOCUMENT_OPEN {#DOCUMENT_OPEN}
```
public static final String DOCUMENT_OPEN
```

Un tipo de evento de documento. Abre un documento.

### DOCUMENT_PRINTED {#DOCUMENT_PRINTED}
```
public static final String DOCUMENT_PRINTED
```

Un tipo de evento de documento. Ejecuta una acción después de imprimir.

### DOCUMENT_SAVED {#DOCUMENT_SAVED}
```
public static final String DOCUMENT_SAVED
```

Un tipo de evento de documento. Ejecuta una acción después de guardar.

### DOCUMENT_WILL_PRINT {#DOCUMENT_WILL_PRINT}
```
public static final String DOCUMENT_WILL_PRINT
```

Un tipo de evento de documento. Ejecuta una acción antes de imprimir.

### DOCUMENT_WILL_SAVE {#DOCUMENT_WILL_SAVE}
```
public static final String DOCUMENT_WILL_SAVE
```

Un tipo de evento de documento. Ejecuta una acción antes de guardar.

### PdfContentEditor {#PdfContentEditor--}
```
public PdfContentEditor()
```

El constructor del objeto PdfContentEditor.

### PdfContentEditor {#PdfContentEditor-com.aspose.pdf.IDocument-}
El constructor del objeto PdfContentEditor.

### addDocumentAdditionalAction {#addDocumentAdditionalAction-java.lang.String-java.lang.String-}
<p> Agrega una acción adicional para el evento del documento. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-}
<p> Agrega un adjunto de documento sin anotación. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.lang.String-java.lang.String-}
<p> Agrega un adjunto de documento sin anotación. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-}
Vincula una secuencia PDF para editar.

### bindPdf {#bindPdf-java.lang.String-}
Vincula un archivo PDF para editar.

### changeViewerPreference {#changeViewerPreference-int-}
```
public void changeViewerPreference(int viewerAttribution)
```

<p> Cambia la preferencia de vista. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| viewerAttribution |  | La atribución de vista definida en la clase ViewerPreference. |

### close {#close--}
```
public void close()
```

Cierra el documento abierto.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-}
Crea un enlace para lanzar una aplicación en el documento PDF.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
Crea un enlace para lanzar una aplicación en el documento PDF.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Crea un enlace para lanzar una aplicación en el documento PDF.

### createBookmarksAction {#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-}
Crea un marcador con la acción especificada.

### createCaret {#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
Crea una anotación de cursor.

### createCustomActionLink {#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Crea un enlace a acciones personalizadas en el documento PDF.

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-}
Crea una anotación de adjunto de archivo.

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}
Crea una anotación de adjunto de archivo.

### createFreeText {#createFreeText-java.awt.Rectangle-java.lang.String-int-}
Crea una anotación de texto libre en el documento PDF

### createJavaScriptLink {#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-}
Crea un enlace a JavaScript en el documento PDF.

### createLine {#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-}
Crea una anotación de línea.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-}
Crea un enlace local en el documento PDF.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-}
Crea un enlace local en el documento PDF.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Crea un enlace local en el documento PDF.

### createMarkup {#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
Crea una anotación de marcado en el documento PDF.

### createMovie {#createMovie-java.awt.Rectangle-java.lang.String-int-}


### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-}
Crea un enlace a otra página de documento PDF.

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
Crea un enlace a otra página de documento PDF.

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Crea un enlace a otra página de documento PDF.

### createPolygon {#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Crea una anotación de polígono.

### createPolyLine {#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Crea una anotación de polilínea.

### createPopup {#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-}
Crea una anotación emergente en el documento PDF.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-}
Crea una anotación de sello de goma.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-}
Crea una anotación de sello de goma.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
Crea una anotación de sello de goma.

### createSound {#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}


### createSquareCircle {#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-}
Crea una anotación de cuadrado-círculo.

### createText {#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-}
Crea una anotación de texto en el documento PDF

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-}
Crea un enlace web en el documento PDF.

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
Crea un enlace web en el documento PDF.

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Crea un enlace web en el documento PDF.

### deleteAttachments {#deleteAttachments--}
```
public void deleteAttachments()
```

<p> Elimina todos los archivos adjuntos en el documento PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage--}
```
public void deleteImage()
```

<p> Elimina todas las imágenes del documento PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage-int-int:A-}
```
public void deleteImage(int pageNumber, int[] index)
```

<p> Elimina las imágenes especificadas en la página especificada. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber |  | El número de página en la que se deben eliminar las imágenes. |
| index |  | Una matriz representa los índices de las imágenes. |

### deleteStamp {#deleteStamp-int-int:A-}
```
public void deleteStamp(int pageNumber, int[] index)
```

<p> Elimina varios sellos en la página especificada por índices de sello. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber |  | Número de página donde se eliminará el sello. |
| index |  | Índices de sellos. |

### deleteStampById {#deleteStampById-int-}
```
public void deleteStampById(int stampId)
```

<p> Elimina el sello por ID de todas las páginas del documento. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stampId |  | Identificador del sello que debe ser eliminado. |

### deleteStampById {#deleteStampById-int-int-}
```
public void deleteStampById(int pageNumber, int stampId)
```

<p> Elimina el sello en la página especificada por ID de sello. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber |  | Número de página donde se eliminará el sello. |
| stampId |  | Identificador del sello que debe ser eliminado. |

### deleteStampByIds {#deleteStampByIds-int:A-}
```
public void deleteStampByIds(int[] stampIds)
```

<p> Elimina los sellos con IDs especificados de todas las páginas del documento. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stampIds |  | Matriz de IDs de sellos. |

### deleteStampByIds {#deleteStampByIds-int-int:A-}
```
public void deleteStampByIds(int pageNumber, int[] stampIds)
```

<p> Elimina los sellos en la página especificada por varios IDs de sello. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber |  | Número de página donde se eliminarán los sellos. |
| stampIds |  | Matriz de IDs de sellos. |

### drawCurve {#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Crea una anotación de curva.

### extractLink {#extractLink--}
```
public List < Annotation > extractLink()
```

<p> Extrae la colección de instancias Link contenidas en el documento PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // work with Link instance } </pre>

**Returns:**
La colección de objetos Link

### getReplaceTextStrategy {#getReplaceTextStrategy--}
```
public ReplaceTextStrategy getReplaceTextStrategy()
```

Obtén un conjunto de parámetros para la operación de reemplazo de texto

**Returns:**
Elemento ReplaceTextStrategy

### getStamps {#getStamps-int-}
```
public StampInfo [] getStamps(int pageNumber)
```

Devuelve una matriz de sellos en la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber |  | Número de página donde se buscarán los sellos. |

**Returns:**
Matriz de sellos.

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Obtiene opciones de edición de texto.

**Returns:**
Elemento TextEditOptions

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

Obtiene opciones de reemplazo de texto.

**Returns:**
Elemento TextReplaceOptions

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Obtiene opciones de búsqueda de texto.

**Returns:**
Elemento TextSearchOptions

### getViewerPreference {#getViewerPreference--}
```
public int getViewerPreference()
```

<p> Devuelve la preferencia de vista. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre>

**Returns:**
Devuelve el conjunto de banderas ViewerPrefernece

### hideStampById {#hideStampById-int-int-}
```
public void hideStampById(int pageNumber, int stampId)
```

Oculta el sello. Después de ocultarlo, la visibilidad del sello puede restaurarse con el método ShowStampById.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber |  | Número de la página. |
| stampId |  | Identificador del sello que debe ocultarse. |

### moveStamp {#moveStamp-int-int-double-double-}
```
public void moveStamp(int pageNumber, int stampIndex, double x, double y)
```

Cambia la posición del sello en la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber |  | Número de página. |
| stampIndex |  | Índice del sello en la página. |
| x |  | Nueva posición horizontal del sello. |
| y |  | Nueva posición vertical del sello. |

### moveStampById {#moveStampById-int-int-double-double-}
```
public void moveStampById(int pageNumber, int stampId, double x, double y)
```

Cambia la posición del sello en la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber |  | Número de página. |
| stampId |  | Identificador del sello que debe moverse. |
| x |  | Nueva posición horizontal del sello en la página. |
| y |  | Nueva posición vertical del sello en la página. |

### removeDocumentOpenAction {#removeDocumentOpenAction--}
```
public void removeDocumentOpenAction()
```

<p> Elimina la acción de apertura del documento. Esta operación es útil al concatenar varios documentos que utilizan una acción explícita 'GoTo' al iniciar. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre>

### replaceImage {#replaceImage-int-int-java.lang.String-}
<p> Reemplaza la imagen especificada en la página especificada del documento PDF con otra imagen. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-}
<p> Reemplaza texto en el archivo PDF en la página especificada. </p> <hr> <pre> El ejemplo muestra cómo reemplazar texto en el documento PDF en la página especificada. // abre el documento Document doc = new Document(inFile); // crea un objeto PdfContentEditor para editar texto PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // cambia el texto editor.replaceText("hello world", 1, "hi world"); // guarda el documento doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-}
<p> Reemplaza texto en el archivo PDF en la página especificada. {@code TextState} objeto (font family, color) puede especificarse para el texto reemplazado. </p> <hr> <pre> El ejemplo muestra cómo reemplazar texto en la primera página del documento PDF y establecer las propiedades de texto {@code TextState} para el nuevo texto. // abrir documento Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // crear objeto PdfContentEditor para editar texto PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // crear objeto textState com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // cambiar texto con la fuente especificada editor.replaceText("hello world", 1, "hi world", textState); // guardar documento doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-}
<p> Reemplaza texto en el archivo PDF. </p> <hr> <pre> El ejemplo muestra cómo reemplazar texto en un documento PDF. Por defecto, reemplaza el primer texto encontrado. // abrir documento Document doc = new Document(inFile); // crear objeto PdfContentEditor para editar texto PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // cambiar texto editor.replaceText("hello world", "hi world"); // guardar documento doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-int-}
<p> Reemplaza texto en el archivo PDF y establece el tamaño de fuente. </p> <hr> <pre> El ejemplo muestra cómo reemplazar texto y establecer el tamaño de fuente para el nuevo texto. // abrir documento Document doc = new Document(inFile); // crear fuente y marcarla para incrustarse com.aspose.pdf.Font font = FontRepository.FindFont("Courier New"); font.isEmbedded ( true); // crear objeto PdfContentEditor para editar texto PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // cambiar texto con la fuente especificada editor.replaceText("hello world", "hi world", 14); // guardar documento doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-}
<p> Reemplaza texto en el archivo PDF usando el objeto {@code TextState} especificado. </p> <hr> <pre> El ejemplo muestra cómo reemplazar texto y establecer las propiedades de texto {@code TextState} para el nuevo texto. Document doc = new Document(inFile); // Crear fuente y marcarla para incrustar com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // crear objeto PdfContentEditor para editar texto PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // crear objeto textState com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); // cambiar texto con la fuente especificada editor.replaceText("hello world", "hi world", textState); // guardar documento doc.save(outFile); </pre>

### setReplaceTextStrategy {#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-}
Establecer un conjunto de parámetros para la operación de reemplazo de texto

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Establece opciones de edición de texto.

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Establece opciones de reemplazo de texto.

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Establece opciones de búsqueda de texto.

### showStampById {#showStampById-int-int-}
```
public void showStampById(int pageNumber, int stampId)
```

Muestra el sello que fue ocultado por HiddenStampById.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber |  | Número de la página. |
| stampId |  | Identificador del sello que debe mostrarse. |
