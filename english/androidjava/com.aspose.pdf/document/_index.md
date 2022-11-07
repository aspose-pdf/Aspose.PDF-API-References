---
title: Document
second_title: Aspose.PDF for Java API Reference
description: Class representing PDF document
type: docs
weight: 78
url: /java/com.aspose.pdf/document/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ADocument

**All Implemented Interfaces:**
[com.aspose.pdf.IDocument](../../com.aspose.pdf/idocument)
```
public final class Document extends ADocument implements IDocument
```

Class representing PDF document
## Constructors

| Constructor | Description |
| --- | --- |
| [Document()](#Document--) | Initializes empty document. |
| [Document(InputStream input)](#Document-java.io.InputStream-) | Initialize new Document instance from the  input  stream. |
| [Document(InputStream input, String password)](#Document-java.io.InputStream-java.lang.String-) |  |
| [Document(System.IO.Stream input)](#Document-com.aspose.ms.System.IO.Stream-) | Initialize new Document instance from the  input  stream. |
| [Document(InputStream input, String password, boolean isManagedStream)](#Document-java.io.InputStream-java.lang.String-boolean-) | Initialize new Document instance from the  input  stream. |
| [Document(InputStream input, boolean isManagedStream)](#Document-java.io.InputStream-boolean-) | Initialize new Document instance from the  input  stream. |
| [Document(InputStream input, LoadOptions options)](#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Opens an existing document from a stream providing necessary converting to get pdf document. |
| [Document(String filename, LoadOptions options)](#Document-java.lang.String-com.aspose.pdf.LoadOptions-) | Opens an existing document from a file providing necessary converting to get pdf document. |
| [Document(System.IO.Stream input, String password)](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-) |  |
| [Document(String filename)](#Document-java.lang.String-) | Just init Document using  filename . |
| [Document(String filename, String password)](#Document-java.lang.String-java.lang.String-) | Initializes new instance of the  Document  class for working with encrypted document. |
| [Document(String filename, String password, boolean isManagedStream)](#Document-java.lang.String-java.lang.String-boolean-) | Initializes new instance of the  Document  class for working with encrypted document. |
## Methods

| Method | Description |
| --- | --- |
| [getLocalFontPaths()](#getLocalFontPaths--) | List for standard font directories in different OS |
| [addLocalFontPath(String path)](#addLocalFontPath-java.lang.String-) | Add one more path to fonts |
| [setLocalFontPaths(List newFontPathsList)](#setLocalFontPaths-java.util.List-) | Sets user list with font paths |
| [restoreLocalFontPath()](#restoreLocalFontPath--) | Restores list for standard font directories by default. |
| [getPageInfo()](#getPageInfo--) | Gets the page info. |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | Sets the page info. |
| [getFontReplaceBehavior()](#getFontReplaceBehavior--) | Gets the TextEditOptions.FontReplace |
| [setFontReplaceBehavior(int value)](#setFontReplaceBehavior-int-) | Sets the TextEditOptions.FontReplace |
| [getDestinations()](#getDestinations--) | Gets the collection of destinations. |
| [getCollection()](#getCollection--) | Gets collection of document. |
| [setCollection(Collection value)](#setCollection-com.aspose.pdf.Collection-) | Sets collection of document. |
| [getEngineDoc()](#getEngineDoc--) | Instance of IPdfDocument used to access to internal document structure. |
| [getVersion()](#getVersion--) | Gets a version of Pdf from Pdf file header. |
| [getOpenAction()](#getOpenAction--) | Gets action performed at document opening. |
| [setOpenAction(IAppointment value)](#setOpenAction-com.aspose.pdf.IAppointment-) | Sets action performed at document opening. |
| [getHideToolBar()](#getHideToolBar--) | Gets flag specifying whether toolbar should be hidden when document is active. |
| [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | Set flag specifying whether toolbar should be hidden when document is active. |
| [getHideMenubar()](#getHideMenubar--) | Gets flag specifying whether menu bar should be hidden when document is active. |
| [setHideMenubar(boolean value)](#setHideMenubar-boolean-) | Sets flag specifying whether menu bar should be hidden when document is active. |
| [getHideWindowUI()](#getHideWindowUI--) | Gets or sets flag specifying whether user interface elements should be hidden when document is active. |
| [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | Sets flag specifying whether user interface elements should be hidden when document is active. |
| [getFitWindow()](#getFitWindow--) | Gets flag specifying whether document window must be resized to fit the first displayed page. |
| [setFitWindow(boolean value)](#setFitWindow-boolean-) | Sets flag specifying whether document window must be resized to fit the first displayed page. |
| [getCenterWindow()](#getCenterWindow--) | Gets flag specifying whether position of the document's window will be centerd on the screen. |
| [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | Sets flag specifying whether position of the document's window will be centerd on the screen. |
| [getDisplayDocTitle()](#getDisplayDocTitle--) | Gets flag specifying whether document's window title bar should display document title. |
| [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | Sets flag specifying whether document's window title bar should display document title. |
| [getPages()](#getPages--) | Gets collection of document pages. |
| [getOutlines()](#getOutlines--) | Gets document outlines. |
| [getActions()](#getActions--) | Gets document actions. |
| [getForm()](#getForm--) | Gets Acro Form of the document. |
| [getEmbeddedFiles()](#getEmbeddedFiles--) | Gets collection of files embedded to document. |
| [getDirection()](#getDirection--) | Gets reading order of text: L2R (left to right) or R2L (right to left). |
| [setDirection(int value)](#setDirection-int-) | Sets reading order of text: L2R (left to right) or R2L (right to left). |
| [getPageMode()](#getPageMode--) | Gets page mode, specifying how document should be displayed when opened. |
| [setPageMode(int pageMode)](#setPageMode-int-) | Sets page mode, specifying how document should be displayed when opened. |
| [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | Gets page mode, specifying how to display the document on exiting full-screen mode. |
| [setNonFullScreenPageMode(int value)](#setNonFullScreenPageMode-int-) | Sets page mode, specifying how to display the document on exiting full-screen mode. |
| [getPageLayout()](#getPageLayout--) | Gets page layout which shall be used when the document is opened. |
| [setPageLayout(int value)](#setPageLayout-int-) | Sets page layout which shall be used when the document is opened. |
| [getFileName()](#getFileName--) | Name of the PDF file that caused this document |
| [getInfo()](#getInfo--) | Gets document info. |
| [getMetadata()](#getMetadata--) | Document metadata. |
| [getLogicalStructure()](#getLogicalStructure--) | Gets logical structure of the document. |
| [processParagraphs()](#processParagraphs--) | Stores document into stream. |
| [saveInternal(System.IO.Stream output)](#saveInternal-com.aspose.ms.System.IO.Stream-) | Stores document into stream. |
| [save(OutputStream output)](#save-java.io.OutputStream-) | Stores document into stream. |
| [save(String outputFileName)](#save-java.lang.String-) | Saves document into the specified file. |
| [exportAnnotationsToXfdf(String fileName)](#exportAnnotationsToXfdf-java.lang.String-) | Exports all document annotations to XFDF file |
| [sendTo(DocumentDevice device, OutputStream output)](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Sends the whole document to the document device for processing. |
| [sendTo(DocumentDevice device, int fromPage, int toPage, OutputStream output)](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Sends the certain pages of the document to the document device for processing. |
| [sendTo(DocumentDevice device, String outputFileName)](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Sends the whole document to the document device for processing. |
| [sendTo(DocumentDevice device, int fromPage, int toPage, String outputFileName)](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Sends the whole document to the document device for processing. |
| [removeMetadata()](#removeMetadata--) | Removes metadata from the document. |
| [importAnnotationsFromXfdf(String fileName)](#importAnnotationsFromXfdf-java.lang.String-) | Imports annotations from XFDF file to document. |
| [validate(String outputLogFileName, int format)](#validate-java.lang.String-int-) | Validate document into the specified file. |
| [convert(String outputLogFileName, int format, int action)](#convert-java.lang.String-int-int-) | Convert document and save errors into the specified file. |
| [convert(Document.CallBackGetHocr callback)](#convert-com.aspose.pdf.Document.CallBackGetHocr-) | Convert document and save errors into the specified file. |
| [convertInternal(System.IO.Stream outputLogStream, int format, int action)](#convertInternal-com.aspose.ms.System.IO.Stream-int-int-) | Convert document and save errors into the specified stream. |
| [convert(OutputStream outputLogStream, int format, int action)](#convert-java.io.OutputStream-int-int-) | Convert document and save errors into the specified stream. |
| [convert(System.Xml.XmlTextWriter xml, int format, boolean onlyValidation, int action)](#convert-com.aspose.ms.System.Xml.XmlTextWriter-int-boolean-int-) | Convert the PDF Document and log results. |
| [flatten()](#flatten--) | Removes all fields from the document and place their values instead. |
| [getCryptoAlgorithm()](#getCryptoAlgorithm--) | Gets security settings if document is encrypted. |
| [encrypt(String userPassword, String ownerPassword, DocumentPrivilege privileges, int cryptoAlgorithm, boolean usePdf20)](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-boolean-) | Encrypts the document. |
| [encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)](#encrypt-java.lang.String-java.lang.String-int-int-) | Encrypts the document. |
| [encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm, boolean usePdf20)](#encrypt-java.lang.String-java.lang.String-int-int-boolean-) | Encrypts the document. |
| [changePasswords(String ownerPassword, String newUserPassword, String newOwnerPassword)](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Changes document passwords. |
| [isLinearized()](#isLinearized--) | Gets a value indicating whether document is linearized. |
| [isLinearized(boolean value)](#isLinearized-boolean-) | Sets a value indicating whether document is linearized. |
| [decrypt()](#decrypt--) | Decrypts the document. |
| [getPermissions()](#getPermissions--) | Gets permissions of the document. |
| [isEncrypted()](#isEncrypted--) | Gets encrypted status of the document. |
| [optimize()](#optimize--) | Linearize document in order to - open the first page as quickly as possible; - display next page or follow by link to the next page as quickly as possible; - display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first); - permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed. |
| [save()](#save--) | Save document incrementally (i.e. using incremental update technque). |
| [save(String outputFileName, int format)](#save-java.lang.String-int-) | Saves the document with a new name along with a file format. |
| [save(OutputStream outputStream, int format)](#save-java.io.OutputStream-int-) | Saves the document with a new name along with a file format. |
| [save(String outputFileName, SaveOptions options)](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | Saves the document with a new name setting its save options. |
| [save(OutputStream outputStream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Saves the document to a stream with a save options. |
| [getId()](#getId--) | Gets the ID. |
| [getMetadataStream()](#getMetadataStream--) | Returns raw metadata stream |
| [suppressUpdate()](#suppressUpdate--) | Suppresses update contents data for all pages The contents is not updated until ResumeUpdate is called |
| [resumeUpdate()](#resumeUpdate--) | resumes document update |
| [dispose()](#dispose--) | Closes all resources used by this document. |
| [getBackground()](#getBackground--) | Gets the background color of the document. |
| [setBackground(Color value)](#setBackground-com.aspose.pdf.java.awt.Color-) | Sets the background color of the document. |
| [getDefaultCopier()](#getDefaultCopier--) | Returns copier used for coping pages to this document. |
| [optimizeResources()](#optimizeResources--) | Optimize resources in the document: 1. |
| [optimizeResources(Document.OptimizationOptions strategy)](#optimizeResources-com.aspose.pdf.Document.OptimizationOptions-) | Optimize resources in the document according to defined optimization strategy. |
| [getOptimizeSize()](#getOptimizeSize--) | Gets optimization flag. |
| [setOptimizeSize(boolean value)](#setOptimizeSize-boolean-) | Sets optimization flag. |
| [getIgnoreCorruptedObjects()](#getIgnoreCorruptedObjects--) | Gets or sets flag of ignoring errors in source files. |
| [setIgnoreCorruptedObjects(boolean value)](#setIgnoreCorruptedObjects-boolean-) | Gets or sets flag of ignoring errors in source files. |
| [getPageLabels()](#getPageLabels--) | Gets page labels in the document. |
| [freeMemory()](#freeMemory--) | Clears memory |
### Document() {#Document--}
```
public Document()
```


Initializes empty document.

### Document(InputStream input) {#Document-java.io.InputStream-}
```
public Document(InputStream input)
```


Initialize new Document instance from the  input  stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.io.InputStream | Stream with pdf document. |

### Document(InputStream input, String password) {#Document-java.io.InputStream-java.lang.String-}
```
public Document(InputStream input, String password)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.io.InputStream |  |
| password | java.lang.String |  |

### Document(System.IO.Stream input) {#Document-com.aspose.ms.System.IO.Stream-}
```
public Document(System.IO.Stream input)
```


Initialize new Document instance from the  input  stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | com.aspose.ms.System.IO.Stream | Stream with pdf document. |

### Document(InputStream input, String password, boolean isManagedStream) {#Document-java.io.InputStream-java.lang.String-boolean-}
```
public Document(InputStream input, String password, boolean isManagedStream)
```


Initialize new Document instance from the  input  stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.io.InputStream | Stream with pdf document. |
| password | java.lang.String | User or owner password. |
| isManagedStream | boolean | if set to  true  inner stream is closed before exit; otherwise, is not. |

### Document(InputStream input, boolean isManagedStream) {#Document-java.io.InputStream-boolean-}
```
public Document(InputStream input, boolean isManagedStream)
```


Initialize new Document instance from the  input  stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.io.InputStream | Stream with pdf document. |
| isManagedStream | boolean | if set to  true  inner stream is closed before exit; otherwise, is not. |

### Document(InputStream input, LoadOptions options) {#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-}
```
public Document(InputStream input, LoadOptions options)
```


Opens an existing document from a stream providing necessary converting to get pdf document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.io.InputStream | Input stream to convert into pdf document. |
| options | [LoadOptions](../../com.aspose.pdf/loadoptions) | Represents properties for converting  input  into pdf document. |

### Document(String filename, LoadOptions options) {#Document-java.lang.String-com.aspose.pdf.LoadOptions-}
```
public Document(String filename, LoadOptions options)
```


Opens an existing document from a file providing necessary converting to get pdf document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Input file to convert into pdf document. |
| options | [LoadOptions](../../com.aspose.pdf/loadoptions) | Represents properties for converting  filename  into pdf document. |

### Document(System.IO.Stream input, String password) {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-}
```
public Document(System.IO.Stream input, String password)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | com.aspose.ms.System.IO.Stream |  |
| password | java.lang.String |  |

### Document(String filename) {#Document-java.lang.String-}
```
public Document(String filename)
```


Just init Document using  filename . The same as  Document(Stream) .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | The name of the pdf document file. |

### Document(String filename, String password) {#Document-java.lang.String-java.lang.String-}
```
public Document(String filename, String password)
```


Initializes new instance of the  Document  class for working with encrypted document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Document file name. |
| password | java.lang.String | User or owner password. |

### Document(String filename, String password, boolean isManagedStream) {#Document-java.lang.String-java.lang.String-boolean-}
```
public Document(String filename, String password, boolean isManagedStream)
```


Initializes new instance of the  Document  class for working with encrypted document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Document file name. |
| password | java.lang.String | User or owner password. |
| isManagedStream | boolean | if set to  true  inner stream is closed before exit; otherwise, is not. |

### getLocalFontPaths() {#getLocalFontPaths--}
```
public static List<String> getLocalFontPaths()
```


List for standard font directories in different OS

**Returns:**
java.util.List<java.lang.String> - list of String
### addLocalFontPath(String path) {#addLocalFontPath-java.lang.String-}
```
public static void addLocalFontPath(String path)
```


Add one more path to fonts

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | String value |

### setLocalFontPaths(List newFontPathsList) {#setLocalFontPaths-java.util.List-}
```
public static void setLocalFontPaths(List newFontPathsList)
```


Sets user list with font paths

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newFontPathsList | java.util.List |  List  object |

### restoreLocalFontPath() {#restoreLocalFontPath--}
```
public static void restoreLocalFontPath()
```


Restores list for standard font directories by default.

### getPageInfo() {#getPageInfo--}
```
public PageInfo getPageInfo()
```


Gets the page info.(for generator only)

**Returns:**
[PageInfo](../../com.aspose.pdf/pageinfo) - The page info.
### setPageInfo(PageInfo value) {#setPageInfo-com.aspose.pdf.PageInfo-}
```
public void setPageInfo(PageInfo value)
```


Sets the page info.(for generator only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageInfo](../../com.aspose.pdf/pageinfo) |  |

### getFontReplaceBehavior() {#getFontReplaceBehavior--}
```
public int getFontReplaceBehavior()
```


Gets the TextEditOptions.FontReplace

**Returns:**
int
### setFontReplaceBehavior(int value) {#setFontReplaceBehavior-int-}
```
public void setFontReplaceBehavior(int value)
```


Sets the TextEditOptions.FontReplace

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDestinations() {#getDestinations--}
```
public DestinationCollection getDestinations()
```


Gets the collection of destinations.

**Returns:**
[DestinationCollection](../../com.aspose.pdf/destinationcollection)
### getCollection() {#getCollection--}
```
public Collection getCollection()
```


Gets collection of document.

**Returns:**
[Collection](../../com.aspose.pdf/collection)
### setCollection(Collection value) {#setCollection-com.aspose.pdf.Collection-}
```
public void setCollection(Collection value)
```


Sets collection of document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Collection](../../com.aspose.pdf/collection) |  |

### getEngineDoc() {#getEngineDoc--}
```
public IPdfDocument getEngineDoc()
```


Instance of IPdfDocument used to access to internal document structure.

**Returns:**
[IPdfDocument](../../com.aspose.pdf.engine/ipdfdocument)
### getVersion() {#getVersion--}
```
public String getVersion()
```


Gets a version of Pdf from Pdf file header.

**Returns:**
java.lang.String
### getOpenAction() {#getOpenAction--}
```
public IAppointment getOpenAction()
```


Gets action performed at document opening. Example demonstrates how to get CenterWindow flag: Document document = new Document("sample.pdf"); IAppointment value = document.getOpenAction();

**Returns:**
[IAppointment](../../com.aspose.pdf/iappointment)
### setOpenAction(IAppointment value) {#setOpenAction-com.aspose.pdf.IAppointment-}
```
public void setOpenAction(IAppointment value)
```


Sets action performed at document opening.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAppointment](../../com.aspose.pdf/iappointment) |  |

### getHideToolBar() {#getHideToolBar--}
```
public boolean getHideToolBar()
```


Gets flag specifying whether toolbar should be hidden when document is active. Example demonstrates how to get HideToolBar flag: Document document = new Document("sample.pdf"); booleanvalue = document.getHideToolBar();

**Returns:**
boolean
### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public void setHideToolBar(boolean value)
```


Set flag specifying whether toolbar should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideMenubar() {#getHideMenubar--}
```
public boolean getHideMenubar()
```


Gets flag specifying whether menu bar should be hidden when document is active. Example demonstrates how to get HideMenubar flag: Document document = new Document("sample.pdf"); booleanvalue = document.getHideMenubar();

**Returns:**
boolean
### setHideMenubar(boolean value) {#setHideMenubar-boolean-}
```
public void setHideMenubar(boolean value)
```


Sets flag specifying whether menu bar should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideWindowUI() {#getHideWindowUI--}
```
public boolean getHideWindowUI()
```


Gets or sets flag specifying whether user interface elements should be hidden when document is active. Example demonstrates how to get HideWindowUI flag: Document document = new Document("sample.pdf"); booleanvalue = document.getHideWindowUI();

**Returns:**
boolean
### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public void setHideWindowUI(boolean value)
```


Sets flag specifying whether user interface elements should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFitWindow() {#getFitWindow--}
```
public boolean getFitWindow()
```


Gets flag specifying whether document window must be resized to fit the first displayed page. Example demonstrates how to get FitWindow flag: Document document = new Document("sample.pdf"); booleanvalue = document.getFitWindow();

**Returns:**
boolean
### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public void setFitWindow(boolean value)
```


Sets flag specifying whether document window must be resized to fit the first displayed page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCenterWindow() {#getCenterWindow--}
```
public boolean getCenterWindow()
```


Gets flag specifying whether position of the document's window will be centerd on the screen. Example demonstrates how to get CenterWindow flag: Document document = new Document("sample.pdf"); booleanvalue = document.getCenterWindow();

**Returns:**
boolean
### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public void setCenterWindow(boolean value)
```


Sets flag specifying whether position of the document's window will be centerd on the screen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisplayDocTitle() {#getDisplayDocTitle--}
```
public boolean getDisplayDocTitle()
```


Gets flag specifying whether document's window title bar should display document title. Example demonstrates how to get DisplayDocTitle flag: Document document = new Document("sample.pdf"); booleanvalue = document.getDisplayDocTitle();

**Returns:**
boolean
### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public void setDisplayDocTitle(boolean value)
```


Sets flag specifying whether document's window title bar should display document title.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPages() {#getPages--}
```
public PageCollection getPages()
```


Gets collection of document pages. Note that pages are numbered from 1 in collection. Example below demonstrates how to operate with the document pages: How to obtain number of pages and how to obtain rectangle of starting page of the document. Document document = new Document("sample.pdf"); Pages pages = document.Pages; Console.WriteLine("Document contains " + pages.Count); Page page = Pages[1]; Rectangle rect = page.Rect;

**Returns:**
[PageCollection](../../com.aspose.pdf/pagecollection)
### getOutlines() {#getOutlines--}
```
public OutlineCollection getOutlines()
```


Gets document outlines.

**Returns:**
[OutlineCollection](../../com.aspose.pdf/outlinecollection)
### getActions() {#getActions--}
```
public DocumentActionCollection getActions()
```


Gets document actions. This property is instance of DocumentActions class which allows to get/set BeforClosing, BeforSaving, etc. actions. This example demonstrates how to obtain after open action of the document: Document document = new Document("PdfWithOpenAction.pdf"); DocumentActions actions = document.Actions; com.aspose.pdf.Action afterSavingAction = actions.AfterSaving;

**Returns:**
[DocumentActionCollection](../../com.aspose.pdf/documentactioncollection)
### getForm() {#getForm--}
```
public Form getForm()
```


Gets Acro Form of the document.

**Returns:**
[Form](../../com.aspose.pdf/form)
### getEmbeddedFiles() {#getEmbeddedFiles--}
```
public EmbeddedFileCollection getEmbeddedFiles()
```


Gets collection of files embedded to document.

**Returns:**
[EmbeddedFileCollection](../../com.aspose.pdf/embeddedfilecollection)
### getDirection() {#getDirection--}
```
public int getDirection()
```


Gets reading order of text: L2R (left to right) or R2L (right to left).

**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public void setDirection(int value)
```


Sets reading order of text: L2R (left to right) or R2L (right to left).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPageMode() {#getPageMode--}
```
public int getPageMode()
```


Gets page mode, specifying how document should be displayed when opened.

**Returns:**
int
### setPageMode(int pageMode) {#setPageMode-int-}
```
public void setPageMode(int pageMode)
```


Sets page mode, specifying how document should be displayed when opened.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageMode | int |  |

### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public int getNonFullScreenPageMode()
```


Gets page mode, specifying how to display the document on exiting full-screen mode.

**Returns:**
int
### setNonFullScreenPageMode(int value) {#setNonFullScreenPageMode-int-}
```
public void setNonFullScreenPageMode(int value)
```


Sets page mode, specifying how to display the document on exiting full-screen mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPageLayout() {#getPageLayout--}
```
public int getPageLayout()
```


Gets page layout which shall be used when the document is opened.

**Returns:**
int
### setPageLayout(int value) {#setPageLayout-int-}
```
public void setPageLayout(int value)
```


Sets page layout which shall be used when the document is opened.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFileName() {#getFileName--}
```
public String getFileName()
```


Name of the PDF file that caused this document

**Returns:**
java.lang.String
### getInfo() {#getInfo--}
```
public DocumentInfo getInfo()
```


Gets document info.

**Returns:**
[DocumentInfo](../../com.aspose.pdf/documentinfo)
### getMetadata() {#getMetadata--}
```
public Metadata getMetadata()
```


Document metadata. (A PDF document may include general information, such as the document\\ufffds title, author, and creation and modification dates. Such global information about the document (as opposed to its content or structure) is called metadata and is intended to assist in cataloguing and searching for documents in external databases.)

**Returns:**
[Metadata](../../com.aspose.pdf/metadata)
### getLogicalStructure() {#getLogicalStructure--}
```
public RootElement getLogicalStructure()
```


Gets logical structure of the document.

**Returns:**
[RootElement](../../com.aspose.pdf/rootelement)
### processParagraphs() {#processParagraphs--}
```
public void processParagraphs()
```


Stores document into stream.

### saveInternal(System.IO.Stream output) {#saveInternal-com.aspose.ms.System.IO.Stream-}
```
public void saveInternal(System.IO.Stream output)
```


Stores document into stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | com.aspose.ms.System.IO.Stream | Stream where document shell be stored. |

### save(OutputStream output) {#save-java.io.OutputStream-}
```
public void save(OutputStream output)
```


Stores document into stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | java.io.OutputStream | Stream where document shell be stored. |

### save(String outputFileName) {#save-java.lang.String-}
```
public void save(String outputFileName)
```


Saves document into the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | java.lang.String | Path to file where the document will be stored. |

### exportAnnotationsToXfdf(String fileName) {#exportAnnotationsToXfdf-java.lang.String-}
```
public void exportAnnotationsToXfdf(String fileName)
```


Exports all document annotations to XFDF file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | XFDF file name |

### sendTo(DocumentDevice device, OutputStream output) {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-}
```
public void sendTo(DocumentDevice device, OutputStream output)
```


Sends the whole document to the document device for processing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| device | [DocumentDevice](../../com.aspose.pdf.devices/documentdevice) | Document device which is used to process the document. |
| output | java.io.OutputStream | Output stream contains the results of the document processing with given device. |

### sendTo(DocumentDevice device, int fromPage, int toPage, OutputStream output) {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-}
```
public void sendTo(DocumentDevice device, int fromPage, int toPage, OutputStream output)
```


Sends the certain pages of the document to the document device for processing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| device | [DocumentDevice](../../com.aspose.pdf.devices/documentdevice) | Document device which is used to process the document. |
| fromPage | int | The first page for processing. |
| toPage | int | The last page for processing. |
| output | java.io.OutputStream | Output stream contains the results of the document pages processing with given device. |

### sendTo(DocumentDevice device, String outputFileName) {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-}
```
public void sendTo(DocumentDevice device, String outputFileName)
```


Sends the whole document to the document device for processing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| device | [DocumentDevice](../../com.aspose.pdf.devices/documentdevice) | Document device which is used to process the document. |
| outputFileName | java.lang.String | Output file name with the results of processing. |

### sendTo(DocumentDevice device, int fromPage, int toPage, String outputFileName) {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-}
```
public void sendTo(DocumentDevice device, int fromPage, int toPage, String outputFileName)
```


Sends the whole document to the document device for processing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| device | [DocumentDevice](../../com.aspose.pdf.devices/documentdevice) | Document device which is used to process the document. |
| fromPage | int | The first page for processing. |
| toPage | int | The last page for processing. |
| outputFileName | java.lang.String | Output file name with the results of processing. |

### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Removes metadata from the document.

### importAnnotationsFromXfdf(String fileName) {#importAnnotationsFromXfdf-java.lang.String-}
```
public void importAnnotationsFromXfdf(String fileName)
```


Imports annotations from XFDF file to document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | XFDF file name |

### validate(String outputLogFileName, int format) {#validate-java.lang.String-int-}
```
public boolean validate(String outputLogFileName, int format)
```


Validate document into the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | java.lang.String | Path to file where the comments will be stored. |
| format | int | Pdf format. |

**Returns:**
boolean
### convert(String outputLogFileName, int format, int action) {#convert-java.lang.String-int-int-}
```
public boolean convert(String outputLogFileName, int format, int action)
```


Convert document and save errors into the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | java.lang.String | Path to file where the comments will be stored. |
| format | int | Pdf format. |
| action | int | Action for objects that can not be converted |

**Returns:**
boolean
### convert(Document.CallBackGetHocr callback) {#convert-com.aspose.pdf.Document.CallBackGetHocr-}
```
public boolean convert(Document.CallBackGetHocr callback)
```


Convert document and save errors into the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | [CallBackGetHocr](../../com.aspose.pdf/callbackgethocr) | Action for objects that can not be converted |

**Returns:**
boolean - 
### convertInternal(System.IO.Stream outputLogStream, int format, int action) {#convertInternal-com.aspose.ms.System.IO.Stream-int-int-}
```
public boolean convertInternal(System.IO.Stream outputLogStream, int format, int action)
```


Convert document and save errors into the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | com.aspose.ms.System.IO.Stream | Stream where the comments will be stored. |
| format | int | Pdf format. |
| action | int | Action for objects that can not be converted |

**Returns:**
boolean
### convert(OutputStream outputLogStream, int format, int action) {#convert-java.io.OutputStream-int-int-}
```
public boolean convert(OutputStream outputLogStream, int format, int action)
```


Convert document and save errors into the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | java.io.OutputStream | Stream where the comments will be stored. |
| format | int | Pdf format. |
| action | int | Action for objects that can not be converted |

**Returns:**
boolean
### convert(System.Xml.XmlTextWriter xml, int format, boolean onlyValidation, int action) {#convert-com.aspose.ms.System.Xml.XmlTextWriter-int-boolean-int-}
```
public boolean convert(System.Xml.XmlTextWriter xml, int format, boolean onlyValidation, int action)
```


Convert the PDF Document and log results.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xml | com.aspose.ms.System.Xml.XmlTextWriter | The log. |
| format | int | Pdf format. |
| onlyValidation | boolean | Only document validation. |
| action | int | Action for objects that can not be converted |

**Returns:**
boolean - 
### flatten() {#flatten--}
```
public void flatten()
```


Removes all fields from the document and place their values instead.

### getCryptoAlgorithm() {#getCryptoAlgorithm--}
```
public int getCryptoAlgorithm()
```


Gets security settings if document is encrypted. If document is not encrypted then corresponding exception will be raised in .net 1.1 or CryptoAlgorithm will be null for other .net versions.

**Returns:**
int
### encrypt(String userPassword, String ownerPassword, DocumentPrivilege privileges, int cryptoAlgorithm, boolean usePdf20) {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-boolean-}
```
public void encrypt(String userPassword, String ownerPassword, DocumentPrivilege privileges, int cryptoAlgorithm, boolean usePdf20)
```


Encrypts the document. Call then Save to get encrypted version of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | java.lang.String | User password. |
| ownerPassword | java.lang.String | Owner password. |
| privileges | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Document permissions, see  Permissions  for details. |
| cryptoAlgorithm | int | Cryptographic algorithm, see  CryptoAlgorithm  for details. |
| usePdf20 | boolean | Support for revision 6 (Extension 8). |

### encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm) {#encrypt-java.lang.String-java.lang.String-int-int-}
```
public void encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)
```


Encrypts the document. Call then Save to get encrypted version of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | java.lang.String | User password. |
| ownerPassword | java.lang.String | Owner password. |
| permissions | int | Document permissions, see  Permissions  for details. |
| cryptoAlgorithm | int | Cryptographic algorithm, see  CryptoAlgorithm  for details. |

### encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm, boolean usePdf20) {#encrypt-java.lang.String-java.lang.String-int-int-boolean-}
```
public void encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm, boolean usePdf20)
```


Encrypts the document. Call then Save to get encrypted version of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | java.lang.String | User password. |
| ownerPassword | java.lang.String | Owner password. |
| permissions | int | Document permissions, see  Permissions  for details. |
| cryptoAlgorithm | int | Cryptographic algorithm, see  CryptoAlgorithm  for details. |
| usePdf20 | boolean | Support for revision 6 (Extension 8). |

### changePasswords(String ownerPassword, String newUserPassword, String newOwnerPassword) {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
```
public void changePasswords(String ownerPassword, String newUserPassword, String newOwnerPassword)
```


Changes document passwords. This action can be done only using owner password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | java.lang.String | Owner password. |
| newUserPassword | java.lang.String | New user password. |
| newOwnerPassword | java.lang.String | New owner password. |

### isLinearized() {#isLinearized--}
```
public boolean isLinearized()
```


Gets a value indicating whether document is linearized.

**Returns:**
boolean
### isLinearized(boolean value) {#isLinearized-boolean-}
```
public void isLinearized(boolean value)
```


Sets a value indicating whether document is linearized.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### decrypt() {#decrypt--}
```
public void decrypt()
```


Decrypts the document. Call then Save to obtain decrypted version of the document.

### getPermissions() {#getPermissions--}
```
public int getPermissions()
```


Gets permissions of the document.

**Returns:**
int
### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Gets encrypted status of the document. True if document is encrypted.

**Returns:**
boolean
### optimize() {#optimize--}
```
public void optimize()
```


Linearize document in order to - open the first page as quickly as possible; - display next page or follow by link to the next page as quickly as possible; - display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first); - permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed. Invoking this method doesn't actually saves the document. On the contrary the document only is prepared to have optimized structure, call then Save to get optimized document.

### save() {#save--}
```
public void save()
```


Save document incrementally (i.e. using incremental update technque). In order to save document incremetally we should open the document file for writing. Therefore Document must be initialized with writable stream like in the next code snippet: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // make some changes and save the document incrementally doc.Save();

### save(String outputFileName, int format) {#save-java.lang.String-int-}
```
public void save(String outputFileName, int format)
```


Saves the document with a new name along with a file format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | java.lang.String | Path to file where the document will be stored. |
| format | int | Format options. |

### save(OutputStream outputStream, int format) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream outputStream, int format)
```


Saves the document with a new name along with a file format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Stream where the document will be stored. |
| format | int | Format options. |

### save(String outputFileName, SaveOptions options) {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
```
public void save(String outputFileName, SaveOptions options)
```


Saves the document with a new name setting its save options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | java.lang.String | Path to file where the document will be stored. |
| options | [SaveOptions](../../com.aspose.pdf/saveoptions) | Save options. |

### save(OutputStream outputStream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
```
public void save(OutputStream outputStream, SaveOptions options)
```


Saves the document to a stream with a save options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Stream where the document will be stored. |
| options | [SaveOptions](../../com.aspose.pdf/saveoptions) | Save options. |

### getId() {#getId--}
```
public Id getId()
```


Gets the ID.

**Returns:**
[Id](../../com.aspose.pdf/id)
### getMetadataStream() {#getMetadataStream--}
```
public IPdfStreamAccessor getMetadataStream()
```


Returns raw metadata stream

**Returns:**
[IPdfStreamAccessor](../../com.aspose.pdf.engine.data.types/ipdfstreamaccessor) - Metadata stream.
### suppressUpdate() {#suppressUpdate--}
```
public void suppressUpdate()
```


Suppresses update contents data for all pages The contents is not updated until ResumeUpdate is called

### resumeUpdate() {#resumeUpdate--}
```
public void resumeUpdate()
```


resumes document update

### dispose() {#dispose--}
```
public void dispose()
```


Closes all resources used by this document.

### getBackground() {#getBackground--}
```
public Color getBackground()
```


Gets the background color of the document.

**Returns:**
[Color](../../com.aspose.pdf.java.awt/color)
### setBackground(Color value) {#setBackground-com.aspose.pdf.java.awt.Color-}
```
public void setBackground(Color value)
```


Sets the background color of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf.java.awt/color) |  |

### getDefaultCopier() {#getDefaultCopier--}
```
public Copier getDefaultCopier()
```


Returns copier used for coping pages to this document.

**Returns:**
[Copier](../../com.aspose.pdf/copier)
### optimizeResources() {#optimizeResources--}
```
public void optimizeResources()
```


Optimize resources in the document: 1. Resources which are not used on the document pages are removed; 2. Equal resources are joined into one object; 3. Unused objects are deleted.

### optimizeResources(Document.OptimizationOptions strategy) {#optimizeResources-com.aspose.pdf.Document.OptimizationOptions-}
```
public void optimizeResources(Document.OptimizationOptions strategy)
```


Optimize resources in the document according to defined optimization strategy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| strategy | [OptimizationOptions](../../com.aspose.pdf/optimizationoptions) | Optimization strategy. |

### getOptimizeSize() {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```


Gets optimization flag. When pages are added to document, equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false.

**Returns:**
boolean - boolean value
### setOptimizeSize(boolean value) {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```


Sets optimization flag. When pages are added to document, equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getIgnoreCorruptedObjects() {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```


Gets or sets flag of ignoring errors in source files. When pages from source document copied into destination document, copying process is stopped with exception if some objects in source files are corrupted when this flag is false. example: dest.Pages.Add(src.Pages); If this flag is set to true then corrupted objects will be replaced with empty values. By default: true.

**Returns:**
boolean - boolean value
### setIgnoreCorruptedObjects(boolean value) {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```


Gets or sets flag of ignoring errors in source files. When pages from source document copied into destination document, copying process is stopped with exception if some objects in source files are corrupted when this flag is false. example: dest.Pages.Add(src.Pages); If this flag is set to true then corrupted objects will be replaced with empty values. By default: true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getPageLabels() {#getPageLabels--}
```
public PageLabelCollection getPageLabels()
```


Gets page labels in the document.

**Returns:**
[PageLabelCollection](../../com.aspose.pdf/pagelabelcollection)
### freeMemory() {#freeMemory--}
```
public void freeMemory()
```


Clears memory

