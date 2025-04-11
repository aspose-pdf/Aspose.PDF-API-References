---
title: Class OpenAIChatCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.OpenAIChatCopilotOptions. Представляет параметры для настройки OpenAICopilot
type: docs
weight: 830
url: /ru/net/aspose.pdf.ai/openaichatcopilotoptions/
---
## Класс OpenAIChatCopilotOptions

Представляет параметры для настройки OpenAICopilot.

```csharp
public class OpenAIChatCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IChatCopilotOptions<OpenAIChatCopilotOptions>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/assistantname/) { get; set; } | Получает или задает имя помощника. |
| [ContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/contextbackupjsonpath/) { get; set; } | Получает или задает путь к файлу для резервной копии контекста в формате JSON. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Получает или задает коллекцию документов для обработки. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Получает или задает максимальное количество токенов завершения, которые могут быть использованы в процессе выполнения. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Получает или задает максимальное количество токенов подсказки, которые могут быть использованы в процессе выполнения. |
| virtual [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Получает или задает модель, которую следует использовать для помощника. |
| [RestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/restorecontextfrombackup/) { get; set; } | Получает или задает значение, указывающее, следует ли восстанавливать контекст из резервной копии. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Получает или задает путь к файлу с текстом, содержащим системные инструкции помощника. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Получает или задает температуру выборки, которую следует использовать для модели. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Получает или задает значение top-p для ядерной выборки. |
| [TruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/truncationstrategy/) { get; set; } | Получает или задает стратегию усечения для потока. |
| [VectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/vectorstoreexpiredays/) { get; set; } | Получает или задает количество дней до истечения срока действия векторного хранилища. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create)() | Создает новый экземпляр `OpenAIChatCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create_1)(Action&lt;OpenAIChatCopilotOptions&gt;) | Создает экземпляр `OpenAIChatCopilotOptions` и настраивает его с помощью предоставленного делегата. |
| [GetOptions](../../aspose.pdf.ai/openaichatcopilotoptions/getoptions/)() | Получает текущие `OpenAIChatCopilotOptions`. |
| [WithAssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/withassistantname/)(string) | Устанавливает имя помощника для параметров чат-коопилота. |
| [WithContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/withcontextbackupjsonpath/)(string) | Устанавливает путь к файлу для резервной копии контекста в формате JSON в параметрах чат-коопилота. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument)(PdfDocument) | Добавляет PDF-документ в коллекцию документов для параметров чат-коопилота. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_2)(string) | Добавляет путь к документу в коллекцию документов для параметров чат-коопилота. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_1)(TextDocument) | Добавляет текстовый документ в коллекцию документов для параметров чат-коопилота. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Устанавливает коллекцию документов для параметров чат-коопилота. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Добавляет несколько PDF-документов в коллекцию документов для параметров чат-коопилота. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Добавляет несколько путей к документам в коллекцию документов для параметров чат-коопилота. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Добавляет несколько текстовых документов в коллекцию документов для параметров чат-коопилота. |
| [WithInstructions](../../aspose.pdf.ai/openaichatcopilotoptions/withinstructions/)(string) | Устанавливает инструкции для параметров чат-коопилота. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxcompletiontokens/)(int?) | Устанавливает максимальное количество токенов завершения для параметров чат-коопилота. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxprompttokens/)(int?) | Устанавливает максимальное количество токенов подсказки для параметров чат-коопилота. |
| [WithModel](../../aspose.pdf.ai/openaichatcopilotoptions/withmodel/)(string) | Устанавливает модель для параметров чат-коопилота. |
| [WithRestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/withrestorecontextfrombackup/)(bool) | Устанавливает, следует ли восстанавливать контекст из резервной копии в параметрах чат-коопилота. |
| [WithTemperature](../../aspose.pdf.ai/openaichatcopilotoptions/withtemperature/)(double?) | Устанавливает температуру для параметров чат-коопилота. |
| [WithTopP](../../aspose.pdf.ai/openaichatcopilotoptions/withtopp/)(double?) | Устанавливает значение top P для параметров чат-коопилота. |
| [WithTruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/withtruncationstrategy/)(TruncationStrategy) | Устанавливает стратегию усечения для параметров чат-коопилота. |
| [WithVectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/withvectorstoreexpiredays/)(int) | Устанавливает количество дней до истечения срока действия векторного хранилища в параметрах чат-коопилота. |

### См. также

* класс [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* интерфейс [IChatCopilotOptions&lt;TOptions&gt;](../ichatcopilotoptions-1/)
* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)