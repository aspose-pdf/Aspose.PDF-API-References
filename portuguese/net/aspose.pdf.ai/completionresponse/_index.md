---
title: Class CompletionResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.CompletionResponse. Representa uma resposta de conclusão de chat retornada pelo modelo com base na entrada fornecida
type: docs
weight: 240
url: /pt/net/aspose.pdf.ai/completionresponse/
---
## Classe CompletionResponse

Representa uma resposta de conclusão de chat retornada pelo modelo, com base na entrada fornecida.

```csharp
public class CompletionResponse : BaseResponse
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [CompletionResponse](completionresponse/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Choices](../../aspose.pdf.ai/completionresponse/choices/) { get; set; } | Obtém ou define uma lista de opções de conclusão de chat. Pode haver mais de uma se n for maior que 1. |
| [Created](../../aspose.pdf.ai/completionresponse/created/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) de quando a conclusão do chat foi criada. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtém ou define o detalhe da resposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtém ou define o erro da resposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtém ou define as informações de erro. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtém ou define os cabeçalhos da resposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtém ou define o código de status HTTP. |
| [Id](../../aspose.pdf.ai/completionresponse/id/) { get; set; } | Obtém ou define um identificador único para a conclusão do chat. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se a resposta foi bem-sucedida. |
| [Model](../../aspose.pdf.ai/completionresponse/model/) { get; set; } | Obtém ou define o modelo usado para a conclusão do chat. |
| [Object](../../aspose.pdf.ai/completionresponse/object/) { get; set; } | Obtém ou define o tipo de objeto, que é sempre chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtém a frase de razão do erro. |
| [SystemFingerprint](../../aspose.pdf.ai/completionresponse/systemfingerprint/) { get; set; } | Obtém ou define a impressão digital que representa a configuração do backend com a qual o modelo é executado. Pode ser usada em conjunto com o parâmetro de solicitação seed para entender quando mudanças no backend foram feitas que podem impactar o determinismo. |
| [Usage](../../aspose.pdf.ai/completionresponse/usage/) { get; set; } | Obtém ou define as estatísticas de uso para a solicitação de conclusão. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/completionresponse/tostring/)() | Retorna o conteúdo da primeira opção como uma string. |

### Veja Também

* classe [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)