---
title: Class CompletionCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.CompletionCreateRequest. Representa uma solicitação para o endpoint Create Chat Completion
type: docs
weight: 220
url: /pt/net/aspose.pdf.ai/completioncreaterequest/
---
## Classe CompletionCreateRequest

Representa uma solicitação para o endpoint Create Chat Completion.

```csharp
public class CompletionCreateRequest
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [CompletionCreateRequest](completioncreaterequest/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [FrequencyPenalty](../../aspose.pdf.ai/completioncreaterequest/frequencypenalty/) { get; set; } | Obtém ou define um número entre -2.0 e 2.0. Valores positivos penalizam novos tokens com base em sua frequência existente no texto até agora, diminuindo a probabilidade do modelo de repetir a mesma linha literalmente. |
| [LogitBias](../../aspose.pdf.ai/completioncreaterequest/logitbias/) { get; set; } | Obtém ou define a probabilidade de tokens especificados aparecerem na conclusão. Aceita um objeto JSON que mapeia tokens (especificados pelo seu ID de token no tokenizador) a um valor de viés associado de -100 a 100. |
| [Logprobs](../../aspose.pdf.ai/completioncreaterequest/logprobs/) { get; set; } | Obtém ou define se deve retornar logaritmos das probabilidades dos tokens de saída ou não. Se verdadeiro, retorna os logaritmos das probabilidades de cada token de saída retornado no conteúdo da mensagem. |
| [MaxTokens](../../aspose.pdf.ai/completioncreaterequest/maxtokens/) { get; set; } | Obtém ou define o número máximo de tokens a serem gerados na conclusão. |
| [Messages](../../aspose.pdf.ai/completioncreaterequest/messages/) { get; set; } | Obtém ou define uma lista de mensagens que compreendem a conversa até agora. |
| [Model](../../aspose.pdf.ai/completioncreaterequest/model/) { get; set; } | Obtém ou define o ID do modelo a ser usado. |
| [NumberOfChoices](../../aspose.pdf.ai/completioncreaterequest/numberofchoices/) { get; set; } | Obtém ou define quantas opções de conclusão de chat gerar para cada mensagem de entrada. Observe que você será cobrado com base no número de tokens gerados em todas as opções. Mantenha n como 1 para minimizar custos. |
| [PresencePenalty](../../aspose.pdf.ai/completioncreaterequest/presencepenalty/) { get; set; } | Obtém ou define um número entre -2.0 e 2.0. Valores positivos penalizam novos tokens com base em sua aparição no texto até agora, aumentando a probabilidade do modelo de falar sobre novos tópicos. |
| [ResponseFormat](../../aspose.pdf.ai/completioncreaterequest/responseformat/) { get; set; } | Obtém ou define um objeto que especifica o formato que o modelo deve gerar. Compatível com GPT-4 Turbo e todos os modelos GPT-3.5 Turbo mais novos que gpt-3.5-turbo-1106. Definir como { "type": "json_object" } ativa o modo JSON, que garante que a mensagem gerada pelo modelo seja um JSON válido. |
| [Seed](../../aspose.pdf.ai/completioncreaterequest/seed/) { get; set; } | Obtém ou define o valor Seed. Este recurso está em Beta. Se especificado, nosso sistema fará o melhor esforço para amostrar de forma determinística, de modo que solicitações repetidas com o mesmo seed e parâmetros devem retornar o mesmo resultado. A determinismo não é garantido, e você deve consultar o parâmetro de resposta system_fingerprint para monitorar mudanças no backend. |
| [Stop](../../aspose.pdf.ai/completioncreaterequest/stop/) { get; set; } | Obtém ou define até 4 sequências onde a API interromperá a geração de tokens adicionais. |
| [Stream](../../aspose.pdf.ai/completioncreaterequest/stream/) { get; set; } | Obtém ou define se deve usar streaming. Se definido, deltas de mensagens parciais serão enviados, como no ChatGPT. Tokens serão enviados como eventos enviados pelo servidor apenas de dados à medida que se tornam disponíveis, com o stream terminado por uma mensagem data: [DONE]. |
| [Temperature](../../aspose.pdf.ai/completioncreaterequest/temperature/) { get; set; } | Obtém ou define qual temperatura de amostragem usar, entre 0 e 2. Valores mais altos como 0.8 tornarão a saída mais aleatória, enquanto valores mais baixos como 0.2 a tornarão mais focada e determinística. |
| [ToolChoice](../../aspose.pdf.ai/completioncreaterequest/toolchoice/) { get; set; } | Obtém ou define um objeto que controla qual (se houver) ferramenta é chamada pelo modelo. none significa que o modelo não chamará nenhuma ferramenta e, em vez disso, gerará uma mensagem. auto significa que o modelo pode escolher entre gerar uma mensagem ou chamar uma ou mais ferramentas. required significa que o modelo deve chamar uma ou mais ferramentas. Especificar uma ferramenta particular via {"type": "function", "function": {"name": "my_function"}} força o modelo a chamar essa ferramenta. none é o padrão quando nenhuma ferramenta está presente. auto é o padrão se ferramentas estão presentes. |
| [Tools](../../aspose.pdf.ai/completioncreaterequest/tools/) { get; set; } | Obtém ou define uma lista de ferramentas que o modelo pode chamar. Atualmente, apenas funções são suportadas como ferramenta. Use isso para fornecer uma lista de funções para as quais o modelo pode gerar entradas JSON. Um máximo de 128 funções são suportadas. |
| [TopP](../../aspose.pdf.ai/completioncreaterequest/topp/) { get; set; } | Obtém ou define uma alternativa à amostragem com temperatura, chamada amostragem de núcleo, onde o modelo considera os resultados dos tokens com massa de probabilidade top_p. Assim, 0.1 significa que apenas os tokens que compõem os 10% superiores da massa de probabilidade são considerados. |
| [User](../../aspose.pdf.ai/completioncreaterequest/user/) { get; set; } | Obtém ou define um identificador único representando seu usuário final, o que pode ajudar a OpenAI a monitorar e detectar abusos. |

### Veja Também

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)