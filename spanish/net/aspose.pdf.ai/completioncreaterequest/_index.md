---
title: Class CompletionCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.CompletionCreateRequest. Representa una solicitud para el endpoint de Crear Chat Completion
type: docs
weight: 220
url: /es/net/aspose.pdf.ai/completioncreaterequest/
---
## Clase CompletionCreateRequest

Representa una solicitud para el endpoint de Crear Chat Completion.

```csharp
public class CompletionCreateRequest
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CompletionCreateRequest](completioncreaterequest/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [FrequencyPenalty](../../aspose.pdf.ai/completioncreaterequest/frequencypenalty/) { get; set; } | Obtiene o establece un número entre -2.0 y 2.0. Los valores positivos penalizan nuevos tokens basados en su frecuencia existente en el texto hasta ahora, disminuyendo la probabilidad del modelo de repetir la misma línea textualmente. |
| [LogitBias](../../aspose.pdf.ai/completioncreaterequest/logitbias/) { get; set; } | Obtiene o establece la probabilidad de que aparezcan tokens especificados en la finalización. Acepta un objeto JSON que mapea tokens (especificados por su ID de token en el tokenizador) a un valor de sesgo asociado de -100 a 100. |
| [Logprobs](../../aspose.pdf.ai/completioncreaterequest/logprobs/) { get; set; } | Obtiene o establece si se deben devolver las probabilidades logarítmicas de los tokens de salida o no. Si es verdadero, devuelve las probabilidades logarítmicas de cada token de salida devuelto en el contenido del mensaje. |
| [MaxTokens](../../aspose.pdf.ai/completioncreaterequest/maxtokens/) { get; set; } | Obtiene o establece el número máximo de tokens a generar en la finalización. |
| [Messages](../../aspose.pdf.ai/completioncreaterequest/messages/) { get; set; } | Obtiene o establece una lista de mensajes que comprenden la conversación hasta ahora. |
| [Model](../../aspose.pdf.ai/completioncreaterequest/model/) { get; set; } | Obtiene o establece el ID del modelo a utilizar. |
| [NumberOfChoices](../../aspose.pdf.ai/completioncreaterequest/numberofchoices/) { get; set; } | Obtiene o establece cuántas opciones de finalización de chat generar para cada mensaje de entrada. Tenga en cuenta que se le cobrará según el número de tokens generados en todas las opciones. Mantenga n como 1 para minimizar costos. |
| [PresencePenalty](../../aspose.pdf.ai/completioncreaterequest/presencepenalty/) { get; set; } | Obtiene o establece un número entre -2.0 y 2.0. Los valores positivos penalizan nuevos tokens basados en si aparecen en el texto hasta ahora, aumentando la probabilidad del modelo de hablar sobre nuevos temas. |
| [ResponseFormat](../../aspose.pdf.ai/completioncreaterequest/responseformat/) { get; set; } | Obtiene o establece un objeto que especifica el formato que el modelo debe generar. Compatible con GPT-4 Turbo y todos los modelos GPT-3.5 Turbo más recientes que gpt-3.5-turbo-1106. Configurar a { "type": "json_object" } habilita el modo JSON, que garantiza que el mensaje que genera el modelo sea un JSON válido. |
| [Seed](../../aspose.pdf.ai/completioncreaterequest/seed/) { get; set; } | Obtiene o establece el valor de Seed. Esta función está en Beta. Si se especifica, nuestro sistema hará un esfuerzo por muestrear de manera determinista, de modo que las solicitudes repetidas con la misma semilla y parámetros deberían devolver el mismo resultado. No se garantiza la determinación, y debe consultar el parámetro de respuesta system_fingerprint para monitorear cambios en el backend. |
| [Stop](../../aspose.pdf.ai/completioncreaterequest/stop/) { get; set; } | Obtiene o establece hasta 4 secuencias donde la API dejará de generar más tokens. |
| [Stream](../../aspose.pdf.ai/completioncreaterequest/stream/) { get; set; } | Obtiene o establece si se debe usar streaming. Si se establece, se enviarán deltas de mensajes parciales, como en ChatGPT. Los tokens se enviarán como eventos enviados por el servidor solo de datos a medida que estén disponibles, con el flujo terminado por un mensaje de datos: [DONE]. |
| [Temperature](../../aspose.pdf.ai/completioncreaterequest/temperature/) { get; set; } | Obtiene o establece qué temperatura de muestreo usar, entre 0 y 2. Valores más altos como 0.8 harán que la salida sea más aleatoria, mientras que valores más bajos como 0.2 la harán más enfocada y determinista. |
| [ToolChoice](../../aspose.pdf.ai/completioncreaterequest/toolchoice/) { get; set; } | Obtiene o establece un objeto que controla qué herramienta (si la hay) es llamada por el modelo. none significa que el modelo no llamará a ninguna herramienta y en su lugar generará un mensaje. auto significa que el modelo puede elegir entre generar un mensaje o llamar a una o más herramientas. required significa que el modelo debe llamar a una o más herramientas. Especificar una herramienta particular a través de {"type": "function", "function": {"name": "my_function"}} obliga al modelo a llamar a esa herramienta. none es el valor predeterminado cuando no hay herramientas presentes. auto es el valor predeterminado si hay herramientas presentes. |
| [Tools](../../aspose.pdf.ai/completioncreaterequest/tools/) { get; set; } | Obtiene o establece una lista de herramientas que el modelo puede llamar. Actualmente, solo se admiten funciones como herramienta. Use esto para proporcionar una lista de funciones para las que el modelo puede generar entradas JSON. Se admiten un máximo de 128 funciones. |
| [TopP](../../aspose.pdf.ai/completioncreaterequest/topp/) { get; set; } | Obtiene o establece una alternativa al muestreo con temperatura, llamada muestreo de núcleo, donde el modelo considera los resultados de los tokens con masa de probabilidad top_p. Así que 0.1 significa que solo se consideran los tokens que comprenden el 10% superior de la masa de probabilidad. |
| [User](../../aspose.pdf.ai/completioncreaterequest/user/) { get; set; } | Obtiene o establece un identificador único que representa a su usuario final, lo que puede ayudar a OpenAI a monitorear y detectar abusos. |

### Ver También

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)