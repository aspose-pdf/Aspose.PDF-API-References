---
title: IOpenAIClient.CreateThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Crea un nuevo hilo de forma asíncrona
type: docs
weight: 70
url: /es/net/aspose.pdf.ai/iopenaiclient/createthreadasync/
---
## Método IOpenAIClient.CreateThreadAsync

Crea un nuevo hilo de forma asíncrona.

```csharp
public Task<ThreadResponse> CreateThreadAsync(ThreadCreateRequest threadCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threadCreateRequest | ThreadCreateRequest | El objeto de solicitud que contiene detalles para crear el hilo. |
| cancellationToken | Nullable`1 | Un token para cancelar la operación. |

### Valor de Retorno

Una tarea que representa la operación asíncrona. El resultado de la tarea contiene la respuesta de la creación del hilo.

### Ver También

* clase [ThreadResponse](../../threadresponse/)
* clase [ThreadCreateRequest](../../threadcreaterequest/)
* interfaz [IOpenAIClient](../)
* espacio de nombres [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../../)