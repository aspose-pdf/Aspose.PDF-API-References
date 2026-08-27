---
title: "Delegate LoadOptions.ResourceLoadingStrategy"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "A volte è necessario evitare l'uso del caricatore interno di risorse esterne, come immagini o CSS, e fornire un metodo personalizzato che recuperi le risorse richieste da qualche parte. Ad esempio, durante l'utilizzo di Aspose.Pdf nel cloud l'accesso diretto ai file di riferimento è impossibile e si deve utilizzare del codice personalizzato inserito in un metodo speciale. Questo delegato definisce la firma di tale metodo personalizzato"
type: docs
weight: 6300
url: /it/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy delegate

A volte è necessario evitare l'uso del caricatore interno di risorse esterne (come immagini o CSS) e fornire un metodo personalizzato che recuperi le risorse richieste da qualche parte. Ad esempio, durante l'utilizzo di Aspose.Pdf nel cloud l'accesso diretto ai file di riferimento è impossibile, e si deve utilizzare del codice personalizzato inserito in un metodo speciale. Questo delegato definisce la firma di tale metodo personalizzato.

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resourceURI | String | URI della risorsa. |

### Valore di ritorno

Oggetto ResourceLoadingResult.

### Vedi anche

* class [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


