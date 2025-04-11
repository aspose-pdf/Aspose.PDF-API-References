---
title: Class RunThreadCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.RunThreadCreateRequest. Representa una solicitud para crear un hilo y ejecutarlo en una sola solicitud
type: docs
weight: 1070
url: /es/net/aspose.pdf.ai/runthreadcreaterequest/
---
## Clase RunThreadCreateRequest

Representa una solicitud para crear un hilo y ejecutarlo en una sola solicitud.

```csharp
public class RunThreadCreateRequest
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RunThreadCreateRequest](runthreadcreaterequest/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runthreadcreaterequest/assistantid/) { get; set; } | Obtiene o establece el ID del asistente que se utilizará para ejecutar esta ejecución. |
| [Instructions](../../aspose.pdf.ai/runthreadcreaterequest/instructions/) { get; set; } | Obtiene o establece las instrucciones que anulan las instrucciones del asistente. Esto es útil para modificar el comportamiento en cada ejecución. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxcompletiontokens/) { get; set; } | Obtiene o establece el número máximo de tokens de finalización que se pueden utilizar durante la ejecución. La ejecución hará un esfuerzo por utilizar solo el número de tokens de finalización especificado, a lo largo de múltiples turnos de la ejecución. Si la ejecución excede el número de tokens de finalización especificado, la ejecución terminará con estado incompleto. Consulte incomplete_details para más información. |
| [MaxPromptTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxprompttokens/) { get; set; } | Obtiene o establece el número máximo de tokens de aviso que se pueden utilizar durante la ejecución. La ejecución hará un esfuerzo por utilizar solo el número de tokens de aviso especificado, a lo largo de múltiples turnos de la ejecución. Si la ejecución excede el número de tokens de aviso especificado, la ejecución terminará con estado incompleto. Consulte incomplete_details para más información. |
| [Metadata](../../aspose.pdf.ai/runthreadcreaterequest/metadata/) { get; set; } | Obtiene o establece un conjunto de 16 pares clave-valor que se pueden adjuntar a un objeto. Esto puede ser útil para almacenar información adicional sobre el objeto en un formato estructurado. Las claves pueden tener un máximo de 64 caracteres y los valores pueden tener un máximo de 512 caracteres. |
| [Model](../../aspose.pdf.ai/runthreadcreaterequest/model/) { get; set; } | Obtiene o establece el ID del modelo que se utilizará para ejecutar esta ejecución. Si se proporciona un valor aquí, anulará el modelo asociado con el asistente. Si no, se utilizará el modelo asociado con el asistente. |
| [ResponseFormat](../../aspose.pdf.ai/runthreadcreaterequest/responseformat/) { get; set; } | Obtiene o establece el formato que el modelo debe generar. Compatible con GPT-4o, GPT-4 Turbo y todos los modelos GPT-3.5 Turbo desde gpt-3.5-turbo-1106. Establecer en { "type": "json_object" } habilita el modo JSON, que garantiza que el mensaje que genera el modelo sea un JSON válido. Importante: al usar el modo JSON, también debe instruir al modelo para que produzca JSON usted mismo a través de un mensaje del sistema o del usuario. Sin esto, el modelo puede generar un flujo interminable de espacios en blanco hasta que la generación alcance el límite de tokens, lo que resulta en una solicitud de larga duración y aparentemente "atascada". También tenga en cuenta que el contenido del mensaje puede ser parcialmente cortado si finish_reason="length", lo que indica que la generación excedió max_tokens o la conversación excedió la longitud máxima del contexto. |
| [Stream](../../aspose.pdf.ai/runthreadcreaterequest/stream/) { get; set; } | Obtiene o establece si se debe usar streaming. Si es verdadero, devuelve un flujo de eventos que ocurren durante la ejecución como eventos enviados por el servidor, terminando cuando la ejecución entra en un estado terminal con un mensaje de data: [DONE]. |
| [Temperature](../../aspose.pdf.ai/runthreadcreaterequest/temperature/) { get; set; } | Obtiene o establece qué temperatura de muestreo utilizar, entre 0 y 2. Valores más altos como 0.8 harán que la salida sea más aleatoria, mientras que valores más bajos como 0.2 la harán más enfocada y determinista. |
| [Thread](../../aspose.pdf.ai/runthreadcreaterequest/thread/) { get; set; } | Obtiene o establece una solicitud para crear un hilo. |
| [ToolChoice](../../aspose.pdf.ai/runthreadcreaterequest/toolchoice/) { get; set; } | Obtiene o establece qué herramienta (si la hay) es llamada por el modelo. none significa que el modelo no llamará a ninguna herramienta y en su lugar generará un mensaje. auto es el valor predeterminado y significa que el modelo puede elegir entre generar un mensaje o llamar a una o más herramientas. required significa que el modelo debe llamar a una o más herramientas antes de responder al usuario. Especificar una herramienta particular como {"type": "file_search"} o {"type": "function", "function": {"name": "my_function"}} obliga al modelo a llamar a esa herramienta. |
| [ToolResources](../../aspose.pdf.ai/runthreadcreaterequest/toolresources/) { get; set; } | Obtiene o establece un conjunto de recursos que son utilizados por las herramientas del asistente. |
| [Tools](../../aspose.pdf.ai/runthreadcreaterequest/tools/) { get; set; } | Obtiene o establece las herramientas que anulan las herramientas que el asistente puede usar para esta ejecución. Esto es útil para modificar el comportamiento en cada ejecución. |
| [TopP](../../aspose.pdf.ai/runthreadcreaterequest/topp/) { get; set; } | Obtiene o establece un valor que es alternativo al muestreo con temperatura, llamado muestreo de núcleo, donde el modelo considera los resultados de los tokens con masa de probabilidad top_p. Así que 0.1 significa que solo se consideran los tokens que comprenden el 10% superior de la masa de probabilidad. Generalmente recomendamos alterar esto o la temperatura, pero no ambos. |
| [TruncationStrategy](../../aspose.pdf.ai/runthreadcreaterequest/truncationstrategy/) { get; set; } | Obtiene o establece la estrategia de truncamiento que controla cómo se truncará un hilo antes de la ejecución. Use esto para controlar la ventana de contexto inicial de la ejecución. |

### Véase también

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)