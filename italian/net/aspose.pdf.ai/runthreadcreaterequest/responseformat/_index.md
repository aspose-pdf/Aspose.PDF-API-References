---
title: RunThreadCreateRequest.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: RunThreadCreateRequest property. Gets or sets the format that the model must output. Compatible with GPT4o GPT4 Turbo and all GPT3.5 Turbo models since gpt3.5turbo1106. Setting to  type json_object  enables JSON mode which guarantees the message the model generates is valid JSON. Important when using JSON mode you must also instruct the model to produce JSON yourself via a system or user message. Without this the model may generate an unending stream of whitespace until the generation reaches the token limit resulting in a longrunning and seemingly stuck request. Also note that the message content may be partially cut off if finish_reasonlength which indicates the generation exceeded max_tokens or the conversation exceeded the max context length
type: docs
weight: 80
url: /it/net/aspose.pdf.ai/runthreadcreaterequest/responseformat/
---
## Proprietà RunThreadCreateRequest.ResponseFormat

Ottiene o imposta il formato che il modello deve restituire. Compatibile con GPT-4o, GPT-4 Turbo e tutti i modelli GPT-3.5 Turbo da gpt-3.5-turbo-1106. Impostare a { "type": "json_object" } abilita la modalità JSON, che garantisce che il messaggio generato dal modello sia un JSON valido. Importante: quando si utilizza la modalità JSON, è necessario anche istruire il modello a produrre JSON da solo tramite un messaggio di sistema o utente. Senza questo, il modello potrebbe generare un flusso infinito di spazi bianchi fino a quando la generazione non raggiunge il limite di token, risultando in una richiesta a lungo termine e apparentemente "bloccata". Nota anche che il contenuto del messaggio potrebbe essere parzialmente tagliato se finish_reason="length", il che indica che la generazione ha superato max_tokens o la conversazione ha superato la lunghezza massima del contesto.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### Vedi Anche

* classe [ResponseFormat](../../responseformat/)
* classe [RunThreadCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)