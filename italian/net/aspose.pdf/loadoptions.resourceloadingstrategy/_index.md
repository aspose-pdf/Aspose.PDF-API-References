---
title: Delegate LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF for .NET API Reference
description: A volte è necessario evitare l'uso del caricatore interno di risorse esterne come immagini o CSS e fornire un metodo personalizzato che ottenga le risorse richieste da qualche parte. Ad esempio, durante l'uso di Aspose.Pdf nel cloud, l'accesso diretto ai file referenziati è impossibile e deve essere utilizzato del codice personalizzato inserito in un metodo speciale. Questo delegato definisce la firma di tale metodo personalizzato.
type: docs
weight: 6160
url: /it/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## Delegate LoadOptions.ResourceLoadingStrategy

A volte è necessario evitare l'uso del caricatore interno di risorse esterne (come immagini o CSS) e fornire un metodo personalizzato che ottenga le risorse richieste da qualche parte. Ad esempio, durante l'uso di Aspose.Pdf nel cloud, l'accesso diretto ai file referenziati è impossibile e deve essere utilizzato del codice personalizzato inserito in un metodo speciale. Questo delegato definisce la firma di tale metodo personalizzato.

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resourceURI | String | URI della risorsa. |

### Valore di ritorno

Oggetto ResourceLoadingResult.

### Vedi anche

* classe [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)