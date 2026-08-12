---
title: "Aspose::Pdf::Facades::PdfFileStamp class"
linktitle: "PdfFileStamp"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileStamp class. Klass för att lägga till stämplar (vattenstämpel eller bakgrund) till PDF‑filer i C++."
type: docs
weight: 2600
url: /sv/cpp/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class


Klass för att lägga till stämplar (vattenstämpel eller bakgrund) till PDF-filer.

```cpp
class PdfFileStamp : public Aspose::Pdf::Facades::SaveableFacade
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddFooter](./addfooter/)(const System::SharedPtr\<FormattedText\>\&, float) | Lägger till sidfot på dokumentets sidor. |
| [AddFooter](./addfooter/)(const System::SharedPtr\<FormattedText\>\&, float, float, float) | Lägger till sidfot på dokumentets sidor. |
| [AddFooter](./addfooter/)(const System::String\&, float) | Lägger till bild som sidfot på dokumentets sidor. |
| [AddFooter](./addfooter/)(const System::String\&, float, float, float) | Lägger till bild som sidfot på sidorna. |
| [AddFooter](./addfooter/)(const System::SharedPtr\<System::IO::Stream\>\&, float) | Lägger till bild som sidfot på sidan. |
| [AddFooter](./addfooter/)(const System::SharedPtr\<System::IO::Stream\>\&, float, float, float) | Lägger till bild som sidfot på sidan. |
| [AddHeader](./addheader/)(const System::SharedPtr\<FormattedText\>\&, float) | Lägger till sidhuvud på sidan. |
| [AddHeader](./addheader/)(const System::SharedPtr\<FormattedText\>\&, float, float, float) | Lägger till sidhuvud på filens sidor. |
| [AddHeader](./addheader/)(const System::String\&, float) | Lägger till bild som sidhuvud på filens sidor. |
| [AddHeader](./addheader/)(const System::String\&, float, float, float) | Lägger till bild som sidhuvud på sidorna. |
| [AddHeader](./addheader/)(const System::SharedPtr\<System::IO::Stream\>\&, float) | Lägger till bild som sidhuvud på sidorna. |
| [AddHeader](./addheader/)(const System::SharedPtr\<System::IO::Stream\>\&, float, float, float) | Lägger till bild högst upp på sidan. |
| [AddPageNumber](./addpagenumber/)(const System::String\&) | Lägg till sidnummer i filen. [Page](../../aspose.pdf/page/) nummertext kan innehålla #‑tecken som kommer att ersättas med sidnumret. [Page](../../aspose.pdf/page/) nummer placeras längst ner på sidan centrerat horisontellt. |
| [AddPageNumber](./addpagenumber/)(const System::SharedPtr\<FormattedText\>\&) | Lägger till sidnummer på sidan. [Page](../../aspose.pdf/page/) nummer kan innehålla #‑tecken som kommer att ersättas med sidnumret. [Page](../../aspose.pdf/page/) nummer placeras längst ner på sidan centrerat horisontellt. |
| [AddPageNumber](./addpagenumber/)(const System::String\&, int32_t, float, float, float, float) | Lägger till sidnummer på dokumentets sidor. |
| [AddPageNumber](./addpagenumber/)(const System::String\&, float, float) | Lägger till sidnummer på den angivna positionen på sidan. |
| [AddPageNumber](./addpagenumber/)(const System::SharedPtr\<FormattedText\>\&, int32_t, float, float, float, float) | Lägger till sidnummer på dokumentets sidor. |
| [AddPageNumber](./addpagenumber/)(const System::SharedPtr\<FormattedText\>\&, float, float) | Lägger till sidnummer på den angivna positionen på sidan. |
| [AddPageNumber](./addpagenumber/)(const System::String\&, int32_t) | Lägger till sidnummer på sidorna. |
| [AddPageNumber](./addpagenumber/)(const System::SharedPtr\<FormattedText\>\&, int32_t) | Lägger till sidnummer på sidorna. |
| [AddStamp](./addstamp/)(const System::SharedPtr\<Stamp\>\&) | Lägger till stämpel i filen. |
| [Close](./close/)() override | Stänger öppna filer och sparar ändringar. Varning. Om in- eller utdataflöden är angivna stängs de inte av [Close()](./close/)‑metoden. |
| [get_AttachmentName](./get_attachmentname/)() const | Hämtar namn på bilagan när resultatet av operationen lagras i HttpResponse‑objekt som bilaga. |
| [get_ContentDisposition](./get_contentdisposition/)() const | Hämtar hur innehållet kommer att lagras när resultatet av operationen lagras i ett HttpResponse‑objekt. Möjligt värde: inline / attachment. Standard: inline. |
| [get_InputFile](./get_inputfile/)() const | Hämtar namn och sökväg för indatafilen. |
| [get_InputStream](./get_inputstream/)() const | Hämtar indataflöde. |
| [get_KeepSecurity](./get_keepsecurity/)() const | Behåller säkerhet om true. (Denna funktion kommer att implementeras i kommande versioner). |
| [get_NumberingStyle](./get_numberingstyle/)() const | Hämtar pabge numreringsstil. Möjliga värden: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase. |
| [get_OptimizeSize](./get_optimizesize/)() const | Hämtar optimeringsflagga. Likadana resursströmmar i den resulterande filen slås ihop till ett PDF‑objekt om denna flagga är satt. Detta minskar filstorleken men kan leda till långsammare körning och högre minneskrav. Standardvärde: false. |
| [get_OutputFile](./get_outputfile/)() const | Hämtar namn och sökväg för utdatafilen. |
| [get_OutputStream](./get_outputstream/)() const | Hämtar utdataflöde. |
| [get_PageHeight](./get_pageheight/)() | Hämtar höjden på den första sidan i souorce‑filen. |
| [get_PageNumberRotation](./get_pagenumberrotation/)() | Hämtar rotation för sidnummer. [Rotation](../../aspose.pdf/rotation/) är i grader. Standard är 0. |
| [get_PageWidth](./get_pagewidth/)() | Hämtar bredden på den första sidan i indatafilen. |
| [get_Response](./get_response/)() const | Hämtar Response-objektet där resultatet av operationen kommer att lagras. |
| [get_SaveOptions](./get_saveoptions/)() const | Hämtar sparalternativ när resultatet lagras som HttpResponse. Standardvärde: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [get_StampId](./get_stampid/)() const | [Stamp](../stamp/) ID för nästa tillagda stämpel (inkluderande sidhuvuden/hooters/sidnummer). |
| [get_StartingNumber](./get_startingnumber/)() const | Hämtar startnummer för den första sidan i indatafilen. Efterföljande sidor numreras med början från detta värde. Till exempel, om StartingNumber är satt till 100, får dokumentsidorna numren 100, 101, 102... |
| [PdfFileStamp](./pdffilestamp/)(const System::String\&, const System::String\&) | Konstruktor för [PdfFileStamp](./). |
| [PdfFileStamp](./pdffilestamp/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Konstruktor för [PdfFileStamp](./). |
| [PdfFileStamp](./pdffilestamp/)(const System::String\&, const System::String\&, bool) | Konstruktor för [PdfFileStamp](./). |
| [PdfFileStamp](./pdffilestamp/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, bool) | Konstruktor för [PdfFileStamp](./). |
| [PdfFileStamp](./pdffilestamp/)() | Konstruktor för [PdfFileStamp](./). Indatafil och utdatafil kan anges via motsvarande egenskaper. |
| [PdfFileStamp](./pdffilestamp/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Initierar ett nytt [PdfFileStamp](./)‑objekt baserat på *dokumentet*. |
| [PdfFileStamp](./pdffilestamp/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Initierar ett nytt [PdfFileStamp](./)‑objekt baserat på *dokumentet*. |
| [PdfFileStamp](./pdffilestamp/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Initierar ett nytt [PdfFileStamp](./)‑objekt baserat på *dokumentet*. |
| [PdfFileStamp](./pdffilestamp/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) | Skapar [PdfFileStamp](./) som sparar resultatet i ett HttpResponse‑objekt. |
| [PdfFileStamp](./pdffilestamp/)(const System::String\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) | Skapar [PdfFileStamp](./) som sparar resultatet i ett HttpResponse‑objekt. |
| [Save](./save/)(System::String) override | Sparar resultatet i angiven fil. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Sparar dokumentet i angiven ström. |
| [set_AttachmentName](./set_attachmentname/)(const System::String\&) | Ställer in namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [set_ContentDisposition](./set_contentdisposition/)(Aspose::Pdf::ContentDisposition) | Ställer in hur innehållet ska lagras när resultatet av operationen lagras i HttpResponse-objektet. Möjligt värde: inline / attachment. Standard: inline. |
| [set_ConvertTo](./set_convertto/)(PdfFormat) | Ställer in PDF-filformat. Resultatfilen sparas i det angivna filformatet. Om denna egenskap inte specificeras sparas filen i standard PDF-format utan konvertering. |
| [set_InputFile](./set_inputfile/)(const System::String\&) | Ställer in namn och sökväg för inmatningsfilen. |
| [set_InputStream](./set_inputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställer in inmatningsström. |
| [set_KeepSecurity](./set_keepsecurity/)(bool) | Behåller säkerhet om true. (Denna funktion kommer att implementeras i kommande versioner). |
| [set_NumberingStyle](./set_numberingstyle/)(Aspose::Pdf::NumberingStyle) | Ställer in pabge‑numreringsstil. Möjliga värden: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase. |
| [set_OptimizeSize](./set_optimizesize/)(bool) | Ställer in optimeringsflagga. Likadana resursströmmar i den resulterande filen slås ihop till ett PDF‑objekt om denna flagga är satt. Detta möjliggör att minska den resulterande filens storlek men kan leda till långsammare körning och större minneskrav. Standardvärde: false. |
| [set_OutputFile](./set_outputfile/)(const System::String\&) | Ställer in namn och sökväg för utdatafilen. |
| [set_OutputStream](./set_outputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställer in utdataström. |
| [set_PageNumberRotation](./set_pagenumberrotation/)(float) | Ställer in rotation för sidnummer. [Rotation](../../aspose.pdf/rotation/) är i grader. Standard är 0. |
| [set_Response](./set_response/)(const System::SharedPtr\<System::Web::HttpResponse\>\&) | Ställer in Response-objektet där resultatet av operationen kommer att lagras. |
| [set_SaveOptions](./set_saveoptions/)(const System::SharedPtr\<Aspose::Pdf::SaveOptions\>\&) | Ställer in sparalternativ när resultatet lagras som HttpResponse. Standardvärde: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [set_StampId](./set_stampid/)(int32_t) | [Stamp](../stamp/) ID för nästa tillagda stämpel (inkluderande sidhuvuden/hooters/sidnummer). |
| [set_StartingNumber](./set_startingnumber/)(int32_t) | Ställer in startnummer för den första sidan i inmatningsfilen. Efterföljande sidor numreras med början från detta värde. Till exempel, om StartingNumber är satt till 100, kommer dokumentsidorna ha numren 100, 101, 102... |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [PosBottomLeft](./posbottomleft/) | Nedre vänstra positionen. |
| static [PosBottomMiddle](./posbottommiddle/) | Nedre mittpositionen. |
| static [PosBottomRight](./posbottomright/) | Nedre högra positionen. |
| static [PosSidesLeft](./possidesleft/) | [Left](../../aspose.pdf/left/) position. |
| static [PosSidesRight](./possidesright/) | [Right](../../aspose.pdf/right/) position. |
| static [PosUpperLeft](./posupperleft/) | Övre vänstra positionen. |
| static [PosUpperMiddle](./posuppermiddle/) | Övre mittpositionen. |
| static [PosUpperRight](./posupperright/) | [Right](../../aspose.pdf/right/) övre position. |
## Se även

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
