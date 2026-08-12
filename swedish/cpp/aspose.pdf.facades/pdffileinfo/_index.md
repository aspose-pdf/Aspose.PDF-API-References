---
title: "Aspose::Pdf::Facades::PdfFileInfo klass"
linktitle: "PdfFileInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileInfo klass. Representerar en klass för att komma åt metainformation om PDF-dokument i C++."
type: docs
weight: 2100
url: /sv/cpp/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class


Representerar en klass för att komma åt metadata för PDF-dokument.

```cpp
class PdfFileInfo : public Aspose::Pdf::Facades::SaveableFacade
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BindPdf](./bindpdf/)(System::SharedPtr\<Aspose::Pdf::Document\>) override | Initierar fasaden. |
| [ClearInfo](./clearinfo/)() | Rensar all metainformation om PDF-dokument. |
| [Close](./close/)() override | Avinitierar instansen. |
| [get_Author](./get_author/)() | Hämtar författarinformationen för PDF-dokumentet. |
| [get_CreationDate](./get_creationdate/)() | Hämtar skapandedatuminformationen för PDF-dokumentet. |
| [get_Creator](./get_creator/)() | Hämtar skaparinformationen för PDF-dokumentet. |
| [get_HasCollection](./get_hascollection/)() | Returnerar true om den aktuella indatafilen är en 'Portfolio'-fil som innehåller en samling PDF-filer. |
| [get_HasEditPassword](./get_haseditpassword/)() | Returnerar true om ett lösenord krävs för att ändra behörigheter eller dokumentets säkerhetsegenskap. Observera att denna egenskap endast kan läsas om ett giltigt lösenord har angetts i [PdfFileInfo](./)-konstruktorn. Om [PasswordType](../../aspose.pdf/passwordtype/) är Inaccessible (betyder att ett ogiltigt lösenord har angetts) kommer läsning av denna egenskap att misslyckas med [InvalidPasswordException](../../aspose.pdf/invalidpasswordexception/). |
| [get_HasOpenPassword](./get_hasopenpassword/)() | Returnerar true om ett lösenord krävs för att öppna ett lösenordsskyddat PDF-dokument. |
| [get_Header](./get_header/)() const | Hämtar den anpassade informationen för PDF-dokumentet. |
| [get_InputFile](./get_inputfile/)() const | Hämtar indatafilen. |
| [get_InputStream](./get_inputstream/)() const | Hämtar indataströmmen. |
| [get_IsEncrypted](./get_isencrypted/)() | Kontrollerar om PDF-dokumentet är krypterat. |
| [get_IsPdfFile](./get_ispdffile/)() | Kontrollerar om källinmatningen är en giltig PDF-fil. |
| [get_Keywords](./get_keywords/)() | Hämtar nyckelordsinformationen för PDF-dokumentet. |
| [get_ModDate](./get_moddate/)() | Hämtar ModDate-datinformationen för PDF-dokumentet. |
| [get_NumberOfPages](./get_numberofpages/)() | Hämtar antalet sidor i dokumentet. |
| [get_PasswordType](./get_passwordtype/)() | Returnerar typen av lösenord som skickades för att skapa [PdfFileInfo](./)-instansen. Se möjliga värden i [PasswordType](../../aspose.pdf/passwordtype/). Observera att PDF-dokumentet kan öppnas med både användarlösenord (eller öppningslösenord) och ägarlösenord (eller behörighets- / redigeringslösenord). |
| [get_Producer](./get_producer/)() | Hämtar producentinformationen för PDF-dokumentet. |
| [get_Subject](./get_subject/)() | Hämtar ämnesinformationen för PDF-dokumentet. |
| [get_Title](./get_title/)() | Hämtar titelinformationen för PDF-dokumentet. |
| [get_UseStrictValidation](./get_usestrictvalidation/)() const | Använder strikta valideringsregler via egenskapen [IsPdfFile](../). |
| [GetDocumentPrivilege](./getdocumentprivilege/)() | Hämtar privileginställningarna för PDF-dokumentet. |
| [GetMetaInfo](./getmetainfo/)(const System::String\&) | Hämtar anpassad information för PDF-dokumentet med egenskapsnamn. Om ingen egenskap matchar namnet returneras en tom sträng. |
| [GetPageHeight](./getpageheight/)(int32_t) | Hämtar höjden på den angivna sidan. |
| [GetPageRotation](./getpagerotation/)(int32_t) | Hämtar rotationen på den angivna sidan. |
| [GetPageWidth](./getpagewidth/)(int32_t) | Hämtar bredden på den angivna sidan. |
| [GetPageXOffset](./getpagexoffset/)(int32_t) | Hämtar den horisontella förskjutningen för den angivna sidans visningsområde. |
| [GetPageYOffset](./getpageyoffset/)(int32_t) | Hämtar den vertikala förskjutningen för den angivna sidans visningsområde. |
| [GetPdfVersion](./getpdfversion/)() | Hämtar versionsinformationen för PDF-dokumentet. |
| [PdfFileInfo](./pdffileinfo/)() | Initierar en ny instans av klassen [Aspose.Pdf.Facades.PdfFileInfo](./) med standardvärden. |
| [PdfFileInfo](./pdffileinfo/)(const System::SharedPtr\<System::IO::Stream\>\&) | Initierar en ny instans av klassen [Aspose.Pdf.Facades.PdfFileInfo](./). |
| [PdfFileInfo](./pdffileinfo/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Initierar en ny instans av klassen [Aspose.Pdf.Facades.PdfFileInfo](./). |
| [PdfFileInfo](./pdffileinfo/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Initierar en ny instans av klassen [Aspose.Pdf.Facades.PdfFileInfo](./). |
| [PdfFileInfo](./pdffileinfo/)(const System::String\&) | Initierar en ny instans av klassen [Aspose.Pdf.Facades.PdfFileInfo](./). |
| [PdfFileInfo](./pdffileinfo/)(const System::String\&, const System::String\&) | Initierar en ny instans av klassen [Aspose.Pdf.Facades.PdfFileInfo](./). |
| [PdfFileInfo](./pdffileinfo/)(const System::String\&, const System::String\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Initierar en ny instans av klassen [Aspose.Pdf.Facades.PdfFileInfo](./). |
| [PdfFileInfo](./pdffileinfo/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Initierar ett nytt [PdfFileInfo](./)-objekt baserat på *dokumentet*. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Sparar PDF-dokumentet till den angivna filen. |
| [Save](./save/)(System::String) override | Sparar PDF-dokumentet till den angivna filen. |
| [SaveNewInfo](./savenewinfo/)(const System::SharedPtr\<System::IO::Stream\>\&) | Spara uppdaterat PDF-dokument i den angivna strömmen. |
| [SaveNewInfo](./savenewinfo/)(const System::String\&) | Spara uppdaterat PDF-dokument i den angivna filen. |
| [SaveNewInfoWithXmp](./savenewinfowithxmp/)(const System::String\&) | Ändrar de egenskaper som specificerats explicit genom att ställa in filinformation, övriga egenskaper förblir. |
| [set_Author](./set_author/)(const System::String\&) | Ställer in författarinformationen för PDF-dokumentet. |
| [set_CreationDate](./set_creationdate/)(const System::String\&) | Ställer in CreationDate‑informationen för PDF‑dokumentet. |
| [set_Creator](./set_creator/)(const System::String\&) | Ställer in Creator‑informationen för PDF‑dokumentet. |
| [set_Header](./set_header/)(const System::SharedPtr\<System::Collections::Generic::Dictionary\<System::String, System::String\>\>\&) | Ställer in den anpassade informationen för PDF‑dokumentet. |
| [set_InputFile](./set_inputfile/)(const System::String\&) | Ställer in indatafilen. |
| [set_InputStream](./set_inputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställer in indataströmmen. |
| [set_Keywords](./set_keywords/)(const System::String\&) | Ställer in Keywords‑informationen för PDF‑dokumentet. |
| [set_ModDate](./set_moddate/)(const System::String\&) | Ställer in ModDate‑datuminformationen för PDF‑dokumentet. |
| [set_Subject](./set_subject/)(const System::String\&) | Ställer in Subject‑informationen för PDF‑dokumentet. |
| [set_Title](./set_title/)(const System::String\&) | Ställer in Title‑informationen för PDF‑dokumentet. |
| [set_UseStrictValidation](./set_usestrictvalidation/)(bool) | Använder strikta valideringsregler via egenskapen [IsPdfFile](../). |
| [SetMetaInfo](./setmetainfo/)(const System::String\&, const System::String\&) | Ställer in anpassad information för PDF‑dokumentet. |
## Se även

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
