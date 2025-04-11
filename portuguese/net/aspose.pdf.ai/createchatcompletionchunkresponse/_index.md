---
title: Class CreateChatCompletionChunkResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.CreateChatCompletionChunkResponse. Representa um pedaço transmitido de uma resposta de conclusão de chat retornada pelo modelo com base na entrada fornecida
type: docs
weight: 250
url: /pt/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## Classe CreateChatCompletionChunkResponse

Representa um pedaço transmitido de uma resposta de conclusão de chat retornada pelo modelo, com base na entrada fornecida.

```csharp
public class CreateChatCompletionChunkResponse
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [CreateChatCompletionChunkResponse](createchatcompletionchunkresponse/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | Obtém ou define uma lista de opções de conclusão de chat. Pode conter mais de um elemento se n for maior que 1. Também pode estar vazio para o último pedaço se você definir stream_options: {"include_usage": true}. |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | Obtém ou define o timestamp Unix (em segundos) de quando a conclusão do chat foi criada. Cada pedaço tem o mesmo timestamp. |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | Obtém ou define um identificador único para a conclusão do chat. Cada pedaço tem o mesmo ID. |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | Obtém ou define o modelo para gerar a conclusão. |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | Obtém ou define o tipo de objeto, que é sempre chat.completion.chunk. |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | Obtém ou define a impressão digital que representa a configuração do backend com a qual o modelo é executado. Pode ser usada em conjunto com o parâmetro de solicitação seed para entender quando mudanças no backend foram feitas que podem impactar o determinismo. |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | Obtém ou define um campo opcional que só estará presente quando você definir stream_options: {"include_usage": true} em sua solicitação. Quando presente, contém um valor nulo, exceto para o último pedaço que contém as estatísticas de uso de token para toda a solicitação. |

### Veja Também

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)