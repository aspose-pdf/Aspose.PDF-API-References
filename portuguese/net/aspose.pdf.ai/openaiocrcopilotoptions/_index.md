---
title: "Classe OpenAIOcrCopilotOptions"
second_title: "Referência da API Aspose.PDF para .NET"
description: "Classe Aspose.Pdf.AI.OpenAIOcrCopilotOptions. Representa as opções para configurar o OpenAIOcrCopilot"
type: docs
weight: 990
url: /pt/net/aspose.pdf.ai/openaiocrcopilotoptions/
---
## OpenAIOcrCopilotOptions class

Representa as opções para configurar o OpenAIOcrCopilot.

```csharp
public class OpenAIOcrCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IOcrCopilotOptions<OpenAIOcrCopilotOptions>
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Detail](../../aspose.pdf.ai/openaiocrcopilotoptions/detail/) { get; set; } | Obtém ou define o nível de detalhe para análise de imagem. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Obtém ou define a coleção de documentos a serem processados. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Obtém ou define o número máximo de tokens de conclusão que podem ser usados ao longo da execução. |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Obtém ou define o modelo a ser usado para o assistente. |
| [Resolution](../../aspose.pdf.ai/openaiocrcopilotoptions/resolution/) { get; set; } | Obtém ou define a resolução usada para converter páginas PDF em imagens. O valor padrão é 300 dpi. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Obtém ou define o caminho do arquivo de texto que contém as instruções do sistema do assistente. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Obtém ou define a temperatura de amostragem a ser usada para o modelo. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Obtém ou define o valor top-p para amostragem de núcleo. |
| [UserInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/userinstructions/) { get; set; } | Obtém ou define o prompt do usuário. |

## Métodos

| Nome | Descrição |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiocrcopilotoptions/create/#create)() | Cria uma nova instância de `OpenAIOcrCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaiocrcopilotoptions/create/#create_1)(Action&lt;OpenAIOcrCopilotOptions&gt;) | Cria uma instância de `OpenAIOcrCopilotOptions` e a configura usando o delegate fornecido. |
| [GetOptions](../../aspose.pdf.ai/openaiocrcopilotoptions/getoptions/)() | Obtém o `OpenAIOcrCopilotOptions` atual. |
| [WithDetail](../../aspose.pdf.ai/openaiocrcopilotoptions/withdetail/)(Detail) | Define o nível de detalhe para a análise de imagens. |
| [WithDocument](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocument/#withdocument)(PdfDocument) | Adiciona um documento PDF à coleção de documentos. |
| [WithDocument](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocument/#withdocument_1)(string) | Adiciona um caminho de documento à coleção de documentos. |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Define a coleção de documentos. |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Adiciona vários documentos PDF à coleção de documentos. |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | Adiciona vários caminhos de documentos à coleção de documentos. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiocrcopilotoptions/withmaxcompletiontokens/)(int?) | Define o número máximo de tokens de conclusão. |
| [WithModel](../../aspose.pdf.ai/openaiocrcopilotoptions/withmodel/)(string) | Define o modelo. |
| [WithResolution](../../aspose.pdf.ai/openaiocrcopilotoptions/withresolution/)(int) | Define a resolução usada para converter páginas PDF em imagens. O valor padrão é 300 dpi. |
| [WithSystemInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/withsysteminstructions/)(string) | Define as instruções para as opções do copilot OCR. |
| [WithTemperature](../../aspose.pdf.ai/openaiocrcopilotoptions/withtemperature/)(double?) | Define a temperatura. |
| [WithTopP](../../aspose.pdf.ai/openaiocrcopilotoptions/withtopp/)(double?) | Define o valor top P. |
| [WithUserInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/withuserinstructions/)(string) | Define o prompt do usuário. |

### Veja Também

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IOcrCopilotOptions&lt;TOptions&gt;](../iocrcopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


