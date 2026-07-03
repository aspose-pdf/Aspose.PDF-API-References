---
title: PdfContentEditor
linktitle: PdfContentEditor
second_title: Aspose.PDF for Java API Reference
description: Represents a class to edit PDF file's content.
type: docs
weight: 380
url: /java/com.aspose.pdf.facades/pdfcontenteditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfContentEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfContentEditor extends SaveableFacade
```

Represents a class to edit PDF file's content.

## Fields

| Field | Description |
| --- | --- |
| [DOCUMENT_CLOSE](#DOCUMENT_CLOSE) | A document event type. Closes a document. |
| [DOCUMENT_OPEN](#DOCUMENT_OPEN) | A document event type. Opens a document. |
| [DOCUMENT_PRINTED](#DOCUMENT_PRINTED) | A document event type. Excute a action after printing. |
| [DOCUMENT_SAVED](#DOCUMENT_SAVED) | A document event type. Excute a action after saving. |
| [DOCUMENT_WILL_PRINT](#DOCUMENT_WILL_PRINT) | A document event type. Excute a action before printing. |
| [DOCUMENT_WILL_SAVE](#DOCUMENT_WILL_SAVE) | A document event type. Excute a action before saving. |

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfContentEditor](#PdfContentEditor--) | The constructor of the PdfContentEditor object. |
| [PdfContentEditor](#PdfContentEditor-com.aspose.pdf.IDocument-) | The constructor of the PdfContentEditor object. |

## Methods

| Method | Description |
| --- | --- |
| [addDocumentAdditionalAction](#addDocumentAdditionalAction-java.lang.String-java.lang.String-) | <p> Adds additional action for document event. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-) | <p> Adds document attachment with no annotation. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.lang.String-java.lang.String-) | <p> Adds document attachment with no annotation. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [bindPdf](#bindPdf-java.io.InputStream-) | Binds a PDF stream for editing. |
| [bindPdf](#bindPdf-java.lang.String-) | Binds a PDF file for editing. |
| [changeViewerPreference](#changeViewerPreference-int-) | <p> Changes the view preference. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre> |
| [close](#close--) | Closes opened document. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-) | Creates a link to launch an application in PDF document. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | Creates a link to launch an application in PDF document. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Creates a link to launch an application in PDF document. |
| [createBookmarksAction](#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-) | Creates a bookmark with the specified action. |
| [createCaret](#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Creates caret annotation. |
| [createCustomActionLink](#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Creates a link to custom actions in PDF document. |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-) | Creates file attachment annotation. |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) | Creates file attachment annotation. |
| [createFreeText](#createFreeText-java.awt.Rectangle-java.lang.String-int-) | Creates free text annotation in PDF document |
| [createJavaScriptLink](#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-) | Creates a link to JavaScript in PDF document. |
| [createLine](#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-) | Creates line annotation. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-) | Creates a local link in PDF document. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-) | Creates a local link in PDF document. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Creates a local link in PDF document. |
| [createMarkup](#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Creates markup annotation it PDF document. |
| [createMovie](#createMovie-java.awt.Rectangle-java.lang.String-int-) |  |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-) | Creates a link to another PDF document page. |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Creates a link to another PDF document page. |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Creates a link to another PDF document page. |
| [createPolygon](#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Creates polygon annotation. |
| [createPolyLine](#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Creates polyline annotation. |
| [createPopup](#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-) | Creates popup annotation in PDF document. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-) | Creates a rubber stamp annotation. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-) | Creates a rubber stamp annotation. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Creates a rubber stamp annotation. |
| [createSound](#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) |  |
| [createSquareCircle](#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-) | Creates square-circle annotation. |
| [createText](#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-) | Creates text annotation in PDF document |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-) | Creates a web link in PDF document. |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | Creates a web link in PDF document. |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Creates a web link in PDF document. |
| [deleteAttachments](#deleteAttachments--) | <p> Deletes all attachments in PDF document. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage--) | <p> Deletes all images from PDF document. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage-int-int:A-) | <p> Deletes the specified images on the specified page. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre> |
| [deleteStamp](#deleteStamp-int-int:A-) | <p> Deletes multiple stamps on the specified page by stamp indexes. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-) | <p> Delete stamp by ID from all pages of the document. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-int-) | <p> Deletes stamp on the specified page by stamp ID. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int:A-) | <p> Deletes stamps with specified IDs from all pages of the document. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int-int:A-) | <p> Deletes stamps on the specified page by multiple stamp IDs. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre> |
| [drawCurve](#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Creates curve annotation. |
| [extractLink](#extractLink--) | <p> Extracts the collection of Link instances contained in PDF document. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // work with Link instance } </pre> |
| [getReplaceTextStrategy](#getReplaceTextStrategy--) | Get a set of parameters for replace text operation |
| [getStamps](#getStamps-int-) | Returns array of stamps on the page. |
| [getTextEditOptions](#getTextEditOptions--) | Gets text edit options. |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Gets text replace options. |
| [getTextSearchOptions](#getTextSearchOptions--) | Gets text search options. |
| [getViewerPreference](#getViewerPreference--) | <p> Returns the view preference. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre> |
| [hideStampById](#hideStampById-int-int-) | Hides the stamp. After hiding, stamp visibility may be restored with ShowStampById method. |
| [moveStamp](#moveStamp-int-int-double-double-) | Changes position of the stamp on page. |
| [moveStampById](#moveStampById-int-int-double-double-) | Changes position of the stamp on page. |
| [removeDocumentOpenAction](#removeDocumentOpenAction--) | <p> Removes open action from the document. This operation is useful when concatenating multiple documents that use explicit 'GoTo' action on startup. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre> |
| [replaceImage](#replaceImage-int-int-java.lang.String-) | <p> Replaces the specified image on the specified page of PDF document with another image. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-) | <p> Replaces text in the PDF file on the specified page. </p> <hr> <pre> The example demonstrates how to replace text in PDF document on the specified page. // open document Document doc = new Document(inFile); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text editor.replaceText("hello world", 1, "hi world"); // save document doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file on the specified page. {@code TextState} object (font family, color) can be specified to replaced text. </p> <hr> <pre> The example demonstrates how to replace text on the first page of the PDF document and set {@code TextState} text properties for the new text. // open document Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \| com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // change text with specified font editor.replaceText("hello world", 1, "hi world", textState); // save document doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-) | <p> Replaces text in the PDF file. </p> <hr> <pre> The example demonstrates how to replace text in PDF document. By default, it replaces the first found text. // open document Document doc = new Document(inFile); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text editor.replaceText("hello world", "hi world"); // save document doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-int-) | <p> Replaces text in the PDF file and sets font size. </p> <hr> <pre> The example demonstrates how to replace text and set font size for the new text. // open document Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = FontRepository.FindFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text with specified font editor.replaceText("hello world", "hi world", 14); // save document doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file using specified {@code TextState} object. </p> <hr> <pre> The example demonstrates how to replace text and set {@code TextState} text properties for the new text. Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \| com.aspose.pdf.FontStyles.Italic); // change text with specified font editor.replaceText("hello world", "hi world", textState); // save document doc.save(outFile); </pre> |
| [setReplaceTextStrategy](#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-) | Set a set of parameters for replace text operation |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Sets text edit options. |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Sets text replace options. |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Sets text search options. |
| [showStampById](#showStampById-int-int-) | Shows stamp which was hidden by HiddenStampById. |

### DOCUMENT_CLOSE {#DOCUMENT_CLOSE}
```
public static final String DOCUMENT_CLOSE
```

A document event type. Closes a document.

### DOCUMENT_OPEN {#DOCUMENT_OPEN}
```
public static final String DOCUMENT_OPEN
```

A document event type. Opens a document.

### DOCUMENT_PRINTED {#DOCUMENT_PRINTED}
```
public static final String DOCUMENT_PRINTED
```

A document event type. Excute a action after printing.

### DOCUMENT_SAVED {#DOCUMENT_SAVED}
```
public static final String DOCUMENT_SAVED
```

A document event type. Excute a action after saving.

### DOCUMENT_WILL_PRINT {#DOCUMENT_WILL_PRINT}
```
public static final String DOCUMENT_WILL_PRINT
```

A document event type. Excute a action before printing.

### DOCUMENT_WILL_SAVE {#DOCUMENT_WILL_SAVE}
```
public static final String DOCUMENT_WILL_SAVE
```

A document event type. Excute a action before saving.

### PdfContentEditor {#PdfContentEditor--}
```
public PdfContentEditor()
```

The constructor of the PdfContentEditor object.

### PdfContentEditor {#PdfContentEditor-com.aspose.pdf.IDocument-}
The constructor of the PdfContentEditor object.

### addDocumentAdditionalAction {#addDocumentAdditionalAction-java.lang.String-java.lang.String-}
<p> Adds additional action for document event. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-}
<p> Adds document attachment with no annotation. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.lang.String-java.lang.String-}
<p> Adds document attachment with no annotation. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-}
Binds a PDF stream for editing.

### bindPdf {#bindPdf-java.lang.String-}
Binds a PDF file for editing.

### changeViewerPreference {#changeViewerPreference-int-}
```
public void changeViewerPreference(int viewerAttribution)
```

<p> Changes the view preference. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| viewerAttribution |  | The view attribution defined in the ViewerPreference class. |

### close {#close--}
```
public void close()
```

Closes opened document.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-}
Creates a link to launch an application in PDF document.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
Creates a link to launch an application in PDF document.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Creates a link to launch an application in PDF document.

### createBookmarksAction {#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-}
Creates a bookmark with the specified action.

### createCaret {#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
Creates caret annotation.

### createCustomActionLink {#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Creates a link to custom actions in PDF document.

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-}
Creates file attachment annotation.

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}
Creates file attachment annotation.

### createFreeText {#createFreeText-java.awt.Rectangle-java.lang.String-int-}
Creates free text annotation in PDF document

### createJavaScriptLink {#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-}
Creates a link to JavaScript in PDF document.

### createLine {#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-}
Creates line annotation.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-}
Creates a local link in PDF document.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-}
Creates a local link in PDF document.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Creates a local link in PDF document.

### createMarkup {#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
Creates markup annotation it PDF document.

### createMovie {#createMovie-java.awt.Rectangle-java.lang.String-int-}


### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-}
Creates a link to another PDF document page.

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
Creates a link to another PDF document page.

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Creates a link to another PDF document page.

### createPolygon {#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Creates polygon annotation.

### createPolyLine {#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Creates polyline annotation.

### createPopup {#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-}
Creates popup annotation in PDF document.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-}
Creates a rubber stamp annotation.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-}
Creates a rubber stamp annotation.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
Creates a rubber stamp annotation.

### createSound {#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}


### createSquareCircle {#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-}
Creates square-circle annotation.

### createText {#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-}
Creates text annotation in PDF document

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-}
Creates a web link in PDF document.

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
Creates a web link in PDF document.

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Creates a web link in PDF document.

### deleteAttachments {#deleteAttachments--}
```
public void deleteAttachments()
```

<p> Deletes all attachments in PDF document. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage--}
```
public void deleteImage()
```

<p> Deletes all images from PDF document. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage-int-int:A-}
```
public void deleteImage(int pageNumber, int[] index)
```

<p> Deletes the specified images on the specified page. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber |  | The number of page on which images must be deleted. |
| index |  | An array repsents images' indexes. |

### deleteStamp {#deleteStamp-int-int:A-}
```
public void deleteStamp(int pageNumber, int[] index)
```

<p> Deletes multiple stamps on the specified page by stamp indexes. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber |  | Page number where stamp will be deleted. |
| index |  | Stamp indexes. |

### deleteStampById {#deleteStampById-int-}
```
public void deleteStampById(int stampId)
```

<p> Delete stamp by ID from all pages of the document. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stampId |  | Identifier of stamp which should be deleted. |

### deleteStampById {#deleteStampById-int-int-}
```
public void deleteStampById(int pageNumber, int stampId)
```

<p> Deletes stamp on the specified page by stamp ID. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber |  | Page number where stamp will be deleted. |
| stampId |  | Identifier of stamp which should be deleted. |

### deleteStampByIds {#deleteStampByIds-int:A-}
```
public void deleteStampByIds(int[] stampIds)
```

<p> Deletes stamps with specified IDs from all pages of the document. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stampIds |  | Array of stamp IDs. |

### deleteStampByIds {#deleteStampByIds-int-int:A-}
```
public void deleteStampByIds(int pageNumber, int[] stampIds)
```

<p> Deletes stamps on the specified page by multiple stamp IDs. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber |  | Page number where stamps will be deleted. |
| stampIds |  | Array of stamp IDs. |

### drawCurve {#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Creates curve annotation.

### extractLink {#extractLink--}
```
public List < Annotation > extractLink()
```

<p> Extracts the collection of Link instances contained in PDF document. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // work with Link instance } </pre>

**Returns:**
The collection of Link objects

### getReplaceTextStrategy {#getReplaceTextStrategy--}
```
public ReplaceTextStrategy getReplaceTextStrategy()
```

Get a set of parameters for replace text operation

**Returns:**
ReplaceTextStrategy element

### getStamps {#getStamps-int-}
```
public StampInfo [] getStamps(int pageNumber)
```

Returns array of stamps on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber |  | Page number where stamps will be searched. |

**Returns:**
Array of stamps.

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Gets text edit options.

**Returns:**
TextEditOptions element

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

Gets text replace options.

**Returns:**
TextReplaceOptions element

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Gets text search options.

**Returns:**
TextSearchOptions element

### getViewerPreference {#getViewerPreference--}
```
public int getViewerPreference()
```

<p> Returns the view preference. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre>

**Returns:**
Returns set of ViewerPrefernece flags

### hideStampById {#hideStampById-int-int-}
```
public void hideStampById(int pageNumber, int stampId)
```

Hides the stamp. After hiding, stamp visibility may be restored with ShowStampById method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber |  | Number of the page. |
| stampId |  | Identifier of stamp which should be hidden. |

### moveStamp {#moveStamp-int-int-double-double-}
```
public void moveStamp(int pageNumber, int stampIndex, double x, double y)
```

Changes position of the stamp on page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber |  | Number of page. |
| stampIndex |  | Index of stamp on the page. |
| x |  | New stamp horizontal position. |
| y |  | New stamp vertical position. |

### moveStampById {#moveStampById-int-int-double-double-}
```
public void moveStampById(int pageNumber, int stampId, double x, double y)
```

Changes position of the stamp on page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber |  | Numer of page. |
| stampId |  | Identifier of stamp which should be moved. |
| x |  | New stamp horizontal pozition on the page. |
| y |  | New stamp vertical position on the page. |

### removeDocumentOpenAction {#removeDocumentOpenAction--}
```
public void removeDocumentOpenAction()
```

<p> Removes open action from the document. This operation is useful when concatenating multiple documents that use explicit 'GoTo' action on startup. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre>

### replaceImage {#replaceImage-int-int-java.lang.String-}
<p> Replaces the specified image on the specified page of PDF document with another image. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-}
<p> Replaces text in the PDF file on the specified page. </p> <hr> <pre> The example demonstrates how to replace text in PDF document on the specified page. // open document Document doc = new Document(inFile); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text editor.replaceText("hello world", 1, "hi world"); // save document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-}
<p> Replaces text in the PDF file on the specified page. {@code TextState} object (font family, color) can be specified to replaced text. </p> <hr> <pre> The example demonstrates how to replace text on the first page of the PDF document and set {@code TextState} text properties for the new text. // open document Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // change text with specified font editor.replaceText("hello world", 1, "hi world", textState); // save document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-}
<p> Replaces text in the PDF file. </p> <hr> <pre> The example demonstrates how to replace text in PDF document. By default, it replaces the first found text. // open document Document doc = new Document(inFile); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text editor.replaceText("hello world", "hi world"); // save document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-int-}
<p> Replaces text in the PDF file and sets font size. </p> <hr> <pre> The example demonstrates how to replace text and set font size for the new text. // open document Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = FontRepository.FindFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text with specified font editor.replaceText("hello world", "hi world", 14); // save document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-}
<p> Replaces text in the PDF file using specified {@code TextState} object. </p> <hr> <pre> The example demonstrates how to replace text and set {@code TextState} text properties for the new text. Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); // change text with specified font editor.replaceText("hello world", "hi world", textState); // save document doc.save(outFile); </pre>

### setReplaceTextStrategy {#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-}
Set a set of parameters for replace text operation

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Sets text edit options.

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Sets text replace options.

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Sets text search options.

### showStampById {#showStampById-int-int-}
```
public void showStampById(int pageNumber, int stampId)
```

Shows stamp which was hidden by HiddenStampById.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber |  | Number of the page. |
| stampId |  | Identifier of stamp which should be shown. |
