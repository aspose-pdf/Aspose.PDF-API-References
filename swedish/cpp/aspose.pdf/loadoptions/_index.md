---
title: "Aspose::Pdf::LoadOptions class"
linktitle: "LoadOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LoadOptions class. LoadOptions-typen innehåller abstraktionsnivån för enskilda laddningsalternativ i C++."
type: docs
weight: 10500
url: /sv/cpp/aspose.pdf/loadoptions/
---
## LoadOptions class


[LoadOptions](./) type holds level of abstraction on individual load options.

```cpp
class LoadOptions : public virtual System::Object
```

## Nested classes

* Class [ResourceLoadingResult](./resourceloadingresult/)
## Enums

| Enum | Beskrivning |
| --- | --- |
| [MarginsAreaUsageModes](./marginsareausagemodes/) | Representerar läge för användning av marginalområdet under konvertering (som HTML, EPUB etc), definierar behandlingen av instruktioner från importerat format relaterade till användning av marginaler. |
| [PageSizeAdjustmentModes](./pagesizeadjustmentmodes/) | OBS! Funktionen har implementerats men har ännu inte placerats i det offentliga API:et på grund av blockerande problem i OSHARED-lagret som upptäcktes för exempel-dokumentet. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [get_DisableFontLicenseVerifications](./get_disablefontlicenseverifications/)() const | Hämtar flagga för att inaktivera alla licensrestriktioner för alla teckensnitt när filen laddas. När **true** |

, tillåter att utföra operationer med ett teckensnitt som är förbjudna enligt teckensnittets licens, till exempel att bädda in ett teckensnitt i ett PDF-dokument även om licensreglerna förbjuder inbäddning för detta teckensnitt. Standardvärdet är **false**

. |
| [get_LoadFormat](./get_loadformat/)() const | Representerar filformat som [LoadOptions](./) beskriver. |
| [get_WarningHandler](./get_warninghandler/)() const | Återanrop för att hantera eventuella varningar som genereras. WarningHandler returnerar [ReturnAction](../returnaction/) enum‑element som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, i vilket fall Load‑operationen ska avbrytas. |
| [LoadOptions](./loadoptions/)() |  |
|  | [set_DisableFontLicenseVerifications](./set_disablefontlicenseverifications/)(bool) | Ställer in flagga för att inaktivera alla licensrestriktioner för alla teckensnitt när filen laddas. När **true** |

, tillåter att utföra operationer med ett teckensnitt som är förbjudna enligt teckensnittets licens, till exempel att bädda in ett teckensnitt i ett PDF-dokument även om licensreglerna förbjuder inbäddning för detta teckensnitt. Standardvärdet är **false**

. |
| [set_WarningHandler](./set_warninghandler/)(const System::SharedPtr\<IWarningCallback\>\&) | Återanrop för att hantera eventuella varningar som genereras. WarningHandler returnerar [ReturnAction](../returnaction/) enum‑element som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, i vilket fall Load‑operationen ska avbrytas. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [ResourceLoadingStrategy](./resourceloadingstrategy/) | Ibland är det nödvändigt att undvika användning av den interna laddaren för externa resurser (som bilder eller CSS-filer) och tillhandahålla en anpassad metod som hämtar de begärda resurserna från någonstans. Till exempel, vid användning av [Aspose.Pdf](../) i molnet är direkt åtkomst till refererade filer omöjlig, och viss anpassad kod som placeras i en särskild metod bör användas. Denna delegat definierar signaturen för en sådan anpassad metod. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
