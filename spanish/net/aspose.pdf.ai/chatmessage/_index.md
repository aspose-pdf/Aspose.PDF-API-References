---
title: Class ChatMessage
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.ChatMessage. Un mensaje de finalización de chat generado por el modelo
type: docs
weight: 190
url: /es/net/aspose.pdf.ai/chatmessage/
---
## Clase ChatMessage

Un mensaje de finalización de chat generado por el modelo.

```csharp
public class ChatMessage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ChatMessage](chatmessage/#constructor)() | Inicializa una nueva instancia de la clase `ChatMessage`. |
| [ChatMessage](chatmessage/#constructor_1)(string, string) | Inicializa una nueva instancia de la clase `ChatMessage`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Content](../../aspose.pdf.ai/chatmessage/content/) { get; set; } | Obtiene o establece el contenido del mensaje. |
| [Name](../../aspose.pdf.ai/chatmessage/name/) { get; set; } | Obtiene o establece un nombre opcional para el participante. Proporciona información al modelo para diferenciar entre participantes del mismo rol. |
| [Role](../../aspose.pdf.ai/chatmessage/role/) { get; set; } | Obtiene o establece el rol del autor del mensaje. |
| [ToolCallId](../../aspose.pdf.ai/chatmessage/toolcallid/) { get; set; } | Obtiene o establece la llamada a la herramienta a la que este mensaje está respondiendo. |
| [ToolCalls](../../aspose.pdf.ai/chatmessage/toolcalls/) { get; set; } | Obtiene o establece las llamadas a la herramienta generadas por el modelo, como llamadas a funciones. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/chatmessage/fromassistant/)(string) | Crea un nuevo objeto ChatMessage que representa un mensaje del asistente. |
| static [FromSystem](../../aspose.pdf.ai/chatmessage/fromsystem/)(string) | Crea un nuevo objeto ChatMessage que representa un mensaje del sistema. |
| static [FromUser](../../aspose.pdf.ai/chatmessage/fromuser/)(string) | Crea un nuevo objeto ChatMessage que representa un mensaje del usuario. |

### Ver También

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)