---
title: Class AssistantResponse
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.AssistantResponse. Representa un asistente que puede llamar al modelo y usar herramientas
type: docs
weight: 140
url: /es/net/aspose.pdf.ai/assistantresponse/
---
## Clase AssistantResponse

Representa un asistente que puede llamar al modelo y usar herramientas.

```csharp
public class AssistantResponse : BaseResponse
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [AssistantResponse](assistantresponse/)() | El constructor por defecto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/assistantresponse/createdat/) { get; set; } | Obtiene o establece la marca de tiempo Unix (en segundos) para cuando se creó el asistente. |
| [Description](../../aspose.pdf.ai/assistantresponse/description/) { get; set; } | Obtiene o establece la descripción del asistente. La longitud máxima es de 512 caracteres. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtiene o establece el detalle de la respuesta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtiene o establece el error de respuesta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtiene o establece la información del error. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtiene o establece los encabezados de respuesta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtiene o establece el código de estado HTTP. |
| [Id](../../aspose.pdf.ai/assistantresponse/id/) { get; set; } | Obtiene o establece el identificador, que puede ser referenciado en los puntos finales de la API. |
| [Instructions](../../aspose.pdf.ai/assistantresponse/instructions/) { get; set; } | Obtiene o establece las instrucciones del sistema que utiliza el asistente. La longitud máxima es de 256,000 caracteres. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica si la respuesta fue exitosa. |
| [Metadata](../../aspose.pdf.ai/assistantresponse/metadata/) { get; set; } | Obtiene o establece un conjunto de 16 pares clave-valor que pueden ser adjuntados a un objeto. Esto puede ser útil para almacenar información adicional sobre el objeto en un formato estructurado. Las claves pueden tener un máximo de 64 caracteres y los valores pueden tener un máximo de 512 caracteres. |
| [Model](../../aspose.pdf.ai/assistantresponse/model/) { get; set; } | Obtiene o establece el ID del modelo a utilizar. Puedes usar la API de Listar modelos para ver todos tus modelos disponibles, o ver nuestra descripción general del modelo para obtener descripciones de ellos. |
| [Name](../../aspose.pdf.ai/assistantresponse/name/) { get; set; } | Obtiene o establece el nombre del asistente. La longitud máxima es de 256 caracteres. |
| [Object](../../aspose.pdf.ai/assistantresponse/object/) { get; set; } | Obtiene o establece el tipo de objeto, que siempre es asistente. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtiene la frase de razón del error. |
| [ResponseFormat](../../aspose.pdf.ai/assistantresponse/responseformat/) { get; set; } | Obtiene o establece el formato que el modelo debe generar. Compatible con GPT-4o, GPT-4 Turbo y todos los modelos GPT-3.5 Turbo desde gpt-3.5-turbo-1106. Establecer en { "type": "json_object" } habilita el modo JSON, que garantiza que el mensaje que genera el modelo sea un JSON válido. Importante: al usar el modo JSON, también debes instruir al modelo para que produzca JSON tú mismo a través de un mensaje del sistema o del usuario. Sin esto, el modelo puede generar un flujo interminable de espacios en blanco hasta que la generación alcance el límite de tokens, lo que resulta en una solicitud de larga duración y aparentemente "atascada". También ten en cuenta que el contenido del mensaje puede ser parcialmente cortado si finish_reason="length", lo que indica que la generación excedió max_tokens o la conversación excedió la longitud máxima del contexto. |
| [Temperature](../../aspose.pdf.ai/assistantresponse/temperature/) { get; set; } | Obtiene o establece qué temperatura de muestreo usar, entre 0 y 2. Valores más altos como 0.8 harán que la salida sea más aleatoria, mientras que valores más bajos como 0.2 la harán más enfocada y determinista. |
| [ToolResources](../../aspose.pdf.ai/assistantresponse/toolresources/) { get; set; } | Obtiene o establece un conjunto de recursos que son utilizados por las herramientas del asistente. Los recursos son específicos del tipo de herramienta. Por ejemplo, la herramienta code_interpreter requiere una lista de IDs de archivos, mientras que la herramienta file_search requiere una lista de IDs de almacenes de vectores. |
| [Tools](../../aspose.pdf.ai/assistantresponse/tools/) { get; set; } | Obtiene o establece una lista de herramientas habilitadas en el asistente. Puede haber un máximo de 128 herramientas por asistente. Las herramientas pueden ser de tipos code_interpreter, file_search o function. |
| [TopP](../../aspose.pdf.ai/assistantresponse/topp/) { get; set; } | Obtiene o establece una alternativa al muestreo con temperatura, llamada muestreo de núcleo, donde el modelo considera los resultados de los tokens con masa de probabilidad top_p. Así que 0.1 significa que solo se consideran los tokens que comprenden el 10% superior de la masa de probabilidad. Generalmente recomendamos alterar esto o la temperatura, pero no ambos. |

### Ver También

* clase [BaseResponse](../baseresponse/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblaje [Aspose.PDF](../../)