---
title: IDocument
second_title: Aspose.PDF for Java API Reference
description: interface representing PDF document
type: docs
weight: 2230
url: /java/com.aspose.pdf/idocument/
---
```
public interface IDocument extends com.aspose.ms.System.IDisposable, Closeable
```

interface representing PDF document

## Methods

| Method | Description |
| --- | --- |
| [afterImport](#afterImport--) | Enumerate all registered annotations and call AfterImport for each of them. |
| [bindXml](#bindXml-java.io.InputStream-) | Bind xml to document |
| [bindXml](#bindXml-java.lang.String-) | Bind xml to document |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | Bind xml/xsl to document |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Changes document passwords. |
| [check](#check-boolean-) | Validates document. |
| [close](#close--) | Closes all resources used by this document. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | Convert document to searchable document. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | Convert document to searchable document and skip errors of hochr that can not be converted. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | Convert document and save errors into the specified file. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | Convert document and save errors into the specified file. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | Convert document and save errors into the specified file. <p> This is allowing to show/hide searchable text on page. Default value is FALSE. This is allowing to get original image from pdf. Default value is FALSE. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | Convert document and save errors into the specified file. <p> This is allowing to show/hide searchable text on page. Default value is FALSE. This is allowing to get original image from pdf. Default value is FALSE. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) |  |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Convert document using specified conversion options |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Convert document and save errors into the specified file. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Convert document and save errors into the specified file. |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Internal method |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | Convert document to searchable document and skip errors of hochr that can not be converted. |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | Convert document to searchable document and skip errors of hochr that can not be converted. |
| [decrypt](#decrypt--) | Decrypts the document. |
| [dispose](#dispose--) | Deprecated. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Encrypts the document. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Encrypts the document. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Encrypts the document. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | Exports all document annotations to XFDF file |
| [flatten](#flatten--) | Removes all fields (and annotations) from the document and place their values instead. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Removes all fields from the document and place their values instead. |
| [flattenTransparency](#flattenTransparency--) | Replaces transparent content with non-transparent raster and vector graphics. |
| [freeMemory](#freeMemory--) | Clears memory |
| [getActions](#getActions--) | Gets document actions. |
| [getBackground](#getBackground--) | Gets the background color of the document. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | Returns item value from catalog dictionary. |
| [getCollection](#getCollection--) | Gets collection of document. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | Gets security settings if document is encrypted. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | Gets a custom security handler. |
| [getDefaultCopier](#getDefaultCopier--) | Returns copier used for coping pages to this document. |
| [getDestinations](#getDestinations--) | Gets the collection of destinations. |
| [getDirection](#getDirection--) | Gets reading order of text: L2R (left to right) or R2L (right to left). |
| [getDuplex](#getDuplex--) | Gets or sets print duplex mode handling option to use when printing the file from the print dialog. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | Gets collection of files embedded to document. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | Gets or sets flag to manage signature fields sanitization. |
| [getEngineDoc](#getEngineDoc--) | Instance of IPdfDocument used to access to internal document structure. |
| [getFileName](#getFileName--) | Name of the PDF file that caused this document |
| [getForm](#getForm--) | Gets Acro Form of the document. |
| [getId](#getId--) | Gets the ID. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Gets or sets flag of ignoring errors in source files. |
| [getInfo](#getInfo--) | Gets document info. |
| [getLogicalStructure](#getLogicalStructure--) | Gets logical structure of the document. |
| [getMetadata](#getMetadata--) | Document metadata. |
| [getMetadataStream](#getMetadataStream--) | Returns raw metadata stream |
| [getNamedDestinations](#getNamedDestinations--) | Collection of Named Destination in the document. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | Gets page mode, specifying how to display the document on exiting full-screen mode. |
| [getObjectById](#getObjectById-java.lang.String-) | Gets a object with specified ID in the document. |
| [getOpenAction](#getOpenAction--) | Gets action performed at document opening. |
| [getOptimizeSize](#getOptimizeSize--) | Gets optimization flag. |
| [getOutlines](#getOutlines--) | Gets document outlines. |
| [getPageInfo](#getPageInfo--) | Gets the page info.(for generator only, not filled in when reading document) |
| [getPageLabels](#getPageLabels--) | Gets page labels in the document. |
| [getPageLayout](#getPageLayout--) | Gets page layout which shall be used when the document is opened. |
| [getPageMode](#getPageMode--) | Gets page mode, specifying how document should be displayed when opened. |
| [getPages](#getPages--) | Gets collection of document pages. |
| [getPdfFormat](#getPdfFormat--) |  |
| [getPermissions](#getPermissions--) | Gets permissions of the document. |
| [getPrintScaling](#getPrintScaling--) | Gets print scaling handling option to use when printing the file from the print dialog. |
| [getTaggedContent](#getTaggedContent--) | Gets access to TaggedPdf content. |
| [getVersion](#getVersion--) | Gets a version of Pdf from Pdf file header. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | Get XMP metadata from document. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | Imports annotations from XFDF file to document. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | Notification about missing fonts when processing documents |
| [isCenterWindow](#isCenterWindow--) | Gets flag specifying whether position of the document's window will be centerd on the screen. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Many operations with font can't be executed if these operations are prohibited by license of this font. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | Gets flag specifying whether document's window title bar should display document title. |
| [isEncrypted](#isEncrypted--) | Gets encrypted status of the document. |
| [isFitWindow](#isFitWindow--) | Gets flag specifying whether document window must be resized to fit the first displayed page. |
| [isHideMenubar](#isHideMenubar--) | Gets flag specifying whether menu bar should be hidden when document is active. |
| [isHideToolBar](#isHideToolBar--) | Gets flag specifying whether toolbar should be hidden when document is active. |
| [isHideWindowUI](#isHideWindowUI--) | Gets or sets flag specifying whether user interface elements should be hidden when document is active. |
| [isLinearized](#isLinearized--) | Gets or sets a value indicating whether document is linearized. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | By default method save close internal streams and release memory resources. We can do some operations and continue work with the document after method save if this ManualDispose parameter is enabled. |
| [isPdfaCompliant](#isPdfaCompliant--) | Gets the is document pdf/a compliant. |
| [isPdfUaCompliant](#isPdfUaCompliant--) | Gets the is document pdfua compliant. |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | Gets a flag specifying whether the PDF page size shall be used to select the input paper tray. |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | Gets or sets the is document pdfa compliant. |
| [optimize](#optimize--) | Linearize document in order to - open the first page as quickly as possible; - display next page or follow by link to the next page as quickly as possible; - display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first); - permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed. |
| [optimizeResources](#optimizeResources--) | Optimize resources in the document: 1. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Optimize resources in the document according to defined optimization strategy. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | Organizes page tree nodes in a document into a balanced tree. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | Organizes page tree nodes in a document into a balanced tree. |
| [processParagraphs](#processParagraphs--) | Stores document into stream. |
| [removeMetadata](#removeMetadata--) | Removes metadata from the document. |
| [removePdfaCompliance](#removePdfaCompliance--) | Remove pdfa compliance from the document |
| [removePdfUaCompliance](#removePdfUaCompliance--) | Remove pdfUa compliance from the document |
| [repair](#repair--) | Repairs broken document. |
| [resumeUpdate](#resumeUpdate--) | resumeUpdate |
| [save](#save--) | Save document incrementally (i.e. |
| [save](#save-java.io.OutputStream-) | Stores document into stream. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | Save document |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Saves the document with a new name setting its save options. |
| [save](#save-java.lang.String-) | Saves document into the specified file. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | Saves the document with a new name setting its save options. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | Saves incrementally the PDF Document to the specified stream. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Saves incrementally the PDF Document to the specified stream. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | Saves incrementally the PDF Document to the specified stream. |
| [saveXml](#saveXml-java.lang.String-) | Save document to XML. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Sends the certain pages of the document to the document device for processing. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Sends the whole document to the document device for processing. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Sends the whole document to the document device for processing. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Sends the whole document to the document device for processing. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | Setting flag for set program determined font in case of absence font. |
| [setBackground](#setBackground-java.awt.Color-) | Sets the background color of the document. |
| [setCenterWindow](#setCenterWindow-boolean-) | Sets flag specifying whether position of the document's window will be centerd on the screen. |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | Sets collection of document. |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | Gets convert parameter for pdf/ua converter (Convert only Metadata and Document Catalog if set true) |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | Sets reading order of text: L2R (left to right) or R2L (right to left). |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Many operations with font can't be executed if these operations are prohibited by license of this font. |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | Sets flag specifying whether document's window title bar should display document title. |
| [setDuplex](#setDuplex-int-) | Gets or sets print duplex mode handling option to use when printing the file from the print dialog. |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | Gets or sets flag to manage signature fields sanitization. |
| [setFitWindow](#setFitWindow-boolean-) | Sets flag specifying whether document window must be resized to fit the first displayed page. |
| [setHideMenubar](#setHideMenubar-boolean-) | Sets flag specifying whether menu bar should be hidden when document is active. |
| [setHideToolBar](#setHideToolBar-boolean-) | Set flag specifying whether toolbar should be hidden when document is active. |
| [setHideWindowUI](#setHideWindowUI-boolean-) | Sets flag specifying whether user interface elements should be hidden when document is active. |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) |  |
| [setLinearized](#setLinearized-boolean-) | Sets a value indicating whether document is linearized. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | By default method save closes internal streams and release memory resources. We can do some operations and continue work with the document after method save is called if this ManualDispose parameter is enabled. But it is strongly recommended to call the dispose method when the Document instance is no longer needed. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | Sets page mode, specifying how to display the document on exiting full-screen mode. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | Sets action performed at document opening. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Sets optimization flag. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Sets the page info.(for generator only, not filled in when reading document) |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | Sets page layout which shall be used when the document is opened. |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | Sets page mode, specifying how document should be displayed when opened. |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | Sets a flag specifying whether the PDF page size shall be used to select the input paper tray. |
| [setPrintScaling](#setPrintScaling-int-) | Sets print scaling handling option to use when printing the file from the print dialog. |
| [setTitle](#setTitle-java.lang.String-) | Set Title for Pdf Document |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | Set XMP metadata of document. |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | Gets or sets the is document pdfa compliant. |
| [suppressUpdate](#suppressUpdate--) | suppressUpdate |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Validate document into the specified file. |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Validate document into the specified file. |

### afterImport {#afterImport--}
```
void afterImport()
```

Enumerate all registered annotations and call AfterImport for each of them.

### bindXml {#bindXml-java.io.InputStream-}
Bind xml to document

### bindXml {#bindXml-java.lang.String-}
Bind xml to document

### bindXml {#bindXml-java.lang.String-java.lang.String-}
Bind xml/xsl to document

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
Changes document passwords.

### check {#check-boolean-}
```
boolean check(boolean doRepair)
```

Validates document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doRepair |  | If true found issues will be repaired. |

**Returns:**
boolean value

### close {#close--}
```
void close()
```

Closes all resources used by this document.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
Convert document to searchable document.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
Convert document to searchable document and skip errors of hochr that can not be converted.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
Convert document and save errors into the specified file.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
Convert document and save errors into the specified file.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
Convert document and save errors into the specified file. <p> This is allowing to show/hide searchable text on page. Default value is FALSE. This is allowing to get original image from pdf. Default value is FALSE.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
Convert document and save errors into the specified file. <p> This is allowing to show/hide searchable text on page. Default value is FALSE. This is allowing to get original image from pdf. Default value is FALSE.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}


### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
Convert document using specified conversion options

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Convert document and save errors into the specified file.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Convert document and save errors into the specified file.

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Internal method

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
Convert document to searchable document and skip errors of hochr that can not be converted.

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
Convert document to searchable document and skip errors of hochr that can not be converted.

### decrypt {#decrypt--}
```
void decrypt()
```

Decrypts the document.

### dispose {#dispose--}
```
@Deprecated void dispose()
```

Deprecated.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
Encrypts the document.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
Encrypts the document.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
Encrypts the document.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
Exports all document annotations to XFDF file

### flatten {#flatten--}
```
void flatten()
```

Removes all fields (and annotations) from the document and place their values instead.

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
Removes all fields from the document and place their values instead.

### flattenTransparency {#flattenTransparency--}
```
void flattenTransparency()
```

Replaces transparent content with non-transparent raster and vector graphics.

### freeMemory {#freeMemory--}
```
void freeMemory()
```

Clears memory

### getActions {#getActions--}
```
DocumentActionCollection getActions()
```

Gets document actions.

**Returns:**
DocumentActionCollection object

### getBackground {#getBackground--}
```
Color getBackground()
```

Gets the background color of the document.

**Returns:**
java.awt.Color object

### getCatalogValue {#getCatalogValue-java.lang.String-}
Returns item value from catalog dictionary.

### getCollection {#getCollection--}
```
Collection getCollection()
```

Gets collection of document.

**Returns:**
Collection object

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
CryptoAlgorithm getCryptoAlgorithm()
```

Gets security settings if document is encrypted.

**Returns:**
CryptoAlgorithm element or null

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

Gets a custom security handler.

**Returns:**
ICustomSecurityHandler instance

### getDefaultCopier {#getDefaultCopier--}
```
Copier getDefaultCopier()
```

Returns copier used for coping pages to this document.

**Returns:**
Copier object

### getDestinations {#getDestinations--}
```
DestinationCollection getDestinations()
```

Gets the collection of destinations.

**Returns:**
DestinationCollection object

### getDirection {#getDirection--}
```
Direction getDirection()
```

Gets reading order of text: L2R (left to right) or R2L (right to left).

**Returns:**
Direction element

### getDuplex {#getDuplex--}
```
int getDuplex()
```

Gets or sets print duplex mode handling option to use when printing the file from the print dialog.

**Returns:**
PrintDuplex element

### getEmbeddedFiles {#getEmbeddedFiles--}
```
EmbeddedFileCollection getEmbeddedFiles()
```

Gets collection of files embedded to document.

**Returns:**
EmbeddedFileCollection object

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
boolean getEmbedStandardFonts()
```

Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true.

**Returns:**
boolean value

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
boolean getEnableSignatureSanitization()
```

Gets or sets flag to manage signature fields sanitization.

**Returns:**
boolean value

### getEngineDoc {#getEngineDoc--}
```
com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

Instance of IPdfDocument used to access to internal document structure.

**Returns:**
IPdfDocument object

### getFileName {#getFileName--}
```
String getFileName()
```

Name of the PDF file that caused this document

**Returns:**
String object

### getForm {#getForm--}
```
Form getForm()
```

Gets Acro Form of the document.

**Returns:**
Form object

### getId {#getId--}
```
Id getId()
```

Gets the ID.

**Returns:**
Id object

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
boolean getIgnoreCorruptedObjects()
```

Gets or sets flag of ignoring errors in source files.

**Returns:**
boolean value

### getInfo {#getInfo--}
```
DocumentInfo getInfo()
```

Gets document info.

**Returns:**
DocumentInfo object

### getLogicalStructure {#getLogicalStructure--}
```
RootElement getLogicalStructure()
```

Gets logical structure of the document.

**Returns:**
RootElement object

### getMetadata {#getMetadata--}
```
Metadata getMetadata()
```

Document metadata.

**Returns:**
Metadata object

### getMetadataStream {#getMetadataStream--}
```
com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

Returns raw metadata stream

**Returns:**
IPdfStreamAccessor object

### getNamedDestinations {#getNamedDestinations--}
```
NamedDestinationCollection getNamedDestinations()
```

Collection of Named Destination in the document.

**Returns:**
NamedDestinationCollection instance

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
PageMode getNonFullScreenPageMode()
```

Gets page mode, specifying how to display the document on exiting full-screen mode.

**Returns:**
PageMode element

### getObjectById {#getObjectById-java.lang.String-}
Gets a object with specified ID in the document.

### getOpenAction {#getOpenAction--}
```
IAppointment getOpenAction()
```

Gets action performed at document opening.

**Returns:**
IAppointment object

### getOptimizeSize {#getOptimizeSize--}
```
boolean getOptimizeSize()
```

Gets optimization flag.

**Returns:**
boolean value

### getOutlines {#getOutlines--}
```
OutlineCollection getOutlines()
```

Gets document outlines.

**Returns:**
OutlineCollection object

### getPageInfo {#getPageInfo--}
```
PageInfo getPageInfo()
```

Gets the page info.(for generator only, not filled in when reading document)

**Returns:**
The page info.

### getPageLabels {#getPageLabels--}
```
PageLabelCollection getPageLabels()
```

Gets page labels in the document.

**Returns:**
PageLabelCollection object

### getPageLayout {#getPageLayout--}
```
PageLayout getPageLayout()
```

Gets page layout which shall be used when the document is opened.

**Returns:**
PageLayout element

### getPageMode {#getPageMode--}
```
PageMode getPageMode()
```

Gets page mode, specifying how document should be displayed when opened.

**Returns:**
PageMode element

### getPages {#getPages--}
```
PageCollection getPages()
```

Gets collection of document pages.

**Returns:**
boolean value

### getPdfFormat {#getPdfFormat--}
```
PdfFormat getPdfFormat()
```



**Returns:**
PdfFormat element

### getPermissions {#getPermissions--}
```
int getPermissions()
```

Gets permissions of the document.

**Returns:**
int value

### getPrintScaling {#getPrintScaling--}
```
int getPrintScaling()
```

Gets print scaling handling option to use when printing the file from the print dialog.

**Returns:**
PrintScaling element

### getTaggedContent {#getTaggedContent--}
```
ITaggedContent getTaggedContent()
```

Gets access to TaggedPdf content.

**Returns:**
ITaggedContent instance

### getVersion {#getVersion--}
```
String getVersion()
```

Gets a version of Pdf from Pdf file header.

**Returns:**
String object

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
Get XMP metadata from document.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
Imports annotations from XFDF file to document.

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
boolean isAbsentFontTryToSubstitute()
```

Notification about missing fonts when processing documents

**Returns:**
boolean value

### isCenterWindow {#isCenterWindow--}
```
boolean isCenterWindow()
```

Gets flag specifying whether position of the document's window will be centerd on the screen.

**Returns:**
boolean value

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
boolean isDisableFontLicenseVerifications()
```

Many operations with font can't be executed if these operations are prohibited by license of this font.

**Returns:**
boolean value By default false.

### isDisplayDocTitle {#isDisplayDocTitle--}
```
boolean isDisplayDocTitle()
```

Gets flag specifying whether document's window title bar should display document title.

**Returns:**
boolean value

### isEncrypted {#isEncrypted--}
```
boolean isEncrypted()
```

Gets encrypted status of the document.

**Returns:**
boolean value

### isFitWindow {#isFitWindow--}
```
boolean isFitWindow()
```

Gets flag specifying whether document window must be resized to fit the first displayed page.

**Returns:**
boolean value

### isHideMenubar {#isHideMenubar--}
```
boolean isHideMenubar()
```

Gets flag specifying whether menu bar should be hidden when document is active.

**Returns:**
boolean value

### isHideToolBar {#isHideToolBar--}
```
boolean isHideToolBar()
```

Gets flag specifying whether toolbar should be hidden when document is active.

**Returns:**
boolean value

### isHideWindowUI {#isHideWindowUI--}
```
boolean isHideWindowUI()
```

Gets or sets flag specifying whether user interface elements should be hidden when document is active.

**Returns:**
boolean value

### isLinearized {#isLinearized--}
```
boolean isLinearized()
```

Gets or sets a value indicating whether document is linearized.

**Returns:**
boolean value

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
boolean isManualDisposeEnabled()
```

By default method save close internal streams and release memory resources. We can do some operations and continue work with the document after method save if this ManualDispose parameter is enabled.

**Returns:**
boolean value. (Default value == false)

### isPdfaCompliant {#isPdfaCompliant--}
```
boolean isPdfaCompliant()
```

Gets the is document pdf/a compliant.

**Returns:**
boolean value

### isPdfUaCompliant {#isPdfUaCompliant--}
```
boolean isPdfUaCompliant()
```

Gets the is document pdfua compliant.

**Returns:**
boolean value

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
boolean isPickTrayByPdfSize()
```

Gets a flag specifying whether the PDF page size shall be used to select the input paper tray.

**Returns:**
boolean value

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
boolean isXrefGapsAllowed()
```

Gets or sets the is document pdfa compliant.

**Returns:**
boolean value

### optimize {#optimize--}
```
void optimize()
```

Linearize document in order to - open the first page as quickly as possible; - display next page or follow by link to the next page as quickly as possible; - display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first); - permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed.

### optimizeResources {#optimizeResources--}
```
void optimizeResources()
```

Optimize resources in the document: 1.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
Optimize resources in the document according to defined optimization strategy.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
void pageNodesToBalancedTree()
```

Organizes page tree nodes in a document into a balanced tree.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

Organizes page tree nodes in a document into a balanced tree.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| nodesNumInSubtrees |  | Desired number of subnodes. Default value is ten. |

### processParagraphs {#processParagraphs--}
```
void processParagraphs()
```

Stores document into stream.

### removeMetadata {#removeMetadata--}
```
void removeMetadata()
```

Removes metadata from the document.

### removePdfaCompliance {#removePdfaCompliance--}
```
void removePdfaCompliance()
```

Remove pdfa compliance from the document

### removePdfUaCompliance {#removePdfUaCompliance--}
```
void removePdfUaCompliance()
```

Remove pdfUa compliance from the document

### repair {#repair--}
```
void repair()
```

Repairs broken document.

### resumeUpdate {#resumeUpdate--}
```
void resumeUpdate()
```

resumeUpdate

### save {#save--}
```
void save()
```

Save document incrementally (i.e.

### save {#save-java.io.OutputStream-}
Stores document into stream.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
Save document

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Saves the document with a new name setting its save options.

### save {#save-java.lang.String-}
Saves document into the specified file.

### save {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
Saves the document with a new name setting its save options.

### saveIncrementally {#saveIncrementally-java.io.OutputStream-}
Saves incrementally the PDF Document to the specified stream.

### saveIncrementally {#saveIncrementally-com.aspose.ms.System.IO.Stream-}
Saves incrementally the PDF Document to the specified stream.

### saveIncrementally {#saveIncrementally-java.lang.String-}
Saves incrementally the PDF Document to the specified stream.

### saveXml {#saveXml-java.lang.String-}
Save document to XML.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-}
Sends the certain pages of the document to the document device for processing.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-}
Sends the whole document to the document device for processing.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-}
Sends the whole document to the document device for processing.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-}
Sends the whole document to the document device for processing.

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```

Setting flag for set program determined font in case of absence font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| setAbsentFontTryToSubstitute |  | boolean value |

### setBackground {#setBackground-java.awt.Color-}
Sets the background color of the document.

### setCenterWindow {#setCenterWindow-boolean-}
```
void setCenterWindow(boolean value)
```

Sets flag specifying whether position of the document's window will be centerd on the screen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
Sets collection of document.

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
void setConvertMetadataAndCatalogOnly(boolean value)
```

Gets convert parameter for pdf/ua converter (Convert only Metadata and Document Catalog if set true)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setDirection {#setDirection-com.aspose.pdf.Direction-}
Sets reading order of text: L2R (left to right) or R2L (right to left).

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
void setDisableFontLicenseVerifications(boolean value)
```

Many operations with font can't be executed if these operations are prohibited by license of this font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value By default false. |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
void setDisplayDocTitle(boolean value)
```

Sets flag specifying whether document's window title bar should display document title.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setDuplex {#setDuplex-int-}
```
void setDuplex(int value)
```

Gets or sets print duplex mode handling option to use when printing the file from the print dialog.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | PrintDuplex element |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
void setEmbedStandardFonts(boolean value)
```

Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
void setEnableSignatureSanitization(boolean value)
```

Gets or sets flag to manage signature fields sanitization.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setFitWindow {#setFitWindow-boolean-}
```
void setFitWindow(boolean value)
```

Sets flag specifying whether document window must be resized to fit the first displayed page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setHideMenubar {#setHideMenubar-boolean-}
```
void setHideMenubar(boolean value)
```

Sets flag specifying whether menu bar should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setHideToolBar {#setHideToolBar-boolean-}
```
void setHideToolBar(boolean value)
```

Set flag specifying whether toolbar should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
void setHideWindowUI(boolean value)
```

Sets flag specifying whether user interface elements should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
void setIgnoreCorruptedObjects(boolean value)
```



### setLinearized {#setLinearized-boolean-}
```
void setLinearized(boolean value)
```

Sets a value indicating whether document is linearized.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

By default method save closes internal streams and release memory resources. We can do some operations and continue work with the document after method save is called if this ManualDispose parameter is enabled. But it is strongly recommended to call the dispose method when the Document instance is no longer needed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| manualDisposeEnabled |  | boolean value. (Default value == false) |

### setNonFullScreenPageMode {#setNonFullScreenPageMode-com.aspose.pdf.PageMode-}
Sets page mode, specifying how to display the document on exiting full-screen mode.

### setOpenAction {#setOpenAction-com.aspose.pdf.IAppointment-}
Sets action performed at document opening.

### setOptimizeSize {#setOptimizeSize-boolean-}
```
void setOptimizeSize(boolean value)
```

Sets optimization flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Sets the page info.(for generator only, not filled in when reading document)

### setPageLayout {#setPageLayout-com.aspose.pdf.PageLayout-}
Sets page layout which shall be used when the document is opened.

### setPageMode {#setPageMode-com.aspose.pdf.PageMode-}
Sets page mode, specifying how document should be displayed when opened.

### setPickTrayByPdfSize {#setPickTrayByPdfSize-boolean-}
```
void setPickTrayByPdfSize(boolean value)
```

Sets a flag specifying whether the PDF page size shall be used to select the input paper tray.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setPrintScaling {#setPrintScaling-int-}
```
void setPrintScaling(int value)
```

Sets print scaling handling option to use when printing the file from the print dialog.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | PrintDuplex element |

### setTitle {#setTitle-java.lang.String-}
Set Title for Pdf Document

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
Set XMP metadata of document.

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
void setXrefGapsAllowed(boolean value)
```

Gets or sets the is document pdfa compliant.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### suppressUpdate {#suppressUpdate--}
```
void suppressUpdate()
```

suppressUpdate

### updatePages {#updatePages--}
```
void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
Validate document into the specified file.

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
Validate document into the specified file.
