---
title: IChatCopilot.GetResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: IChatCopilot-metod. Hämtar asynkront ett svar för det angivna meddelandet
type: docs
weight: 20
url: /sv/net/aspose.pdf.ai/ichatcopilot/getresponseasync/
---
## GetResponseAsync(string, CancellationToken?) {#getresponseasync_1}

Hämtar asynkront ett svar för det angivna meddelandet.

```csharp
public Task<string> GetResponseAsync(string message, CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| message | String | Det inmatade meddelandet för vilket ett svar begärs. |
| cancellationToken | Nullable`1 | Avbokningstoken (valfritt). |

### Return Value

En uppgift som representerar den asynkrona operationen med svarsträngen.

### Se Även

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## GetResponseAsync(List&lt;string&gt;, CancellationToken?) {#getresponseasync}

Hämtar asynkront ett svar för den angivna listan av meddelanden.

```csharp
public Task<string> GetResponseAsync(List<string> messages, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messages | List`1 | Listan av inmatade meddelanden för vilka svar begärs. |
| cancellationToken | Nullable`1 | Avbokningstoken (valfritt). |

### Return Value

En uppgift som representerar den asynkrona operationen med svarsträngen.

### Se Även

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)