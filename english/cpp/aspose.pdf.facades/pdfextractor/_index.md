---
title: Aspose::Pdf::Facades::PdfExtractor class
linktitle: PdfExtractor
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfExtractor class. Class for extracting images and text from PDF document in C++.'
type: docs
weight: 1900
url: /cpp/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class


Class for extracting images and text from PDF document.

```cpp
class PdfExtractor : public Aspose::Pdf::Facades::Facade
```

## Methods

| Method | Description |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Bind input PDF file. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Binds PDF document from stream. |
| [ExtractAttachment](./extractattachment/)() | Extracts attachments from a [Pdf](../../aspose.pdf/) document. |
| [ExtractAttachment](./extractattachment/)(System::String) | Extracts attachment to PDF file by attachment name. |
| [ExtractImage](./extractimage/)() | Extract images from PDF file. |
| [ExtractText](./extracttext/)() | Extracts text from a [Pdf](../../aspose.pdf/) document using Unicode encoding. |
| [ExtractText](./extracttext/)(System::SharedPtr\<System::Text::Encoding\>) | Extracts text from a [Pdf](../../aspose.pdf/) document using specified encoding. |
| [get_EndPage](./get_endpage/)() const | Gets end page in the page range where extracting operation will be performed. |
| [get_ExtractImageMode](./get_extractimagemode/)() const | Sets the mode for extract images process. |
| [get_ExtractTextMode](./get_extracttextmode/)() const | Sets the mode for extract text's result. |
| [get_IsBidi](./get_isbidi/)() | Is true when text has hebriew or arabic symbols. This case must be specially considered because string functions change their behaviour and start process text from right to left (except numbers and other non text chars). |
| [get_Password](./get_password/)() const | Gets input file's password. |
| [get_Resolution](./get_resolution/)() const | Set or gets resolution for extracted images. Default value is 150. Images which have greater resolution value are more clear. However increasing resolution value results in increasing time and memory needed to extract images. Usually to get clear image it's enough to set resolution to 150 or 300. |
| [get_StartPage](./get_startpage/)() const | Gets start page in the page range where extracting operation will be performed. |
| [get_TextSearchOptions](./get_textsearchoptions/)() const | Gets text search options. |
| [GetAttachment](./getattachment/)(System::String) | Stores attachment into file. |
| [GetAttachment](./getattachment/)() | Saves all the attachment file to streams. |
| [GetAttachmentInfo](./getattachmentinfo/)() | Gets the list of attachments. |
| [GetAttachNames](./getattachnames/)() | Returns list of attachments in PDF file. [Note](../../aspose.pdf/note/): ExtractAttachments must be called before using this method. |
| [GetNextImage](./getnextimage/)(System::String) | Retrieves next image from PDF document. [Note](../../aspose.pdf/note/): ExtractImage must be called before using of this method. |
| [GetNextImage](./getnextimage/)(System::String, System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>) | Retrieves next image from PDF document with given image format. [Note](../../aspose.pdf/note/): ExtractImage must be called before using of this method. |
| [GetNextImage](./getnextimage/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>) | Retrieve next image from PDF file and stores it into stream with given image format. |
| [GetNextImage](./getnextimage/)(System::SharedPtr\<System::IO::Stream\>) | Retrieve next image from PDF file and stores it into stream. |
| [GetNextPageText](./getnextpagetext/)(System::String) | Saves one page's text to file. |
| [GetNextPageText](./getnextpagetext/)(System::SharedPtr\<System::IO::Stream\>) | Saves one page's text to stream. |
| [GetText](./gettext/)(System::String) | Saves text to file. see also:[ExtractText](./extracttext/) |
| [GetText](./gettext/)(System::SharedPtr\<System::IO::Stream\>) | Saves text to stream. see also:[ExtractText](./extracttext/) |
| [GetText](./gettext/)(System::SharedPtr\<System::IO::Stream\>, bool) | Saves text to stream. see also:[ExtractText](./extracttext/) |
| [HasNextImage](./hasnextimage/)() | Checks if more images are accessible in PDF document. [Note](../../aspose.pdf/note/): ExtractImage must be called before using of this method. |
| [HasNextPageText](./hasnextpagetext/)() | Indicates that whether can get more texts or not. |
| [PdfExtractor](./pdfextractor/)() | Initializes new [PdfExtractor](./) object. |
| [PdfExtractor](./pdfextractor/)(System::SharedPtr\<Aspose::Pdf::Document\>) | Initializes new [PdfExtractor](./) object on base of the *document* . |
| [set_EndPage](./set_endpage/)(int32_t) | Sets end page in the page range where extracting operation will be performed. |
| [set_ExtractImageMode](./set_extractimagemode/)(Aspose::Pdf::ExtractImageMode) | Sets the mode for extract images process. |
| [set_ExtractTextMode](./set_extracttextmode/)(int32_t) | Sets the mode for extract text's result. |
| [set_Password](./set_password/)(System::String) | Sets input file's password. |
| [set_Resolution](./set_resolution/)(int32_t) | Set or gets resolution for extracted images. Default value is 150. Images which have greater resolution value are more clear. However increasing resolution value results in increasing time and memory needed to extract images. Usually to get clear image it's enough to set resolution to 150 or 300. |
| [set_StartPage](./set_startpage/)(int32_t) | Sets start page in the page range where extracting operation will be performed. |
| [set_TextSearchOptions](./set_textsearchoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) | Sets text search options. |
## See Also

* Class [Facade](../facade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
