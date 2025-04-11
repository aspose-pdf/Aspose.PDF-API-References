---
title: Class OpenAISummaryCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.OpenAISummaryCopilotOptions. Representa las opciones para configurar el OpenAICopilot
type: docs
weight: 930
url: /es/net/aspose.pdf.ai/openaisummarycopilotoptions/
---
## Clase OpenAISummaryCopilotOptions

Representa las opciones para configurar el OpenAICopilot.

```csharp
public class OpenAISummaryCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    ISummaryCopilotOptions<OpenAISummaryCopilotOptions>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/assistantname/) { get; set; } | Obtiene o establece el nombre del asistente. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Obtiene o establece la colección de documentos a procesar. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Obtiene o establece el número máximo de tokens de finalización que se pueden usar durante la ejecución. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Obtiene o establece el número máximo de tokens de aviso que se pueden usar durante la ejecución. |
| virtual [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Obtiene o establece el modelo a utilizar para el asistente. |
| [SummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/summaryprompt/) { get; set; } | Obtiene o establece el aviso para instruir al modelo a proporcionar un resumen del documento. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Obtiene o establece la ruta del archivo para el archivo de texto que contiene las instrucciones del sistema del asistente. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Obtiene o establece la temperatura de muestreo a utilizar para el modelo. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Obtiene o establece el valor top-p para el muestreo de núcleo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create)() | Crea una nueva instancia de `OpenAISummaryCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create_1)(Action&lt;OpenAISummaryCopilotOptions&gt;) | Crea una instancia de `OpenAISummaryCopilotOptions` y la configura utilizando el delegado proporcionado. |
| [GetOptions](../../aspose.pdf.ai/openaisummarycopilotoptions/getoptions/)() | Obtiene las actuales `OpenAISummaryCopilotOptions`. |
| [WithAssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/withassistantname/)(string) | Establece el nombre del asistente para las opciones del copiloto de resumen. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | Agrega un documento PDF a la colección de documentos para las opciones del copiloto de resumen. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_2)(string) | Agrega una ruta de documento a la colección de documentos para las opciones del copiloto de resumen. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | Agrega un documento de texto a la colección de documentos para las opciones del copiloto de resumen. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Establece la colección de documentos para las opciones del copiloto de resumen. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Agrega múltiples documentos PDF a la colección de documentos para las opciones del copiloto de resumen. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Agrega múltiples rutas de documentos a la colección de documentos para las opciones del copiloto de resumen. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Agrega múltiples documentos de texto a la colección de documentos para las opciones del copiloto de resumen. |
| [WithInstructions](../../aspose.pdf.ai/openaisummarycopilotoptions/withinstructions/)(string) | Establece las instrucciones para las opciones del copiloto de resumen. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxcompletiontokens/)(int?) | Establece los tokens de finalización máximos para las opciones del copiloto de resumen. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxprompttokens/)(int?) | Establece los tokens de aviso máximos para las opciones del copiloto de resumen. |
| [WithModel](../../aspose.pdf.ai/openaisummarycopilotoptions/withmodel/)(string) | Establece el modelo para las opciones del copiloto de resumen. |
| [WithSummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/withsummaryprompt/)(string) | Establece el aviso de resumen para las opciones del copiloto de resumen. |
| [WithTemperature](../../aspose.pdf.ai/openaisummarycopilotoptions/withtemperature/)(double?) | Establece la temperatura para las opciones del copiloto de resumen. |
| [WithTopP](../../aspose.pdf.ai/openaisummarycopilotoptions/withtopp/)(double?) | Establece el valor top P para las opciones del copiloto de resumen. |

### Ver También

* clase [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interfaz [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblaje [Aspose.PDF](../../)