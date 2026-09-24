---
title: "Document Class"
linktitle: "Document"
articleTitle: "Document"
second_title: "Aspose.PDF for .NET"
description: "Class representing PDF document."
type: docs
weight: 610
url: "/net/aspose.pdf/document/"
keywords: "Document, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Document class

Class representing PDF document.

```csharp
public sealed class Document : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [Document](./document/#constructor) | Initializes empty document. |
| [Document](./document/#constructor_1)(*Stream*) | Initialize new Document instance from the stream. |
| [Document](./document/#constructor_2)(*string*) | Just init Document using . The same as `#ctor`. |
| [Document](./document/#constructor_3)(*[PdfVersion](../../aspose.pdf/pdfversion/)*) | Initializes empty document by version. |
| [Document](./document/#constructor_4)(*Stream, bool*) | Initialize new Document instance from the stream. |
| [Document](./document/#constructor_5)(*Stream, string*) | Initialize new Document instance from the stream. |
| [Document](./document/#constructor_6)(*Stream, [CertificateEncryptionOptions](../../aspose.pdf.security/certificateencryptionoptions/)*) | Initialize new Document instance from the stream. |
| [Document](./document/#constructor_7)(*string, [CertificateEncryptionOptions](../../aspose.pdf.security/certificateencryptionoptions/)*) | Initializes new instance of the [`Document`](../../aspose.pdf/document/) class for working with encrypted document. |
| [Document](./document/#constructor_8)(*string, bool*) | Just init Document using . The same as `#ctor`. |
| [Document](./document/#constructor_9)(*string, string*) | Initializes new instance of the [`Document`](../../aspose.pdf/document/) class for working with encrypted document. |
| [Document](./document/#constructor_10)(*string, [LoadOptions](../../aspose.pdf/loadoptions/)*) | Opens an existing document from a file providing necessary converting options to get pdf document. |
| [Document](./document/#constructor_11)(*Stream, [LoadOptions](../../aspose.pdf/loadoptions/)*) | Opens an existing document from a stream providing necessary converting to get pdf document. |
| [Document](./document/#constructor_12)(*Stream, [CertificateEncryptionOptions](../../aspose.pdf.security/certificateencryptionoptions/), bool*) | Initialize new Document instance from the stream. |
| [Document](./document/#constructor_13)(*string, [CertificateEncryptionOptions](../../aspose.pdf.security/certificateencryptionoptions/), bool*) | Initializes new instance of the [`Document`](../../aspose.pdf/document/) class for working with encrypted document. |
| [Document](./document/#constructor_14)(*Stream, string, [ICustomSecurityHandler](../../aspose.pdf.security/icustomsecurityhandler/)*) | Initialize new Document instance from the stream. |
| [Document](./document/#constructor_15)(*Stream, string, bool*) | Initialize new Document instance from the stream. |
| [Document](./document/#constructor_16)(*string, string, [ICustomSecurityHandler](../../aspose.pdf.security/icustomsecurityhandler/)*) | Initializes new instance of the [`Document`](../../aspose.pdf/document/) class for working with encrypted document. |
| [Document](./document/#constructor_17)(*string, string, bool*) | Initializes new instance of the [`Document`](../../aspose.pdf/document/) class for working with encrypted document. |
| [Document](./document/#constructor_18)(*Stream, string, bool, [ICustomSecurityHandler](../../aspose.pdf.security/icustomsecurityhandler/)*) | Initialize new Document instance from the stream. |
| [Document](./document/#constructor_19)(*string, string, bool, [ICustomSecurityHandler](../../aspose.pdf.security/icustomsecurityhandler/)*) | Initializes new instance of the [`Document`](../../aspose.pdf/document/) class for working with encrypted document. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](./actions/) { get; } | Gets document actions. This property is instance of DocumentActions class which allows to get/set BeforClosing, BeforSaving, etc. actions. |
| [AllowReusePageContent](./allowreusepagecontent/) { get; set; } | Allows to merge page contents to optimize docuement size. If used then differnet but duplicated pages may reference to the. |
| [Background](./background/) { get; set; } | Gets or sets the background color of the document. |
| [CenterWindow](./centerwindow/) { get; set; } | Gets or sets flag specifying whether position of the document's window will be centerd on the screen. |
| [Collection](./collection/) { get; set; } | Gets collection of document. |
| [CryptoAlgorithm](./cryptoalgorithm/) { get; } | Gets security settings if document is encrypted. |
| [CustomSecurityHandler](./customsecurityhandler/) { get; } | Gets a custom security handler. |
| [Destinations](./destinations/) { get; } | Gets the collection of destinations. |
| [Direction](./direction/) { get; set; } | Gets or sets reading order of text: L2R (left to right) or R2L (right to left). |
| [DisableFontLicenseVerifications](./disablefontlicenseverifications/) { get; set; } | Many operations with font can't be executed if these operations are prohibited by license of this font. |
| [DisplayDocTitle](./displaydoctitle/) { get; set; } | Gets or sets flag specifying whether document's window title bar should display document title. |
| [Duplex](./duplex/) { get; set; } | Gets or sets print duplex mode handling option to use when printing the file from the print dialog. |
| [EmbedStandardFonts](./embedstandardfonts/) { get; set; } | Property which declares that document must embed all standard Type1 fonts. |
| [EmbeddedFiles](./embeddedfiles/) { get; } | Gets collection of files embedded to document. |
| [EnableNotificationLogging](./enablenotificationlogging/) { get; set; } | Gets or sets a value indicating whether to enable the logging of notifications. |
| [EnableObjectUnload](./enableobjectunload/) { get; set; } | Get or sets flag which enables document partially be unloaded from memory. |
| [EnableSignatureSanitization](./enablesignaturesanitization/) { get; set; } | Gets or sets flag to manage signature fields sanitization. Enabled by default. |
| [FileName](./filename/) { get; } | Name of the PDF file that caused this document. |
| [FileSizeLimitToMemoryLoading](./filesizelimittomemoryloading/) { get; set; } | Get and set the file size limit for loading an entire file into memory. |
| [FitWindow](./fitwindow/) { get; set; } | Gets or sets flag specifying whether document window must be resized to fit the first displayed page. |
| [FontUtilities](./fontutilities/) { get; } | IDocumentFontUtilities instance. |
| [Form](./form/) { get; } | Gets Acro Form of the document. |
| [HandleSignatureChange](./handlesignaturechange/) { get; set; } | Throw Exception if the document will save with changes and have signature. |
| [HideMenubar](./hidemenubar/) { get; set; } | Gets or sets flag specifying whether menu bar should be hidden when document is active. |
| [HideToolBar](./hidetoolbar/) { get; set; } | Gets or sets flag specifying whether toolbar should be hidden when document is active. |
| [HideWindowUI](./hidewindowui/) { get; set; } | Gets or sets flag specifying whether user interface elements should be hidden when document is active. |
| [Id](./id/) { get; } | Gets the ID. |
| [IgnoreCorruptedObjects](./ignorecorruptedobjects/) { get; set; } | Gets or sets flag of ignoring errors in source files. |
| [Info](./info/) { get; } | Gets document info. |
| [IsEncrypted](./isencrypted/) { get; } | Gets encrypted status of the document. True if document is encrypted. |
| [IsLicensed](./islicensed/) { get; } | Gets licensed state of the system. Returns true is system works in licensed mode and false otherwise. |
| [IsLinearized](./islinearized/) { get; set; } | Gets or sets a value indicating whether document is linearized. |
| [IsPdfUaCompliant](./ispdfuacompliant/) { get; } | Gets the is document pdfua compliant. |
| [IsPdfaCompliant](./ispdfacompliant/) { get; } | Gets the is document pdfa compliant. |
| [IsXrefGapsAllowed](./isxrefgapsallowed/) { get; set; } | Gets or sets the is document pdfa compliant. |
| [JavaScript](./javascript/) { get; } | Collection of JavaScript of document level. |
| [LogicalStructure](./logicalstructure/) { get; } | Gets logical structure of the document. |
| [Metadata](./metadata/) { get; } | Document metadata. |
| [NamedDestinations](./nameddestinations/) { get; } | Collection of Named Destination in the document. |
| [NonFullScreenPageMode](./nonfullscreenpagemode/) { get; set; } | Gets or sets page mode, specifying how to display the document on exiting full-screen mode. |
| [OpenAction](./openaction/) { get; set; } | Gets or sets action performed at document opening. |
| [OptimizeSize](./optimizesize/) { get; set; } | Gets or sets optimization flag. When pages are added to document, equal resource streams in resultant file are. |
| [Outlines](./outlines/) { get; } | Gets document outlines. |
| [OutputIntents](./outputintents/) { get; } | Gets the collection of Output intents in the document. |
| [PageInfo](./pageinfo/) { get; set; } | Gets or sets the page info.(for generator only, not filled in when reading document). |
| [PageLabels](./pagelabels/) { get; } | Gets page labels in the document. |
| [PageLayout](./pagelayout/) { get; set; } | Gets or sets page layout which shall be used when the document is opened. |
| [PageMode](./pagemode/) { get; set; } | Gets or sets page mode, specifying how document should be displayed when opened. |
| [Pages](./pages/) { get; } | Gets or sets collection of document pages. |
| [PdfFormat](./pdfformat/) { get; } | Gets PDF format. |
| [Permissions](./permissions/) { get; } | Gets permissions of the document. |
| [PickTrayByPdfSize](./picktraybypdfsize/) { get; set; } | Gets or sets a flag specifying whether the PDF page size shall be used to select the input paper tray. |
| [PrintScaling](./printscaling/) { get; set; } | Gets or sets the page scaling option that shall be selected when a print dialog is displayed for this document. |
| [TaggedContent](./taggedcontent/) { get; } | Gets access to TaggedPdf content. |
| [Version](./version/) { get; } | Gets a version of Pdf from Pdf file header. |

## Methods

| Name | Description |
| --- | --- |
| [BindXml](./bindxml/)(*string*) | Bind xml to document. |
| [BindXml](./bindxml/)(*Stream*) | Bind xml to document. |
| [BindXml](./bindxml/)(*string, string*) | Bind xml/xsl to document. |
| [BindXml](./bindxml/)(*Stream, Stream*) | Bind xml/xsl to document. |
| [BindXml](./bindxml/)(*Stream, Stream, XmlReaderSettings*) | Bind xml/xsl to document. |
| [ChangePasswords](./changepasswords/)(*string, string, string*) | Changes document passwords. This action can be done only using owner password. |
| [Check](./check/)(*bool*) | Validates document. |
| [Convert](./convert/)(*PdfFormatConversionOptions*) | Convert document using specified conversion options. |
| [Convert](./convert/)(*CallBackGetHocrWithPage, bool*) |  |
| [Convert](./convert/)(*CallBackGetHocr, bool*) |  |
| [Convert](./convert/)(*string, PdfFormat, ConvertErrorAction*) | Convert document and save errors into the specified file. |
| [Convert](./convert/)(*Stream, PdfFormat, ConvertErrorAction*) | Convert document and save errors into the specified stream. |
| [Convert](./convert/)(*string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction*) | Convert document and save errors into the specified file. |
| [Convert](./convert/)(*Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction*) | Convert document and save errors into the specified file. |
| [Convert](./convert/)(*Fixup, Stream, bool, object[]*) | Convert document by applying the Fixup. |
| [Convert](./convert/)(*Fixup, string, bool, object[]*) | Convert document by applying the Fixup. |
| [Convert](./convert/)(*string, LoadOptions, string, SaveOptions*) | Converts source file in source format into destination file in destination format. |
| [Convert](./convert/)(*Stream, LoadOptions, string, SaveOptions*) | Converts stream in source format into destination file in destination format. |
| [Convert](./convert/)(*string, LoadOptions, Stream, SaveOptions*) | Converts source file in source format into stream in destination format. |
| [Convert](./convert/)(*Stream, LoadOptions, Stream, SaveOptions*) | Converts stream in source format into stream in destination format. |
| [ConvertPageToPNGMemoryStream](./convertpagetopngmemorystream/)(*Page*) | Convert page to PNG for DSR, OMR, OCR image stream. |
| [Decrypt](./decrypt/) | Decrypts the document. Call then Save to obtain decrypted version of the document. |
| [Dispose](./dispose/) | Closes all resources used by this document. |
| [Encrypt](./encrypt/)(*Permissions, CryptoAlgorithm, IList<X509Certificate2>*) | Encrypts the document. |
| [Encrypt](./encrypt/)(*string, string, DocumentPrivilege, ICustomSecurityHandler*) | Encrypts the document. |
| [Encrypt](./encrypt/)(*string, string, Permissions, ICustomSecurityHandler*) | Encrypts the document. |
| [Encrypt](./encrypt/)(*string, string, Permissions, CryptoAlgorithm*) | Encrypts the document. |
| [Encrypt](./encrypt/)(*string, string, DocumentPrivilege, CryptoAlgorithm, bool*) | Encrypts the document. |
| [Encrypt](./encrypt/)(*string, string, Permissions, CryptoAlgorithm, bool*) | Encrypts the document. |
| [ExportAnnotationsToXfdf](./exportannotationstoxfdf/)(*string*) | Exports all document annotations to XFDF file. |
| [ExportAnnotationsToXfdf](./exportannotationstoxfdf/)(*Stream*) | Export all document annotations into stream. |
| [Flatten](./flatten/) | Removes all fields from the document and place their values instead. |
| [Flatten](./flatten/)(*FlattenSettings*) |  |
| [FlattenTransparency](./flattentransparency/) | Replaces transparent content with non-transparent raster and vector graphics. |
| [FreeMemory](./freememory/) | Clears memory. |
| [GetCatalogValue](./getcatalogvalue/)(*string*) | Returns item value from catalog dictionary. |
| [GetObjectById](./getobjectbyid/)(*string*) | Gets a object with specified ID in the document. |
| [GetXmpMetadata](./getxmpmetadata/)(*Stream*) | Get XMP metadata from document. |
| [HasIncrementalUpdate](./hasincrementalupdate/) | Checks if the current PDF document has been saved with incremental updates. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(*string*) | Imports annotations from XFDF file to document. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(*Stream*) | Imports annotations from stream to document. |
| [IsRepairNeeded](./isrepairneeded/)(*RepairOptions*) |  |
| [LoadFrom](./loadfrom/)(*string, LoadOptions*) | Loads a file, converting it to PDF. |
| [Merge](./merge/)(*Document[]*) | Merges documents. |
| [Merge](./merge/)(*string[]*) | Merges pdf files. |
| [Merge](./merge/)(*MergeOptions, Document[]*) |  |
| [Merge](./merge/)(*MergeOptions, string[]*) |  |
| [MergeDocuments](./mergedocuments/)(*string[]*) | Merges pdf files. |
| [MergeDocuments](./mergedocuments/)(*Document[]*) | Merges documents. |
| [MergeDocuments](./mergedocuments/)(*MergeOptions, string[]*) |  |
| [MergeDocuments](./mergedocuments/)(*MergeOptions, Document[]*) |  |
| [Optimize](./optimize/) | Linearize the document in order to. |
| [OptimizeResources](./optimizeresources/) | Optimize resources in the document:. |
| [OptimizeResources](./optimizeresources/)(*OptimizationOptions*) | Optimize resources in the document according to defined optimization strategy. |
| [PageNodesToBalancedTree](./pagenodestobalancedtree/)(*byte*) | Organizes page tree nodes in a document into a balanced tree. |
| [ProcessParagraphs](./processparagraphs/) | Process paragraphs for generator. |
| [RemoveMetadata](./removemetadata/) | Removes metadata from the document. |
| [RemovePdfUaCompliance](./removepdfuacompliance/) | Remove pdfUa compliance from the document. |
| [RemovePdfaCompliance](./removepdfacompliance/) | Remove pdfa compliance from the document. |
| [Repair](./repair/)(*RepairOptions*) |  |
| [Save](./save/) | Save document incrementally (i.e. using incremental update technique). |
| [Save](./save/)(*Stream*) | Stores document into stream. |
| [Save](./save/)(*string*) | Saves document into the specified file. |
| [Save](./save/)(*SaveOptions*) | Saves the document with save options. |
| [Save](./save/)(*string, SaveFormat*) | Saves the document with a new name along with a file format. |
| [Save](./save/)(*Stream, SaveFormat*) | Saves the document with a new name along with a file format. |
| [Save](./save/)(*string, SaveOptions*) | Saves the document with a new name setting its save options. |
| [Save](./save/)(*Stream, SaveOptions*) | Saves the document to a stream with a save options. |
| [SaveAsync](./saveasync/)(*CancellationToken*) | Save document incrementally (i.e. using incremental update technique). |
| [SaveAsync](./saveasync/)(*Stream, CancellationToken*) | Stores document into stream. |
| [SaveAsync](./saveasync/)(*string, CancellationToken*) | Saves document into the specified file. |
| [SaveAsync](./saveasync/)(*SaveOptions, CancellationToken*) | Saves the document with save options. |
| [SaveAsync](./saveasync/)(*string, SaveFormat, CancellationToken*) | Saves the document with a new name along with a file format. |
| [SaveAsync](./saveasync/)(*Stream, SaveFormat, CancellationToken*) | Saves the document with a new name along with a file format. |
| [SaveAsync](./saveasync/)(*string, SaveOptions, CancellationToken*) | Saves the document with a new name setting its save options. |
| [SaveAsync](./saveasync/)(*Stream, SaveOptions, CancellationToken*) | Saves the document to a stream with a save options. |
| [SaveXml](./savexml/)(*string*) | Save document to XML. |
| [SendTo](./sendto/)(*DocumentDevice, Stream*) | Sends the whole document to the document device for processing. |
| [SendTo](./sendto/)(*DocumentDevice, string*) | Sends the whole document to the document device for processing. |
| [SendTo](./sendto/)(*DocumentDevice, int, int, Stream*) | Sends the certain pages of the document to the document device for processing. |
| [SendTo](./sendto/)(*DocumentDevice, int, int, string*) | Sends the whole document to the document device for processing. |
| [SetDefaultFileSizeLimitToMemoryLoading](./setdefaultfilesizelimittomemoryloading/) | Sets the file size limit for loading an entire file into memory to default value equals 210 Mb. |
| [SetTitle](./settitle/)(*string*) | Set Title for Pdf Document. |
| [SetXmpMetadata](./setxmpmetadata/)(*Stream*) | Set XMP metadata of document. |
| [Validate](./validate/)(*PdfFormatConversionOptions*) | Validate document into the specified file. |
| [Validate](./validate/)(*string, PdfFormat*) | Validate document into the specified file. |
| [Validate](./validate/)(*Stream, PdfFormat*) | Validate document into the specified file. |

## Fields

| Name | Description |
| --- | --- |
| const [DefaultNodesNumInSubtrees](./defaultnodesnuminsubtrees/) |  |

## Events

| Name | Description |
| --- | --- |
| event [FontSubstitution](./fontsubstitution/) | Occurs when font replaces another font in document. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

