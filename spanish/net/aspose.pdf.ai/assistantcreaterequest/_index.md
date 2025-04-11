---
title: Class AssistantCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.AssistantCreateRequest. Objeto de solicitud para crear un asistente
type: docs
weight: 100
url: /es/net/aspose.pdf.ai/assistantcreaterequest/
---
## Clase AssistantCreateRequest

Objeto de solicitud para crear un asistente.

```csharp
public class AssistantCreateRequest
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [AssistantCreateRequest](assistantcreaterequest/)() | El constructor por defecto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Description](../../aspose.pdf.ai/assistantcreaterequest/description/) { get; set; } | Obtiene o establece la descripción del asistente. La longitud máxima es de 512 caracteres. |
| [Instructions](../../aspose.pdf.ai/assistantcreaterequest/instructions/) { get; set; } | Obtiene o establece las instrucciones del sistema que utiliza el asistente. La longitud máxima es de 256,000 caracteres. |
| [Metadata](../../aspose.pdf.ai/assistantcreaterequest/metadata/) { get; set; } | Obtiene o establece un conjunto de 16 pares clave-valor que se pueden adjuntar a un objeto. Esto puede ser útil para almacenar información adicional sobre el objeto en un formato estructurado. Las claves pueden tener un máximo de 64 caracteres y los valores pueden tener un máximo de 512 caracteres. |
| [Model](../../aspose.pdf.ai/assistantcreaterequest/model/) { get; set; } | Obtiene o establece el ID del modelo a utilizar. Puede usar la API de List models para ver todos sus modelos disponibles, o consultar nuestra descripción general del modelo para obtener descripciones de ellos. |
| [Name](../../aspose.pdf.ai/assistantcreaterequest/name/) { get; set; } | Obtiene o establece el nombre del asistente. La longitud máxima es de 256 caracteres. |
| [ResponseFormat](../../aspose.pdf.ai/assistantcreaterequest/responseformat/) { get; set; } | Obtiene o establece el formato que el modelo debe generar. Compatible con GPT-4o, GPT-4 Turbo y todos los modelos GPT-3.5 Turbo desde gpt-3.5-turbo-1106. Establecer en { "type": "json_object" } habilita el modo JSON, que garantiza que el mensaje que genera el modelo sea un JSON válido. Importante: al usar el modo JSON, también debe instruir al modelo para que produzca JSON usted mismo a través de un mensaje del sistema o del usuario. Sin esto, el modelo puede generar un flujo interminable de espacios en blanco hasta que la generación alcance el límite de tokens, lo que resulta en una solicitud de larga duración y aparentemente "atascada". También tenga en cuenta que el contenido del mensaje puede ser parcialmente cortado si finish_reason="length", lo que indica que la generación excedió max_tokens o la conversación excedió la longitud máxima del contexto. |
| [Temperature](../../aspose.pdf.ai/assistantcreaterequest/temperature/) { get; set; } | Obtiene o establece la temperatura de muestreo a utilizar, entre 0 y 2. Valores más altos como 0.8 harán que la salida sea más aleatoria, mientras que valores más bajos como 0.2 la harán más enfocada y determinista. |
| [ToolResources](../../aspose.pdf.ai/assistantcreaterequest/toolresources/) { get; set; } | Obtiene o establece los recursos que son utilizados por las herramientas del asistente. Los recursos son específicos del tipo de herramienta. Por ejemplo, la herramienta code_interpreter requiere una lista de IDs de archivos, mientras que la herramienta file_search requiere una lista de IDs de almacenes de vectores. |
| [Tools](../../aspose.pdf.ai/assistantcreaterequest/tools/) { get; set; } | Obtiene o establece una lista de herramientas habilitadas en el asistente. Puede haber un máximo de 128 herramientas por asistente. Las herramientas pueden ser de los tipos code_interpreter, file_search o function. |
| [TopP](../../aspose.pdf.ai/assistantcreaterequest/topp/) { get; set; } | Obtiene o establece una alternativa al muestreo con temperatura, llamada muestreo de núcleo, donde el modelo considera los resultados de los tokens con masa de probabilidad top_p. Así que 0.1 significa que solo se consideran los tokens que comprenden el 10% superior de la masa de probabilidad. Generalmente recomendamos alterar esto o la temperatura, pero no ambos. |

### Ver También

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)