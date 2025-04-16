---
title: AssistantCreateRequest.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: Propriedade AssistantCreateRequest. Obtém ou define o formato que o modelo deve gerar. Compatível com GPT-4o, GPT-4 Turbo e todos os modelos GPT-3.5 Turbo desde gpt-3.5-turbo-1106. Definir como "type": "json_object" ativa o modo JSON, que garante que a mensagem gerada pelo modelo seja um JSON válido. Importante: ao usar o modo JSON, você também deve instruir o modelo a produzir JSON você mesmo através de uma mensagem de sistema ou do usuário. Sem isso, o modelo pode gerar um fluxo interminável de espaços em branco até que a geração atinja o limite de tokens, resultando em uma solicitação de longa duração e aparentemente "travada". Também observe que o conteúdo da mensagem pode ser parcialmente cortado se finish_reason="length", o que indica que a geração excedeu max_tokens ou a conversa excedeu o comprimento máximo do contexto.
type: docs
weight: 70
url: /pt/net/aspose.pdf.ai/assistantcreaterequest/responseformat/
---
## Propriedade AssistantCreateRequest.ResponseFormat

Obtém ou define o formato que o modelo deve gerar. Compatível com GPT-4o, GPT-4 Turbo e todos os modelos GPT-3.5 Turbo desde gpt-3.5-turbo-1106. Definir como { "type": "json_object" } ativa o modo JSON, que garante que a mensagem gerada pelo modelo seja um JSON válido. Importante: ao usar o modo JSON, você também deve instruir o modelo a produzir JSON você mesmo através de uma mensagem de sistema ou do usuário. Sem isso, o modelo pode gerar um fluxo interminável de espaços em branco até que a geração atinja o limite de tokens, resultando em uma solicitação de longa duração e aparentemente "travada". Também observe que o conteúdo da mensagem pode ser parcialmente cortado se finish_reason="length", o que indica que a geração excedeu max_tokens ou a conversa excedeu o comprimento máximo do contexto.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### Veja Também

* classe [ResponseFormat](../../responseformat/)
* classe [AssistantCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)