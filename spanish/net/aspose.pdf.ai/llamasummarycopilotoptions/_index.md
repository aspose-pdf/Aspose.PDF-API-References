---
title: Class LlamaSummaryCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.LlamaSummaryCopilotOptions. Representa las opciones para configurar el OpenAICopilot
type: docs
weight: 750
url: /es/net/aspose.pdf.ai/llamasummarycopilotoptions/
---
## Clase LlamaSummaryCopilotOptions

Representa las opciones para configurar el OpenAICopilot.

```csharp
public class LlamaSummaryCopilotOptions : LlamaCopilotOptionsBase, 
    ISummaryCopilotOptions<LlamaSummaryCopilotOptions>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DocumentCollection](../../aspose.pdf.ai/llamacopilotoptionsbase/documentcollection/) { get; set; } | Obtiene o establece la colección de documentos a procesar. |
| [MaxCompletionTokens](../../aspose.pdf.ai/llamacopilotoptionsbase/maxcompletiontokens/) { get; set; } | Obtiene o establece el número máximo de tokens de finalización que se pueden usar durante la ejecución. |
| virtual [Model](../../aspose.pdf.ai/llamacopilotoptionsbase/model/) { get; set; } | Obtiene o establece el modelo a utilizar para el asistente. |
| [SummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/summaryprompt/) { get; set; } | Obtiene o establece el aviso para instruir al modelo a proporcionar un resumen del documento. |
| [SystemInstructions](../../aspose.pdf.ai/llamacopilotoptionsbase/systeminstructions/) { get; set; } | Obtiene o establece la ruta del archivo para el archivo de texto que contiene las instrucciones del sistema del asistente. |
| [Temperature](../../aspose.pdf.ai/llamacopilotoptionsbase/temperature/) { get; set; } | Obtiene o establece la temperatura de muestreo a utilizar para el modelo. |
| [TopP](../../aspose.pdf.ai/llamacopilotoptionsbase/topp/) { get; set; } | Obtiene o establece el valor top-p para el muestreo de núcleo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create)() | Crea una nueva instancia de `LlamaSummaryCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create_1)(Action&lt;LlamaSummaryCopilotOptions&gt;) | Crea una instancia de `LlamaSummaryCopilotOptions` y la configura utilizando el delegado proporcionado. |
| [GetOptions](../../aspose.pdf.ai/llamasummarycopilotoptions/getoptions/)() | Obtiene las actuales `LlamaSummaryCopilotOptions`. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | Agrega un documento PDF a la colección de documentos para las opciones del copilot de resumen. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_2)(string) | Agrega una ruta de documento a la colección de documentos para las opciones del copilot de resumen. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | Agrega un documento de texto a la colección de documentos para las opciones del copilot de resumen. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Establece la colección de documentos para las opciones del copilot de resumen. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Agrega múltiples documentos PDF a la colección de documentos para las opciones del copilot de resumen. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Agrega múltiples rutas de documentos a la colección de documentos para las opciones del copilot de resumen. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Agrega múltiples documentos de texto a la colección de documentos para las opciones del copilot de resumen. |
| [WithInstructions](../../aspose.pdf.ai/llamasummarycopilotoptions/withinstructions/)(string) | Establece las instrucciones para las opciones del copilot de resumen. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/llamasummarycopilotoptions/withmaxcompletiontokens/)(int?) | Establece los tokens de finalización máximos para las opciones del copilot de resumen. |
| [WithModel](../../aspose.pdf.ai/llamasummarycopilotoptions/withmodel/)(string) | Establece el modelo para las opciones del copilot de resumen. |
| [WithSummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/withsummaryprompt/)(string) | Establece el aviso de resumen para las opciones del copilot de resumen. |
| [WithTemperature](../../aspose.pdf.ai/llamasummarycopilotoptions/withtemperature/)(double?) | Establece la temperatura para las opciones del copilot de resumen. |
| [WithTopP](../../aspose.pdf.ai/llamasummarycopilotoptions/withtopp/)(double?) | Establece el valor top P para las opciones del copilot de resumen. |

### Véase también

* clase [LlamaCopilotOptionsBase](../llamacopilotoptionsbase/)
* interfaz [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../)