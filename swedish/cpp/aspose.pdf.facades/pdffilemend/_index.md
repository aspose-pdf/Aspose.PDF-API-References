---
title: "Aspose::Pdf::Facades::PdfFileMend klass"
linktitle: "PdfFileMend"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileMend klass. Representerar en klass för att lägga till texter och bilder på sidorna i ett befintligt PDF-dokument i C++."
type: docs
weight: 2200
url: /sv/cpp/aspose.pdf.facades/pdffilemend/
---
## PdfFileMend class


Representerar en klass för att lägga till text och bilder på sidorna i ett befintligt PDF-dokument.

```cpp
class PdfFileMend : public Aspose::Pdf::Facades::SaveableFacade
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, float, float, float, float) | Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater. |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) | Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater. |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float) | Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater. |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) | Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater. |
| [AddImage](./addimage/)(const System::String\&, int32_t, float, float, float, float) | Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater. |
| [AddImage](./addimage/)(const System::String\&, int32_t, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) | Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater. |
| [AddImage](./addimage/)(const System::String\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float) | Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater. |
| [AddImage](./addimage/)(const System::String\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) | Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater. |
| [AddText](./addtext/)(const System::SharedPtr\<FormattedText\>\&, int32_t, float, float) | Ej implementerad. |
| [AddText](./addtext/)(const System::SharedPtr\<FormattedText\>\&, int32_t, float, float, float, float) | Ej implementerad. |
| [AddText](./addtext/)(const System::SharedPtr\<FormattedText\>\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float) | Ej implementerad. |
| [Close](./close/)() override | Stänger [PdfFileMend](./) objektet. |
| [get_InputFile](./get_inputfile/)() const | Ställer in indatafilen. |
| [get_InputStream](./get_inputstream/)() const | Ställer in indataströmmen. |
| [get_OutputFile](./get_outputfile/)() const | Ställer in utfilen. |
| [get_OutputStream](./get_outputstream/)() const | Ställer in utströmmen. |
| [get_TextPositioningMode](./get_textpositioningmode/)() const | Ställer in eller hämtar textpositioneringsstrategi. [PositioningMode](../positioningmode/) Standardläge är Legacy. |
| [get_WrapMode](./get_wrapmode/)() const | Ställer in eller hämtar radbrytningsalgoritm. Se [WordWrapMode](../wordwrapmode/) och IsWordWrap. |
| [PdfFileMend](./pdffilemend/)() | Konstruktor. |
| [PdfFileMend](./pdffilemend/)(const System::String\&, const System::String\&) | Konstruktor. |
| [PdfFileMend](./pdffilemend/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Konstruktor. |
| [PdfFileMend](./pdffilemend/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Initierar ett nytt [PdfFileMend](./) objekt baserat på *document*. |
| [PdfFileMend](./pdffilemend/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Initierar ett nytt [PdfFileMend](./) objekt baserat på *document*. |
| [PdfFileMend](./pdffilemend/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Initierar ett nytt [PdfFileMend](./) objekt baserat på *document*. |
| [Save](./save/)(System::String) override | Sparar PDF-dokumentet till den angivna filen. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Sparar PDF-dokumentet till den angivna strömmen. |
| [set_InputFile](./set_inputfile/)(const System::String\&) | Ställer in indatafilen. |
| [set_InputStream](./set_inputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställer in indataströmmen. |
| [set_IsWordWrap](./set_iswordwrap/)(bool) | Ställer in ett booleskt värde som indikerar radbrytning i AddText-metoder. Om värdet är true kommer texten i [FormattedText](../formattedtext/) att radbrytas. Som standard är värdet false. |
| [set_OutputFile](./set_outputfile/)(const System::String\&) | Ställer in utfilen. |
| [set_OutputStream](./set_outputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställer in utströmmen. |
| [set_TextPositioningMode](./set_textpositioningmode/)(PositioningMode) | Ställer in eller hämtar textpositioneringsstrategi. [PositioningMode](../positioningmode/) Standardläge är Legacy. |
| [set_WrapMode](./set_wrapmode/)(WordWrapMode) | Ställer in eller hämtar radbrytningsalgoritm. Se [WordWrapMode](../wordwrapmode/) och IsWordWrap. |
## Se även

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
