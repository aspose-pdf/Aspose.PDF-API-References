---
title: Document
linktitle: Document
second_title: Aspose.PDF for Java API Reference
description: Class representing PDF document.
type: docs
weight: 1060
url: /java/com.aspose.pdf/document/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Document

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IDocument, Closeable, AutoCloseable

```
public final class Document extends Object implements IDocument
```

Class representing PDF document.

## Fields

| Field | Description |
| --- | --- |
| [DefaultNodesNumInSubtrees](#DefaultNodesNumInSubtrees) |  |
| [FontSubstitution](#FontSubstitution) | It occurs when font replaces another font in document. |

## Constructors

| Constructor | Description |
| --- | --- |
| [Document](#Document--) | Initializes empty document. |
| [Document](#Document-byte:A-) | Initialize new Document instance from the {@code input} byte array. |
| [Document](#Document-java.io.InputStream-) | Initializes empty document. |
| [Document](#Document-java.io.InputStream-boolean-) | Initializes empty document. |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-) | Initializes empty document. |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-) | Initializes empty document. |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Initializes empty document. |
| [Document](#Document-java.io.InputStream-java.lang.String-) | Initializes empty document. |
| [Document](#Document-java.io.InputStream-java.lang.String-boolean-) | Initializes empty document. |
| [Document](#Document-java.io.InputStream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initializes empty document. |
| [Document](#Document-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initializes empty document. |
| [Document](#Document-com.aspose.pdf.PdfVersion-) | Initializes empty document. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-) | Initializes empty document. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-com.aspose.pdf.LoadOptions-) | Initializes empty document. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-) | Initializes empty document. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initializes empty document. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initializes empty document. |
| [Document](#Document-java.lang.String-) | Initializes empty document. |
| [Document](#Document-java.lang.String-boolean-) | Initializes empty document. |
| [Document](#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-) | Initializes empty document. |
| [Document](#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-) | Initializes empty document. |
| [Document](#Document-java.lang.String-com.aspose.pdf.LoadOptions-) | Initializes empty document. |
| [Document](#Document-java.lang.String-java.lang.String-) | Initializes empty document. |
| [Document](#Document-java.lang.String-java.lang.String-boolean-) | Initializes empty document. |
| [Document](#Document-java.lang.String-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initializes empty document. |
| [Document](#Document-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initializes empty document. |

## Methods

| Method | Description |
| --- | --- |
| [afterImport](#afterImport--) | Enumerate all registered annotations and call AfterImport for each of them. |
| [bindXml](#bindXml-java.io.InputStream-) | Bind xml to document |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-) | Bind xml/xsl to document |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-) | Bind xml/xsl to document |
| [bindXml](#bindXml-java.lang.String-) | Bind xml to document |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | Bind xml/xsl to document |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Changes document passwords. This action can be done only using owner password. |
| [check](#check-boolean-) | Validates document. |
| [close](#close--) | Closes all resources used by this document. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | Recognize images inside the document and add hocr strings over it. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | Convert document and save errors into the specified file. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | Convert document and save errors into the specified file. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | Convert document and save errors into the specified file. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | Convert document and save errors into the specified file. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | Convert document and save errors into the specified file. |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-) | Convert document by applying the Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-) | Convert document by applying the Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-) | Convert document by applying the Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-) | Convert document by applying the Fixup. |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Converts stream in source format into stream in destination format. |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | Converts stream in source format into destination file in destination format. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Convert document and save errors into the specified stream. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Convert document and save errors into the specified file. |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Convert document using specified conversion options |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Converts source file in source format into stream in destination format. |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | Converts source file in source format into destination file in destination format. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Convert document and save errors into the specified file. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Convert document and save errors into the specified file. |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Convert document and save errors into the specified stream. |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | Convert page to PNG for DSR, OMR, OCR image stream. |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | Convert document to searchable document and skip errors of hochr that can not be converted. |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | Convert document to searchable document and skip errors of hochr that can not be converted. |
| [decrypt](#decrypt--) | Decrypts the document. Call then Save to obtain decrypted version of the document. |
| [dispose](#dispose--) | Closes all resources used by this document. This method is obsolete, use close() instead. |
| [encrypt](#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-) | Encrypts the document. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Encrypts the document. Call then Save to get encrypted version of the document. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Encrypts the document. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Encrypts the document. Call then Save to get encrypted version of the document. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Encrypts the document. Call then Save to get encrypted version of the document. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Encrypts the document. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | Export all document annotations into stream. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | Exports all document annotations to XFDF file |
| [flatten](#flatten--) | Removes all fields (and annotations) from the document and place their values instead. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Removes all fields (and annotations) from the document and place their values instead. |
| [flattenTransparency](#flattenTransparency--) | Replaces transparent content with non-transparent raster and vector graphics. |
| [freeMemory](#freeMemory--) | Clears memory |
| [getAbsentFontHandler](#getAbsentFontHandler--) | Notification about missing fonts while processing documents. |
| [getActions](#getActions--) | <p> Gets document actions. This property is instance of DocumentActions class which allows to get/set BeforClosing, BeforSaving, etc. actions. </p> |
| [getAllowReusePageContent](#getAllowReusePageContent--) | Allows to merge page contents to optimize docuement size. |
| [getBackground](#getBackground--) | Gets the background color of the document. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | Returns item value from catalog dictionary. |
| [getCollection](#getCollection--) | Gets collection of document. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | Gets security settings if document is encrypted. If document is not encrypted then corresponding exception will be raised in .net 1.1 or CryptoAlgorithm will be null for other .net versions. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | Gets a custom security handler. |
| [getDefaultCopier](#getDefaultCopier--) | Returns copier used for coping pages to this document. |
| [getDestinations](#getDestinations--) | Gets the collection of destinations. |
| [getDirection](#getDirection--) | Gets reading order of text: L2R (left to right) or R2L (right to left). |
| [getDuplex](#getDuplex--) | Gets or sets print duplex mode handling option to use when printing the file from the print dialog. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | Gets collection of files embedded to document. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | Gets or sets flag to manage signature fields sanitization. |
| [getEngineDoc](#getEngineDoc--) | Instance of IPdfDocument used to access to internal document structure. Internal only |
| [getFileName](#getFileName--) | Name of the PDF file that caused this document |
| [getFileSizeLimitToMemoryLoading](#getFileSizeLimitToMemoryLoading--) | Get and set the file size limit for loading an entire file into memory. |
| [getFontUtilities](#getFontUtilities--) | IDocumentFontUtilities instance |
| [getForm](#getForm--) | Gets Acro Form of the document. |
| [getId](#getId--) | Gets the ID. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Gets or sets flag of ignoring errors in source files. When pages from source document copied into destination document, copying process is stopped with exception if some objects in source files are corrupted when this flag is false. example: dest.Pages.Add(src.Pages); If this flag is set to true then corrupted objects will be replaced with empty values. By default: true. |
| [getInfo](#getInfo--) | Gets document info. |
| [getJavaScript](#getJavaScript--) | Collection of JavaScript of document level. |
| [getLogicalStructure](#getLogicalStructure--) | Gets logical structure of the document. |
| [getMetadata](#getMetadata--) | Document metadata. (A PDF document may include general information, such as the document's title, author, and creation and modification dates. Such global information about the document (as opposed to its content or structure) is called metadata and is intended to assist in cataloguing and searching for documents in external databases.) |
| [getMetadataStream](#getMetadataStream--) | Returns raw metadata stream |
| [getNamedDestinations](#getNamedDestinations--) | Collection of Named Destination in the document. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | Gets page mode, specifying how to display the document on exiting full-screen mode. |
| [getObjectById](#getObjectById-java.lang.String-) | Gets a object with specified ID in the document. |
| [getOpenAction](#getOpenAction--) | <p> Gets action performed at document opening. </p> <hr> <pre> Example demonstrates how to get CenterWindow flag: Document document = new Document("sample.pdf"); IAppointment value = document.getOpenAction(); </pre> |
| [getOptimizeSize](#getOptimizeSize--) | Gets optimization flag. When pages are added to document, equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false. |
| [getOutlines](#getOutlines--) | Gets document outlines. |
| [getOutputIntents](#getOutputIntents--) | Gets the collection of Output intents in the document. |
| [getPageInfo](#getPageInfo--) | Gets the page info.(for generator only, not filled in when reading document) |
| [getPageLabels](#getPageLabels--) | Gets page labels in the document. |
| [getPageLayout](#getPageLayout--) | Gets page layout which shall be used when the document is opened. |
| [getPageMode](#getPageMode--) | Gets page mode, specifying how document should be displayed when opened. |
| [getPages](#getPages--) | <p> Gets collection of document pages. Note that pages are numbered from 1 in collection. </p> |
| [getPdfFormat](#getPdfFormat--) | Gets pdfa format |
| [getPermissions](#getPermissions--) | Gets permissions of the document. |
| [getPrintScaling](#getPrintScaling--) | Gets print scaling handling option to use when printing the file from the print dialog. |
| [getTaggedContent](#getTaggedContent--) | Gets access to TaggedPdf content. The example demonstrates how to use tagged content for creating new document with header, paragraphs and images. // Create new document Document document = new Document(); // Get the tagged content ITaggedContent taggedContent = document.getTaggedContent(); // Set language for document taggedContent.setLanguage("en-US"); // Set title for PDF document taggedContent.setTitle("Example document"); // Creating and adding Section SectElement sect = taggedContent.createSectElement(); taggedContent.getRootElement().appendChild(sect); // Create Header HeaderElement h1 = taggedContent.createHeaderElement(1); h1.setText("The Header"); sect.appendChild(h1); // Create paragraph ParagraphElement p = taggedContent.createParagraphElement(); p.setTag("Paragraph"); p.setText("The text of paragraph."); sect.appendChild(p); // Create illustration IllustrationElement figure1 = taggedContent.createFigureElement(); sect.appendChild(figure1); figure1.setAlternativeText("Figure 1"); figure1.setTitle("Image 1"); figure1.setTag("Fig"); figure1.setImage("path/of/image.jpg"); // Save document document.save("example.pdf"); |
| [getVersion](#getVersion--) | Gets a version of Pdf from Pdf file header. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | Get XMP metadata from document. |
| [hasIncrementalUpdate](#hasIncrementalUpdate--) | Checks if the current PDF document has been saved with incremental updates. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | Imports annotations from stream to document. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | Imports annotations from XFDF file to document. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | Flag which informs about replacement of missing font. |
| [isCenterWindow](#isCenterWindow--) | <p> Gets flag specifying whether position of the document's window will be centered on the screen. </p> |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Many operations with font can't be executed if these operations are prohibited by license of this font. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | <p> Gets flag specifying whether document's window title bar should display document title. </p> |
| [isEnableNotificationLogging](#isEnableNotificationLogging--) | Gets or sets a value indicating whether to enable the logging of notifications. |
| [isEnableObjectUnload](#isEnableObjectUnload--) | Get or sets flag which enables document partially be unloaded from memory. |
| [isEncrypted](#isEncrypted--) | Gets encrypted status of the document. True if document is encrypted. |
| [isFitWindow](#isFitWindow--) | <p> Gets flag specifying whether document window must be resized to fit the first displayed page. </p> |
| [isHandleSignatureChange](#isHandleSignatureChange--) | Throw Exception if the document will save with changes and have signature |
| [isHideMenubar](#isHideMenubar--) | <p> Gets flag specifying whether menu bar should be hidden when document is active. </p> |
| [isHideToolBar](#isHideToolBar--) | <p> Gets flag specifying whether toolbar should be hidden when document is active. </p> |
| [isHideWindowUI](#isHideWindowUI--) | <p> Gets flag specifying whether user interface elements should be hidden when document is active. </p> |
| [isLicensed](#isLicensed--) | Gets licensed state of the system. |
| [isLinearized](#isLinearized--) | Gets a value indicating whether document is linearized. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | By default, method save close internal streams and release memory resources. We can do some operations and continue work with the document after method save if this ManualDispose parameter is enabled. |
| [isPdfaCompliant](#isPdfaCompliant--) | Gets the is document pdfa compliant. |
| [isPdfUaCompliant](#isPdfUaCompliant--) | Gets the is document pdfua compliant. |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | Gets a flag specifying whether the PDF page size shall be used to select the input paper tray. |
| [isRepairNeeded](#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-) | Checks if document requires Repair method call. |
| [isSkippedPdfaCompliantValidationBeforeSave](#isSkippedPdfaCompliantValidationBeforeSave--) | By default pdfa validation process is necessary to update or remove pdfa compliant data if some rules were broken. |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | Gets or sets the is document pdfa compliant. |
| [loadFrom](#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-) | Loads a file, converting it to PDF. |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | Merges documents. |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | Merges documents. |
| [merge](#merge-com.aspose.pdf.Document...-) | Merges documents. |
| [merge](#merge-java.lang.String...-) | Merges pdf files. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | Merges documents. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | Merges documents. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.Document...-) | Merges documents. |
| [mergeDocuments](#mergeDocuments-java.lang.String...-) | Merges pdf files. |
| [optimize](#optimize--) | Linearize document in order to - open the first page as quickly as possible; - display next page or follow by link to the next page as quickly as possible; - display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first); - permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed. Invoking this method doesn't actually saves the document. On the contrary the document only is prepared to have optimized structure, call then Save to get optimized document. |
| [optimizeResources](#optimizeResources--) | Optimize resources in the document: 1. Resources which are not used on the document pages are removed; 2. Equal resources are joined into one object; 3. Unused objects are deleted. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Optimize resources in the document: 1. Resources which are not used on the document pages are removed; 2. Equal resources are joined into one object; 3. Unused objects are deleted. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | Organizes page tree nodes in a document into a balanced tree. Only if the document has more than nodesNumInSubtrees page objects, otherwise it does nothing. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | Organizes page tree nodes in a document into a balanced tree. Only if the document has more than nodesNumInSubtrees page objects, otherwise it does nothing. |
| [preSave](#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-) | Internal method |
| [processParagraphs](#processParagraphs--) | Stores document into stream. |
| [removeMetadata](#removeMetadata--) | Removes metadata from the document. |
| [removePdfaCompliance](#removePdfaCompliance--) | Remove pdfa compliance from the document |
| [removePdfUaCompliance](#removePdfUaCompliance--) | Remove pdfUa compliance from the document |
| [repair](#repair--) | Repairs broken document. |
| [repair](#repair-com.aspose.pdf.Document.RepairOptions-) | Repairs broken document. |
| [resumeUpdate](#resumeUpdate--) | resumes document update |
| [save](#save--) | <p> Save document incrementally (i.e. using incremental update technique). </p> <hr> <p> In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save(); </p> In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally. |
| [save](#save-java.io.OutputStream-) | <p> Save document incrementally (i.e. using incremental update technique). </p> <hr> <p> In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save(); </p> In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | <p> Save document incrementally (i.e. using incremental update technique). </p> <hr> <p> In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save(); </p> In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | <p> Save document incrementally (i.e. using incremental update technique). </p> <hr> <p> In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save(); </p> In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally. |
| [save](#save-com.aspose.pdf.SaveOptions-) | <p> Save document incrementally (i.e. using incremental update technique). </p> <hr> <p> In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save(); </p> In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally. |
| [save](#save-com.aspose.ms.System.IO.Stream-) | <p> Save document incrementally (i.e. using incremental update technique). </p> <hr> <p> In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save(); </p> In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally. |
| [save](#save-java.lang.String-) | <p> Save document incrementally (i.e. using incremental update technique). </p> <hr> <p> In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save(); </p> In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveFormat-) | <p> Save document incrementally (i.e. using incremental update technique). </p> <hr> <p> In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save(); </p> In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | <p> Save document incrementally (i.e. using incremental update technique). </p> <hr> <p> In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save(); </p> In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | Saves incrementally the PDF Document to the specified stream. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Saves incrementally the PDF Document to the specified stream. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | Saves incrementally the PDF Document to the specified stream. |
| [saveXml](#saveXml-java.lang.String-) | Save document to XML. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Sends the certain pages of the document to the document device for processing. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Sends the whole document to the document device for processing. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Sends the whole document to the document device for processing. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Sends the whole document to the document device for processing. |
| [setAbsentFontHandler](#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-) | Notification about missing fonts while processing documents. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | Setting flag for set program determined font in case of absense font. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | Allows to merge page contents to optimize docuement size. |
| [setBackground](#setBackground-java.awt.Color-) | Sets the background color of the document. |
| [setCenterWindow](#setCenterWindow-boolean-) | Sets flag specifying whether position of the document's window will be centered on the screen. |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | Sets collection of document. |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | Gets convert parameter for pdf/ua converter (Convert only Metadata and Document Catalog if set true) |
| [setDefaultFileSizeLimitToMemoryLoading](#setDefaultFileSizeLimitToMemoryLoading--) | Sets the file size limit for loading an entire file into memory to default value equals 210 Mb. |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | Sets reading order of text: L2R (left to right) or R2L (right to left). |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Many operations with font can't be executed if these operations are prohibited by license of this font. |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | Sets flag specifying whether document's window title bar should display document title. |
| [setDuplex](#setDuplex-int-) | Gets or sets print duplex mode handling option to use when printing the file from the print dialog. |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. |
| [setEnableNotificationLogging](#setEnableNotificationLogging-boolean-) | Gets or sets a value indicating whether to enable the logging of notifications. |
| [setEnableObjectUnload](#setEnableObjectUnload-boolean-) | Get or sets flag which enables document partially be unloaded from memory. |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | Gets or sets flag to manage signature fields sanitization. |
| [setFileSizeLimitToMemoryLoading](#setFileSizeLimitToMemoryLoading-int-) | Get and set the file size limit for loading an entire file into memory. |
| [setFitWindow](#setFitWindow-boolean-) | Sets flag specifying whether document window must be resized to fit the first displayed page. |
| [setHandleSignatureChange](#setHandleSignatureChange-boolean-) | Throw Exception if the document will save with changes and have signature |
| [setHideMenubar](#setHideMenubar-boolean-) | Sets flag specifying whether menu bar should be hidden when document is active. |
| [setHideToolBar](#setHideToolBar-boolean-) | Set flag specifying whether toolbar should be hidden when document is active. |
| [setHideWindowUI](#setHideWindowUI-boolean-) | Sets flag specifying whether user interface elements should be hidden when document is active. |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | Gets or sets flag of ignoring errors in source files. When pages from source document copied into destination document, copying process is stopped with exception if some objects in source files are corrupted when this flag is false. example: dest.Pages.Add(src.Pages); If this flag is set to true then corrupted objects will be replaced with empty values. By default: true. |
| [setLinearized](#setLinearized-boolean-) | Sets a value indicating whether document is linearized. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | By default, method save closes internal streams and release memory resources. We can do some operations and continue work with the document after method save is called if this ManualDispose parameter is enabled. But it is strongly recommended to call the dispose method when the Document instance is no longer needed. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | Sets page mode, specifying how to display the document on exiting full-screen mode. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | <p> Sets action performed at document opening. <p> |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Sets optimization flag. When pages are added to document, equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Sets the page info.(for generator only, not filled in when reading document) |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | Sets page layout which shall be used when the document is opened. |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | Sets page mode, specifying how document should be displayed when opened. |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | Sets a flag specifying whether the PDF page size shall be used to select the input paper tray. |
| [setPrintScaling](#setPrintScaling-int-) | Sets print scaling handling option to use when printing the file from the print dialog. |
| [setSkipPdfaCompliantValidationBeforeSave](#setSkipPdfaCompliantValidationBeforeSave-boolean-) | By default pdfa validation process is necessary to update or remove pdfa if some rules were broken. |
| [setTitle](#setTitle-java.lang.String-) | Set Title for Pdf Document |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | Set XMP metadata of document. |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | Gets or sets the is document pdfa compliant. |
| [suppressUpdate](#suppressUpdate--) | Suppresses update contents data for all pages The contents is not updated until ResumeUpdate is called |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Validate document into the specified file. |
| [validate](#validate-com.aspose.pdf.PdfFormatConversionOptions-) | Validate document into the specified file. |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Validate document into the specified file. |

### DefaultNodesNumInSubtrees {#DefaultNodesNumInSubtrees}
```
public static final byte DefaultNodesNumInSubtrees
```



### FontSubstitution {#FontSubstitution}
```
public final PdfEvent <com.aspose.pdf.ADocument.FontSubstitutionHandler> FontSubstitution
```

It occurs when font replaces another font in document.

### Document {#Document--}
```
public Document()
```

Initializes empty document.

### Document {#Document-byte:A-}
```
public Document(byte[] input)
```

Initialize new Document instance from the {@code input} byte array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input |  | byte array with pdf document. |

### Document {#Document-java.io.InputStream-}
Initializes empty document.

### Document {#Document-java.io.InputStream-boolean-}
Initializes empty document.

### Document {#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-}
Initializes empty document.

### Document {#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-}
Initializes empty document.

### Document {#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-}
Initializes empty document.

### Document {#Document-java.io.InputStream-java.lang.String-}
Initializes empty document.

### Document {#Document-java.io.InputStream-java.lang.String-boolean-}
Initializes empty document.

### Document {#Document-java.io.InputStream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initializes empty document.

### Document {#Document-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initializes empty document.

### Document {#Document-com.aspose.pdf.PdfVersion-}
Initializes empty document.

### Document {#Document-com.aspose.ms.System.IO.Stream-}
Initializes empty document.

### Document {#Document-com.aspose.ms.System.IO.Stream-com.aspose.pdf.LoadOptions-}
Initializes empty document.

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-}
Initializes empty document.

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initializes empty document.

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initializes empty document.

### Document {#Document-java.lang.String-}
Initializes empty document.

### Document {#Document-java.lang.String-boolean-}
Initializes empty document.

### Document {#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-}
Initializes empty document.

### Document {#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-}
Initializes empty document.

### Document {#Document-java.lang.String-com.aspose.pdf.LoadOptions-}
Initializes empty document.

### Document {#Document-java.lang.String-java.lang.String-}
Initializes empty document.

### Document {#Document-java.lang.String-java.lang.String-boolean-}
Initializes empty document.

### Document {#Document-java.lang.String-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initializes empty document.

### Document {#Document-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initializes empty document.

### afterImport {#afterImport--}
```
public void afterImport()
```

Enumerate all registered annotations and call AfterImport for each of them.

### bindXml {#bindXml-java.io.InputStream-}
Bind xml to document

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-}
Bind xml/xsl to document

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-}
Bind xml/xsl to document

### bindXml {#bindXml-java.lang.String-}
Bind xml to document

### bindXml {#bindXml-java.lang.String-java.lang.String-}
Bind xml/xsl to document

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
Changes document passwords. This action can be done only using owner password.

### check {#check-boolean-}
```
public boolean check(boolean doRepair)
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
public void close()
```

Closes all resources used by this document.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
Recognize images inside the document and add hocr strings over it.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
Convert document and save errors into the specified file.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
Convert document and save errors into the specified file.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
Convert document and save errors into the specified file.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
Convert document and save errors into the specified file.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
Convert document and save errors into the specified file.

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-}
Convert document by applying the Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-}
Convert document by applying the Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-}
Convert document by applying the Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-}
Convert document by applying the Fixup.

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Converts stream in source format into stream in destination format.

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
Converts stream in source format into destination file in destination format.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Convert document and save errors into the specified stream.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Convert document and save errors into the specified file.

### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
Convert document using specified conversion options

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Converts source file in source format into stream in destination format.

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
Converts source file in source format into destination file in destination format.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Convert document and save errors into the specified file.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Convert document and save errors into the specified file.

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Convert document and save errors into the specified stream.

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
Convert page to PNG for DSR, OMR, OCR image stream.

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
Convert document to searchable document and skip errors of hochr that can not be converted.

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
Convert document to searchable document and skip errors of hochr that can not be converted.

### decrypt {#decrypt--}
```
public void decrypt()
```

Decrypts the document. Call then Save to obtain decrypted version of the document.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Closes all resources used by this document. This method is obsolete, use close() instead.

### encrypt {#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-}
Encrypts the document.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
Encrypts the document. Call then Save to get encrypted version of the document.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Encrypts the document.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
Encrypts the document. Call then Save to get encrypted version of the document.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
Encrypts the document. Call then Save to get encrypted version of the document.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Encrypts the document.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.io.OutputStream-}
Export all document annotations into stream.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
Exports all document annotations to XFDF file

### flatten {#flatten--}
```
public void flatten()
```

Removes all fields (and annotations) from the document and place their values instead.

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
Removes all fields (and annotations) from the document and place their values instead.

### flattenTransparency {#flattenTransparency--}
```
public void flattenTransparency()
```

Replaces transparent content with non-transparent raster and vector graphics.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Clears memory

### getAbsentFontHandler {#getAbsentFontHandler--}
```
public com.aspose.pdf.ADocument.AbsentFontHandler getAbsentFontHandler()
```

Notification about missing fonts while processing documents.

**Returns:**
ADocument.AbsentFontHandler instance

### getActions {#getActions--}
```
public DocumentActionCollection getActions()
```

<p> Gets document actions. This property is instance of DocumentActions class which allows to get/set BeforClosing, BeforSaving, etc. actions. </p>

**Returns:**
DocumentActionCollection object <hr> <pre> This example demonstrates how to obtain after open action of the document: Document document = new Document("PdfWithOpenAction.pdf"); DocumentActionCollection actions = document.getActions(); PdfAction afterSavingAction = actions.getAfterSaving(); </pre>

### getAllowReusePageContent {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```

Allows to merge page contents to optimize docuement size.

**Returns:**
value boolean value

### getBackground {#getBackground--}
```
public Color getBackground()
```

Gets the background color of the document.

**Returns:**
Color object

### getCatalogValue {#getCatalogValue-java.lang.String-}
Returns item value from catalog dictionary.

### getCollection {#getCollection--}
```
public Collection getCollection()
```

Gets collection of document.

**Returns:**
Collection object

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
public CryptoAlgorithm getCryptoAlgorithm()
```

Gets security settings if document is encrypted. If document is not encrypted then corresponding exception will be raised in .net 1.1 or CryptoAlgorithm will be null for other .net versions.

**Returns:**
CryptoAlgorithm element @see CryptoAlgorithm

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
public final com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

Gets a custom security handler.

**Returns:**
ICustomSecurityHandler instance

### getDefaultCopier {#getDefaultCopier--}
```
public Copier getDefaultCopier()
```

Returns copier used for coping pages to this document.

**Returns:**
Copier object

### getDestinations {#getDestinations--}
```
public DestinationCollection getDestinations()
```

Gets the collection of destinations.

**Returns:**
DestinationCollection element

### getDirection {#getDirection--}
```
public Direction getDirection()
```

Gets reading order of text: L2R (left to right) or R2L (right to left).

**Returns:**
Direction element @see Direction

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

Gets or sets print duplex mode handling option to use when printing the file from the print dialog.

**Returns:**
PrintDuplex element

### getEmbeddedFiles {#getEmbeddedFiles--}
```
public EmbeddedFileCollection getEmbeddedFiles()
```

Gets collection of files embedded to document.

**Returns:**
EmbeddedFileCollection object

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
public boolean getEmbedStandardFonts()
```

Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true.

**Returns:**
boolean value

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
public final boolean getEnableSignatureSanitization()
```

Gets or sets flag to manage signature fields sanitization.

**Returns:**
boolean value

### getEngineDoc {#getEngineDoc--}
```
public com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

Instance of IPdfDocument used to access to internal document structure. Internal only

**Returns:**
IPdfDocument object

### getFileName {#getFileName--}
```
public String getFileName()
```

Name of the PDF file that caused this document

**Returns:**
String object

### getFileSizeLimitToMemoryLoading {#getFileSizeLimitToMemoryLoading--}
```
public static int getFileSizeLimitToMemoryLoading()
```

Get and set the file size limit for loading an entire file into memory.

**Returns:**
int value

### getFontUtilities {#getFontUtilities--}
```
public Document.IDocumentFontUtilities getFontUtilities()
```

IDocumentFontUtilities instance

**Returns:**
IDocumentFontUtilities instance

### getForm {#getForm--}
```
public Form getForm()
```

Gets Acro Form of the document.

**Returns:**
Form object

### getId {#getId--}
```
public Id getId()
```

Gets the ID.

**Returns:**
Id object

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```

Gets or sets flag of ignoring errors in source files. When pages from source document copied into destination document, copying process is stopped with exception if some objects in source files are corrupted when this flag is false. example: dest.Pages.Add(src.Pages); If this flag is set to true then corrupted objects will be replaced with empty values. By default: true.

**Returns:**
boolean value

### getInfo {#getInfo--}
```
public DocumentInfo getInfo()
```

Gets document info.

**Returns:**
DocumentInfo object

### getJavaScript {#getJavaScript--}
```
public JavaScriptCollection getJavaScript()
```

Collection of JavaScript of document level.

**Returns:**
JavaScriptCollection object

### getLogicalStructure {#getLogicalStructure--}
```
public RootElement getLogicalStructure()
```

Gets logical structure of the document.

**Returns:**
RootElement object

### getMetadata {#getMetadata--}
```
public Metadata getMetadata()
```

Document metadata. (A PDF document may include general information, such as the document's title, author, and creation and modification dates. Such global information about the document (as opposed to its content or structure) is called metadata and is intended to assist in cataloguing and searching for documents in external databases.)

**Returns:**
Metadata object

### getMetadataStream {#getMetadataStream--}
```
public com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

Returns raw metadata stream

**Returns:**
IPdfStreamAccessor object

### getNamedDestinations {#getNamedDestinations--}
```
public NamedDestinationCollection getNamedDestinations()
```

Collection of Named Destination in the document.

**Returns:**
NamedDestinationCollection instance

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
public PageMode getNonFullScreenPageMode()
```

Gets page mode, specifying how to display the document on exiting full-screen mode.

**Returns:**
PageMode element @see PageMode

### getObjectById {#getObjectById-java.lang.String-}
Gets a object with specified ID in the document.

### getOpenAction {#getOpenAction--}
```
public IAppointment getOpenAction()
```

<p> Gets action performed at document opening. </p> <hr> <pre> Example demonstrates how to get CenterWindow flag: Document document = new Document("sample.pdf"); IAppointment value = document.getOpenAction(); </pre>

**Returns:**
IAppointment object

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Gets optimization flag. When pages are added to document, equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false.

**Returns:**
boolean value

### getOutlines {#getOutlines--}
```
public OutlineCollection getOutlines()
```

Gets document outlines.

**Returns:**
OutlineCollection object

### getOutputIntents {#getOutputIntents--}
```
public final OutputIntents getOutputIntents()
```

Gets the collection of Output intents in the document.

**Returns:**
OutputIntents instance

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Gets the page info.(for generator only, not filled in when reading document)

**Returns:**
The page info.

### getPageLabels {#getPageLabels--}
```
public PageLabelCollection getPageLabels()
```

Gets page labels in the document.

**Returns:**
PageLabelCollection object

### getPageLayout {#getPageLayout--}
```
public PageLayout getPageLayout()
```

Gets page layout which shall be used when the document is opened.

**Returns:**
PageLayout element @see PageLayout

### getPageMode {#getPageMode--}
```
public PageMode getPageMode()
```

Gets page mode, specifying how document should be displayed when opened.

**Returns:**
PageMode element @see PageMode

### getPages {#getPages--}
```
public PageCollection getPages()
```

<p> Gets collection of document pages. Note that pages are numbered from 1 in collection. </p>

**Returns:**
PageCollection object <hr> <pre> Example below demonstrates how to operate with the document pages: How to obtain number of pages and how to obtain rectangle of starting page of the document. Document document = new Document("sample.pdf"); PageCollection pages = document.getPages(); System.out.println("Document contains " + pages.size()); Page page = pages.get_Item(1); Rectangle rect = page.getRect(); </pre>

### getPdfFormat {#getPdfFormat--}
```
public PdfFormat getPdfFormat()
```

Gets pdfa format

**Returns:**
PdfFormat element @see PdfFormat

### getPermissions {#getPermissions--}
```
public int getPermissions()
```

Gets permissions of the document.

**Returns:**
int value

### getPrintScaling {#getPrintScaling--}
```
public int getPrintScaling()
```

Gets print scaling handling option to use when printing the file from the print dialog.

**Returns:**
PrintScaling element

### getTaggedContent {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```

Gets access to TaggedPdf content. The example demonstrates how to use tagged content for creating new document with header, paragraphs and images. // Create new document Document document = new Document(); // Get the tagged content ITaggedContent taggedContent = document.getTaggedContent(); // Set language for document taggedContent.setLanguage("en-US"); // Set title for PDF document taggedContent.setTitle("Example document"); // Creating and adding Section SectElement sect = taggedContent.createSectElement(); taggedContent.getRootElement().appendChild(sect); // Create Header HeaderElement h1 = taggedContent.createHeaderElement(1); h1.setText("The Header"); sect.appendChild(h1); // Create paragraph ParagraphElement p = taggedContent.createParagraphElement(); p.setTag("Paragraph"); p.setText("The text of paragraph."); sect.appendChild(p); // Create illustration IllustrationElement figure1 = taggedContent.createFigureElement(); sect.appendChild(figure1); figure1.setAlternativeText("Figure 1"); figure1.setTitle("Image 1"); figure1.setTag("Fig"); figure1.setImage("path/of/image.jpg"); // Save document document.save("example.pdf");

**Returns:**
ITaggedContent instance

### getVersion {#getVersion--}
```
public String getVersion()
```

Gets a version of Pdf from Pdf file header.

**Returns:**
String value

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
Get XMP metadata from document.

### hasIncrementalUpdate {#hasIncrementalUpdate--}
```
public final boolean hasIncrementalUpdate()
```

Checks if the current PDF document has been saved with incremental updates.

**Returns:**
true if the PDF document has incremental updates; otherwise, false .

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.io.InputStream-}
Imports annotations from stream to document.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
Imports annotations from XFDF file to document.

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
public boolean isAbsentFontTryToSubstitute()
```

Flag which informs about replacement of missing font.

**Returns:**
boolean value

### isCenterWindow {#isCenterWindow--}
```
public boolean isCenterWindow()
```

<p> Gets flag specifying whether position of the document's window will be centered on the screen. </p>

**Returns:**
boolean value <hr> <pre> Example demonstrates how to get CenterWindow flag: Document document = new Document("sample.pdf"); boolean value = document.isCenterWindow(); </pre>

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

Many operations with font can't be executed if these operations are prohibited by license of this font.

**Returns:**
boolean value By default false.

### isDisplayDocTitle {#isDisplayDocTitle--}
```
public boolean isDisplayDocTitle()
```

<p> Gets flag specifying whether document's window title bar should display document title. </p>

**Returns:**
boolean value <hr> <pre> Example demonstrates how to get DisplayDocTitle flag: Document document = new Document("sample.pdf"); boolean value = document.isDisplayDocTitle(); </pre>

### isEnableNotificationLogging {#isEnableNotificationLogging--}
```
public final boolean isEnableNotificationLogging()
```

Gets or sets a value indicating whether to enable the logging of notifications.

**Returns:**
boolean value

### isEnableObjectUnload {#isEnableObjectUnload--}
```
public boolean isEnableObjectUnload()
```

Get or sets flag which enables document partially be unloaded from memory.

**Returns:**
boolean value

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

Gets encrypted status of the document. True if document is encrypted.

**Returns:**
boolean value

### isFitWindow {#isFitWindow--}
```
public boolean isFitWindow()
```

<p> Gets flag specifying whether document window must be resized to fit the first displayed page. </p>

**Returns:**
boolean value <hr> <pre> Example demonstrates how to get FitWindow flag: Document document = new Document("sample.pdf"); boolean value = document.isFitWindow(); </pre>

### isHandleSignatureChange {#isHandleSignatureChange--}
```
public final boolean isHandleSignatureChange()
```

Throw Exception if the document will save with changes and have signature

**Returns:**
boolean value

### isHideMenubar {#isHideMenubar--}
```
public boolean isHideMenubar()
```

<p> Gets flag specifying whether menu bar should be hidden when document is active. </p>

**Returns:**
boolean value <hr> <pre> Example demonstrates how to get HideMenubar flag: Document document = new Document("sample.pdf"); boolean value = document.isHideMenubar(); </pre>

### isHideToolBar {#isHideToolBar--}
```
public boolean isHideToolBar()
```

<p> Gets flag specifying whether toolbar should be hidden when document is active. </p>

**Returns:**
boolean value <hr> <pre> Example demonstrates how to get HideToolBar flag: Document document = new Document("sample.pdf"); boolean value = document.isHideToolBar(); </pre>

### isHideWindowUI {#isHideWindowUI--}
```
public boolean isHideWindowUI()
```

<p> Gets flag specifying whether user interface elements should be hidden when document is active. </p>

**Returns:**
boolean value <hr> <pre> Example demonstrates how to get HideWindowUI flag: Document document = new Document("sample.pdf"); boolean value = document.isHideWindowUI(); </pre>

### isLicensed {#isLicensed--}
```
public static boolean isLicensed()
```

Gets licensed state of the system.

**Returns:**
boolean value

### isLinearized {#isLinearized--}
```
public boolean isLinearized()
```

Gets a value indicating whether document is linearized.

**Returns:**
boolean value

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
public boolean isManualDisposeEnabled()
```

By default, method save close internal streams and release memory resources. We can do some operations and continue work with the document after method save if this ManualDispose parameter is enabled.

**Returns:**
boolean value. (Default value == false)

### isPdfaCompliant {#isPdfaCompliant--}
```
public boolean isPdfaCompliant()
```

Gets the is document pdfa compliant.

**Returns:**
boolean value

### isPdfUaCompliant {#isPdfUaCompliant--}
```
public boolean isPdfUaCompliant()
```

Gets the is document pdfua compliant.

**Returns:**
boolean value

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
public final boolean isPickTrayByPdfSize()
```

Gets a flag specifying whether the PDF page size shall be used to select the input paper tray.

**Returns:**
boolean value

### isRepairNeeded {#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-}
Checks if document requires Repair method call.

### isSkippedPdfaCompliantValidationBeforeSave {#isSkippedPdfaCompliantValidationBeforeSave--}
```
public boolean isSkippedPdfaCompliantValidationBeforeSave()
```

By default pdfa validation process is necessary to update or remove pdfa compliant data if some rules were broken.

**Returns:**
boolean value

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
public boolean isXrefGapsAllowed()
```

Gets or sets the is document pdfa compliant.

**Returns:**
boolean value

### loadFrom {#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-}
Loads a file, converting it to PDF.

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
Merges documents.

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
Merges documents.

### merge {#merge-com.aspose.pdf.Document...-}
Merges documents.

### merge {#merge-java.lang.String...-}
Merges pdf files.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
Merges documents.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
Merges documents.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.Document...-}
Merges documents.

### mergeDocuments {#mergeDocuments-java.lang.String...-}
Merges pdf files.

### optimize {#optimize--}
```
public void optimize()
```

Linearize document in order to - open the first page as quickly as possible; - display next page or follow by link to the next page as quickly as possible; - display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first); - permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed. Invoking this method doesn't actually saves the document. On the contrary the document only is prepared to have optimized structure, call then Save to get optimized document.

### optimizeResources {#optimizeResources--}
```
public void optimizeResources()
```

Optimize resources in the document: 1. Resources which are not used on the document pages are removed; 2. Equal resources are joined into one object; 3. Unused objects are deleted.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
Optimize resources in the document: 1. Resources which are not used on the document pages are removed; 2. Equal resources are joined into one object; 3. Unused objects are deleted.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
public void pageNodesToBalancedTree()
```

Organizes page tree nodes in a document into a balanced tree. Only if the document has more than nodesNumInSubtrees page objects, otherwise it does nothing.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
public void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

Organizes page tree nodes in a document into a balanced tree. Only if the document has more than nodesNumInSubtrees page objects, otherwise it does nothing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| nodesNumInSubtrees |  | Desired number of subnodes. |

### preSave {#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-}
Internal method

### processParagraphs {#processParagraphs--}
```
public void processParagraphs()
```

Stores document into stream.

### removeMetadata {#removeMetadata--}
```
public void removeMetadata()
```

Removes metadata from the document.

### removePdfaCompliance {#removePdfaCompliance--}
```
public void removePdfaCompliance()
```

Remove pdfa compliance from the document

### removePdfUaCompliance {#removePdfUaCompliance--}
```
public void removePdfUaCompliance()
```

Remove pdfUa compliance from the document

### repair {#repair--}
```
public void repair()
```

Repairs broken document.

### repair {#repair-com.aspose.pdf.Document.RepairOptions-}
Repairs broken document.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

resumes document update

### save {#save--}
```
public void save()
```

<p> Save document incrementally (i.e. using incremental update technique). </p> <hr> <p> In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save(); </p> In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally.

### save {#save-java.io.OutputStream-}
<p> Save document incrementally (i.e. using incremental update technique). </p> <hr> <p> In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save(); </p> In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
<p> Save document incrementally (i.e. using incremental update technique). </p> <hr> <p> In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save(); </p> In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
<p> Save document incrementally (i.e. using incremental update technique). </p> <hr> <p> In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save(); </p> In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally.

### save {#save-com.aspose.pdf.SaveOptions-}
<p> Save document incrementally (i.e. using incremental update technique). </p> <hr> <p> In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save(); </p> In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally.

### save {#save-com.aspose.ms.System.IO.Stream-}
<p> Save document incrementally (i.e. using incremental update technique). </p> <hr> <p> In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save(); </p> In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally.

### save {#save-java.lang.String-}
<p> Save document incrementally (i.e. using incremental update technique). </p> <hr> <p> In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save(); </p> In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally.

### save {#save-java.lang.String-com.aspose.pdf.SaveFormat-}
<p> Save document incrementally (i.e. using incremental update technique). </p> <hr> <p> In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save(); </p> In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally.

### save {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
<p> Save document incrementally (i.e. using incremental update technique). </p> <hr> <p> In order to save document incrementally we should open the document file for writing. Therefore Document must not be initialized with InputStream but with path to the file, like in the next code snippet: Document doc = new Document("document.pdf"); // make some changes and save the document incrementally doc.save(); </p> In case when document was initialized with InputStream, writing to InputStream is impossible, so we recommend to use separate methods "save" to save document or "saveIncrementally" to save document incrementally.

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

### setAbsentFontHandler {#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-}
Notification about missing fonts while processing documents.

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
public void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```

Setting flag for set program determined font in case of absense font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| setAbsentFontTryToSubstitute |  |  |

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```

Allows to merge page contents to optimize docuement size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setBackground {#setBackground-java.awt.Color-}
Sets the background color of the document.

### setCenterWindow {#setCenterWindow-boolean-}
```
public void setCenterWindow(boolean value)
```

Sets flag specifying whether position of the document's window will be centered on the screen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
Sets collection of document.

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
public final void setConvertMetadataAndCatalogOnly(boolean value)
```

Gets convert parameter for pdf/ua converter (Convert only Metadata and Document Catalog if set true)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setDefaultFileSizeLimitToMemoryLoading {#setDefaultFileSizeLimitToMemoryLoading--}
```
public static void setDefaultFileSizeLimitToMemoryLoading()
```

Sets the file size limit for loading an entire file into memory to default value equals 210 Mb.

### setDirection {#setDirection-com.aspose.pdf.Direction-}
Sets reading order of text: L2R (left to right) or R2L (right to left).

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

Many operations with font can't be executed if these operations are prohibited by license of this font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value By default false. |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
public void setDisplayDocTitle(boolean value)
```

Sets flag specifying whether document's window title bar should display document title.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

Gets or sets print duplex mode handling option to use when printing the file from the print dialog.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | PrintDuplex element |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
public void setEmbedStandardFonts(boolean value)
```

Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setEnableNotificationLogging {#setEnableNotificationLogging-boolean-}
```
public final void setEnableNotificationLogging(boolean value)
```

Gets or sets a value indicating whether to enable the logging of notifications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setEnableObjectUnload {#setEnableObjectUnload-boolean-}
```
public void setEnableObjectUnload(boolean value)
```

Get or sets flag which enables document partially be unloaded from memory.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
public final void setEnableSignatureSanitization(boolean value)
```

Gets or sets flag to manage signature fields sanitization.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setFileSizeLimitToMemoryLoading {#setFileSizeLimitToMemoryLoading-int-}
```
public static void setFileSizeLimitToMemoryLoading(int value)
```

Get and set the file size limit for loading an entire file into memory.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setFitWindow {#setFitWindow-boolean-}
```
public void setFitWindow(boolean value)
```

Sets flag specifying whether document window must be resized to fit the first displayed page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setHandleSignatureChange {#setHandleSignatureChange-boolean-}
```
public final void setHandleSignatureChange(boolean value)
```

Throw Exception if the document will save with changes and have signature

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setHideMenubar {#setHideMenubar-boolean-}
```
public void setHideMenubar(boolean value)
```

Sets flag specifying whether menu bar should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setHideToolBar {#setHideToolBar-boolean-}
```
public void setHideToolBar(boolean value)
```

Set flag specifying whether toolbar should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
public void setHideWindowUI(boolean value)
```

Sets flag specifying whether user interface elements should be hidden when document is active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```

Gets or sets flag of ignoring errors in source files. When pages from source document copied into destination document, copying process is stopped with exception if some objects in source files are corrupted when this flag is false. example: dest.Pages.Add(src.Pages); If this flag is set to true then corrupted objects will be replaced with empty values. By default: true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setLinearized {#setLinearized-boolean-}
```
public void setLinearized(boolean value)
```

Sets a value indicating whether document is linearized.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
public void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

By default, method save closes internal streams and release memory resources. We can do some operations and continue work with the document after method save is called if this ManualDispose parameter is enabled. But it is strongly recommended to call the dispose method when the Document instance is no longer needed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| manualDisposeEnabled |  | boolean value. (Default value == false) |

### setNonFullScreenPageMode {#setNonFullScreenPageMode-com.aspose.pdf.PageMode-}
Sets page mode, specifying how to display the document on exiting full-screen mode.

### setOpenAction {#setOpenAction-com.aspose.pdf.IAppointment-}
<p> Sets action performed at document opening. <p>

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Sets optimization flag. When pages are added to document, equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false.

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
public final void setPickTrayByPdfSize(boolean value)
```

Sets a flag specifying whether the PDF page size shall be used to select the input paper tray.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setPrintScaling {#setPrintScaling-int-}
```
public void setPrintScaling(int value)
```

Sets print scaling handling option to use when printing the file from the print dialog.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | PrintDuplex element |

### setSkipPdfaCompliantValidationBeforeSave {#setSkipPdfaCompliantValidationBeforeSave-boolean-}
```
public void setSkipPdfaCompliantValidationBeforeSave(boolean pdfaCompliantValidationBeforeSave)
```

By default pdfa validation process is necessary to update or remove pdfa if some rules were broken.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfaCompliantValidationBeforeSave |  | boolean value |

### setTitle {#setTitle-java.lang.String-}
Set Title for Pdf Document

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
Set XMP metadata of document.

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
public void setXrefGapsAllowed(boolean value)
```

Gets or sets the is document pdfa compliant.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Suppresses update contents data for all pages The contents is not updated until ResumeUpdate is called

### updatePages {#updatePages--}
```
public void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
Validate document into the specified file.

### validate {#validate-com.aspose.pdf.PdfFormatConversionOptions-}
Validate document into the specified file.

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
Validate document into the specified file.
