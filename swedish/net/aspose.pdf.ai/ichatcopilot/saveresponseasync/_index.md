---
title: "IChatCopilot.SaveResponseAsync"
second_title: "Aspose.PDF för .NET API‑referens"
description: "IChatCopilot-metod. Sparar asynkront svaret för det givna meddelandet till en PDF-fil."
type: docs
weight: 40
url: /sv/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/
---
## SaveResponseAsync(string, string, CancellationToken?) {#saveresponseasync_3}

Sparar asynkront svaret för det angivna meddelandet till en PDF-fil.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | String | Det inmatade meddelandet för vilket svaret sparas. |
| outputFileName | String | Namnet på PDF-utdatafilen för att spara svaret. |
| cancellationToken | Nullable`1 | Avbokningstoken (valfritt). |

### Returvärde

En uppgift som representerar den asynkrona operationen.

### Se även

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, SaveFormat, CancellationToken?) {#saveresponseasync_2}

Sparar asynkront svaret för det angivna meddelandet till en fil med angivet format.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | String | Det inmatade meddelandet för vilket svaret sparas. |
| outputFileName | String | Namnet på utdatafilen för att spara svaret. |
| saveFormat | SaveFormat | Formatet att spara svaret i (PDF om inget annat anges). |
| cancellationToken | Nullable`1 | Avbokningstoken (valfritt). |

### Returvärde

En uppgift som representerar den asynkrona operationen.

### Se även

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, CancellationToken?) {#saveresponseasync_1}

Sparar asynkront svaren för den angivna listan med meddelanden till en PDF-fil.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelanden | List`1 | Listan över inmatade meddelanden för vilka svar sparas. |
| outputFileName | String | Namnet på PDF-utdatafilen för att spara svaren. |
| cancellationToken | Nullable`1 | Avbokningstoken (valfritt). |

### Returvärde

En uppgift som representerar den asynkrona operationen.

### Se även

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, SaveFormat, CancellationToken?) {#saveresponseasync}

Sparar asynkront svaren för den angivna listan med meddelanden till en fil med angivet format.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelanden | List`1 | Listan över inmatade meddelanden för vilka svar sparas. |
| outputFileName | String | Namnet på utdatafilen för att spara svaren. |
| saveFormat | SaveFormat | Formatet att spara svaren i (PDF om inget annat anges). |
| cancellationToken | Nullable`1 | Avbokningstoken (valfritt). |

### Returvärde

En uppgift som representerar den asynkrona operationen.

### Se även

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


