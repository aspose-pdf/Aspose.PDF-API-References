---
title: CompletionCreateRequest.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: CompletionCreateRequest-Eigenschaft. Ruft ein Objekt ab oder legt es fest, das steuert, welches Werkzeug vom Modell aufgerufen wird. none bedeutet, dass das Modell kein Werkzeug aufruft und stattdessen eine Nachricht generiert. auto bedeutet, dass das Modell zwischen der Generierung einer Nachricht oder dem Aufruf eines oder mehrerer Werkzeuge wählen kann. required bedeutet, dass das Modell ein oder mehrere Werkzeuge aufrufen muss. Das Festlegen eines bestimmten Werkzeugs über "type": "function", "function": "name": "my_function" zwingt das Modell, dieses Werkzeug aufzurufen. none ist der Standard, wenn keine Werkzeuge vorhanden sind. auto ist der Standard, wenn Werkzeuge vorhanden sind.
type: docs
weight: 150
url: /de/net/aspose.pdf.ai/completioncreaterequest/toolchoice/
---
## CompletionCreateRequest.ToolChoice-Eigenschaft

Ruft ein Objekt ab oder legt es fest, das steuert, welches (falls vorhanden) Werkzeug vom Modell aufgerufen wird. none bedeutet, dass das Modell kein Werkzeug aufruft und stattdessen eine Nachricht generiert. auto bedeutet, dass das Modell zwischen der Generierung einer Nachricht oder dem Aufruf eines oder mehrerer Werkzeuge wählen kann. required bedeutet, dass das Modell ein oder mehrere Werkzeuge aufrufen muss. Das Festlegen eines bestimmten Werkzeugs über {"type": "function", "function": {"name": "my_function"}} zwingt das Modell, dieses Werkzeug aufzurufen. none ist der Standard, wenn keine Werkzeuge vorhanden sind. auto ist der Standard, wenn Werkzeuge vorhanden sind.

```csharp
public ToolChoice ToolChoice { get; set; }
```

### Siehe auch

* Klasse [ToolChoice](../../toolchoice/)
* Klasse [CompletionCreateRequest](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)