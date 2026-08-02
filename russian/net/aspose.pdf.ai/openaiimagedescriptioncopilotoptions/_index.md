---
title: "Класс OpenAIImageDescriptionCopilotOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.AI.OpenAIImageDescriptionCopilotOptions. Представляет параметры настройки OpenAICopilot"
type: docs
weight: 960
url: /ru/net/aspose.pdf.ai/openaiimagedescriptioncopilotoptions/
---
## OpenAIImageDescriptionCopilotOptions class

Представляет параметры настройки OpenAICopilot.

```csharp
public class OpenAIImageDescriptionCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IImageDescriptionCopilotOptions<OpenAIImageDescriptionCopilotOptions>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/assistantname/) { get; set; } | Получает или задает имя помощника. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Получает или задаёт коллекцию документов для обработки. |
| [ImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedescriptionprompt/) { get; set; } | Получает или задает подсказку, инструктирующую модель предоставить описание изображения. |
| [ImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedetail/) { get; set; } | Получает или задает уровень детализации изображения, если он указан пользователем. "low" использует меньше токенов, вы можете выбрать высокое разрешение, используя "high". Если не задано, по умолчанию используется "auto". |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Получает или задаёт максимальное количество токенов завершения, которые могут быть использованы в ходе выполнения. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/maxprompttokens/) { get; set; } | Получает или задает максимальное количество токенов подсказки, которое может быть использовано в течение выполнения. |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Получает или задаёт модель, используемую для помощника. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Получает или задаёт путь к файлу текста, содержащему системные инструкции помощника. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Получает или задаёт температуру выборки, используемую для модели. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Получает или задаёт значение top-p для ядерной выборки. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create)() | Создаёт новый экземпляр `OpenAIImageDescriptionCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create_1)(Action&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Создаёт экземпляр `OpenAIImageDescriptionCopilotOptions` и настраивает его с помощью предоставленного делегата. |
| [GetOptions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/getoptions/)() | Получает текущий `OpenAIImageDescriptionCopilotOptions`. |
| [WithAssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withassistantname/)(string) | Задаёт имя помощника для параметров копилота описания изображения. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument)(PdfDocument) | Добавляет PDF‑документ в коллекцию документов для параметров копилота описания изображения. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument_1)(string) | Добавляет путь к документу в коллекцию документов для параметров копилота описания изображения. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Задаёт коллекцию документов для параметров копилота описания изображения. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Добавляет несколько PDF‑документов в коллекцию документов для параметров копилота описания изображения. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | Добавляет несколько путей к документам в коллекцию документов для параметров копилота описания изображения. |
| [WithImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedescriptionprompt/)(string) | Задаёт подсказку для параметров копилота описания изображения. |
| [WithImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedetail/)(string) | Задаёт уровень детализации изображения. |
| [WithInstructions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withinstructions/)(string) | Задаёт инструкции для параметров копилота описания изображения. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxcompletiontokens/)(int?) | Задаёт максимальное количество токенов завершения для параметров копилота описания изображения. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxprompttokens/)(int?) | Задаёт максимальное количество токенов подсказки для параметров копилота описания изображения. |
| [WithModel](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmodel/)(string) | Устанавливает модель для параметров помощника описания изображения. |
| [WithTemperature](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtemperature/)(double?) | Устанавливает температуру для параметров помощника описания изображения. |
| [WithTopP](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtopp/)(double?) | Устанавливает значение top P для параметров помощника описания изображения. |

### См. также

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IImageDescriptionCopilotOptions&lt;TOptions&gt;](../iimagedescriptioncopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


