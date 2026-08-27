---
title: "HtmlLoadOptions.CustomLoaderOfExternalResources"
second_title: "Aspose.PDF för .NET API‑referens"
description: "HtmlLoadOptions fält. Ibland är det nödvändigt att undvika användning av den interna laddaren för externa resurser såsom bilder eller CSS-filer och tillhandahålla en anpassad metod som hämtar de begärda resurserna från någonstans. Till exempel, vid användning av Aspose.PDF i molnet är direkt åtkomst till refererade filer omöjlig; i sådant fall bör någon anpassad kod placeras i en särskild metod som används, och en delegat som refererar till den metoden ska tilldelas detta attribut."
type: docs
weight: 100
url: /sv/net/aspose.pdf/htmlloadoptions/customloaderofexternalresources/
---
## HtmlLoadOptions.CustomLoaderOfExternalResources field

Ibland är det nödvändigt att undvika användning av den interna laddaren för externa resurser (som bilder eller CSS-filer) och tillhandahålla en anpassad metod som hämtar de begärda resurserna från någonstans. Till exempel, vid användning av Aspose.PDF i molnet är direkt åtkomst till refererade filer omöjlig: i sådant fall bör viss anpassad kod som placeras i en speciell metod användas, och en delegat som refererar till den metoden bör tilldelas detta attribut.

```csharp
public ResourceLoadingStrategy CustomLoaderOfExternalResources;
```

### Se även

* delegate [ResourceLoadingStrategy](../../loadoptions.resourceloadingstrategy/)
* class [HtmlLoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


