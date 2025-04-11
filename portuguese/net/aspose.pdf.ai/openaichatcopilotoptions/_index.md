---
title: Class OpenAIChatCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.OpenAIChatCopilotOptions. Representa as opções para configurar o OpenAICopilot
type: docs
weight: 830
url: /pt/net/aspose.pdf.ai/openaichatcopilotoptions/
---
## Classe OpenAIChatCopilotOptions

Representa as opções para configurar o OpenAICopilot.

```csharp
public class OpenAIChatCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IChatCopilotOptions<OpenAIChatCopilotOptions>
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/assistantname/) { get; set; } | Obtém ou define o nome do assistente. |
| [ContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/contextbackupjsonpath/) { get; set; } | Obtém ou define o caminho do arquivo para o backup do JSON de contexto. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Obtém ou define a coleção de documentos a serem processados. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Obtém ou define o número máximo de tokens de conclusão que podem ser usados durante a execução. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Obtém ou define o número máximo de tokens de prompt que podem ser usados durante a execução. |
| virtual [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Obtém ou define o modelo a ser usado para o assistente. |
| [RestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/restorecontextfrombackup/) { get; set; } | Obtém ou define um valor indicando se deve restaurar o contexto do backup. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Obtém ou define o caminho do arquivo para o arquivo de texto contendo as instruções do sistema do assistente. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Obtém ou define a temperatura de amostragem a ser usada para o modelo. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Obtém ou define o valor top-p para amostragem de núcleo. |
| [TruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/truncationstrategy/) { get; set; } | Obtém ou define a estratégia de truncamento para o thread. |
| [VectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/vectorstoreexpiredays/) { get; set; } | Obtém ou define o número de dias antes que o armazenamento de vetores expire. |

## Métodos

| Nome | Descrição |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create)() | Cria uma nova instância de `OpenAIChatCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create_1)(Action&lt;OpenAIChatCopilotOptions&gt;) | Cria uma instância de `OpenAIChatCopilotOptions` e a configura usando o delegado fornecido. |
| [GetOptions](../../aspose.pdf.ai/openaichatcopilotoptions/getoptions/)() | Obtém as atuais `OpenAIChatCopilotOptions`. |
| [WithAssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/withassistantname/)(string) | Define o nome do assistente para as opções do chat copilot. |
| [WithContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/withcontextbackupjsonpath/)(string) | Define o caminho do arquivo para o backup do JSON de contexto nas opções do chat copilot. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument)(PdfDocument) | Adiciona um documento PDF à coleção de documentos para as opções do chat copilot. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_2)(string) | Adiciona um caminho de documento à coleção de documentos para as opções do chat copilot. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_1)(TextDocument) | Adiciona um documento de texto à coleção de documentos para as opções do chat copilot. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Define a coleção de documentos para as opções do chat copilot. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Adiciona múltiplos documentos PDF à coleção de documentos para as opções do chat copilot. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Adiciona múltiplos caminhos de documentos à coleção de documentos para as opções do chat copilot. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Adiciona múltiplos documentos de texto à coleção de documentos para as opções do chat copilot. |
| [WithInstructions](../../aspose.pdf.ai/openaichatcopilotoptions/withinstructions/)(string) | Define as instruções para as opções do chat copilot. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxcompletiontokens/)(int?) | Define os tokens de conclusão máximos para as opções do chat copilot. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxprompttokens/)(int?) | Define os tokens de prompt máximos para as opções do chat copilot. |
| [WithModel](../../aspose.pdf.ai/openaichatcopilotoptions/withmodel/)(string) | Define o modelo para as opções do chat copilot. |
| [WithRestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/withrestorecontextfrombackup/)(bool) | Define se deve restaurar o contexto do backup nas opções do chat copilot. |
| [WithTemperature](../../aspose.pdf.ai/openaichatcopilotoptions/withtemperature/)(double?) | Define a temperatura para as opções do chat copilot. |
| [WithTopP](../../aspose.pdf.ai/openaichatcopilotoptions/withtopp/)(double?) | Define o valor top P para as opções do chat copilot. |
| [WithTruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/withtruncationstrategy/)(TruncationStrategy) | Define a estratégia de truncamento para as opções do chat copilot. |
| [WithVectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/withvectorstoreexpiredays/)(int) | Define o número de dias para a expiração do armazenamento de vetores nas opções do chat copilot. |

### Veja Também

* classe [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IChatCopilotOptions&lt;TOptions&gt;](../ichatcopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)