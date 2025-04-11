---
title: LoadOptions.DisableFontLicenseVerifications
second_title: Aspose.PDF for .NET API Reference
description: LoadOptions-egenskap. Hämtar eller ställer in en flagga för att inaktivera eventuella licensbegränsningar för alla typsnitt när filen laddas. När den är sann tillåter den att utföra operationer med typsnitt som är förbjudna av en licens för detta typsnitt, till exempel tillåter den att bädda in ett typsnitt i ett PDF-dokument även om licensreglerna inaktiverar inbäddning för detta typsnitt. Som standard falsk
type: docs
weight: 10
url: /sv/net/aspose.pdf/loadoptions/disablefontlicenseverifications/
---
## LoadOptions.DisableFontLicenseVerifications-egenskap

Hämtar eller ställer in en flagga för att inaktivera eventuella licensbegränsningar för alla typsnitt när filen laddas. När `true`, tillåter den att utföra operationer med typsnitt som är förbjudna av en licens för detta typsnitt, till exempel tillåter den att bädda in ett typsnitt i ett PDF-dokument även om licensreglerna inaktiverar inbäddning för detta typsnitt. Som standard `false`.

```csharp
public bool DisableFontLicenseVerifications { get; set; }
```

## Kommentarer

Var försiktig när du använder denna flagga. När den är inställd betyder det att personen som ställer in denna flagga tar allt ansvar för eventuella licens-/lagöverträdelser på sig själv. Så han tar det på egen risk. Det rekommenderas starkt att använda denna flagga endast när du är helt säker på att du inte bryter mot upphovsrättslagen.

### Se Även

* klass [LoadOptions](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)