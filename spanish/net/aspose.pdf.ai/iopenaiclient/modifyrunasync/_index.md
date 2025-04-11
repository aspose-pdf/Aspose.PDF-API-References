---
title: IOpenAIClient.ModifyRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Modifica una ejecución existente dentro de un hilo de manera asíncrona
type: docs
weight: 370
url: /es/net/aspose.pdf.ai/iopenaiclient/modifyrunasync/
---
## Método IOpenAIClient.ModifyRunAsync

Modifica una ejecución existente dentro de un hilo de manera asíncrona.

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, 
    RunModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threadId | String | El ID del hilo que contiene la ejecución. |
| runId | String | El ID de la ejecución a modificar. |
| assistantModifyRequest | RunModifyRequest | Los detalles de la solicitud para modificar la ejecución. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene la respuesta de la modificación de la ejecución.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id del hilo es nulo o está vacío. |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el Id de la ejecución es nulo o está vacío. |

### Véase También

* clase [RunResponse](../../runresponse/)
* clase [RunModifyRequest](../../runmodifyrequest/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)