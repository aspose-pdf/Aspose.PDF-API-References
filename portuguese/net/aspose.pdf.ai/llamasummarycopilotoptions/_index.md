---
title: Class LlamaSummaryCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.LlamaSummaryCopilotOptions. Representa as opções para configurar o OpenAICopilot
type: docs
weight: 750
url: /pt/net/aspose.pdf.ai/llamasummarycopilotoptions/
---
## Classe LlamaSummaryCopilotOptions

Representa as opções para configurar o OpenAICopilot.

```csharp
public class LlamaSummaryCopilotOptions : LlamaCopilotOptionsBase, 
    ISummaryCopilotOptions<LlamaSummaryCopilotOptions>
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [DocumentCollection](../../aspose.pdf.ai/llamacopilotoptionsbase/documentcollection/) { get; set; } | Obtém ou define a coleção de documentos a serem processados. |
| [MaxCompletionTokens](../../aspose.pdf.ai/llamacopilotoptionsbase/maxcompletiontokens/) { get; set; } | Obtém ou define o número máximo de tokens de conclusão que podem ser usados durante a execução. |
| virtual [Model](../../aspose.pdf.ai/llamacopilotoptionsbase/model/) { get; set; } | Obtém ou define o modelo a ser usado para o assistente. |
| [SummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/summaryprompt/) { get; set; } | Obtém ou define o prompt para instruir o modelo a fornecer um resumo do documento. |
| [SystemInstructions](../../aspose.pdf.ai/llamacopilotoptionsbase/systeminstructions/) { get; set; } | Obtém ou define o caminho do arquivo para o arquivo de texto contendo as instruções do sistema do assistente. |
| [Temperature](../../aspose.pdf.ai/llamacopilotoptionsbase/temperature/) { get; set; } | Obtém ou define a temperatura de amostragem a ser usada para o modelo. |
| [TopP](../../aspose.pdf.ai/llamacopilotoptionsbase/topp/) { get; set; } | Obtém ou define o valor top-p para amostragem de núcleo. |

## Métodos

| Nome | Descrição |
| --- | --- |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create)() | Cria uma nova instância de `LlamaSummaryCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create_1)(Action&lt;LlamaSummaryCopilotOptions&gt;) | Cria uma instância de `LlamaSummaryCopilotOptions` e a configura usando o delegado fornecido. |
| [GetOptions](../../aspose.pdf.ai/llamasummarycopilotoptions/getoptions/)() | Obtém as atuais `LlamaSummaryCopilotOptions`. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | Adiciona um documento PDF à coleção de documentos para as opções do copilot de resumo. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_2)(string) | Adiciona um caminho de documento à coleção de documentos para as opções do copilot de resumo. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | Adiciona um documento de texto à coleção de documentos para as opções do copilot de resumo. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Define a coleção de documentos para as opções do copilot de resumo. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Adiciona múltiplos documentos PDF à coleção de documentos para as opções do copilot de resumo. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Adiciona múltiplos caminhos de documentos à coleção de documentos para as opções do copilot de resumo. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Adiciona múltiplos documentos de texto à coleção de documentos para as opções do copilot de resumo. |
| [WithInstructions](../../aspose.pdf.ai/llamasummarycopilotoptions/withinstructions/)(string) | Define as instruções para as opções do copilot de resumo. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/llamasummarycopilotoptions/withmaxcompletiontokens/)(int?) | Define os tokens de conclusão máximos para as opções do copilot de resumo. |
| [WithModel](../../aspose.pdf.ai/llamasummarycopilotoptions/withmodel/)(string) | Define o modelo para as opções do copilot de resumo. |
| [WithSummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/withsummaryprompt/)(string) | Define o prompt de resumo para as opções do copilot de resumo. |
| [WithTemperature](../../aspose.pdf.ai/llamasummarycopilotoptions/withtemperature/)(double?) | Define a temperatura para as opções do copilot de resumo. |
| [WithTopP](../../aspose.pdf.ai/llamasummarycopilotoptions/withtopp/)(double?) | Define o valor top P para as opções do copilot de resumo. |

### Veja Também

* classe [LlamaCopilotOptionsBase](../llamacopilotoptionsbase/)
* interface [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)