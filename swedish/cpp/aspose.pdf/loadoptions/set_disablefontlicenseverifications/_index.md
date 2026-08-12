---
title: "Aspose::Pdf::LoadOptions::set_DisableFontLicenseVerifications method"
linktitle: "set_DisableFontLicenseVerifications"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LoadOptions::set_DisableFontLicenseVerifications method. Ställer in en flagga för att inaktivera alla licensrestriktioner för alla teckensnitt vid inläsning av filen. När den är true tillåts operationer med ett teckensnitt som är förbjudet av teckensnittets licens, till exempel att bädda in ett teckensnitt i ett PDF‑dokument även om licensreglerna förbjuder inbäddning av detta teckensnitt. Standardvärdet är false i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.pdf/loadoptions/set_disablefontlicenseverifications/
---
## LoadOptions::set_DisableFontLicenseVerifications method


Ställer in flagga för att inaktivera alla licensrestriktioner för alla teckensnitt när filen laddas. När **true**

, tillåter att utföra operationer med ett teckensnitt som är förbjudna enligt teckensnittets licens, till exempel att bädda in ett teckensnitt i ett PDF-dokument även om licensreglerna förbjuder inbäddning för detta teckensnitt. Standardvärdet är **false**

.

```cpp
void Aspose::Pdf::LoadOptions::set_DisableFontLicenseVerifications(bool value)
```

## Anmärkningar


Var försiktig när du använder den här flaggan. När den är satt betyder det att personen som sätter flaggan tar fullt ansvar för eventuella licens‑/lagöverträdelser på sig själv. Så han gör det på egen risk. Det rekommenderas starkt att endast använda flaggan när du är helt säker på att du inte bryter mot upphovsrättslagen.
## Se även

* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
