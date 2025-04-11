---
title: Class ThreadMessageResponse
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.ThreadMessageResponse. Representa un mensaje dentro de un hilo
type: docs
weight: 1160
url: /es/net/aspose.pdf.ai/threadmessageresponse/
---
## Clase ThreadMessageResponse

Representa un mensaje dentro de un hilo.

```csharp
public class ThreadMessageResponse : BaseResponse, IStatus
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ThreadMessageResponse](threadmessageresponse/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/threadmessageresponse/assistantid/) { get; set; } | Obtiene o establece, si corresponde, el ID del asistente que redactó este mensaje. |
| [Attachments](../../aspose.pdf.ai/threadmessageresponse/attachments/) { get; set; } | Obtiene o establece una lista de archivos adjuntos al mensaje. |
| [CompletedAt](../../aspose.pdf.ai/threadmessageresponse/completedat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) para cuando se completó el mensaje. |
| [Content](../../aspose.pdf.ai/threadmessageresponse/content/) { get; set; } | Obtiene o establece el contenido del mensaje en un arreglo de texto y/o imágenes. |
| [CreatedAt](../../aspose.pdf.ai/threadmessageresponse/createdat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) para cuando se creó el mensaje. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtiene o establece el detalle de la respuesta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtiene o establece el error de respuesta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtiene o establece la información del error. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtiene o establece los encabezados de respuesta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtiene o establece el código de estado HTTP. |
| [Id](../../aspose.pdf.ai/threadmessageresponse/id/) { get; set; } | Obtiene o establece el identificador, que puede ser referenciado en los puntos finales de la API. |
| [IncompleteAt](../../aspose.pdf.ai/threadmessageresponse/incompleteat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) para cuando el mensaje fue marcado como incompleto. |
| [IncompleteDetails](../../aspose.pdf.ai/threadmessageresponse/incompletedetails/) { get; set; } | Obtiene o establece un mensaje incompleto, detalles sobre por qué el mensaje está incompleto. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica si la respuesta fue exitosa. |
| [Metadata](../../aspose.pdf.ai/threadmessageresponse/metadata/) { get; set; } | Obtiene o establece un conjunto de 16 pares clave-valor que pueden ser adjuntados a un objeto. Esto puede ser útil para almacenar información adicional sobre el objeto en un formato estructurado. Las claves pueden tener un máximo de 64 caracteres y los valores pueden tener un máximo de 512 caracteres. |
| [Object](../../aspose.pdf.ai/threadmessageresponse/object/) { get; set; } | Obtiene o establece el tipo de objeto, que siempre es "thread.message". |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtiene la frase de razón del error. |
| [Role](../../aspose.pdf.ai/threadmessageresponse/role/) { get; set; } | Obtiene o establece la entidad que produjo el mensaje. Uno de "user" o "assistant". |
| [RunId](../../aspose.pdf.ai/threadmessageresponse/runid/) { get; set; } | Obtiene o establece el ID de la ejecución asociada con la creación de este mensaje. El valor es nulo cuando los mensajes se crean manualmente. |
| [Status](../../aspose.pdf.ai/threadmessageresponse/status/) { get; set; } | Obtiene o establece el estado del mensaje. Uno de queued, in_progress, requires_action o completed. |
| [ThreadId](../../aspose.pdf.ai/threadmessageresponse/threadid/) { get; set; } | Obtiene o establece el ID del hilo al que pertenece este mensaje. |

### Ver También

* clase [BaseResponse](../baseresponse/)
* interfaz [IStatus](../istatus/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblaje [Aspose.PDF](../../)