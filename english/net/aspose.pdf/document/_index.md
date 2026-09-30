---
title: "Document Class"
linktitle: "Document"
articleTitle: "Document"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Document class. Class representing PDF document."
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
| [Document](./document/#constructor)() | Initializes empty document. |
| [Document](./document/#constructor_1)(PdfVersion) | Initializes empty document by version. |
| [Document](./document/#constructor_2)(Stream) | Initialize new Document instance from the *input* stream. |
| [Document](./document/#constructor_3)(string) | Just init Document using *filename*. The same as [`Document`](../../aspose.pdf/document/). |
| [Document](./document/#constructor_4)(Stream, bool) | Initialize new Document instance from the *input* stream. |
| [Document](./document/#constructor_5)(Stream, CertificateEncryptionOptions) | Initialize new Document instance from the *input* stream. |
| [Document](./document/#constructor_6)(Stream, LoadOptions) | Opens an existing document from a stream providing necessary converting to get pdf document. |
| [Document](./document/#constructor_7)(Stream, string) | Initialize new Document instance from the *input* stream. |
| [Document](./document/#constructor_8)(string, bool) | Just init Document using *filename*. The same as [`Document`](../../aspose.pdf/document/). |
| [Document](./document/#constructor_9)(string, CertificateEncryptionOptions) | Initializes new instance of the [`Document`](../../aspose.pdf/document/) class for working with encrypted document. |
| [Document](./document/#constructor_10)(string, LoadOptions) | Opens an existing document from a file providing necessary converting options to get pdf document. |
| [Document](./document/#constructor_11)(string, string) | Initializes new instance of the [`Document`](../../aspose.pdf/document/) class for working with encrypted document. |
| [Document](./document/#constructor_12)(Stream, CertificateEncryptionOptions, bool) | Initialize new Document instance from the *input* stream. |
| [Document](./document/#constructor_13)(Stream, string, bool) | Initialize new Document instance from the *input* stream. |
| [Document](./document/#constructor_14)(Stream, string, ICustomSecurityHandler) | Initialize new Document instance from the *input* stream. |
| [Document](./document/#constructor_15)(string, CertificateEncryptionOptions, bool) | Initializes new instance of the [`Document`](../../aspose.pdf/document/) class for working with encrypted document. |
| [Document](./document/#constructor_16)(string, string, bool) | Initializes new instance of the [`Document`](../../aspose.pdf/document/) class for working with encrypted document. |
| [Document](./document/#constructor_17)(string, string, ICustomSecurityHandler) | Initializes new instance of the [`Document`](../../aspose.pdf/document/) class for working with encrypted document. |
| [Document](./document/#constructor_18)(Stream, string, bool, ICustomSecurityHandler) | Initialize new Document instance from the *input* stream. |
| [Document](./document/#constructor_19)(string, string, bool, ICustomSecurityHandler) | Initializes new instance of the [`Document`](../../aspose.pdf/document/) class for working with encrypted document. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](./actions/) { get; } | Gets document actions. This property is instance of DocumentActions class which allows to get/set BeforClosing, BeforSaving, etc. actions. |
| [AllowReusePageContent](./allowreusepagecontent/) { get; set; } | Allows to merge page contents to optimize docuement size. If used then differnet but duplicated pages may reference to the same content object. Please note that this mode may cause side effects like changing page content when other page is changed. |
| [Background](./background/) { get; set; } | Gets or sets the background color of the document. |
| [CenterWindow](./centerwindow/) { get; set; } | Gets or sets flag specifying whether position of the document's window will be centerd on the screen. |
| [Collection](./collection/) { get; set; } | Gets collection of document. |
| [CryptoAlgorithm](./cryptoalgorithm/) { get; } | Gets security settings if document is encrypted. If document is not encrypted then corresponding exception will be raised in .net 1.1 or CryptoAlgorithm will be null for other .net versions. |
| [CustomSecurityHandler](./customsecurityhandler/) { get; } | Gets a custom security handler. |
| [Destinations](./destinations/) { get; } | Gets the collection of destinations. Obsolete. Please use NamedDestinations. |
| [Direction](./direction/) { get; set; } | Gets or sets reading order of text: L2R (left to right) or R2L (right to left). |
| [DisableFontLicenseVerifications](./disablefontlicenseverifications/) { get; set; } | Many operations with font can't be executed if these operations are prohibited by license of this font. For example some font can't be embedded into PDF document if license rules disable embedding for this font. This flag is used to disable any license restrictions for all fonts in current PDF document. Be careful when using this flag. When it is set it means that person who sets this flag, takes all responsibility of possible license/law violations on himself. So He takes it on it's own risk. It's strongly recommended to use this flag only when you are fully confident that you are not breaking the copyright law. By default false. |
| [DisplayDocTitle](./displaydoctitle/) { get; set; } | Gets or sets flag specifying whether document's window title bar should display document title. |
| [Duplex](./duplex/) { get; set; } | Gets or sets print duplex mode handling option to use when printing the file from the print dialog. |
| [EmbedStandardFonts](./embedstandardfonts/) { get; set; } | Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. All PDF fonts can be embedded into document simply via setting of flag IsEmbedded into true, but PDF standard Type1 fonts is an exception from this rule. Standard Type1 font embedding requires much time, so to embed these fonts it's necessary not only set flag IsEmbedded into true for specified font but also set an additiona flag on document's level - EmbedStandardFonts = true; This property can be set only one time for all fonts. By default false. |
| [EmbeddedFiles](./embeddedfiles/) { get; } | Gets collection of files embedded to document. |
| [EnableNotificationLogging](./enablenotificationlogging/) { get; set; } | Gets or sets a value indicating whether to enable the logging of notifications. |
| [EnableObjectUnload](./enableobjectunload/) { get; set; } | Get or sets flag which enables document partially be unloaded from memory. This allow to decrease memory usage but may have negative effect on perfomance. |
| [EnableSignatureSanitization](./enablesignaturesanitization/) { get; set; } | Gets or sets flag to manage signature fields sanitization. Enabled by default. |
| [FileName](./filename/) { get; } | Name of the PDF file that caused this document |
| static [FileSizeLimitToMemoryLoading](./filesizelimittomemoryloading/) { get; set; } | Get and set the file size limit for loading an entire file into memory. The value is set in megabytes. The default value is 210 Mb. |
| [FitWindow](./fitwindow/) { get; set; } | Gets or sets flag specifying whether document window must be resized to fit the first displayed page. |
| [FontUtilities](./fontutilities/) { get; } | IDocumentFontUtilities instance |
| [Form](./form/) { get; } | Gets Acro Form of the document. |
| [HandleSignatureChange](./handlesignaturechange/) { get; set; } | Throw Exception if the document will save with changes and have signature |
| [HideMenubar](./hidemenubar/) { get; set; } | Gets or sets flag specifying whether menu bar should be hidden when document is active. |
| [HideToolBar](./hidetoolbar/) { get; set; } | Gets or sets flag specifying whether toolbar should be hidden when document is active. |
| [HideWindowUI](./hidewindowui/) { get; set; } | Gets or sets flag specifying whether user interface elements should be hidden when document is active. |
| [Id](./id/) { get; } | Gets the ID. |
| [IgnoreCorruptedObjects](./ignorecorruptedobjects/) { get; set; } | Gets or sets flag of ignoring errors in source files. When pages from source document copied into destination document, copying process is stopped with exception if some objects in source files are corrupted when this flag is false. example: dest.Pages.Add(src.Pages); If this flag is set to true then corrupted objects will be replaced with empty values. By default: true. |
| [Info](./info/) { get; } | Gets document info. |
| [IsEncrypted](./isencrypted/) { get; } | Gets encrypted status of the document. True if document is encrypted. |
| static [IsLicensed](./islicensed/) { get; } | Gets licensed state of the system. Returns true is system works in licensed mode and false otherwise. |
| [IsLinearized](./islinearized/) { get; set; } | Gets or sets a value indicating whether document is linearized. |
| [IsPdfUaCompliant](./ispdfuacompliant/) { get; } | Gets the is document pdfua compliant. |
| [IsPdfaCompliant](./ispdfacompliant/) { get; } | Gets the is document pdfa compliant. |
| [IsXrefGapsAllowed](./isxrefgapsallowed/) { get; set; } | Gets or sets the is document pdfa compliant. |
| [JavaScript](./javascript/) { get; } | Collection of JavaScript of document level. |
| [LogicalStructure](./logicalstructure/) { get; } | Gets logical structure of the document. |
| [Metadata](./metadata/) { get; } | Document metadata. (A PDF document may include general information, such as the document's title, author, and creation and modification dates. Such global information about the document (as opposed to its content or structure) is called metadata and is intended to assist in cataloguing and searching for documents in external databases.) |
| [NamedDestinations](./nameddestinations/) { get; } | Collection of Named Destination in the document. |
| [NonFullScreenPageMode](./nonfullscreenpagemode/) { get; set; } | Gets or sets page mode, specifying how to display the document on exiting full-screen mode. |
| [OpenAction](./openaction/) { get; set; } | Gets or sets action performed at document opening. |
| [OptimizeSize](./optimizesize/) { get; set; } | Gets or sets optimization flag. When pages are added to document, equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false. |
| [Outlines](./outlines/) { get; } | Gets document outlines. |
| [OutputIntents](./outputintents/) { get; } | Gets the collection of Output intents in the document. |
| [PageInfo](./pageinfo/) { get; set; } | Gets or sets the page info.(for generator only, not filled in when reading document) |
| [PageLabels](./pagelabels/) { get; } | Gets page labels in the document. |
| [PageLayout](./pagelayout/) { get; set; } | Gets or sets page layout which shall be used when the document is opened. |
| [PageMode](./pagemode/) { get; set; } | Gets or sets page mode, specifying how document should be displayed when opened. |
| [Pages](./pages/) { get; } | Gets or sets collection of document pages. Note that pages are numbered from 1 in collection. |
| [PdfFormat](./pdfformat/) { get; } | Gets PDF format |
| [Permissions](./permissions/) { get; } | Gets permissions of the document. |
| [PickTrayByPdfSize](./picktraybypdfsize/) { get; set; } | Gets or sets a flag specifying whether the PDF page size shall be used to select the input paper tray. |
| [PrintScaling](./printscaling/) { get; set; } | Gets or sets the page scaling option that shall be selected when a print dialog is displayed for this document. |
| [TaggedContent](./taggedcontent/) { get; } | Gets access to TaggedPdf content. |
| [Version](./version/) { get; } | Gets a version of Pdf from Pdf file header. |

## Methods

| Name | Description |
| --- | --- |
| [BindXml](./bindxml/)(Stream) | Bind xml to document |
| [BindXml](./bindxml/)(string) | Bind xml to document |
| [BindXml](./bindxml/)(Stream, Stream) | Bind xml/xsl to document |
| [BindXml](./bindxml/)(string, string) | Bind xml/xsl to document |
| [BindXml](./bindxml/)(Stream, Stream, XmlReaderSettings) | Bind xml/xsl to document |
| [ChangePasswords](./changepasswords/)(string, string, string) | Changes document passwords. This action can be done only using owner password. |
| [Check](./check/)(bool) | Validates document. |
| [Convert](./convert/)(PdfFormatConversionOptions) | Convert document using specified conversion options |
| [Convert](./convert/)(CallBackGetHocr, bool) | Recognize images inside the document and add hocr strings over it. |
| [Convert](./convert/)(CallBackGetHocrWithPage, bool) | Recognize images inside the document and add hocr strings over it. |
| [Convert](./convert/)(Stream, PdfFormat, ConvertErrorAction) | Convert document and save errors into the specified stream. |
| [Convert](./convert/)(string, PdfFormat, ConvertErrorAction) | Convert document and save errors into the specified file. |
| [Convert](./convert/)(Fixup, Stream, bool, object[]) | Convert document by applying the Fixup. |
| [Convert](./convert/)(Fixup, string, bool, object[]) | Convert document by applying the Fixup. |
| static [Convert](./convert/)(Stream, LoadOptions, Stream, SaveOptions) | Converts stream in source format into stream in destination format. |
| static [Convert](./convert/)(Stream, LoadOptions, string, SaveOptions) | Converts stream in source format into destination file in destination format. |
| [Convert](./convert/)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Convert document and save errors into the specified file. |
| static [Convert](./convert/)(string, LoadOptions, Stream, SaveOptions) | Converts source file in source format into stream in destination format. |
| static [Convert](./convert/)(string, LoadOptions, string, SaveOptions) | Converts source file in source format into destination file in destination format. |
| [Convert](./convert/)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Convert document and save errors into the specified file. |
| [ConvertPageToPNGMemoryStream](./convertpagetopngmemorystream/)(Page) | Convert page to PNG for DSR, OMR, OCR image stream. |
| [Decrypt](./decrypt/)() | Decrypts the document. Call then Save to obtain decrypted version of the document. |
| [Dispose](./dispose/)() | Closes all resources used by this document. |
| [Encrypt](./encrypt/)(Permissions, CryptoAlgorithm, IList<X509Certificate2>) | Encrypts the document. |
| [Encrypt](./encrypt/)(string, string, DocumentPrivilege, ICustomSecurityHandler) | Encrypts the document. |
| [Encrypt](./encrypt/)(string, string, Permissions, CryptoAlgorithm) | Encrypts the document. |
| [Encrypt](./encrypt/)(string, string, Permissions, ICustomSecurityHandler) | Encrypts the document. |
| [Encrypt](./encrypt/)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Encrypts the document. |
| [Encrypt](./encrypt/)(string, string, Permissions, CryptoAlgorithm, bool) | Encrypts the document. |
| [ExportAnnotationsToXfdf](./exportannotationstoxfdf/)(Stream) | Export all document annotations into stream. |
| [ExportAnnotationsToXfdf](./exportannotationstoxfdf/)(string) | Exports all document annotations to XFDF file |
| [Flatten](./flatten/)() | Removes all fields from the document and place their values instead. |
| [Flatten](./flatten/)(FlattenSettings) | Removes all fields (and annotations) from the document and place their values instead. |
| [FlattenTransparency](./flattentransparency/)() | Replaces transparent content with non-transparent raster and vector graphics. |
| [FreeMemory](./freememory/)() | Clears memory |
| [GetCatalogValue](./getcatalogvalue/)(string) | Returns item value from catalog dictionary. |
| [GetObjectById](./getobjectbyid/)(string) | Gets a object with specified ID in the document. |
| [GetXmpMetadata](./getxmpmetadata/)(Stream) | Get XMP metadata from document. |
| [HasIncrementalUpdate](./hasincrementalupdate/)() | Checks if the current PDF document has been saved with incremental updates. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(Stream) | Imports annotations from stream to document. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(string) | Imports annotations from XFDF file to document. |
| [IsRepairNeeded](./isrepairneeded/)(out RepairOptions) | Checks if document requires Repair method call. |
| [LoadFrom](./loadfrom/)(string, LoadOptions) | Loads a file, converting it to PDF. |
| [Merge](./merge/)(params Document[]) | Merges documents. |
| [Merge](./merge/)(params string[]) | Merges pdf files. |
| [Merge](./merge/)(MergeOptions, params Document[]) | Merges documents. |
| [Merge](./merge/)(MergeOptions, params string[]) | Merges documents. |
| static [MergeDocuments](./mergedocuments/)(params Document[]) | Merges documents. |
| static [MergeDocuments](./mergedocuments/)(params string[]) | Merges pdf files. |
| static [MergeDocuments](./mergedocuments/)(MergeOptions, params Document[]) | Merges documents. |
| static [MergeDocuments](./mergedocuments/)(MergeOptions, params string[]) | Merges documents. |
| [Optimize](./optimize/)() | Linearize the document in order to - open the first page as quickly as possible; - display next page or follow by link to the next page as quickly as possible; - display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first); - permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed. Invoking this method doesn't actually saves the document. On the contrary the document only is prepared to have optimized structure, call then Save to get optimized document. |
| [OptimizeResources](./optimizeresources/)() | Optimize resources in the document: 1. Resources which are not used on the document pages are removed; 2. Equal resources are joined into one object; 3. Unused objects are deleted. |
| [OptimizeResources](./optimizeresources/)(OptimizationOptions) | Optimize resources in the document according to defined optimization strategy. |
| [PageNodesToBalancedTree](./pagenodestobalancedtree/)(byte) | Organizes page tree nodes in a document into a balanced tree. Only if the document has more than nodesNumInSubtrees page objects, otherwise it does nothing. Do not call this method while iterating over Pages elements, it may give unpredictable results |
| [ProcessParagraphs](./processparagraphs/)() | Process paragraphs for generator. |
| [RemoveMetadata](./removemetadata/)() | Removes metadata from the document. |
| [RemovePdfUaCompliance](./removepdfuacompliance/)() | Remove pdfUa compliance from the document |
| [RemovePdfaCompliance](./removepdfacompliance/)() | Remove pdfa compliance from the document |
| [Repair](./repair/)(RepairOptions) | Repairs broken document. |
| [Save](./save/)() | Save document incrementally (i.e. using incremental update technique). |
| [Save](./save/)(SaveOptions) | Saves the document with save options. |
| [Save](./save/)(Stream) | Stores document into stream. |
| [Save](./save/)(string) | Saves document into the specified file. |
| [Save](./save/)(Stream, SaveFormat) | Saves the document with a new name along with a file format. |
| [Save](./save/)(Stream, SaveOptions) | Saves the document to a stream with a save options. |
| [Save](./save/)(string, SaveFormat) | Saves the document with a new name along with a file format. |
| [Save](./save/)(string, SaveOptions) | Saves the document with a new name setting its save options. |
| [SaveAsync](./saveasync/)(CancellationToken) | Save document incrementally (i.e. using incremental update technique). |
| [SaveAsync](./saveasync/)(SaveOptions, CancellationToken) | Saves the document with save options. |
| [SaveAsync](./saveasync/)(Stream, CancellationToken) | Stores document into stream. |
| [SaveAsync](./saveasync/)(string, CancellationToken) | Saves document into the specified file. |
| [SaveAsync](./saveasync/)(Stream, SaveFormat, CancellationToken) | Saves the document with a new name along with a file format. |
| [SaveAsync](./saveasync/)(Stream, SaveOptions, CancellationToken) | Saves the document to a stream with a save options. |
| [SaveAsync](./saveasync/)(string, SaveFormat, CancellationToken) | Saves the document with a new name along with a file format. |
| [SaveAsync](./saveasync/)(string, SaveOptions, CancellationToken) | Saves the document with a new name setting its save options. |
| [SaveXml](./savexml/)(string) | Save document to XML. |
| [SendTo](./sendto/)(DocumentDevice, Stream) | Sends the whole document to the document device for processing. |
| [SendTo](./sendto/)(DocumentDevice, string) | Sends the whole document to the document device for processing. |
| [SendTo](./sendto/)(DocumentDevice, int, int, Stream) | Sends the certain pages of the document to the document device for processing. |
| [SendTo](./sendto/)(DocumentDevice, int, int, string) | Sends the whole document to the document device for processing. |
| static [SetDefaultFileSizeLimitToMemoryLoading](./setdefaultfilesizelimittomemoryloading/)() | Sets the file size limit for loading an entire file into memory to default value equals 210 Mb. |
| [SetTitle](./settitle/)(string) | Set Title for Pdf Document |
| [SetXmpMetadata](./setxmpmetadata/)(Stream) | Set XMP metadata of document. |
| [Validate](./validate/)(PdfFormatConversionOptions) | Validate document into the specified file. |
| [Validate](./validate/)(Stream, PdfFormat) | Validate document into the specified file. |
| [Validate](./validate/)(string, PdfFormat) | Validate document into the specified file. |

## Fields

| Name | Description |
| --- | --- |
| const [DefaultNodesNumInSubtrees](./defaultnodesnuminsubtrees/) |  |

## Events

| Name | Description |
| --- | --- |
| event [FontSubstitution](./fontsubstitution/) | Occurs when font replaces another font in document. |

## Other Members

| Name | Description |
| --- | --- |
| delegate [CallBackGetHocr](../../aspose.pdf/document.callbackgethocr) |  |
| delegate [CallBackGetHocrWithPage](../../aspose.pdf/document.callbackgethocrwithpage) |  |
| delegate [FontSubstitutionHandler](../../aspose.pdf/document.fontsubstitutionhandler) | Represents the method that will handle FontSubstitution event. |
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | Holds functionality to tune fonts |
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | Represents the options to Merge methods. |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | Represents options for repairing a PDF document. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

