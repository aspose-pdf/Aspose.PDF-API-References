---
title: "RunCreateRequest.ToolChoice"
second_title: "Aspose.PDF för .NET API‑referens"
description: "RunCreateRequest property. Hämtar eller anger vilken, om någon, verktyg som anropas av modellen. none betyder att modellen inte kommer att anropa några verktyg utan istället genererar ett meddelande. auto är standardvärdet och betyder att modellen kan välja mellan att generera ett meddelande eller anropa ett eller flera verktyg. required betyder att modellen måste anropa ett eller flera verktyg innan den svarar användaren. Att specificera ett särskilt verktyg som typ file_search eller typ function med funktionsnamnet my_function tvingar modellen att anropa det verktyget"
type: docs
weight: 130
url: /sv/net/aspose.pdf.ai/runcreaterequest/toolchoice/
---
## RunCreateRequest.ToolChoice property

Hämtar eller anger vilket (om något) verktyg som modellen anropar. none betyder att modellen inte kommer att anropa några verktyg utan istället genererar ett meddelande. auto är standardvärdet och betyder att modellen kan välja mellan att generera ett meddelande eller anropa ett eller flera verktyg. required betyder att modellen måste anropa ett eller flera verktyg innan den svarar användaren. Att specificera ett särskilt verktyg som {"type": "file_search"} eller {"type": "function", "function": {"name": "my_function"}} tvingar modellen att anropa det verktyget.

```csharp
public string ToolChoice { get; set; }
```

### Se även

* class [RunCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


