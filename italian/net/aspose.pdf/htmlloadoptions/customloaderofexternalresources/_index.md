---
title: HtmlLoadOptions.CustomLoaderOfExternalResources
second_title: Aspose.PDF for .NET API Reference
description: Campo HtmlLoadOptions. A volte è necessario evitare l'uso del caricatore interno delle risorse esterne come immagini o CSS e fornire un metodo personalizzato che recuperi le risorse richieste da qualche parte. Ad esempio, durante l'uso di Aspose.PDF nel cloud, l'accesso diretto ai file di riferimento è impossibile in tal caso, dovrebbe essere utilizzato del codice personalizzato inserito in un metodo speciale, e il delegato che si riferisce a quel metodo dovrebbe essere assegnato a questo attributo.
type: docs
weight: 100
url: /it/net/aspose.pdf/htmlloadoptions/customloaderofexternalresources/
---
## Campo HtmlLoadOptions.CustomLoaderOfExternalResources

A volte è necessario evitare l'uso del caricatore interno delle risorse esterne (come immagini o CSS) e fornire un metodo personalizzato che recuperi le risorse richieste da qualche parte. Ad esempio, durante l'uso di Aspose.PDF nel cloud, l'accesso diretto ai file di riferimento è impossibile: in tal caso, dovrebbe essere utilizzato del codice personalizzato inserito in un metodo speciale, e il delegato che si riferisce a quel metodo dovrebbe essere assegnato a questo attributo.

```csharp
public ResourceLoadingStrategy CustomLoaderOfExternalResources;
```

### Vedi Anche

* delegato [ResourceLoadingStrategy](../../loadoptions.resourceloadingstrategy/)
* classe [HtmlLoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)