---
title: Class SvgSaveOptions.SvgImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgSaveOptionsSvgImageSavingInfo klass. Denna klass representerar en uppsättning data som är relaterade till sparande av externa resursbildfiler under PDF till HTML-konvertering
type: docs
weight: 10260
url: /sv/net/aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
## SvgSaveOptions.SvgImageSavingInfo klass

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
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Satt av konverteraren. Antagen filnamn som går från konverteraren till koden för den anpassade metoden. Kan användas i anpassad kod för att avgöra hur man ska bearbeta eller var man ska spara den filen. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Satt av konverteraren. Representerar binärt innehåll av den sparade filen. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Denna flagga måste sättas till "true" i anpassad kod om filen av någon anledning bör bearbetas inte med anpassad kod utan med konverterarens egen kod på standard sätt för konverteraren. Så, att den sätts till true betyder att den anpassade koden inte bearbetade den refererade filen och konverteraren måste hantera den själv (i båda avseenden - för att spara någonstans och för namngivning i den refererade filen). |
| [ImageType](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/imagetype) | Representerar typen av den sparade bilden som refereras i HTML. Satt av konverteraren och kan användas i anpassad kod för att avgöra vad som ska göras. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Satt av konverteraren. Antagen filnamn som går från konverteraren till koden för den anpassade metoden. Kan användas i anpassad kod för att avgöra hur man ska bearbeta eller var man ska spara den filen. |

### Se Även

* klass [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* klass [SvgSaveOptions](../svgsaveoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)