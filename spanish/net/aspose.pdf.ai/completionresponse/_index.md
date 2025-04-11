---
title: Class CompletionResponse
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.CompletionResponse. Representa una respuesta de finalización de chat devuelta por el modelo basado en la entrada proporcionada
type: docs
weight: 240
url: /es/net/aspose.pdf.ai/completionresponse/
---
## Clase CompletionResponse

Representa una respuesta de finalización de chat devuelta por el modelo, basada en la entrada proporcionada.

```csharp
public class CompletionResponse : BaseResponse
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CompletionResponse](completionresponse/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Choices](../../aspose.pdf.ai/completionresponse/choices/) { get; set; } | Obtiene o establece una lista de opciones de finalización de chat. Puede haber más de una si n es mayor que 1. |
| [Created](../../aspose.pdf.ai/completionresponse/created/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) de cuándo se creó la finalización del chat. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtiene o establece el detalle de la respuesta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtiene o establece el error de respuesta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtiene o establece la información del error. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtiene o establece los encabezados de respuesta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtiene o establece el código de estado HTTP. |
| [Id](../../aspose.pdf.ai/completionresponse/id/) { get; set; } | Obtiene o establece un identificador único para la finalización del chat. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica si la respuesta fue exitosa. |
| [Model](../../aspose.pdf.ai/completionresponse/model/) { get; set; } | Obtiene o establece el modelo utilizado para la finalización del chat. |
| [Object](../../aspose.pdf.ai/completionresponse/object/) { get; set; } | Obtiene o establece el tipo de objeto, que siempre es chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtiene la frase de razón del error. |
| [SystemFingerprint](../../aspose.pdf.ai/completionresponse/systemfingerprint/) { get; set; } | Obtiene o establece la huella digital que representa la configuración del backend con la que se ejecuta el modelo. Se puede usar junto con el parámetro de solicitud seed para entender cuándo se han realizado cambios en el backend que podrían afectar el determinismo. |
| [Usage](../../aspose.pdf.ai/completionresponse/usage/) { get; set; } | Obtiene o establece las estadísticas de uso para la solicitud de finalización. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/completionresponse/tostring/)() | Devuelve el contenido de la primera opción como una cadena. |

### Ver También

* clase [BaseResponse](../baseresponse/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../)