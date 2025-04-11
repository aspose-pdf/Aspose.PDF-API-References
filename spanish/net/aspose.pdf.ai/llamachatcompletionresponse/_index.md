---
title: Class LlamaChatCompletionResponse
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.LlamaChatCompletionResponse. Representa una respuesta de finalización de chat devuelta por el modelo basado en la entrada proporcionada
type: docs
weight: 690
url: /es/net/aspose.pdf.ai/llamachatcompletionresponse/
---
## Clase LlamaChatCompletionResponse

Representa una respuesta de finalización de chat devuelta por el modelo, basada en la entrada proporcionada.

```csharp
public class LlamaChatCompletionResponse : BaseResponse
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LlamaChatCompletionResponse](llamachatcompletionresponse/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Choices](../../aspose.pdf.ai/llamachatcompletionresponse/choices/) { get; set; } | Obtiene o establece una lista de opciones de finalización de chat. Puede haber más de una si n es mayor que 1. |
| [Created](../../aspose.pdf.ai/llamachatcompletionresponse/created/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) de cuándo se creó la finalización del chat. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtiene o establece el detalle de la respuesta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtiene o establece el error de respuesta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtiene o establece la información del error. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtiene o establece los encabezados de respuesta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtiene o establece el código de estado HTTP. |
| [Id](../../aspose.pdf.ai/llamachatcompletionresponse/id/) { get; set; } | Obtiene o establece un identificador único para la finalización del chat. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica si la respuesta fue exitosa. |
| [Model](../../aspose.pdf.ai/llamachatcompletionresponse/model/) { get; set; } | Obtiene o establece el modelo utilizado para la finalización del chat. |
| [Object](../../aspose.pdf.ai/llamachatcompletionresponse/object/) { get; set; } | Obtiene o establece el tipo de objeto, que siempre es chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtiene la frase de razón del error. |
| [SystemFingerprint](../../aspose.pdf.ai/llamachatcompletionresponse/systemfingerprint/) { get; set; } | Obtiene o establece la huella digital que representa la configuración del backend con la que se ejecuta el modelo. |
| [Usage](../../aspose.pdf.ai/llamachatcompletionresponse/usage/) { get; set; } | Obtiene o establece estadísticas de uso para la solicitud de finalización. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/llamachatcompletionresponse/tostring/)() | Devuelve una representación en cadena de la primera opción. |

### Véase también

* clase [BaseResponse](../baseresponse/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../)