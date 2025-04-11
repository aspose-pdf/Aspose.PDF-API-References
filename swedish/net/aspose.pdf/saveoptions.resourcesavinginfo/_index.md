---
title: Class SaveOptions.ResourceSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SaveOptionsResourceSavingInfo klass. Denna klass representerar en uppsättning data som är relaterad till sparande av externa resursfiler som sker under konvertering av PDF till något annat format, t.ex. HTML
type: docs
weight: 9940
url: /sv/net/aspose.pdf/saveoptions.resourcesavinginfo/
---
## SaveOptions.ResourceSavingInfo klass

Denna klass representerar en uppsättning data som är relaterad till sparande av externa resursfiler som sker under konvertering av PDF till något annat format (t.ex. HTML)

```csharp
public class ResourceSavingInfo
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Satt av konverteraren. Antagen filnamn som går från konverteraren till koden för den anpassade metoden. Kan användas i anpassad kod för att avgöra hur man ska bearbeta eller var man ska spara den filen |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Satt av konverteraren. Representerar binärt innehåll av den sparade filen. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Denna flagga måste sättas till "true" i anpassad kod om filen av någon anledning bör bearbetas inte med anpassad kod utan med konverterarens egen kod på standard sätt för konverteraren. Så, att den sätts till true betyder att den anpassade koden inte bearbetade den refererade filen och konverteraren måste hantera den själv (i båda avseenden - för att spara någonstans och för namngivning i den refererade filen). |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Satt av konverteraren. Antagen filnamn som går från konverteraren till koden för den anpassade metoden. Kan användas i anpassad kod för att avgöra hur man ska bearbeta eller var man ska spara den filen |

### Se Även

* klass [SaveOptions](../saveoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)