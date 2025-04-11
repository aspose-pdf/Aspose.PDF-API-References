---
title: IChatCopilot.SaveResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: IChatCopilot-metod. Asynkront sparar svaret för det angivna meddelandet till en PDF-fil
type: docs
weight: 40
url: /sv/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/
---
## SaveResponseAsync(string, string, CancellationToken?) {#saveresponseasync_3}

Asynkront sparar svaret för det angivna meddelandet till en PDF-fil.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| message | String | Inmatningsmeddelandet för vilket svaret sparas. |
| outputFileName | String | Namnet på PDF-filen som svaret ska sparas i. |
| cancellationToken | Nullable`1 | Avbokningstoken (valfritt). |

### Returvärde

En uppgift som representerar den asynkrona operationen.

### Se Även

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, SaveFormat, CancellationToken?) {#saveresponseasync_2}

Asynkront sparar svaret för det angivna meddelandet till en fil med angivet format.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| message | String | Inmatningsmeddelandet för vilket svaret sparas. |
| outputFileName | String | Namnet på filen som svaret ska sparas i. |
| saveFormat | SaveFormat | Formatet i vilket svaret ska sparas (PDF om inget anges). |
| cancellationToken | Nullable`1 | Avbokningstoken (valfritt). |

### Returvärde

En uppgift som representerar den asynkrona operationen.

### Se Även

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, CancellationToken?) {#saveresponseasync_1}

Asynkront sparar svaren för den angivna listan av meddelanden till en PDF-fil.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messages | List`1 | Listan av inmatningsmeddelanden för vilka svaren sparas. |
| outputFileName | String | Namnet på PDF-filen som svaren ska sparas i. |
| cancellationToken | Nullable`1 | Avbokningstoken (valfritt). |

### Returvärde

En uppgift som representerar den asynkrona operationen.

### Se Även

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, SaveFormat, CancellationToken?) {#saveresponseasync}

Asynkront sparar svaren för den angivna listan av meddelanden till en fil med angivet format.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messages | List`1 | Listan av inmatningsmeddelanden för vilka svaren sparas. |
| outputFileName | String | Namnet på filen som svaren ska sparas i. |
| saveFormat | SaveFormat | Formatet i vilket svaren ska sparas (PDF om inget anges). |
| cancellationToken | Nullable`1 | Avbokningstoken (valfritt). |

### Returvärde

En uppgift som representerar den asynkrona operationen.

### Se Även

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)