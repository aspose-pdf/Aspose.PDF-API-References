---
title: IChatCopilot.GetResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IChatCopilot. Obtiene asíncronamente una respuesta para el mensaje dado
type: docs
weight: 20
url: /es/net/aspose.pdf.ai/ichatcopilot/getresponseasync/
---
## GetResponseAsync(string, CancellationToken?) {#getresponseasync_1}

Obtiene asíncronamente una respuesta para el mensaje dado.

```csharp
public Task<string> GetResponseAsync(string message, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | El mensaje de entrada para el cual se solicita una respuesta. |
| cancellationToken | Nullable`1 | El token de cancelación (opcional). |

### Return Value

Una tarea que representa la operación asíncrona con la cadena de respuesta.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## GetResponseAsync(List&lt;string&gt;, CancellationToken?) {#getresponseasync}

Obtiene asíncronamente una respuesta para la lista dada de mensajes.

```csharp
public Task<string> GetResponseAsync(List<string> messages, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | List`1 | La lista de mensajes de entrada para los cuales se solicitan respuestas. |
| cancellationToken | Nullable`1 | El token de cancelación (opcional). |

### Return Value

Una tarea que representa la operación asíncrona con la cadena de respuesta.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)