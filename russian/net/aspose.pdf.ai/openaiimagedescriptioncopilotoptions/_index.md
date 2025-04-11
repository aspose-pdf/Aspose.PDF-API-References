---
title: Class OpenAIImageDescriptionCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.OpenAIImageDescriptionCopilotOptions. Представляет параметры для настройки OpenAICopilot
type: docs
weight: 900
url: /ru/net/aspose.pdf.ai/openaiimagedescriptioncopilotoptions/
---
## OpenAIImageDescriptionCopilotOptions class

Представляет параметры для настройки OpenAICopilot.

```csharp
public class OpenAIImageDescriptionCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IImageDescriptionCopilotOptions<OpenAIImageDescriptionCopilotOptions>
```

## Properties

| Name | Description |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/assistantname/) { get; set; } | Получает или задает имя помощника. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Получает или задает коллекцию документов для обработки. |
| [ImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedescriptionprompt/) { get; set; } | Получает или задает подсказку для инструкции модели по предоставлению описания изображения. |
| [ImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedetail/) { get; set; } | Получает или задает уровень детализации изображения, если это указано пользователем. "low" использует меньше токенов, вы можете выбрать высокое разрешение, используя "high". Если не задано, по умолчанию используется "auto". |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Получает или задает максимальное количество токенов завершения, которые могут быть использованы в процессе выполнения. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Получает или задает максимальное количество токенов подсказки, которые могут быть использованы в процессе выполнения. |
| override [Model](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/model/) { get; set; } | Получает или задает модель зрения, которую следует использовать для помощника. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Получает или задает путь к файлу для текстового файла, содержащего системные инструкции помощника. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Получает или задает температуру выборки, которую следует использовать для модели. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Получает или задает значение top-p для ядерной выборки. |

## Methods

| Name | Description |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create)() | Создает новый экземпляр `OpenAIImageDescriptionCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create_1)(Action&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Создает экземпляр `OpenAIImageDescriptionCopilotOptions` и настраивает его с помощью предоставленного делегата. |
| [GetOptions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/getoptions/)() | Получает текущий `OpenAIImageDescriptionCopilotOptions`. |
| [WithAssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withassistantname/)(string) | Устанавливает имя помощника для параметров копилота описания изображения. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument)(PdfDocument) | Добавляет PDF-документ в коллекцию документов для параметров копилота описания изображения. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument_1)(string) | Добавляет путь к документу в коллекцию документов для параметров копилота описания изображения. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Устанавливает коллекцию документов для параметров копилота описания изображения. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Добавляет несколько PDF-документов в коллекцию документов для параметров копилота описания изображения. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | Добавляет несколько путей к документам в коллекцию документов для параметров копилота описания изображения. |
| [WithImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedescriptionprompt/)(string) | Устанавливает подсказку для параметров копилота описания изображения. |
| [WithImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedetail/)(string) | Устанавливает уровень детализации изображения. |
| [WithInstructions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withinstructions/)(string) | Устанавливает инструкции для параметров копилота описания изображения. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxcompletiontokens/)(int?) | Устанавливает максимальное количество токенов завершения для параметров копилота описания изображения. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxprompttokens/)(int?) | Устанавливает максимальное количество токенов подсказки для параметров копилота описания изображения. |
| [WithModel](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmodel/)(string) | Устанавливает модель для параметров копилота описания изображения. |
| [WithTemperature](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtemperature/)(double?) | Устанавливает температуру для параметров копилота описания изображения. |
| [WithTopP](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtopp/)(double?) | Устанавливает значение top P для параметров копилота описания изображения. |

### See Also

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IImageDescriptionCopilotOptions&lt;TOptions&gt;](../iimagedescriptioncopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)