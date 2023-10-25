---
title: Class Document
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Document class. Class representing PDF document
type: docs
weight: 1910
url: /net/aspose.pdf/document/
---
## Document class

Class representing PDF document

```csharp
public sealed class Document : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [Document](document/#constructor)() | Initializes empty document. |
| [Document](document/#constructor_1)(Stream) | Initialize new Document instance from the *input* stream. |
| [Document](document/#constructor_6)(string) | Just init Document using *filename*. The same as [`Document`](./document/). |
| [Document](document/#constructor_3)(Stream, bool) | Initialize new Document instance from the *input* stream. |
| [Document](document/#constructor_2)(Stream, LoadOptions) | Opens an existing document from a stream providing necessary converting to get pdf document. |
| [Document](document/#constructor_4)(Stream, string) | Initialize new Document instance from the *input* stream. |
| [Document](document/#constructor_7)(string, LoadOptions) | Opens an existing document from a file providing necessary converting options to get pdf document. |
| [Document](document/#constructor_8)(string, string) | Initializes new instance of the `Document` class for working with encrypted document. |
| [Document](document/#constructor_5)(Stream, string, bool) | Initialize new Document instance from the *input* stream. |
| [Document](document/#constructor_9)(string, string, bool) | Initializes new instance of the `Document` class for working with encrypted document. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | Gets document actions. This property is instance of DocumentActions class which allows to get/set BeforClosing, BeforSaving, etc. actions. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | Allows to merge page contents to optimize docuement size. If used then differnet but duplicated pages may reference to the same content object. Please note that this mode may cause side effects like changing page content when other page is changed. |
| [Background](../../aspose.pdf/document/background/) { get; set; } | Gets or sets the background color of the document. |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | Gets or sets flag specifying whether position of the document's window will be centerd on the screen. |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | Gets collection of document. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | Gets security settings if document is encrypted. If document is not encrypted then corresponding exception will be raised in .net 1.1 or CryptoAlgorithm will be null for other .net versions. |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | Gets the collection of destinations. Obsolete. Please use NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | Gets or sets reading order of text: L2R (left to right) or R2L (right to left). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | Many operations with font can't be executed if these operations are prohibited by license of this font. For example some font can't be embedded into PDF document if license rules disable embedding for this font. This flag is used to disable any license restrictions for all fonts in current PDF document. Be careful when using this flag. When it is set it means that person who sets this flag, takes all responsibility of possible license/law violations on himself. So He takes it on it's own risk. It's strongly recommended to use this flag only when you are fully confident that you are not breaking the copyright law. By default false. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | Gets or sets flag specifying whether document's window title bar should display document title. |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | Gets or sets print duplex mode handling option to use when printing the file from the print dialog. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | Gets collection of files embedded to document. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. All PDF fonts can be embedded into document simply via setting of flag IsEmbedded into true, but PDF standard Type1 fonts is an exception from this rule. Standard Type1 font embedding requires much time, so to embed these fonts it's necessary not only set flag IsEmbedded into true for specified font but also set an additiona flag on document's level - EmbedStandardFonts = true; This property can be set only one time for all fonts. By default false. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | Get or sets flag which enables document partially be unloaded from memory. This allow to decrease memory usage but may have negative effect on perfomance. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | Gets or sets flag to manage signature fields sanitization. Enabled by default. |
| [FileName](../../aspose.pdf/document/filename/) { get; } | Name of the PDF file that caused this document |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | Gets or sets flag specifying whether document window must be resized to fit the first displayed page. |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | IDocumentFontUtilities instance |
| [Form](../../aspose.pdf/document/form/) { get; } | Gets Acro Form of the document. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | Throw Exception if the document will save with changes and have signature |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | Gets or sets flag specifying whether menu bar should be hidden when document is active. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | Gets or sets flag specifying whether toolbar should be hidden when document is active. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | Gets or sets flag specifying whether user interface elements should be hidden when document is active. |
| [Id](../../aspose.pdf/document/id/) { get; } | Gets the ID. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | Gets or sets flag of ignoring errors in source files. When pages from source document copied into destination document, copying process is stopped with exception if some objects in source files are corrupted when this flag is false. example: dest.Pages.Add(src.Pages); If this flag is set to true then corrupted objects will be replaced with empty values. By default: true. |
| [Info](../../aspose.pdf/document/info/) { get; } | Gets document info. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | Gets encrypted status of the document. True if document is encrypted. |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | Gets or sets a value indicating whether document is linearized. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | Gets the is document pdfa compliant. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | Gets the is document pdfua compliant. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | Gets or sets the is document pdfa compliant. |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | Collection of JavaScript of document level. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | Gets logical structure of the document. |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | Document metadata. (A PDF document may include general information, such as the document's title, author, and creation and modification dates. Such global information about the document (as opposed to its content or structure) is called metadata and is intended to assist in cataloguing and searching for documents in external databases.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | Collection of Named Destination in the document. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | Gets or sets page mode, specifying how to display the document on exiting full-screen mode. |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | Gets or sets action performed at document opening. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | Gets or sets optimization flag. When pages are added to document, equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false. |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | Gets document outlines. |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | Gets the collection of Output intents in the document. |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | Gets or sets the page info.(for generator only, not filled in when reading document) |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | Gets page labels in the document. |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | Gets or sets page layout which shall be used when the document is opened. |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | Gets or sets page mode, specifying how document should be displayed when opened. |
| [Pages](../../aspose.pdf/document/pages/) { get; } | Gets or sets collection of document pages. Note that pages are numbered from 1 in collection. |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | Gets PDF format |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | Gets permissions of the document. |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | Gets or sets the page scaling option that shall be selected when a print dialog is displayed for this document. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | Gets access to TaggedPdf content. |
| [Version](../../aspose.pdf/document/version/) { get; } | Gets a version of Pdf from Pdf file header. |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | Gets licensed state of the system. Returns true is system works in licensed mode and false otherwise. |

## Methods

| Name | Description |
| --- | --- |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml)(Stream) | Bind xml to document |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_3)(string) | Bind xml to document |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_1)(Stream, Stream) | Bind xml/xsl to document |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_4)(string, string) | Bind xml/xsl to document |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_2)(Stream, Stream, XmlReaderSettings) | Bind xml/xsl to document |
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | Changes document passwords. This action can be done only using owner password. |
| [Check](../../aspose.pdf/document/check/)(bool) | Validates document. |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr) | Recognize images inside the document and add hocr strings over it. |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | Convert document using specified conversion options |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(Stream, PdfFormat, ConvertErrorAction) | Convert document and save errors into the specified stream. |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(string, PdfFormat, ConvertErrorAction) | Convert document and save errors into the specified file. |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | Convert document by applying the Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | Convert document by applying the Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Convert document and save errors into the specified file. |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Convert document and save errors into the specified file. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | Convert page to PNG for DSR, OMR, OCR image stream. |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | Decrypts the document. Call then Save to obtain decrypted version of the document. |
| [Dispose](../../aspose.pdf/document/dispose/)() | Closes all resources used by this document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | Encrypts the document. Call then Save to get encrypted version of the document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Encrypts the document. Call then Save to get encrypted version of the document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | Encrypts the document. Call then Save to get encrypted version of the document. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | Export all document annotations into stream. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | Exports all document annotations to XFDF file |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | Removes all fields from the document and place their values instead. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | Removes all fields (and annotations) from the document and place their values instead. |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | Replaces transparent content with non-transparent raster and vector graphics. |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | Clears memory |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | Returns item value from catalog dictionary. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | Gets a object with specified ID in the document. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | Get XMP metadata from document. |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | Checks if the current PDF document has been saved with incremental updates. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Imports annotations from stream to document. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Imports annotations from XFDF file to document. |
| [Optimize](../../aspose.pdf/document/optimize/)() | Linearize the document in order to - open the first page as quickly as possible; - display next page or follow by link to the next page as quickly as possible; - display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first); - permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed. Invoking this method doesn't actually saves the document. On the contrary the document only is prepared to have optimized structure, call then Save to get optimized document. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | Optimize resources in the document: 1. Resources which are not used on the document pages are removed; 2. Equal resources are joined into one object; 3. Unused objects are deleted. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | Optimize resources in the document according to defined optimization strategy. |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | Organizes page tree nodes in a document into a balanced tree. Only if the document has more than nodesNumInSubtrees page objects, otherwise it does nothing. |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | Process paragraphs for generator. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | Removes metadata from the document. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | Remove pdfa compliance from the document |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/)() | Remove pdfUa compliance from the document |
| [Repair](../../aspose.pdf/document/repair/)() | Repairs broken document. |
| [Save](../../aspose.pdf/document/save/#save)() | Save document incrementally (i.e. using incremental update technique). |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | Saves the document with save options. |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | Stores document into stream. |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | Saves document into the specified file. |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | Saves the document with a new name along with a file format. |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | Saves the document to a stream with a save options. |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | Saves the document with a new name along with a file format. |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | Saves the document with a new name setting its save options. |
| [Save](../../aspose.pdf/document/save/#save_8)(HttpResponse, string, ContentDisposition, SaveOptions) | Saves the document to a response stream with a save options. |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | Save document to XML. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | Sends the whole document to the document device for processing. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | Sends the whole document to the document device for processing. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | Sends the certain pages of the document to the document device for processing. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | Sends the whole document to the document device for processing. |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | Set Title for Pdf Document |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | Set XMP metadata of document. |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | Validate document into the specified file. |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | Validate document into the specified file. |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | Validate document into the specified file. |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | Converts stream in source format into stream in destination format. |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | Converts stream in source format into destination file in destination format. |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | Converts source file in source format into stream in destination format. |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | Converts source file in source format into destination file in destination format. |

## Fields

| Name | Description |
| --- | --- |
| const [DefaultNodesNumInSubtrees](../../aspose.pdf/document/defaultnodesnuminsubtrees/) |  |

## Events

| Name | Description |
| --- | --- |
| event [FontSubstitution](../../aspose.pdf/document/fontsubstitution/) | Occurs when font replaces another font in document. |

## Other Members

| Name | Description |
| --- | --- |
| delegate [CallBackGetHocr](../../aspose.pdf/document.callbackgethocr) | The call back procedure for hocr recognize. |
| delegate [FontSubstitutionHandler](../../aspose.pdf/document.fontsubstitutionhandler) | Represents the method that will handle FontSubstitution event. |
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | Holds functionality to tune fonts |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


