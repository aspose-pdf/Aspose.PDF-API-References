---
title: Class OpenAIChatCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.OpenAIChatCopilotOptions. Representa las opciones para configurar el OpenAICopilot
type: docs
weight: 830
url: /es/net/aspose.pdf.ai/openaichatcopilotoptions/
---
## Clase OpenAIChatCopilotOptions

Representa las opciones para configurar el OpenAICopilot.

```csharp
public class OpenAIChatCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IChatCopilotOptions<OpenAIChatCopilotOptions>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/assistantname/) { get; set; } | Obtiene o establece el nombre del asistente. |
| [ContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/contextbackupjsonpath/) { get; set; } | Obtiene o establece la ruta del archivo para la copia de seguridad del contexto en JSON. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Obtiene o establece la colección de documentos a procesar. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Obtiene o establece el número máximo de tokens de finalización que se pueden usar durante la ejecución. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Obtiene o establece el número máximo de tokens de aviso que se pueden usar durante la ejecución. |
| virtual [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Obtiene o establece el modelo a utilizar para el asistente. |
| [RestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/restorecontextfrombackup/) { get; set; } | Obtiene o establece un valor que indica si se debe restaurar el contexto desde la copia de seguridad. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Obtiene o establece la ruta del archivo para el archivo de texto que contiene las instrucciones del sistema del asistente. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Obtiene o establece la temperatura de muestreo a utilizar para el modelo. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Obtiene o establece el valor top-p para el muestreo de núcleo. |
| [TruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/truncationstrategy/) { get; set; } | Obtiene o establece la estrategia de truncamiento para el hilo. |
| [VectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/vectorstoreexpiredays/) { get; set; } | Obtiene o establece el número de días antes de que expire el almacén de vectores. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create)() | Crea una nueva instancia de `OpenAIChatCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create_1)(Action&lt;OpenAIChatCopilotOptions&gt;) | Crea una instancia de `OpenAIChatCopilotOptions` y la configura utilizando el delegado proporcionado. |
| [GetOptions](../../aspose.pdf.ai/openaichatcopilotoptions/getoptions/)() | Obtiene las actuales `OpenAIChatCopilotOptions`. |
| [WithAssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/withassistantname/)(string) | Establece el nombre del asistente para las opciones del chat copilot. |
| [WithContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/withcontextbackupjsonpath/)(string) | Establece la ruta del archivo para la copia de seguridad del contexto en JSON en las opciones del chat copilot. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument)(PdfDocument) | Agrega un documento PDF a la colección de documentos para las opciones del chat copilot. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_2)(string) | Agrega una ruta de documento a la colección de documentos para las opciones del chat copilot. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_1)(TextDocument) | Agrega un documento de texto a la colección de documentos para las opciones del chat copilot. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Establece la colección de documentos para las opciones del chat copilot. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Agrega múltiples documentos PDF a la colección de documentos para las opciones del chat copilot. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Agrega múltiples rutas de documentos a la colección de documentos para las opciones del chat copilot. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Agrega múltiples documentos de texto a la colección de documentos para las opciones del chat copilot. |
| [WithInstructions](../../aspose.pdf.ai/openaichatcopilotoptions/withinstructions/)(string) | Establece las instrucciones para las opciones del chat copilot. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxcompletiontokens/)(int?) | Establece los tokens de finalización máximos para las opciones del chat copilot. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxprompttokens/)(int?) | Establece los tokens de aviso máximos para las opciones del chat copilot. |
| [WithModel](../../aspose.pdf.ai/openaichatcopilotoptions/withmodel/)(string) | Establece el modelo para las opciones del chat copilot. |
| [WithRestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/withrestorecontextfrombackup/)(bool) | Establece si se debe restaurar el contexto desde la copia de seguridad en las opciones del chat copilot. |
| [WithTemperature](../../aspose.pdf.ai/openaichatcopilotoptions/withtemperature/)(double?) | Establece la temperatura para las opciones del chat copilot. |
| [WithTopP](../../aspose.pdf.ai/openaichatcopilotoptions/withtopp/)(double?) | Establece el valor top P para las opciones del chat copilot. |
| [WithTruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/withtruncationstrategy/)(TruncationStrategy) | Establece la estrategia de truncamiento para las opciones del chat copilot. |
| [WithVectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/withvectorstoreexpiredays/)(int) | Establece el número de días para la expiración del almacén de vectores en las opciones del chat copilot. |

### Ver También

* clase [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interfaz [IChatCopilotOptions&lt;TOptions&gt;](../ichatcopilotoptions-1/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblaje [Aspose.PDF](../../)