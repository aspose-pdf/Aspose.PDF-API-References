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
## Fields

| Field | Description |
| --- | --- |
| [FontSubstitution](#FontSubstitution) | It occurs when font replaces another font in document. |
## Methods

| Method | Description |
| --- | --- |
| [afterImport()](#afterImport--) | Enumerate all registered annotations and call AfterImport for each of them. |
| [bindXml(InputStream stream)](#bindXml-java.io.InputStream-) | Bind xml to document |
| [bindXml(InputStream xmlStream, InputStream xslStream)](#bindXml-java.io.InputStream-java.io.InputStream-) | Bind xml/xsl to document |
| [bindXml(InputStream xmlStream, InputStream xslStream, System.Xml.XmlReaderSettings settings)](#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-) | Bind xml/xsl to document |
| [bindXml(String file)](#bindXml-java.lang.String-) | Bind xml to document |
| [bindXml(String xmlFile, String xslFile)](#bindXml-java.lang.String-java.lang.String-) | Bind xml/xsl to document |
| [changePasswords(String ownerPassword, String newUserPassword, String newOwnerPassword)](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Changes document passwords. |
| [check(boolean doRepair)](#check-boolean-) | Validates document. |
| [close()](#close--) | Closes all resources used by this document. |
| [convert(Document.CallBackGetHocr callback)](#convert-com.aspose.pdf.Document.CallBackGetHocr-) | Convert document to searchable document. |
| [convert(Document.CallBackGetHocr callback, boolean isTestVisible)](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-) | Convert document and save errors into the specified file. |
| [convert(Document.CallBackGetHocr callback, boolean isTextVisible, boolean isOriginalImage)](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-) | Convert document and save errors into the specified file. |
| [convert(PdfFormatConversionOptions options)](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Convert document using specified conversion options |
| [convert(int fixup, OutputStream outputLog)](#convert-int-java.io.OutputStream-) | Convert document by applying the Fixup. |
| [convert(int fixup, OutputStream outputLog, boolean onlyValidation, Object[] parameters)](#convert-int-java.io.OutputStream-boolean-java.lang.Object---) | Convert document by applying the Fixup. |
| [convert(int fixup, String outputLog)](#convert-int-java.lang.String-) | Convert document by applying the Fixup. |
| [convert(int fixup, String outputLog, boolean onlyValidation, Object[] parameters)](#convert-int-java.lang.String-boolean-java.lang.Object---) | Convert document by applying the Fixup. |
| [convert(InputStream srcStream, LoadOptions loadOptions, OutputStream dstStream, SaveOptions saveOptions)](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Converts stream in source format into stream in destination format. |
| [convert(InputStream srcStream, LoadOptions loadOptions, String dstFileName, SaveOptions saveOptions)](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | Converts stream in source format into destination file in destination format. |
| [convert(OutputStream outputLogStream, PdfFormat format, int action)](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-) | Convert document and save errors into the specified stream. |
| [convert(OutputStream outputLogStream, PdfFormat format, int action, int transparencyAction)](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-int-) | Convert document and save errors into the specified file. |
| [convert(String srcFileName, LoadOptions loadOptions, OutputStream dstStream, SaveOptions saveOptions)](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Converts source file in source format into stream in destination format. |
| [convert(String srcFileName, LoadOptions loadOptions, String dstFileName, SaveOptions saveOptions)](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | Converts source file in source format into destination file in destination format. |
| [convert(String outputLogFileName, PdfFormat format, int action)](#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-) | Convert document and save errors into the specified file. |
| [convert(String outputLogFileName, PdfFormat format, int action, int transparencyAction)](#convert-java.lang.String-com.aspose.pdf.PdfFormat-int-int-) | Convert document and save errors into the specified file. |
| [convertInternal(System.IO.Stream outputLogStream, PdfFormat format, int action)](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-int-) | Convert document and save errors into the specified stream. |
| [convertPageToPNGMemoryStream(Page page)](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | Convert page to PNG for DSR, OMR, OCR image stream. |
| [convertWithSkippingErrors(Document.CallBackGetHocr callback)](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocr-) | Convert document to searchable document and skip errors of hochr that can not be converted. |
| [decrypt()](#decrypt--) | Decrypts the document. |
| [dispose()](#dispose--) | Closes all resources used by this document. |
| [encrypt(String userPassword, String ownerPassword, DocumentPrivilege privileges, int cryptoAlgorithm, boolean usePdf20)](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-boolean-) | Encrypts the document. |
| [encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)](#encrypt-java.lang.String-java.lang.String-int-int-) | Encrypts the document. |
| [encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm, boolean usePdf20)](#encrypt-java.lang.String-java.lang.String-int-int-boolean-) | Encrypts the document. |
| [endOperation()](#endOperation--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportAnnotationsToXfdf(OutputStream output)](#exportAnnotationsToXfdf-java.io.OutputStream-) | Export all document annotations into stream. |
| [exportAnnotationsToXfdf(String fileName)](#exportAnnotationsToXfdf-java.lang.String-) | Exports all document annotations to XFDF file |
| [flatten()](#flatten--) | Removes all fields from the document and place their values instead. |
| [flatten(Form.FlattenSettings flattenSettings)](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Removes all fields from the document and place their values instead. |
| [freeMemory()](#freeMemory--) | Clears memory |
| [getAbsentFontHandler()](#getAbsentFontHandler--) | Notification about missing fonts while processing documents. |
| [getActions()](#getActions--) | Gets document actions. |
| [getAllowReusePageContent()](#getAllowReusePageContent--) | Allows to merge page contents to optimize docuement size. |
| [getBackground()](#getBackground--) | Gets the background color of the document. |
| [getCatalogValue(String key)](#getCatalogValue-java.lang.String-) | Returns item value from catalog dictionary. |
| [getClass()](#getClass--) |  |
| [getCollection()](#getCollection--) | Gets collection of document. |
| [getCryptoAlgorithm()](#getCryptoAlgorithm--) | Gets security settings if document is encrypted. |
| [getDefaultCopier()](#getDefaultCopier--) | Returns copier used for coping pages to this document. |
| [getDestinations()](#getDestinations--) | Gets the collection of destinations. |
| [getDirection()](#getDirection--) | Gets reading order of text: L2R (left to right) or R2L (right to left). |
| [getDuplex()](#getDuplex--) | Gets or sets print duplex mode handling option to use when printing the file from the print dialog. |
| [getEmbedStandardFonts()](#getEmbedStandardFonts--) | Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. |
| [getEmbeddedFiles()](#getEmbeddedFiles--) | Gets collection of files embedded to document. |
| [getEnableSignatureSanitization()](#getEnableSignatureSanitization--) | Gets or sets flag to manage signature fields sanitization. |
| [getEngineDoc()](#getEngineDoc--) | Instance of IPdfDocument used to access to internal document structure. |
| [getFileName()](#getFileName--) | Name of the PDF file that caused this document |
| [getFontUtilities()](#getFontUtilities--) | IDocumentFontUtilities instance |
| [getForm()](#getForm--) | Gets Acro Form of the document. |
| [getId()](#getId--) | Gets the ID. |
| [getIgnoreCorruptedObjects()](#getIgnoreCorruptedObjects--) | Gets or sets flag of ignoring errors in source files. |
| [getInfo()](#getInfo--) | Gets document info. |
| [getJavaScript()](#getJavaScript--) | Collection of JavaScript of document level. |
| [getLogicalStructure()](#getLogicalStructure--) | Gets logical structure of the document. |
| [getMetadata()](#getMetadata--) | Document metadata. |
| [getMetadataStream()](#getMetadataStream--) | Returns raw metadata stream |
| [getNamedDestinations()](#getNamedDestinations--) | Collection of Named Destination in the document. |
| [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | Gets page mode, specifying how to display the document on exiting full-screen mode. |
| [getObjectById(String id)](#getObjectById-java.lang.String-) | Gets a object with specified ID in the document. |
| [getOpenAction()](#getOpenAction--) | Gets action performed at document opening. |
| [getOptimizeSize()](#getOptimizeSize--) | Gets optimization flag. |
| [getOutlines()](#getOutlines--) | Gets document outlines. |
| [getPageInfo()](#getPageInfo--) | Gets the page info. |
| [getPageLabels()](#getPageLabels--) | Gets page labels in the document. |
| [getPageLayout()](#getPageLayout--) | Gets page layout which shall be used when the document is opened. |
| [getPageMode()](#getPageMode--) | Gets page mode, specifying how document should be displayed when opened. |
| [getPages()](#getPages--) | Gets collection of document pages. |
| [getPdfFormat()](#getPdfFormat--) | Gets pdfa format |
| [getPermissions()](#getPermissions--) | Gets permissions of the document. |
| [getTaggedContent()](#getTaggedContent--) | Gets access to TaggedPdf content. |
| [getVersion()](#getVersion--) | Gets a version of Pdf from Pdf file header. |
| [getXmpMetadata(OutputStream output)](#getXmpMetadata-java.io.OutputStream-) | Get XMP metadata from document. |
| [hashCode()](#hashCode--) |  |
| [importAnnotationsFromXfdf(InputStream stream)](#importAnnotationsFromXfdf-java.io.InputStream-) | Imports annotations from stream to document. |
| [importAnnotationsFromXfdf(String fileName)](#importAnnotationsFromXfdf-java.lang.String-) | Imports annotations from XFDF file to document. |
| [isAbsentFontTryToSubstitute()](#isAbsentFontTryToSubstitute--) | Flag which informs about replacement of missing font. |
| [isCenterWindow()](#isCenterWindow--) | Gets flag specifying whether position of the document's window will be centered on the screen. |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Many operations with font can't be executed if these operations are prohibited by license of this font. |
| [isDisplayDocTitle()](#isDisplayDocTitle--) | Gets flag specifying whether document's window title bar should display document title. |
| [isEnableObjectUnload()](#isEnableObjectUnload--) | Get or sets flag which enables document partially be unloaded from memory. |
| [isEncrypted()](#isEncrypted--) | Gets encrypted status of the document. |
| [isFitWindow()](#isFitWindow--) | Gets flag specifying whether document window must be resized to fit the first displayed page. |
| [isHandleSignatureChange()](#isHandleSignatureChange--) | Throw Exception if the document will save with changes and have signature |
| [isHideMenubar()](#isHideMenubar--) | Gets flag specifying whether menu bar should be hidden when document is active. |
| [isHideToolBar()](#isHideToolBar--) | Gets flag specifying whether toolbar should be hidden when document is active. |
| [isHideWindowUI()](#isHideWindowUI--) | Gets flag specifying whether user interface elements should be hidden when document is active. |
| [isLicensed()](#isLicensed--) | Gets licensed state of the system. |
| [isLinearized()](#isLinearized--) | Gets a value indicating whether document is linearized. |
| [isManualDisposeEnabled()](#isManualDisposeEnabled--) | By default method save close internal streams and release memory resources. |
| [isPdfUaCompliant()](#isPdfUaCompliant--) | Gets the is document pdfua compliant. |
| [isPdfaCompliant()](#isPdfaCompliant--) | Gets the is document pdfa compliant. |
| [isSkippedPdfaCompliantValidationBeforeSave()](#isSkippedPdfaCompliantValidationBeforeSave--) | By default pdfa validation process is necessary to update or remove pdfa compliant data if some rules were broken. |
| [isXrefGapsAllowed()](#isXrefGapsAllowed--) | Gets or sets the is document pdfa compliant. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [optimize()](#optimize--) | Linearize document in order to - open the first page as quickly as possible; - display next page or follow by link to the next page as quickly as possible; - display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first); - permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed. |
| [optimizeResources()](#optimizeResources--) | Optimize resources in the document: 1. |
| [optimizeResources(OptimizationOptions strategy)](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Optimize resources in the document according to defined optimization strategy. |
| [pageNodesToBalancedTree()](#pageNodesToBalancedTree--) | Organizes page tree nodes in a document into a balanced tree. |
| [pageNodesToBalancedTree(byte nodesNumInSubtrees)](#pageNodesToBalancedTree-byte-) | Organizes page tree nodes in a document into a balanced tree. |
| [preSave(PageCollection pages, SaveOptions saveOptions)](#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-) | Internal method |
| [processParagraphs()](#processParagraphs--) | Stores document into stream. |
| [removeMetadata()](#removeMetadata--) | Removes metadata from the document. |
| [removePdfUaCompliance()](#removePdfUaCompliance--) | Remove pdfUa compliance from the document |
| [removePdfaCompliance()](#removePdfaCompliance--) | Remove pdfa compliance from the document |
| [repair()](#repair--) | Repairs broken document. |
| [resumeUpdate()](#resumeUpdate--) | resumes document update |
| [save()](#save--) | Save document incrementally (i.e. using incremental update technique). |
| [save(System.IO.Stream output)](#save-com.aspose.ms.System.IO.Stream-) | Stores document into stream. |
| [save(SaveOptions options)](#save-com.aspose.pdf.SaveOptions-) | Saves the document with save options. |
| [save(OutputStream output)](#save-java.io.OutputStream-) | Stores document into stream. |
| [save(OutputStream outputStream, SaveFormat format)](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | Saves the document with a new name along with a file format. |
| [save(OutputStream outputStream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Saves the document to a stream with a save options. |
| [save(String outputFileName)](#save-java.lang.String-) | Saves document into the specified file. |
| [save(String outputFileName, SaveFormat format)](#save-java.lang.String-com.aspose.pdf.SaveFormat-) | Saves the document with a new name along with a file format. |
| [save(String outputFileName, SaveOptions options)](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | Saves the document with a new name setting its save options. |
| [saveIncrementally(System.IO.Stream output)](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Saves incrementally the PDF Document to the specified stream. |
| [saveIncrementally(OutputStream output)](#saveIncrementally-java.io.OutputStream-) | Saves incrementally the PDF Document to the specified stream. |
| [saveIncrementally(String outputFileName)](#saveIncrementally-java.lang.String-) | Saves incrementally the PDF Document to the specified stream. |
| [saveXml(String file)](#saveXml-java.lang.String-) | Save document to XML. |
| [sendTo(DocumentDevice device, int fromPage, int toPage, OutputStream output)](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Sends the certain pages of the document to the document device for processing. |
| [sendTo(DocumentDevice device, int fromPage, int toPage, String outputFileName)](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Sends the whole document to the document device for processing. |
| [sendTo(DocumentDevice device, OutputStream output)](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Sends the whole document to the document device for processing. |
| [sendTo(DocumentDevice device, String outputFileName)](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Sends the whole document to the document device for processing. |
| [setAbsentFontHandler(ADocument.AbsentFontHandler absentFontHandler)](#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-) | Notification about missing fonts while processing documents. |
| [setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)](#setAbsentFontTryToSubstitute-boolean-) | Setting flag for set program determined font in case of absense font. |
| [setAllowReusePageContent(boolean value)](#setAllowReusePageContent-boolean-) | Allows to merge page contents to optimize docuement size. |
| [setBackground(Color value)](#setBackground-java.awt.Color-) | Sets the background color of the document. |
| [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | Sets flag specifying whether position of the document's window will be centered on the screen. |
| [setCollection(Collection value)](#setCollection-com.aspose.pdf.Collection-) | Sets collection of document. |
| [setConvertMetadataAndCatalogOnly(boolean value)](#setConvertMetadataAndCatalogOnly-boolean-) | Gets convert parameter for pdf/ua converter (Convert only Metadata and Document Catalog if set true) |
| [setDirection(int value)](#setDirection-int-) | Sets reading order of text: L2R (left to right) or R2L (right to left). |
| [setDisableFontLicenseVerifications(boolean value)](#setDisableFontLicenseVerifications-boolean-) | Many operations with font can't be executed if these operations are prohibited by license of this font. |
| [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | Sets flag specifying whether document's window title bar should display document title. |
| [setDuplex(int value)](#setDuplex-int-) | Gets or sets print duplex mode handling option to use when printing the file from the print dialog. |
| [setEmbedStandardFonts(boolean value)](#setEmbedStandardFonts-boolean-) | Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. |
| [setEnableObjectUnload(boolean value)](#setEnableObjectUnload-boolean-) | Get or sets flag which enables document partially be unloaded from memory. |
| [setEnableSignatureSanitization(boolean value)](#setEnableSignatureSanitization-boolean-) | Gets or sets flag to manage signature fields sanitization. |
| [setFitWindow(boolean value)](#setFitWindow-boolean-) | Sets flag specifying whether document window must be resized to fit the first displayed page. |
| [setHandleSignatureChange(boolean value)](#setHandleSignatureChange-boolean-) | Throw Exception if the document will save with changes and have signature |
| [setHideMenubar(boolean value)](#setHideMenubar-boolean-) | Sets flag specifying whether menu bar should be hidden when document is active. |
| [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | Set flag specifying whether toolbar should be hidden when document is active. |
| [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | Sets flag specifying whether user interface elements should be hidden when document is active. |
| [setIgnoreCorruptedObjects(boolean value)](#setIgnoreCorruptedObjects-boolean-) | Gets or sets flag of ignoring errors in source files. |
| [setLayersAdded(boolean value)](#setLayersAdded-boolean-) |  |
| [setLinearized(boolean value)](#setLinearized-boolean-) | Sets a value indicating whether document is linearized. |
| [setManualDisposeEnabled(boolean manualDisposeEnabled)](#setManualDisposeEnabled-boolean-) | By default method save closes internal streams and release memory resources. |
| [setNonFullScreenPageMode(int value)](#setNonFullScreenPageMode-int-) | Sets page mode, specifying how to display the document on exiting full-screen mode. |
| [setOpenAction(IAppointment value)](#setOpenAction-com.aspose.pdf.IAppointment-) | Sets action performed at document opening. |
| [setOptimizeSize(boolean value)](#setOptimizeSize-boolean-) | Sets optimization flag. |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | Sets the page info. |
| [setPageLayout(int value)](#setPageLayout-int-) | Sets page layout which shall be used when the document is opened. |
| [setPageMode(int pageMode)](#setPageMode-int-) | Sets page mode, specifying how document should be displayed when opened. |
| [setSkipPdfaCompliantValidationBeforeSave(boolean pdfaCompliantValidationBeforeSave)](#setSkipPdfaCompliantValidationBeforeSave-boolean-) | By default pdfa validation process is necessary to update or remove pdfa if some rules were broken. |
| [setTitle(String title)](#setTitle-java.lang.String-) | Set Title for Pdf Document |
| [setXmpMetadata(InputStream stream)](#setXmpMetadata-java.io.InputStream-) | Set XMP metadata of document. |
| [setXrefGapsAllowed(boolean value)](#setXrefGapsAllowed-boolean-) | Gets or sets the is document pdfa compliant. |
| [startOperation()](#startOperation--) |  |
| [suppressUpdate()](#suppressUpdate--) | Suppresses update contents data for all pages The contents is not updated until ResumeUpdate is called |
| [toString()](#toString--) |  |
| [updatePages()](#updatePages--) |  |
| [validate(PdfFormatConversionOptions options)](#validate-com.aspose.pdf.PdfFormatConversionOptions-) | Validate document into the specified file. |
| [validate(OutputStream outputLogStream, PdfFormat format)](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Validate document into the specified file. |
| [validate(String outputLogFileName, PdfFormat format)](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Validate document into the specified file. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### FontSubstitution {#FontSubstitution}
```
public final PdfEvent<ADocument.FontSubstitutionHandler> FontSubstitution
```


It occurs when font replaces another font in document.

### afterImport() {#afterImport--}
```
public void afterImport()
```


Enumerate all registered annotations and call AfterImport for each of them. InternalMethod

### bindXml(InputStream stream) {#bindXml-java.io.InputStream-}
```
public void bindXml(InputStream stream)
```


Bind xml to document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream with xml file |

### bindXml(InputStream xmlStream, InputStream xslStream) {#bindXml-java.io.InputStream-java.io.InputStream-}
```
public void bindXml(InputStream xmlStream, InputStream xslStream)
```


Bind xml/xsl to document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlStream | java.io.InputStream | The xml stream. |
| xslStream | java.io.InputStream | The xsl stream if XSLT is used. |

### bindXml(InputStream xmlStream, InputStream xslStream, System.Xml.XmlReaderSettings settings) {#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-}
```
public void bindXml(InputStream xmlStream, InputStream xslStream, System.Xml.XmlReaderSettings settings)
```


Bind xml/xsl to document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlStream | java.io.InputStream | The xml stream. |
| xslStream | java.io.InputStream | The xsl stream if XSLT is used. |
| settings | com.aspose.ms.System.Xml.XmlReaderSettings | The xml reader settings. |

### bindXml(String file) {#bindXml-java.lang.String-}
```
public void bindXml(String file)
```


Bind xml to document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | The xml file |

### bindXml(String xmlFile, String xslFile) {#bindXml-java.lang.String-java.lang.String-}
```
public void bindXml(String xmlFile, String xslFile)
```


Bind xml/xsl to document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlFile | java.lang.String | The xml file. |
| xslFile | java.lang.String | The xsl file if XSLT is used. |

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
### close() {#close--}
```
public void close()
```


Closes all resources used by this document.

### convert(Document.CallBackGetHocr callback) {#convert-com.aspose.pdf.Document.CallBackGetHocr-}
```
public boolean convert(Document.CallBackGetHocr callback)
```


Convert document to searchable document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | [CallBackGetHocr](../../com.aspose.pdf/callbackgethocr) | The call back procedure for hocr recognize. |

**Returns:**
boolean - boolean value
### convert(Document.CallBackGetHocr callback, boolean isTestVisible) {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-}
```
public boolean convert(Document.CallBackGetHocr callback, boolean isTestVisible)
```


Convert document and save errors into the specified file.

This is allow to show/hide searchable text. Default value is FALSE.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | [CallBackGetHocr](../../com.aspose.pdf/callbackgethocr) | Action for objects that can not be converted |
| isTestVisible | boolean | boolean value |

**Returns:**
boolean - The operation result
### convert(Document.CallBackGetHocr callback, boolean isTextVisible, boolean isOriginalImage) {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-}
```
public boolean convert(Document.CallBackGetHocr callback, boolean isTextVisible, boolean isOriginalImage)
```


Convert document and save errors into the specified file.

This is allow to show/hide searchable text on page. Default value is FALSE. This is allow to getting original image from pdf. Default value is FALSE.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| callback | [CallBackGetHocr](../../com.aspose.pdf/callbackgethocr) | Action for objects that can not be converted |
| isTextVisible | boolean | boolean value |
| isOriginalImage | boolean | boolean value |

**Returns:**
boolean - The operation result
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
### convert(InputStream srcStream, LoadOptions loadOptions, OutputStream dstStream, SaveOptions saveOptions) {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
```
public static void convert(InputStream srcStream, LoadOptions loadOptions, OutputStream dstStream, SaveOptions saveOptions)
```


Converts stream in source format into stream in destination format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | The source stream. |
| loadOptions | [LoadOptions](../../com.aspose.pdf/loadoptions) | The source stream format. |
| dstStream | java.io.OutputStream | The destination stream. |
| saveOptions | [SaveOptions](../../com.aspose.pdf/saveoptions) | The destination file format. |

### convert(InputStream srcStream, LoadOptions loadOptions, String dstFileName, SaveOptions saveOptions) {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
```
public static void convert(InputStream srcStream, LoadOptions loadOptions, String dstFileName, SaveOptions saveOptions)
```


Converts stream in source format into destination file in destination format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | The source stream. |
| loadOptions | [LoadOptions](../../com.aspose.pdf/loadoptions) | The source stream format. |
| dstFileName | java.lang.String | The destination file name. |
| saveOptions | [SaveOptions](../../com.aspose.pdf/saveoptions) | The destination file format. |

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
### convert(OutputStream outputLogStream, PdfFormat format, int action, int transparencyAction) {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-int-}
```
public final boolean convert(OutputStream outputLogStream, PdfFormat format, int action, int transparencyAction)
```


Convert document and save errors into the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | java.io.OutputStream | Stream where the comments will be stored. |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | The pdf format. |
| action | int | Action for objects that can not be converted |
| transparencyAction | int | Action for image masked objects |

**Returns:**
boolean - The operation result
### convert(String srcFileName, LoadOptions loadOptions, OutputStream dstStream, SaveOptions saveOptions) {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
```
public static void convert(String srcFileName, LoadOptions loadOptions, OutputStream dstStream, SaveOptions saveOptions)
```


Converts source file in source format into stream in destination format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | java.lang.String | The source file name. |
| loadOptions | [LoadOptions](../../com.aspose.pdf/loadoptions) | The source file format. |
| dstStream | java.io.OutputStream | The destination stream. |
| saveOptions | [SaveOptions](../../com.aspose.pdf/saveoptions) | The destination stream format. |

### convert(String srcFileName, LoadOptions loadOptions, String dstFileName, SaveOptions saveOptions) {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
```
public static void convert(String srcFileName, LoadOptions loadOptions, String dstFileName, SaveOptions saveOptions)
```


Converts source file in source format into destination file in destination format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | java.lang.String | The source file name. |
| loadOptions | [LoadOptions](../../com.aspose.pdf/loadoptions) | The source file format. |
| dstFileName | java.lang.String | The destination file name. |
| saveOptions | [SaveOptions](../../com.aspose.pdf/saveoptions) | The destination file format. |

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
### convertPageToPNGMemoryStream(Page page) {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
```
public byte[] convertPageToPNGMemoryStream(Page page)
```


Convert page to PNG for DSR, OMR, OCR image stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page object to convert. |

**Returns:**
byte[] - Image stream in byte[] array.
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
### decrypt() {#decrypt--}
```
public void decrypt()
```


Decrypts the document. Call then Save to obtain decrypted version of the document.

### dispose() {#dispose--}
```
public void dispose()
```


Closes all resources used by this document.

This method is obsolete, use close() instead.

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

### endOperation() {#endOperation--}
```
public static void endOperation()
```




### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### exportAnnotationsToXfdf(OutputStream output) {#exportAnnotationsToXfdf-java.io.OutputStream-}
```
public final void exportAnnotationsToXfdf(OutputStream output)
```


Export all document annotations into stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | java.io.OutputStream | Stream where store XFDF. |

### exportAnnotationsToXfdf(String fileName) {#exportAnnotationsToXfdf-java.lang.String-}
```
public void exportAnnotationsToXfdf(String fileName)
```


Exports all document annotations to XFDF file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | XFDF file name |

### flatten() {#flatten--}
```
public void flatten()
```


Removes all fields from the document and place their values instead.

### flatten(Form.FlattenSettings flattenSettings) {#flatten-com.aspose.pdf.Form.FlattenSettings-}
```
public void flatten(Form.FlattenSettings flattenSettings)
```


Removes all fields from the document and place their values instead.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flattenSettings | [FlattenSettings](../../com.aspose.pdf/flattensettings) | Settings for flattening process. |

### freeMemory() {#freeMemory--}
```
public void freeMemory()
```


Clears memory

### getAbsentFontHandler() {#getAbsentFontHandler--}
```
public ADocument.AbsentFontHandler getAbsentFontHandler()
```


Notification about missing fonts while processing documents.

**Returns:**
com.aspose.pdf.ADocument.AbsentFontHandler - ADocument.AbsentFontHandler instance
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
### getAllowReusePageContent() {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```


Allows to merge page contents to optimize docuement size. If used then differnet but duplicated pages may reference to the same content object. Please note that this mode may cause side effects like changing page content when other page is changed.

**Returns:**
boolean - value boolean value
### getBackground() {#getBackground--}
```
public Color getBackground()
```


Gets the background color of the document.

**Returns:**
[Color](../../java.awt/color) - Color object
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCollection() {#getCollection--}
```
public Collection getCollection()
```


Gets collection of document.

**Returns:**
[Collection](../../com.aspose.pdf/collection) - Collection object
### getCryptoAlgorithm() {#getCryptoAlgorithm--}
```
public int getCryptoAlgorithm()
```


Gets security settings if document is encrypted. If document is not encrypted then corresponding exception will be raised in .net 1.1 or CryptoAlgorithm will be null for other .net versions.

**Returns:**
int - CryptoAlgorithm element
### getDefaultCopier() {#getDefaultCopier--}
```
public Copier getDefaultCopier()
```


Returns copier used for coping pages to this document.

**Returns:**
[Copier](../../com.aspose.pdf/copier) - Copier object
### getDestinations() {#getDestinations--}
```
public DestinationCollection getDestinations()
```


Gets the collection of destinations.

**Returns:**
[DestinationCollection](../../com.aspose.pdf/destinationcollection) - DestinationCollection element
### getDirection() {#getDirection--}
```
public int getDirection()
```


Gets reading order of text: L2R (left to right) or R2L (right to left).

**Returns:**
int - Direction element
### getDuplex() {#getDuplex--}
```
public int getDuplex()
```


Gets or sets print duplex mode handling option to use when printing the file from the print dialog.

**Returns:**
int - PrintDuplex element
### getEmbedStandardFonts() {#getEmbedStandardFonts--}
```
public boolean getEmbedStandardFonts()
```


Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. All PDF fonts can be embedded into document simply via setting of flag IsEmbedded into true, but PDF standard Type1 fonts is an exception from this rule. Standard Type1 font embedding requires much time, so to embed these fonts it's necessary not only set flag IsEmbedded into true for specified font but also set an additiona flag on document's level - EmbedStandardFonts = true; This property can be set only one time for all fonts. By default false.

**Returns:**
boolean
### getEmbeddedFiles() {#getEmbeddedFiles--}
```
public EmbeddedFileCollection getEmbeddedFiles()
```


Gets collection of files embedded to document.

**Returns:**
[EmbeddedFileCollection](../../com.aspose.pdf/embeddedfilecollection) - EmbeddedFileCollection object
### getEnableSignatureSanitization() {#getEnableSignatureSanitization--}
```
public final boolean getEnableSignatureSanitization()
```


Gets or sets flag to manage signature fields sanitization. Enabled by default.

**Returns:**
boolean - boolean value
### getEngineDoc() {#getEngineDoc--}
```
public IPdfDocument getEngineDoc()
```


Instance of IPdfDocument used to access to internal document structure. Internal only

**Returns:**
[IPdfDocument](../../com.aspose.pdf.engine/ipdfdocument) - IPdfDocument object
### getFileName() {#getFileName--}
```
public String getFileName()
```


Name of the PDF file that caused this document

**Returns:**
java.lang.String - String object
### getFontUtilities() {#getFontUtilities--}
```
public Document.IDocumentFontUtilities getFontUtilities()
```


IDocumentFontUtilities instance

**Returns:**
[IDocumentFontUtilities](../../com.aspose.pdf/idocumentfontutilities) - IDocumentFontUtilities instance
### getForm() {#getForm--}
```
public Form getForm()
```


Gets Acro Form of the document.

**Returns:**
[Form](../../com.aspose.pdf/form) - Form object
### getId() {#getId--}
```
public Id getId()
```


Gets the ID.

**Returns:**
[Id](../../com.aspose.pdf/id) - Id object
### getIgnoreCorruptedObjects() {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```


Gets or sets flag of ignoring errors in source files. When pages from source document copied into destination document, copying process is stopped with exception if some objects in source files are corrupted when this flag is false. example: dest.Pages.Add(src.Pages); If this flag is set to true then corrupted objects will be replaced with empty values. By default: true.

**Returns:**
boolean - boolean value
### getInfo() {#getInfo--}
```
public DocumentInfo getInfo()
```


Gets document info.

**Returns:**
[DocumentInfo](../../com.aspose.pdf/documentinfo) - DocumentInfo object
### getJavaScript() {#getJavaScript--}
```
public JavaScriptCollection getJavaScript()
```


Collection of JavaScript of document level.

**Returns:**
[JavaScriptCollection](../../com.aspose.pdf/javascriptcollection) - JavaScriptCollection object
### getLogicalStructure() {#getLogicalStructure--}
```
public RootElement getLogicalStructure()
```


Gets logical structure of the document.

**Returns:**
[RootElement](../../com.aspose.pdf/rootelement) - RootElement object
### getMetadata() {#getMetadata--}
```
public Metadata getMetadata()
```


Document metadata. (A PDF document may include general information, such as the document's title, author, and creation and modification dates. Such global information about the document (as opposed to its content or structure) is called metadata and is intended to assist in cataloguing and searching for documents in external databases.)

**Returns:**
[Metadata](../../com.aspose.pdf/metadata) - Metadata object
### getMetadataStream() {#getMetadataStream--}
```
public IPdfStreamAccessor getMetadataStream()
```


Returns raw metadata stream

**Returns:**
[IPdfStreamAccessor](../../com.aspose.pdf.engine.data.types/ipdfstreamaccessor) - IPdfStreamAccessor object
### getNamedDestinations() {#getNamedDestinations--}
```
public NamedDestinationCollection getNamedDestinations()
```


Collection of Named Destination in the document.

**Returns:**
[NamedDestinationCollection](../../com.aspose.pdf.nameddestinations/nameddestinationcollection)
### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public int getNonFullScreenPageMode()
```


Gets page mode, specifying how to display the document on exiting full-screen mode.

**Returns:**
int - PageMode element
### getObjectById(String id) {#getObjectById-java.lang.String-}
```
public Object getObjectById(String id)
```


Gets a object with specified ID in the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | The object id. |

**Returns:**
java.lang.Object - The object with specified id. Null if the id is not found.
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
### getOptimizeSize() {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```


Gets optimization flag. When pages are added to document, equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false.

**Returns:**
boolean - boolean value
### getOutlines() {#getOutlines--}
```
public OutlineCollection getOutlines()
```


Gets document outlines.

**Returns:**
[OutlineCollection](../../com.aspose.pdf/outlinecollection) - OutlineCollection object
### getPageInfo() {#getPageInfo--}
```
public PageInfo getPageInfo()
```


Gets the page info.(for generator only, not filled in when reading document)

**Returns:**
[PageInfo](../../com.aspose.pdf/pageinfo) - The page info.
### getPageLabels() {#getPageLabels--}
```
public PageLabelCollection getPageLabels()
```


Gets page labels in the document.

**Returns:**
[PageLabelCollection](../../com.aspose.pdf/pagelabelcollection) - PageLabelCollection object
### getPageLayout() {#getPageLayout--}
```
public int getPageLayout()
```


Gets page layout which shall be used when the document is opened.

**Returns:**
int - PageLayout element
### getPageMode() {#getPageMode--}
```
public int getPageMode()
```


Gets page mode, specifying how document should be displayed when opened.

**Returns:**
int - PageMode element
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
### getPdfFormat() {#getPdfFormat--}
```
public PdfFormat getPdfFormat()
```


Gets pdfa format

**Returns:**
[PdfFormat](../../com.aspose.pdf/pdfformat) - PdfFormat element
### getPermissions() {#getPermissions--}
```
public int getPermissions()
```


Gets permissions of the document.

**Returns:**
int - int value
### getTaggedContent() {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```


Gets access to TaggedPdf content.

The example demonstrates how to use tagged content for creating new document with header, paragraphs and images.

```
// Create new document
     Document document = new Document();

     // Get the tagged content
     ITaggedContent taggedContent = document.getTaggedContent();

     // Set language for document
     taggedContent.setLanguage("en-US");

     // Set title for PDF document
     taggedContent.setTitle("Example document");

     // Creating and adding Section
     SectElement sect = taggedContent.createSectElement();
     taggedContent.getRootElement().appendChild(sect);

     // Create Header
     HeaderElement h1 = taggedContent.createHeaderElement(1);
     h1.setText("The Header");
     sect.appendChild(h1);

     // Create paragraph
     ParagraphElement p = taggedContent.createParagraphElement();
     p.setTag("Paragraph");
     p.setText("The text of paragraph.");
     sect.appendChild(p);
     // Create illustration
     IllustrationElement figure1 = taggedContent.createFigureElement();
     sect.appendChild(figure1);
     figure1.setAlternativeText("Figure 1");
     figure1.setTitle("Image 1");
     figure1.setTag("Fig");
     figure1.setImage("path/of/image.jpg");
     // Save document
     document.save("example.pdf");
```

**Returns:**
[ITaggedContent](../../com.aspose.pdf.tagged/itaggedcontent) - ITaggedContent instance
### getVersion() {#getVersion--}
```
public String getVersion()
```


Gets a version of Pdf from Pdf file header.

**Returns:**
java.lang.String - String value
### getXmpMetadata(OutputStream output) {#getXmpMetadata-java.io.OutputStream-}
```
public void getXmpMetadata(OutputStream output)
```


Get XMP metadata from document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | java.io.OutputStream | Stream where metadata will be stored. |

### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### importAnnotationsFromXfdf(InputStream stream) {#importAnnotationsFromXfdf-java.io.InputStream-}
```
public final void importAnnotationsFromXfdf(InputStream stream)
```


Imports annotations from stream to document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream contains XFDF data. |

### importAnnotationsFromXfdf(String fileName) {#importAnnotationsFromXfdf-java.lang.String-}
```
public void importAnnotationsFromXfdf(String fileName)
```


Imports annotations from XFDF file to document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | XFDF file name |

### isAbsentFontTryToSubstitute() {#isAbsentFontTryToSubstitute--}
```
public boolean isAbsentFontTryToSubstitute()
```


Flag which informs about replacement of missing font.

**Returns:**
boolean
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
### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```


Many operations with font can't be executed if these operations are prohibited by license of this font. For example some font can't be embedded into PDF document if license rules disable embedding for this font. This flag is used to disable any license restrictions for all fonts in current PDF document. Be careful when using this flag. When it is set it means that person who sets this flag, takes all responsibility of possible license/law violations on himself. So He takes it on it's own risk. It's strongly recommended to use this flag only when you are fully confident that you are not breaking the copyright law. By default false.

**Returns:**
boolean - boolean value By default false.
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
### isEnableObjectUnload() {#isEnableObjectUnload--}
```
public boolean isEnableObjectUnload()
```


Get or sets flag which enables document partially be unloaded from memory. This allow to decrease memory usage but may have negative effect on performance.

**Returns:**
boolean - boolean value
### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Gets encrypted status of the document. True if document is encrypted.

**Returns:**
boolean - boolean value
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
### isHandleSignatureChange() {#isHandleSignatureChange--}
```
public final boolean isHandleSignatureChange()
```


Throw Exception if the document will save with changes and have signature

**Returns:**
boolean - boolean value
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
### isLicensed() {#isLicensed--}
```
public static boolean isLicensed()
```


Gets licensed state of the system. Returns true is system works in licensed mode and false otherwise.

**Returns:**
boolean - boolean value
### isLinearized() {#isLinearized--}
```
public boolean isLinearized()
```


Gets a value indicating whether document is linearized.

**Returns:**
boolean - boolean value
### isManualDisposeEnabled() {#isManualDisposeEnabled--}
```
public boolean isManualDisposeEnabled()
```


By default method save close internal streams and release memory resources. We can do some operations and continue work with the document after method save if this ManualDispose parameter is enabled.

**Returns:**
boolean - boolean value. (Default value == false)
### isPdfUaCompliant() {#isPdfUaCompliant--}
```
public boolean isPdfUaCompliant()
```


Gets the is document pdfua compliant.

**Returns:**
boolean - boolean value
### isPdfaCompliant() {#isPdfaCompliant--}
```
public boolean isPdfaCompliant()
```


Gets the is document pdfa compliant.

**Returns:**
boolean - boolean value
### isSkippedPdfaCompliantValidationBeforeSave() {#isSkippedPdfaCompliantValidationBeforeSave--}
```
public boolean isSkippedPdfaCompliantValidationBeforeSave()
```


By default pdfa validation process is necessary to update or remove pdfa compliant data if some rules were broken. But for fast saving process is can be skipped.

**Returns:**
boolean - boolean value
### isXrefGapsAllowed() {#isXrefGapsAllowed--}
```
public boolean isXrefGapsAllowed()
```


Gets or sets the is document pdfa compliant.

**Returns:**
boolean - boolean value
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### optimize() {#optimize--}
```
public void optimize()
```


Linearize document in order to - open the first page as quickly as possible; - display next page or follow by link to the next page as quickly as possible; - display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first); - permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed. Invoking this method doesn't actually saves the document. On the contrary the document only is prepared to have optimized structure, call then Save to get optimized document.

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

### preSave(PageCollection pages, SaveOptions saveOptions) {#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-}
```
public static void preSave(PageCollection pages, SaveOptions saveOptions)
```


Internal method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pages | [PageCollection](../../com.aspose.pdf/pagecollection) | PageCollection instance |
| saveOptions | [SaveOptions](../../com.aspose.pdf/saveoptions) | SaveOptions instance |

### processParagraphs() {#processParagraphs--}
```
public void processParagraphs()
```


Stores document into stream.

### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Removes metadata from the document.

### removePdfUaCompliance() {#removePdfUaCompliance--}
```
public void removePdfUaCompliance()
```


Remove pdfUa compliance from the document

### removePdfaCompliance() {#removePdfaCompliance--}
```
public void removePdfaCompliance()
```


Remove pdfa compliance from the document

### repair() {#repair--}
```
public void repair()
```


Repairs broken document.

### resumeUpdate() {#resumeUpdate--}
```
public void resumeUpdate()
```


resumes document update

### save() {#save--}
```
public void save()
```


Save document incrementally (i.e. using incremental update technique).

--------------------

In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save();

In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally.

### save(System.IO.Stream output) {#save-com.aspose.ms.System.IO.Stream-}
```
public void save(System.IO.Stream output)
```


Stores document into stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | com.aspose.ms.System.IO.Stream | Stream where document shell be stored. |

### save(SaveOptions options) {#save-com.aspose.pdf.SaveOptions-}
```
public final void save(SaveOptions options)
```


Saves the document with save options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [SaveOptions](../../com.aspose.pdf/saveoptions) | Save options. |

### save(OutputStream output) {#save-java.io.OutputStream-}
```
public void save(OutputStream output)
```


Stores document into stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | java.io.OutputStream | Stream where document shell be stored. |

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

### save(String outputFileName) {#save-java.lang.String-}
```
public void save(String outputFileName)
```


Saves document into the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | java.lang.String | Path to file where the document will be stored. |

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

### saveIncrementally(System.IO.Stream output) {#saveIncrementally-com.aspose.ms.System.IO.Stream-}
```
public void saveIncrementally(System.IO.Stream output)
```


Saves incrementally the PDF Document to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | com.aspose.ms.System.IO.Stream | OutputStream object |

### saveIncrementally(OutputStream output) {#saveIncrementally-java.io.OutputStream-}
```
public void saveIncrementally(OutputStream output)
```


Saves incrementally the PDF Document to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | java.io.OutputStream | OutputStream object |

### saveIncrementally(String outputFileName) {#saveIncrementally-java.lang.String-}
```
public void saveIncrementally(String outputFileName)
```


Saves incrementally the PDF Document to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | java.lang.String | OutputStream object |

### saveXml(String file) {#saveXml-java.lang.String-}
```
public void saveXml(String file)
```


Save document to XML.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | The document model xml file |

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

### setAbsentFontHandler(ADocument.AbsentFontHandler absentFontHandler) {#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-}
```
public void setAbsentFontHandler(ADocument.AbsentFontHandler absentFontHandler)
```


Notification about missing fonts while processing documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| absentFontHandler | com.aspose.pdf.ADocument.AbsentFontHandler | ADocument.AbsentFontHandler instance |

### setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute) {#setAbsentFontTryToSubstitute-boolean-}
```
public void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```


Setting flag for set program determined font in case of absense font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| setAbsentFontTryToSubstitute | boolean |  |

### setAllowReusePageContent(boolean value) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```


Allows to merge page contents to optimize docuement size. If used then differnet but duplicated pages may reference to the same content object. Please note that this mode may cause side effects like changing page content when other page is changed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public void setBackground(Color value)
```


Sets the background color of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color | Color object |

### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public void setCenterWindow(boolean value)
```


Sets flag specifying whether position of the document's window will be centered on the screen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setCollection(Collection value) {#setCollection-com.aspose.pdf.Collection-}
```
public void setCollection(Collection value)
```


Sets collection of document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Collection](../../com.aspose.pdf/collection) | Collection object |

### setConvertMetadataAndCatalogOnly(boolean value) {#setConvertMetadataAndCatalogOnly-boolean-}
```
public final void setConvertMetadataAndCatalogOnly(boolean value)
```


Gets convert parameter for pdf/ua converter (Convert only Metadata and Document Catalog if set true)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setDirection(int value) {#setDirection-int-}
```
public void setDirection(int value)
```


Sets reading order of text: L2R (left to right) or R2L (right to left).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setDisableFontLicenseVerifications(boolean value) {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```


Many operations with font can't be executed if these operations are prohibited by license of this font. For example some font can't be embedded into PDF document if license rules disable embedding for this font. This flag is used to disable any license restrictions for all fonts in current PDF document. Be careful when using this flag. When it is set it means that person who sets this flag, takes all responsibility of possible license/law violations on himself. So He takes it on it's own risk. It's strongly recommended to use this flag only when you are fully confident that you are not breaking the copyright law. By default false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value By default false. |

### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public void setDisplayDocTitle(boolean value)
```


Sets flag specifying whether document's window title bar should display document title.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setDuplex(int value) {#setDuplex-int-}
```
public void setDuplex(int value)
```


Gets or sets print duplex mode handling option to use when printing the file from the print dialog.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | PrintDuplex element |

### setEmbedStandardFonts(boolean value) {#setEmbedStandardFonts-boolean-}
```
public void setEmbedStandardFonts(boolean value)
```


Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. All PDF fonts can be embedded into document simply via setting of flag IsEmbedded into true, but PDF standard Type1 fonts is an exception from this rule. Standard Type1 font embedding requires much time, so to embed these fonts it's necessary not only set flag IsEmbedded into true for specified font but also set an additiona flag on document's level - EmbedStandardFonts = true; This property can be set only one time for all fonts. By default false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setEnableObjectUnload(boolean value) {#setEnableObjectUnload-boolean-}
```
public void setEnableObjectUnload(boolean value)
```


Get or sets flag which enables document partially be unloaded from memory. This allow to decrease memory usage but may have negative effect on performance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setEnableSignatureSanitization(boolean value) {#setEnableSignatureSanitization-boolean-}
```
public final void setEnableSignatureSanitization(boolean value)
```


Gets or sets flag to manage signature fields sanitization. Enabled by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public void setFitWindow(boolean value)
```


Sets flag specifying whether document window must be resized to fit the first displayed page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setHandleSignatureChange(boolean value) {#setHandleSignatureChange-boolean-}
```
public final void setHandleSignatureChange(boolean value)
```


Throw Exception if the document will save with changes and have signature

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setHideMenubar(boolean value) {#setHideMenubar-boolean-}
```
public void setHideMenubar(boolean value)
```


Sets flag specifying whether menu bar should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public void setHideToolBar(boolean value)
```


Set flag specifying whether toolbar should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public void setHideWindowUI(boolean value)
```


Sets flag specifying whether user interface elements should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setIgnoreCorruptedObjects(boolean value) {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```


Gets or sets flag of ignoring errors in source files. When pages from source document copied into destination document, copying process is stopped with exception if some objects in source files are corrupted when this flag is false. example: dest.Pages.Add(src.Pages); If this flag is set to true then corrupted objects will be replaced with empty values. By default: true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setLayersAdded(boolean value) {#setLayersAdded-boolean-}
```
public void setLayersAdded(boolean value)
```


Set LayersAdded value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setLinearized(boolean value) {#setLinearized-boolean-}
```
public void setLinearized(boolean value)
```


Sets a value indicating whether document is linearized.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setManualDisposeEnabled(boolean manualDisposeEnabled) {#setManualDisposeEnabled-boolean-}
```
public void setManualDisposeEnabled(boolean manualDisposeEnabled)
```


By default method save closes internal streams and release memory resources. We can do some operations and continue work with the document after method save is called if this ManualDispose parameter is enabled. But it is strongly recommended to call the dispose method when the Document instance is no longer needed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| manualDisposeEnabled | boolean | boolean value. (Default value == false) |

### setNonFullScreenPageMode(int value) {#setNonFullScreenPageMode-int-}
```
public void setNonFullScreenPageMode(int value)
```


Sets page mode, specifying how to display the document on exiting full-screen mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setOpenAction(IAppointment value) {#setOpenAction-com.aspose.pdf.IAppointment-}
```
public void setOpenAction(IAppointment value)
```


Sets action performed at document opening.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | IAppointment value |

### setOptimizeSize(boolean value) {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```


Sets optimization flag. When pages are added to document, equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setPageInfo(PageInfo value) {#setPageInfo-com.aspose.pdf.PageInfo-}
```
public void setPageInfo(PageInfo value)
```


Sets the page info.(for generator only, not filled in when reading document)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageInfo](../../com.aspose.pdf/pageinfo) | PageInfo object |

### setPageLayout(int value) {#setPageLayout-int-}
```
public void setPageLayout(int value)
```


Sets page layout which shall be used when the document is opened.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setPageMode(int pageMode) {#setPageMode-int-}
```
public void setPageMode(int pageMode)
```


Sets page mode, specifying how document should be displayed when opened.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageMode | int | int value |

### setSkipPdfaCompliantValidationBeforeSave(boolean pdfaCompliantValidationBeforeSave) {#setSkipPdfaCompliantValidationBeforeSave-boolean-}
```
public void setSkipPdfaCompliantValidationBeforeSave(boolean pdfaCompliantValidationBeforeSave)
```


By default pdfa validation process is necessary to update or remove pdfa if some rules were broken. But for fast saving process is can be skipped.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfaCompliantValidationBeforeSave | boolean | boolean value |

### setTitle(String title) {#setTitle-java.lang.String-}
```
public final void setTitle(String title)
```


Set Title for Pdf Document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| title | java.lang.String | Document's title |

### setXmpMetadata(InputStream stream) {#setXmpMetadata-java.io.InputStream-}
```
public void setXmpMetadata(InputStream stream)
```


Set XMP metadata of document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream which contains XMP metadata. |

### setXrefGapsAllowed(boolean value) {#setXrefGapsAllowed-boolean-}
```
public void setXrefGapsAllowed(boolean value)
```


Gets or sets the is document pdfa compliant.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### startOperation() {#startOperation--}
```
public static void startOperation()
```




### suppressUpdate() {#suppressUpdate--}
```
public void suppressUpdate()
```


Suppresses update contents data for all pages The contents is not updated until ResumeUpdate is called

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updatePages() {#updatePages--}
```
public void updatePages()
```


updatePages

### validate(PdfFormatConversionOptions options) {#validate-com.aspose.pdf.PdfFormatConversionOptions-}
```
public boolean validate(PdfFormatConversionOptions options)
```


Validate document into the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [PdfFormatConversionOptions](../../com.aspose.pdf/pdfformatconversionoptions) | set of options for convert PDF document |

**Returns:**
boolean - The operation result
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
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

