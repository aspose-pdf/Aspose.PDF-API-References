---
title: Class OpenAIImageDescriptionCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.OpenAIImageDescriptionCopilotOptions. Representa las opciones para configurar el OpenAICopilot
type: docs
weight: 900
url: /es/net/aspose.pdf.ai/openaiimagedescriptioncopilotoptions/
---
## Clase OpenAIImageDescriptionCopilotOptions

Representa las opciones para configurar el OpenAICopilot.

```csharp
public class OpenAIImageDescriptionCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IImageDescriptionCopilotOptions<OpenAIImageDescriptionCopilotOptions>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/assistantname/) { get; set; } | Obtiene o establece el nombre del asistente. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Obtiene o establece la colección de documentos a procesar. |
| [ImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedescriptionprompt/) { get; set; } | Obtiene o establece el aviso para instruir al modelo a proporcionar la descripción de la imagen. |
| [ImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedetail/) { get; set; } | Obtiene o establece el nivel de detalle de la imagen si es especificado por el usuario. "bajo" utiliza menos tokens, puedes optar por alta resolución usando "alto". Si no se establece, por defecto es "automático". |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Obtiene o establece el número máximo de tokens de finalización que pueden ser utilizados durante la ejecución. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Obtiene o establece el número máximo de tokens de aviso que pueden ser utilizados durante la ejecución. |
| override [Model](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/model/) { get; set; } | Obtiene o establece el modelo de visión a utilizar para el asistente. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Obtiene o establece la ruta del archivo para el archivo de texto que contiene las instrucciones del sistema del asistente. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Obtiene o establece la temperatura de muestreo a utilizar para el modelo. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Obtiene o establece el valor top-p para el muestreo de núcleo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create)() | Crea una nueva instancia de `OpenAIImageDescriptionCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create_1)(Action&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Crea una instancia de `OpenAIImageDescriptionCopilotOptions` y la configura utilizando el delegado proporcionado. |
| [GetOptions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/getoptions/)() | Obtiene las actuales `OpenAIImageDescriptionCopilotOptions`. |
| [WithAssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withassistantname/)(string) | Establece el nombre del asistente para las opciones del copiloto de descripción de imagen. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument)(PdfDocument) | Agrega un documento PDF a la colección de documentos para las opciones del copiloto de descripción de imagen. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument_1)(string) | Agrega una ruta de documento a la colección de documentos para las opciones del copiloto de descripción de imagen. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Establece la colección de documentos para las opciones del copiloto de descripción de imagen. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Agrega múltiples documentos PDF a la colección de documentos para las opciones del copiloto de descripción de imagen. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | Agrega múltiples rutas de documentos a la colección de documentos para las opciones del copiloto de descripción de imagen. |
| [WithImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedescriptionprompt/)(string) | Establece el aviso para las opciones del copiloto de descripción de imagen. |
| [WithImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedetail/)(string) | Establece el nivel de detalle de la imagen. |
| [WithInstructions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withinstructions/)(string) | Establece las instrucciones para las opciones del copiloto de descripción de imagen. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxcompletiontokens/)(int?) | Establece los tokens de finalización máximos para las opciones del copiloto de descripción de imagen. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxprompttokens/)(int?) | Establece los tokens de aviso máximos para las opciones del copiloto de descripción de imagen. |
| [WithModel](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmodel/)(string) | Establece el modelo para las opciones del copiloto de descripción de imagen. |
| [WithTemperature](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtemperature/)(double?) | Establece la temperatura para las opciones del copiloto de descripción de imagen. |
| [WithTopP](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtopp/)(double?) | Establece el valor top P para las opciones del copiloto de descripción de imagen. |

### Ver También

* clase [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interfaz [IImageDescriptionCopilotOptions&lt;TOptions&gt;](../iimagedescriptioncopilotoptions-1/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../)