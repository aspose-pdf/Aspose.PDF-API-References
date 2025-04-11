---
title: Class RunResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.RunResponse. Representa uma execução em uma thread
type: docs
weight: 1020
url: /pt/net/aspose.pdf.ai/runresponse/
---
## Classe RunResponse

Representa uma execução em uma thread.

```csharp
public class RunResponse : BaseResponse, IStatus
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [RunResponse](runresponse/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runresponse/assistantid/) { get; set; } | Obtém ou define o ID do assistente usado para a execução desta execução. |
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) para quando a execução foi cancelada. |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) para quando a execução foi concluída. |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) para quando a execução foi criada. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtém ou define os detalhes da resposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtém ou define o erro da resposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtém ou define as informações de erro. |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) para quando a execução irá expirar. |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) para quando a execução falhou. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtém ou define os cabeçalhos da resposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtém ou define o código de status HTTP. |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | Obtém ou define o identificador, que pode ser referenciado em endpoints da API. |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | Obtém ou define os detalhes sobre o motivo pelo qual a execução está incompleta. Será nulo se a execução não estiver incompleta. |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | Obtém ou define as instruções que o assistente usou para esta execução. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se a resposta foi bem-sucedida. |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | Obtém ou define o último erro associado a esta execução. Será nulo se não houver erros. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | Obtém ou define o número máximo de tokens de conclusão especificados que foram usados ao longo da execução. |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | Obtém ou define o número máximo de tokens de prompt especificados que foram usados ao longo da execução. |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | Obtém ou define um conjunto de 16 pares chave-valor que podem ser anexados a um objeto. Isso pode ser útil para armazenar informações adicionais sobre o objeto em um formato estruturado. As chaves podem ter no máximo 64 caracteres e os valores podem ter no máximo 512 caracteres. |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | Obtém ou define o modelo que o assistente usou para esta execução. |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | Obtém ou define o tipo de objeto, que é sempre thread.run. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtém a frase de razão do erro. |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | Obtém ou define os detalhes sobre a ação necessária para continuar a execução. Será nulo se nenhuma ação for necessária. |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | Obtém ou define o formato que o modelo deve gerar. Compatível com GPT-4o, GPT-4 Turbo e todos os modelos GPT-3.5 Turbo desde gpt-3.5-turbo-1106. Definir como { "type": "json_object" } ativa o modo JSON, que garante que a mensagem gerada pelo modelo seja um JSON válido. Importante: ao usar o modo JSON, você também deve instruir o modelo a produzir JSON você mesmo por meio de uma mensagem de sistema ou de usuário. Sem isso, o modelo pode gerar um fluxo interminável de espaços em branco até que a geração atinja o limite de tokens, resultando em uma solicitação de longa duração e aparentemente "travada". Também observe que o conteúdo da mensagem pode ser parcialmente cortado se finish_reason="length", o que indica que a geração excedeu max_tokens ou a conversa excedeu o comprimento máximo do contexto. |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) para quando a execução foi iniciada. |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | Obtém ou define o status da execução, que pode ser queued, in_progress, requires_action, cancelling, cancelled, failed, completed, incomplete ou expired. |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | Obtém ou define a temperatura de amostragem usada para esta execução. Se não definido, o padrão é 1. |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | Obtém ou define o ID da thread que foi executada como parte desta execução. |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | Obtém ou define qual (se houver) ferramenta é chamada pelo modelo. none significa que o modelo não chamará nenhuma ferramenta e, em vez disso, gerará uma mensagem. auto é o valor padrão e significa que o modelo pode escolher entre gerar uma mensagem ou chamar uma ou mais ferramentas. required significa que o modelo deve chamar uma ou mais ferramentas antes de responder ao usuário. Especificar uma ferramenta particular como {"type": "file_search"} ou {"type": "function", "function": {"name": "my_function"}} força o modelo a chamar essa ferramenta. |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | Obtém ou define a lista de ferramentas que o assistente usou para esta execução. |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | Obtém ou define o valor de amostragem de núcleo usado para esta execução. Se não definido, o padrão é 1. |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | Obtém ou define a estratégia de truncamento que controla como uma thread será truncada antes da execução. Use isso para controlar a janela de contexto inicial da execução. |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | Obtém ou define as estatísticas de uso relacionadas à execução. Este valor será nulo se a execução não estiver em um estado terminal (ou seja, in_progress, queued, etc.). |

### Veja Também

* classe [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)