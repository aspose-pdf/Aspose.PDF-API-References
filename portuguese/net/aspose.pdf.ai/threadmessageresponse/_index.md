---
title: Class ThreadMessageResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.ThreadMessageResponse. Representa uma mensagem dentro de um thread
type: docs
weight: 1160
url: /pt/net/aspose.pdf.ai/threadmessageresponse/
---
## Classe ThreadMessageResponse

Representa uma mensagem dentro de um thread.

```csharp
public class ThreadMessageResponse : BaseResponse, IStatus
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [ThreadMessageResponse](threadmessageresponse/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/threadmessageresponse/assistantid/) { get; set; } | Obtém ou define, se aplicável, o ID do assistente que criou esta mensagem. |
| [Attachments](../../aspose.pdf.ai/threadmessageresponse/attachments/) { get; set; } | Obtém ou define uma lista de arquivos anexados à mensagem. |
| [CompletedAt](../../aspose.pdf.ai/threadmessageresponse/completedat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) de quando a mensagem foi concluída. |
| [Content](../../aspose.pdf.ai/threadmessageresponse/content/) { get; set; } | Obtém ou define o conteúdo da mensagem em um array de texto e/ou imagens. |
| [CreatedAt](../../aspose.pdf.ai/threadmessageresponse/createdat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) de quando a mensagem foi criada. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtém ou define o detalhe da resposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtém ou define o erro da resposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtém ou define as informações de erro. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtém ou define os cabeçalhos da resposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtém ou define o código de status HTTP. |
| [Id](../../aspose.pdf.ai/threadmessageresponse/id/) { get; set; } | Obtém ou define o identificador, que pode ser referenciado em endpoints da API. |
| [IncompleteAt](../../aspose.pdf.ai/threadmessageresponse/incompleteat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) de quando a mensagem foi marcada como incompleta. |
| [IncompleteDetails](../../aspose.pdf.ai/threadmessageresponse/incompletedetails/) { get; set; } | Obtém ou define uma mensagem incompleta, detalhes sobre o motivo pelo qual a mensagem está incompleta. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se a resposta foi bem-sucedida. |
| [Metadata](../../aspose.pdf.ai/threadmessageresponse/metadata/) { get; set; } | Obtém ou define um conjunto de 16 pares chave-valor que podem ser anexados a um objeto. Isso pode ser útil para armazenar informações adicionais sobre o objeto em um formato estruturado. As chaves podem ter no máximo 64 caracteres e os valores podem ter no máximo 512 caracteres. |
| [Object](../../aspose.pdf.ai/threadmessageresponse/object/) { get; set; } | Obtém ou define o tipo de objeto, que é sempre "thread.message". |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtém a frase de razão do erro. |
| [Role](../../aspose.pdf.ai/threadmessageresponse/role/) { get; set; } | Obtém ou define a entidade que produziu a mensagem. Um de "user" ou "assistant". |
| [RunId](../../aspose.pdf.ai/threadmessageresponse/runid/) { get; set; } | Obtém ou define o ID da execução associada à criação desta mensagem. O valor é nulo quando as mensagens são criadas manualmente. |
| [Status](../../aspose.pdf.ai/threadmessageresponse/status/) { get; set; } | Obtém ou define o status da mensagem. Um de queued, in_progress, requires_action ou completed. |
| [ThreadId](../../aspose.pdf.ai/threadmessageresponse/threadid/) { get; set; } | Obtém ou define o ID do thread ao qual esta mensagem pertence. |

### Veja Também

* classe [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)