---
title: PdfContentEditor
second_title: Aspose.PDF for Java API Reference
description: Represents a class to edit PDF files content.
type: docs
weight: 36
url: /java/com.aspose.pdf.facades/pdfcontenteditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfContentEditor extends SaveableFacade
```

Represents a class to edit PDF file's content.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfContentEditor()](#PdfContentEditor--) | The constructor of the PdfContentEditor object. |
| [PdfContentEditor(IDocument document)](#PdfContentEditor-com.aspose.pdf.IDocument-) | Initializes new  PdfContentEditor  object on base of the  document . |
## Fields

| Field | Description |
| --- | --- |
| [DOCUMENT_OPEN](#DOCUMENT-OPEN) | A document event type. |
| [DOCUMENT_CLOSE](#DOCUMENT-CLOSE) | A document event type. |
| [DOCUMENT_WILL_SAVE](#DOCUMENT-WILL-SAVE) | A document event type. |
| [DOCUMENT_SAVED](#DOCUMENT-SAVED) | A document event type. |
| [DOCUMENT_WILL_PRINT](#DOCUMENT-WILL-PRINT) | A document event type. |
| [DOCUMENT_PRINTED](#DOCUMENT-PRINTED) | A document event type. |
## Methods

| Method | Description |
| --- | --- |
| [getTextSearchOptions()](#getTextSearchOptions--) | Gets text search options. |
| [setTextSearchOptions(TextSearchOptions value)](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Sets text search options. |
| [getTextEditOptions()](#getTextEditOptions--) | Gets text edit options. |
| [setTextEditOptions(TextEditOptions value)](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Sets text edit options. |
| [getTextReplaceOptions()](#getTextReplaceOptions--) | Gets text replace options. |
| [setTextReplaceOptions(TextReplaceOptions value)](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Sets text replace options. |
| [getReplaceTextStrategy()](#getReplaceTextStrategy--) | Get a set of parameters for replace text operation |
| [setReplaceTextStrategy(ReplaceTextStrategy value)](#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-) | Set a set of parameters for replace text operation |
| [bindPdf(String inputFile)](#bindPdf-java.lang.String-) | Binds a PDF file for editing. |
| [bindPdf(InputStream inputStream)](#bindPdf-java.io.InputStream-) | Binds a PDF stream for editing. |
| [extractLink()](#extractLink--) | Extracts the collection of Link instances contained in PDF document. |
| [createWebLink(Rectangle rect, String url, int originalPage, Color clr, int[] actionName)](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-int---) | Creates a web link in PDF document. |
| [createWebLink(Rectangle rect, String url, int originalPage, Color clr)](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | Creates a web link in PDF document. |
| [createWebLink(Rectangle rect, String url, int originalPage)](#createWebLink-java.awt.Rectangle-java.lang.String-int-) | Creates a web link in PDF document. |
| [createLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, int[] actionName)](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-int---) | Creates a local link in PDF document. |
| [createLocalLink(Rectangle rect, int desPage, int originalPage, Color clr)](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-) | Creates a local link in PDF document. |
| [createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage, Color clr, int[] actionName)](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-int---) | Creates a link to another PDF document page. |
| [createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage, Color clr)](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Creates a link to another PDF document page. |
| [createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage)](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-) | Creates a link to another PDF document page. |
| [createCustomActionLink(Rectangle rect, int originalPage, Color color, int[] actionName)](#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-int---) | Creates a link to custom actions in PDF document. |
| [createApplicationLink(Rectangle rect, String application, int page, Color clr, int[] actionName)](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-int---) | Creates a link to launch an application in PDF document. |
| [createApplicationLink(Rectangle rect, String application, int page, Color clr)](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | Creates a link to launch an application in PDF document. |
| [createApplicationLink(Rectangle rect, String application, int page)](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-) | Creates a link to launch an application in PDF document. |
| [createJavaScriptLink(String code, Rectangle rect, int originalPage, Color color)](#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-) | Creates a link to JavaScript in PDF document. |
| [createText(Rectangle rect, String title, String contents, boolean open, String icon, int page)](#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-) | Creates text annotation in PDF document |
| [createFreeText(Rectangle rect, String contents, int page)](#createFreeText-java.awt.Rectangle-java.lang.String-int-) | Creates free text annotation in PDF document |
| [createMarkup(Rectangle rect, String contents, int type, int page, Color clr)](#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Creates markup annotation it PDF document. |
| [createPopup(Rectangle rect, String contents, boolean open, int page)](#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-) | Creates popup annotation in PDF document. |
| [createFileAttachment(Rectangle rect, String contents, String filePath, int page, String name)](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) | Creates file attachment annotation. |
| [createFileAttachment(Rectangle rect, String contents, InputStream attachmentStream, String attachmentName, int page, String name)](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-) | Creates file attachment annotation. |
| [addDocumentAttachment(String fileAttachmentPath, String description)](#addDocumentAttachment-java.lang.String-java.lang.String-) | Adds document attachment with no annotation. |
| [addDocumentAttachment(InputStream fileAttachmentStream, String fileAttachmentName, String description)](#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-) | Adds document attachment with no annotation. |
| [deleteAttachments()](#deleteAttachments--) | Deletes all attachments in PDF document. |
| [createLine(Rectangle rect, String contents, float x1, float y1, float x2, float y2, int page, int border, Color clr, String borderStyle, int[] dashArray, String[] LEArray)](#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int---java.lang.String---) | Creates line annotation. |
| [createSquareCircle(Rectangle rect, String contents, Color clr, boolean square, int page, int borderWidth)](#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-) | Creates square-circle annotation. |
| [drawCurve(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents)](#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Creates curve annotation. |
| [createPolygon(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents)](#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Creates polygon annotation. |
| [createPolyLine(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents)](#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Creates polyline annotation. |
| [createCaret(int page, Rectangle annotRect, Rectangle caretRect, String symbol, String annotContents, Color color)](#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Creates caret annotation. |
| [createRubberStamp(int page, Rectangle annotRect, String icon, String annotContents, Color color)](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Creates a rubber stamp annotation. |
| [createRubberStamp(int page, Rectangle annotRect, String annotContents, Color color, String appearanceFile)](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-) | Creates a rubber stamp annotation. |
| [createRubberStamp(int page, Rectangle annotRect, String annotContents, Color color, InputStream appearanceStream)](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-) | Creates a rubber stamp annotation. |
| [createBookmarksAction(String title, Color color, boolean boldFlag, boolean italicFlag, String file, String actionType, String destination)](#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-) | Creates a bookmark with the specified action. |
| [addDocumentAdditionalAction(String eventType, String code)](#addDocumentAdditionalAction-java.lang.String-java.lang.String-) | Adds additional action for document event. |
| [removeDocumentOpenAction()](#removeDocumentOpenAction--) | Removes open action from the document. |
| [changeViewerPreference(int viewerAttribution)](#changeViewerPreference-int-) | Changes the view preference. |
| [getViewerPreference()](#getViewerPreference--) | Returns the view preference. |
| [replaceImage(int pageNumber, int index, String imageFile)](#replaceImage-int-int-java.lang.String-) | Replaces the specified image on the specified page of PDF document with another image. |
| [deleteImage(int pageNumber, int[] index)](#deleteImage-int-int---) | Deletes the specified images on the specified page. |
| [deleteImage()](#deleteImage--) | Deletes all images from PDF document. |
| [replaceText(String srcString, int thePage, String destString, TextState textState)](#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-) | Replaces text in the PDF file on the specified page. |
| [replaceText(String srcString, String destString)](#replaceText-java.lang.String-java.lang.String-) | Replaces text in the PDF file. |
| [replaceText(String srcString, int thePage, String destString)](#replaceText-java.lang.String-int-java.lang.String-) | Replaces text in the PDF file on the specified page. |
| [replaceText(String srcString, String destString, TextState textState)](#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-) | Replaces text in the PDF file using specified  TextState  object. |
| [createMovie(Rectangle rect, String filePath, int page)](#createMovie-java.awt.Rectangle-java.lang.String-int-) |  |
| [createSound(Rectangle rect, String filePath, String name, int page, String rate)](#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) |  |
| [deleteStamp(int pageNumber, int[] index)](#deleteStamp-int-int---) | Deletes multiple stamps on the specified page by stamp indexes. |
| [deleteStampByIds(int[] stampIds)](#deleteStampByIds-int---) | Deletes stamps with specified IDs from all pages of the document. |
| [deleteStampByIds(int pageNumber, int[] stampIds)](#deleteStampByIds-int-int---) | Deletes stamps on the specified page by multiple stamp IDs. |
| [deleteStampById(int pageNumber, int stampId)](#deleteStampById-int-int-) | Deletes stamp on the specified page by stamp ID. |
| [hideStampById(int pageNumber, int stampId)](#hideStampById-int-int-) | Hides the stamp. |
| [showStampById(int pageNumber, int stampId)](#showStampById-int-int-) | Shows stamp which was hidden by HiddenStampById. |
| [moveStampById(int pageNumber, int stampId, double x, double y)](#moveStampById-int-int-double-double-) | Changes position of the stamp on page. |
| [moveStamp(int pageNumber, int stampIndex, double x, double y)](#moveStamp-int-int-double-double-) | Changes position of the stamp on page. |
| [deleteStampById(int stampId)](#deleteStampById-int-) | Delete stamp by ID from all pages of the document. |
| [createLocalLink(Rectangle rect, int desPage, int originalPage)](#createLocalLink-java.awt.Rectangle-int-int-) | Creates a local link in PDF document. |
| [replaceText(String srcString, String destString, int fontSize)](#replaceText-java.lang.String-java.lang.String-int-) | Replaces text in the PDF file and sets font size. |
| [getStamps(int pageNumber)](#getStamps-int-) | Returns array of stamps on the page. |
| [close()](#close--) | Closes opened document. |
### PdfContentEditor() {#PdfContentEditor--}
```
public PdfContentEditor()
```


The constructor of the PdfContentEditor object.

### PdfContentEditor(IDocument document) {#PdfContentEditor-com.aspose.pdf.IDocument-}
```
public PdfContentEditor(IDocument document)
```


Initializes new  PdfContentEditor  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |

### DOCUMENT_OPEN {#DOCUMENT-OPEN}
```
public static final String DOCUMENT_OPEN
```


A document event type. Opens a document.

### DOCUMENT_CLOSE {#DOCUMENT-CLOSE}
```
public static final String DOCUMENT_CLOSE
```


A document event type. Closes a document.

### DOCUMENT_WILL_SAVE {#DOCUMENT-WILL-SAVE}
```
public static final String DOCUMENT_WILL_SAVE
```


A document event type. Excute a action before saving.

### DOCUMENT_SAVED {#DOCUMENT-SAVED}
```
public static final String DOCUMENT_SAVED
```


A document event type. Excute a action after saving.

### DOCUMENT_WILL_PRINT {#DOCUMENT-WILL-PRINT}
```
public static final String DOCUMENT_WILL_PRINT
```


A document event type. Excute a action before printing.

### DOCUMENT_PRINTED {#DOCUMENT-PRINTED}
```
public static final String DOCUMENT_PRINTED
```


A document event type. Excute a action after printing.

### getTextSearchOptions() {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```


Gets text search options.

**Returns:**
[TextSearchOptions](../../com.aspose.pdf/textsearchoptions) - TextSearchOptions element
### setTextSearchOptions(TextSearchOptions value) {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
```
public void setTextSearchOptions(TextSearchOptions value)
```


Sets text search options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | TextSearchOptions element |

### getTextEditOptions() {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```


Gets text edit options.

**Returns:**
[TextEditOptions](../../com.aspose.pdf/texteditoptions) - TextEditOptions element
### setTextEditOptions(TextEditOptions value) {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
```
public void setTextEditOptions(TextEditOptions value)
```


Sets text edit options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | setTextEditOptions element |

### getTextReplaceOptions() {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```


Gets text replace options.

**Returns:**
[TextReplaceOptions](../../com.aspose.pdf/textreplaceoptions) - TextReplaceOptions element
### setTextReplaceOptions(TextReplaceOptions value) {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
```
public void setTextReplaceOptions(TextReplaceOptions value)
```


Sets text replace options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextReplaceOptions](../../com.aspose.pdf/textreplaceoptions) | TextReplaceOptions element |

### getReplaceTextStrategy() {#getReplaceTextStrategy--}
```
public ReplaceTextStrategy getReplaceTextStrategy()
```


Get a set of parameters for replace text operation

**Returns:**
[ReplaceTextStrategy](../../com.aspose.pdf.facades/replacetextstrategy) - ReplaceTextStrategy element
### setReplaceTextStrategy(ReplaceTextStrategy value) {#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-}
```
public void setReplaceTextStrategy(ReplaceTextStrategy value)
```


Set a set of parameters for replace text operation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ReplaceTextStrategy](../../com.aspose.pdf.facades/replacetextstrategy) | ReplaceTextStrategy element |

### bindPdf(String inputFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String inputFile)
```


Binds a PDF file for editing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | A PDF file to be edited. |

### bindPdf(InputStream inputStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream inputStream)
```


Binds a PDF stream for editing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | A PDF stream to be edited. |

### extractLink() {#extractLink--}
```
public List<Annotation> extractLink()
```


Extracts the collection of Link instances contained in PDF document.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 List links = editor.extractLink();
 for (object obj : links)
 {
     Link link = (Link)obj;
     // work with Link instance
 }
```

**Returns:**
java.util.List<com.aspose.pdf.Annotation> - The collection of Link objects
### createWebLink(Rectangle rect, String url, int originalPage, Color clr, int[] actionName) {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-int---}
```
public void createWebLink(Rectangle rect, String url, int originalPage, Color clr, int[] actionName)
```


Creates a web link in PDF document.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createWebLink(new Rectangle(0, 0, 100, 100),
     "http://www.aspose.com", 1, Color.red,
     new int[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The rectangle for active click. |
| url | java.lang.String | The web link destination. |
| originalPage | int | The number of original page on which rectangle bound with web link will be created. |
| clr | java.awt.Color | The color of rectangle for active click. |
| actionName | int[] | The array of actions (members of PredefinedAction enum) corresponding to executing menu items in Acrobat viewer. |

### createWebLink(Rectangle rect, String url, int originalPage, Color clr) {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
```
public void createWebLink(Rectangle rect, String url, int originalPage, Color clr)
```


Creates a web link in PDF document.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createWebLink(new Rectangle(0, 0, 100, 100),
     "http://www.aspose.com", 1, Color.red });
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The rectangle for active click. |
| url | java.lang.String | The web link destination. |
| originalPage | int | The number of original page where rectangle bound with web link will be created. |
| clr | java.awt.Color | The color of rectangle for active click. |

### createWebLink(Rectangle rect, String url, int originalPage) {#createWebLink-java.awt.Rectangle-java.lang.String-int-}
```
public void createWebLink(Rectangle rect, String url, int originalPage)
```


Creates a web link in PDF document.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createWebLink(new Rectangle(0, 0, 100, 100), "http://www.aspose.com", 1 });
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The rectangle for active click. |
| url | java.lang.String | The web link destination. |
| originalPage | int | The number of original page where rectangle bound with web link will be created. |

### createLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, int[] actionName) {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-int---}
```
public void createLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, int[] actionName)
```


Creates a local link in PDF document.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createLocalLink(new Rectangle(0, 0, 100, 100),
     2, 1, Color.red,
     new int[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The rectangle for active click. |
| desPage | int | The destination page. |
| originalPage | int | The number of original page where rectangle bound with local link will be created. |
| clr | java.awt.Color | The color of rectangle for active click. |
| actionName | int[] | The array of actions (members of PredefinedAction enum) corresponding to executing menu items in Acrobat viewer. |

### createLocalLink(Rectangle rect, int desPage, int originalPage, Color clr) {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-}
```
public void createLocalLink(Rectangle rect, int desPage, int originalPage, Color clr)
```


Creates a local link in PDF document.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createLocalLink(new Rectangle(0, 0, 100, 100),
     2, 1, Color.red });
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The rectangle for active click. |
| desPage | int | The destination page. |
| originalPage | int | The number of original page where rectangle bound with local link will be created. |
| clr | java.awt.Color | The color of rectangle for active click. |

### createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage, Color clr, int[] actionName) {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-int---}
```
public void createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage, Color clr, int[] actionName)
```


Creates a link to another PDF document page.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createPdfDocumentLink(new Rectangle(0, 0, 100, 100),
     "another_example.pdf", 1, 1, Color.red,
     new int[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The rectangle for active click. |
| remotePdf | java.lang.String | The PDF document which page will be opened. |
| originalPage | int | The number of original page where rectangle bound with link will be created. |
| destinationPage | int | The destination page. |
| clr | java.awt.Color | The color of rectangle for active click. |
| actionName | int[] | The array of actions (members of PredefinedAction enum) corresponding to executing menu items in Acrobat viewer. |

### createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage, Color clr) {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
```
public void createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage, Color clr)
```


Creates a link to another PDF document page.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createPdfDocumentLink(new Rectangle(0, 0, 100, 100),
     "another_example.pdf", 1, 1, Color.red });
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The rectangle for active click. |
| remotePdf | java.lang.String | The PDF document which page will be opened. |
| originalPage | int | The number of original page where rectangle bound with link will be created. |
| destinationPage | int | The destination page. |
| clr | java.awt.Color | The color of rectangle for active click. |

### createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage) {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-}
```
public void createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage)
```


Creates a link to another PDF document page.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createPdfDocumentLink(new Rectangle(0, 0, 100, 100), "another_example.pdf", 1, 1 });
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The rectangle for active click. |
| remotePdf | java.lang.String | The PDF document which page will be opened. |
| originalPage | int | The number of original page where rectangle bound with link will be created. |
| destinationPage | int | The destination page. |

### createCustomActionLink(Rectangle rect, int originalPage, Color color, int[] actionName) {#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-int---}
```
public void createCustomActionLink(Rectangle rect, int originalPage, Color color, int[] actionName)
```


Creates a link to custom actions in PDF document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The rectangle for active click. |
| originalPage | int | The number of original page where rectangle bound with link will be created. |
| color | java.awt.Color | The color of rectangle for active click. |
| actionName | int[] | The array of actions (members of PredefinedAction enum) corresponding to executing menu items in Acrobat viewer. |

### createApplicationLink(Rectangle rect, String application, int page, Color clr, int[] actionName) {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-int---}
```
public void createApplicationLink(Rectangle rect, String application, int page, Color clr, int[] actionName)
```


Creates a link to launch an application in PDF document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The rectangle for active click. |
| application | java.lang.String | The path of application to be launched. |
| page | int | The number of original page where rectangle bound with link will be created. |
| clr | java.awt.Color | The color of rectangle for active click. |
| actionName | int[] | The array of actions (members of PredefinedAction enum) corresponding to executing menu items in Acrobat viewer. |

### createApplicationLink(Rectangle rect, String application, int page, Color clr) {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
```
public void createApplicationLink(Rectangle rect, String application, int page, Color clr)
```


Creates a link to launch an application in PDF document.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createApplicationLink(new Rectangle(0, 0, 100, 100),
     "explorer", 1, Color.red });
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The rectangle for active click. |
| application | java.lang.String | The path of application to be launched. |
| page | int | The number of original page where rectangle bound with link will be created. |
| clr | java.awt.Color | The color of rectangle for active click. |

### createApplicationLink(Rectangle rect, String application, int page) {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-}
```
public void createApplicationLink(Rectangle rect, String application, int page)
```


Creates a link to launch an application in PDF document.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createApplicationLink(new Rectangle(0, 0, 100, 100), "explorer", 1 });
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The rectangle for active click. |
| application | java.lang.String | The path of application to be launched. |
| page | int | The number of original page where rectangle bound with link will be created. |

### createJavaScriptLink(String code, Rectangle rect, int originalPage, Color color) {#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-}
```
public void createJavaScriptLink(String code, Rectangle rect, int originalPage, Color color)
```


Creates a link to JavaScript in PDF document.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createJavaScriptLink("app.alert('welcome to aspose!');",
     new Rectangle(0, 0, 100, 100), 1, Color.red });
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| code | java.lang.String | The JavaScript code. |
| rect | java.awt.Rectangle | The rectangle for active click. |
| originalPage | int | The number of original page where rectangle bound with link will be created. |
| color | java.awt.Color | The color of rectangle for active click. |

### createText(Rectangle rect, String title, String contents, boolean open, String icon, int page) {#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-}
```
public void createText(Rectangle rect, String title, String contents, boolean open, String icon, int page)
```


Creates text annotation in PDF document

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createText(new Rectangle(0, 0, 100, 100),
     "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| title | java.lang.String | The title of the annotation. |
| contents | java.lang.String | The contents of the annotation. |
| open | boolean | A flag specifying whether the annotation should initially be displayed open. |
| icon | java.lang.String | The name of an icon will be used in displaying the annotation. This value can be: "Comment", "Key", "Note", "Help", "NewParagraph", "Paragraph", "Insert" |
| page | int | The number of original page where the text annotation will be created. |

### createFreeText(Rectangle rect, String contents, int page) {#createFreeText-java.awt.Rectangle-java.lang.String-int-}
```
public void createFreeText(Rectangle rect, String contents, int page)
```


Creates free text annotation in PDF document

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createFreeText(new Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| contents | java.lang.String | The contents of the annotation. |
| page | int | The number of original page where the text annotation will be created. |

### createMarkup(Rectangle rect, String contents, int type, int page, Color clr) {#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
```
public void createMarkup(Rectangle rect, String contents, int type, int page, Color clr)
```


Creates markup annotation it PDF document.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createMarkup(new Rectangle(0, 0, 100, 100),
     "Welcome to Aspose", 0, 1, Color.red);
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The rectangle defining the location of the annotation on the page. |
| contents | java.lang.String | The contents of the annotation. |
| type | int | The type of markup annotation. Can be 0 (Highlight), 1 (Underline), 2 (StrikeOut), 3 (Squiggly). |
| page | int | The number of original page where the annotation will be created. |
| clr | java.awt.Color | The color of markup. |

### createPopup(Rectangle rect, String contents, boolean open, int page) {#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-}
```
public void createPopup(Rectangle rect, String contents, boolean open, int page)
```


Creates popup annotation in PDF document.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createPopup(new Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| contents | java.lang.String | The contents of the annotation. |
| open | boolean | A flag specifying whether the pop-up annotation should initially be displayed open. |
| page | int | The number of original page where the annotation will be created. |

### createFileAttachment(Rectangle rect, String contents, String filePath, int page, String name) {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}
```
public void createFileAttachment(Rectangle rect, String contents, String filePath, int page, String name)
```


Creates file attachment annotation.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createFileAttachment(new Rectangle(0, 0, 100, 100),
     "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| contents | java.lang.String | The contents of the annotation. |
| filePath | java.lang.String | The path of the file will be attached. |
| page | int | The number of original page where the annotation will be created. |
| name | java.lang.String | The name of an icon will be used in displaying the annotation. This value can be: "Graph", "PushPin", "Paperclip", "Tag". |

### createFileAttachment(Rectangle rect, String contents, InputStream attachmentStream, String attachmentName, int page, String name) {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-}
```
public void createFileAttachment(Rectangle rect, String contents, InputStream attachmentStream, String attachmentName, int page, String name)
```


Creates file attachment annotation.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 java.io.InputStream attStream = new java.io.FileInputStream("attachment_file.pdf");

     editor.createFileAttachment(new Rectangle(0, 0, 100, 100),
         "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph");
     editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| contents | java.lang.String | The contents of the annotation. |
| attachmentStream | java.io.InputStream | The attachment file stream. |
| attachmentName | java.lang.String | The attachment name. |
| page | int | The number of original page where the annotation will be created. |
| name | java.lang.String | The name of an icon will be used in displaying the annotation. This value can be: "Graph", "PushPin", "Paperclip", "Tag". |

### addDocumentAttachment(String fileAttachmentPath, String description) {#addDocumentAttachment-java.lang.String-java.lang.String-}
```
public void addDocumentAttachment(String fileAttachmentPath, String description)
```


Adds document attachment with no annotation.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file");
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileAttachmentPath | java.lang.String | The path of the file will be attached. |
| description | java.lang.String | The description information. |

### addDocumentAttachment(InputStream fileAttachmentStream, String fileAttachmentName, String description) {#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-}
```
public void addDocumentAttachment(InputStream fileAttachmentStream, String fileAttachmentName, String description)
```


Adds document attachment with no annotation.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 InputStream attStream = new FileInputStream("attachment_file.pdf")
     editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file");
     editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileAttachmentStream | java.io.InputStream | The stream of the file will be attached. |
| fileAttachmentName | java.lang.String | The attachment name. |
| description | java.lang.String | The description information. |

### deleteAttachments() {#deleteAttachments--}
```
public void deleteAttachments()
```


Deletes all attachments in PDF document.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.deleteAttachments();
 editor.save("example_out.pdf");
```

### createLine(Rectangle rect, String contents, float x1, float y1, float x2, float y2, int page, int border, Color clr, String borderStyle, int[] dashArray, String[] LEArray) {#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int---java.lang.String---}
```
public void createLine(Rectangle rect, String contents, float x1, float y1, float x2, float y2, int page, int border, Color clr, String borderStyle, int[] dashArray, String[] LEArray)
```


Creates line annotation.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createLine(new Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
     1, 1, Color.red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| contents | java.lang.String | The contents of the annotation. |
| x1 | float | The starting horizontal coordinate of the line. |
| y1 | float | The starting vertical coordinate of the line. |
| x2 | float | The ending horizontal coordinate of the line. |
| y2 | float | The ending vertical coordinate of the line. |
| page | int | The number of original page where the annotation will be created. |
| border | int | The border width in points. If this value is 0 no border is drawn. Default value is 1. |
| clr | java.awt.Color | The color of line. |
| borderStyle | java.lang.String | The border style specifying the width and dash pattern to be used in drawing the line. This value can be: "S" (Solid), "D" (Dashed), "B" (Beveled), "I" (Inset), "U" (Underline). |
| dashArray | int[] | A dash array defining a pattern of dashes and gaps to be used in drawing a dashed border. If it is used, borderSyle must be accordingly set to "D". |
| LEArray | java.lang.String[] | An array of two values respectively specifying the beginning and ending style of the drawing line. The values can be: "Square", "Circle", "Diamond", "OpenArrow", "ClosedArrow", "None", "Butt", "ROpenArrow", "RClosedArrow", "Slash". |

### createSquareCircle(Rectangle rect, String contents, Color clr, boolean square, int page, int borderWidth) {#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-}
```
public void createSquareCircle(Rectangle rect, String contents, Color clr, boolean square, int page, int borderWidth)
```


Creates square-circle annotation.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
  editor.bindPdf("example.pdf");
 	editor.createSquareCircle(new Rectangle(0, 0, 100, 100),
 	    "Welcome to Aspose", Color.red, false, 1, 5);
  editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| contents | java.lang.String | The contents of the annotation. |
| clr | java.awt.Color | The color of square or circle. |
| square | boolean | True (square), false (sircle). |
| page | int | The number of original page where the annotation will be created. |
| borderWidth | int | The border width of square or circle. |

### drawCurve(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents) {#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
```
public void drawCurve(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents)
```


Creates curve annotation.

```
PdfContentEditor editor = new PdfContentEditor();
 newApiEditor.bindPdf("example.pdf");
 LineInfo lineInfo = new LineInfo();
 lineInfo.setVerticeCoordinate ( new float[] { 0, 0, 100, 100 });  //x1, y1, x2, y2, .. xn, yn
 lineInfo.setVisibility ( true);
 editor.drawCurve(lineInfo, 1, new Rectangle(0, 0, 0, 0), "Welcome to Aspose");
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lineInfo | [LineInfo](../../com.aspose.pdf.facades/lineinfo) | The instance of LineInfo class. |
| page | int | The number of original page where the annotation will be created. |
| annotRect | java.awt.Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| annotContents | java.lang.String | The contents of the annotation. |

### createPolygon(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents) {#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
```
public void createPolygon(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents)
```


Creates polygon annotation.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 LineInfo lineInfo = new LineInfo();
 lineInfo.setVerticeCoordinate ( new float[] { 0, 0, 100, 100, 100, 50 });
 lineInfo.setVisibility ( true);
 editor.createPolygon(lineInfo, 1 , new Rectangle(0, 0, 0, 0), "Welcome to Aspose");
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lineInfo | [LineInfo](../../com.aspose.pdf.facades/lineinfo) | The instance of LineInfo class. |
| page | int | The number of original page where the annotation will be created. |
| annotRect | java.awt.Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| annotContents | java.lang.String | The contents of the annotation. |

### createPolyLine(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents) {#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
```
public void createPolyLine(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents)
```


Creates polyline annotation.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 LineInfo lineInfo = new LineInfo();
 lineInfo.setVerticeCoordinate ( new float[] { 0, 0, 100, 100, 100, 50 });
 lineInfo.setVisibility ( true);
 editor.createPolyLine(lineInfo, 1 , new Rectangle(0, 0, 0, 0), "Welcome to Aspose");
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lineInfo | [LineInfo](../../com.aspose.pdf.facades/lineinfo) | The instance of LineInfo class. |
| page | int | The number of original page where the annotation will be created. |
| annotRect | java.awt.Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| annotContents | java.lang.String | The contents of the annotation. |

### createCaret(int page, Rectangle annotRect, Rectangle caretRect, String symbol, String annotContents, Color color) {#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
```
public void createCaret(int page, Rectangle annotRect, Rectangle caretRect, String symbol, String annotContents, Color color)
```


Creates caret annotation.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
  editor.bindPdf("example.pdf");
 	editor.createCaret(1,
 	    new Rectangle(50, 50, 100, 100),
 	    new Rectangle(60, 60, 70, 70),
 	    "None", "Welcome to Aspose", Color.red);
  editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int | The number of original page where the annotation will be created. |
| annotRect | java.awt.Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| caretRect | java.awt.Rectangle | The actual boundaries of the underlying caret. |
| symbol | java.lang.String | A symbol will be associated with the caret. Value can be: "P" (Paragraph), "None". |
| annotContents | java.lang.String | The contents of the annotation. |
| color | java.awt.Color | The color of the annotation. |

### createRubberStamp(int page, Rectangle annotRect, String icon, String annotContents, Color color) {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
```
public void createRubberStamp(int page, Rectangle annotRect, String icon, String annotContents, Color color)
```


Creates a rubber stamp annotation.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
  editor.bindPdf("example.pdf");
 	editor.createRubberStamp(1, Rectangle(0, 0, 100, 100),
 	    "Welcome to Aspose", Color.red);
  editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int | The number of original page where the annotation will be created. |
| annotRect | java.awt.Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| icon | java.lang.String | String value |
| annotContents | java.lang.String | The contents of the annotation. |
| color | java.awt.Color | The color of the annotation. |

### createRubberStamp(int page, Rectangle annotRect, String annotContents, Color color, String appearanceFile) {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-}
```
public void createRubberStamp(int page, Rectangle annotRect, String annotContents, Color color, String appearanceFile)
```


Creates a rubber stamp annotation.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
  editor.bindPdf("example.pdf");
 	editor.createRubberStamp(1, Rectangle(0, 0, 100, 100),
 	    "Welcome to Aspose", Color.red, "appearance_file.pdf");
  editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int | The number of original page where the annotation will be created. |
| annotRect | java.awt.Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| annotContents | java.lang.String | The contents of the annotation. |
| color | java.awt.Color | The color of the annotation. |
| appearanceFile | java.lang.String | The path of appearance file. |

### createRubberStamp(int page, Rectangle annotRect, String annotContents, Color color, InputStream appearanceStream) {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-}
```
public void createRubberStamp(int page, Rectangle annotRect, String annotContents, Color color, InputStream appearanceStream)
```


Creates a rubber stamp annotation.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
  editor.bindPdf("example.pdf");
  InputStream appStream = new FileInputStream("appearance_file.pdf");
 	    editor.createRubberStamp(1, Rectangle(0, 0, 100, 100),
 	        "Welcome to Aspose", Color.red, appStream);
      editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int | The number of original page where the annotation will be created. |
| annotRect | java.awt.Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| annotContents | java.lang.String | The contents of the annotation. |
| color | java.awt.Color | The color of the annotation. |
| appearanceStream | java.io.InputStream | The stream of appearance file. |

### createBookmarksAction(String title, Color color, boolean boldFlag, boolean italicFlag, String file, String actionType, String destination) {#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-}
```
public void createBookmarksAction(String title, Color color, boolean boldFlag, boolean italicFlag, String file, String actionType, String destination)
```


Creates a bookmark with the specified action.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createBookmarksAction("bookmark title",
     Color.red, true, true, null, "GoTo", 1(page number));
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| title | java.lang.String | The title of the bookmark. |
| color | java.awt.Color | The color of the bookmark's title. |
| boldFlag | boolean | The flag of bold attribution. |
| italicFlag | boolean | The flag of italic attribution. |
| file | java.lang.String | Another file or application required when the action type is "GoToR" or "Launch". |
| actionType | java.lang.String | The action type. The value can be: "GoToR", "Launch", "GoTo", "URI". |
| destination | java.lang.String | The local destination or remote destination or URL. |

### addDocumentAdditionalAction(String eventType, String code) {#addDocumentAdditionalAction-java.lang.String-java.lang.String-}
```
public void addDocumentAdditionalAction(String eventType, String code)
```


Adds additional action for document event.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| eventType | java.lang.String | The document event types. |
| code | java.lang.String | The code of JavaScript. |

### removeDocumentOpenAction() {#removeDocumentOpenAction--}
```
public void removeDocumentOpenAction()
```


Removes open action from the document. This operation is useful when concatenating multiple documents that use explicit 'GoTo' action on startup.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.removeDocumentOpenAction();
 editor.save("example_out.pdf");
```

### changeViewerPreference(int viewerAttribution) {#changeViewerPreference-int-}
```
public void changeViewerPreference(int viewerAttribution)
```


Changes the view preference.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.changeViewerPreference(ViewerPreference.HideMenubar);
 editor.changeViewerPreference(ViewerPreference.PageModeUseNone);
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| viewerAttribution | int | The view attribution defined in the ViewerPreference class. |

### getViewerPreference() {#getViewerPreference--}
```
public int getViewerPreference()
```


Returns the view preference.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 int prefValue = editor.GetViewerPreference();
 if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
 { // ... }
```

**Returns:**
int - Returns set of ViewerPrefernece flags
### replaceImage(int pageNumber, int index, String imageFile) {#replaceImage-int-int-java.lang.String-}
```
public void replaceImage(int pageNumber, int index, String imageFile)
```


Replaces the specified image on the specified page of PDF document with another image.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.replaceImage(1, 1, "image.jpg");
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of page on which the image is replaced. |
| index | int | The index of the image object must be replaced. |
| imageFile | java.lang.String | The image file will be used for replacing. |

### deleteImage(int pageNumber, int[] index) {#deleteImage-int-int---}
```
public void deleteImage(int pageNumber, int[] index)
```


Deletes the specified images on the specified page.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.deleteImage(1, new int[] {1, 2});
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of page on which images must be deleted. |
| index | int[] | An array repsents images' indexes. |

### deleteImage() {#deleteImage--}
```
public void deleteImage()
```


Deletes all images from PDF document.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.deleteImage();
 editor.save("example_out.pdf");
```

### replaceText(String srcString, int thePage, String destString, TextState textState) {#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-}
```
public boolean replaceText(String srcString, int thePage, String destString, TextState textState)
```


Replaces text in the PDF file on the specified page.  TextState  object (font family, color) can be specified to replaced text.

--------------------

```
The example demonstrates how to replace text on the first page of the PDF document and set ```
TextState
```
 text properties for the new text.


 // open document
 Document doc = new Document(inFile);
 com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New");
 font.isEmbedded ( true);
 // create PdfContentEditor object to edit text
 PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf(doc);
 // create textState object
 com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState();
 textState.setFont ( font);
 textState.setFontSize ( 17);
 textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic);
 textState.setForegroundColor ( com.aspose.pdf.Color.getRed());
 // change text with specified font
 editor.replaceText("hello world", 1, "hi world", textState);
 // save document
 doc.save(outFile);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcString | java.lang.String | The string to be replaced. |
| thePage | int | Page number (0 means "all pages"). |
| destString | java.lang.String | The replaced string. |
| textState | [TextState](../../com.aspose.pdf/textstate) | Text state (Text Color, Font etc). |

**Returns:**
boolean - Returns true if replacement was made.
### replaceText(String srcString, String destString) {#replaceText-java.lang.String-java.lang.String-}
```
public boolean replaceText(String srcString, String destString)
```


Replaces text in the PDF file.

--------------------

```
The example demonstrates how to replace text in PDF document.


 // open document
 Document doc = new Document(inFile);
 // create PdfContentEditor object to edit text
 PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf(doc);
 // change text
 editor.replaceText("hello world", "hi world");
 // save document
 doc.save(outFile);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcString | java.lang.String | The string to be replaced. |
| destString | java.lang.String | Replacing string. |

**Returns:**
boolean - Returns true if replacement was made.
### replaceText(String srcString, int thePage, String destString) {#replaceText-java.lang.String-int-java.lang.String-}
```
public boolean replaceText(String srcString, int thePage, String destString)
```


Replaces text in the PDF file on the specified page.

--------------------

```
The example demonstrates how to replace text in PDF document on the specified page.


 // open document
 Document doc = new Document(inFile);
 // create PdfContentEditor object to edit text
 PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf(doc);
 // change text
 editor.replaceText("hello world", 1, "hi world");
 // save document
 doc.save(outFile);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcString | java.lang.String | The sting to be replaced. |
| thePage | int | Page number (0 for all pages) |
| destString | java.lang.String | Replacing string. |

**Returns:**
boolean - Returns true if replacement was made.
### replaceText(String srcString, String destString, TextState textState) {#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-}
```
public boolean replaceText(String srcString, String destString, TextState textState)
```


Replaces text in the PDF file using specified  TextState  object.

--------------------

```
The example demonstrates how to replace text and set ```
TextState
``` text properties for the new text.


 Document doc = new Document(inFile);
 // Create font and mark it to be embedded
 com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New");
 font.isEmbedded ( true);
 // create PdfContentEditor object to edit text
 PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf(doc);
 // create textState object
 com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState();
 textState.setFont ( font);
 textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic);
 // change text with specified font
 editor.replaceText("hello world", "hi world", textState);
 // save document
 doc.save(outFile);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcString | java.lang.String | String to be replaced |
| destString | java.lang.String | Replacing string |
| textState | [TextState](../../com.aspose.pdf/textstate) | Text state (Text Color, Font etc) |

**Returns:**
boolean - Returns true if replacement was made.
### createMovie(Rectangle rect, String filePath, int page) {#createMovie-java.awt.Rectangle-java.lang.String-int-}
```
public void createMovie(Rectangle rect, String filePath, int page)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle |  |
| filePath | java.lang.String |  |
| page | int |  |

### createSound(Rectangle rect, String filePath, String name, int page, String rate) {#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}
```
public void createSound(Rectangle rect, String filePath, String name, int page, String rate)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle |  |
| filePath | java.lang.String |  |
| name | java.lang.String |  |
| page | int |  |
| rate | java.lang.String |  |

### deleteStamp(int pageNumber, int[] index) {#deleteStamp-int-int---}
```
public void deleteStamp(int pageNumber, int[] index)
```


Deletes multiple stamps on the specified page by stamp indexes.

--------------------

```
PdfContentEditor contentEditor = new PdfContentEditor();
 contentEditor.bindPdf("file.pdf");
 contentEditor.deleteStamp(1, new int[] { 2, 3, 5} );
 contentEditor.save("outfile.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Page number where stamp will be deleted. |
| index | int[] | Stamp indexes. |

### deleteStampByIds(int[] stampIds) {#deleteStampByIds-int---}
```
public void deleteStampByIds(int[] stampIds)
```


Deletes stamps with specified IDs from all pages of the document.

--------------------

```
PdfContentEditor contentEditor = new PdfContentEditor();
 contentEditor.bindPdf("file.pdf");
 contentEditor.deleteStampByIds(new int[] { 102, 103 } );
 contentEditor.save("outfile.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stampIds | int[] | Array of stamp IDs. |

### deleteStampByIds(int pageNumber, int[] stampIds) {#deleteStampByIds-int-int---}
```
public void deleteStampByIds(int pageNumber, int[] stampIds)
```


Deletes stamps on the specified page by multiple stamp IDs.

--------------------

```
PdfContentEditor contentEditor = new PdfContentEditor();
 contentEditor.bindPdf("file.pdf");
 contentEditor.deleteStampByIds(1, new int[] { 100, 101 } );
 contentEditor.save("outfile.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Page number where stamps will be deleted. |
| stampIds | int[] | Array of stamp IDs. |

### deleteStampById(int pageNumber, int stampId) {#deleteStampById-int-int-}
```
public void deleteStampById(int pageNumber, int stampId)
```


Deletes stamp on the specified page by stamp ID.

--------------------

```
PdfContentEditor contentEditor = new PdfContentEditor();
 contentEditor.bindPdf("file.pdf");
 contentEditor.deleteStampById(1, 100);
 contentEditor.save("outfile.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Page number where stamp will be deleted. |
| stampId | int | Identifier of stamp which should be deleted. |

### hideStampById(int pageNumber, int stampId) {#hideStampById-int-int-}
```
public void hideStampById(int pageNumber, int stampId)
```


Hides the stamp. After hiding, stamp visibility may be restored with ShowStampById method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Number of the page. |
| stampId | int | Identifier of stamp which should be hidden. |

### showStampById(int pageNumber, int stampId) {#showStampById-int-int-}
```
public void showStampById(int pageNumber, int stampId)
```


Shows stamp which was hidden by HiddenStampById.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Number of the page. |
| stampId | int | Identifier of stamp which should be shown. |

### moveStampById(int pageNumber, int stampId, double x, double y) {#moveStampById-int-int-double-double-}
```
public void moveStampById(int pageNumber, int stampId, double x, double y)
```


Changes position of the stamp on page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Numer of page. |
| stampId | int | Identifier of stamp which should be moved. |
| x | double | New stamp horizontal pozition on the page. |
| y | double | New stamp vertical position on the page. |

### moveStamp(int pageNumber, int stampIndex, double x, double y) {#moveStamp-int-int-double-double-}
```
public void moveStamp(int pageNumber, int stampIndex, double x, double y)
```


Changes position of the stamp on page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Number of page. |
| stampIndex | int | Index of stamp on the page. |
| x | double | New stamp horizontal position. |
| y | double | New stamp vertical position. |

### deleteStampById(int stampId) {#deleteStampById-int-}
```
public void deleteStampById(int stampId)
```


Delete stamp by ID from all pages of the document.

--------------------

```
PdfContentEditor contentEditor = new PdfContentEditor();
 contentEditor.bindPdf("file.pdf");
 contentEditor.deleteStampById(100);
 contentEditor.save("outfile.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stampId | int | Identifier of stamp which should be deleted. |

### createLocalLink(Rectangle rect, int desPage, int originalPage) {#createLocalLink-java.awt.Rectangle-int-int-}
```
public void createLocalLink(Rectangle rect, int desPage, int originalPage)
```


Creates a local link in PDF document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The rectangle for active click. |
| desPage | int | The destination page. |
| originalPage | int | The number of original page where rectangle bound with local link will be created. |

### replaceText(String srcString, String destString, int fontSize) {#replaceText-java.lang.String-java.lang.String-int-}
```
public boolean replaceText(String srcString, String destString, int fontSize)
```


Replaces text in the PDF file and sets font size.

--------------------

```
The example demonstrates how to replace text and set font size for the new text.


 // open document
 Document doc = new Document(inFile);
 // Create font and mark it to be embedded
 com.aspose.pdf.Font font = FontRepository.FindFont("Courier New");
 font.isEmbedded ( true);
 // create PdfContentEditor object to edit text
 PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf(doc);
 // change text with specified font
 editor.replaceText("hello world", "hi world", 14);
 // save document
 doc.save(outFile);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcString | java.lang.String | String to be replaced. |
| destString | java.lang.String | Replacing string. |
| fontSize | int | Font size. |

**Returns:**
boolean - Returns true if replacement was made.
### getStamps(int pageNumber) {#getStamps-int-}
```
public StampInfo[] getStamps(int pageNumber)
```


Returns array of stamps on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Page number where stamps will be searched. |

**Returns:**
com.aspose.pdf.facades.StampInfo[] - Array of stamps.
### close() {#close--}
```
public void close()
```


Closes opened document.

