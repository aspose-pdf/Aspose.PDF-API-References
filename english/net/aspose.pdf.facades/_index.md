---
title: "Aspose.Pdf.Facades"
linktitle: "Aspose.Pdf.Facades"
articleTitle: "Aspose.Pdf.Facades"
second_title: "Aspose.PDF for .NET API Reference"
description: "The Aspose.Pdf.Facades namespace provides classes."
type: docs
weight: 10
url: "/net/aspose.pdf.facades/"
keywords: "Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Overview

The **Aspose.Pdf.Facades** namespace provides classes.

Part of the [Aspose.PDF for .NET](../) API reference.

## Classes

| Class | Description |
| --- | --- |
| [AutoFiller](./autofiller/) | Represents a class to receive data from database or other datasource, fills them into the designed fields of the template pdf and at last generates new pdf file or stream. It has two template file input modes:input as a stream or a pdf file. It has four types of output modes:one merged stream, one merged file, many small streams, many small files. It can recieve literal data contained in a System.Data.DataTable. |
| [BDCProperties](./bdcproperties/) | BDC operator properties. |
| [Bookmark](./bookmark/) | Represents a bookmark. |
| [Bookmarks](./bookmarks/) | Represents a collection of [`Bookmark`](../aspose.pdf.facades/bookmark/) objects. |
| [DocumentPrivilege](./documentprivilege/) | Represents the privileges for accessing Pdf file. Refer to[`PdfFileSecurity`](../aspose.pdf.facades/pdffilesecurity/). There are 4 ways using this class: 1.Using predefined privilege directly. 2.Based on a predefined privilege and change some specifical permissions. 3.Based on a predefined privilege and change some specifical Adobe Professional permissions combination. 4.Mixes the way2 and way3. |
| [Facade](./facade/) | Base facade class. |
| [FontColor](./fontcolor/) | Class representing color of the text. |
| [Form](./form/) | Class representing Acro form object. |
| [Form.FormImportResult](./form.formimportresult/) | Class which describes result if field import. |
| [FormDataConverter](./formdataconverter/) | Represents a class to convert data from one format to another format. It can convert the data in fdf/xml/pdf/xfdf to the OLEDB/OdbcDB. It also can convert the data in the OLEDB/OdbcDB to the data in fdf/xml/xfdf. It can convert the fdf to the xml with "hard-named" tag. |
| [FormEditor](./formeditor/) | Class for editing forms (ading/deleting field etc) |
| [FormFieldFacade](./formfieldfacade/) | Class for representing field properties. |
| [FormattedText](./formattedtext/) | Class which represents formatted text. Contains information about text and its color, size, style. |
| [LineInfo](./lineinfo/) | Represents the information of line. |
| [PdfAnnotationEditor](./pdfannotationeditor/) | Represents a class for work with PDF document annotations (comments). |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | Represents a class to work with PDF file's bookmarks including create, modify, export, import and delete. |
| [PdfContentEditor](./pdfcontenteditor/) | Represents a class to edit PDF file's content. |
| [PdfConverter](./pdfconverter/) | Represents a class to convert a pdf file's each page to images, supporting BMP, JPEG, PNG and TIFF now. Supported content in pdfs: pictures, form, comment. |
| [PdfExtractor](./pdfextractor/) | Class for extracting images and text from PDF document. |
| [PdfFileEditor](./pdffileeditor/) | Implements operations with PDF file: concatenation, splitting, extracting pages, making booklet, etc. |
| [PdfFileEditor.ContentsResizeParameters](./pdffileeditor.contentsresizeparameters/) | Class for specifing page resize parameters. Allow to set the following parameters: Size of result page (width, height) in default space units or in percents of initial pages size; Left, Top, Bottom and Right margins in default space units or in percents of initial page size; Some values may be left null for automatic calculation. These values will be calculated from rest of page size after calculation explicitly specified values. For example: if page width = 100 and new page width specified 60 units then left and right margins are automatically calculated: (100 - 60) / 2 = 15. This class is used in ResizeContents method. |
| [PdfFileEditor.ContentsResizeValue](./pdffileeditor.contentsresizevalue/) | Value of margin or content size specified in percents of default space units. This class is used in ContentsResizeParameters. |
| [PdfFileEditor.CorruptedItem](./pdffileeditor.corrupteditem/) | Class which provides information about corrupted files in time of concatenation. |
| [PdfFileEditor.PageBreak](./pdffileeditor.pagebreak/) | Data of page break position. |
| [PdfFileInfo](./pdffileinfo/) | Represents a class for accessing meta information of PDF document. |
| [PdfFileMend](./pdffilemend/) | Represents a class for adding texts and images on the pages of existing PDF document. |
| [PdfFileSanitization](./pdffilesanitization/) | Represents sanitization and recovery API. Use it if you can't create/open documents in any other way. |
| [PdfFileSecurity](./pdffilesecurity/) | Represents encrypting or decrypting a Pdf file with owner or user password, changing the security setting and password. |
| [PdfFileSignature](./pdffilesignature/) | Represents a class to sign a pdf file with a certificate. |
| [PdfFileStamp](./pdffilestamp/) | Class for adding stamps (watermark or background) to PDF files. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | Class for removing all Java Script code. |
| [PdfPageEditor](./pdfpageeditor/) | Represents a class to edit the PDF file's page, including rotating page, zooming page, moving position and changing page size. |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | Represents an object that contains current printing page info. |
| [PdfProducer](./pdfproducer/) | Represents a class to produce PDF from other formats. This sample shows how to produce Pdf file from CGM file. |
| [PdfViewer](./pdfviewer/) | Represents a class to view or print a pdf. |
| [PdfXmpMetadata](./pdfxmpmetadata/) | Class for manipulation with XMP metadata. |
| [ReplaceTextStrategy](./replacetextstrategy/) | This class contains parameters which define PdfContentEditor behavior when ReplaceText operation is performed. |
| [SaveableFacade](./saveablefacade/) | Base class for all saveable facades. |
| [SignatureName](./signaturename/) | Represents a class for a signature name. |
| [Stamp](./stamp/) | Class represeting stamp. |
| [StampInfo](./stampinfo/) | Class representing stamp information. |
| [TextProperties](./textproperties/) | Represents text properties such as: text size, color, style etc. |
| [ViewerPreference](./viewerpreference/) | Describes viewer prefereces (page mode, non full screen page mode, page layout). |

## Interfaces

| Interface | Description |
| --- | --- |
| [IFacade](./ifacade/) | General facade interface that defines common facades methods. |
| [ISaveableFacade](./isaveablefacade/) | Facade interface that defines methods common for all saveable facades. |

## Enumeration

| Enumeration | Description |
| --- | --- |
| [Algorithm](./algorithm/) | Represents algorithms which can be used to encrypt pdf document. |
| [AutoRotateMode](./autorotatemode/) | Direction of the rotation when document is printed. |
| [BlendingColorSpace](./blendingcolorspace/) | Class represents blending color space. |
| [DataType](./datatype/) | Enumerates field types definitions. |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | Enumeration of standard XMP properties. |
| [EncodingType](./encodingtype/) | Enumerates encoding types of the text using. |
| [FieldType](./fieldtype/) | Enumeration of possible field types. |
| [FontStyle](./fontstyle/) | Enumerates 14 types of font. |
| [Form.ImportStatus](./form.importstatus/) | Status of imported field |
| [ImageMergeMode](./imagemergemode/) | Represents modes for merging images. |
| [KeySize](./keysize/) | Defines different key sizes which can be used to encrypt pdf documents. |
| [PdfFileEditor.ConcatenateCorruptedFileAction](./pdffileeditor.concatenatecorruptedfileaction/) | Action performed when corrupted file was met in concatenation process. |
| [PositioningMode](./positioningmode/) | Defines positioning mode. Possible values include Legacy (backward compatibility) and Current (updated text position calculation method) |
| [PropertyFlag](./propertyflag/) | Enumeration of possible field flags. |
| [ReplaceTextStrategy.NoCharacterAction](./replacetextstrategy.nocharacteraction/) | Action to perform if font does not contain required character |
| [ReplaceTextStrategy.Scope](./replacetextstrategy.scope/) | Scope where replace text operation is applied REPLACE_FIRST by default |
| [StampType](./stamptype/) | Describes stamp types. |
| [SubmitFormFlag](./submitformflag/) | Enumeration of possible submit form flags. |
| [WordWrapMode](./wordwrapmode/) | Defines word wrapping strategies |

## Delegates

| Delegate | Description |
| --- | --- |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | Represents the method that handles the `PdfQueryPageSettings` event of a [`PdfViewer`](../aspose.pdf.facades/pdfviewer/). |

## FAQ

### What classes does the Aspose.Pdf.Facades namespace contain?

[AutoFiller](./autofiller/), [BDCProperties](./bdcproperties/), [Bookmark](./bookmark/), [Bookmarks](./bookmarks/), [DocumentPrivilege](./documentprivilege/), and 38 more.

### How many types are in the Aspose.Pdf.Facades namespace?

The Aspose.Pdf.Facades namespace contains 65 types, listed above.

