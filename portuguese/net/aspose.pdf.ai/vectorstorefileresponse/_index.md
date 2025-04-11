---
title: Class VectorStoreFileResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.VectorStoreFileResponse. Uma resposta de arquivo de armazenamento vetorial
type: docs
weight: 1350
url: /pt/net/aspose.pdf.ai/vectorstorefileresponse/
---
## Classe VectorStoreFileResponse

Uma resposta de arquivo de armazenamento vetorial.

```csharp
public class VectorStoreFileResponse : BaseResponse, IStatus
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [VectorStoreFileResponse](vectorstorefileresponse/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstorefileresponse/createdat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) para quando o arquivo de armazenamento vetorial foi criado. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtém ou define os detalhes da resposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtém ou define o erro da resposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtém ou define as informações de erro. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtém ou define os cabeçalhos da resposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtém ou define o código de status HTTP. |
| [Id](../../aspose.pdf.ai/vectorstorefileresponse/id/) { get; set; } | Obtém ou define o identificador, que pode ser referenciado em endpoints da API. /// |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se a resposta foi bem-sucedida. |
| [LastError](../../aspose.pdf.ai/vectorstorefileresponse/lasterror/) { get; set; } | Obtém ou define o último erro associado a este arquivo de armazenamento vetorial. Será nulo se não houver erros. |
| [Object](../../aspose.pdf.ai/vectorstorefileresponse/object/) { get; set; } | Obtém ou define o tipo de objeto, que é sempre vector_store.file. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtém a frase de razão do erro. |
| [Status](../../aspose.pdf.ai/vectorstorefileresponse/status/) { get; set; } | Obtém ou define o status do arquivo de armazenamento vetorial, que pode ser in_progress, completed, cancelled ou failed. O status completed indica que o arquivo de armazenamento vetorial está pronto para uso. |
| [UsageBytes](../../aspose.pdf.ai/vectorstorefileresponse/usagebytes/) { get; set; } | Obtém ou define o uso total do armazenamento vetorial em bytes. Observe que isso pode ser diferente do tamanho do arquivo original. |
| [VectorStoreId](../../aspose.pdf.ai/vectorstorefileresponse/vectorstoreid/) { get; set; } | Obtém ou define o ID do armazenamento vetorial ao qual o arquivo está anexado. |

### Veja Também

* classe [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)