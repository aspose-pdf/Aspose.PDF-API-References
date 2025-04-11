---
title: Class VectorStoreResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.VectorStoreResponse. O objeto de armazenamento de vetores
type: docs
weight: 1390
url: /pt/net/aspose.pdf.ai/vectorstoreresponse/
---
## Classe VectorStoreResponse

O objeto de armazenamento de vetores.

```csharp
public class VectorStoreResponse : BaseResponse, IEntityId, IStatus
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [VectorStoreResponse](vectorstoreresponse/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstoreresponse/createdat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) de quando o armazenamento de vetores foi criado. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtém ou define os detalhes da resposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtém ou define o erro da resposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtém ou define as informações de erro. |
| [ExpiresAfter](../../aspose.pdf.ai/vectorstoreresponse/expiresafter/) { get; set; } | Obtém ou define a política de expiração para um armazenamento de vetores. |
| [ExpiresAt](../../aspose.pdf.ai/vectorstoreresponse/expiresat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) de quando o armazenamento de vetores irá expirar. |
| [FileCounts](../../aspose.pdf.ai/vectorstoreresponse/filecounts/) { get; set; } | Obtém ou define o número de arquivos que foram processados. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtém ou define os cabeçalhos da resposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtém ou define o código de status HTTP. |
| [Id](../../aspose.pdf.ai/vectorstoreresponse/id/) { get; set; } | Obtém ou define o identificador, que pode ser referenciado em endpoints da API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se a resposta foi bem-sucedida. |
| [LastActiveAt](../../aspose.pdf.ai/vectorstoreresponse/lastactiveat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) de quando o armazenamento de vetores foi mais recentemente ativo. |
| [Metadata](../../aspose.pdf.ai/vectorstoreresponse/metadata/) { get; set; } | Obtém ou define um conjunto de 16 pares chave-valor que podem ser anexados a um objeto. Isso pode ser útil para armazenar informações adicionais sobre o objeto em um formato estruturado. As chaves podem ter no máximo 64 caracteres e os valores podem ter no máximo 512 caracteres. |
| [Name](../../aspose.pdf.ai/vectorstoreresponse/name/) { get; set; } | Obtém ou define o nome do armazenamento de vetores. |
| [Object](../../aspose.pdf.ai/vectorstoreresponse/object/) { get; set; } | Obtém ou define o tipo de objeto, que é sempre vector_store. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtém a frase de razão do erro. |
| [Status](../../aspose.pdf.ai/vectorstoreresponse/status/) { get; set; } | Obtém ou define o status do armazenamento de vetores, que pode ser expirado, em_andamento ou concluído. Um status de concluído indica que o armazenamento de vetores está pronto para uso. |
| [UsageBytes](../../aspose.pdf.ai/vectorstoreresponse/usagebytes/) { get; set; } | Obtém ou define o número total de bytes usados pelos arquivos no armazenamento de vetores. |

### Veja Também

* classe [BaseResponse](../baseresponse/)
* interface [IEntityId](../ientityid/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)