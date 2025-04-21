---
title: RunResponse.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: Proprietà di RunResponse. Ottiene o imposta quale strumento, se presente, è chiamato dal modello. none significa che il modello non chiamerà alcuno strumento e invece genera un messaggio. auto è il valore predefinito e significa che il modello può scegliere tra generare un messaggio o chiamare uno o più strumenti. required significa che il modello deve chiamare uno o più strumenti prima di rispondere all'utente. Specificare uno strumento particolare come "type" "file_search" o "type" "function", "function" "name" "my_function" costringe il modello a chiamare quello strumento.
type: docs
weight: 230
url: /it/net/aspose.pdf.ai/runresponse/toolchoice/
---
## Proprietà RunResponse.ToolChoice

Ottiene o imposta quale (se presente) strumento è chiamato dal modello. none significa che il modello non chiamerà alcuno strumento e invece genera un messaggio. auto è il valore predefinito e significa che il modello può scegliere tra generare un messaggio o chiamare uno o più strumenti. required significa che il modello deve chiamare uno o più strumenti prima di rispondere all'utente. Specificare uno strumento particolare come {"type": "file_search"} o {"type": "function", "function": {"name": "my_function"}} costringe il modello a chiamare quello strumento.

```csharp
public string ToolChoice { get; set; }
```

### Vedi Anche

* classe [RunResponse](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)