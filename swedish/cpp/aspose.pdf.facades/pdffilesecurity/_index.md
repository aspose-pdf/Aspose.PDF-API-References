---
title: "Aspose::Pdf::Facades::PdfFileSecurity class"
linktitle: "PdfFileSecurity"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileSecurity-klass. Representerar kryptering eller dekryptering av en Pdf-fil med ägare- eller användarlösenord, ändring av säkerhetsinställningarna och lösenordet i C++."
type: docs
weight: 2400
url: /sv/cpp/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class


Representerar kryptering eller dekryptering av en [Pdf](../../aspose.pdf/) fil med ägare- eller användarlösenord, ändring av säkerhetsinställningarna och lösenordet.

```cpp
class PdfFileSecurity : public Aspose::Pdf::Facades::SaveableFacade
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Initierar fasaden. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Initierar fasaden. |
| [ChangePassword](./changepassword/)(const System::String\&, const System::String\&, const System::String\&) | Ändrar användarlösenordet och ägarlösenordet med ägarlösenordet, behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar ett undantag om processen misslyckas. |
| [ChangePassword](./changepassword/)(const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize) | Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av [Pdf](../../aspose.pdf/) dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar ett undantag om processen misslyckas. |
| [ChangePassword](./changepassword/)(const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize, Algorithm) | Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av [Pdf](../../aspose.pdf/) dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Det finns 6 möjliga kombinationer av [KeySize](../keysize/) och [Algorithm](../algorithm/) värden. Dock är ([KeySize.x40](../keysize/), [Algorithm.AES](../algorithm/)) och ([KeySize.x256](../keysize/), [Algorithm.RC4](../algorithm/)) ogiltiga och motsvarande undantag kommer att kastas om verktyget stöter på denna kombination. Kastar ett undantag om processen misslyckas. |
| [Close](./close/)() override | Stänger fasaden. |
| [get_AllowExceptions](./get_allowexceptions/)() | Om detta värde är satt till true kastas ett undantag vid operationens misslyckande. Annars returnerar metoden false vid fel och det senaste undantaget kan kontrolleras med egenskapen LastException. |
| [get_LastException](./get_lastexception/)() const | Returnerar undantaget som kastades av den senaste operationen. |
| [MfDecryptFile](./mfdecryptfile/)(const System::String\&) | Dekrypterar ett krypterat [Pdf](../../aspose.pdf/) dokument med ägarlösenord. Om dokumentet inte har ägarlösenord tillåts användarlösenord. Kastar ett undantag om processen misslyckas. |
| [MfEncryptFile](./mfencryptfile/)(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize) | Krypterar [Pdf](../../aspose.pdf/) fil med användarlösenord och ägarlösenord och sätter dokumentets åtkomsträttigheter. Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt. Kastar ett undantag om processen misslyckas. |
| [MfEncryptFile](./mfencryptfile/)(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize, Algorithm) | Krypterar [Pdf](../../aspose.pdf/) fil med användarlösenord och ägarlösenord och sätter dokumentets åtkomsträttigheter. Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt. Det finns 6 möjliga kombinationer av [KeySize](../keysize/) och [Algorithm](../algorithm/) värden. Dock är ([KeySize.x40](../keysize/), [Algorithm.AES](../algorithm/)) och ([KeySize.x256](../keysize/), [Algorithm.RC4](../algorithm/)) ogiltiga och motsvarande undantag kommer att kastas om verktyget stöter på denna kombination. Kastar ett undantag om processen misslyckas. |
| [PdfFileSecurity](./pdffilesecurity/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Initierar objektet av [PdfFileSecurity](./) med in- och utström. |
| [PdfFileSecurity](./pdffilesecurity/)(const System::String\&, const System::String\&) | Initierar objektet av [PdfFileSecurity](./) med in- och utfil. |
| [PdfFileSecurity](./pdffilesecurity/)() | Initierar objektet av [PdfFileSecurity](./). |
| [PdfFileSecurity](./pdffilesecurity/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Initierar ett nytt [PdfFileSecurity](./) objekt baserat på *dokumentet*. |
| [PdfFileSecurity](./pdffilesecurity/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Initierar ett nytt [PdfFileSecurity](./) objekt baserat på *dokumentet*. |
| [PdfFileSecurity](./pdffilesecurity/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Initierar ett nytt [PdfFileSecurity](./) objekt baserat på *dokumentet*. |
| [set_AllowExceptions](./set_allowexceptions/)(bool) | Om detta värde är satt till true kastas ett undantag vid operationens misslyckande. Annars returnerar metoden false vid fel och det senaste undantaget kan kontrolleras med egenskapen LastException. |
| [set_InputFile](./set_inputfile/)(const System::String\&) | Ställer in indatafilen. |
| [set_InputStream](./set_inputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställer in indataströmmen. |
| [set_OutputFile](./set_outputfile/)(const System::String\&) | Ställer in utfilen. |
| [set_OutputStream](./set_outputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställer in utströmmen. |
| [SetPrivilege](./setprivilege/)(const System::SharedPtr\<DocumentPrivilege\>\&) | Ställer in [Pdf](../../aspose.pdf/) filens säkerhet med tomma användar-/ägarlösenord. Ägarlösenordet kommer att läggas till med en slumpmässig sträng. Kastar ett undantag om processen misslyckas. |
| [SetPrivilege](./setprivilege/)(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&) | Ställer in [Pdf](../../aspose.pdf/) filens säkerhet med originallösenordet. Kastar ett undantag om processen misslyckas. |
| [TryChangePassword](./trychangepassword/)(const System::String\&, const System::String\&, const System::String\&) | Ändrar användarlösenordet och ägarlösenordet med ägarlösenordet, behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar inte ett undantag om processen misslyckas. |
| [TryChangePassword](./trychangepassword/)(const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize) | Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av [Pdf](../../aspose.pdf/) dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar inte ett undantag om processen misslyckas. |
| [TryChangePassword](./trychangepassword/)(const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize, Algorithm) | Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av [Pdf](../../aspose.pdf/) dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Det finns 6 möjliga kombinationer av [KeySize](../keysize/) och [Algorithm](../algorithm/) värden. Dock är ([KeySize.x40](../keysize/), [Algorithm.AES](../algorithm/)) och ([KeySize.x256](../keysize/), [Algorithm.RC4](../algorithm/)) ogiltiga och motsvarande undantag kommer att kastas om verktyget stöter på denna kombination. Kastar inte ett undantag om processen misslyckas. |
| [TryDecryptFile](./trydecryptfile/)(const System::String\&) | Dekrypterar ett krypterat [Pdf](../../aspose.pdf/) dokument med ägarlösenord. Om dokumentet saknar ägarlösenord tillåts användning av användarlösenord. Kastar inte ett undantag om processen misslyckas. |
| [TryEncryptFile](./tryencryptfile/)(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize) | Krypterar [Pdf](../../aspose.pdf/) fil med användarlösenord och ägarlösenord och sätter dokumentets åtkomsträttigheter. Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt. Kastar inte ett undantag om processen misslyckas. |
| [TrySetPrivilege](./trysetprivilege/)(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&) | Ställer in [Pdf](../../aspose.pdf/) filens säkerhet med originallösenordet. Kastar inte ett undantag om processen misslyckas. |
## Se även

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
