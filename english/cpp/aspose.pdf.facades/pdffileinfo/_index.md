---
title: Aspose::Pdf::Facades::PdfFileInfo class
linktitle: PdfFileInfo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileInfo class. Represents a class for accessing meta information of PDF document in C++.'
type: docs
weight: 2100
url: /cpp/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class


Represents a class for accessing meta information of PDF document.

```cpp
class PdfFileInfo : public Aspose::Pdf::Facades::SaveableFacade
```

## Methods

| Method | Description |
| --- | --- |
| [BindPdf](./bindpdf/)(System::SharedPtr\<Aspose::Pdf::Document\>) override | Initializes the facade. |
| [ClearInfo](./clearinfo/)() | Clears all meta information of PDF document. |
| [Close](./close/)() override | Deinitializes the instance. |
| [get_Author](./get_author/)() | Gets the Author information of PDF document. |
| [get_CreationDate](./get_creationdate/)() | Gets the CreationDate information of PDF document. |
| [get_Creator](./get_creator/)() | Gets the Creator information of PDF document. |
| [get_HasCollection](./get_hascollection/)() | Returns true if the current input file is a 'Portfolio' file containing collection of PDF files in it. |
| [get_HasEditPassword](./get_haseditpassword/)() | Returns true if password is needed to modify permissions or document security property. Pay attention that this property can be read only if valid password was provided in [PdfFileInfo](./) constructor. In case [PasswordType](../../aspose.pdf/passwordtype/) is Inaccessible (means that invalid password was provided) reading this property will fail with [InvalidPasswordException](../../aspose.pdf/invalidpasswordexception/). |
| [get_HasOpenPassword](./get_hasopenpassword/)() | Returns true if password is needed to open password protected pdf document. |
| [get_Header](./get_header/)() const | Gets the customized information of PDF document. |
| [get_InputFile](./get_inputfile/)() const | Gets the input file. |
| [get_InputStream](./get_inputstream/)() const | Gets the input stream. |
| [get_IsEncrypted](./get_isencrypted/)() | Checkes whether the PDF document is encrypted. |
| [get_IsPdfFile](./get_ispdffile/)() | Checkes whether the source input is a valid PDF file. |
| [get_Keywords](./get_keywords/)() | Gets the Keywords information of PDF document. |
| [get_ModDate](./get_moddate/)() | Gets the ModDate date information of PDF document. |
| [get_NumberOfPages](./get_numberofpages/)() | Gets the number of document pages. |
| [get_PasswordType](./get_passwordtype/)() | Returns the type of password which was passed for creating [PdfFileInfo](./) instance. See possible values in [PasswordType](../../aspose.pdf/passwordtype/). Pay attention that pdf document can be opened using both user (or open) password and owner (or permissions, edit) password. |
| [get_Producer](./get_producer/)() | Gets the Producer information of PDF document. |
| [get_Subject](./get_subject/)() | Gets the Subject information of PDF document. |
| [get_Title](./get_title/)() | Gets the Title information of PDF document. |
| [get_UseStrictValidation](./get_usestrictvalidation/)() const | Uses strict validation rules via using [IsPdfFile](../) property. |
| [GetDocumentPrivilege](./getdocumentprivilege/)() | Gets the PDF document privilege settings. |
| [GetMetaInfo](./getmetainfo/)(System::String) | Gets customized information of PDF document with property name. If there is no property match the name it will return a blank string. |
| [GetPageHeight](./getpageheight/)(int32_t) | Gets the height of the specified page. |
| [GetPageRotation](./getpagerotation/)(int32_t) | Gets the rotation of the specified page. |
| [GetPageWidth](./getpagewidth/)(int32_t) | Gets the width of the specified page. |
| [GetPageXOffset](./getpagexoffset/)(int32_t) | Gets the horizontal offset of the specified page display area. |
| [GetPageYOffset](./getpageyoffset/)(int32_t) | Gets the vertical offset of the specified page display area. |
| [GetPdfVersion](./getpdfversion/)() | Gets the version info of PDF document. |
| [PdfFileInfo](./pdffileinfo/)() | Initializes a new instance of the [Aspose.Pdf.Facades.PdfFileInfo](./) class with default values. |
| [PdfFileInfo](./pdffileinfo/)(System::SharedPtr\<System::IO::Stream\>) | Initializes a new instance of the [Aspose.Pdf.Facades.PdfFileInfo](./) class. |
| [PdfFileInfo](./pdffileinfo/)(System::SharedPtr\<System::IO::Stream\>, System::String) | Initializes a new instance of the [Aspose.Pdf.Facades.PdfFileInfo](./) class. |
| [PdfFileInfo](./pdffileinfo/)(System::SharedPtr\<System::IO::Stream\>, System::String, System::SharedPtr\<Security::ICustomSecurityHandler\>) | Initializes a new instance of the [Aspose.Pdf.Facades.PdfFileInfo](./) class. |
| [PdfFileInfo](./pdffileinfo/)(System::String) | Initializes a new instance of the [Aspose.Pdf.Facades.PdfFileInfo](./) class. |
| [PdfFileInfo](./pdffileinfo/)(System::String, System::String) | Initializes a new instance of the [Aspose.Pdf.Facades.PdfFileInfo](./) class. |
| [PdfFileInfo](./pdffileinfo/)(System::String, System::String, System::SharedPtr\<Security::ICustomSecurityHandler\>) | Initializes a new instance of the [Aspose.Pdf.Facades.PdfFileInfo](./) class. |
| [PdfFileInfo](./pdffileinfo/)(System::SharedPtr\<Aspose::Pdf::Document\>) | Initializes new [PdfFileInfo](./) object on base of the *document* . |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Saves the PDF document to the specified file. |
| [Save](./save/)(System::String) override | Saves the PDF document to the specified file. |
| [SaveNewInfo](./savenewinfo/)(System::SharedPtr\<System::IO::Stream\>) | Save updated PDF document into specified stream. |
| [SaveNewInfo](./savenewinfo/)(System::String) | Save updated PDF document into specified file. |
| [SaveNewInfoWithXmp](./savenewinfowithxmp/)(System::String) | Changes the properties specified explicitly by setting file information, other properties remain. |
| [set_Author](./set_author/)(System::String) | Sets the Author information of PDF document. |
| [set_CreationDate](./set_creationdate/)(System::String) | Sets the CreationDate information of PDF document. |
| [set_Creator](./set_creator/)(System::String) | Sets the Creator information of PDF document. |
| [set_Header](./set_header/)(System::SharedPtr\<System::Collections::Generic::Dictionary\<System::String, System::String\>\>) | Sets the customized information of PDF document. |
| [set_InputFile](./set_inputfile/)(System::String) | Sets the input file. |
| [set_InputStream](./set_inputstream/)(System::SharedPtr\<System::IO::Stream\>) | Sets the input stream. |
| [set_Keywords](./set_keywords/)(System::String) | Sets the Keywords information of PDF document. |
| [set_ModDate](./set_moddate/)(System::String) | Sets the ModDate date information of PDF document. |
| [set_Subject](./set_subject/)(System::String) | Sets the Subject information of PDF document. |
| [set_Title](./set_title/)(System::String) | Sets the Title information of PDF document. |
| [set_UseStrictValidation](./set_usestrictvalidation/)(bool) | Uses strict validation rules via using [IsPdfFile](../) property. |
| [SetMetaInfo](./setmetainfo/)(System::String, System::String) | Sets customized information of PDF document. |
## See Also

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
