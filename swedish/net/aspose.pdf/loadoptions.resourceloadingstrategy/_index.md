---
title: LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF för .NET API Referens
description: Ibland är det nödvändigt att undvika användning av intern laddare av externa resurser som bilder eller CSSer och tillhandahålla anpassad metod som kommer att få begärda resurser någonstans ifrån. Till exempel under användning av Aspose.Pdf i molnet direkt tillgång till refererade filer omöjlig och viss anpassad kod som lagts in i special -metoden bör användas. Denna delegat definierar signaturen för en sådan anpassad metod.
type: docs
weight: 3990
url: /sv/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy delegate

Ibland är det nödvändigt att undvika användning av intern laddare av externa resurser (som bilder eller CSS:er) och tillhandahålla anpassad metod, som kommer att få begärda resurser någonstans ifrån. Till exempel under användning av Aspose.Pdf i molnet direkt tillgång till refererade filer omöjlig, och viss anpassad kod som lagts in i special -metoden bör användas. Denna delegat definierar signaturen för en sådan anpassad metod.

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resourceURI | String | Resurs-URI. |

### Returvärde

ResourceLoadingResult-objekt.

### Se även

* class [ResourceLoadingResult](../loadoptions.resourceloadingresult)
* class [LoadOptions](../loadoptions)
* namnutrymme [Aspose.Pdf](../../aspose.pdf)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->