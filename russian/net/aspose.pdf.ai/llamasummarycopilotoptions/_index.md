---
title: Class LlamaSummaryCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.LlamaSummaryCopilotOptions. Представляет параметры для настройки OpenAICopilot
type: docs
weight: 750
url: /ru/net/aspose.pdf.ai/llamasummarycopilotoptions/
---
## Класс LlamaSummaryCopilotOptions

Представляет параметры для настройки OpenAICopilot.

```csharp
public class LlamaSummaryCopilotOptions : LlamaCopilotOptionsBase, 
    ISummaryCopilotOptions<LlamaSummaryCopilotOptions>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [DocumentCollection](../../aspose.pdf.ai/llamacopilotoptionsbase/documentcollection/) { get; set; } | Получает или задает коллекцию документов для обработки. |
| [MaxCompletionTokens](../../aspose.pdf.ai/llamacopilotoptionsbase/maxcompletiontokens/) { get; set; } | Получает или задает максимальное количество токенов завершения, которые могут быть использованы в ходе выполнения. |
| virtual [Model](../../aspose.pdf.ai/llamacopilotoptionsbase/model/) { get; set; } | Получает или задает модель, которую следует использовать для помощника. |
| [SummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/summaryprompt/) { get; set; } | Получает или задает подсказку для указания модели предоставить резюме документа. |
| [SystemInstructions](../../aspose.pdf.ai/llamacopilotoptionsbase/systeminstructions/) { get; set; } | Получает или задает путь к файлу для текстового файла, содержащего системные инструкции помощника. |
| [Temperature](../../aspose.pdf.ai/llamacopilotoptionsbase/temperature/) { get; set; } | Получает или задает температуру выборки, которую следует использовать для модели. |
| [TopP](../../aspose.pdf.ai/llamacopilotoptionsbase/topp/) { get; set; } | Получает или задает значение top-p для выборки по ядру. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create)() | Создает новый экземпляр `LlamaSummaryCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create_1)(Action&lt;LlamaSummaryCopilotOptions&gt;) | Создает экземпляр `LlamaSummaryCopilotOptions` и настраивает его с помощью предоставленного делегата. |
| [GetOptions](../../aspose.pdf.ai/llamasummarycopilotoptions/getoptions/)() | Получает текущие `LlamaSummaryCopilotOptions`. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | Добавляет PDF-документ в коллекцию документов для параметров резюме помощника. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_2)(string) | Добавляет путь к документу в коллекцию документов для параметров резюме помощника. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | Добавляет текстовый документ в коллекцию документов для параметров резюме помощника. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Устанавливает коллекцию документов для параметров резюме помощника. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Добавляет несколько PDF-документов в коллекцию документов для параметров резюме помощника. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Добавляет несколько путей к документам в коллекцию документов для параметров резюме помощника. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Добавляет несколько текстовых документов в коллекцию документов для параметров резюме помощника. |
| [WithInstructions](../../aspose.pdf.ai/llamasummarycopilotoptions/withinstructions/)(string) | Устанавливает инструкции для параметров резюме помощника. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/llamasummarycopilotoptions/withmaxcompletiontokens/)(int?) | Устанавливает максимальные токены завершения для параметров резюме помощника. |
| [WithModel](../../aspose.pdf.ai/llamasummarycopilotoptions/withmodel/)(string) | Устанавливает модель для параметров резюме помощника. |
| [WithSummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/withsummaryprompt/)(string) | Устанавливает подсказку резюме для параметров резюме помощника. |
| [WithTemperature](../../aspose.pdf.ai/llamasummarycopilotoptions/withtemperature/)(double?) | Устанавливает температуру для параметров резюме помощника. |
| [WithTopP](../../aspose.pdf.ai/llamasummarycopilotoptions/withtopp/)(double?) | Устанавливает значение top P для параметров резюме помощника. |

### См. также

* класс [LlamaCopilotOptionsBase](../llamacopilotoptionsbase/)
* интерфейс [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)