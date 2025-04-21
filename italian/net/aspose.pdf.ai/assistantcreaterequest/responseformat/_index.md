---
title: AssistantCreateRequest.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: Proprietà AssistantCreateRequest. Ottiene o imposta il formato che il modello deve restituire. Compatibile con GPT-4o, GPT-4 Turbo e tutti i modelli GPT-3.5 Turbo da gpt-3.5-turbo-1106. Impostare a "type" "json_object" abilita la modalità JSON, che garantisce che il messaggio generato dal modello sia un JSON valido. Importante quando si utilizza la modalità JSON, è necessario anche istruire il modello a produrre JSON autonomamente tramite un messaggio di sistema o utente. Senza questo, il modello potrebbe generare un flusso infinito di spazi bianchi fino a quando la generazione non raggiunge il limite di token, risultando in una richiesta a lungo termine e apparentemente "bloccata". Nota anche che il contenuto del messaggio potrebbe essere parzialmente tagliato se finish_reason="length", il che indica che la generazione ha superato max_tokens o la conversazione ha superato la lunghezza massima del contesto.
type: docs
weight: 70
url: /it/net/aspose.pdf.ai/assistantcreaterequest/responseformat/
---
## Proprietà AssistantCreateRequest.ResponseFormat

Ottiene o imposta il formato che il modello deve restituire. Compatibile con GPT-4o, GPT-4 Turbo e tutti i modelli GPT-3.5 Turbo da gpt-3.5-turbo-1106. Impostare a { "type": "json_object" } abilita la modalità JSON, che garantisce che il messaggio generato dal modello sia un JSON valido. Importante: quando si utilizza la modalità JSON, è necessario anche istruire il modello a produrre JSON autonomamente tramite un messaggio di sistema o utente. Senza questo, il modello potrebbe generare un flusso infinito di spazi bianchi fino a quando la generazione non raggiunge il limite di token, risultando in una richiesta a lungo termine e apparentemente "bloccata". Nota anche che il contenuto del messaggio potrebbe essere parzialmente tagliato se finish_reason="length", il che indica che la generazione ha superato max_tokens o la conversazione ha superato la lunghezza massima del contesto.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### Vedi Anche

* classe [ResponseFormat](../../responseformat/)
* classe [AssistantCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)