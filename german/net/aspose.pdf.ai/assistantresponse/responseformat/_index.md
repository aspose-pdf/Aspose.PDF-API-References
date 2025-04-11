---
title: AssistantResponse.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: AssistantResponse-Eigenschaft. Legt das Format fest, das das Modell ausgeben muss. Kompatibel mit GPT-4o, GPT-4 Turbo und allen GPT-3.5 Turbo-Modellen seit gpt-3.5-turbo-1106. Das Setzen auf { "type": "json_object" } aktiviert den JSON-Modus, der garantiert, dass die vom Modell generierte Nachricht gültiges JSON ist. Wichtig: Wenn Sie den JSON-Modus verwenden, müssen Sie das Modell auch anweisen, selbst über eine System- oder Benutzernachricht JSON zu erzeugen. Andernfalls kann das Modell einen unendlichen Strom von Leerzeichen erzeugen, bis die Generierung das Token-Limit erreicht, was zu einer lang laufenden und scheinbar "festgefahrenen" Anfrage führt. Beachten Sie auch, dass der Nachrichteninhalt teilweise abgeschnitten werden kann, wenn finish_reason="length" ist, was darauf hinweist, dass die Generierung die max_tokens überschritten hat oder das Gespräch die maximale Kontextlänge überschritten hat.
type: docs
weight: 100
url: /de/net/aspose.pdf.ai/assistantresponse/responseformat/
---
## AssistantResponse.ResponseFormat-Eigenschaft

Legt das Format fest, das das Modell ausgeben muss. Kompatibel mit GPT-4o, GPT-4 Turbo und allen GPT-3.5 Turbo-Modellen seit gpt-3.5-turbo-1106. Das Setzen auf { "type": "json_object" } aktiviert den JSON-Modus, der garantiert, dass die vom Modell generierte Nachricht gültiges JSON ist. Wichtig: Wenn Sie den JSON-Modus verwenden, müssen Sie das Modell auch anweisen, selbst über eine System- oder Benutzernachricht JSON zu erzeugen. Andernfalls kann das Modell einen unendlichen Strom von Leerzeichen erzeugen, bis die Generierung das Token-Limit erreicht, was zu einer lang laufenden und scheinbar "festgefahrenen" Anfrage führt. Beachten Sie auch, dass der Nachrichteninhalt teilweise abgeschnitten werden kann, wenn finish_reason="length" ist, was darauf hinweist, dass die Generierung die max_tokens überschritten hat oder das Gespräch die maximale Kontextlänge überschritten hat.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### Siehe auch

* Klasse [ResponseFormat](../../responseformat/)
* Klasse [AssistantResponse](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)