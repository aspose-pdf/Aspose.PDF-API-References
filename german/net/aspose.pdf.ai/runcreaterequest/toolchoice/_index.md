---
title: RunCreateRequest.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: RunCreateRequest-Eigenschaft. Gibt an, welches Werkzeug vom Modell aufgerufen wird. none bedeutet, dass das Modell keine Werkzeuge aufruft und stattdessen eine Nachricht generiert. auto ist der Standardwert und bedeutet, dass das Modell zwischen der Generierung einer Nachricht oder dem Aufruf eines oder mehrerer Werkzeuge wählen kann. required bedeutet, dass das Modell ein oder mehrere Werkzeuge aufrufen muss, bevor es auf den Benutzer antwortet. Das Angeben eines bestimmten Werkzeugs wie {"type": "file_search"} oder {"type": "function", "function": {"name": "my_function"}} zwingt das Modell, dieses Werkzeug aufzurufen.
type: docs
weight: 130
url: /de/net/aspose.pdf.ai/runcreaterequest/toolchoice/
---
## RunCreateRequest.ToolChoice-Eigenschaft

Gibt an, welches (falls vorhanden) Werkzeug vom Modell aufgerufen wird. none bedeutet, dass das Modell keine Werkzeuge aufruft und stattdessen eine Nachricht generiert. auto ist der Standardwert und bedeutet, dass das Modell zwischen der Generierung einer Nachricht oder dem Aufruf eines oder mehrerer Werkzeuge wählen kann. required bedeutet, dass das Modell ein oder mehrere Werkzeuge aufrufen muss, bevor es auf den Benutzer antwortet. Das Angeben eines bestimmten Werkzeugs wie {"type": "file_search"} oder {"type": "function", "function": {"name": "my_function"}} zwingt das Modell, dieses Werkzeug aufzurufen.

```csharp
public string ToolChoice { get; set; }
```

### Siehe auch

* Klasse [RunCreateRequest](../)
* Namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../../)