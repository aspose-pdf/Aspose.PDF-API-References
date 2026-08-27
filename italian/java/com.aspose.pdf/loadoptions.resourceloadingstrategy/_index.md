---
title: "LoadOptions.ResourceLoadingStrategy"
linktitle: "LoadOptions.ResourceLoadingStrategy"
second_title: "Riferimento API Aspose.PDF per Java"
description: "A volte è necessario evitare l'uso del caricatore interno di risorse esterne (come immagini o CSS) e fornire un metodo personalizzato, che otterrà le risorse richieste da qualche parte."
type: docs
weight: 2830
url: /it/java/com.aspose.pdf/loadoptions.resourceloadingstrategy/
---
```
public static interface LoadOptions.ResourceLoadingStrategy
```

A volte è necessario evitare l'uso del caricatore interno di risorse esterne (come immagini o CSS) e fornire un metodo personalizzato, che otterrà le risorse richieste da qualche parte. Ad esempio, durante l'uso di Aspose.PDf nel cloud l'accesso diretto ai file di riferimento è impossibile, e del codice personalizzato inserito in un metodo speciale dovrebbe essere utilizzato. Questo delegato definisce la firma di tale metodo personalizzato.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [invoke](#invoke-java.lang.String-) |  |

### invoke {#invoke-java.lang.String-}
