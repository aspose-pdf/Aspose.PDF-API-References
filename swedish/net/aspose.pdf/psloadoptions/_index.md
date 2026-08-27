---
title: "Klass PsLoadOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.PsLoadOptions‑klass. Representerar alternativ för inläsning/import av .mht‑fil till pdf‑dokument."
type: docs
weight: 9880
url: /sv/net/aspose.pdf/psloadoptions/
---
## PsLoadOptions class

Representerar alternativ för laddning/import av .mht-fil till pdf-dokument.

```csharp
public sealed class PsLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PsLoadOptions](psloadoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ConvertFontsToTTF](../../aspose.pdf/psloadoptions/convertfontstottf/) { get; set; } | Anger om icke‑TrueType‑typsnitt ska sparas som TTF. Det minskar avsevärt volymen på det resulterande dokumentet vid PS‑till‑PDF‑konvertering och ökar hastigheten för konvertering av PS‑filer med stor mängd text i icke‑TrueType‑typsnitt till vilket output‑format som helst. Däremot uppstår en liten vertikal förskjutning av texten när en PostSctipt‑fil konverteras till bild. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller anger en flagga för att inaktivera alla licensrestriktioner för alla teckensnitt vid inläsning av filen. När `true` tillåts operationer med ett teckensnitt som är förbjudet av dess licens, till exempel att bädda in ett teckensnitt i ett PDF‑dokument även om licensreglerna förbjuder inbäddning av detta teckensnitt. Standardvärdet är `false`. |
| [FontsFolders](../../aspose.pdf/psloadoptions/fontsfolders/) { get; set; } | Hämtar eller anger sökvägar till teckensnittsmappar. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformat som [`LoadOptions`](../loadoptions/) beskriver. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, varvid Load‑operationen ska avbrytas. |

### Se även

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


