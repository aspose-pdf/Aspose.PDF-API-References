---
title: PdfFileInfo
second_title: Aspose.PDF for .NET API Reference
description: Represents a class for accessing meta information of PDF document.
type: docs
weight: 2570
url: /net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class

Represents a class for accessing meta information of PDF document.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileInfo](pdffileinfo#constructor)() | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class with default values. |
| [PdfFileInfo](pdffileinfo#constructor_1)(Document) | Initializes new [`PdfFileInfo`](../pdffileinfo) object on base of the *document*. |
| [PdfFileInfo](pdffileinfo#constructor_2)(Stream) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class. |
| [PdfFileInfo](pdffileinfo#constructor_4)(string) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class. |
| [PdfFileInfo](pdffileinfo#constructor_3)(Stream, string) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class. |
| [PdfFileInfo](pdffileinfo#constructor_5)(string, string) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class. |

## Properties

| Name | Description |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author) { get; set; } | Gets or sets the Author information of PDF document. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate) { get; set; } | Gets or sets the CreationDate information of PDF document. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator) { get; set; } | Gets or sets the Creator information of PDF document. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Gets the document facade is working on. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection) { get; } | Returns true if the current input file is a 'Portfolio' file containing collection of PDF files in it. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword) { get; } | Returns true if password is needed to modify permissions or document security property. Pay attention that this property can be read only if valid password was provided in [`PdfFileInfo`](../pdffileinfo) constructor. In case PasswordType is Inaccessible (means that invalid password was provided) reading this property will fail with [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception). |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword) { get; } | Returns true if password is needed to open password protected pdf document. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header) { get; set; } | Gets or sets the customized information of PDF document. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted) { get; } | Checkes whether the PDF document is encrypted. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile) { get; } | Checkes whether the source input is a valid PDF file. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords) { get; set; } | Gets or sets the Keywords information of PDF document. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate) { get; set; } | Gets or sets the ModDate date information of PDF document. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages) { get; } | Gets the number of document pages. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype) { get; } | Returns the type of password which was passed for creating PdfFileInfo instance. See possible values in [`PasswordType`](./passwordtype). Pay attention that pdf document can be opened using both user (or open) password and owner (or permissions, edit) password. |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer) { get; } | Gets the Producer information of PDF document. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject) { get; set; } | Gets or sets the Subject information of PDF document. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title) { get; set; } | Gets or sets the Title information of PDF document. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation) { get; set; } | Uses strict validation rules via using [`IsPdfFile`](./ispdffile) property. |

## Methods

| Name | Description |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf#bindpdf)(Document) | Initializes the facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initializes the facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initializes the facade. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo)() | Clears all meta information of PDF document. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close)() | Deinitializes the instance. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Disposes the facade. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege)() | Gets the PDF document privilege settings. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo)(string) | Gets customized information of PDF document with property name. If there is no property match the name it will return a blank string. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight)(int) | Gets the height of the specified page. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation)(int) | Gets the rotation of the specified page. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth)(int) | Gets the width of the specified page. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset)(int) | Gets the horizontal offset of the specified page display area. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset)(int) | Gets the vertical offset of the specified page display area. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion)() | Gets the version info of PDF document. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save#save)(Stream) | Saves the PDF document to the specified file. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save#save_1)(string) | Saves the PDF document to the specified file. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo#savenewinfo_1)(string) | Save updated PDF document into specified file. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp)(string) | Changes the properties specified explicitly by setting file information, other properties remain. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo)(string, string) | Sets customized information of PDF document. |

### See Also

* class [SaveableFacade](../saveablefacade)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* assembly [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
