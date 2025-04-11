---
title: AssistantResponse.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: Proprietà AssistantResponse. Ottiene o imposta il formato che il modello deve restituire. Compatibile con GPT4o, GPT4 Turbo e tutti i modelli GPT3.5 Turbo a partire da gpt3.5turbo1106. Impostare a  type json_object  abilita la modalità JSON che garantisce che il messaggio generato dal modello sia JSON valido. Importante: quando si utilizza la modalità JSON, è necessario istruire anche il modello a produrre JSON autonomamente tramite un messaggio di sistema o utente. In assenza di ciò, il modello potrebbe generare un flusso infinito di spazi bianchi fino a raggiungere il limite di token, risultando in una richiesta di lunga durata e apparentemente "bloccata". Nota inoltre che il contenuto del messaggio potrebbe essere parzialmente troncato se finish_reason="length", il che indica che la generazione ha superato max_tokens o che la conversazione ha superato la lunghezza massima del contesto.
type: docs
weight: 100
url: /it/net/aspose.pdf.ai/assistantresponse/responseformat/
---
## Proprietà AssistantResponse.ResponseFormat

Ottiene o imposta il formato che il modello deve restituire. Compatibile con GPT-4o, GPT-4 Turbo e tutti i modelli GPT-3.5 Turbo a partire da gpt-3.5-turbo-1106. Impostare a { "type": "json_object" } abilita la modalità JSON, che garantisce che il messaggio generato dal modello sia JSON valido. Importante: quando si utilizza la modalità JSON, è necessario istruire anche il modello a produrre JSON autonomamente tramite un messaggio di sistema o utente. In mancanza di ciò, il modello potrebbe generare un flusso infinito di spazi bianchi fino a raggiungere il limite di token, provocando una richiesta di lunga durata e apparentemente "bloccata". Nota inoltre che il contenuto del messaggio potrebbe essere parzialmente troncato se finish_reason="length", il che indica che la generazione ha superato max_tokens o che la conversazione ha superato la lunghezza massima del contesto.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### Vedi anche

* class [ResponseFormat](../../responseformat/)
* class [AssistantResponse](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)