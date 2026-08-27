---
title: "Klass SvgSaveOptions.SvgImageSavingInfo"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.SvgSaveOptionsSvgImageSavingInfo-klass. Denna klass representerar en uppsättning data som är relaterade till sparande av externa resursbildfiler under PDF till HTML-konvertering."
type: docs
weight: 10440
url: /sv/net/aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
## SvgSaveOptions.SvgImageSavingInfo class

Denna klass representerar en uppsättning data som är relaterade till sparande av externa resursbildfiler under PDF till HTML-konvertering.

```csharp
public class SvgImageSavingInfo : ResourceSavingInfo
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SvgImageSavingInfo](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/.ctor)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Sätts av konverteraren. Antaget filnamn som går från konverteraren till kod för anpassad metod. Kan användas i anpassad kod för att avgöra hur filen ska bearbetas eller var den ska sparas. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Sätts av konverteraren. Representerar binärt innehåll i den sparade filen. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Denna flagga måste sättas till "true" i anpassad kod om den föreslagna filen av någon anledning ska bearbetas av konverterarens kod istället för av anpassad kod på standardiserat sätt för konverteraren. Så, om flaggan är satt till true betyder det att anpassad kod inte har bearbetat den refererade filen och konverteraren måste hantera den själv (både för att spara den någonstans och för att namnge den i referensfilen). |
| [ImageType](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/imagetype) | representerar typen av sparad bild som refereras i HTML. Sätts av konverteraren och kan användas i anpassad kod för att avgöra vad som ska göras |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Sätts av konverteraren. Antaget filnamn som går från konverteraren till kod för anpassad metod. Kan användas i anpassad kod för att avgöra hur filen ska bearbetas eller var den ska sparas. |

### Se även

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


