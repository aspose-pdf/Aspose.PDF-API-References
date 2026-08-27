---
title: "CompletionCreateRequest.ToolChoice"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "CompletionCreateRequest property. Ottiene o imposta un oggetto che controlla quale, se presente, strumento viene chiamato dal modello. none indica che il modello non chiamerà alcuno strumento e genererà invece un messaggio. auto indica che il modello può scegliere tra generare un messaggio o chiamare uno o più strumenti. required indica che il modello deve chiamare uno o più strumenti. Specificare uno strumento particolare tramite type function function name my_function costringe il modello a chiamare quello strumento. none è il valore predefinito quando non sono presenti strumenti. auto è il valore predefinito se sono presenti strumenti."
type: docs
weight: 150
url: /it/net/aspose.pdf.ai/completioncreaterequest/toolchoice/
---
## CompletionCreateRequest.ToolChoice property

Ottiene o imposta un oggetto che controlla quale (se presente) strumento è chiamato dal modello. none significa che il modello non chiamerà alcuno strumento e genererà invece un messaggio. auto significa che il modello può scegliere tra generare un messaggio o chiamare uno o più strumenti. required significa che il modello deve chiamare uno o più strumenti. Specificare uno strumento particolare tramite {"type": "function", "function": {"name": "my_function"}} forza il modello a chiamare quello strumento. none è il valore predefinito quando non sono presenti strumenti. auto è il valore predefinito se sono presenti strumenti.

```csharp
public ToolChoice ToolChoice { get; set; }
```

### Vedi anche

* class [ToolChoice](../../toolchoice/)
* class [CompletionCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


