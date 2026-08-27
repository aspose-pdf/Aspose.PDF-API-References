---
title: "Clase OpenAIOcrCopilotOptions"
second_title: "Aspose.PDF para .NET Referencia de API"
description: "Aspose.Pdf.AI.OpenAIOcrCopilotOptions class. Representa las opciones para configurar el OpenAIOcrCopilot"
type: docs
weight: 990
url: /es/net/aspose.pdf.ai/openaiocrcopilotoptions/
---
## OpenAIOcrCopilotOptions class

Representa las opciones para configurar el OpenAIOcrCopilot.

```csharp
public class OpenAIOcrCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IOcrCopilotOptions<OpenAIOcrCopilotOptions>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Detail](../../aspose.pdf.ai/openaiocrcopilotoptions/detail/) { get; set; } | Obtiene o establece el nivel de detalle para el análisis de imágenes. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Obtiene o establece la colección de documentos a procesar. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Obtiene o establece el número máximo de tokens de finalización que pueden usarse durante la ejecución. |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Obtiene o establece el modelo a usar para el asistente. |
| [Resolution](../../aspose.pdf.ai/openaiocrcopilotoptions/resolution/) { get; set; } | Obtiene o establece la resolución utilizada para convertir páginas PDF en imágenes. El valor predeterminado es 300 dpi. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Obtiene o establece la ruta del archivo de texto que contiene las instrucciones del sistema del asistente. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Obtiene o establece la temperatura de muestreo a usar para el modelo. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Obtiene o establece el valor top-p para el muestreo de núcleo. |
| [UserInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/userinstructions/) { get; set; } | Obtiene o establece la solicitud del usuario. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiocrcopilotoptions/create/#create)() | Crea una nueva instancia de `OpenAIOcrCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaiocrcopilotoptions/create/#create_1)(Action&lt;OpenAIOcrCopilotOptions&gt;) | Crea una instancia de `OpenAIOcrCopilotOptions` y la configura usando el delegado proporcionado. |
| [GetOptions](../../aspose.pdf.ai/openaiocrcopilotoptions/getoptions/)() | Obtiene el `OpenAIOcrCopilotOptions` actual. |
| [WithDetail](../../aspose.pdf.ai/openaiocrcopilotoptions/withdetail/)(Detail) | Establece el nivel de detalle para el análisis de imágenes. |
| [WithDocument](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocument/#withdocument)(PdfDocument) | Agrega un documento PDF a la colección de documentos. |
| [WithDocument](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocument/#withdocument_1)(string) | Agrega una ruta de documento a la colección de documentos. |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Establece la colección de documentos. |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Agrega varios documentos PDF a la colección de documentos. |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | Agrega varias rutas de documentos a la colección de documentos. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiocrcopilotoptions/withmaxcompletiontokens/)(int?) | Establece el número máximo de tokens de finalización. |
| [WithModel](../../aspose.pdf.ai/openaiocrcopilotoptions/withmodel/)(string) | Establece el modelo. |
| [WithResolution](../../aspose.pdf.ai/openaiocrcopilotoptions/withresolution/)(int) | Establece la resolución utilizada para convertir páginas PDF en imágenes. El valor predeterminado es 300 dpi. |
| [WithSystemInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/withsysteminstructions/)(string) | Establece las instrucciones para las opciones del copilot OCR. |
| [WithTemperature](../../aspose.pdf.ai/openaiocrcopilotoptions/withtemperature/)(double?) | Establece la temperatura. |
| [WithTopP](../../aspose.pdf.ai/openaiocrcopilotoptions/withtopp/)(double?) | Establece el valor top P. |
| [WithUserInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/withuserinstructions/)(string) | Establece el mensaje del usuario. |

### Ver también

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IOcrCopilotOptions&lt;TOptions&gt;](../iocrcopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


