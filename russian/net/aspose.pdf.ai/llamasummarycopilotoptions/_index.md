---
title: "Класс LlamaSummaryCopilotOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.AI.LlamaSummaryCopilotOptions. Представляет параметры для настройки OpenAICopilot"
type: docs
weight: 800
url: /ru/net/aspose.pdf.ai/llamasummarycopilotoptions/
---
## LlamaSummaryCopilotOptions class

Представляет параметры настройки OpenAICopilot.

```csharp
public class LlamaSummaryCopilotOptions : LlamaCopilotOptionsBase, 
    ISummaryCopilotOptions<LlamaSummaryCopilotOptions>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [DocumentCollection](../../aspose.pdf.ai/llamacopilotoptionsbase/documentcollection/) { get; set; } | Получает или задаёт коллекцию документов для обработки. |
| [MaxCompletionTokens](../../aspose.pdf.ai/llamacopilotoptionsbase/maxcompletiontokens/) { get; set; } | Получает или задаёт максимальное количество токенов завершения, которые могут быть использованы в ходе выполнения. |
| virtual [Model](../../aspose.pdf.ai/llamacopilotoptionsbase/model/) { get; set; } | Получает или задаёт модель, используемую для помощника. |
| [SummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/summaryprompt/) { get; set; } | Получает или задает подсказку, инструктирующую модель предоставить резюме документа. |
| [SystemInstructions](../../aspose.pdf.ai/llamacopilotoptionsbase/systeminstructions/) { get; set; } | Получает или задаёт путь к файлу текста, содержащему системные инструкции помощника. |
| [Temperature](../../aspose.pdf.ai/llamacopilotoptionsbase/temperature/) { get; set; } | Получает или задаёт температуру выборки, используемую для модели. |
| [TopP](../../aspose.pdf.ai/llamacopilotoptionsbase/topp/) { get; set; } | Получает или задаёт значение top-p для ядерной выборки. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create)() | Создаёт новый экземпляр `LlamaSummaryCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create_1)(Action&lt;LlamaSummaryCopilotOptions&gt;) | Создаёт экземпляр `LlamaSummaryCopilotOptions` и настраивает его с помощью предоставленного делегата. |
| [GetOptions](../../aspose.pdf.ai/llamasummarycopilotoptions/getoptions/)() | Получает текущий `LlamaSummaryCopilotOptions`. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | Добавляет PDF‑документ в коллекцию документов для параметров сводного копилота. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_2)(string) | Добавляет путь к документу в коллекцию документов для параметров сводного копилота. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | Добавляет текстовый документ в коллекцию документов для параметров сводного копилота. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Задает коллекцию документов для параметров сводного копилота. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Добавляет несколько PDF‑документов в коллекцию документов для параметров сводного копилота. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Добавляет несколько путей к документам в коллекцию документов для параметров сводного копилота. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Добавляет несколько текстовых документов в коллекцию документов для параметров сводного копилота. |
| [WithInstructions](../../aspose.pdf.ai/llamasummarycopilotoptions/withinstructions/)(string) | Задает инструкции для параметров сводного копилота. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/llamasummarycopilotoptions/withmaxcompletiontokens/)(int?) | Устанавливает максимальное количество токенов завершения для параметров сопилота резюме. |
| [WithModel](../../aspose.pdf.ai/llamasummarycopilotoptions/withmodel/)(string) | Устанавливает модель для параметров сопилота резюме. |
| [WithSummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/withsummaryprompt/)(string) | Устанавливает подсказку сводки для параметров сопилота резюме. |
| [WithTemperature](../../aspose.pdf.ai/llamasummarycopilotoptions/withtemperature/)(double?) | Устанавливает температуру для параметров сопилота резюме. |
| [WithTopP](../../aspose.pdf.ai/llamasummarycopilotoptions/withtopp/)(double?) | Устанавливает значение top P для параметров сопилота резюме. |

### См. также

* class [LlamaCopilotOptionsBase](../llamacopilotoptionsbase/)
* interface [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


