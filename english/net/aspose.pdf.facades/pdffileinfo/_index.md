---
title: "PdfFileInfo Class"
linktitle: "PdfFileInfo"
articleTitle: "PdfFileInfo"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.PdfFileInfo class. Represents a class for accessing meta information of PDF document."
type: docs
weight: 410
url: "/net/aspose.pdf.facades/pdffileinfo/"
keywords: "PdfFileInfo, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfFileInfo class

Represents a class for accessing meta information of PDF document.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileInfo](./pdffileinfo/#constructor) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class with default values. |
| [PdfFileInfo](./pdffileinfo/#constructor_1)(*Stream*) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class. |
| [PdfFileInfo](./pdffileinfo/#constructor_2)(*string*) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class. |
| [PdfFileInfo](./pdffileinfo/#constructor_3)(*[Document](../../aspose.pdf/document/)*) | Initializes new [`PdfFileInfo`](../../aspose.pdf.facades/pdffileinfo/) object on base of the *document*. |
| [PdfFileInfo](./pdffileinfo/#constructor_4)(*Stream, string*) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class. |
| [PdfFileInfo](./pdffileinfo/#constructor_5)(*string, string*) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class. |
| [PdfFileInfo](./pdffileinfo/#constructor_6)(*Stream, string, [ICustomSecurityHandler](../../aspose.pdf.security/icustomsecurityhandler/)*) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class. |
| [PdfFileInfo](./pdffileinfo/#constructor_7)(*string, string, [ICustomSecurityHandler](../../aspose.pdf.security/icustomsecurityhandler/)*) | Initializes a new instance of the Aspose.Pdf.Facades.PdfFileInfo class. |

## Properties

| Name | Description |
| --- | --- |
| [Author](./author/) { get; set; } | Gets or sets the Author information of PDF document. |
| [CreationDate](./creationdate/) { get; set; } | Gets or sets the CreationDate information of PDF document. |
| [Creator](./creator/) { get; set; } | Gets or sets the Creator information of PDF document. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. *(Inherited from Facade)* |
| [HasCollection](./hascollection/) { get; } | Returns true if the current input file is a 'Portfolio' file containing collection of PDF files in it. |
| [HasEditPassword](./haseditpassword/) { get; } | Returns true if password is needed to modify permissions or document security property. |
| [HasOpenPassword](./hasopenpassword/) { get; } | Returns true if password is needed to open password protected pdf document. |
| [Header](./header/) { get; set; } | Gets or sets the customized information of PDF document. |
| [InputFile](./inputfile/) { get; set; } | Gets or sets the input file. |
| [InputStream](./inputstream/) { get; set; } | Gets or sets the input stream. |
| [IsEncrypted](./isencrypted/) { get; } | Checkes whether the PDF document is encrypted. |
| [IsPdfFile](./ispdffile/) { get; } | Checkes whether the source input is a valid PDF file. |
| [Keywords](./keywords/) { get; set; } | Gets or sets the Keywords information of PDF document. |
| [ModDate](./moddate/) { get; set; } | Gets or sets the ModDate date information of PDF document. |
| [NumberOfPages](./numberofpages/) { get; } | Gets the number of document pages. |
| [PasswordType](./passwordtype/) { get; } | Returns the type of password which was passed for creating PdfFileInfo instance. See possible values in `PasswordType`. |
| [Producer](./producer/) { get; } | Gets the Producer information of PDF document. |
| [Subject](./subject/) { get; set; } | Gets or sets the Subject information of PDF document. |
| [Title](./title/) { get; set; } | Gets or sets the Title information of PDF document. |
| [UseStrictValidation](./usestrictvalidation/) { get; set; } | Uses strict validation rules via using `IsPdfFile` property. |

## Methods

| Name | Description |
| --- | --- |
| [BindPdf](./bindpdf/)(*Document*) | Initializes the facade. |
| [ClearInfo](./clearinfo/) | Clears all meta information of PDF document. |
| [Close](./close/) | Deinitializes the instance. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/) | Disposes the facade. *(Inherited from Facade)* |
| [GetDocumentPrivilege](./getdocumentprivilege/) | Gets the PDF document privilege settings. |
| [GetMetaInfo](./getmetainfo/)(*string*) | Gets customized information of PDF document with property name. If there is no property match the name it will return a blank string. |
| [GetPageHeight](./getpageheight/)(*int*) | Gets the height of the specified page. |
| [GetPageRotation](./getpagerotation/)(*int*) | Gets the rotation of the specified page. |
| [GetPageWidth](./getpagewidth/)(*int*) | Gets the width of the specified page. |
| [GetPageXOffset](./getpagexoffset/)(*int*) | Gets the horizontal offset of the specified page display area. |
| [GetPageYOffset](./getpageyoffset/)(*int*) | Gets the vertical offset of the specified page display area. |
| [GetPdfVersion](./getpdfversion/) | Gets the version info of PDF document. |
| [Save](./save/)(*Stream*) | Saves the PDF document to the specified file. |
| [Save](./save/)(*string*) | Saves the PDF document to the specified file. |
| [SaveNewInfo](./savenewinfo/)(*Stream*) | Save updated PDF document into specified stream. |
| [SaveNewInfo](./savenewinfo/)(*string*) | Save updated PDF document into specified file. |
| [SaveNewInfoWithXmp](./savenewinfowithxmp/)(*string*) | Changes the properties specified explicitly by setting file information, other properties remain. |
| [SetMetaInfo](./setmetainfo/)(*string, string*) | Sets customized information of PDF document. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

