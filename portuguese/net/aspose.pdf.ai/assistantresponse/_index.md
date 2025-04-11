---
title: Class AssistantResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.AssistantResponse. Representa um assistente que pode chamar o modelo e usar ferramentas
type: docs
weight: 140
url: /pt/net/aspose.pdf.ai/assistantresponse/
---
## Classe AssistantResponse

Representa um assistente que pode chamar o modelo e usar ferramentas.

```csharp
public class AssistantResponse : BaseResponse
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [AssistantResponse](assistantresponse/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/assistantresponse/createdat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) de quando o assistente foi criado. |
| [Description](../../aspose.pdf.ai/assistantresponse/description/) { get; set; } | Obtém ou define a descrição do assistente. O comprimento máximo é 512 caracteres. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtém ou define o detalhe da resposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtém ou define o erro da resposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtém ou define as informações de erro. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtém ou define os cabeçalhos da resposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtém ou define o código de status HTTP. |
| [Id](../../aspose.pdf.ai/assistantresponse/id/) { get; set; } | Obtém ou define o identificador, que pode ser referenciado em endpoints da API. |
| [Instructions](../../aspose.pdf.ai/assistantresponse/instructions/) { get; set; } | Obtém ou define as instruções do sistema que o assistente usa. O comprimento máximo é 256.000 caracteres. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se a resposta foi bem-sucedida. |
| [Metadata](../../aspose.pdf.ai/assistantresponse/metadata/) { get; set; } | Obtém ou define um conjunto de 16 pares chave-valor que podem ser anexados a um objeto. Isso pode ser útil para armazenar informações adicionais sobre o objeto em um formato estruturado. As chaves podem ter no máximo 64 caracteres e os valores podem ter no máximo 512 caracteres. |
| [Model](../../aspose.pdf.ai/assistantresponse/model/) { get; set; } | Obtém ou define o ID do modelo a ser usado. Você pode usar a API List models para ver todos os seus modelos disponíveis ou consultar nossa visão geral do Modelo para descrições deles. |
| [Name](../../aspose.pdf.ai/assistantresponse/name/) { get; set; } | Obtém ou define o nome do assistente. O comprimento máximo é 256 caracteres. |
| [Object](../../aspose.pdf.ai/assistantresponse/object/) { get; set; } | Obtém ou define o tipo de objeto, que é sempre assistente. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtém a frase de razão do erro. |
| [ResponseFormat](../../aspose.pdf.ai/assistantresponse/responseformat/) { get; set; } | Obtém ou define o formato que o modelo deve gerar. Compatível com GPT-4o, GPT-4 Turbo e todos os modelos GPT-3.5 Turbo desde gpt-3.5-turbo-1106. Definir como { "type": "json_object" } ativa o modo JSON, que garante que a mensagem gerada pelo modelo seja um JSON válido. Importante: ao usar o modo JSON, você também deve instruir o modelo a produzir JSON você mesmo por meio de uma mensagem de sistema ou de usuário. Sem isso, o modelo pode gerar um fluxo interminável de espaços em branco até que a geração atinja o limite de tokens, resultando em uma solicitação de longa duração e aparentemente "travada". Também observe que o conteúdo da mensagem pode ser parcialmente cortado se finish_reason="length", o que indica que a geração excedeu max_tokens ou a conversa excedeu o comprimento máximo do contexto. |
| [Temperature](../../aspose.pdf.ai/assistantresponse/temperature/) { get; set; } | Obtém ou define qual temperatura de amostragem usar, entre 0 e 2. Valores mais altos, como 0.8, tornarão a saída mais aleatória, enquanto valores mais baixos, como 0.2, a tornarão mais focada e determinística. |
| [ToolResources](../../aspose.pdf.ai/assistantresponse/toolresources/) { get; set; } | Obtém ou define um conjunto de recursos que são usados pelas ferramentas do assistente. Os recursos são específicos para o tipo de ferramenta. Por exemplo, a ferramenta code_interpreter requer uma lista de IDs de arquivos, enquanto a ferramenta file_search requer uma lista de IDs de armazenamento vetorial. |
| [Tools](../../aspose.pdf.ai/assistantresponse/tools/) { get; set; } | Obtém ou define uma lista de ferramentas habilitadas no assistente. Pode haver um máximo de 128 ferramentas por assistente. As ferramentas podem ser dos tipos code_interpreter, file_search ou function. |
| [TopP](../../aspose.pdf.ai/assistantresponse/topp/) { get; set; } | Obtém ou define uma alternativa à amostragem com temperatura, chamada amostragem de núcleo, onde o modelo considera os resultados dos tokens com massa de probabilidade top_p. Assim, 0.1 significa que apenas os tokens que compõem os 10% principais da massa de probabilidade são considerados. Geralmente, recomendamos alterar isso ou a temperatura, mas não ambos. |

### Veja Também

* classe [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)