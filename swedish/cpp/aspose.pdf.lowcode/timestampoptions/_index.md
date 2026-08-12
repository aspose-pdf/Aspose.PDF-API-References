---
title: "Aspose::Pdf::LowCode::TimestampOptions klass"
linktitle: "TimestampOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LowCode::TimestampOptions klass. Alternativ för Timestamp Low‑Code plugin i C++."
type: docs
weight: 9100
url: /sv/cpp/aspose.pdf.lowcode/timestampoptions/
---
## TimestampOptions class


Alternativ för [Timestamp](../timestamp/) Low‑Code‑plugin.

```cpp
class TimestampOptions : public Aspose::Pdf::LowCode::PdfConverterOptions
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_BasicAuthCredentials](./get_basicauthcredentials/)() const | Hämtar de grundläggande autentiseringsuppgifterna, Användarnamn och lösenord kombineras till en sträng "username:password". |
| [get_DigestHashAlgorithm](./get_digesthashalgorithm/)() const | Digest‑hashalgoritm att använda för tidsstämpeln. Standard är Sha256. |
| [get_OperationName](./get_operationname/)() override | Returnerar operationens namn. |
| [get_PageNumber](./get_pagenumber/)() const | [Page](../../aspose.pdf/page/) nummer på vilket den tidsstämplade signaturen kommer att tillämpas. |
| [get_Rectangle](./get_rectangle/)() const | [Rectangle](../../aspose.pdf/rectangle/) som definierar annoteringsområdet (ignoreras när Visible är falskt). |
| [get_ServerUrl](./get_serverurl/)() const | URL för tidsstämplingsservern. |
| [get_SigContact](./get_sigcontact/)() const | Kontaktinformation för signaturen. |
| [get_SigLocation](./get_siglocation/)() const | Plats för signaturen. |
| [get_SigReason](./get_sigreason/)() const | Orsak till signaturen. |
| [get_Visible](./get_visible/)() const | Synlighetsflagga – falskt för en ren tidsstämpel (ingen synlig annotering). |
| [set_BasicAuthCredentials](./set_basicauthcredentials/)(const System::String\&) | Ställer in de grundläggande autentiseringsuppgifterna, Användarnamn och lösenord kombineras till en sträng "username:password". |
| [set_DigestHashAlgorithm](./set_digesthashalgorithm/)(Aspose::Pdf::DigestHashAlgorithm) | Digest‑hashalgoritm att använda för tidsstämpeln. Standard är Sha256. |
| [set_PageNumber](./set_pagenumber/)(int32_t) | [Page](../../aspose.pdf/page/) nummer på vilket den tidsstämplade signaturen kommer att tillämpas. |
| [set_Rectangle](./set_rectangle/)(System::Drawing::Rectangle) | [Rectangle](../../aspose.pdf/rectangle/) som definierar annoteringsområdet (ignoreras när Visible är falskt). |
| [set_ServerUrl](./set_serverurl/)(const System::String\&) | URL för tidsstämplingsservern. |
| [set_SigContact](./set_sigcontact/)(const System::String\&) | Kontaktinformation för signaturen. |
| [set_SigLocation](./set_siglocation/)(const System::String\&) | Plats för signaturen. |
| [set_SigReason](./set_sigreason/)(const System::String\&) | Orsak till signaturen. |
| [set_Visible](./set_visible/)(bool) | Synlighetsflagga – falskt för en ren tidsstämpel (ingen synlig annotering). |
| [TimestampOptions](./timestampoptions/)(const System::String\&, const System::String\&) | Skapar en ny instans med en PFX‑filväg och lösenord. |
| [TimestampOptions](./timestampoptions/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Skapar en ny instans med en PFX‑ström och lösenord. |
| [TimestampOptions](./timestampoptions/)() | Skapar en ny instans med standardvärden. Används för att signera TSA med en PFX‑fil. |
## Se även

* Class [PdfConverterOptions](../pdfconverteroptions/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
