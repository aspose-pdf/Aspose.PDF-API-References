---
title: Aspose::Pdf::Facades::PdfFileStamp class
linktitle: PdfFileStamp
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileStamp class. Class for adding stamps (watermark or background) to PDF files in C++.'
type: docs
weight: 2600
url: /cpp/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class


Class for adding stamps (watermark or background) to PDF files.

```cpp
class PdfFileStamp : public Aspose::Pdf::Facades::SaveableFacade
```

## Methods

| Method | Description |
| --- | --- |
| [AddFooter](./addfooter/)(System::SharedPtr\<FormattedText\>, float) | Adds footer to the pages of the document. |
| [AddFooter](./addfooter/)(System::SharedPtr\<FormattedText\>, float, float, float) | Adds footer to the pages of the document. |
| [AddFooter](./addfooter/)(System::String, float) | Adds image as footer to the pages of the document. |
| [AddFooter](./addfooter/)(System::String, float, float, float) | Adds image as footer of the pages. |
| [AddFooter](./addfooter/)(System::SharedPtr\<System::IO::Stream\>, float) | Adds image as footer of the page. |
| [AddFooter](./addfooter/)(System::SharedPtr\<System::IO::Stream\>, float, float, float) | Adds image as footer of the page. |
| [AddHeader](./addheader/)(System::SharedPtr\<FormattedText\>, float) | Adds header to the page. |
| [AddHeader](./addheader/)(System::SharedPtr\<FormattedText\>, float, float, float) | Adds header to the pages of file. |
| [AddHeader](./addheader/)(System::String, float) | Adds image as header to the pages of the file. |
| [AddHeader](./addheader/)(System::String, float, float, float) | Adds image as header on the pages. |
| [AddHeader](./addheader/)(System::SharedPtr\<System::IO::Stream\>, float) | Adds image as header on the pages. |
| [AddHeader](./addheader/)(System::SharedPtr\<System::IO::Stream\>, float, float, float) | Adds image at the top of the page. |
| [AddPageNumber](./addpagenumber/)(System::String) | Add page number to file. [Page](../../aspose.pdf/page/) number text may contain # sign which will be replaced with number of the page. [Page](../../aspose.pdf/page/) number is placed in the bottom of the page centered horizontally. |
| [AddPageNumber](./addpagenumber/)(System::SharedPtr\<FormattedText\>) | Adds page number to the page. [Page](../../aspose.pdf/page/) number may contain # sign which will be replaced with page number. [Page](../../aspose.pdf/page/) number is placed in the bottom of the page centered horizontally. |
| [AddPageNumber](./addpagenumber/)(System::String, int32_t, float, float, float, float) | Adds page number to the pages of document. |
| [AddPageNumber](./addpagenumber/)(System::String, float, float) | Adds page number at the specified position on the page. |
| [AddPageNumber](./addpagenumber/)(System::SharedPtr\<FormattedText\>, int32_t, float, float, float, float) | Adds page number to the pages of document. |
| [AddPageNumber](./addpagenumber/)(System::SharedPtr\<FormattedText\>, float, float) | Adds page number at the specified position on the page. |
| [AddPageNumber](./addpagenumber/)(System::String, int32_t) | Adds page number to the pages. |
| [AddPageNumber](./addpagenumber/)(System::SharedPtr\<FormattedText\>, int32_t) | Adds page number to the pages. |
| [AddStamp](./addstamp/)(System::SharedPtr\<Stamp\>) | Adds stamp to the file. |
| [Close](./close/)() override | Closes opened files and saves changes. Warning. If input or output streams are specified they are not closed by [Close()](./close/) method. |
| [get_AttachmentName](./get_attachmentname/)() const | Gets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [get_ContentDisposition](./get_contentdisposition/)() const | Gets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline. |
| [get_InputFile](./get_inputfile/)() const | Gets name and path of input file. |
| [get_InputStream](./get_inputstream/)() const | Gets input stream. |
| [get_KeepSecurity](./get_keepsecurity/)() const | Keeps security if true. (This feature will be implemented in next versions). |
| [get_NumberingStyle](./get_numberingstyle/)() const | Gets pabge numbering style. Possible values: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase. |
| [get_OptimizeSize](./get_optimizesize/)() const | Gets optimization flag. Equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false. |
| [get_OutputFile](./get_outputfile/)() const | Gets name and path of output file. |
| [get_OutputStream](./get_outputstream/)() const | Gets output stream. |
| [get_PageHeight](./get_pageheight/)() | Gets height of first page in souorce file. |
| [get_PageNumberRotation](./get_pagenumberrotation/)() | Gets rotation of page number. [Rotation](../../aspose.pdf/rotation/) is in degrees. Default is 0. |
| [get_PageWidth](./get_pagewidth/)() | Gets width of first page in input file. |
| [get_Response](./get_response/)() const | Gets Response object where result of operation will be stored. |
| [get_SaveOptions](./get_saveoptions/)() const | Gets save options when result is stored as HttpResponse. Default value: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [get_StampId](./get_stampid/)() const | [Stamp](../stamp/) ID of next added stamp (incluiding page headers/hooters/page numbers). |
| [get_StartingNumber](./get_startingnumber/)() const | Gets starting number for first page in input file. Next pages will be numbered starting from this value. For example if StartingNumber is set to 100, document pages will have numbers 100, 101, 102... |
| [PdfFileStamp](./pdffilestamp/)(System::String, System::String) | Constructor for [PdfFileStamp](./). |
| [PdfFileStamp](./pdffilestamp/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) | Constructor for [PdfFileStamp](./). |
| [PdfFileStamp](./pdffilestamp/)(System::String, System::String, bool) | Constructor for [PdfFileStamp](./). |
| [PdfFileStamp](./pdffilestamp/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, bool) | Constructor of [PdfFileStamp](./). |
| [PdfFileStamp](./pdffilestamp/)() | Constructor of the [PdfFileStamp](./). Input file and output file may be specified via corresponding properties. |
| [PdfFileStamp](./pdffilestamp/)(System::SharedPtr\<Aspose::Pdf::Document\>) | Initializes new [PdfFileStamp](./) object on base of the *document* . |
| [PdfFileStamp](./pdffilestamp/)(System::SharedPtr\<Aspose::Pdf::Document\>, System::String) | Initializes new [PdfFileStamp](./) object on base of the *document* . |
| [PdfFileStamp](./pdffilestamp/)(System::SharedPtr\<Aspose::Pdf::Document\>, System::SharedPtr\<System::IO::Stream\>) | Initializes new [PdfFileStamp](./) object on base of the *document* . |
| [PdfFileStamp](./pdffilestamp/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::Web::HttpResponse\>) | Creates [PdfFileStamp](./) which will save result into HttpResponse object. |
| [PdfFileStamp](./pdffilestamp/)(System::String, System::SharedPtr\<System::Web::HttpResponse\>) | Creates [PdfFileStamp](./) which will save result into HttpResponse object. |
| [Save](./save/)(System::String) override | Saves result into specified file. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Saves document into specified stream. |
| [set_AttachmentName](./set_attachmentname/)(System::String) | Sets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [set_ContentDisposition](./set_contentdisposition/)(Aspose::Pdf::ContentDisposition) | Sets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline. |
| [set_ConvertTo](./set_convertto/)(PdfFormat) | Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion. |
| [set_InputFile](./set_inputfile/)(System::String) | Sets name and path of input file. |
| [set_InputStream](./set_inputstream/)(System::SharedPtr\<System::IO::Stream\>) | Sets input stream. |
| [set_KeepSecurity](./set_keepsecurity/)(bool) | Keeps security if true. (This feature will be implemented in next versions). |
| [set_NumberingStyle](./set_numberingstyle/)(Aspose::Pdf::NumberingStyle) | Sets pabge numbering style. Possible values: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase. |
| [set_OptimizeSize](./set_optimizesize/)(bool) | Sets optimization flag. Equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false. |
| [set_OutputFile](./set_outputfile/)(System::String) | Sets name and path of output file. |
| [set_OutputStream](./set_outputstream/)(System::SharedPtr\<System::IO::Stream\>) | Sets output stream. |
| [set_PageNumberRotation](./set_pagenumberrotation/)(float) | Sets rotation of page number. [Rotation](../../aspose.pdf/rotation/) is in degrees. Default is 0. |
| [set_Response](./set_response/)(System::SharedPtr\<System::Web::HttpResponse\>) | Sets Response object where result of operation will be stored. |
| [set_SaveOptions](./set_saveoptions/)(System::SharedPtr\<Aspose::Pdf::SaveOptions\>) | Sets save options when result is stored as HttpResponse. Default value: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [set_StampId](./set_stampid/)(int32_t) | [Stamp](../stamp/) ID of next added stamp (incluiding page headers/hooters/page numbers). |
| [set_StartingNumber](./set_startingnumber/)(int32_t) | Sets starting number for first page in input file. Next pages will be numbered starting from this value. For example if StartingNumber is set to 100, document pages will have numbers 100, 101, 102... |
## Fields

| Field | Description |
| --- | --- |
| static [PosBottomLeft](./posbottomleft/) | Bottom left position. |
| static [PosBottomMiddle](./posbottommiddle/) | Bottom middle position. |
| static [PosBottomRight](./posbottomright/) | Bottom right position. |
| static [PosSidesLeft](./possidesleft/) | [Left](../../aspose.pdf/left/) position. |
| static [PosSidesRight](./possidesright/) | [Right](../../aspose.pdf/right/) position. |
| static [PosUpperLeft](./posupperleft/) | Upper let position. |
| static [PosUpperMiddle](./posuppermiddle/) | Upper middle position. |
| static [PosUpperRight](./posupperright/) | [Right](../../aspose.pdf/right/) upper position. |
## See Also

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
