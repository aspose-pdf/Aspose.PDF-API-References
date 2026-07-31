---
title: "Classe TruncationStrategy"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.AI.TruncationStrategy. Rappresenta la strategia di troncamento che controlla come un thread verrà troncato prima dell'esecuzione."
type: docs
weight: 1330
url: /it/net/aspose.pdf.ai/truncationstrategy/
---
## TruncationStrategy class

Rappresenta la strategia di troncamento che controlla come un thread verrà troncato prima dell'esecuzione.

```csharp
public class TruncationStrategy
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TruncationStrategy](truncationstrategy/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | Ottiene o imposta il numero dei messaggi più recenti dal thread durante la costruzione del contesto per l'esecuzione. |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | Ottiene o imposta la strategia di troncamento da utilizzare per il thread. Il valore predefinito è auto. Se impostato su last_messages, il thread verrà troncato ai n messaggi più recenti del thread. Quando impostato su auto, i messaggi al centro del thread verranno eliminati per adattarsi alla lunghezza del contesto del modello, max_prompt_tokens. |

### Vedi anche

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


