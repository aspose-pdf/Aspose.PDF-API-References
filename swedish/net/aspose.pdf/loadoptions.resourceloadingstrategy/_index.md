---
title: Delegate LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Ibland är det nödvändigt att undvika användning av intern laddare för externa resurser som bilder eller CSS och tillhandahålla en anpassad metod som hämtar begärda resurser från någonstans. Till exempel, under användning av Aspose.Pdf i molnet är direkt åtkomst till refererade filer omöjlig, och viss anpassad kod som placeras i en speciell metod bör användas. Denna delegering definierar signaturen för en sådan anpassad metod.
type: docs
weight: 6160
url: /sv/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy-delegat

Ibland är det nödvändigt att undvika användning av intern laddare för externa resurser (som bilder eller CSS) och tillhandahålla en anpassad metod som hämtar begärda resurser från någonstans. Till exempel, under användning av Aspose.Pdf i molnet är direkt åtkomst till refererade filer omöjlig, och viss anpassad kod som placeras i en speciell metod bör användas. Denna delegering definierar signaturen för en sådan anpassad metod.

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resourceURI | Sträng | Resurs URI. |

### Returvärde

ResourceLoadingResult-objekt.

### Se Även

* klass [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* klass [LoadOptions](../loadoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* samling [Aspose.PDF](../../)