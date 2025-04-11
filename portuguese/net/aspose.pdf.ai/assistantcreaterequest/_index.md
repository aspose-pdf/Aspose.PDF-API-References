---
title: Class AssistantCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.AssistantCreateRequest. Objeto de solicitação para criar um assistente
type: docs
weight: 100
url: /pt/net/aspose.pdf.ai/assistantcreaterequest/
---
## Classe AssistantCreateRequest

Objeto de solicitação para criar um assistente.

```csharp
public class AssistantCreateRequest
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [AssistantCreateRequest](assistantcreaterequest/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Description](../../aspose.pdf.ai/assistantcreaterequest/description/) { get; set; } | Obtém ou define a descrição do assistente. O comprimento máximo é 512 caracteres. |
| [Instructions](../../aspose.pdf.ai/assistantcreaterequest/instructions/) { get; set; } | Obtém ou define as instruções do sistema que o assistente usa. O comprimento máximo é 256.000 caracteres. |
| [Metadata](../../aspose.pdf.ai/assistantcreaterequest/metadata/) { get; set; } | Obtém ou define um conjunto de 16 pares chave-valor que podem ser anexados a um objeto. Isso pode ser útil para armazenar informações adicionais sobre o objeto em um formato estruturado. As chaves podem ter no máximo 64 caracteres e os valores podem ter no máximo 512 caracteres. |
| [Model](../../aspose.pdf.ai/assistantcreaterequest/model/) { get; set; } | Obtém ou define o ID do modelo a ser usado. Você pode usar a API List models para ver todos os seus modelos disponíveis ou ver nossa visão geral do Modelo para descrições deles. |
| [Name](../../aspose.pdf.ai/assistantcreaterequest/name/) { get; set; } | Obtém ou define o nome do assistente. O comprimento máximo é 256 caracteres. |
| [ResponseFormat](../../aspose.pdf.ai/assistantcreaterequest/responseformat/) { get; set; } | Obtém ou define o formato que o modelo deve gerar. Compatível com GPT-4o, GPT-4 Turbo e todos os modelos GPT-3.5 Turbo desde gpt-3.5-turbo-1106. Definir como { "type": "json_object" } ativa o modo JSON, que garante que a mensagem gerada pelo modelo seja um JSON válido. Importante: ao usar o modo JSON, você também deve instruir o modelo a produzir JSON você mesmo por meio de uma mensagem de sistema ou usuário. Sem isso, o modelo pode gerar um fluxo interminável de espaços em branco até que a geração atinja o limite de tokens, resultando em uma solicitação de longa duração e aparentemente "travada". Também observe que o conteúdo da mensagem pode ser parcialmente cortado se finish_reason="length", o que indica que a geração excedeu max_tokens ou a conversa excedeu o comprimento máximo do contexto. |
| [Temperature](../../aspose.pdf.ai/assistantcreaterequest/temperature/) { get; set; } | Obtém ou define a temperatura de amostragem a ser usada, entre 0 e 2. Valores mais altos, como 0.8, tornarão a saída mais aleatória, enquanto valores mais baixos, como 0.2, a tornarão mais focada e determinística. |
| [ToolResources](../../aspose.pdf.ai/assistantcreaterequest/toolresources/) { get; set; } | Obtém ou define recursos que são usados pelas ferramentas do assistente. Os recursos são específicos para o tipo de ferramenta. Por exemplo, a ferramenta code_interpreter requer uma lista de IDs de arquivos, enquanto a ferramenta file_search requer uma lista de IDs de armazenamento vetorial. |
| [Tools](../../aspose.pdf.ai/assistantcreaterequest/tools/) { get; set; } | Obtém ou define uma lista de ferramentas habilitadas no assistente. Pode haver um máximo de 128 ferramentas por assistente. As ferramentas podem ser dos tipos code_interpreter, file_search ou function. |
| [TopP](../../aspose.pdf.ai/assistantcreaterequest/topp/) { get; set; } | Obtém ou define uma alternativa à amostragem com temperatura, chamada amostragem de núcleo, onde o modelo considera os resultados dos tokens com massa de probabilidade top_p. Assim, 0.1 significa que apenas os tokens que compõem os 10% superiores da massa de probabilidade são considerados. Geralmente, recomendamos alterar isso ou a temperatura, mas não ambos. |

### Veja Também

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)