---
title: "HtmlLoadOptions.CustomLoaderOfExternalResources"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "HtmlLoadOptions campo. A volte è necessario evitare l'uso del loader interno di risorse esterne come immagini o CSS e fornire un metodo personalizzato che recuperi le risorse richieste da qualche parte. Per esempio, durante l'uso di Aspose.PDF nel cloud l'accesso diretto ai file di riferimento è impossibile; in tal caso del codice personalizzato inserito in un metodo speciale dovrebbe essere utilizzato e il delegato che fa riferimento a quel metodo dovrebbe essere assegnato a questo attributo."
type: docs
weight: 100
url: /it/net/aspose.pdf/htmlloadoptions/customloaderofexternalresources/
---
## HtmlLoadOptions.CustomLoaderOfExternalResources field

A volte è necessario evitare l'uso del loader interno di risorse esterne (come immagini o CSS) e fornire un metodo personalizzato che ottenga le risorse richieste da qualche parte. Ad esempio, durante l'uso di Aspose.PDF in cloud l'accesso diretto ai file di riferimento è impossibile: in tal caso dovrebbe essere utilizzato del codice personalizzato inserito in un metodo speciale, e il delegato che fa riferimento a quel metodo dovrebbe essere assegnato a questo attributo.

```csharp
public ResourceLoadingStrategy CustomLoaderOfExternalResources;
```

### Vedi anche

* delegate [ResourceLoadingStrategy](../../loadoptions.resourceloadingstrategy/)
* class [HtmlLoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


