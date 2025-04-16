---
title: CompletionCreateRequest.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: Propriedade CompletionCreateRequest. Obtém ou define um objeto que controla qual ferramenta, se houver, é chamada pelo modelo. none significa que o modelo não chamará nenhuma ferramenta e, em vez disso, gera uma mensagem. auto significa que o modelo pode escolher entre gerar uma mensagem ou chamar uma ou mais ferramentas. required significa que o modelo deve chamar uma ou mais ferramentas. Especificar uma ferramenta particular via "type": "function", "function": "name": "my_function" força o modelo a chamar essa ferramenta. none é o padrão quando nenhuma ferramenta está presente. auto é o padrão se ferramentas estão presentes.
type: docs
weight: 150
url: /pt/net/aspose.pdf.ai/completioncreaterequest/toolchoice/
---
## Propriedade CompletionCreateRequest.ToolChoice

Obtém ou define um objeto que controla qual (se houver) ferramenta é chamada pelo modelo. none significa que o modelo não chamará nenhuma ferramenta e, em vez disso, gera uma mensagem. auto significa que o modelo pode escolher entre gerar uma mensagem ou chamar uma ou mais ferramentas. required significa que o modelo deve chamar uma ou mais ferramentas. Especificar uma ferramenta particular via {"type": "function", "function": {"name": "my_function"}} força o modelo a chamar essa ferramenta. none é o padrão quando nenhuma ferramenta está presente. auto é o padrão se ferramentas estão presentes.

```csharp
public ToolChoice ToolChoice { get; set; }
```

### Veja Também

* classe [ToolChoice](../../toolchoice/)
* classe [CompletionCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)