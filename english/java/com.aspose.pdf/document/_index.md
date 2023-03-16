---
title: Document
second_title: Aspose.PDF for Java API Reference
description: Class representing PDF document
type: docs
weight: 91
url: /java/com.aspose.pdf/document/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.IVentureLicenseTarget, com.aspose.pdf.ADocument

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
| [Document(byte[] input)](#Document-byte---) | Initialize new Document instance from the  input  byte array. |
| [Document(InputStream input)](#Document-java.io.InputStream-) | Initialize new Document instance from the  input  stream. |
| [Document(InputStream input, String password)](#Document-java.io.InputStream-java.lang.String-) | Initialize new Document instance from the  input  stream. |
| [Document(System.IO.Stream input)](#Document-com.aspose.ms.System.IO.Stream-) | Initialize new Document instance from the  input  stream. |
| [Document(InputStream input, String password, boolean isManagedStream)](#Document-java.io.InputStream-java.lang.String-boolean-) | Initialize new Document instance from the  input  stream. |
| [Document(InputStream input, boolean isManagedStream)](#Document-java.io.InputStream-boolean-) | Initialize new Document instance from the  input  stream. |
| [Document(InputStream input, LoadOptions options)](#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Opens an existing document from a stream providing necessary converting to get pdf document. |
| [Document(String filename, LoadOptions options)](#Document-java.lang.String-com.aspose.pdf.LoadOptions-) | Opens an existing document from a file providing necessary converting to get pdf document. |
| [Document(System.IO.Stream input, String password)](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-) | Opens an existing document from a stream. |
| [Document(String filename)](#Document-java.lang.String-) | Just init Document using  filename . |
| [Document(String filename, String password)](#Document-java.lang.String-java.lang.String-) | Initializes new instance of the  Document  class for working with encrypted document. |
| [Document(String filename, String password, boolean isManagedStream)](#Document-java.lang.String-java.lang.String-boolean-) | Initializes new instance of the  Document  class for working with encrypted document. |
## Methods

| Method | Description |
| --- | --- |
| [getPageInfo()](#getPageInfo--) | Gets the page info. |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | Sets the page info. |
| [getDestinations()](#getDestinations--) | Gets the collection of destinations. |
| [getPdfFormat()](#getPdfFormat--) | Gets pdfa format |
| [getFontUtilities()](#getFontUtilities--) | IDocumentFontUtilities instance |
| [removePdfaCompliance()](#removePdfaCompliance--) | Remove pdfa compliance from the document |
| [getCollection()](#getCollection--) | Gets collection of document. |
| [setCollection(Collection value)](#setCollection-com.aspose.pdf.Collection-) | Sets collection of document. |
| [getVersion()](#getVersion--) | Gets a version of Pdf from Pdf file header. |
| [getOpenAction()](#getOpenAction--) | Gets action performed at document opening. |
| [setOpenAction(IAppointment value)](#setOpenAction-com.aspose.pdf.IAppointment-) | Sets action performed at document opening. |
| [isHideToolBar()](#isHideToolBar--) | Gets flag specifying whether toolbar should be hidden when document is active. |
| [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | Set flag specifying whether toolbar should be hidden when document is active. |
| [isHideMenubar()](#isHideMenubar--) | Gets flag specifying whether menu bar should be hidden when document is active. |
| [setHideMenubar(boolean value)](#setHideMenubar-boolean-) | Sets flag specifying whether menu bar should be hidden when document is active. |
| [isHideWindowUI()](#isHideWindowUI--) | Gets flag specifying whether user interface elements should be hidden when document is active. |
| [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | Sets flag specifying whether user interface elements should be hidden when document is active. |
| [isFitWindow()](#isFitWindow--) | Gets flag specifying whether document window must be resized to fit the first displayed page. |
| [setFitWindow(boolean value)](#setFitWindow-boolean-) | Sets flag specifying whether document window must be resized to fit the first displayed page. |
| [isCenterWindow()](#isCenterWindow--) | Gets flag specifying whether position of the document's window will be centered on the screen. |
| [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | Sets flag specifying whether position of the document's window will be centered on the screen. |
| [isDisplayDocTitle()](#isDisplayDocTitle--) | Gets flag specifying whether document's window title bar should display document title. |
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
| [save(System.IO.Stream output)](#save-com.aspose.ms.System.IO.Stream-) | Stores document into stream. |
| [save(OutputStream output)](#save-java.io.OutputStream-) | Stores document into stream. |
| [save(String outputFileName)](#save-java.lang.String-) | Saves document into the specified file. |
| [exportAnnotationsToXfdf(String fileName)](#exportAnnotationsToXfdf-java.lang.String-) | Exports all document annotations to XFDF file |
| [sendTo(DocumentDevice device, OutputStream output)](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Sends the whole document to the document device for processing. |
| [sendTo(DocumentDevice device, int fromPage, int toPage, OutputStream output)](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Sends the certain pages of the document to the document device for processing. |
| [sendTo(DocumentDevice device, String outputFileName)](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Sends the whole document to the document device for processing. |
| [sendTo(DocumentDevice device, int fromPage, int toPage, String outputFileName)](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Sends the whole document to the document device for processing. |
| [removeMetadata()](#removeMetadata--) | Removes metadata from the document. |
| [importAnnotationsFromXfdf(String fileName)](#importAnnotationsFromXfdf-java.lang.String-) | Imports annotations from XFDF file to document. |
| [validate(String outputLogFileName, PdfFormat format)](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Validate document into the specified file. |
| [convert(String outputLogFileName, PdfFormat format, int action)](#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-) | Convert document and save errors into the specified file. |
| [validate(OutputStream outputLogStream, PdfFormat format)](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Validate document into the specified file. |
| [convert(String outputLogFileName, PdfFormat format, int action, int transparencyAction)](#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-int-) | Convert document and save errors into the specified file. |
| [convert(Document.CallBackGetHocr callback)](#convert-com.aspose.pdf.Document.CallBackGetHocr-) | Recognize images inside the document and add hocr strings over it. |
| [convertWithSkippingErrors(Document.CallBackGetHocr callback)](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocr-) | Convert document to searchable document and skip errors of hochr that can not be converted. |
| [convertInternal(System.IO.Stream outputLogStream, PdfFormat format, int action)](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-int-) | Convert document and save errors into the specified stream. |
| [convert(OutputStream outputLogStream, PdfFormat format, int action)](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-) | Convert document and save errors into the specified stream. |
| [convert(PdfFormatConversionOptions options)](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Convert document using specified conversion options |
| [convert(int fixup, OutputStream outputLog)](#convert-int-java.io.OutputStream-) | Convert document by applying the Fixup. |
| [convert(int fixup, OutputStream outputLog, boolean onlyValidation, Object[] parameters)](#convert-int-java.io.OutputStream-boolean-java.lang.Object---) | Convert document by applying the Fixup. |
| [convert(int fixup, String outputLog)](#convert-int-java.lang.String-) | Convert document by applying the Fixup. |
| [convert(int fixup, String outputLog, boolean onlyValidation, Object[] parameters)](#convert-int-java.lang.String-boolean-java.lang.Object---) | Convert document by applying the Fixup. |
| [flatten()](#flatten--) | Removes all fields from the document and place their values instead. |
| [getCryptoAlgorithm()](#getCryptoAlgorithm--) | Gets security settings if document is encrypted. |
| [encrypt(String userPassword, String ownerPassword, DocumentPrivilege privileges, CryptoAlgorithm cryptoAlgorithm, boolean usePdf20)](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Encrypts the document. |
| [encrypt(String userPassword, String ownerPassword, int permissions, CryptoAlgorithm cryptoAlgorithm)](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Encrypts the document. |
| [encrypt(String userPassword, String ownerPassword, int permissions, CryptoAlgorithm cryptoAlgorithm, boolean usePdf20)](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Encrypts the document. |
| [changePasswords(String ownerPassword, String newUserPassword, String newOwnerPassword)](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Changes document passwords. |
| [isLinearized()](#isLinearized--) | Gets a value indicating whether document is linearized. |
| [setLinearized(boolean value)](#setLinearized-boolean-) | Sets a value indicating whether document is linearized. |
| [decrypt()](#decrypt--) | Decrypts the document. |
| [getPermissions()](#getPermissions--) | Gets permissions of the document. |
| [isEncrypted()](#isEncrypted--) | Gets encrypted status of the document. |
| [optimize()](#optimize--) | Linearize document in order to - open the first page as quickly as possible; - display next page or follow by link to the next page as quickly as possible; - display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first); - permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed. |
| [save()](#save--) | Save document incrementally (i.e. using incremental update technique). |
| [save(String outputFileName, SaveFormat format)](#save-java.lang.String-com.aspose.pdf.SaveFormat-) | Saves the document with a new name along with a file format. |
| [saveIncrementally(OutputStream output)](#saveIncrementally-java.io.OutputStream-) | Saves incrementally the PDF Document to the specified stream. |
| [saveIncrementally(System.IO.Stream output)](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Saves incrementally the PDF Document to the specified stream. |
| [saveIncrementally(String outputFileName)](#saveIncrementally-java.lang.String-) | Saves incrementally the PDF Document to the specified stream. |
| [save(OutputStream outputStream, SaveFormat format)](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | Saves the document with a new name along with a file format. |
| [save(String outputFileName, SaveOptions options)](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | Saves the document with a new name setting its save options. |
| [save(OutputStream outputStream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Saves the document to a stream with a save options. |
| [getId()](#getId--) | Gets the ID. |
| [getMetadataStream()](#getMetadataStream--) | Returns raw metadata stream |
| [suppressUpdate()](#suppressUpdate--) | Suppresses update contents data for all pages The contents is not updated until ResumeUpdate is called |
| [resumeUpdate()](#resumeUpdate--) | resumes document update |
| [dispose()](#dispose--) | Closes all resources used by this document. |
| [close()](#close--) | Closes all resources used by this document. |
| [getBackground()](#getBackground--) | Gets the background color of the document. |
| [setBackground(Color value)](#setBackground-java.awt.Color-) | Sets the background color of the document. |
| [getDefaultCopier()](#getDefaultCopier--) | Returns copier used for coping pages to this document. |
| [optimizeResources()](#optimizeResources--) | Optimize resources in the document: 1. |
| [optimizeResources(OptimizationOptions strategy)](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Optimize resources in the document according to defined optimization strategy. |
| [getOptimizeSize()](#getOptimizeSize--) | Gets optimization flag. |
| [setOptimizeSize(boolean value)](#setOptimizeSize-boolean-) | Sets optimization flag. |
| [getIgnoreCorruptedObjects()](#getIgnoreCorruptedObjects--) | Gets or sets flag of ignoring errors in source files. |
| [setIgnoreCorruptedObjects(boolean value)](#setIgnoreCorruptedObjects-boolean-) | Gets or sets flag of ignoring errors in source files. |
| [getCatalogValue(String key)](#getCatalogValue-java.lang.String-) | Returns item value from catalog dictionary. |
| [getPageLabels()](#getPageLabels--) | Gets page labels in the document. |
| [freeMemory()](#freeMemory--) | Clears memory |
| [isAbsentFontTryToSubstitute()](#isAbsentFontTryToSubstitute--) | Flag which informs about replacement of missing font. |
| [setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)](#setAbsentFontTryToSubstitute-boolean-) | Setting flag for set program determined font in case of absense font. |
| [check(boolean doRepair)](#check-boolean-) | Validates document. |
| [isManualDisposeEnabled()](#isManualDisposeEnabled--) | By default method save close internal streams and release memory resources. |
| [setManualDisposeEnabled(boolean manualDisposeEnabled)](#setManualDisposeEnabled-boolean-) | By default method save closes internal streams and release memory resources. |
| [pageNodesToBalancedTree()](#pageNodesToBalancedTree--) | Organizes page tree nodes in a document into a balanced tree. |
| [pageNodesToBalancedTree(byte nodesNumInSubtrees)](#pageNodesToBalancedTree-byte-) | Organizes page tree nodes in a document into a balanced tree. |
### Document() {#Document--}
```
public Document()
```


Initializes empty document.

### Document(byte[] input) {#Document-byte---}
```
public Document(byte[] input)
```


Initialize new Document instance from the  input  byte array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | byte[] | byte array with pdf document. |

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


Initialize new Document instance from the  input  stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.io.InputStream | Input stream object, corresponding pdf is password protected. |
| password | java.lang.String | User or owner password. |

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


Opens an existing document from a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | com.aspose.ms.System.IO.Stream | Input file to convert into pdf document. |
| password | java.lang.String | User or owner password. |

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

### getPageInfo() {#getPageInfo--}
```
public PageInfo getPageInfo()
```


Gets the page info.(for generator only, not filled in when reading document)

**Returns:**
[PageInfo](../../com.aspose.pdf/pageinfo) - The page info.
### setPageInfo(PageInfo value) {#setPageInfo-com.aspose.pdf.PageInfo-}
```
public void setPageInfo(PageInfo value)
```


Sets the page info.(for generator only, not filled in when reading document)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageInfo](../../com.aspose.pdf/pageinfo) | PageInfo object |

### getDestinations() {#getDestinations--}
```
public DestinationCollection getDestinations()
```


Gets the collection of destinations.

**Returns:**
[DestinationCollection](../../com.aspose.pdf/destinationcollection) - DestinationCollection element
### getPdfFormat() {#getPdfFormat--}
```
public PdfFormat getPdfFormat()
```


Gets pdfa format

**Returns:**
[PdfFormat](../../com.aspose.pdf/pdfformat) - PdfFormat element
### getFontUtilities() {#getFontUtilities--}
```
public Document.IDocumentFontUtilities getFontUtilities()
```


IDocumentFontUtilities instance

**Returns:**
[IDocumentFontUtilities](../../com.aspose.pdf/idocumentfontutilities) - IDocumentFontUtilities instance
### removePdfaCompliance() {#removePdfaCompliance--}
```
public void removePdfaCompliance()
```


Remove pdfa compliance from the document

### getCollection() {#getCollection--}
```
public Collection getCollection()
```


Gets collection of document.

**Returns:**
[Collection](../../com.aspose.pdf/collection) - Collection object
### setCollection(Collection value) {#setCollection-com.aspose.pdf.Collection-}
```
public void setCollection(Collection value)
```


Sets collection of document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Collection](../../com.aspose.pdf/collection) | Collection object |

### getVersion() {#getVersion--}
```
public String getVersion()
```


Gets a version of Pdf from Pdf file header.

**Returns:**
java.lang.String - String value
### getOpenAction() {#getOpenAction--}
```
public IAppointment getOpenAction()
```


Gets action performed at document opening.

--------------------

```
Example demonstrates how to get CenterWindow flag:

 Document document = new Document("sample.pdf");
 IAppointment value = document.getOpenAction();
```

**Returns:**
[IAppointment](../../com.aspose.pdf/iappointment) - IAppointment object
### setOpenAction(IAppointment value) {#setOpenAction-com.aspose.pdf.IAppointment-}
```
public void setOpenAction(IAppointment value)
```


Sets action performed at document opening.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | IAppointment value |

### isHideToolBar() {#isHideToolBar--}
```
public boolean isHideToolBar()
```


Gets flag specifying whether toolbar should be hidden when document is active.

**Returns:**
boolean - boolean value

--------------------

```
Example demonstrates how to get HideToolBar flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isHideToolBar();
```
### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public void setHideToolBar(boolean value)
```


Set flag specifying whether toolbar should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isHideMenubar() {#isHideMenubar--}
```
public boolean isHideMenubar()
```


Gets flag specifying whether menu bar should be hidden when document is active.

**Returns:**
boolean - boolean value

--------------------

```
Example demonstrates how to get HideMenubar flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isHideMenubar();
```
### setHideMenubar(boolean value) {#setHideMenubar-boolean-}
```
public void setHideMenubar(boolean value)
```


Sets flag specifying whether menu bar should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isHideWindowUI() {#isHideWindowUI--}
```
public boolean isHideWindowUI()
```


Gets flag specifying whether user interface elements should be hidden when document is active.

**Returns:**
boolean - boolean value

--------------------

```
Example demonstrates how to get HideWindowUI flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isHideWindowUI();
```
### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public void setHideWindowUI(boolean value)
```


Sets flag specifying whether user interface elements should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isFitWindow() {#isFitWindow--}
```
public boolean isFitWindow()
```


Gets flag specifying whether document window must be resized to fit the first displayed page.

**Returns:**
boolean - boolean value

--------------------

```
Example demonstrates how to get FitWindow flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isFitWindow();
```
### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public void setFitWindow(boolean value)
```


Sets flag specifying whether document window must be resized to fit the first displayed page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isCenterWindow() {#isCenterWindow--}
```
public boolean isCenterWindow()
```


Gets flag specifying whether position of the document's window will be centered on the screen.

**Returns:**
boolean - boolean value

--------------------

```
Example demonstrates how to get CenterWindow flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isCenterWindow();
```
### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public void setCenterWindow(boolean value)
```


Sets flag specifying whether position of the document's window will be centered on the screen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isDisplayDocTitle() {#isDisplayDocTitle--}
```
public boolean isDisplayDocTitle()
```


Gets flag specifying whether document's window title bar should display document title.

**Returns:**
boolean - boolean value

--------------------

```
Example demonstrates how to get DisplayDocTitle flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isDisplayDocTitle();
```
### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public void setDisplayDocTitle(boolean value)
```


Sets flag specifying whether document's window title bar should display document title.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getPages() {#getPages--}
```
public PageCollection getPages()
```


Gets collection of document pages. Note that pages are numbered from 1 in collection.

**Returns:**
[PageCollection](../../com.aspose.pdf/pagecollection) - PageCollection object

--------------------

```
Example below demonstrates how to operate with the document pages:
 How to obtain number of pages and how to obtain rectangle of starting page of the document.

 Document document = new Document("sample.pdf");
 PageCollection  pages = document.getPages();
 System.out.println("Document contains " + pages.size());
 Page page = pages.get_Item(1);
 Rectangle rect = page.getRect();
```
### getOutlines() {#getOutlines--}
```
public OutlineCollection getOutlines()
```


Gets document outlines.

**Returns:**
[OutlineCollection](../../com.aspose.pdf/outlinecollection) - OutlineCollection object
### getActions() {#getActions--}
```
public DocumentActionCollection getActions()
```


Gets document actions. This property is instance of DocumentActions class which allows to get/set BeforClosing, BeforSaving, etc. actions.

**Returns:**
[DocumentActionCollection](../../com.aspose.pdf/documentactioncollection) - DocumentActionCollection object

--------------------

```
This example demonstrates how to obtain after open action of the document:

 Document document = new Document("PdfWithOpenAction.pdf");
 DocumentActionCollection actions = document.getActions();
 PdfAction afterSavingAction = actions.getAfterSaving();
```
### getForm() {#getForm--}
```
public Form getForm()
```


Gets Acro Form of the document.

**Returns:**
[Form](../../com.aspose.pdf/form) - Form object
### getEmbeddedFiles() {#getEmbeddedFiles--}
```
public EmbeddedFileCollection getEmbeddedFiles()
```


Gets collection of files embedded to document.

**Returns:**
[EmbeddedFileCollection](../../com.aspose.pdf/embeddedfilecollection) - EmbeddedFileCollection object
### getDirection() {#getDirection--}
```
public int getDirection()
```


Gets reading order of text: L2R (left to right) or R2L (right to left).

**Returns:**
int - Direction element
### setDirection(int value) {#setDirection-int-}
```
public void setDirection(int value)
```


Sets reading order of text: L2R (left to right) or R2L (right to left).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getPageMode() {#getPageMode--}
```
public int getPageMode()
```


Gets page mode, specifying how document should be displayed when opened.

**Returns:**
int - PageMode element
### setPageMode(int pageMode) {#setPageMode-int-}
```
public void setPageMode(int pageMode)
```


Sets page mode, specifying how document should be displayed when opened.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageMode | int | int value |

### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public int getNonFullScreenPageMode()
```


Gets page mode, specifying how to display the document on exiting full-screen mode.

**Returns:**
int - PageMode element
### setNonFullScreenPageMode(int value) {#setNonFullScreenPageMode-int-}
```
public void setNonFullScreenPageMode(int value)
```


Sets page mode, specifying how to display the document on exiting full-screen mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getPageLayout() {#getPageLayout--}
```
public int getPageLayout()
```


Gets page layout which shall be used when the document is opened.

**Returns:**
int - PageLayout element
### setPageLayout(int value) {#setPageLayout-int-}
```
public void setPageLayout(int value)
```


Sets page layout which shall be used when the document is opened.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getFileName() {#getFileName--}
```
public String getFileName()
```


Name of the PDF file that caused this document

**Returns:**
java.lang.String - String object
### getInfo() {#getInfo--}
```
public DocumentInfo getInfo()
```


Gets document info.

**Returns:**
[DocumentInfo](../../com.aspose.pdf/documentinfo) - DocumentInfo object
### getMetadata() {#getMetadata--}
```
public Metadata getMetadata()
```


Document metadata. (A PDF document may include general information, such as the document's title, author, and creation and modification dates. Such global information about the document (as opposed to its content or structure) is called metadata and is intended to assist in cataloguing and searching for documents in external databases.)

**Returns:**
[Metadata](../../com.aspose.pdf/metadata) - Metadata object
### getLogicalStructure() {#getLogicalStructure--}
```
public RootElement getLogicalStructure()
```


Gets logical structure of the document.

**Returns:**
[RootElement](../../com.aspose.pdf/rootelement) - RootElement object
### processParagraphs() {#processParagraphs--}
```
public void processParagraphs()
```


Stores document into stream.

### save(System.IO.Stream output) {#save-com.aspose.ms.System.IO.Stream-}
```
public void save(System.IO.Stream output)
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

### validate(String outputLogFileName, PdfFormat format) {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
```
public boolean validate(String outputLogFileName, PdfFormat format)
```


Validate document into the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | java.lang.String | Path to file where the comments will be stored. |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | PdfFormat element. |

**Returns:**
boolean
### convert(String outputLogFileName, PdfFormat format, int action) {#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-}
```
public boolean convert(String outputLogFileName, PdfFormat format, int action)
```


Convert document and save errors into the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | java.lang.String | Path to file where the comments will be stored. |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | Pdf format. |
| action | int | Action for objects that can not be converted |

**Returns:**
boolean - boolean value
### validate(OutputStream outputLogStream, PdfFormat format) {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
```
public boolean validate(OutputStream outputLogStream, PdfFormat format)
```


Validate document into the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | java.io.OutputStream | Stream where the comments will be stored. |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | Pdf format. |

**Returns:**
boolean - boolean value
### convert(String outputLogFileName, PdfFormat format, int action, int transparencyAction) {#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-int-}
```
public boolean convert(String outputLogFileName, PdfFormat format, int action, int transparencyAction)
```


Convert document and save errors into the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | java.lang.String | Path to file where the comments will be stored. |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | The pdf format. |
| action | int | Action for objects that can not be converted |
| transparencyAction | int | Action for image masked objects |

**Returns:**
boolean - The operation result
### convert(Document.CallBackGetHocr callback) {#convert-com.aspose.pdf.Document.CallBackGetHocr-}
```
public boolean convert(Document.CallBackGetHocr callback)
```


Recognize images inside the document and add hocr strings over it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | [CallBackGetHocr](../../com.aspose.pdf/callbackgethocr) | callback Action for images that will be processed by hocr recognize. |

**Returns:**
boolean - boolean value The operation result. If there are no images in the document returns  false .
### convertWithSkippingErrors(Document.CallBackGetHocr callback) {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocr-}
```
public boolean convertWithSkippingErrors(Document.CallBackGetHocr callback)
```


Convert document to searchable document and skip errors of hochr that can not be converted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | [CallBackGetHocr](../../com.aspose.pdf/callbackgethocr) | The call back procedure for hocr recognize. |

**Returns:**
boolean - boolean value
### convertInternal(System.IO.Stream outputLogStream, PdfFormat format, int action) {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-int-}
```
public boolean convertInternal(System.IO.Stream outputLogStream, PdfFormat format, int action)
```


Convert document and save errors into the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | com.aspose.ms.System.IO.Stream | Stream where the comments will be stored. |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | Pdf format. |
| action | int | The call back procedure for hocr recognize. |

**Returns:**
boolean - boolean value
### convert(OutputStream outputLogStream, PdfFormat format, int action) {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-}
```
public boolean convert(OutputStream outputLogStream, PdfFormat format, int action)
```


Convert document and save errors into the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | java.io.OutputStream | Stream where the comments will be stored. |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | Pdf format. |
| action | int | Action for objects that can not be converted |

**Returns:**
boolean - boolean value
### convert(PdfFormatConversionOptions options) {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
```
public boolean convert(PdfFormatConversionOptions options)
```


Convert document using specified conversion options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [PdfFormatConversionOptions](../../com.aspose.pdf/pdfformatconversionoptions) | set of options for convert PDF document |

**Returns:**
boolean - The operation result
### convert(int fixup, OutputStream outputLog) {#convert-int-java.io.OutputStream-}
```
public final boolean convert(int fixup, OutputStream outputLog)
```


Convert document by applying the Fixup.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fixup | int | The Fixup type. |
| outputLog | java.io.OutputStream | The log of process. |

**Returns:**
boolean - The operation result.
### convert(int fixup, OutputStream outputLog, boolean onlyValidation, Object[] parameters) {#convert-int-java.io.OutputStream-boolean-java.lang.Object---}
```
public final boolean convert(int fixup, OutputStream outputLog, boolean onlyValidation, Object[] parameters)
```


Convert document by applying the Fixup.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fixup | int | The Fixup type. |
| outputLog | java.io.OutputStream | The log of process. |
| onlyValidation | boolean | Only document validation. |
| parameters | java.lang.Object[] | Properties for Fixup that can not be set. |

**Returns:**
boolean - The operation result.
### convert(int fixup, String outputLog) {#convert-int-java.lang.String-}
```
public boolean convert(int fixup, String outputLog)
```


Convert document by applying the Fixup.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fixup | int | The Fixup type. |
| outputLog | java.lang.String | The log of process. |

**Returns:**
boolean - The operation result.
### convert(int fixup, String outputLog, boolean onlyValidation, Object[] parameters) {#convert-int-java.lang.String-boolean-java.lang.Object---}
```
public boolean convert(int fixup, String outputLog, boolean onlyValidation, Object[] parameters)
```


Convert document by applying the Fixup.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fixup | int | The Fixup type. |
| outputLog | java.lang.String | The log of process. |
| onlyValidation | boolean | Only document validation. |
| parameters | java.lang.Object[] | Properties for Fixup that can not be set. |

**Returns:**
boolean - The operation result.
### flatten() {#flatten--}
```
public void flatten()
```


Removes all fields from the document and place their values instead.

### getCryptoAlgorithm() {#getCryptoAlgorithm--}
```
public CryptoAlgorithm getCryptoAlgorithm()
```


Gets security settings if document is encrypted. If document is not encrypted then corresponding exception will be raised in .net 1.1 or CryptoAlgorithm will be null for other .net versions.

**Returns:**
[CryptoAlgorithm](../../com.aspose.pdf/cryptoalgorithm) - CryptoAlgorithm element
### encrypt(String userPassword, String ownerPassword, DocumentPrivilege privileges, CryptoAlgorithm cryptoAlgorithm, boolean usePdf20) {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
```
public void encrypt(String userPassword, String ownerPassword, DocumentPrivilege privileges, CryptoAlgorithm cryptoAlgorithm, boolean usePdf20)
```


Encrypts the document. Call then Save to get encrypted version of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | java.lang.String | User password. |
| ownerPassword | java.lang.String | Owner password. |
| privileges | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Document permissions, see  Permissions  for details. |
| cryptoAlgorithm | [CryptoAlgorithm](../../com.aspose.pdf/cryptoalgorithm) | Cryptographic algorithm, see  CryptoAlgorithm  for details. |
| usePdf20 | boolean | Support for revision 6 (Extension 8). |

### encrypt(String userPassword, String ownerPassword, int permissions, CryptoAlgorithm cryptoAlgorithm) {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
```
public void encrypt(String userPassword, String ownerPassword, int permissions, CryptoAlgorithm cryptoAlgorithm)
```


Encrypts the document. Call then Save to get encrypted version of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | java.lang.String | User password. |
| ownerPassword | java.lang.String | Owner password. |
| permissions | int | Document permissions, see  Permissions  for details. |
| cryptoAlgorithm | [CryptoAlgorithm](../../com.aspose.pdf/cryptoalgorithm) | Cryptographic algorithm, see  CryptoAlgorithm  for details. |

### encrypt(String userPassword, String ownerPassword, int permissions, CryptoAlgorithm cryptoAlgorithm, boolean usePdf20) {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
```
public void encrypt(String userPassword, String ownerPassword, int permissions, CryptoAlgorithm cryptoAlgorithm, boolean usePdf20)
```


Encrypts the document. Call then Save to get encrypted version of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | java.lang.String | User password. |
| ownerPassword | java.lang.String | Owner password. |
| permissions | int | Document permissions, see  Permissions  for details. |
| cryptoAlgorithm | [CryptoAlgorithm](../../com.aspose.pdf/cryptoalgorithm) | Cryptographic algorithm, see  CryptoAlgorithm  for details. |
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
boolean - boolean value
### setLinearized(boolean value) {#setLinearized-boolean-}
```
public void setLinearized(boolean value)
```


Sets a value indicating whether document is linearized.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

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
int - int value
### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Gets encrypted status of the document. True if document is encrypted.

**Returns:**
boolean - boolean value
### optimize() {#optimize--}
```
public void optimize()
```


Linearize document in order to - open the first page as quickly as possible; - display next page or follow by link to the next page as quickly as possible; - display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first); - permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed. Invoking this method doesn't actually saves the document. On the contrary the document only is prepared to have optimized structure, call then Save to get optimized document.

### save() {#save--}
```
public void save()
```


Save document incrementally (i.e. using incremental update technique).

--------------------

In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save();

In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally.

### save(String outputFileName, SaveFormat format) {#save-java.lang.String-com.aspose.pdf.SaveFormat-}
```
public void save(String outputFileName, SaveFormat format)
```


Saves the document with a new name along with a file format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | java.lang.String | Path to file where the document will be stored. |
| format | [SaveFormat](../../com.aspose.pdf/saveformat) | Format options. |

### saveIncrementally(OutputStream output) {#saveIncrementally-java.io.OutputStream-}
```
public void saveIncrementally(OutputStream output)
```


Saves incrementally the PDF Document to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | java.io.OutputStream | OutputStream object |

### saveIncrementally(System.IO.Stream output) {#saveIncrementally-com.aspose.ms.System.IO.Stream-}
```
public void saveIncrementally(System.IO.Stream output)
```


Saves incrementally the PDF Document to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | com.aspose.ms.System.IO.Stream | OutputStream object |

### saveIncrementally(String outputFileName) {#saveIncrementally-java.lang.String-}
```
public void saveIncrementally(String outputFileName)
```


Saves incrementally the PDF Document to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | java.lang.String | OutputStream object |

### save(OutputStream outputStream, SaveFormat format) {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
```
public void save(OutputStream outputStream, SaveFormat format)
```


Saves the document with a new name along with a file format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Stream where the document will be stored. |
| format | [SaveFormat](../../com.aspose.pdf/saveformat) | Format options. |

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
[Id](../../com.aspose.pdf/id) - Id object
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

This method is obsolete, use close() instead.

### close() {#close--}
```
public void close()
```


Closes all resources used by this document.

### getBackground() {#getBackground--}
```
public Color getBackground()
```


Gets the background color of the document.

**Returns:**
[Color](../../java.awt/color) - Color object
### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public void setBackground(Color value)
```


Sets the background color of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color | Color object |

### getDefaultCopier() {#getDefaultCopier--}
```
public Copier getDefaultCopier()
```


Returns copier used for coping pages to this document.

**Returns:**
[Copier](../../com.aspose.pdf/copier) - Copier object
### optimizeResources() {#optimizeResources--}
```
public void optimizeResources()
```


Optimize resources in the document: 1. Resources which are not used on the document pages are removed; 2. Equal resources are joined into one object; 3. Unused objects are deleted.

### optimizeResources(OptimizationOptions strategy) {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
```
public void optimizeResources(OptimizationOptions strategy)
```


Optimize resources in the document according to defined optimization strategy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| strategy | [OptimizationOptions](../../com.aspose.pdf.optimization/optimizationoptions) | Optimization strategy. |

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

### getCatalogValue(String key) {#getCatalogValue-java.lang.String-}
```
public Object getCatalogValue(String key)
```


Returns item value from catalog dictionary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key of item. |

**Returns:**
java.lang.Object - Item value - if key was successfully found; otherwise, null.
### getPageLabels() {#getPageLabels--}
```
public PageLabelCollection getPageLabels()
```


Gets page labels in the document.

**Returns:**
[PageLabelCollection](../../com.aspose.pdf/pagelabelcollection) - PageLabelCollection object
### freeMemory() {#freeMemory--}
```
public void freeMemory()
```


Clears memory

### isAbsentFontTryToSubstitute() {#isAbsentFontTryToSubstitute--}
```
public boolean isAbsentFontTryToSubstitute()
```


Flag which informs about replacement of missing font.

**Returns:**
boolean
### setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute) {#setAbsentFontTryToSubstitute-boolean-}
```
public void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```


Setting flag for set program determined font in case of absense font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| setAbsentFontTryToSubstitute | boolean |  |

### check(boolean doRepair) {#check-boolean-}
```
public boolean check(boolean doRepair)
```


Validates document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doRepair | boolean | If true found issues will be repaired. |

**Returns:**
boolean - boolean value
### isManualDisposeEnabled() {#isManualDisposeEnabled--}
```
public boolean isManualDisposeEnabled()
```


By default method save close internal streams and release memory resources. We can do some operations and continue work with the document after method save if this ManualDispose parameter is enabled.

**Returns:**
boolean - boolean value. (Default value == false)
### setManualDisposeEnabled(boolean manualDisposeEnabled) {#setManualDisposeEnabled-boolean-}
```
public void setManualDisposeEnabled(boolean manualDisposeEnabled)
```


By default method save closes internal streams and release memory resources. We can do some operations and continue work with the document after method save is called if this ManualDispose parameter is enabled. But it is strongly recommended to call the dispose method when the Document instance is no longer needed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| manualDisposeEnabled | boolean | boolean value. (Default value == false) |

### pageNodesToBalancedTree() {#pageNodesToBalancedTree--}
```
public final void pageNodesToBalancedTree()
```


Organizes page tree nodes in a document into a balanced tree. Only if the document has more than nodesNumInSubtrees page objects, otherwise it does nothing.

### pageNodesToBalancedTree(byte nodesNumInSubtrees) {#pageNodesToBalancedTree-byte-}
```
public final void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```


Organizes page tree nodes in a document into a balanced tree. Only if the document has more than nodesNumInSubtrees page objects, otherwise it does nothing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| nodesNumInSubtrees | byte | Desired number of subnodes. |

