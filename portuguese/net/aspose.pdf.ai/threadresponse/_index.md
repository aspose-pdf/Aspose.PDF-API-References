---
title: Class ThreadResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.ThreadResponse. Representa um thread que contém mensagens
type: docs
weight: 1180
url: /pt/net/aspose.pdf.ai/threadresponse/
---
## Classe ThreadResponse

Representa um thread que contém mensagens.

```csharp
public class ThreadResponse : BaseResponse
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [ThreadResponse](threadresponse/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/threadresponse/createdat/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) para quando o thread foi criado. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtém ou define os detalhes da resposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtém ou define o erro da resposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtém ou define as informações de erro. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtém ou define os cabeçalhos da resposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtém ou define o código de status HTTP. |
| [Id](../../aspose.pdf.ai/threadresponse/id/) { get; set; } | Obtém ou define o identificador, que pode ser referenciado em endpoints da API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se a resposta foi bem-sucedida. |
| [Metadata](../../aspose.pdf.ai/threadresponse/metadata/) { get; set; } | Obtém ou define um conjunto de 16 pares chave-valor que podem ser anexados a um objeto. Isso pode ser útil para armazenar informações adicionais sobre o objeto em um formato estruturado. As chaves podem ter no máximo 64 caracteres e os valores podem ter no máximo 512 caracteres. |
| [Object](../../aspose.pdf.ai/threadresponse/object/) { get; set; } | Obtém ou define o tipo de objeto, que é sempre thread. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtém a frase de razão do erro. |
| [ToolResources](../../aspose.pdf.ai/threadresponse/toolresources/) { get; set; } | Obtém ou define um conjunto de recursos que são disponibilizados para as ferramentas do assistente neste thread. Os recursos são específicos para o tipo de ferramenta. Por exemplo, a ferramenta code_interpreter requer uma lista de IDs de arquivos, enquanto a ferramenta file_search requer uma lista de IDs de armazenamento vetorial. |

### Veja Também

* classe [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)