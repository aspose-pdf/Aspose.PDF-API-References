---
title: IChatCopilot.SaveResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IChatCopilot. Salva assíncronamente a resposta para a mensagem dada em um arquivo PDF
type: docs
weight: 40
url: /pt/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/
---
## SaveResponseAsync(string, string, CancellationToken?) {#saveresponseasync_3}

Salva assíncronamente a resposta para a mensagem dada em um arquivo PDF.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | String | A mensagem de entrada para a qual a resposta é salva. |
| outputFileName | String | O nome do arquivo PDF de saída para salvar a resposta. |
| cancellationToken | Nullable`1 | O token de cancelamento (opcional). |

### Valor de Retorno

Uma tarefa representando a operação assíncrona.

### Veja Também

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, SaveFormat, CancellationToken?) {#saveresponseasync_2}

Salva assíncronamente a resposta para a mensagem dada em um arquivo com formato especificado.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | String | A mensagem de entrada para a qual a resposta é salva. |
| outputFileName | String | O nome do arquivo de saída para salvar a resposta. |
| saveFormat | SaveFormat | O formato em que salvar a resposta (PDF se não especificado). |
| cancellationToken | Nullable`1 | O token de cancelamento (opcional). |

### Valor de Retorno

Uma tarefa representando a operação assíncrona.

### Veja Também

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, CancellationToken?) {#saveresponseasync_1}

Salva assíncronamente as respostas para a lista dada de mensagens em um arquivo PDF.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| messages | List`1 | A lista de mensagens de entrada para as quais as respostas são salvas. |
| outputFileName | String | O nome do arquivo PDF de saída para salvar as respostas. |
| cancellationToken | Nullable`1 | O token de cancelamento (opcional). |

### Valor de Retorno

Uma tarefa representando a operação assíncrona.

### Veja Também

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, SaveFormat, CancellationToken?) {#saveresponseasync}

Salva assíncronamente as respostas para a lista dada de mensagens em um arquivo com formato especificado.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| messages | List`1 | A lista de mensagens de entrada para as quais as respostas são salvas. |
| outputFileName | String | O nome do arquivo de saída para salvar as respostas. |
| saveFormat | SaveFormat | O formato em que salvar as respostas (PDF se não especificado). |
| cancellationToken | Nullable`1 | O token de cancelamento (opcional). |

### Valor de Retorno

Uma tarefa representando a operação assíncrona.

### Veja Também

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)