---
title: OpenAIImageDescriptionCopilotExtensions.AddPdfImageDescriptionsAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo OpenAIImageDescriptionCopilotExtensions. Aggiunge in modo asincrono descrizioni delle immagini a un file PDF e salva nuovi documenti in cartelle specificate
type: docs
weight: 10
url: /it/net/aspose.pdf.ai/openaiimagedescriptioncopilotextensions/addpdfimagedescriptionsasync/
---
## Metodo OpenAIImageDescriptionCopilotExtensions.AddPdfImageDescriptionsAsync

Aggiunge in modo asincrono descrizioni delle immagini a un file PDF e salva nuovi documenti in cartelle specificate.

```csharp
public static Task AddPdfImageDescriptionsAsync(
    this IImageDescriptionCopilot imageDescriptionCopilot, string outputDirectory, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageDescriptionCopilot | IImageDescriptionCopilot | Il copilot per la descrizione delle immagini. |
| outputDirectory | String | La directory di output dove salvare i file PDF di output. |
| cancellationToken | Nullable`1 | Il token di cancellazione (opzionale). |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona.

### Vedi anche

* interfaccia [IImageDescriptionCopilot](../../iimagedescriptioncopilot/)
* classe [OpenAIImageDescriptionCopilotExtensions](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)