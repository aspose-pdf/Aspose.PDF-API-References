---
title: IChatCopilot.SaveResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IChatCopilot. Guarda asíncronamente la respuesta para el mensaje dado en un archivo PDF
type: docs
weight: 40
url: /es/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/
---
## SaveResponseAsync(string, string, CancellationToken?) {#saveresponseasync_3}

Guarda asíncronamente la respuesta para el mensaje dado en un archivo PDF.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| message | String | El mensaje de entrada para el cual se guarda la respuesta. |
| outputFileName | String | El nombre del archivo PDF de salida para guardar la respuesta. |
| cancellationToken | Nullable`1 | El token de cancelación (opcional). |

### Valor de Retorno

Una tarea que representa la operación asíncrona.

### Véase También

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, SaveFormat, CancellationToken?) {#saveresponseasync_2}

Guarda asíncronamente la respuesta para el mensaje dado en un archivo con el formato especificado.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| message | String | El mensaje de entrada para el cual se guarda la respuesta. |
| outputFileName | String | El nombre del archivo de salida para guardar la respuesta. |
| saveFormat | SaveFormat | El formato en el que guardar la respuesta (PDF si no se especifica). |
| cancellationToken | Nullable`1 | El token de cancelación (opcional). |

### Valor de Retorno

Una tarea que representa la operación asíncrona.

### Véase También

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, CancellationToken?) {#saveresponseasync_1}

Guarda asíncronamente las respuestas para la lista dada de mensajes en un archivo PDF.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| messages | List`1 | La lista de mensajes de entrada para los cuales se guardan las respuestas. |
| outputFileName | String | El nombre del archivo PDF de salida para guardar las respuestas. |
| cancellationToken | Nullable`1 | El token de cancelación (opcional). |

### Valor de Retorno

Una tarea que representa la operación asíncrona.

### Véase También

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, SaveFormat, CancellationToken?) {#saveresponseasync}

Guarda asíncronamente las respuestas para la lista dada de mensajes en un archivo con el formato especificado.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| messages | List`1 | La lista de mensajes de entrada para los cuales se guardan las respuestas. |
| outputFileName | String | El nombre del archivo de salida para guardar las respuestas. |
| saveFormat | SaveFormat | El formato en el que guardar las respuestas (PDF si no se especifica). |
| cancellationToken | Nullable`1 | El token de cancelación (opcional). |

### Valor de Retorno

Una tarea que representa la operación asíncrona.

### Véase También

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)