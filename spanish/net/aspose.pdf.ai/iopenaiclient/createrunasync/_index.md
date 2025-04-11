---
title: IOpenAIClient.CreateRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Crea una ejecución dentro de un hilo especificado de manera asíncrona
type: docs
weight: 50
url: /es/net/aspose.pdf.ai/iopenaiclient/createrunasync/
---
## Método IOpenAIClient.CreateRunAsync

Crea una ejecución dentro de un hilo especificado de manera asíncrona.

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threadId | String | El ID del hilo donde se creará la ejecución. |
| runCreateRequest | RunCreateRequest | Los detalles de la solicitud para crear la ejecución. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene la respuesta de la creación de la ejecución.

### Excepciones

| excepción | condición |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lanzada cuando el ID del hilo es nulo o está vacío. |

### Véase También

* clase [RunResponse](../../runresponse/)
* clase [RunCreateRequest](../../runcreaterequest/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)