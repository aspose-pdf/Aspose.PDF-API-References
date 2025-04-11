---
title: Class CreateEmbeddingRequest
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.CreateEmbeddingRequest. Representa uma solicitação para o endpoint Create Embeddings
type: docs
weight: 260
url: /pt/net/aspose.pdf.ai/createembeddingrequest/
---
## Classe CreateEmbeddingRequest

Representa uma solicitação para o endpoint Create Embeddings.

```csharp
public class CreateEmbeddingRequest
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [CreateEmbeddingRequest](createembeddingrequest/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | Obtém ou define o número de dimensões que as embeddings de saída resultantes devem ter. Suportado apenas em modelos text-embedding-3 e posteriores. |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | Obtém ou define o formato para retornar as embeddings. Pode ser float ou base64. |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | Obtém ou define o texto de entrada a ser incorporado, codificado como uma string ou array de tokens. Para incorporar várias entradas em uma única solicitação, passe um array de strings ou um array de arrays de tokens. A entrada não deve exceder o número máximo de tokens de entrada para o modelo (8192 tokens para text-embedding-ada-002), não pode ser uma string vazia e qualquer array deve ter 2048 dimensões ou menos. |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | Obtém ou define o modelo para gerar a embedding. |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | Obtém ou define um identificador único representando seu usuário final, que pode ajudar a OpenAI a monitorar e detectar abusos. |

### Veja Também

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)