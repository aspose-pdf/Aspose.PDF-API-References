---
title: Aspose::Pdf::Facades::PdfFileMend class
linktitle: PdfFileMend
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileMend class. Represents a class for adding texts and images on the pages of existing PDF document in C++.'
type: docs
weight: 2200
url: /cpp/aspose.pdf.facades/pdffilemend/
---
## PdfFileMend class


Represents a class for adding texts and images on the pages of existing PDF document.

```cpp
class PdfFileMend : public Aspose::Pdf::Facades::SaveableFacade
```

## Methods

| Method | Description |
| --- | --- |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, float, float, float, float) | Adds image to the specified page of PDF document at specified coordinates. |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) | Adds image to the specified page of PDF document at specified coordinates. |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float) | Adds image to the specified pages of PDF document at specified coordinates. |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) | Adds image to the specified pages of PDF document at specified coordinates. |
| [AddImage](./addimage/)(const System::String\&, int32_t, float, float, float, float) | Adds image to the specified page of PDF document at specified coordinates. |
| [AddImage](./addimage/)(const System::String\&, int32_t, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) | Adds image to the specified page of PDF document at specified coordinates. |
| [AddImage](./addimage/)(const System::String\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float) | Adds image to the specified pages of PDF document at specified coordinates. |
| [AddImage](./addimage/)(const System::String\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) | Adds image to the specified pages of PDF document at specified coordinates. |
| [AddText](./addtext/)(const System::SharedPtr\<FormattedText\>\&, int32_t, float, float) | Not implemented. |
| [AddText](./addtext/)(const System::SharedPtr\<FormattedText\>\&, int32_t, float, float, float, float) | Not implemented. |
| [AddText](./addtext/)(const System::SharedPtr\<FormattedText\>\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float) | Not implemented. |
| [Close](./close/)() override | Closes [PdfFileMend](./) object. |
| [get_InputFile](./get_inputfile/)() const | Sets the input file. |
| [get_InputStream](./get_inputstream/)() const | Sets the input stream. |
| [get_OutputFile](./get_outputfile/)() const | Sets the output file. |
| [get_OutputStream](./get_outputstream/)() const | Sets the output stream. |
| [get_TextPositioningMode](./get_textpositioningmode/)() const | Sets or gets text positioning strategy. [PositioningMode](../positioningmode/) Default mode is Legacy. |
| [get_WrapMode](./get_wrapmode/)() const | Sets or gets word wrapping algorithm. See [WordWrapMode](../wordwrapmode/) and IsWordWrap. |
| [PdfFileMend](./pdffilemend/)() | Constructor. |
| [PdfFileMend](./pdffilemend/)(const System::String\&, const System::String\&) | Constructor. |
| [PdfFileMend](./pdffilemend/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Constructor. |
| [PdfFileMend](./pdffilemend/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Initializes new [PdfFileMend](./) object on base of the *document* . |
| [PdfFileMend](./pdffilemend/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Initializes new [PdfFileMend](./) object on base of the *document* . |
| [PdfFileMend](./pdffilemend/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Initializes new [PdfFileMend](./) object on base of the *document* . |
| [Save](./save/)(System::String) override | Saves the PDF document to the specified file. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Saves the PDF document to the specified stream. |
| [set_InputFile](./set_inputfile/)(const System::String\&) | Sets the input file. |
| [set_InputStream](./set_inputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Sets the input stream. |
| [set_IsWordWrap](./set_iswordwrap/)(bool) | Sets a bool value that indicates word wrap in AddText methods. If the value is true, the text in [FormattedText](../formattedtext/) will word wrap. By defalt, the value is false. |
| [set_OutputFile](./set_outputfile/)(const System::String\&) | Sets the output file. |
| [set_OutputStream](./set_outputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Sets the output stream. |
| [set_TextPositioningMode](./set_textpositioningmode/)(PositioningMode) | Sets or gets text positioning strategy. [PositioningMode](../positioningmode/) Default mode is Legacy. |
| [set_WrapMode](./set_wrapmode/)(WordWrapMode) | Sets or gets word wrapping algorithm. See [WordWrapMode](../wordwrapmode/) and IsWordWrap. |
## See Also

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
