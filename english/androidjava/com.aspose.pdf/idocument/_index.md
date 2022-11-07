---
title: IDocument
second_title: Aspose.PDF for Java API Reference
description: interface representing PDF document
type: docs
weight: 350
url: /java/com.aspose.pdf/idocument/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public interface IDocument extends System.IDisposable
```

interface representing PDF document
## Methods

| Method | Description |
| --- | --- |
| [removePdfaCompliance()](#removePdfaCompliance--) | Remove pdfa compliance from the document |
| [getCollection()](#getCollection--) | Gets collection of document. |
| [setCollection(Collection value)](#setCollection-com.aspose.pdf.Collection-) |  |
| [getEngineDoc()](#getEngineDoc--) | Instance of IPdfDocument used to access to internal document structure. |
| [getVersion()](#getVersion--) | Gets a version of Pdf from Pdf file header. |
| [getOpenAction()](#getOpenAction--) | Gets action performed at document opening. |
| [setOpenAction(IAppointment value)](#setOpenAction-com.aspose.pdf.IAppointment-) | Sets action performed at document opening. |
| [getOptimizeSize()](#getOptimizeSize--) | Gets optimization flag. |
| [setOptimizeSize(boolean value)](#setOptimizeSize-boolean-) | Sets optimization flag. |
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
| [setPageMode(int value)](#setPageMode-int-) | Sets page mode, specifying how document should be displayed when opened. |
| [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | Gets page mode, specifying how to display the document on exiting full-screen mode. |
| [setNonFullScreenPageMode(int value)](#setNonFullScreenPageMode-int-) | Sets page mode, specifying how to display the document on exiting full-screen mode. |
| [getPageLayout()](#getPageLayout--) | Gets page layout which shall be used when the document is opened. |
| [setPageLayout(int value)](#setPageLayout-int-) | Sets page layout which shall be used when the document is opened. |
| [getFileName()](#getFileName--) | Name of the PDF file that caused this document |
| [getPageInfo()](#getPageInfo--) | Gets the page info. |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | Sets the page info. |
| [getFontReplaceBehavior()](#getFontReplaceBehavior--) | Gets the TextEditOptions.FontReplace |
| [setFontReplaceBehavior(int value)](#setFontReplaceBehavior-int-) | Sets the TextEditOptions.FontReplace |
| [getInfo()](#getInfo--) | Gets document info. |
| [getMetadata()](#getMetadata--) | Document metadata. |
| [getLogicalStructure()](#getLogicalStructure--) | Gets logical structure of the document. |
| [processParagraphs()](#processParagraphs--) | Stores document into stream. |
| [saveInternal(System.IO.Stream output)](#saveInternal-com.aspose.ms.System.IO.Stream-) | Stores document into stream. |
| [save(OutputStream output)](#save-java.io.OutputStream-) | Stores document into stream. |
| [save(String outputFileName)](#save-java.lang.String-) | Saves document into the specified file. |
| [save(System.IO.FileStream output)](#save-com.aspose.ms.System.IO.FileStream-) |  |
| [exportAnnotationsToXfdf(String fileName)](#exportAnnotationsToXfdf-java.lang.String-) | Exports all document annotations to XFDF file |
| [sendTo(DocumentDevice device, OutputStream output)](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) |  |
| [sendTo(DocumentDevice device, int fromPage, int toPage, OutputStream output)](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Sends the certain pages of the document to the document device for processing. |
| [sendTo(DocumentDevice device, String outputFileName)](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Sends the whole document to the document device for processing. |
| [sendTo(DocumentDevice device, int fromPage, int toPage, String outputFileName)](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Sends the whole document to the document device for processing. |
| [removeMetadata()](#removeMetadata--) | Removes metadata from the document. |
| [importAnnotationsFromXfdf(String fileName)](#importAnnotationsFromXfdf-java.lang.String-) | Imports annotations from XFDF file to document. |
| [validate(String outputLogFileName, int format)](#validate-java.lang.String-int-) | Validate document into the specified file. |
| [convert(String outputLogFileName, int format, int action)](#convert-java.lang.String-int-int-) | Convert document and save errors into the specified file. |
| [convert(System.Xml.XmlTextWriter xml, int format, boolean onlyValidation, int action)](#convert-com.aspose.ms.System.Xml.XmlTextWriter-int-boolean-int-) | Convert the PDF Document and log results. |
| [convertInternal(System.IO.Stream outputLogStream, int format, int action)](#convertInternal-com.aspose.ms.System.IO.Stream-int-int-) | Convert document and save errors into the specified stream. |
| [convert(OutputStream outputLogStream, int format, int action)](#convert-java.io.OutputStream-int-int-) |  |
| [flatten()](#flatten--) | Removes all fields from the document and place their values instead. |
| [getCryptoAlgorithm()](#getCryptoAlgorithm--) | Gets security settings if document is encrypted. |
| [encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)](#encrypt-java.lang.String-java.lang.String-int-int-) | Encrypts the document. |
| [changePasswords(String ownerPassword, String newUserPassword, String newOwnerPassword)](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Changes document passwords. |
| [isLinearized()](#isLinearized--) | Gets or sets a value indicating whether document is linearized. |
| [isLinearized(boolean value)](#isLinearized-boolean-) |  |
| [decrypt()](#decrypt--) | Decrypts the document. |
| [getPermissions()](#getPermissions--) | Gets permissions of the document. |
| [isEncrypted()](#isEncrypted--) | Gets encrypted status of the document. |
| [optimize()](#optimize--) | Linearize document in order to - open the first page as quickly as possible; - display next page or follow by link to the next page as quickly as possible; - display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first); - permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed. |
| [save()](#save--) | Save document incrementally (i.e. using incremental update technque). |
| [save(OutputStream outputStream, int format)](#save-java.io.OutputStream-int-) |  |
| [save(String outputFileName, SaveOptions options)](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | Saves the document with a new name setting its save options. |
| [save(OutputStream outputStream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) |  |
| [getId()](#getId--) | Gets the ID. |
| [getMetadataStream()](#getMetadataStream--) | Returns raw metadata stream |
| [updatePages()](#updatePages--) |  |
| [suppressUpdate()](#suppressUpdate--) |  |
| [resumeUpdate()](#resumeUpdate--) |  |
| [dispose()](#dispose--) | Closes all resources used by this document. |
| [getBackground()](#getBackground--) | Gets the background color of the document. |
| [setBackground(Color value)](#setBackground-com.aspose.pdf.java.awt.Color-) | Sets the background color of the document. |
| [optimizeResources()](#optimizeResources--) | Optimize resources in the document: 1. |
| [freeMemory()](#freeMemory--) | Clears memory |
| [getDefaultCopier()](#getDefaultCopier--) | Returns copier used for coping pages to this document. |
| [getNamedDestinations()](#getNamedDestinations--) | Collection of Named Destination in the document. |
| [setConvertMetadataAndCatalogOnly(boolean value)](#setConvertMetadataAndCatalogOnly-boolean-) | Gets convert parameter for pdf/ua converter (Convert only Metadata and Document Catalog if set true) |
| [setTitle(String title)](#setTitle-java.lang.String-) | Set Title for Pdf Document |
| [getEmbedStandardFonts()](#getEmbedStandardFonts--) | Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. |
| [setEmbedStandardFonts(boolean value)](#setEmbedStandardFonts-boolean-) | Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. |
### removePdfaCompliance() {#removePdfaCompliance--}
```
public abstract void removePdfaCompliance()
```


Remove pdfa compliance from the document

### getCollection() {#getCollection--}
```
public abstract Collection getCollection()
```


Gets collection of document.

**Returns:**
[Collection](../../com.aspose.pdf/collection)
### setCollection(Collection value) {#setCollection-com.aspose.pdf.Collection-}
```
public abstract void setCollection(Collection value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Collection](../../com.aspose.pdf/collection) |  |

### getEngineDoc() {#getEngineDoc--}
```
public abstract IPdfDocument getEngineDoc()
```


Instance of IPdfDocument used to access to internal document structure.

**Returns:**
[IPdfDocument](../../com.aspose.pdf.engine/ipdfdocument)
### getVersion() {#getVersion--}
```
public abstract String getVersion()
```


Gets a version of Pdf from Pdf file header.

**Returns:**
java.lang.String
### getOpenAction() {#getOpenAction--}
```
public abstract IAppointment getOpenAction()
```


Gets action performed at document opening. Example demonstrates how to get CenterWindow flag: Document document = new Document("sample.pdf"); IAppointment value = document.getOpenAction();

**Returns:**
[IAppointment](../../com.aspose.pdf/iappointment)
### setOpenAction(IAppointment value) {#setOpenAction-com.aspose.pdf.IAppointment-}
```
public abstract void setOpenAction(IAppointment value)
```


Sets action performed at document opening.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAppointment](../../com.aspose.pdf/iappointment) |  |

### getOptimizeSize() {#getOptimizeSize--}
```
public abstract boolean getOptimizeSize()
```


Gets optimization flag. When pages are added to document, equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false.

**Returns:**
boolean - boolean value
### setOptimizeSize(boolean value) {#setOptimizeSize-boolean-}
```
public abstract void setOptimizeSize(boolean value)
```


Sets optimization flag. When pages are added to document, equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideToolBar() {#getHideToolBar--}
```
public abstract boolean getHideToolBar()
```


Gets flag specifying whether toolbar should be hidden when document is active. Example demonstrates how to get HideToolBar flag: Document document = new Document("sample.pdf"); booleanvalue = document.getHideToolBar();

**Returns:**
boolean
### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public abstract void setHideToolBar(boolean value)
```


Set flag specifying whether toolbar should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideMenubar() {#getHideMenubar--}
```
public abstract boolean getHideMenubar()
```


Gets flag specifying whether menu bar should be hidden when document is active. Example demonstrates how to get HideMenubar flag: Document document = new Document("sample.pdf"); booleanvalue = document.getHideMenubar();

**Returns:**
boolean
### setHideMenubar(boolean value) {#setHideMenubar-boolean-}
```
public abstract void setHideMenubar(boolean value)
```


Sets flag specifying whether menu bar should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideWindowUI() {#getHideWindowUI--}
```
public abstract boolean getHideWindowUI()
```


Gets or sets flag specifying whether user interface elements should be hidden when document is active. Example demonstrates how to get HideWindowUI flag: Document document = new Document("sample.pdf"); booleanvalue = document.getHideWindowUI();

**Returns:**
boolean
### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public abstract void setHideWindowUI(boolean value)
```


Sets flag specifying whether user interface elements should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFitWindow() {#getFitWindow--}
```
public abstract boolean getFitWindow()
```


Gets flag specifying whether document window must be resized to fit the first displayed page. Example demonstrates how to get FitWindow flag: Document document = new Document("sample.pdf"); booleanvalue = document.getFitWindow();

**Returns:**
boolean
### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public abstract void setFitWindow(boolean value)
```


Sets flag specifying whether document window must be resized to fit the first displayed page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCenterWindow() {#getCenterWindow--}
```
public abstract boolean getCenterWindow()
```


Gets flag specifying whether position of the document's window will be centerd on the screen. Example demonstrates how to get CenterWindow flag: Document document = new Document("sample.pdf"); booleanvalue = document.getCenterWindow();

**Returns:**
boolean
### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public abstract void setCenterWindow(boolean value)
```


Sets flag specifying whether position of the document's window will be centerd on the screen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisplayDocTitle() {#getDisplayDocTitle--}
```
public abstract boolean getDisplayDocTitle()
```


Gets flag specifying whether document's window title bar should display document title. Example demonstrates how to get DisplayDocTitle flag: Document document = new Document("sample.pdf"); booleanvalue = document.getDisplayDocTitle();

**Returns:**
boolean
### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public abstract void setDisplayDocTitle(boolean value)
```


Sets flag specifying whether document's window title bar should display document title.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPages() {#getPages--}
```
public abstract PageCollection getPages()
```


Gets collection of document pages. Note that pages are numbered from 1 in collection. Example below demonstrates how to operate with the document pages: How to obtain number of pages and how to obtain rectangle of starting page of the document. Document document = new Document("sample.pdf"); Pages pages = document.Pages; Console.WriteLine("Document contains " + pages.Count); Page page = Pages[1]; Rectangle rect = page.Rect;

**Returns:**
[PageCollection](../../com.aspose.pdf/pagecollection)
### getOutlines() {#getOutlines--}
```
public abstract OutlineCollection getOutlines()
```


Gets document outlines.

**Returns:**
[OutlineCollection](../../com.aspose.pdf/outlinecollection)
### getActions() {#getActions--}
```
public abstract DocumentActionCollection getActions()
```


Gets document actions. This property is instance of DocumentActions class which allows to get/set BeforClosing, BeforSaving, etc. actions. This example demonstrates how to obtain after open action of the document: Document document = new Document("PdfWithOpenAction.pdf"); DocumentActions actions = document.Actions; com.aspose.pdf.Action afterSavingAction = actions.AfterSaving;

**Returns:**
[DocumentActionCollection](../../com.aspose.pdf/documentactioncollection)
### getForm() {#getForm--}
```
public abstract Form getForm()
```


Gets Acro Form of the document.

**Returns:**
[Form](../../com.aspose.pdf/form)
### getEmbeddedFiles() {#getEmbeddedFiles--}
```
public abstract EmbeddedFileCollection getEmbeddedFiles()
```


Gets collection of files embedded to document.

**Returns:**
[EmbeddedFileCollection](../../com.aspose.pdf/embeddedfilecollection)
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Gets reading order of text: L2R (left to right) or R2L (right to left).

**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```


Sets reading order of text: L2R (left to right) or R2L (right to left).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPageMode() {#getPageMode--}
```
public abstract int getPageMode()
```


Gets page mode, specifying how document should be displayed when opened.

**Returns:**
int
### setPageMode(int value) {#setPageMode-int-}
```
public abstract void setPageMode(int value)
```


Sets page mode, specifying how document should be displayed when opened.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public abstract int getNonFullScreenPageMode()
```


Gets page mode, specifying how to display the document on exiting full-screen mode.

**Returns:**
int
### setNonFullScreenPageMode(int value) {#setNonFullScreenPageMode-int-}
```
public abstract void setNonFullScreenPageMode(int value)
```


Sets page mode, specifying how to display the document on exiting full-screen mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPageLayout() {#getPageLayout--}
```
public abstract int getPageLayout()
```


Gets page layout which shall be used when the document is opened.

**Returns:**
int
### setPageLayout(int value) {#setPageLayout-int-}
```
public abstract void setPageLayout(int value)
```


Sets page layout which shall be used when the document is opened.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFileName() {#getFileName--}
```
public abstract String getFileName()
```


Name of the PDF file that caused this document

**Returns:**
java.lang.String
### getPageInfo() {#getPageInfo--}
```
public abstract PageInfo getPageInfo()
```


Gets the page info.(for generator only)

**Returns:**
[PageInfo](../../com.aspose.pdf/pageinfo) - The page info.
### setPageInfo(PageInfo value) {#setPageInfo-com.aspose.pdf.PageInfo-}
```
public abstract void setPageInfo(PageInfo value)
```


Sets the page info.(for generator only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageInfo](../../com.aspose.pdf/pageinfo) |  |

### getFontReplaceBehavior() {#getFontReplaceBehavior--}
```
public abstract int getFontReplaceBehavior()
```


Gets the TextEditOptions.FontReplace

**Returns:**
int
### setFontReplaceBehavior(int value) {#setFontReplaceBehavior-int-}
```
public abstract void setFontReplaceBehavior(int value)
```


Sets the TextEditOptions.FontReplace

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getInfo() {#getInfo--}
```
public abstract DocumentInfo getInfo()
```


Gets document info.

**Returns:**
[DocumentInfo](../../com.aspose.pdf/documentinfo)
### getMetadata() {#getMetadata--}
```
public abstract Metadata getMetadata()
```


Document metadata. (A PDF document may include general information, such as the document\\ufffds title, author, and creation and modification dates. Such global information about the document (as opposed to its content or structure) is called metadata and is intended to assist in cataloguing and searching for documents in external databases.)

**Returns:**
[Metadata](../../com.aspose.pdf/metadata)
### getLogicalStructure() {#getLogicalStructure--}
```
public abstract RootElement getLogicalStructure()
```


Gets logical structure of the document.

**Returns:**
[RootElement](../../com.aspose.pdf/rootelement)
### processParagraphs() {#processParagraphs--}
```
public abstract void processParagraphs()
```


Stores document into stream.

### saveInternal(System.IO.Stream output) {#saveInternal-com.aspose.ms.System.IO.Stream-}
```
public abstract void saveInternal(System.IO.Stream output)
```


Stores document into stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | com.aspose.ms.System.IO.Stream | Stream where document shell be stored. |

### save(OutputStream output) {#save-java.io.OutputStream-}
```
public abstract void save(OutputStream output)
```


Stores document into stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | java.io.OutputStream | Stream where document shell be stored. |

### save(String outputFileName) {#save-java.lang.String-}
```
public abstract void save(String outputFileName)
```


Saves document into the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | java.lang.String | Path to file where the document will be stored. |

### save(System.IO.FileStream output) {#save-com.aspose.ms.System.IO.FileStream-}
```
public abstract void save(System.IO.FileStream output)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | com.aspose.ms.System.IO.FileStream |  |

### exportAnnotationsToXfdf(String fileName) {#exportAnnotationsToXfdf-java.lang.String-}
```
public abstract void exportAnnotationsToXfdf(String fileName)
```


Exports all document annotations to XFDF file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | XFDF file name |

### sendTo(DocumentDevice device, OutputStream output) {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-}
```
public abstract void sendTo(DocumentDevice device, OutputStream output)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| device | [DocumentDevice](../../com.aspose.pdf.devices/documentdevice) |  |
| output | java.io.OutputStream |  |

### sendTo(DocumentDevice device, int fromPage, int toPage, OutputStream output) {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-}
```
public abstract void sendTo(DocumentDevice device, int fromPage, int toPage, OutputStream output)
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
public abstract void sendTo(DocumentDevice device, String outputFileName)
```


Sends the whole document to the document device for processing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| device | [DocumentDevice](../../com.aspose.pdf.devices/documentdevice) | Document device which is used to process the document. |
| outputFileName | java.lang.String | Output file name with the results of processing. |

### sendTo(DocumentDevice device, int fromPage, int toPage, String outputFileName) {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-}
```
public abstract void sendTo(DocumentDevice device, int fromPage, int toPage, String outputFileName)
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
public abstract void removeMetadata()
```


Removes metadata from the document.

### importAnnotationsFromXfdf(String fileName) {#importAnnotationsFromXfdf-java.lang.String-}
```
public abstract void importAnnotationsFromXfdf(String fileName)
```


Imports annotations from XFDF file to document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | XFDF file name |

### validate(String outputLogFileName, int format) {#validate-java.lang.String-int-}
```
public abstract boolean validate(String outputLogFileName, int format)
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
public abstract boolean convert(String outputLogFileName, int format, int action)
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
### convert(System.Xml.XmlTextWriter xml, int format, boolean onlyValidation, int action) {#convert-com.aspose.ms.System.Xml.XmlTextWriter-int-boolean-int-}
```
public abstract boolean convert(System.Xml.XmlTextWriter xml, int format, boolean onlyValidation, int action)
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
### convertInternal(System.IO.Stream outputLogStream, int format, int action) {#convertInternal-com.aspose.ms.System.IO.Stream-int-int-}
```
public abstract boolean convertInternal(System.IO.Stream outputLogStream, int format, int action)
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
public abstract boolean convert(OutputStream outputLogStream, int format, int action)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | java.io.OutputStream |  |
| format | int |  |
| action | int |  |

**Returns:**
boolean
### flatten() {#flatten--}
```
public abstract void flatten()
```


Removes all fields from the document and place their values instead.

### getCryptoAlgorithm() {#getCryptoAlgorithm--}
```
public abstract int getCryptoAlgorithm()
```


Gets security settings if document is encrypted. If document is not encrypted then corresponding exception will be raised in .net 1.1 or CryptoAlgorithm will be null for other .net versions.

**Returns:**
int
### encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm) {#encrypt-java.lang.String-java.lang.String-int-int-}
```
public abstract void encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)
```


Encrypts the document. Call then Save to get encrypted version of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | java.lang.String | User password. |
| ownerPassword | java.lang.String | Owner password. |
| permissions | int | Document permissions, see  Permissions  for details. |
| cryptoAlgorithm | int | Cryptographic algorithm, see  CryptoAlgorithm  for details. |

### changePasswords(String ownerPassword, String newUserPassword, String newOwnerPassword) {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
```
public abstract void changePasswords(String ownerPassword, String newUserPassword, String newOwnerPassword)
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
public abstract boolean isLinearized()
```


Gets or sets a value indicating whether document is linearized.

**Returns:**
boolean
### isLinearized(boolean value) {#isLinearized-boolean-}
```
public abstract void isLinearized(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### decrypt() {#decrypt--}
```
public abstract void decrypt()
```


Decrypts the document. Call then Save to obtain decrypted version of the document.

### getPermissions() {#getPermissions--}
```
public abstract int getPermissions()
```


Gets permissions of the document.

**Returns:**
int
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


Gets encrypted status of the document. True if document is encrypted.

**Returns:**
boolean
### optimize() {#optimize--}
```
public abstract void optimize()
```


Linearize document in order to - open the first page as quickly as possible; - display next page or follow by link to the next page as quickly as possible; - display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first); - permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed. Invoking this method doesn't actually saves the document. On the contrary the document only is prepared to have optimized structure, call then Save to get optimized document.

### save() {#save--}
```
public abstract void save()
```


Save document incrementally (i.e. using incremental update technque).

--------------------

In order to save document incremetally we should open the document file for writing. Therefore Document must be initialized with writable stream like in the next code snippet: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // make some changes and save the document incrementally doc.Save();

### save(OutputStream outputStream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream outputStream, int format)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream |  |
| format | int |  |

### save(String outputFileName, SaveOptions options) {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
```
public abstract void save(String outputFileName, SaveOptions options)
```


Saves the document with a new name setting its save options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | java.lang.String | Path to file where the document will be stored. |
| options | [SaveOptions](../../com.aspose.pdf/saveoptions) | Save options. |

### save(OutputStream outputStream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
```
public abstract void save(OutputStream outputStream, SaveOptions options)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream |  |
| options | [SaveOptions](../../com.aspose.pdf/saveoptions) |  |

### getId() {#getId--}
```
public abstract Id getId()
```


Gets the ID.

**Returns:**
[Id](../../com.aspose.pdf/id)
### getMetadataStream() {#getMetadataStream--}
```
public abstract IPdfStreamAccessor getMetadataStream()
```


Returns raw metadata stream

**Returns:**
[IPdfStreamAccessor](../../com.aspose.pdf.engine.data.types/ipdfstreamaccessor) - 
### updatePages() {#updatePages--}
```
public abstract void updatePages()
```




### suppressUpdate() {#suppressUpdate--}
```
public abstract void suppressUpdate()
```




### resumeUpdate() {#resumeUpdate--}
```
public abstract void resumeUpdate()
```




### dispose() {#dispose--}
```
public abstract void dispose()
```


Closes all resources used by this document.

### getBackground() {#getBackground--}
```
public abstract Color getBackground()
```


Gets the background color of the document.

**Returns:**
[Color](../../com.aspose.pdf.java.awt/color)
### setBackground(Color value) {#setBackground-com.aspose.pdf.java.awt.Color-}
```
public abstract void setBackground(Color value)
```


Sets the background color of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf.java.awt/color) |  |

### optimizeResources() {#optimizeResources--}
```
public abstract void optimizeResources()
```


Optimize resources in the document: 1. Resources which are not used on the document pages are removed; 2. Equal resources are joined into one object; 3. Unused objects are deleted.

### freeMemory() {#freeMemory--}
```
public abstract void freeMemory()
```


Clears memory

### getDefaultCopier() {#getDefaultCopier--}
```
public abstract Copier getDefaultCopier()
```


Returns copier used for coping pages to this document.

**Returns:**
[Copier](../../com.aspose.pdf/copier)
### getNamedDestinations() {#getNamedDestinations--}
```
public abstract NamedDestinationCollection getNamedDestinations()
```


Collection of Named Destination in the document.

**Returns:**
[NamedDestinationCollection](../../com.aspose.pdf.nameddestinations/nameddestinationcollection) - NamedDestinationCollection instance
### setConvertMetadataAndCatalogOnly(boolean value) {#setConvertMetadataAndCatalogOnly-boolean-}
```
public abstract void setConvertMetadataAndCatalogOnly(boolean value)
```


Gets convert parameter for pdf/ua converter (Convert only Metadata and Document Catalog if set true)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setTitle(String title) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String title)
```


Set Title for Pdf Document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| title | java.lang.String | Document's title |

### getEmbedStandardFonts() {#getEmbedStandardFonts--}
```
public abstract boolean getEmbedStandardFonts()
```


Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. All PDF fonts can be embedded into document simply via setting of flag IsEmbedded into true, but PDF standard Type1 fonts is an exception from this rule. Standard Type1 font embedding requires much time, so to embed these fonts it's necessary not only set flag IsEmbedded into true for specified font but also set an additiona flag on document's level - EmbedStandardFonts = true; This property can be set only one time for all fonts. By default false.

**Returns:**
boolean - boolean value
### setEmbedStandardFonts(boolean value) {#setEmbedStandardFonts-boolean-}
```
public abstract void setEmbedStandardFonts(boolean value)
```


Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. All PDF fonts can be embedded into document simply via setting of flag IsEmbedded into true, but PDF standard Type1 fonts is an exception from this rule. Standard Type1 font embedding requires much time, so to embed these fonts it's necessary not only set flag IsEmbedded into true for specified font but also set an additiona flag on document's level - EmbedStandardFonts = true; This property can be set only one time for all fonts. By default false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

