---
title: Class RunThreadCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.RunThreadCreateRequest. Representa uma solicitação para criar um thread e executá-lo em uma única solicitação
type: docs
weight: 1070
url: /pt/net/aspose.pdf.ai/runthreadcreaterequest/
---
## Classe RunThreadCreateRequest

Representa uma solicitação para criar um thread e executá-lo em uma única solicitação.

```csharp
public class RunThreadCreateRequest
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [RunThreadCreateRequest](runthreadcreaterequest/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runthreadcreaterequest/assistantid/) { get; set; } | Obtém ou define o ID do assistente a ser usado para executar esta execução. |
| [Instructions](../../aspose.pdf.ai/runthreadcreaterequest/instructions/) { get; set; } | Obtém ou define as instruções que substituem as instruções do assistente. Isso é útil para modificar o comportamento em uma base por execução. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxcompletiontokens/) { get; set; } | Obtém ou define o número máximo de tokens de conclusão que podem ser usados ao longo da execução. A execução fará o melhor esforço para usar apenas o número de tokens de conclusão especificado, ao longo de várias turnos da execução. Se a execução exceder o número de tokens de conclusão especificados, a execução terminará com status incompleto. Veja incomplete_details para mais informações. |
| [MaxPromptTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxprompttokens/) { get; set; } | Obtém ou define o número máximo de tokens de prompt que podem ser usados ao longo da execução. A execução fará o melhor esforço para usar apenas o número de tokens de prompt especificado, ao longo de várias turnos da execução. Se a execução exceder o número de tokens de prompt especificados, a execução terminará com status incompleto. Veja incomplete_details para mais informações. |
| [Metadata](../../aspose.pdf.ai/runthreadcreaterequest/metadata/) { get; set; } | Obtém ou define um conjunto de 16 pares chave-valor que podem ser anexados a um objeto. Isso pode ser útil para armazenar informações adicionais sobre o objeto em um formato estruturado. As chaves podem ter no máximo 64 caracteres de comprimento e os valores podem ter no máximo 512 caracteres de comprimento. |
| [Model](../../aspose.pdf.ai/runthreadcreaterequest/model/) { get; set; } | Obtém ou define o ID do Modelo a ser usado para executar esta execução. Se um valor for fornecido aqui, ele substituirá o modelo associado ao assistente. Caso contrário, o modelo associado ao assistente será usado. |
| [ResponseFormat](../../aspose.pdf.ai/runthreadcreaterequest/responseformat/) { get; set; } | Obtém ou define o formato que o modelo deve gerar. Compatível com GPT-4o, GPT-4 Turbo e todos os modelos GPT-3.5 Turbo desde gpt-3.5-turbo-1106. Definir como { "type": "json_object" } ativa o modo JSON, que garante que a mensagem gerada pelo modelo seja um JSON válido. Importante: ao usar o modo JSON, você também deve instruir o modelo a produzir JSON você mesmo através de uma mensagem de sistema ou de usuário. Sem isso, o modelo pode gerar um fluxo interminável de espaços em branco até que a geração atinja o limite de tokens, resultando em uma solicitação de longa duração e aparentemente "presa". Também observe que o conteúdo da mensagem pode ser parcialmente cortado se finish_reason="length", o que indica que a geração excedeu max_tokens ou a conversa excedeu o comprimento máximo do contexto. |
| [Stream](../../aspose.pdf.ai/runthreadcreaterequest/stream/) { get; set; } | Obtém ou define se deve usar streaming. Se verdadeiro, retorna um fluxo de eventos que acontecem durante a execução como eventos enviados pelo servidor, terminando quando a execução entra em um estado terminal com uma mensagem data: [DONE]. |
| [Temperature](../../aspose.pdf.ai/runthreadcreaterequest/temperature/) { get; set; } | Obtém ou define qual temperatura de amostragem usar, entre 0 e 2. Valores mais altos como 0.8 tornarão a saída mais aleatória, enquanto valores mais baixos como 0.2 a tornarão mais focada e determinística. |
| [Thread](../../aspose.pdf.ai/runthreadcreaterequest/thread/) { get; set; } | Obtém ou define uma solicitação para criar um thread. |
| [ToolChoice](../../aspose.pdf.ai/runthreadcreaterequest/toolchoice/) { get; set; } | Obtém ou define qual (se houver) ferramenta é chamada pelo modelo. none significa que o modelo não chamará nenhuma ferramenta e, em vez disso, gerará uma mensagem. auto é o valor padrão e significa que o modelo pode escolher entre gerar uma mensagem ou chamar uma ou mais ferramentas. required significa que o modelo deve chamar uma ou mais ferramentas antes de responder ao usuário. Especificar uma ferramenta particular como {"type": "file_search"} ou {"type": "function", "function": {"name": "my_function"}} força o modelo a chamar essa ferramenta. |
| [ToolResources](../../aspose.pdf.ai/runthreadcreaterequest/toolresources/) { get; set; } | Obtém ou define um conjunto de recursos que são usados pelas ferramentas do assistente. |
| [Tools](../../aspose.pdf.ai/runthreadcreaterequest/tools/) { get; set; } | Obtém ou define as ferramentas que substituem as ferramentas que o assistente pode usar para esta execução. Isso é útil para modificar o comportamento em uma base por execução. |
| [TopP](../../aspose.pdf.ai/runthreadcreaterequest/topp/) { get; set; } | Obtém ou define um valor que é uma alternativa à amostragem com temperatura, chamada amostragem de núcleo, onde o modelo considera os resultados dos tokens com massa de probabilidade top_p. Assim, 0.1 significa que apenas os tokens que compõem os 10% superiores da massa de probabilidade são considerados. Geralmente, recomendamos alterar isso ou a temperatura, mas não ambos. |
| [TruncationStrategy](../../aspose.pdf.ai/runthreadcreaterequest/truncationstrategy/) { get; set; } | Obtém ou define a estratégia de truncamento que controla como um thread será truncado antes da execução. Use isso para controlar a janela de contexto inicial da execução. |

### Veja Também

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)