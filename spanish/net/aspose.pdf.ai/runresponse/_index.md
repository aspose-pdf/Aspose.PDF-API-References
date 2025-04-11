---
title: Class RunResponse
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.RunResponse. Representa una ejecución en un hilo
type: docs
weight: 1020
url: /es/net/aspose.pdf.ai/runresponse/
---
## Clase RunResponse

Representa una ejecución en un hilo.

```csharp
public class RunResponse : BaseResponse, IStatus
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RunResponse](runresponse/)() | El constructor por defecto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runresponse/assistantid/) { get; set; } | Obtiene o establece el ID del asistente utilizado para la ejecución de esta ejecución. |
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) para cuando se canceló la ejecución. |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) para cuando se completó la ejecución. |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) para cuando se creó la ejecución. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtiene o establece el detalle de la respuesta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtiene o establece el error de respuesta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtiene o establece la información del error. |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) para cuando la ejecución expirará. |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) para cuando la ejecución falló. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtiene o establece los encabezados de respuesta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtiene o establece el código de estado HTTP. |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | Obtiene o establece el identificador, que puede ser referenciado en los puntos finales de la API. |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | Obtiene o establece los detalles sobre por qué la ejecución está incompleta. Será nulo si la ejecución no está incompleta. |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | Obtiene o establece las instrucciones que el asistente utilizó para esta ejecución. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica si la respuesta fue exitosa. |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | Obtiene o establece el último error asociado con esta ejecución. Será nulo si no hay errores. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | Obtiene o establece el número máximo de tokens de finalización especificados que se han utilizado durante la ejecución. |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | Obtiene o establece el número máximo de tokens de aviso especificados que se han utilizado durante la ejecución. |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | Obtiene o establece un conjunto de 16 pares clave-valor que se pueden adjuntar a un objeto. Esto puede ser útil para almacenar información adicional sobre el objeto en un formato estructurado. Las claves pueden tener un máximo de 64 caracteres y los valores pueden tener un máximo de 512 caracteres. |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | Obtiene o establece el modelo que el asistente utilizó para esta ejecución. |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | Obtiene o establece el tipo de objeto, que siempre es thread.run. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtiene la frase de razón del error. |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | Obtiene o establece los detalles sobre la acción requerida para continuar la ejecución. Será nulo si no se requiere ninguna acción. |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | Obtiene o establece el formato que el modelo debe generar. Compatible con GPT-4o, GPT-4 Turbo y todos los modelos GPT-3.5 Turbo desde gpt-3.5-turbo-1106. Establecer en { "type": "json_object" } habilita el modo JSON, que garantiza que el mensaje que genera el modelo sea un JSON válido. Importante: al usar el modo JSON, también debe instruir al modelo para que produzca JSON usted mismo a través de un mensaje del sistema o del usuario. Sin esto, el modelo puede generar un flujo interminable de espacios en blanco hasta que la generación alcance el límite de tokens, lo que resulta en una solicitud de larga duración y aparentemente "atascada". También tenga en cuenta que el contenido del mensaje puede ser parcialmente cortado si finish_reason="length", lo que indica que la generación excedió max_tokens o la conversación excedió la longitud máxima del contexto. |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) para cuando se inició la ejecución. |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | Obtiene o establece el estado de la ejecución, que puede ser en cola, en progreso, requiere acción, cancelando, cancelado, fallido, completado, incompleto o expirado. |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | Obtiene o establece la temperatura de muestreo utilizada para esta ejecución. Si no se establece, por defecto es 1. |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | Obtiene o establece el ID del hilo que se ejecutó como parte de esta ejecución. |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | Obtiene o establece qué herramienta (si la hay) es llamada por el modelo. none significa que el modelo no llamará a ninguna herramienta y en su lugar generará un mensaje. auto es el valor predeterminado y significa que el modelo puede elegir entre generar un mensaje o llamar a una o más herramientas. required significa que el modelo debe llamar a una o más herramientas antes de responder al usuario. Especificar una herramienta particular como {"type": "file_search"} o {"type": "function", "function": {"name": "my_function"}} obliga al modelo a llamar a esa herramienta. |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | Obtiene o establece la lista de herramientas que el asistente utilizó para esta ejecución. |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | Obtiene o establece el valor de muestreo de núcleo utilizado para esta ejecución. Si no se establece, por defecto es 1. |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | Obtiene o establece la estrategia de truncamiento que controla cómo se truncará un hilo antes de la ejecución. Use esto para controlar la ventana de contexto inicial de la ejecución. |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | Obtiene o establece las estadísticas de uso relacionadas con la ejecución. Este valor será nulo si la ejecución no está en un estado terminal (es decir, en progreso, en cola, etc.). |

### Ver También

* clase [BaseResponse](../baseresponse/)
* interfaz [IStatus](../istatus/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblaje [Aspose.PDF](../../)