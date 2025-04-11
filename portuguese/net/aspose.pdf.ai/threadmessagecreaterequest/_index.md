---
title: Class ThreadMessageCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.ThreadMessageCreateRequest. Representa uma solicitação para criar uma mensagem dentro de um thread
type: docs
weight: 1120
url: /pt/net/aspose.pdf.ai/threadmessagecreaterequest/
---
## Classe ThreadMessageCreateRequest

Representa uma solicitação para criar uma mensagem dentro de um thread.

```csharp
public class ThreadMessageCreateRequest
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [ThreadMessageCreateRequest](threadmessagecreaterequest/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Attachments](../../aspose.pdf.ai/threadmessagecreaterequest/attachments/) { get; set; } | Obtém ou define uma lista de arquivos anexados à mensagem. |
| [Content](../../aspose.pdf.ai/threadmessagecreaterequest/content/) { get; set; } | Obtém ou define o conteúdo da mensagem. Pode ser uma string ou um array de partes de conteúdo. |
| [Metadata](../../aspose.pdf.ai/threadmessagecreaterequest/metadata/) { get; set; } | Obtém ou define um conjunto de 16 pares chave-valor que podem ser anexados a um objeto. Isso pode ser útil para armazenar informações adicionais sobre o objeto em um formato estruturado. As chaves podem ter no máximo 64 caracteres e os valores podem ter no máximo 512 caracteres. |
| [Role](../../aspose.pdf.ai/threadmessagecreaterequest/role/) { get; set; } | Obtém ou define o papel da entidade que cria a mensagem. Os valores permitidos incluem: "user", "assistant". |

## Métodos

| Nome | Descrição |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/threadmessagecreaterequest/fromassistant/)() | Cria uma nova `ThreadMessageCreateRequest` com o papel definido como Assistant. |
| static [FromUser](../../aspose.pdf.ai/threadmessagecreaterequest/fromuser/)() | Cria uma nova `ThreadMessageCreateRequest` com o papel definido como User. |
| [WithAttachments](../../aspose.pdf.ai/threadmessagecreaterequest/withattachments/)(List&lt;Attachment&gt;) | Define os anexos para a solicitação de mensagem do thread. |
| [WithContent](../../aspose.pdf.ai/threadmessagecreaterequest/withcontent/)(MessageContentRequest) | Adiciona um conteúdo de mensagem à solicitação de mensagem do thread. |
| [WithContents](../../aspose.pdf.ai/threadmessagecreaterequest/withcontents/)(List&lt;MessageContentRequest&gt;) | Define os conteúdos da mensagem para a solicitação de mensagem do thread. |
| [WithMetadata](../../aspose.pdf.ai/threadmessagecreaterequest/withmetadata/)(Dictionary&lt;string, string&gt;) | Define os metadados para a solicitação de mensagem do thread. |

### Veja Também

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)