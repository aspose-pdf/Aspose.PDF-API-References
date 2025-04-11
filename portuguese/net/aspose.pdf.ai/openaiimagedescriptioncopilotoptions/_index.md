---
title: Class OpenAIImageDescriptionCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.OpenAIImageDescriptionCopilotOptions. Representa as opções para configurar o OpenAICopilot
type: docs
weight: 900
url: /pt/net/aspose.pdf.ai/openaiimagedescriptioncopilotoptions/
---
## Classe OpenAIImageDescriptionCopilotOptions

Representa as opções para configurar o OpenAICopilot.

```csharp
public class OpenAIImageDescriptionCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IImageDescriptionCopilotOptions<OpenAIImageDescriptionCopilotOptions>
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/assistantname/) { get; set; } | Obtém ou define o nome do assistente. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Obtém ou define a coleção de documentos a serem processados. |
| [ImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedescriptionprompt/) { get; set; } | Obtém ou define o prompt para instruir o modelo a fornecer a descrição da imagem. |
| [ImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedetail/) { get; set; } | Obtém ou define o nível de detalhe da imagem, se especificado pelo usuário. "low" usa menos tokens, você pode optar por alta resolução usando "high". Se não definido, o padrão é "auto". |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Obtém ou define o número máximo de tokens de conclusão que podem ser usados durante a execução. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Obtém ou define o número máximo de tokens de prompt que podem ser usados durante a execução. |
| override [Model](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/model/) { get; set; } | Obtém ou define o modelo de visão a ser usado para o assistente. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Obtém ou define o caminho do arquivo para o arquivo de texto contendo as instruções do sistema do assistente. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Obtém ou define a temperatura de amostragem a ser usada para o modelo. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Obtém ou define o valor top-p para amostragem de núcleo. |

## Métodos

| Nome | Descrição |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create)() | Cria uma nova instância de `OpenAIImageDescriptionCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create_1)(Action&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Cria uma instância de `OpenAIImageDescriptionCopilotOptions` e a configura usando o delegado fornecido. |
| [GetOptions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/getoptions/)() | Obtém as atuais `OpenAIImageDescriptionCopilotOptions`. |
| [WithAssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withassistantname/)(string) | Define o nome do assistente para as opções do copilot de descrição de imagem. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument)(PdfDocument) | Adiciona um documento PDF à coleção de documentos para as opções do copilot de descrição de imagem. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument_1)(string) | Adiciona um caminho de documento à coleção de documentos para as opções do copilot de descrição de imagem. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Define a coleção de documentos para as opções do copilot de descrição de imagem. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Adiciona vários documentos PDF à coleção de documentos para as opções do copilot de descrição de imagem. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | Adiciona vários caminhos de documentos à coleção de documentos para as opções do copilot de descrição de imagem. |
| [WithImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedescriptionprompt/)(string) | Define o prompt para as opções do copilot de descrição de imagem. |
| [WithImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedetail/)(string) | Define o nível de detalhe da imagem. |
| [WithInstructions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withinstructions/)(string) | Define as instruções para as opções do copilot de descrição de imagem. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxcompletiontokens/)(int?) | Define os tokens de conclusão máximos para as opções do copilot de descrição de imagem. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxprompttokens/)(int?) | Define os tokens de prompt máximos para as opções do copilot de descrição de imagem. |
| [WithModel](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmodel/)(string) | Define o modelo para as opções do copilot de descrição de imagem. |
| [WithTemperature](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtemperature/)(double?) | Define a temperatura para as opções do copilot de descrição de imagem. |
| [WithTopP](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtopp/)(double?) | Define o valor top P para as opções do copilot de descrição de imagem. |

### Veja Também

* classe [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IImageDescriptionCopilotOptions&lt;TOptions&gt;](../iimagedescriptioncopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)