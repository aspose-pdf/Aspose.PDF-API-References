---
title: IOpenAIClient.GetFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IOpenAIClient. Recupera un elenco di file in modo asincrono in base allo scopo specificato
type: docs
weight: 220
url: /it/net/aspose.pdf.ai/iopenaiclient/getfilesasync/
---
## Metodo IOpenAIClient.GetFilesAsync

Recupera un elenco di file in modo asincrono in base allo scopo specificato.

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| purpose | String | Facoltativo. Lo scopo dei file da recuperare. Se nullo, vengono recuperati file per tutti gli scopi. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di Ritorno

Un'attività che rappresenta l'operazione asincrona. Il risultato dell'attività contiene un elenco di file.

### Vedi Anche

* classe [FileListResponse](../../filelistresponse/)
* interfaccia [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)