---
title: Class RunStepResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.RunStepResponse. Representa um passo na execução de uma execução
type: docs
weight: 1060
url: /pt/net/aspose.pdf.ai/runstepresponse/
---
## Classe RunStepResponse

Representa um passo na execução de uma execução.

```csharp
public class RunStepResponse : BaseResponse
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [RunStepResponse](runstepresponse/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runstepresponse/assistantid/) { get; set; } | Obtém ou define o ID do assistente associado ao passo da execução. |
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) para quando o passo da execução foi cancelado. |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) para quando o passo da execução foi concluído. |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) para quando o passo da execução foi criado. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtém ou define o detalhe da resposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtém ou define o erro da resposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtém ou define as informações do erro. |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) para quando o passo da execução expirou. Um passo é considerado expirado se a execução pai estiver expirada. |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) para quando o passo da execução falhou. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtém ou define os cabeçalhos da resposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtém ou define o código de status HTTP. |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | Obtém ou define o identificador do passo da execução, que pode ser referenciado em endpoints da API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se a resposta foi bem-sucedida. |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | Obtém ou define o último erro associado a este passo da execução. Será nulo se não houver erros. |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | Obtém ou define um conjunto de 16 pares chave-valor que podem ser anexados a um objeto. Isso pode ser útil para armazenar informações adicionais sobre o objeto em um formato estruturado. As chaves podem ter no máximo 64 caracteres e os valores podem ter no máximo 512 caracteres. |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | Obtém ou define o tipo de objeto, que é sempre thread.run.step. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtém a frase de razão do erro. |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | Obtém ou define o ID da execução da qual este passo da execução faz parte. |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | Obtém ou define o tipo de passo da execução, que pode ser message_creation ou tool_calls. |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | Obtém ou define o status do passo da execução, que pode ser in_progress, cancelled, failed, completed ou expired. |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | Obtém ou define os detalhes do passo da execução. |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | Obtém ou define o ID da thread que foi executada. |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | Obtém ou define estatísticas de uso relacionadas ao passo da execução. Este valor será nulo enquanto o status do passo da execução estiver in_progress. |

### Veja Também

* classe [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)