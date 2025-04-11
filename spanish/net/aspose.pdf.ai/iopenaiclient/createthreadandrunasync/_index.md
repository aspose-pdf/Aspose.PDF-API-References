---
title: IOpenAIClient.CreateThreadAndRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Crea un hilo y una ejecución dentro de él de manera asíncrona
type: docs
weight: 60
url: /es/net/aspose.pdf.ai/iopenaiclient/createthreadandrunasync/
---
## Método IOpenAIClient.CreateThreadAndRunAsync

Crea un hilo y una ejecución dentro de él de manera asíncrona.

```csharp
public Task<RunResponse> CreateThreadAndRunAsync(RunThreadCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| runCreateRequest | RunThreadCreateRequest | Los detalles de la solicitud para crear el hilo y la ejecución. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene la respuesta de la creación del hilo y la ejecución.

### Véase También

* clase [RunResponse](../../runresponse/)
* clase [RunThreadCreateRequest](../../runthreadcreaterequest/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)