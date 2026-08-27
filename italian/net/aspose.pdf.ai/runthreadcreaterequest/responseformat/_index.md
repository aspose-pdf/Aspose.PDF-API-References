---
title: "RunThreadCreateRequest.ResponseFormat"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà RunThreadCreateRequest. Ottiene o imposta il formato che il modello deve restituire. Compatibile con GPT4o, GPT4 Turbo e tutti i modelli GPT3.5 Turbo a partire da gpt3.5turbo1106. Impostare su type json_object abilita la modalità JSON, che garantisce che il messaggio generato dal modello sia JSON valido. È importante, quando si utilizza la modalità JSON, istruire anche il modello a produrre JSON tramite un messaggio di sistema o utente. Senza ciò, il modello potrebbe generare un flusso infinito di spazi bianchi fino a quando la generazione raggiunge il limite di token, risultando in una richiesta a lunga esecuzione e apparentemente bloccata. Inoltre, nota che il contenuto del messaggio potrebbe essere parzialmente troncato se finish_reasonlength, che indica che la generazione ha superato max_tokens o che la conversazione ha superato la lunghezza massima del contesto."
type: docs
weight: 80
url: /it/net/aspose.pdf.ai/runthreadcreaterequest/responseformat/
---
## RunThreadCreateRequest.ResponseFormat property

Ottiene o imposta il formato che il modello deve produrre. Compatibile con GPT-4o, GPT-4 Turbo e tutti i modelli GPT-3.5 Turbo a partire da gpt-3.5-turbo-1106. Impostare a { \"type\": \"json_object\" } abilita la modalità JSON, che garantisce che il messaggio generato dal modello sia JSON valido. Importante: quando si utilizza la modalità JSON, è necessario anche istruire il modello a produrre JSON tramite un messaggio di sistema o utente. Senza ciò, il modello potrebbe generare un flusso infinito di spazi bianchi finché la generazione non raggiunge il limite di token, risultando in una richiesta a lunga durata e apparentemente \"bloccata\". Nota inoltre che il contenuto del messaggio potrebbe essere parzialmente troncato se finish_reason=\"length\", il che indica che la generazione ha superato max_tokens o che la conversazione ha superato la lunghezza massima del contesto.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### Vedi anche

* class [ResponseFormat](../../responseformat/)
* class [RunThreadCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


