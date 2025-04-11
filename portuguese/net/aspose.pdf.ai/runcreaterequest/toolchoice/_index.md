---
title: RunCreateRequest.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: Propriedade RunCreateRequest. Obtém ou define qual ferramenta, se houver, é chamada pelo modelo. nenhum significa que o modelo não chamará nenhuma ferramenta e, em vez disso, gera uma mensagem. automático é o valor padrão e significa que o modelo pode escolher entre gerar uma mensagem ou chamar uma ou mais ferramentas. obrigatório significa que o modelo deve chamar uma ou mais ferramentas antes de responder ao usuário. Especificar uma ferramenta específica como {"type": "file_search"} ou {"type": "function", "function": {"name": "my_function"}} força o modelo a chamar essa ferramenta.
type: docs
weight: 130
url: /pt/net/aspose.pdf.ai/runcreaterequest/toolchoice/
---
## Propriedade RunCreateRequest.ToolChoice

Obtém ou define qual (se houver) ferramenta é chamada pelo modelo. nenhum significa que o modelo não chamará nenhuma ferramenta e, em vez disso, gera uma mensagem. automático é o valor padrão e significa que o modelo pode escolher entre gerar uma mensagem ou chamar uma ou mais ferramentas. obrigatório significa que o modelo deve chamar uma ou mais ferramentas antes de responder ao usuário. Especificar uma ferramenta específica como {"type": "file_search"} ou {"type": "function", "function": {"name": "my_function"}} força o modelo a chamar essa ferramenta.

```csharp
public string ToolChoice { get; set; }
```

### Veja Também

* classe [RunCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)