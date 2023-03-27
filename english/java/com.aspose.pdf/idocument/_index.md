---
title: IDocument
second_title: Aspose.PDF for Java API Reference
description: interface representing PDF document
type: docs
weight: 431
url: /java/com.aspose.pdf/idocument/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public interface IDocument extends System.IDisposable, Closeable
```

interface representing PDF document
## Methods

| Method | Description |
| --- | --- |
| [isPdfaCompliant()](#isPdfaCompliant--) |  |
| [isPdfUaCompliant()](#isPdfUaCompliant--) | Gets the is document pdfua compliant. |
| [getDestinations()](#getDestinations--) | Gets the collection of destinations. |
| [getPdfFormat()](#getPdfFormat--) |  |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Many operations with font can't be executed if these operations are prohibited by license of this font. |
| [setDisableFontLicenseVerifications(boolean value)](#setDisableFontLicenseVerifications-boolean-) | Many operations with font can't be executed if these operations are prohibited by license of this font. |
| [removePdfaCompliance()](#removePdfaCompliance--) | Remove pdfa compliance from the document |
| [getCollection()](#getCollection--) | Gets collection of document. |
| [setCollection(Collection value)](#setCollection-com.aspose.pdf.Collection-) | Sets collection of document. |
| [getEngineDoc()](#getEngineDoc--) | Instance of IPdfDocument used to access to internal document structure. |
| [getVersion()](#getVersion--) | Gets a version of Pdf from Pdf file header. |
| [getOpenAction()](#getOpenAction--) | Gets action performed at document opening. |
| [setOpenAction(IAppointment value)](#setOpenAction-com.aspose.pdf.IAppointment-) | Sets action performed at document opening. |
| [getOptimizeSize()](#getOptimizeSize--) | Gets optimization flag. |
| [setOptimizeSize(boolean value)](#setOptimizeSize-boolean-) | Sets optimization flag. |
| [getIgnoreCorruptedObjects()](#getIgnoreCorruptedObjects--) | Gets or sets flag of ignoring errors in source files. |
| [setIgnoreCorruptedObjects(boolean value)](#setIgnoreCorruptedObjects-boolean-) |  |
| [getCatalogValue(String key)](#getCatalogValue-java.lang.String-) | Returns item value from catalog dictionary. |
| [isHideToolBar()](#isHideToolBar--) | Gets flag specifying whether toolbar should be hidden when document is active. |
| [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | Set flag specifying whether toolbar should be hidden when document is active. |
| [isHideMenubar()](#isHideMenubar--) | Gets flag specifying whether menu bar should be hidden when document is active. |
| [setHideMenubar(boolean value)](#setHideMenubar-boolean-) | Sets flag specifying whether menu bar should be hidden when document is active. |
| [isHideWindowUI()](#isHideWindowUI--) | Gets or sets flag specifying whether user interface elements should be hidden when document is active. |
| [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | Sets flag specifying whether user interface elements should be hidden when document is active. |
| [isFitWindow()](#isFitWindow--) | Gets flag specifying whether document window must be resized to fit the first displayed page. |
| [setFitWindow(boolean value)](#setFitWindow-boolean-) | Sets flag specifying whether document window must be resized to fit the first displayed page. |
| [isCenterWindow()](#isCenterWindow--) | Gets flag specifying whether position of the document's window will be centerd on the screen. |
| [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | Sets flag specifying whether position of the document's window will be centerd on the screen. |
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
| [setPageMode(int value)](#setPageMode-int-) | Sets page mode, specifying how document should be displayed when opened. |
| [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | Gets page mode, specifying how to display the document on exiting full-screen mode. |
| [setNonFullScreenPageMode(int value)](#setNonFullScreenPageMode-int-) | Sets page mode, specifying how to display the document on exiting full-screen mode. |
| [getPageLayout()](#getPageLayout--) | Gets page layout which shall be used when the document is opened. |
| [setPageLayout(int value)](#setPageLayout-int-) | Sets page layout which shall be used when the document is opened. |
| [getDuplex()](#getDuplex--) | Gets or sets print duplex mode handling option to use when printing the file from the print dialog. |
| [setDuplex(int value)](#setDuplex-int-) | Gets or sets print duplex mode handling option to use when printing the file from the print dialog. |
| [getFileName()](#getFileName--) | Name of the PDF file that caused this document |
| [setLayersAdded(boolean value)](#setLayersAdded-boolean-) | Set LayersAdded value |
| [getPageInfo()](#getPageInfo--) | Gets the page info. |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | Sets the page info. |
| [getEnableSignatureSanitization()](#getEnableSignatureSanitization--) | Gets or sets flag to manage signature fields sanitization. |
| [setEnableSignatureSanitization(boolean value)](#setEnableSignatureSanitization-boolean-) | Gets or sets flag to manage signature fields sanitization. |
| [getInfo()](#getInfo--) | Gets document info. |
| [getMetadata()](#getMetadata--) | Document metadata. |
| [getLogicalStructure()](#getLogicalStructure--) | Gets logical structure of the document. |
| [processParagraphs()](#processParagraphs--) | Stores document into stream. |
| [save(OutputStream output)](#save-java.io.OutputStream-) | Stores document into stream. |
| [saveIncrementally(OutputStream output)](#saveIncrementally-java.io.OutputStream-) | Saves incrementally the PDF Document to the specified stream. |
| [saveIncrementally(System.IO.Stream output)](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Saves incrementally the PDF Document to the specified stream. |
| [save(String outputFileName)](#save-java.lang.String-) | Saves document into the specified file. |
| [exportAnnotationsToXfdf(String fileName)](#exportAnnotationsToXfdf-java.lang.String-) | Exports all document annotations to XFDF file |
| [sendTo(DocumentDevice device, OutputStream output)](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Sends the whole document to the document device for processing. |
| [sendTo(DocumentDevice device, int fromPage, int toPage, OutputStream output)](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Sends the certain pages of the document to the document device for processing. |
| [sendTo(DocumentDevice device, String outputFileName)](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Sends the whole document to the document device for processing. |
| [sendTo(DocumentDevice device, int fromPage, int toPage, String outputFileName)](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Sends the whole document to the document device for processing. |
| [removeMetadata()](#removeMetadata--) | Removes metadata from the document. |
| [importAnnotationsFromXfdf(String fileName)](#importAnnotationsFromXfdf-java.lang.String-) | Imports annotations from XFDF file to document. |
| [validate(String outputLogFileName, PdfFormat format)](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Validate document into the specified file. |
| [validate(OutputStream outputLogStream, PdfFormat format)](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Validate document into the specified file. |
| [convert(String outputLogFileName, PdfFormat format, int action, int transparencyAction)](#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-int-) | Convert document and save errors into the specified file. |
| [convert(String outputLogFileName, PdfFormat format, int action)](#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-) | Convert document and save errors into the specified file. |
| [convert(PdfFormatConversionOptions options)](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Convert document using specified conversion options |
| [convert(Document.CallBackGetHocr callback)](#convert-com.aspose.pdf.Document.CallBackGetHocr-) | Convert document to searchable document. |
| [convertWithSkippingErrors(Document.CallBackGetHocr callback)](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocr-) | Convert document to searchable document and skip errors of hochr that can not be converted. |
| [convert(Document.CallBackGetHocr callback, boolean isTestVisible)](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-) | Convert document and save errors into the specified file. |
| [convert(Document.CallBackGetHocr callback, boolean isTestVisible, boolean isOriginalImage)](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-) | Convert document and save errors into the specified file. |
| [convert(OutputStream outputLogStream, PdfFormat format, int action)](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-) |  |
| [flatten()](#flatten--) | Removes all fields from the document and place their values instead. |
| [flatten(Form.FlattenSettings flattenSettings)](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Removes all fields from the document and place their values instead. |
| [getCryptoAlgorithm()](#getCryptoAlgorithm--) | Gets security settings if document is encrypted. |
| [encrypt(String userPassword, String ownerPassword, DocumentPrivilege privileges, CryptoAlgorithm cryptoAlgorithm, boolean usePdf20)](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Encrypts the document. |
| [encrypt(String userPassword, String ownerPassword, int permissions, CryptoAlgorithm cryptoAlgorithm)](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Encrypts the document. |
| [encrypt(String userPassword, String ownerPassword, int permissions, CryptoAlgorithm cryptoAlgorithm, boolean usePdf20)](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Encrypts the document. |
| [changePasswords(String ownerPassword, String newUserPassword, String newOwnerPassword)](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Changes document passwords. |
| [isLinearized()](#isLinearized--) | Gets or sets a value indicating whether document is linearized. |
| [setLinearized(boolean value)](#setLinearized-boolean-) | Sets a value indicating whether document is linearized. |
| [decrypt()](#decrypt--) | Decrypts the document. |
| [getPermissions()](#getPermissions--) | Gets permissions of the document. |
| [isEncrypted()](#isEncrypted--) | Gets encrypted status of the document. |
| [optimize()](#optimize--) | Linearize document in order to - open the first page as quickly as possible; - display next page or follow by link to the next page as quickly as possible; - display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first); - permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed. |
| [save()](#save--) | Save document incrementally (i.e. using incremental update technique). |
| [saveIncrementally(String outputFileName)](#saveIncrementally-java.lang.String-) | Saves incrementally the PDF Document to the specified stream. |
| [save(OutputStream outputStream, SaveFormat format)](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | Save document |
| [save(String outputFileName, SaveOptions options)](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | Saves the document with a new name setting its save options. |
| [save(OutputStream outputStream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Saves the document with a new name setting its save options. |
| [getId()](#getId--) | Gets the ID. |
| [getMetadataStream()](#getMetadataStream--) | Returns raw metadata stream |
| [updatePages()](#updatePages--) | updatePages |
| [suppressUpdate()](#suppressUpdate--) | suppressUpdate |
| [resumeUpdate()](#resumeUpdate--) | resumeUpdate |
| [dispose()](#dispose--) | Closes all resources used by this document. |
| [close()](#close--) | Closes all resources used by this document. |
| [getBackground()](#getBackground--) | Gets the background color of the document. |
| [setBackground(Color value)](#setBackground-java.awt.Color-) | Sets the background color of the document. |
| [getDefaultCopier()](#getDefaultCopier--) | Returns copier used for coping pages to this document. |
| [optimizeResources()](#optimizeResources--) | Optimize resources in the document: 1. |
| [optimizeResources(OptimizationOptions strategy)](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Optimize resources in the document according to defined optimization strategy. |
| [getPageLabels()](#getPageLabels--) | Gets page labels in the document. |
| [freeMemory()](#freeMemory--) | Clears memory |
| [afterImport()](#afterImport--) | Enumerate all registered annotations and call AfterImport for each of them. |
| [saveXml(String file)](#saveXml-java.lang.String-) | Save document to XML. |
| [bindXml(String xmlFile, String xslFile)](#bindXml-java.lang.String-java.lang.String-) | Bind xml/xsl to document |
| [getObjectById(String id)](#getObjectById-java.lang.String-) | Gets a object with specified ID in the document. |
| [bindXml(InputStream stream)](#bindXml-java.io.InputStream-) | Bind xml to document |
| [bindXml(String file)](#bindXml-java.lang.String-) | Bind xml to document |
| [repair()](#repair--) | Repairs broken document. |
| [getEmbedStandardFonts()](#getEmbedStandardFonts--) | Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. |
| [setEmbedStandardFonts(boolean value)](#setEmbedStandardFonts-boolean-) | Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. |
| [convertInternal(System.IO.Stream log, PdfFormat _convertTo, int none)](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-int-) | Internal method |
| [getXmpMetadata(OutputStream stream)](#getXmpMetadata-java.io.OutputStream-) | Get XMP metadata from document. |
| [setXmpMetadata(InputStream stream)](#setXmpMetadata-java.io.InputStream-) | Set XMP metadata of document. |
| [isAbsentFontTryToSubstitute()](#isAbsentFontTryToSubstitute--) | Notification about missing fonts when processing documents |
| [setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)](#setAbsentFontTryToSubstitute-boolean-) | Setting flag for set program determined font in case of absence font. |
| [isXrefGapsAllowed()](#isXrefGapsAllowed--) | Gets or sets the is document pdfa compliant. |
| [setXrefGapsAllowed(boolean value)](#setXrefGapsAllowed-boolean-) | Gets or sets the is document pdfa compliant. |
| [getNamedDestinations()](#getNamedDestinations--) | Collection of Named Destination in the document. |
| [check(boolean doRepair)](#check-boolean-) | Validates document. |
| [removePdfUaCompliance()](#removePdfUaCompliance--) | Remove pdfUa compliance from the document |
| [setConvertMetadataAndCatalogOnly(boolean value)](#setConvertMetadataAndCatalogOnly-boolean-) | Gets convert parameter for pdf/ua converter (Convert only Metadata and Document Catalog if set true) |
| [setTitle(String title)](#setTitle-java.lang.String-) | Set Title for Pdf Document |
| [isManualDisposeEnabled()](#isManualDisposeEnabled--) | By default method save close internal streams and release memory resources. |
| [setManualDisposeEnabled(boolean manualDisposeEnabled)](#setManualDisposeEnabled-boolean-) | By default method save closes internal streams and release memory resources. |
| [pageNodesToBalancedTree()](#pageNodesToBalancedTree--) | Organizes page tree nodes in a document into a balanced tree. |
| [pageNodesToBalancedTree(byte nodesNumInSubtrees)](#pageNodesToBalancedTree-byte-) | Organizes page tree nodes in a document into a balanced tree. |
### isPdfaCompliant() {#isPdfaCompliant--}
```
public abstract boolean isPdfaCompliant()
```




**Returns:**
boolean
### isPdfUaCompliant() {#isPdfUaCompliant--}
```
public abstract boolean isPdfUaCompliant()
```


Gets the is document pdfua compliant.

**Returns:**
boolean - boolean value
### getDestinations() {#getDestinations--}
```
public abstract DestinationCollection getDestinations()
```


Gets the collection of destinations.

**Returns:**
[DestinationCollection](../../com.aspose.pdf/destinationcollection) - DestinationCollection object
### getPdfFormat() {#getPdfFormat--}
```
public abstract PdfFormat getPdfFormat()
```




**Returns:**
[PdfFormat](../../com.aspose.pdf/pdfformat) - PdfFormat element
### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public abstract boolean isDisableFontLicenseVerifications()
```


Many operations with font can't be executed if these operations are prohibited by license of this font. For example some font can't be embedded into PDF document if license rules disable embedding for this font. This flag is used to disable any license restrictions for all fonts in current PDF document. Be careful when using this flag. When it is set it means that person who sets this flag, takes all responsibility of possible license/law violations on himself. So He takes it on it's own risk. It's strongly recommended to use this flag only when you are fully confident that you are not breaking the copyright law.

**Returns:**
boolean - boolean value By default false.
### setDisableFontLicenseVerifications(boolean value) {#setDisableFontLicenseVerifications-boolean-}
```
public abstract void setDisableFontLicenseVerifications(boolean value)
```


Many operations with font can't be executed if these operations are prohibited by license of this font. For example some font can't be embedded into PDF document if license rules disable embedding for this font. This flag is used to disable any license restrictions for all fonts in current PDF document. Be careful when using this flag. When it is set it means that person who sets this flag, takes all responsibility of possible license/law violations on himself. So He takes it on it's own risk. It's strongly recommended to use this flag only when you are fully confident that you are not breaking the copyright law.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value By default false. |

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
[Collection](../../com.aspose.pdf/collection) - Collection object
### setCollection(Collection value) {#setCollection-com.aspose.pdf.Collection-}
```
public abstract void setCollection(Collection value)
```


Sets collection of document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Collection](../../com.aspose.pdf/collection) | Collection object |

### getEngineDoc() {#getEngineDoc--}
```
public abstract IPdfDocument getEngineDoc()
```


Instance of IPdfDocument used to access to internal document structure. Internal only

**Returns:**
[IPdfDocument](../../com.aspose.pdf.engine/ipdfdocument) - IPdfDocument object
### getVersion() {#getVersion--}
```
public abstract String getVersion()
```


Gets a version of Pdf from Pdf file header.

**Returns:**
java.lang.String - String object
### getOpenAction() {#getOpenAction--}
```
public abstract IAppointment getOpenAction()
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
public abstract void setOpenAction(IAppointment value)
```


Sets action performed at document opening.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | IAppointment object |

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
| value | boolean | boolean value |

### getIgnoreCorruptedObjects() {#getIgnoreCorruptedObjects--}
```
public abstract boolean getIgnoreCorruptedObjects()
```


Gets or sets flag of ignoring errors in source files. When pages from source document copied into destination document, copying process is stopped with exception if some objects in source files are corrupted when this flag is false. example: dest.Pages.Add(src.Pages); If this flag is set to true then corrupted objects will be replaced with empty values. By default: true.

**Returns:**
boolean - boolean value
### setIgnoreCorruptedObjects(boolean value) {#setIgnoreCorruptedObjects-boolean-}
```
public abstract void setIgnoreCorruptedObjects(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCatalogValue(String key) {#getCatalogValue-java.lang.String-}
```
public abstract Object getCatalogValue(String key)
```


Returns item value from catalog dictionary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key of item. |

**Returns:**
java.lang.Object - Item value - if key was successfully found; otherwise, null.
### isHideToolBar() {#isHideToolBar--}
```
public abstract boolean isHideToolBar()
```


Gets flag specifying whether toolbar should be hidden when document is active.

--------------------

```
Example demonstrates how to get HideToolBar flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isHideToolBar();
```

**Returns:**
boolean - boolean value
### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public abstract void setHideToolBar(boolean value)
```


Set flag specifying whether toolbar should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isHideMenubar() {#isHideMenubar--}
```
public abstract boolean isHideMenubar()
```


Gets flag specifying whether menu bar should be hidden when document is active.

--------------------

```
Example demonstrates how to get HideMenubar flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isHideMenubar();
```

**Returns:**
boolean - boolean value
### setHideMenubar(boolean value) {#setHideMenubar-boolean-}
```
public abstract void setHideMenubar(boolean value)
```


Sets flag specifying whether menu bar should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isHideWindowUI() {#isHideWindowUI--}
```
public abstract boolean isHideWindowUI()
```


Gets or sets flag specifying whether user interface elements should be hidden when document is active.

--------------------

```
Example demonstrates how to get HideWindowUI flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isHideWindowUI();
```

**Returns:**
boolean - boolean value
### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public abstract void setHideWindowUI(boolean value)
```


Sets flag specifying whether user interface elements should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isFitWindow() {#isFitWindow--}
```
public abstract boolean isFitWindow()
```


Gets flag specifying whether document window must be resized to fit the first displayed page.

--------------------

```
Example demonstrates how to get FitWindow flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isFitWindow();
```

**Returns:**
boolean - boolean value
### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public abstract void setFitWindow(boolean value)
```


Sets flag specifying whether document window must be resized to fit the first displayed page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isCenterWindow() {#isCenterWindow--}
```
public abstract boolean isCenterWindow()
```


Gets flag specifying whether position of the document's window will be centerd on the screen.

--------------------

```
Example demonstrates how to get CenterWindow flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isCenterWindow();
```

**Returns:**
boolean - boolean value
### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public abstract void setCenterWindow(boolean value)
```


Sets flag specifying whether position of the document's window will be centerd on the screen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isDisplayDocTitle() {#isDisplayDocTitle--}
```
public abstract boolean isDisplayDocTitle()
```


Gets flag specifying whether document's window title bar should display document title.

--------------------

```
Example demonstrates how to get DisplayDocTitle flag:

 Document document = new Document("sample.pdf");
 boolean value = document.isDisplayDocTitle();
```

**Returns:**
boolean - boolean value
### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public abstract void setDisplayDocTitle(boolean value)
```


Sets flag specifying whether document's window title bar should display document title.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getPages() {#getPages--}
```
public abstract PageCollection getPages()
```


Gets collection of document pages. Note that pages are numbered from 1 in collection.

--------------------

```
Example below demonstrates how to operate with the document pages:
 How to obtain number of pages and how to obtain rectangle of starting page of the document.

 Document document = new Document("sample.pdf");
 Pages pages = document.getPages();
 System.out.println("Document contains " + pages.size());
 Page page = pages.get_Item(1);
 Rectangle rect = page.getRect();
```

**Returns:**
[PageCollection](../../com.aspose.pdf/pagecollection) - boolean value
### getOutlines() {#getOutlines--}
```
public abstract OutlineCollection getOutlines()
```


Gets document outlines.

**Returns:**
[OutlineCollection](../../com.aspose.pdf/outlinecollection) - OutlineCollection object
### getActions() {#getActions--}
```
public abstract DocumentActionCollection getActions()
```


Gets document actions. This property is instance of DocumentActions class which allows to get/set BeforClosing, BeforSaving, etc. actions.

--------------------

```
This example demonstrates how to obtain after open action of the document:

 Document document = new Document("PdfWithOpenAction.pdf");
 DocumentActions actions = document.getActions();
 com.aspose.pdf.Action afterSavingAction = actions.getAfterSaving();
```

**Returns:**
[DocumentActionCollection](../../com.aspose.pdf/documentactioncollection) - DocumentActionCollection object
### getForm() {#getForm--}
```
public abstract Form getForm()
```


Gets Acro Form of the document.

**Returns:**
[Form](../../com.aspose.pdf/form) - Form object
### getEmbeddedFiles() {#getEmbeddedFiles--}
```
public abstract EmbeddedFileCollection getEmbeddedFiles()
```


Gets collection of files embedded to document.

**Returns:**
[EmbeddedFileCollection](../../com.aspose.pdf/embeddedfilecollection) - EmbeddedFileCollection object
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Gets reading order of text: L2R (left to right) or R2L (right to left).

**Returns:**
int - Direction element
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```


Sets reading order of text: L2R (left to right) or R2L (right to left).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | Direction element |

### getPageMode() {#getPageMode--}
```
public abstract int getPageMode()
```


Gets page mode, specifying how document should be displayed when opened.

**Returns:**
int - PageMode element
### setPageMode(int value) {#setPageMode-int-}
```
public abstract void setPageMode(int value)
```


Sets page mode, specifying how document should be displayed when opened.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | PageMode element |

### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public abstract int getNonFullScreenPageMode()
```


Gets page mode, specifying how to display the document on exiting full-screen mode.

**Returns:**
int - PageMode element
### setNonFullScreenPageMode(int value) {#setNonFullScreenPageMode-int-}
```
public abstract void setNonFullScreenPageMode(int value)
```


Sets page mode, specifying how to display the document on exiting full-screen mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | PageMode element |

### getPageLayout() {#getPageLayout--}
```
public abstract int getPageLayout()
```


Gets page layout which shall be used when the document is opened.

**Returns:**
int - PageLayout element
### setPageLayout(int value) {#setPageLayout-int-}
```
public abstract void setPageLayout(int value)
```


Sets page layout which shall be used when the document is opened.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | PageLayout element |

### getDuplex() {#getDuplex--}
```
public abstract int getDuplex()
```


Gets or sets print duplex mode handling option to use when printing the file from the print dialog.

**Returns:**
int - PrintDuplex element
### setDuplex(int value) {#setDuplex-int-}
```
public abstract void setDuplex(int value)
```


Gets or sets print duplex mode handling option to use when printing the file from the print dialog.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | PrintDuplex element |

### getFileName() {#getFileName--}
```
public abstract String getFileName()
```


Name of the PDF file that caused this document

**Returns:**
java.lang.String - String object
### setLayersAdded(boolean value) {#setLayersAdded-boolean-}
```
public abstract void setLayersAdded(boolean value)
```


Set LayersAdded value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getPageInfo() {#getPageInfo--}
```
public abstract PageInfo getPageInfo()
```


Gets the page info.(for generator only, not filled in when reading document)

**Returns:**
[PageInfo](../../com.aspose.pdf/pageinfo) - The page info.
### setPageInfo(PageInfo value) {#setPageInfo-com.aspose.pdf.PageInfo-}
```
public abstract void setPageInfo(PageInfo value)
```


Sets the page info.(for generator only, not filled in when reading document)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageInfo](../../com.aspose.pdf/pageinfo) | PageInfo object |

### getEnableSignatureSanitization() {#getEnableSignatureSanitization--}
```
public abstract boolean getEnableSignatureSanitization()
```


Gets or sets flag to manage signature fields sanitization. Enabled by default.

**Returns:**
boolean - boolean value
### setEnableSignatureSanitization(boolean value) {#setEnableSignatureSanitization-boolean-}
```
public abstract void setEnableSignatureSanitization(boolean value)
```


Gets or sets flag to manage signature fields sanitization. Enabled by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getInfo() {#getInfo--}
```
public abstract DocumentInfo getInfo()
```


Gets document info.

**Returns:**
[DocumentInfo](../../com.aspose.pdf/documentinfo) - DocumentInfo object
### getMetadata() {#getMetadata--}
```
public abstract Metadata getMetadata()
```


Document metadata. (A PDF document may include general information, such as the document's title, author, and creation and modification dates. Such global information about the document (as opposed to its content or structure) is called metadata and is intended to assist in cataloguing and searching for documents in external databases.)

**Returns:**
[Metadata](../../com.aspose.pdf/metadata) - Metadata object
### getLogicalStructure() {#getLogicalStructure--}
```
public abstract RootElement getLogicalStructure()
```


Gets logical structure of the document.

**Returns:**
[RootElement](../../com.aspose.pdf/rootelement) - RootElement object
### processParagraphs() {#processParagraphs--}
```
public abstract void processParagraphs()
```


Stores document into stream.

### save(OutputStream output) {#save-java.io.OutputStream-}
```
public abstract void save(OutputStream output)
```


Stores document into stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | java.io.OutputStream | Stream where document shell be stored. |

### saveIncrementally(OutputStream output) {#saveIncrementally-java.io.OutputStream-}
```
public abstract void saveIncrementally(OutputStream output)
```


Saves incrementally the PDF Document to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | java.io.OutputStream | OutputStream object |

### saveIncrementally(System.IO.Stream output) {#saveIncrementally-com.aspose.ms.System.IO.Stream-}
```
public abstract void saveIncrementally(System.IO.Stream output)
```


Saves incrementally the PDF Document to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | com.aspose.ms.System.IO.Stream | OutputStream object |

### save(String outputFileName) {#save-java.lang.String-}
```
public abstract void save(String outputFileName)
```


Saves document into the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | java.lang.String | Path to file where the document will be stored. |

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


Sends the whole document to the document device for processing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| device | [DocumentDevice](../../com.aspose.pdf.devices/documentdevice) | DocumentDevice object |
| output | java.io.OutputStream | OutputStream object |

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

### validate(String outputLogFileName, PdfFormat format) {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
```
public abstract boolean validate(String outputLogFileName, PdfFormat format)
```


Validate document into the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | java.lang.String | Path to file where the comments will be stored. |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | Pdf format. |

**Returns:**
boolean - boolean value
### validate(OutputStream outputLogStream, PdfFormat format) {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
```
public abstract boolean validate(OutputStream outputLogStream, PdfFormat format)
```


Validate document into the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | java.io.OutputStream | Stream where the comments will be stored. |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | Pdf format. |

**Returns:**
boolean - The operation result
### convert(String outputLogFileName, PdfFormat format, int action, int transparencyAction) {#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-int-}
```
public abstract boolean convert(String outputLogFileName, PdfFormat format, int action, int transparencyAction)
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
### convert(String outputLogFileName, PdfFormat format, int action) {#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-}
```
public abstract boolean convert(String outputLogFileName, PdfFormat format, int action)
```


Convert document and save errors into the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | java.lang.String | Path to file where the comments will be stored. |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | Pdf format. |
| action | int | Action for objects that can not be converted |

**Returns:**
boolean - The operation result
### convert(PdfFormatConversionOptions options) {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
```
public abstract boolean convert(PdfFormatConversionOptions options)
```


Convert document using specified conversion options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [PdfFormatConversionOptions](../../com.aspose.pdf/pdfformatconversionoptions) | set of options for convert PDF document |

**Returns:**
boolean - The operation result
### convert(Document.CallBackGetHocr callback) {#convert-com.aspose.pdf.Document.CallBackGetHocr-}
```
public abstract boolean convert(Document.CallBackGetHocr callback)
```


Convert document to searchable document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | [CallBackGetHocr](../../com.aspose.pdf/callbackgethocr) | The call back procedure for hocr recognize. |

**Returns:**
boolean - boolean value
### convertWithSkippingErrors(Document.CallBackGetHocr callback) {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocr-}
```
public abstract boolean convertWithSkippingErrors(Document.CallBackGetHocr callback)
```


Convert document to searchable document and skip errors of hochr that can not be converted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | [CallBackGetHocr](../../com.aspose.pdf/callbackgethocr) | The call back procedure for hocr recognize. |

**Returns:**
boolean - boolean value
### convert(Document.CallBackGetHocr callback, boolean isTestVisible) {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-}
```
public abstract boolean convert(Document.CallBackGetHocr callback, boolean isTestVisible)
```


Convert document and save errors into the specified file.

This is allow to show/hide searchable text on page. Default value is FALSE.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | [CallBackGetHocr](../../com.aspose.pdf/callbackgethocr) | Action for objects that can not be converted |
| isTestVisible | boolean | boolean value |

**Returns:**
boolean - The operation result
### convert(Document.CallBackGetHocr callback, boolean isTestVisible, boolean isOriginalImage) {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-}
```
public abstract boolean convert(Document.CallBackGetHocr callback, boolean isTestVisible, boolean isOriginalImage)
```


Convert document and save errors into the specified file.

This is allow to show/hide searchable text on page. Default value is FALSE. This is allow to getting original image from pdf. Default value is FALSE.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | [CallBackGetHocr](../../com.aspose.pdf/callbackgethocr) | Action for objects that can not be converted |
| isTestVisible | boolean | boolean value |
| isOriginalImage | boolean | boolean value |

**Returns:**
boolean - The operation result
### convert(OutputStream outputLogStream, PdfFormat format, int action) {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-}
```
public abstract boolean convert(OutputStream outputLogStream, PdfFormat format, int action)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | java.io.OutputStream |  |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) |  |
| action | int |  |

**Returns:**
boolean
### flatten() {#flatten--}
```
public abstract void flatten()
```


Removes all fields from the document and place their values instead.

### flatten(Form.FlattenSettings flattenSettings) {#flatten-com.aspose.pdf.Form.FlattenSettings-}
```
public abstract void flatten(Form.FlattenSettings flattenSettings)
```


Removes all fields from the document and place their values instead.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flattenSettings | [FlattenSettings](../../com.aspose.pdf/flattensettings) | Settings for flattening process. |

### getCryptoAlgorithm() {#getCryptoAlgorithm--}
```
public abstract CryptoAlgorithm getCryptoAlgorithm()
```


Gets security settings if document is encrypted. If document is not encrypted then will be null

**Returns:**
[CryptoAlgorithm](../../com.aspose.pdf/cryptoalgorithm) - CryptoAlgorithm element or null
### encrypt(String userPassword, String ownerPassword, DocumentPrivilege privileges, CryptoAlgorithm cryptoAlgorithm, boolean usePdf20) {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
```
public abstract void encrypt(String userPassword, String ownerPassword, DocumentPrivilege privileges, CryptoAlgorithm cryptoAlgorithm, boolean usePdf20)
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
public abstract void encrypt(String userPassword, String ownerPassword, int permissions, CryptoAlgorithm cryptoAlgorithm)
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
public abstract void encrypt(String userPassword, String ownerPassword, int permissions, CryptoAlgorithm cryptoAlgorithm, boolean usePdf20)
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
boolean - boolean value
### setLinearized(boolean value) {#setLinearized-boolean-}
```
public abstract void setLinearized(boolean value)
```


Sets a value indicating whether document is linearized.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

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
int - int value
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


Gets encrypted status of the document. True if document is encrypted.

**Returns:**
boolean - boolean value
### optimize() {#optimize--}
```
public abstract void optimize()
```


Linearize document in order to - open the first page as quickly as possible; - display next page or follow by link to the next page as quickly as possible; - display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first); - permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed. Invoking this method doesn't actually saves the document. On the contrary the document only is prepared to have optimized structure, call then Save to get optimized document.

### save() {#save--}
```
public abstract void save()
```


Save document incrementally (i.e. using incremental update technique).

--------------------

In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save();

In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally.

### saveIncrementally(String outputFileName) {#saveIncrementally-java.lang.String-}
```
public abstract void saveIncrementally(String outputFileName)
```


Saves incrementally the PDF Document to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | java.lang.String | String value |

### save(OutputStream outputStream, SaveFormat format) {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
```
public abstract void save(OutputStream outputStream, SaveFormat format)
```


Save document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | OutputStream object |
| format | [SaveFormat](../../com.aspose.pdf/saveformat) | SaveFormat value |

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


Saves the document with a new name setting its save options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | OutputStream where the document will be stored. |
| options | [SaveOptions](../../com.aspose.pdf/saveoptions) | Save options. |

### getId() {#getId--}
```
public abstract Id getId()
```


Gets the ID.

**Returns:**
[Id](../../com.aspose.pdf/id) - Id object
### getMetadataStream() {#getMetadataStream--}
```
public abstract IPdfStreamAccessor getMetadataStream()
```


Returns raw metadata stream

**Returns:**
[IPdfStreamAccessor](../../com.aspose.pdf.engine.data.types/ipdfstreamaccessor) - IPdfStreamAccessor object
### updatePages() {#updatePages--}
```
public abstract void updatePages()
```


updatePages

### suppressUpdate() {#suppressUpdate--}
```
public abstract void suppressUpdate()
```


suppressUpdate

### resumeUpdate() {#resumeUpdate--}
```
public abstract void resumeUpdate()
```


resumeUpdate

### dispose() {#dispose--}
```
public abstract void dispose()
```


Closes all resources used by this document.

This method is obsoleted, use close() instead.

### close() {#close--}
```
public abstract void close()
```


Closes all resources used by this document.

### getBackground() {#getBackground--}
```
public abstract Color getBackground()
```


Gets the background color of the document.

**Returns:**
[Color](../../java.awt/color) - java.awt.Color object
### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public abstract void setBackground(Color value)
```


Sets the background color of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color | java.awt.Color object |

### getDefaultCopier() {#getDefaultCopier--}
```
public abstract Copier getDefaultCopier()
```


Returns copier used for coping pages to this document.

**Returns:**
[Copier](../../com.aspose.pdf/copier) - Copier object
### optimizeResources() {#optimizeResources--}
```
public abstract void optimizeResources()
```


Optimize resources in the document: 1. Resources which are not used on the document pages are removed; 2. Equal resources are joined into one object; 3. Unused objects are deleted.

### optimizeResources(OptimizationOptions strategy) {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
```
public abstract void optimizeResources(OptimizationOptions strategy)
```


Optimize resources in the document according to defined optimization strategy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| strategy | [OptimizationOptions](../../com.aspose.pdf.optimization/optimizationoptions) | Optimization strategy. |

### getPageLabels() {#getPageLabels--}
```
public abstract PageLabelCollection getPageLabels()
```


Gets page labels in the document.

**Returns:**
[PageLabelCollection](../../com.aspose.pdf/pagelabelcollection) - PageLabelCollection object
### freeMemory() {#freeMemory--}
```
public abstract void freeMemory()
```


Clears memory

### afterImport() {#afterImport--}
```
public abstract void afterImport()
```


Enumerate all registered annotations and call AfterImport for each of them.

### saveXml(String file) {#saveXml-java.lang.String-}
```
public abstract void saveXml(String file)
```


Save document to XML.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | The document model xml file |

### bindXml(String xmlFile, String xslFile) {#bindXml-java.lang.String-java.lang.String-}
```
public abstract void bindXml(String xmlFile, String xslFile)
```


Bind xml/xsl to document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlFile | java.lang.String | The xml file. |
| xslFile | java.lang.String | The xsl file if XSLT is used. |

### getObjectById(String id) {#getObjectById-java.lang.String-}
```
public abstract Object getObjectById(String id)
```


Gets a object with specified ID in the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | The object id. |

**Returns:**
java.lang.Object - The object with specified id. Null if the id is not found.
### bindXml(InputStream stream) {#bindXml-java.io.InputStream-}
```
public abstract void bindXml(InputStream stream)
```


Bind xml to document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream with xml file |

### bindXml(String file) {#bindXml-java.lang.String-}
```
public abstract void bindXml(String file)
```


Bind xml to document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | The xml file |

### repair() {#repair--}
```
public abstract void repair()
```


Repairs broken document.

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

### convertInternal(System.IO.Stream log, PdfFormat _convertTo, int none) {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-int-}
```
public abstract boolean convertInternal(System.IO.Stream log, PdfFormat _convertTo, int none)
```


Internal method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| log | com.aspose.ms.System.IO.Stream | Internal object |
| _convertTo | [PdfFormat](../../com.aspose.pdf/pdfformat) | Internal object |
| none | int | Internal object |

**Returns:**
boolean - Internal value
### getXmpMetadata(OutputStream stream) {#getXmpMetadata-java.io.OutputStream-}
```
public abstract void getXmpMetadata(OutputStream stream)
```


Get XMP metadata from document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream where metadata will be stored. |

### setXmpMetadata(InputStream stream) {#setXmpMetadata-java.io.InputStream-}
```
public abstract void setXmpMetadata(InputStream stream)
```


Set XMP metadata of document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream which contains XMP metadata. |

### isAbsentFontTryToSubstitute() {#isAbsentFontTryToSubstitute--}
```
public abstract boolean isAbsentFontTryToSubstitute()
```


Notification about missing fonts when processing documents

**Returns:**
boolean - boolean value
### setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute) {#setAbsentFontTryToSubstitute-boolean-}
```
public abstract void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```


Setting flag for set program determined font in case of absence font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| setAbsentFontTryToSubstitute | boolean | boolean value |

### isXrefGapsAllowed() {#isXrefGapsAllowed--}
```
public abstract boolean isXrefGapsAllowed()
```


Gets or sets the is document pdfa compliant.

**Returns:**
boolean - boolean value
### setXrefGapsAllowed(boolean value) {#setXrefGapsAllowed-boolean-}
```
public abstract void setXrefGapsAllowed(boolean value)
```


Gets or sets the is document pdfa compliant.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getNamedDestinations() {#getNamedDestinations--}
```
public abstract NamedDestinationCollection getNamedDestinations()
```


Collection of Named Destination in the document.

**Returns:**
[NamedDestinationCollection](../../com.aspose.pdf.nameddestinations/nameddestinationcollection) - NamedDestinationCollection instance
### check(boolean doRepair) {#check-boolean-}
```
public abstract boolean check(boolean doRepair)
```


Validates document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doRepair | boolean | If true found issues will be repaired. |

**Returns:**
boolean - boolean value
### removePdfUaCompliance() {#removePdfUaCompliance--}
```
public abstract void removePdfUaCompliance()
```


Remove pdfUa compliance from the document

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

### isManualDisposeEnabled() {#isManualDisposeEnabled--}
```
public abstract boolean isManualDisposeEnabled()
```


By default method save close internal streams and release memory resources. We can do some operations and continue work with the document after method save if this ManualDispose parameter is enabled.

**Returns:**
boolean - boolean value. (Default value == false)
### setManualDisposeEnabled(boolean manualDisposeEnabled) {#setManualDisposeEnabled-boolean-}
```
public abstract void setManualDisposeEnabled(boolean manualDisposeEnabled)
```


By default method save closes internal streams and release memory resources. We can do some operations and continue work with the document after method save is called if this ManualDispose parameter is enabled. But it is strongly recommended to call the dispose method when the Document instance is no longer needed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| manualDisposeEnabled | boolean | boolean value. (Default value == false) |

### pageNodesToBalancedTree() {#pageNodesToBalancedTree--}
```
public abstract void pageNodesToBalancedTree()
```


Organizes page tree nodes in a document into a balanced tree. Only if the document has more than nodesNumInSubtrees page objects, otherwise it does nothing.

### pageNodesToBalancedTree(byte nodesNumInSubtrees) {#pageNodesToBalancedTree-byte-}
```
public abstract void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```


Organizes page tree nodes in a document into a balanced tree. Only if the document has more than nodesNumInSubtrees page objects, otherwise it does nothing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| nodesNumInSubtrees | byte | Desired number of subnodes. |

