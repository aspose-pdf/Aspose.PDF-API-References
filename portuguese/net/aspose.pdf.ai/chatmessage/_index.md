---
title: Class ChatMessage
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.ChatMessage. Uma mensagem de conclusão de chat gerada pelo modelo
type: docs
weight: 190
url: /pt/net/aspose.pdf.ai/chatmessage/
---
## Classe ChatMessage

Uma mensagem de conclusão de chat gerada pelo modelo.

```csharp
public class ChatMessage
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [ChatMessage](chatmessage/#constructor)() | Inicializa uma nova instância da classe `ChatMessage`. |
| [ChatMessage](chatmessage/#constructor_1)(string, string) | Inicializa uma nova instância da classe `ChatMessage`. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Content](../../aspose.pdf.ai/chatmessage/content/) { get; set; } | Obtém ou define o conteúdo da mensagem. |
| [Name](../../aspose.pdf.ai/chatmessage/name/) { get; set; } | Obtém ou define um nome opcional para o participante. Fornece informações ao modelo para diferenciar entre participantes do mesmo papel. |
| [Role](../../aspose.pdf.ai/chatmessage/role/) { get; set; } | Obtém ou define o papel do autor das mensagens. |
| [ToolCallId](../../aspose.pdf.ai/chatmessage/toolcallid/) { get; set; } | Obtém ou define a chamada de ferramenta à qual esta mensagem está respondendo. |
| [ToolCalls](../../aspose.pdf.ai/chatmessage/toolcalls/) { get; set; } | Obtém ou define as chamadas de ferramenta geradas pelo modelo, como chamadas de função. |

## Métodos

| Nome | Descrição |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/chatmessage/fromassistant/)(string) | Cria um novo objeto ChatMessage representando uma mensagem de assistente. |
| static [FromSystem](../../aspose.pdf.ai/chatmessage/fromsystem/)(string) | Cria um novo objeto ChatMessage representando uma mensagem de sistema. |
| static [FromUser](../../aspose.pdf.ai/chatmessage/fromuser/)(string) | Cria um novo objeto ChatMessage representando uma mensagem de usuário. |

### Veja Também

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)