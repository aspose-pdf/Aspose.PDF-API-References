---
title: com.aspose.pdf.facades
linktitle: com.aspose.pdf.facades
second_title: Aspose.PDF for Java API Reference
description: The com.aspose.pdf.facades package provides classes originally came from Aspose.Pdf.Kit.
type: docs
weight: 180
url: /java/com.aspose.pdf.facades/
---
The com.aspose.pdf.facades package provides classes originally came from Aspose.Pdf.Kit.

## Interfaces

| Interface | Description |
| --- | --- |
| [IFacade](./ifacade/) | General facade interface that defines common facades methods. |
| [IForm](./iform/) | Class representing Acro form object. |
| [IFormEditor](./iformeditor/) | Class for editing forms (adding/deleting field etc) |
| [IPdfFileEditor](./ipdffileeditor/) | Implements operations with PDF file: concatenation, splitting, extracting pages, making booklet, etc. |
| [IPdfFileStamp](./ipdffilestamp/) | interface for adding stamps (watermark or background) to PDF files. |
| [ISaveableFacade](./isaveablefacade/) | Facade interface that defines methods common for all saveable facades. |
## Classes

| Class | Description |
| --- | --- |
| [AlignmentType](./alignmenttype/) | Class contains possibly alignment types. Use HorizontalAlignment instead |
| [AutoRotateMode](./autorotatemode/) | Direction of the rotation when document is printed. |
| [BDCProperties](./bdcproperties/) | BDC operator properties. |
| [Bookmark](./bookmark/) | Represents a bookmark. |
| [Bookmarks](./bookmarks/) | Represents a collection of {@code Bookmark} objects. |
| [CgmPdfProducer](./cgmpdfproducer/) | Represents a class to produce PDF from Computer Graphics Metafile(CGM) format. |
| [DataType](./datatype/) | Enumerates field types definitions. |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | Enumeration of standard XMP properties. |
| [DocumentPrivilege](./documentprivilege/) | Represents the privileges for accessing Pdf file. Refer to{@code PdfFileSecurity}. There are 4 ways using this class: 1.Using predefined privilege directly. 2.Based on a predefined privilege and change some specifical permissions. 3.Based on a predefined privilege and change some specifical Adobe Professional permissions combination. 4.Mixes the way2 and way3. //Way1: Using predefined privilege directly. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Based on a predefined privilege and change some specifical permissions. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: Mixes the way2 and way3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true); |
| [EncodingType](./encodingtype/) | Enumerates encoding types of the text using. |
| [Facade](./facade/) | Base facade class. |
| [FontColor](./fontcolor/) | Class representing color of the text. |
| [Form](./form/) | Class representing Acro form object. |
| [Form.ImportStatus](./form.importstatus/) | Status of imported field |
| [FormattedText](./formattedtext/) | Class which represents formatted text. Contains information about text and its color, size, style. |
| [FormEditor](./formeditor/) | Class for editing forms (adding/deleting field etc) |
| [FormEditorWeb](./formeditorweb/) | Class for editing forms (ading/deleting field etc) |
| [FormFieldFacade](./formfieldfacade/) | Class for representing field properties. |
| [FormWeb](./formweb/) | Representing Acro form Interface. |
| [InternalHelper](./internalhelper/) | Help class |
| [IPdfFileEditor.ContentsResizeParameters](./ipdffileeditor.contentsresizeparameters/) | Class for specifing page resize parameters. Allow to set the following parameters: Size of result page (width, height) in default space units or in percents of initial pages size; Left, Top, Bottom and Right margins in default space units or in percents of initial page size; Some values may be left null for automatic calculation. These values will be calculated from rest of page size after calculation explicitly specified values. For example: if page width = 100 and new page width specified 60 units then left and right margins are automatically calculated: (100 - 60) / 2 = 15. This class is used in ResizeContents method. |
| [IPdfFileEditor.ContentsResizeValue](./ipdffileeditor.contentsresizevalue/) | Value of margin or content size specified in percents of default space units. This class is used in ContentsResizeParameters. |
| [LineInfo](./lineinfo/) | Represents the information of line. |
| [PdfAnnotationEditor](./pdfannotationeditor/) | Represents a class for work with PDF document annotations (comments). |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | Represents a class to work with PDF file's bookmarks including create, modify, export, import and delete. |
| [PdfContentEditor](./pdfcontenteditor/) | Represents a class to edit PDF file's content. |
| [PdfConverter](./pdfconverter/) | Represents a class to convert a pdf file's each page to images, supporting BMP, JPEG, PNG and TIFF now. Supported content in pdfs: pictures, form, comment. |
| [PdfExtractor](./pdfextractor/) | Class for extracting images and text from PDF document. |
| [PdfFileEditor](./pdffileeditor/) | Implements operations with PDF file: concatenation, splitting, extracting pages, making booklet, etc. |
| [PdfFileEditor.ConcatenateCorruptedFileAction](./pdffileeditor.concatenatecorruptedfileaction/) | Action performed when corrupted file was met in concatenation process. |
| [PdfFileEditor.ConcatenationProgressHandler](./pdffileeditor.concatenationprogresshandler/) | Represents class with abstract method that usually supplied by calling side and handles progress events that comes from concatenation. Usually such supplied customer's handler can be used to show total concatenation progress on console or in progress bar. represents information about occurred progress event |
| [PdfFileEditor.CorruptedItem](./pdffileeditor.corrupteditem/) | Class which provides information about corrupted files in time of concatenation. |
| [PdfFileEditor.PageBreak](./pdffileeditor.pagebreak/) | Data of page break position. |
| [PdfFileEditor.ProgressEventHandlerInfo](./pdffileeditor.progresseventhandlerinfo/) | This class represents information about concatenation progress that can be used in external application. |
| [PdfFileEditor.ProgressEventType](./pdffileeditor.progresseventtype/) | This enum describes possible progress event types that can occure during concatenation |
| [PdfFileEditorWeb](./pdffileeditorweb/) | Represents PdfFileEditorWeb class Implements operations with PDF file: concatenation, splitting, extracting pages, making booklet, etc. |
| [PdfFileInfo](./pdffileinfo/) | Represents a class for accessing meta information of PDF document. |
| [PdfFileMend](./pdffilemend/) | Represents a class for adding texts and images on the pages of existing PDF document. |
| [PdfFileSanitization](./pdffilesanitization/) | Represents sanitization and recovery API. Use it if you can't create/open documents in any other way. |
| [PdfFileSecurity](./pdffilesecurity/) | Represents encrypting or decrypting a Pdf file with owner or user password, changing the security setting and password. |
| [PdfFileSignature](./pdffilesignature/) | Represents a class to sign a pdf file with a certificate. |
| [PdfFileStamp](./pdffilestamp/) | Class for adding stamps (watermark or background) to PDF files. |
| [PdfFileStampWeb](./pdffilestampweb/) | Class for adding stamps (watermark or background) to PDF files. Enable to work with HttpServletResponse. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | Class for removing all Java Script code. |
| [PdfPageEditor](./pdfpageeditor/) | Represents a class to edit the PDF file's page, including rotating page, zooming page, moving position and changing page size. |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | Represents an object that contains current printing page info. |
| [PdfProducer](./pdfproducer/) | <p> Represents a class to produce PDF from other formats. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Success produced pdf file. } catch (Exception e) { // Do something... } </pre> |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | Represents the method that handles the QueryPageSettings event of a PrintDocument. |
| [PdfViewer](./pdfviewer/) | Represents a class to view or print a pdf. |
| [PdfXmpMetadata](./pdfxmpmetadata/) | Class for manipulation with XMP metadata. |
| [PositioningMode](./positioningmode/) | Defines positioning mode. Possible values include Legacy (backward compatibility) and Current (updated text position calculation method) |
| [PropertyFlag](./propertyflag/) | Enumeration of possible field flags. |
| [ReplaceTextStrategy](./replacetextstrategy/) | This class contains parameters which define PdfContentEditor behavior when ReplaceText operation is performed. |
| [SaveableFacade](./saveablefacade/) | <p> Base class for all saveable facades. |
| [SignatureName](./signaturename/) | Represents a class for a signature name. Represents a more precise signature name. Used instead of string names. Allows you to present signatures with the same string names. |
| [Stamp](./stamp/) | Class represeting stamp. |
| [StampInfo](./stampinfo/) | Class representing stamp information. |
| [TextProperties](./textproperties/) | Represents text properties such as: text size, color, style etc. |
| [VerticalAlignmentType](./verticalalignmenttype/) | Class representing possible vertical alignment values. Use VerticalAlignment instead |
| [ViewerPreference](./viewerpreference/) | Describes viewer prefereces (page mode, non full screen page mode, page layout). |
| [WordWrapMode](./wordwrapmode/) | Defines word wrapping strategies |
## Enums

| Enum | Description |
| --- | --- |
| [Algorithm](./algorithm/) | Represents algorithms which can be used to encrypt pdf document. |
| [BlendingColorSpace](./blendingcolorspace/) | Class represents blending color space. |
| [FieldType](./fieldtype/) | Enumeration of possible field types. |
| [FontStyle](./fontstyle/) | Enumerates 14 types of font. |
| [ImageMergeMode](./imagemergemode/) | Represents modes for merging images. |
| [KeySize](./keysize/) | Defines different key sizes which can be used to encrypt pdf documents. |
| [ReplaceTextStrategy.NoCharacterAction](./replacetextstrategy.nocharacteraction/) | Action to perform if font does not contain required character |
| [ReplaceTextStrategy.Scope](./replacetextstrategy.scope/) | Scope where replace text operation is applied REPLACE_FIRST by default |
| [StampType](./stamptype/) | Describes stamp types. |
| [SubmitFormFlag](./submitformflag/) | Enumeration of possible submit form flags. |
