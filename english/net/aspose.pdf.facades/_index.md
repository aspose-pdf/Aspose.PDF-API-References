---
title: Aspose.Pdf.Facades
second_title: Aspose.PDF for .NET API Reference
description: The Aspose.Pdf.Facades namespace provides classes originaly came from Aspose.Pdf.Kit. These classes are used for manipulating documents perfoming operations like concatenating stamping signing annotating etc. but on the high level without access to a documents inner structure.
type: docs
weight: 80
url: /net/aspose.pdf.facades/
---
The **Aspose.Pdf.Facades** namespace provides classes originaly came from Aspose.Pdf.Kit. These classes are used for manipulating documents perfoming operations like concatenating, stamping, signing, annotating etc. but on the high level without access to a document's inner structure.

## Classes

| Class | Description |
| --- | --- |
| [AutoFiller](./autofiller) | Represents a class to receive data from database or other datasource, fills them into the designed fields of the template pdf and at last generates new pdf file or stream. It has two template file input modes:input as a stream or a pdf file. It has four types of output modes:one merged stream, one merged file, many small streams, many small files. It can recieve literal data contained in a System.Data.DataTable. |
| [Bookmark](./bookmark) | Represents a bookmark. |
| [Bookmarks](./bookmarks) | Represents a collection of [`Bookmark`](../aspose.pdf.facades/bookmark) objects. |
| [DocumentPrivilege](./documentprivilege) | Represents the privileges for accessing Pdf file. Refer to[`PdfFileSecurity`](../aspose.pdf.facades/pdffilesecurity). There are 4 ways using this class: 1.Using predefined privilege directly. 2.Based on a predefined privilege and change some specifical permissions. 3.Based on a predefined privilege and change some specifical Adobe Professional permissions combination. 4.Mixes the way2 and way3. |
| [Facade](./facade) | Base facade class. |
| [FontColor](./fontcolor) | Class representing color of the text. |
| [Form](./form) | Class representing Acro form object. |
| [FormattedText](./formattedtext) | Class which represents formatted text. Contains information about text and its color, size, style. |
| [FormDataConverter](./formdataconverter) | Represents a class to convert data from one format to another format. It can convert the data in fdf/xml/pdf/xfdf to the OLEDB/OdbcDB. It also can convert the data in the OLEDB/OdbcDB to the data in fdf/xml/xfdf. It can convert the fdf to the xml with "hard-named" tag. |
| [FormEditor](./formeditor) | Class for editing forms (ading/deleting field etc) |
| [FormFieldFacade](./formfieldfacade) | Class for representing field properties. |
| [LineInfo](./lineinfo) | Represents the information of line. |
| [PdfAnnotationEditor](./pdfannotationeditor) | Represents a class for work with PDF document annotations (comments). |
| [PdfBookmarkEditor](./pdfbookmarkeditor) | Represents a class to work with PDF file's bookmarks including create, modify, export, import and delete. |
| [PdfContentEditor](./pdfcontenteditor) | Represents a class to edit PDF file's content. |
| [PdfConverter](./pdfconverter) | Represents a class to convert a pdf file's each page to images, supporting BMP, JPEG, PNG and TIFF now. Supported content in pdfs: pictures, form, comment. |
| [PdfExtractor](./pdfextractor) | Class for extracting images and text from PDF document. |
| [PdfFileEditor](./pdffileeditor) | Implements operations with PDF file: concatenation, splitting, extracting pages, making booklet, etc. |
| [PdfFileInfo](./pdffileinfo) | Represents a class for accessing meta information of PDF document. |
| [PdfFileMend](./pdffilemend) | Represents a class for adding texts and images on the pages of existing PDF document. |
| [PdfFileSanitization](./pdffilesanitization) | Represents sanitization and recovery API. Use it if you can't create/open documents in any other way. |
| [PdfFileSecurity](./pdffilesecurity) | Represents encrypting or decrypting a Pdf file with owner or user password, changing the security setting and password. |
| [PdfFileSignature](./pdffilesignature) | Represents a class to sign a pdf file with a certificate. |
| [PdfFileStamp](./pdffilestamp) | Class for adding stamps (watermark or background) to PDF files. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper) | Class for removing all Java Script code. |
| [PdfPageEditor](./pdfpageeditor) | Represents a class to edit the PDF file's page, including rotating page, zooming page, moving position and changing page size. |
| [PdfPrintPageInfo](./pdfprintpageinfo) | Represents an object that contains current printing page info. |
| [PdfProducer](./pdfproducer) | Represents a class to produce PDF from other formats. This sample shows how to produce Pdf file from CGM file. |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler) | Represents the method that handles the QueryPageSettings event of a PrintDocument. |
| [PdfViewer](./pdfviewer) | Represents a class to view or print a pdf. |
| [PdfXmpMetadata](./pdfxmpmetadata) | Class for manipulation with XMP metadata. |
| [ReplaceTextStrategy](./replacetextstrategy) | This class contains parameters which define PdfContentEditor behavior when ReplaceText operation is performed. |
| [SaveableFacade](./saveablefacade) | Base class for all saveable facades. |
| [Stamp](./stamp) | Class represeting stamp. |
| [StampInfo](./stampinfo) | Class representing stamp information. |
| [TextProperties](./textproperties) | Represents text properties such as: text size, color, style etc. |
| [ViewerPreference](./viewerpreference) | Describes viewer prefereces (page mode, non full screen page mode, page layout). |
## Interfaces

| Interface | Description |
| --- | --- |
| [IFacade](./ifacade) | General facade interface that defines common facades methods. |
| [ISaveableFacade](./isaveablefacade) | Facade interface that defines methods common for all saveable facades. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [Algorithm](./algorithm) | Represents algorithms which can be used to encrypt pdf document. |
| [AutoRotateMode](./autorotatemode) | Direction of the rotation when document is printed. |
| [BlendingColorSpace](./blendingcolorspace) | Class represents blending color space. |
| [DataType](./datatype) | Enumerates field types definitions. |
| [DefaultMetadataProperties](./defaultmetadataproperties) | Enumeration of standard XMP properties. |
| [EncodingType](./encodingtype) | Enumerates encoding types of the text using. |
| [FieldType](./fieldtype) | Enumeration of possible field types. |
| [FontStyle](./fontstyle) | Enumerates 14 types of font. |
| [ImageMergeMode](./imagemergemode) | Represents modes for merging images. |
| [KeySize](./keysize) | Defines different key sizes which can be used to encrypt pdf documents. |
| [PositioningMode](./positioningmode) | Defines positioning mode. Possible values include Legacy (backward compatibility) and Current (updated text position calculation method) |
| [PropertyFlag](./propertyflag) | Enumeration of possible field flags. |
| [StampType](./stamptype) | Describes stamp types. |
| [SubmitFormFlag](./submitformflag) | Enumeration of possible submit form flags. |
| [WordWrapMode](./wordwrapmode) | Defines word wrapping strategies |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
