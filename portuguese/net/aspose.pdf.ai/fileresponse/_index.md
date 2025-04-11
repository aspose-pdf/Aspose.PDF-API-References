---
title: Class FileResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.FileResponse. O objeto FileResponse representa um documento que foi enviado para o OpenAI
type: docs
weight: 400
url: /pt/net/aspose.pdf.ai/fileresponse/
---
## Classe FileResponse

O objeto FileResponse representa um documento que foi enviado para o OpenAI.

```csharp
public class FileResponse : BaseResponse, IEntityId
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [FileResponse](fileresponse/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Bytes](../../aspose.pdf.ai/fileresponse/bytes/) { get; set; } | Obtém ou define o tamanho do arquivo, em bytes. |
| [CreatedAt](../../aspose.pdf.ai/fileresponse/createdat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) para quando o arquivo foi criado. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtém ou define o detalhe da resposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtém ou define o erro da resposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtém ou define as informações do erro. |
| [Filename](../../aspose.pdf.ai/fileresponse/filename/) { get; set; } | Obtém ou define o nome do arquivo. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtém ou define os cabeçalhos da resposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtém ou define o código de status HTTP. |
| [Id](../../aspose.pdf.ai/fileresponse/id/) { get; set; } | Obtém ou define o identificador do arquivo, que pode ser referenciado nos endpoints da API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se a resposta foi bem-sucedida. |
| [Object](../../aspose.pdf.ai/fileresponse/object/) { get; set; } | Obtém ou define o tipo de objeto, que é sempre arquivo. |
| [Purpose](../../aspose.pdf.ai/fileresponse/purpose/) { get; set; } | Obtém ou define o propósito pretendido do arquivo. Os valores suportados são assistants, assistants_output, batch, batch_output, fine-tune, fine-tune-results e vision. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtém a frase de razão do erro. |

### Veja Também

* classe [BaseResponse](../baseresponse/)
* interface [IEntityId](../ientityid/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)