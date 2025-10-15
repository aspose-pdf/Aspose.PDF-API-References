---
title: Aspose::Pdf::Facades namespace
linktitle: Aspose::Pdf::Facades
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades namespace. The Aspose.Pdf.Facades namespace provides classes originaly came from Aspose.Pdf.Kit. These classes are used for manipulating documents perfoming operations like concatenating, stamping, signing, annotating etc. but on the high level without access to a document''s inner structure in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf.facades/
---

The **[Aspose.Pdf.Facades](./)** namespace provides classes originaly came from Aspose.Pdf.Kit. These classes are used for manipulating documents perfoming operations like concatenating, stamping, signing, annotating etc. but on the high level without access to a document's inner structure.

## Classes

| Class | Description |
| --- | --- |
| [AutoFiller](./autofiller/) | Represents a class to receive data from database or other datasource, fills them into the designed fields of the template pdf and at last generates new pdf file or stream. It has two template file input modes:input as a stream or a pdf file. It has four types of output modes:one merged stream, one merged file, many small streams, many small files. It can recieve literal data contained in a [System.Data.DataTable](../system.data/datatable/). |
| [BDCProperties](./bdcproperties/) | BDC operator properties. |
| [Bookmark](./bookmark/) | Represents a bookmark. |
| [Bookmarks](./bookmarks/) | Represents a collection of [Bookmark](./bookmark/) objects. |
| [DocumentPrivilege](./documentprivilege/) | Represents the privileges for accessing [Pdf](../aspose.pdf/) file. Refer to[PdfFileSecurity](./pdffilesecurity/). There are 4 ways using this class: 1.Using predefined privilege directly. 2.Based on a predefined privilege and change some specifical permissions. 3.Based on a predefined privilege and change some specifical Adobe Professional permissions combination. 4.Mixes the way2 and way3. |
| [Facade](./facade/) | Base facade class. |
| [FontColor](./fontcolor/) | Class representing color of the text. |
| [Form](./form/) | Class representing Acro form object. |
| [FormattedText](./formattedtext/) | Class which represents formatted text. Contains information about text and its color, size, style. |
| [FormEditor](./formeditor/) | Class for editing forms (ading/deleting field etc) |
| [FormFieldFacade](./formfieldfacade/) | Class for representing field properties. |
| [IFacade](./ifacade/) | General facade interface that defines common facades methods. |
| [ISaveableFacade](./isaveablefacade/) | [Facade](./facade/) interface that defines methods common for all saveable facades. |
| [LineInfo](./lineinfo/) | Represents the information of line. |
| [PdfAnnotationEditor](./pdfannotationeditor/) | Represents a class for work with PDF document annotations (comments). |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | Represents a class to work with PDF file's bookmarks including create, modify, export, import and delete. |
| [PdfContentEditor](./pdfcontenteditor/) | Represents a class to edit PDF file's content. |
| [PdfConverter](./pdfconverter/) | Represents a class to convert a pdf file's each page to images, supporting BMP, JPEG, PNG and TIFF now. Supported content in pdfs: pictures, form, comment. |
| [PdfExtractor](./pdfextractor/) | Class for extracting images and text from PDF document. |
| [PdfFileEditor](./pdffileeditor/) | Implements operations with PDF file: concatenation, splitting, extracting pages, making booklet, etc. |
| [PdfFileInfo](./pdffileinfo/) | Represents a class for accessing meta information of PDF document. |
| [PdfFileMend](./pdffilemend/) | Represents a class for adding texts and images on the pages of existing PDF document. |
| [PdfFileSanitization](./pdffilesanitization/) | Represents sanitization and recovery API. Use it if you can't create/open documents in any other way. |
| [PdfFileSecurity](./pdffilesecurity/) | Represents encrypting or decrypting a [Pdf](../aspose.pdf/) file with owner or user password, changing the security setting and password. |
| [PdfFileSignature](./pdffilesignature/) | Represents a class to sign a pdf file with a certificate. |
| [PdfFileStamp](./pdffilestamp/) | Class for adding stamps (watermark or background) to PDF files. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | Class for removing all Java Script code. |
| [PdfPageEditor](./pdfpageeditor/) | Represents a class to edit the PDF file's page, including rotating page, zooming page, moving position and changing page size. |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | Represents an object that contains current printing page info. |
| [PdfProducer](./pdfproducer/) | Represents a class to produce PDF from other formats. |
| [PdfXmpMetadata](./pdfxmpmetadata/) | Class for manipulation with XMP metadata. |
| [ReplaceTextStrategy](./replacetextstrategy/) | This class contains parameters which define [PdfContentEditor](./pdfcontenteditor/) behavior when ReplaceText operation is performed. |
| [SaveableFacade](./saveablefacade/) | Base class for all saveable facades. |
| [SignatureName](./signaturename/) | Represents a class for a signature name. |
| [Stamp](./stamp/) | Class represeting stamp. |
| [StampInfo](./stampinfo/) | Class representing stamp information. |
| [TextProperties](./textproperties/) | Represents text properties such as: text size, color, style etc. |
| [ViewerPreference](./viewerpreference/) | Describes viewer prefereces (page mode, non full screen page mode, page layout). |
## Enums

| Enum | Description |
| --- | --- |
| [Algorithm](./algorithm/) | Represents algorithms which can be used to encrypt pdf document. |
| [AutoRotateMode](./autorotatemode/) | [Direction](../aspose.pdf/direction/) of the rotation when document is printed. |
| [BlendingColorSpace](./blendingcolorspace/) | Class represents blending color space. |
| [DataType](./datatype/) | Enumerates field types definitions. |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | Enumeration of standard XMP properties. |
| [EncodingType](./encodingtype/) | Enumerates encoding types of the text using. |
| [FieldType](./fieldtype/) | Enumeration of possible field types. |
| [FontStyle](./fontstyle/) | Enumerates 14 types of font. |
| [ImageMergeMode](./imagemergemode/) | Represents modes for merging images. |
| [KeySize](./keysize/) | Defines different key sizes which can be used to encrypt pdf documents. |
| [PositioningMode](./positioningmode/) | Defines positioning mode. Possible values include Legacy (backward compatibility) and Current (updated text position calculation method) |
| [PropertyFlag](./propertyflag/) | Enumeration of possible field flags. |
| [StampType](./stamptype/) | Describes stamp types. |
| [SubmitFormFlag](./submitformflag/) | Enumeration of possible submit form flags. |
| [WordWrapMode](./wordwrapmode/) | Defines word wrapping strategies. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | Represents the method that handles the [PdfViewer::PdfQueryPageSettings](../) event of a [PdfViewer](../). |
