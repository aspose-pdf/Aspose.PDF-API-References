---
title: Class RunCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.RunCreateRequest. Representa una solicitud para crear una ejecución
type: docs
weight: 980
url: /es/net/aspose.pdf.ai/runcreaterequest/
---
## Clase RunCreateRequest

Representa una solicitud para crear una ejecución.

```csharp
public class RunCreateRequest
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RunCreateRequest](runcreaterequest/)() | El constructor por defecto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AdditionalInstructions](../../aspose.pdf.ai/runcreaterequest/additionalinstructions/) { get; set; } | Obtiene o establece las instrucciones adicionales. Agrega instrucciones adicionales al final de las instrucciones para la ejecución. Esto es útil para modificar el comportamiento en una base por ejecución sin anular otras instrucciones. |
| [AdditionalMessages](../../aspose.pdf.ai/runcreaterequest/additionalmessages/) { get; set; } | Obtiene o establece los mensajes adicionales al hilo antes de crear la ejecución. |
| [AssistantId](../../aspose.pdf.ai/runcreaterequest/assistantid/) { get; set; } | Obtiene o establece el ID del asistente que se utilizará para ejecutar esta ejecución. |
| [Instructions](../../aspose.pdf.ai/runcreaterequest/instructions/) { get; set; } | Obtiene o establece las instrucciones que anulan las instrucciones del asistente. Esto es útil para modificar el comportamiento en una base por ejecución. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runcreaterequest/maxcompletiontokens/) { get; set; } | Obtiene o establece el número máximo de tokens de finalización que pueden usarse durante la ejecución. La ejecución hará un esfuerzo por usar solo el número de tokens de finalización especificado, a través de múltiples turnos de la ejecución. Si la ejecución excede el número de tokens de finalización especificados, la ejecución terminará con estado incompleto. Consulte incomplete_details para más información. |
| [MaxPromptTokens](../../aspose.pdf.ai/runcreaterequest/maxprompttokens/) { get; set; } | Obtiene o establece el número máximo de tokens de aviso que pueden usarse durante la ejecución. La ejecución hará un esfuerzo por usar solo el número de tokens de aviso especificado, a través de múltiples turnos de la ejecución. Si la ejecución excede el número de tokens de aviso especificados, la ejecución terminará con estado incompleto. Consulte incomplete_details para más información. |
| [Metadata](../../aspose.pdf.ai/runcreaterequest/metadata/) { get; set; } | Obtiene o establece un conjunto de 16 pares clave-valor que se pueden adjuntar a un objeto. Esto puede ser útil para almacenar información adicional sobre el objeto en un formato estructurado. Las claves pueden tener un máximo de 64 caracteres de longitud y los valores pueden tener un máximo de 512 caracteres de longitud. |
| [Model](../../aspose.pdf.ai/runcreaterequest/model/) { get; set; } | Obtiene o establece el ID del modelo que se utilizará para ejecutar esta ejecución. Si se proporciona un valor aquí, anulará el modelo asociado con el asistente. Si no, se utilizará el modelo asociado con el asistente. |
| [ResponseFormat](../../aspose.pdf.ai/runcreaterequest/responseformat/) { get; set; } | Obtiene o establece el formato de respuesta. Especifica el formato que el modelo debe generar. Compatible con GPT-4o, GPT-4 Turbo y todos los modelos GPT-3.5 Turbo desde gpt-3.5-turbo-1106. Establecer en { "type": "json_object" } habilita el modo JSON, que garantiza que el mensaje que genera el modelo sea un JSON válido. Importante: al usar el modo JSON, también debe instruir al modelo para que produzca JSON usted mismo a través de un mensaje del sistema o del usuario. Sin esto, el modelo puede generar un flujo interminable de espacios en blanco hasta que la generación alcance el límite de tokens, resultando en una solicitud de larga duración y aparentemente "atascada". También tenga en cuenta que el contenido del mensaje puede ser parcialmente cortado si finish_reason="length", lo que indica que la generación excedió max_tokens o la conversación excedió la longitud máxima del contexto. |
| [Stream](../../aspose.pdf.ai/runcreaterequest/stream/) { get; set; } | Obtiene o establece si se debe usar streaming. Si es verdadero, devuelve un flujo de eventos que ocurren durante la ejecución como eventos enviados por el servidor, terminando cuando la ejecución entra en un estado terminal con un mensaje de data: [DONE]. |
| [Temperature](../../aspose.pdf.ai/runcreaterequest/temperature/) { get; set; } | Obtiene o establece qué temperatura de muestreo usar, entre 0 y 2. Valores más altos como 0.8 harán que la salida sea más aleatoria, mientras que valores más bajos como 0.2 la harán más enfocada y determinista. |
| [ToolChoice](../../aspose.pdf.ai/runcreaterequest/toolchoice/) { get; set; } | Obtiene o establece qué herramienta (si la hay) es llamada por el modelo. none significa que el modelo no llamará a ninguna herramienta y en su lugar generará un mensaje. auto es el valor predeterminado y significa que el modelo puede elegir entre generar un mensaje o llamar a una o más herramientas. required significa que el modelo debe llamar a una o más herramientas antes de responder al usuario. Especificar una herramienta particular como {"type": "file_search"} o {"type": "function", "function": {"name": "my_function"}} obliga al modelo a llamar a esa herramienta. |
| [Tools](../../aspose.pdf.ai/runcreaterequest/tools/) { get; set; } | Obtiene o establece las herramientas que anulan las herramientas que el asistente puede usar para esta ejecución. Esto es útil para modificar el comportamiento en una base por ejecución. |
| [TopP](../../aspose.pdf.ai/runcreaterequest/topp/) { get; set; } | Obtiene o establece una alternativa al muestreo con temperatura, llamada muestreo de núcleo, donde el modelo considera los resultados de los tokens con masa de probabilidad top_p. Así que 0.1 significa que solo se consideran los tokens que comprenden el 10% superior de la masa de probabilidad. Generalmente recomendamos alterar esto o la temperatura, pero no ambos. |
| [TruncationStrategy](../../aspose.pdf.ai/runcreaterequest/truncationstrategy/) { get; set; } | Obtiene o establece la estrategia de truncamiento. Controla cómo se truncará un hilo antes de la ejecución. Use esto para controlar la ventana de contexto inicial de la ejecución. |

### Ver También

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)