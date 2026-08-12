---
title: "Aspose::Pdf::Facades::PdfExtractor class"
linktitle: "PdfExtractor"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfExtractor class. Klass för att extrahera bilder och text från PDF-dokument i C++."
type: docs
weight: 1900
url: /sv/cpp/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class


Klass för att extrahera bilder och text från PDF-dokument.

```cpp
class PdfExtractor : public Aspose::Pdf::Facades::Facade
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Bind inmatnings-PDF-fil. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Binder PDF-dokument från ström. |
| [ExtractAttachment](./extractattachment/)() | Extraherar bilagor från ett [Pdf](../../aspose.pdf/) dokument. |
| [ExtractAttachment](./extractattachment/)(const System::String\&) | Extraherar bilaga till PDF-fil efter bilagans namn. |
| [ExtractImage](./extractimage/)() | Extrahera bilder från PDF-fil. |
| [ExtractText](./extracttext/)() | Extraherar text från ett [Pdf](../../aspose.pdf/) dokument med Unicode-kodning. |
| [ExtractText](./extracttext/)(const System::SharedPtr\<System::Text::Encoding\>\&) | Extraherar text från ett [Pdf](../../aspose.pdf/) dokument med angiven kodning. |
| [get_EndPage](./get_endpage/)() const | Hämtar slutsidnummer i sidintervallet där extraheringsoperationen kommer att utföras. |
| [get_ExtractImageMode](./get_extractimagemode/)() const | Ställer in läget för bildextraktionsprocessen. |
| [get_ExtractTextMode](./get_extracttextmode/)() const | Ställer in läget för resultatet av textextraktion. |
| [get_IsBidi](./get_isbidi/)() | Är sant när texten innehåller hebreiska eller arabiska tecken. Detta fall måste beaktas särskilt eftersom strängfunktioner ändrar sitt beteende och startar textprocessen från höger till vänster (förutom siffror och andra icke‑texttecken). |
| [get_Password](./get_password/)() const | Hämtar lösenordet för indatafilen. |
| [get_Resolution](./get_resolution/)() const | Ställer in eller hämtar upplösningen för extraherade bilder. Standardvärdet är 150. Bilder med högre upplösning är tydligare. Att öka upplösningen ökar dock den tid och det minne som krävs för att extrahera bilder. Vanligtvis räcker det att sätta upplösningen till 150 eller 300 för att få en klar bild. |
| [get_StartPage](./get_startpage/)() const | Hämtar startsidnummer i sidintervallet där extraheringsoperationen kommer att utföras. |
| [get_TextSearchOptions](./get_textsearchoptions/)() const | Hämtar alternativ för textsökning. |
| [GetAttachment](./getattachment/)(const System::String\&) | Sparar bilagan i en fil. |
| [GetAttachment](./getattachment/)() | Sparar alla bilagor till strömmar. |
| [GetAttachmentInfo](./getattachmentinfo/)() | Hämtar listan över bilagor. |
| [GetAttachNames](./getattachnames/)() | Returnerar en lista över bilagor i PDF‑filen. [Note](../../aspose.pdf/note/): ExtractAttachments måste anropas innan denna metod används. |
| [GetNextImage](./getnextimage/)(const System::String\&) | Hämtar nästa bild från PDF‑dokumentet. [Note](../../aspose.pdf/note/): ExtractImage måste anropas innan denna metod används. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Hämtar nästa bild från PDF‑dokumentet med angivet bildformat. [Note](../../aspose.pdf/note/): ExtractImage måste anropas innan denna metod används. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Hämtar nästa bild från PDF‑filen och sparar den i en ström med angivet bildformat. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&) | Hämtar nästa bild från PDF‑filen och sparar den i en ström. |
| [GetNextPageText](./getnextpagetext/)(const System::String\&) | Sparar en sidas text till en fil. |
| [GetNextPageText](./getnextpagetext/)(const System::SharedPtr\<System::IO::Stream\>\&) | Sparar en sidas text till en ström. |
| [GetText](./gettext/)(const System::String\&) | Sparar text till en fil. se även:[ExtractText](./extracttext/) |
| [GetText](./gettext/)(const System::SharedPtr\<System::IO::Stream\>\&) | Sparar text till en ström. se även:[ExtractText](./extracttext/) |
| [GetText](./gettext/)(const System::SharedPtr\<System::IO::Stream\>\&, bool) | Sparar text till en ström. se även:[ExtractText](./extracttext/) |
| [HasNextImage](./hasnextimage/)() | Kontrollerar om fler bilder är tillgängliga i PDF‑dokumentet. [Note](../../aspose.pdf/note/): ExtractImage måste anropas innan denna metod används. |
| [HasNextPageText](./hasnextpagetext/)() | Indikerar om fler texter kan hämtas eller inte. |
| [PdfExtractor](./pdfextractor/)() | Initierar ett nytt [PdfExtractor](./)‑objekt. |
| [PdfExtractor](./pdfextractor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Initierar ett nytt [PdfExtractor](./)‑objekt baserat på *dokumentet*. |
| [set_EndPage](./set_endpage/)(int32_t) | Ställer in slutsidnummer i sidintervallet där extraheringsoperationen kommer att utföras. |
| [set_ExtractImageMode](./set_extractimagemode/)(Aspose::Pdf::ExtractImageMode) | Ställer in läget för bildextraktionsprocessen. |
| [set_ExtractTextMode](./set_extracttextmode/)(int32_t) | Ställer in läget för resultatet av textextraktion. |
| [set_Password](./set_password/)(const System::String\&) | Ställer in lösenordet för inmatningsfilen. |
| [set_Resolution](./set_resolution/)(int32_t) | Ställer in eller hämtar upplösningen för extraherade bilder. Standardvärdet är 150. Bilder med högre upplösning är tydligare. Att öka upplösningen ökar dock den tid och det minne som krävs för att extrahera bilder. Vanligtvis räcker det att sätta upplösningen till 150 eller 300 för att få en klar bild. |
| [set_StartPage](./set_startpage/)(int32_t) | Ställer in startsidon i sidintervallet där extraheringsoperationen kommer att utföras. |
| [set_TextSearchOptions](./set_textsearchoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Ställer in alternativ för textsökning. |
## Se även

* Class [Facade](../facade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
