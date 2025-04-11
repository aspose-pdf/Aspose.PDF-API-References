---
title: OpenAIClient.GetRunsAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Recupera una lista de ejecuciones para un hilo especificado de manera asíncrona
type: docs
weight: 260
url: /es/net/aspose.pdf.ai/openaiclient/getrunsasync/
---
## Método OpenAIClient.GetRunsAsync

Recupera una lista de ejecuciones para un hilo especificado de manera asíncrona.

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threadId | String | El ID del hilo del que recuperar ejecuciones. |
| queryParameters | RunListQueryParameters | Parámetros de consulta opcionales para filtrar la lista de ejecuciones. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene una lista de ejecuciones.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id del hilo es nulo o está vacío. |

### Véase También

* clase [RunListResponse](../../runlistresponse/)
* clase [RunListQueryParameters](../../runlistqueryparameters/)
* clase [OpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)