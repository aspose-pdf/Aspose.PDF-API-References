---
title: Class TruncationStrategy
second_title: Aspose.PDF for .NET API Reference
description: La classe Aspose.Pdf.AI.TruncationStrategy. Rappresenta la strategia di troncamento che controlla come un thread verrà troncato prima dell'esecuzione
type: docs
weight: 1240
url: /it/net/aspose.pdf.ai/truncationstrategy/
---
## Classe TruncationStrategy

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
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | Ottiene o imposta il numero di messaggi più recenti dal thread durante la costruzione del contesto per l'esecuzione. |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | Ottiene o imposta la strategia di troncamento da utilizzare per il thread. Il predefinito è auto. Se impostato su last_messages, il thread verrà troncato ai n messaggi più recenti nel thread. Quando impostato su auto, i messaggi nel mezzo del thread verranno eliminati per adattarsi alla lunghezza del contesto del modello, max_prompt_tokens. |

### Vedi Anche

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)