---
title: Class CreateChatCompletionChunkResponse
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.CreateChatCompletionChunkResponse. Representa un fragmento transmitido de una respuesta de finalización de chat devuelta por el modelo basado en la entrada proporcionada
type: docs
weight: 250
url: /es/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## Clase CreateChatCompletionChunkResponse

Representa un fragmento transmitido de una respuesta de finalización de chat devuelta por el modelo, basado en la entrada proporcionada.

```csharp
public class CreateChatCompletionChunkResponse
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CreateChatCompletionChunkResponse](createchatcompletionchunkresponse/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | Obtiene o establece una lista de opciones de finalización de chat. Puede contener más de un elemento si n es mayor que 1. También puede estar vacío para el último fragmento si estableces stream_options: {"include_usage": true}. |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) de cuándo se creó la finalización de chat. Cada fragmento tiene la misma marca de tiempo. |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | Obtiene o establece un identificador único para la finalización de chat. Cada fragmento tiene el mismo ID. |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | Obtiene o establece el modelo para generar la finalización. |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | Obtiene o establece el tipo de objeto, que siempre es chat.completion.chunk. |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | Obtiene o establece la huella digital que representa la configuración del backend con la que se ejecuta el modelo. Puede usarse junto con el parámetro de solicitud seed para entender cuándo se han realizado cambios en el backend que podrían afectar el determinismo. |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | Obtiene o establece un campo opcional que solo estará presente cuando establezcas stream_options: {"include_usage": true} en tu solicitud. Cuando está presente, contiene un valor nulo excepto para el último fragmento que contiene las estadísticas de uso de tokens para toda la solicitud. |

### Ver También

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)