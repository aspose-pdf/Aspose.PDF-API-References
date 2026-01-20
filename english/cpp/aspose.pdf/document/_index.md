---
title: Aspose::Pdf::Document class
linktitle: Document
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Document class. Class representing PDF document in C++.'
type: docs
weight: 3900
url: /cpp/aspose.pdf/document/
---
## Document class


Class representing PDF document.

```cpp
class Document : public System::IDisposable,
                 public Aspose::Pdf::ISupportsMemoryCleanup,
                 public Aspose::Pdf::LicenseManagement::IVentureLicenseTarget
```

## Nested classes

* Class [IDocumentFontUtilities](./idocumentfontutilities/)
* Class [MergeOptions](./mergeoptions/)
* Class [OptimizationOptions](./optimizationoptions/)
* Class [RepairOptions](./repairoptions/)
## Methods

| Method | Description |
| --- | --- |
| [BindXml](./bindxml/)(System::String) | Bind xml to document. |
| [BindXml](./bindxml/)(System::String, System::String) | Bind xml/xsl to document. |
| [BindXml](./bindxml/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) | Bind xml/xsl to document. |
| [BindXml](./bindxml/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::Xml::XmlReaderSettings\>) | Bind xml/xsl to document. |
| [BindXml](./bindxml/)(System::SharedPtr\<System::IO::Stream\>) | Bind xml to document. |
| [ChangePasswords](./changepasswords/)(System::String, System::String, System::String) | Changes document passwords. This action can be done only using owner password. |
| [Check](./check/)(bool) | Validates document. |
| [Convert](./convert/)(System::String, Aspose::Pdf::PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Convert document and save errors into the specified file. |
| [Convert](./convert/)(System::SharedPtr\<System::IO::Stream\>, Aspose::Pdf::PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Convert document and save errors into the specified file. |
| [Convert](./convert/)(System::String, Aspose::Pdf::PdfFormat, ConvertErrorAction) | Convert document and save errors into the specified file. |
| [Convert](./convert/)(System::SharedPtr\<PdfFormatConversionOptions\>) | Convert document using specified conversion options. |
| [Convert](./convert/)(Document::CallBackGetHocrWithPage, bool) | Recognize images inside the document and add hocr strings over it. |
| [Convert](./convert/)(Document::CallBackGetHocr, bool) | Recognize images inside the document and add hocr strings over it. |
| [Convert](./convert/)(System::SharedPtr\<System::IO::Stream\>, Aspose::Pdf::PdfFormat, ConvertErrorAction) | Convert document and save errors into the specified stream. |
| [Convert](./convert/)(Fixup, System::SharedPtr\<System::IO::Stream\>, bool, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) | Convert document by applying the [Fixup](../fixup/). |
| [Convert](./convert/)(Fixup, System::String, bool, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) | Convert document by applying the [Fixup](../fixup/). |
| static [Convert](./convert/)(System::String, System::SharedPtr\<LoadOptions\>, System::String, System::SharedPtr\<SaveOptions\>) | Converts source file in source format into destination file in destination format. |
| static [Convert](./convert/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<LoadOptions\>, System::String, System::SharedPtr\<SaveOptions\>) | Converts stream in source format into destination file in destination format. |
| static [Convert](./convert/)(System::String, System::SharedPtr\<LoadOptions\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<SaveOptions\>) | Converts source file in source format into stream in destination format. |
| static [Convert](./convert/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<LoadOptions\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<SaveOptions\>) | Converts stream in source format into stream in destination format. |
| [ConvertPageToPNGMemoryStream](./convertpagetopngmemorystream/)(System::SharedPtr\<Page\>) | Convert page to PNG for DSR, OMR, OCR image stream. |
| [Decrypt](./decrypt/)() | Decrypts the document. Call then Save to obtain decrypted version of the document. |
| [Dispose](./dispose/)() override | Closes all resources used by this document. |
| [Document](./document/)(System::SharedPtr\<System::IO::Stream\>) | Initialize new [Document](./) instance from the *input*  stream. |
| [Document](./document/)(System::SharedPtr\<System::IO::Stream\>, bool) | Initialize new [Document](./) instance from the *input*  stream. |
| [Document](./document/)(System::SharedPtr\<System::IO::Stream\>, System::String) | Initialize new [Document](./) instance from the *input*  stream. |
| [Document](./document/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Security::CertificateEncryptionOptions\>) | Initialize new [Document](./) instance from the *input*  stream. |
| [Document](./document/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Security::CertificateEncryptionOptions\>, bool) | Initialize new [Document](./) instance from the *input*  stream. |
| [Document](./document/)(System::String, System::SharedPtr\<Security::CertificateEncryptionOptions\>) | Initializes new instance of the [Document](./) class for working with encrypted document. |
| [Document](./document/)(System::String, System::SharedPtr\<Security::CertificateEncryptionOptions\>, bool) | Initializes new instance of the [Document](./) class for working with encrypted document. |
| [Document](./document/)(System::SharedPtr\<System::IO::Stream\>, System::String, System::SharedPtr\<Security::ICustomSecurityHandler\>) | Initialize new [Document](./) instance from the *input*  stream. |
| [Document](./document/)(System::SharedPtr\<System::IO::Stream\>, System::String, bool) | Initialize new [Document](./) instance from the *input*  stream. |
| [Document](./document/)(System::SharedPtr\<System::IO::Stream\>, System::String, bool, System::SharedPtr\<Security::ICustomSecurityHandler\>) | Initialize new [Document](./) instance from the *input*  stream. |
| [Document](./document/)(System::String) | Just init [Document](./) using *filename* . The same as [Document(Stream)](../). |
| [Document](./document/)(System::String, bool) | Just init [Document](./) using *filename* . The same as [Document(Stream)](../). |
| [Document](./document/)(System::String, System::String, System::SharedPtr\<Security::ICustomSecurityHandler\>) | Initializes new instance of the [Document](./) class for working with encrypted document. |
| [Document](./document/)(System::String, System::String) | Initializes new instance of the [Document](./) class for working with encrypted document. |
| [Document](./document/)(System::String, System::String, bool) | Initializes new instance of the [Document](./) class for working with encrypted document. |
| [Document](./document/)(System::String, System::String, bool, System::SharedPtr\<Security::ICustomSecurityHandler\>) | Initializes new instance of the [Document](./) class for working with encrypted document. |
| [Document](./document/)() | Initializes empty document. |
| [Document](./document/)(PdfVersion) | Initializes empty document by version. |
| [Document](./document/)(System::String, System::SharedPtr\<LoadOptions\>) | Opens an existing document from a file providing necessary converting options to get pdf document. |
| [Document](./document/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<LoadOptions\>) | Opens an existing document from a stream providing necessary converting to get pdf document. |
| [Encrypt](./encrypt/)(Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm, System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\>\>) | Encrypts the document. |
| [Encrypt](./encrypt/)(System::String, System::String, System::SharedPtr\<Facades::DocumentPrivilege\>, System::SharedPtr\<Security::ICustomSecurityHandler\>) | Encrypts the document. |
| [Encrypt](./encrypt/)(System::String, System::String, Aspose::Pdf::Permissions, System::SharedPtr\<Security::ICustomSecurityHandler\>) | Encrypts the document. |
| [Encrypt](./encrypt/)(System::String, System::String, System::SharedPtr\<Facades::DocumentPrivilege\>, Aspose::Pdf::CryptoAlgorithm, bool) | Encrypts the document. |
| [Encrypt](./encrypt/)(System::String, System::String, Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm) | Encrypts the document. |
| [Encrypt](./encrypt/)(System::String, System::String, Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm, bool) | Encrypts the document. |
| [ExportAnnotationsToXfdf](./exportannotationstoxfdf/)(System::String) | Exports all document annotations to XFDF file. |
| [ExportAnnotationsToXfdf](./exportannotationstoxfdf/)(System::SharedPtr\<System::IO::Stream\>) | Export all document annotations into stream. |
| [Flatten](./flatten/)() | Removes all fields from the document and place their values instead. |
| [Flatten](./flatten/)(System::SharedPtr\<Forms::Form::FlattenSettings\>) | Removes all fields (and annotations) from the document and place their values instead. |
| [FlattenTransparency](./flattentransparency/)() | Replaces transparent content with non-transparent raster and vector graphics. |
| [FreeMemory](./freememory/)() override | Clears memory. |
| [get_Actions](./get_actions/)() | Gets document actions. This property is instance of DocumentActions class which allows to get/set BeforClosing, BeforSaving, etc. actions. |
| [get_AllowReusePageContent](./get_allowreusepagecontent/)() | Allows to merge page contents to optimize docuement size. If used then differnet but duplicated pages may reference to the same content object. Please note that this mode may cause side effects like changing page content when other page is changed. |
| [get_Background](./get_background/)() | Gets the background color of the document. |
| [get_CenterWindow](./get_centerwindow/)() | Gets flag specifying whether position of the document's window will be centerd on the screen. |
| [get_Collection](./get_collection/)() | Gets collection of document. |
| [get_CryptoAlgorithm](./get_cryptoalgorithm/)() | Gets security settings if document is encrypted. If document is not encrypted then corresponding exception will be raised in .net 1.1 or [CryptoAlgorithm](../cryptoalgorithm/) will be null for other .net versions. |
| [get_CustomSecurityHandler](./get_customsecurityhandler/)() const | Gets a custom security handler. |
| [get_Destinations](./get_destinations/)() | Gets the collection of destinations. Obsolete. Please use NamedDestinations. |
| [get_Direction](./get_direction/)() | Gets reading order of text: L2R (left to right) or R2L (right to left). |
| [get_DisableFontLicenseVerifications](./get_disablefontlicenseverifications/)() const | Many operations with font can't be executed if these operations are prohibited by license of this font. For example some font can't be embedded into PDF document if license rules disable embedding for this font. This flag is used to disable any license restrictions for all fonts in current PDF document. Be careful when using this flag. When it is set it means that person who sets this flag, takes all responsibility of possible license/law violations on himself. So He takes it on it's own risk. It's strongly recommended to use this flag only when you are fully confident that you are not breaking the copyright law. By default false. |
| [get_DisplayDocTitle](./get_displaydoctitle/)() | Gets flag specifying whether document's window title bar should display document title. |
| [get_Duplex](./get_duplex/)() | Gets print duplex mode handling option to use when printing the file from the print dialog. |
| [get_EmbeddedFiles](./get_embeddedfiles/)() | Gets collection of files embedded to document. |
| [get_EmbedStandardFonts](./get_embedstandardfonts/)() const | Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. All PDF fonts can be embedded into document simply via setting of flag IsEmbedded into true, but PDF standard Type1 fonts is an exception from this rule. Standard Type1 font embedding requires much time, so to embed these fonts it's necessary not only set flag IsEmbedded into true for specified font but also set an additiona flag on document's level - EmbedStandardFonts = true; This property can be set only one time for all fonts. By default false. |
| [get_EnableNotificationLogging](./get_enablenotificationlogging/)() const | Gets a value indicating whether to enable the logging of notifications. |
| [get_EnableObjectUnload](./get_enableobjectunload/)() | Get or sets flag which enables document partially be unloaded from memory. This allow to decrease memory usage but may have negative effect on perfomance. |
| [get_EnableSignatureSanitization](./get_enablesignaturesanitization/)() const | Gets flag to manage signature fields sanitization. Enabled by default. |
| [get_FileName](./get_filename/)() | Name of the PDF file that caused this document. |
| static [get_FileSizeLimitToMemoryLoading](./get_filesizelimittomemoryloading/)() | Get and set the file size limit for loading an entire file into memory. The value is set in megabytes. The default value is 210 Mb. |
| [get_FitWindow](./get_fitwindow/)() | Gets flag specifying whether document window must be resized to fit the first displayed page. |
| [get_FontUtilities](./get_fontutilities/)() | [IDocumentFontUtilities](./idocumentfontutilities/) instance. |
| [get_Form](./get_form/)() | Gets Acro Form of the document. |
| [get_HandleSignatureChange](./get_handlesignaturechange/)() const | Throw Exception if the document will save with changes and have signature. |
| [get_HideMenubar](./get_hidemenubar/)() | Gets flag specifying whether menu bar should be hidden when document is active. |
| [get_HideToolBar](./get_hidetoolbar/)() | Gets flag specifying whether toolbar should be hidden when document is active. |
| [get_HideWindowUI](./get_hidewindowui/)() | Gets flag specifying whether user interface elements should be hidden when document is active. |
| [get_Id](./get_id/)() | Gets the ID. |
| [get_IgnoreCorruptedObjects](./get_ignorecorruptedobjects/)() | Gets flag of ignoring errors in source files. When pages from source document copied into destination document, copying process is stopped with exception if some objects in source files are corrupted when this flag is false. example: dest.Pages.Add(src.Pages); If this flag is set to true then corrupted objects will be replaced with empty values. By default: true. |
| [get_Info](./get_info/)() | Gets document info. |
| [get_IsEncrypted](./get_isencrypted/)() | Gets encrypted status of the document. True if document is encrypted. |
| static [get_IsLicensed](./get_islicensed/)() | Gets licensed state of the system. Returns true is system works in licensed mode and false otherwise. |
| [get_IsLinearized](./get_islinearized/)() | Gets a value indicating whether document is linearized. |
| [get_IsPdfaCompliant](./get_ispdfacompliant/)() | Gets the is document pdfa compliant. |
| [get_IsPdfUaCompliant](./get_ispdfuacompliant/)() | Gets the is document pdfua compliant. |
| [get_IsXrefGapsAllowed](./get_isxrefgapsallowed/)() | Gets the is document pdfa compliant. |
| [get_JavaScript](./get_javascript/)() | [Collection](../collection/) of JavaScript of document level. |
| [get_LogicalStructure](./get_logicalstructure/)() | Gets logical structure of the document. |
| [get_Metadata](./get_metadata/)() | [Document](./) metadata. (A PDF document may include general information, such as the document's title, author, and creation and modification dates. Such global information about the document (as opposed to its content or structure) is called metadata and is intended to assist in cataloguing and searching for documents in external databases.) |
| [get_NamedDestinations](./get_nameddestinations/)() | [Collection](../collection/) of Named Destination in the document. |
| [get_NonFullScreenPageMode](./get_nonfullscreenpagemode/)() | Gets page mode, specifying how to display the document on exiting full-screen mode. |
| [get_OpenAction](./get_openaction/)() | Gets action performed at document opening. |
| [get_OptimizeSize](./get_optimizesize/)() | Gets optimization flag. When pages are added to document, equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false. |
| [get_Outlines](./get_outlines/)() | Gets document outlines. |
| [get_OutputIntents](./get_outputintents/)() | Gets the collection of Output intents in the document. |
| [get_PageInfo](./get_pageinfo/)() | Gets the page info.(for generator only, not filled in when reading document) |
| [get_PageLabels](./get_pagelabels/)() | Gets page labels in the document. |
| [get_PageLayout](./get_pagelayout/)() | Gets page layout which shall be used when the document is opened. |
| [get_PageMode](./get_pagemode/)() | Gets page mode, specifying how document should be displayed when opened. |
| [get_Pages](./get_pages/)() | Gets collection of document pages. [Note](../note/) that pages are numbered from 1 in collection. |
| [get_PdfFormat](./get_pdfformat/)() | Gets PDF format. |
| [get_Permissions](./get_permissions/)() | Gets permissions of the document. |
| [get_PickTrayByPdfSize](./get_picktraybypdfsize/)() | Gets a flag specifying whether the PDF page size shall be used to select the input paper tray. |
| [get_PrintScaling](./get_printscaling/)() | Gets the page scaling option that shall be selected when a print dialog is displayed for this document. |
| [get_TaggedContent](./get_taggedcontent/)() |  |
| [get_Version](./get_version/)() | Gets a version of [Pdf](../) from [Pdf](../) file header. |
| [GetCatalogValue](./getcatalogvalue/)(System::String) | Returns item value from catalog dictionary. |
| [GetObjectById](./getobjectbyid/)(System::String) | Gets a object with specified ID in the document. |
| [GetXmpMetadata](./getxmpmetadata/)(System::SharedPtr\<System::IO::Stream\>) | Get XMP metadata from document. |
| [HasIncrementalUpdate](./hasincrementalupdate/)() | Checks if the current PDF document has been saved with incremental updates. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(System::String) | Imports annotations from XFDF file to document. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(System::SharedPtr\<System::IO::Stream\>) | Imports annotations from stream to document. |
| [IsRepairNeeded](./isrepairneeded/)(System::SharedPtr\<Document::RepairOptions\>\&) | Checks if document requires Repair method call. |
| [LoadFrom](./loadfrom/)(System::String, System::SharedPtr\<LoadOptions\>) | Loads a file, converting it to PDF. |
| [Merge](./merge/)(System::SharedPtr\<Document::MergeOptions\>, const System::ArrayPtr\<System::SharedPtr\<Document\>\>\&) | Merges documents. |
| [Merge](./merge/)(System::SharedPtr\<Document::MergeOptions\>, const System::ArrayPtr\<System::String\>\&) | Merges documents. |
| [Merge](./merge/)(const System::ArrayPtr\<System::SharedPtr\<Document\>\>\&) | Merges documents. |
| [Merge](./merge/)(const System::ArrayPtr\<System::String\>\&) | Merges pdf files. |
| static [MergeDocuments](./mergedocuments/)(System::SharedPtr\<Document::MergeOptions\>, const System::ArrayPtr\<System::String\>\&) | Merges documents. |
| static [MergeDocuments](./mergedocuments/)(System::SharedPtr\<Document::MergeOptions\>, const System::ArrayPtr\<System::SharedPtr\<Document\>\>\&) | Merges documents. |
| static [MergeDocuments](./mergedocuments/)(const System::ArrayPtr\<System::String\>\&) | Merges pdf files. |
| static [MergeDocuments](./mergedocuments/)(const System::ArrayPtr\<System::SharedPtr\<Document\>\>\&) | Merges documents. |
| [Optimize](./optimize/)() | Linearize the document in order to. |
| [OptimizeResources](./optimizeresources/)() | Optimize resources in the document: |
| [OptimizeResources](./optimizeresources/)(System::SharedPtr\<Aspose::Pdf::Optimization::OptimizationOptions\>) | Optimize resources in the document according to defined optimization strategy. |
| [PageNodesToBalancedTree](./pagenodestobalancedtree/)(uint8_t) | Organizes page tree nodes in a document into a balanced tree. Only if the document has more than nodesNumInSubtrees page objects, otherwise it does nothing. Do not call this method while iterating over Pages elements, it may give unpredictable results. |
| [ProcessParagraphs](./processparagraphs/)() | Process paragraphs for generator. |
| [RemoveMetadata](./removemetadata/)() | Removes metadata from the document. |
| [RemovePdfaCompliance](./removepdfacompliance/)() | Remove pdfa compliance from the document. |
| [RemovePdfUaCompliance](./removepdfuacompliance/)() | Remove pdfUa compliance from the document. |
| [Repair](./repair/)(System::SharedPtr\<Document::RepairOptions\>) | Repairs broken document. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) | Stores document into stream. |
| [Save](./save/)(System::String) | Saves document into the specified file. |
| [Save](./save/)() | Save document incrementally (i.e. using incremental update technique). |
| [Save](./save/)(System::SharedPtr\<SaveOptions\>) | Saves the document with save options. |
| [Save](./save/)(System::String, SaveFormat) | Saves the document with a new name along with a file format. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, SaveFormat) | Saves the document with a new name along with a file format. |
| [Save](./save/)(System::String, System::SharedPtr\<SaveOptions\>) | Saves the document with a new name setting its save options. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<SaveOptions\>) | Saves the document to a stream with a save options. |
| [Save](./save/)(System::SharedPtr\<System::Web::HttpResponse\>, System::String, ContentDisposition, System::SharedPtr\<SaveOptions\>) | Saves the document to a response stream with a save options. |
| [SaveXml](./savexml/)(System::String) | Save document to XML. |
| [SendTo](./sendto/)(System::SharedPtr\<Devices::DocumentDevice\>, System::SharedPtr\<System::IO::Stream\>) | Sends the whole document to the document device for processing. |
| [SendTo](./sendto/)(System::SharedPtr\<Devices::DocumentDevice\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) | Sends the certain pages of the document to the document device for processing. |
| [SendTo](./sendto/)(System::SharedPtr\<Devices::DocumentDevice\>, System::String) | Sends the whole document to the document device for processing. |
| [SendTo](./sendto/)(System::SharedPtr\<Devices::DocumentDevice\>, int32_t, int32_t, System::String) | Sends the whole document to the document device for processing. |
| [set_AllowReusePageContent](./set_allowreusepagecontent/)(bool) | Allows to merge page contents to optimize docuement size. If used then differnet but duplicated pages may reference to the same content object. Please note that this mode may cause side effects like changing page content when other page is changed. |
| [set_Background](./set_background/)(System::SharedPtr\<Color\>) | Sets the background color of the document. |
| [set_CenterWindow](./set_centerwindow/)(bool) | Sets flag specifying whether position of the document's window will be centerd on the screen. |
| [set_Collection](./set_collection/)(System::SharedPtr\<Aspose::Pdf::Collection\>) | Gets collection of document. |
| [set_Direction](./set_direction/)(Aspose::Pdf::Direction) | Sets reading order of text: L2R (left to right) or R2L (right to left). |
| [set_DisableFontLicenseVerifications](./set_disablefontlicenseverifications/)(bool) | Many operations with font can't be executed if these operations are prohibited by license of this font. For example some font can't be embedded into PDF document if license rules disable embedding for this font. This flag is used to disable any license restrictions for all fonts in current PDF document. Be careful when using this flag. When it is set it means that person who sets this flag, takes all responsibility of possible license/law violations on himself. So He takes it on it's own risk. It's strongly recommended to use this flag only when you are fully confident that you are not breaking the copyright law. By default false. |
| [set_DisplayDocTitle](./set_displaydoctitle/)(bool) | Sets flag specifying whether document's window title bar should display document title. |
| [set_Duplex](./set_duplex/)(PrintDuplex) | Sets print duplex mode handling option to use when printing the file from the print dialog. |
| [set_EmbedStandardFonts](./set_embedstandardfonts/)(bool) | Property which declares that document must embed all standard Type1 fonts which has flag IsEmbedded set into true. All PDF fonts can be embedded into document simply via setting of flag IsEmbedded into true, but PDF standard Type1 fonts is an exception from this rule. Standard Type1 font embedding requires much time, so to embed these fonts it's necessary not only set flag IsEmbedded into true for specified font but also set an additiona flag on document's level - EmbedStandardFonts = true; This property can be set only one time for all fonts. By default false. |
| [set_EnableNotificationLogging](./set_enablenotificationlogging/)(bool) | Sets a value indicating whether to enable the logging of notifications. |
| [set_EnableObjectUnload](./set_enableobjectunload/)(bool) | Get or sets flag which enables document partially be unloaded from memory. This allow to decrease memory usage but may have negative effect on perfomance. |
| [set_EnableSignatureSanitization](./set_enablesignaturesanitization/)(bool) | Sets flag to manage signature fields sanitization. Enabled by default. |
| static [set_FileSizeLimitToMemoryLoading](./set_filesizelimittomemoryloading/)(int32_t) | Get and set the file size limit for loading an entire file into memory. The value is set in megabytes. The default value is 210 Mb. |
| [set_FitWindow](./set_fitwindow/)(bool) | Sets flag specifying whether document window must be resized to fit the first displayed page. |
| [set_HandleSignatureChange](./set_handlesignaturechange/)(bool) | Throw Exception if the document will save with changes and have signature. |
| [set_HideMenubar](./set_hidemenubar/)(bool) | Sets flag specifying whether menu bar should be hidden when document is active. |
| [set_HideToolBar](./set_hidetoolbar/)(bool) | Sets flag specifying whether toolbar should be hidden when document is active. |
| [set_HideWindowUI](./set_hidewindowui/)(bool) | Sets flag specifying whether user interface elements should be hidden when document is active. |
| [set_IgnoreCorruptedObjects](./set_ignorecorruptedobjects/)(bool) | Sets flag of ignoring errors in source files. When pages from source document copied into destination document, copying process is stopped with exception if some objects in source files are corrupted when this flag is false. example: dest.Pages.Add(src.Pages); If this flag is set to true then corrupted objects will be replaced with empty values. By default: true. |
| [set_IsLinearized](./set_islinearized/)(bool) | Sets a value indicating whether document is linearized. |
| [set_IsXrefGapsAllowed](./set_isxrefgapsallowed/)(bool) | Sets the is document pdfa compliant. |
| [set_NonFullScreenPageMode](./set_nonfullscreenpagemode/)(Aspose::Pdf::PageMode) | Sets page mode, specifying how to display the document on exiting full-screen mode. |
| [set_OpenAction](./set_openaction/)(System::SharedPtr\<Annotations::IAppointment\>) | Sets action performed at document opening. |
| [set_OptimizeSize](./set_optimizesize/)(bool) | Sets optimization flag. When pages are added to document, equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false. |
| [set_PageInfo](./set_pageinfo/)(System::SharedPtr\<Aspose::Pdf::PageInfo\>) | Sets the page info.(for generator only, not filled in when reading document) |
| [set_PageLayout](./set_pagelayout/)(Aspose::Pdf::PageLayout) | Sets page layout which shall be used when the document is opened. |
| [set_PageMode](./set_pagemode/)(Aspose::Pdf::PageMode) | Sets page mode, specifying how document should be displayed when opened. |
| [set_PickTrayByPdfSize](./set_picktraybypdfsize/)(bool) | Sets a flag specifying whether the PDF page size shall be used to select the input paper tray. |
| [set_PrintScaling](./set_printscaling/)(Aspose::Pdf::PrintScaling) | Sets the page scaling option that shall be selected when a print dialog is displayed for this document. |
| static [SetDefaultFileSizeLimitToMemoryLoading](./setdefaultfilesizelimittomemoryloading/)() | Sets the file size limit for loading an entire file into memory to default value equals 210 Mb. |
| [SetTitle](./settitle/)(System::String) | Set Title for [Pdf](../)[Document](./). |
| [SetXmpMetadata](./setxmpmetadata/)(System::SharedPtr\<System::IO::Stream\>) | Set XMP metadata of document. |
| [Validate](./validate/)(System::String, Aspose::Pdf::PdfFormat) | Validate document into the specified file. |
| [Validate](./validate/)(System::SharedPtr\<System::IO::Stream\>, Aspose::Pdf::PdfFormat) | Validate document into the specified file. |
| [Validate](./validate/)(System::SharedPtr\<PdfFormatConversionOptions\>) | Validate document into the specified file. |
## Fields

| Field | Description |
| --- | --- |
| static [DefaultNodesNumInSubtrees](./defaultnodesnuminsubtrees/) |  |
## Typedefs

| Typedef | Description |
| --- | --- |
| [CallBackGetHocr](./callbackgethocr/) | The call back procedure for hocr recognize. |
| [CallBackGetHocrWithPage](./callbackgethocrwithpage/) | The call back procedure for hocr recognize. |
| [FontSubstitutionHandler](./fontsubstitutionhandler/) | Represents the method that will handle FontSubstitution event. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
