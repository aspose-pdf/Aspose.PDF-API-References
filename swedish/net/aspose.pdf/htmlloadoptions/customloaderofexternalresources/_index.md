---
title: HtmlLoadOptions.CustomLoaderOfExternalResources
second_title: Aspose.PDF for .NET API Reference
description: HtmlLoadOptions-fält. Ibland är det nödvändigt att undvika användning av intern laddare för externa resurser som bilder eller CSS och tillhandahålla en anpassad metod som hämtar begärda resurser från någonstans. Till exempel, under användning av Aspose.PDF i molnet är direkt åtkomst till refererade filer omöjlig i sådana fall bör viss anpassad kod sättas in i en speciell metod, och en delegerad som refererar till den metoden bör tilldelas detta attribut.
type: docs
weight: 100
url: /sv/net/aspose.pdf/htmlloadoptions/customloaderofexternalresources/
---
## HtmlLoadOptions.CustomLoaderOfExternalResources-fält

Ibland är det nödvändigt att undvika användning av intern laddare för externa resurser (som bilder eller CSS) och tillhandahålla en anpassad metod som hämtar begärda resurser från någonstans. Till exempel, under användning av Aspose.PDF i molnet är direkt åtkomst till refererade filer omöjlig: i sådana fall bör viss anpassad kod sättas in i en speciell metod, och en delegerad som refererar till den metoden bör tilldelas detta attribut.

```csharp
public ResourceLoadingStrategy CustomLoaderOfExternalResources;
```

### Se Även

* delegerad [ResourceLoadingStrategy](../../loadoptions.resourceloadingstrategy/)
* klass [HtmlLoadOptions](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)