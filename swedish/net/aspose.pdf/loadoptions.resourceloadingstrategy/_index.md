---
title: "Delegate LoadOptions.ResourceLoadingStrategy"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Ibland är det nödvändigt att undvika användning av den interna laddaren för externa resurser som bilder eller CSS-filer och tillhandahålla en anpassad metod som hämtar de begärda resurserna från någonstans. Till exempel, vid användning av Aspose.Pdf i molnet är direkt åtkomst till refererade filer omöjlig och viss anpassad kod som placeras i en särskild metod bör användas. Denna delegate definierar signaturen för en sådan anpassad metod."
type: docs
weight: 6300
url: /sv/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy delegate

Ibland är det nödvändigt att undvika användning av den interna laddaren för externa resurser (som bilder eller CSS-filer) och tillhandahålla en anpassad metod som hämtar de begärda resurserna från någonstans. Till exempel, vid användning av Aspose.Pdf i molnet är direkt åtkomst till refererade filer omöjlig, och viss anpassad kod som placeras i en särskild metod bör användas. Denna delegate definierar signaturen för en sådan anpassad metod.

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resourceURI | String | Resurs-URI. |

### Returvärde

ResourceLoadingResult-objekt.

### Se även

* class [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


