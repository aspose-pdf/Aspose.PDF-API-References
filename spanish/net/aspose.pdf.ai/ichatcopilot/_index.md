---
title: Interface IChatCopilot
second_title: Aspose.PDF for .NET API Reference
description: Interfaz Aspose.Pdf.AI.IChatCopilot. Representa un copiloto de chat para interactuar con documentos a través de modelos de IA
type: docs
weight: 470
url: /es/net/aspose.pdf.ai/ichatcopilot/
---
## Interfaz IChatCopilot

Representa un copiloto de chat para interactuar con documentos a través de modelos de IA.

```csharp
public interface IChatCopilot : IAICopilot
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/ichatcopilot/deletecontextasync/)(CancellationToken?) | Elimina el contexto de forma asíncrona. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) | Obtiene de forma asíncrona una respuesta para la lista dada de mensajes. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) | Obtiene de forma asíncrona una respuesta para el mensaje dado. |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | Guarda de forma asíncrona el contexto en un archivo JSON. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) | Guarda de forma asíncrona las respuestas para la lista dada de mensajes en un archivo PDF. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) | Guarda de forma asíncrona la respuesta para el mensaje dado en un archivo PDF. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) | Guarda de forma asíncrona las respuestas para la lista dada de mensajes en un archivo con el formato especificado. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) | Guarda de forma asíncrona la respuesta para el mensaje dado en un archivo con el formato especificado. |

### Ver También

* interfaz [IAICopilot](../iaicopilot/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblaje [Aspose.PDF](../../)