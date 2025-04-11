---
title: Class RunStepResponse
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.RunStepResponse. Representa un paso en la ejecución de una ejecución
type: docs
weight: 1060
url: /es/net/aspose.pdf.ai/runstepresponse/
---
## Clase RunStepResponse

Representa un paso en la ejecución de una ejecución.

```csharp
public class RunStepResponse : BaseResponse
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RunStepResponse](runstepresponse/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runstepresponse/assistantid/) { get; set; } | Obtiene o establece el ID del asistente asociado con el paso de ejecución. |
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) para cuando se canceló el paso de ejecución. |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) para cuando se completó el paso de ejecución. |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) para cuando se creó el paso de ejecución. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtiene o establece el detalle de la respuesta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtiene o establece el error de respuesta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtiene o establece la información del error. |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) para cuando expiró el paso de ejecución. Un paso se considera expirado si la ejecución principal ha expirado. |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) para cuando falló el paso de ejecución. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtiene o establece los encabezados de respuesta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtiene o establece el código de estado HTTP. |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | Obtiene o establece el identificador del paso de ejecución, que se puede referenciar en los puntos finales de la API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica si la respuesta fue exitosa. |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | Obtiene o establece el último error asociado con este paso de ejecución. Será nulo si no hay errores. |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | Obtiene o establece un conjunto de 16 pares clave-valor que se pueden adjuntar a un objeto. Esto puede ser útil para almacenar información adicional sobre el objeto en un formato estructurado. Las claves pueden tener un máximo de 64 caracteres y los valores pueden tener un máximo de 512 caracteres. |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | Obtiene o establece el tipo de objeto, que siempre es thread.run.step. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtiene la frase de razón del error. |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | Obtiene o establece el ID de la ejecución de la que forma parte este paso de ejecución. |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | Obtiene o establece el tipo de paso de ejecución, que puede ser message_creation o tool_calls. |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | Obtiene o establece el estado del paso de ejecución, que puede ser in_progress, cancelled, failed, completed o expired. |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | Obtiene o establece los detalles del paso de ejecución. |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | Obtiene o establece el ID del hilo que se ejecutó. |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | Obtiene o establece estadísticas de uso relacionadas con el paso de ejecución. Este valor será nulo mientras el estado del paso de ejecución esté in_progress. |

### Véase también

* clase [BaseResponse](../baseresponse/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblaje [Aspose.PDF](../../)