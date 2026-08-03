---
title: "RunThreadCreateRequest.ToolChoice"
second_title: "Aspose.PDF för .NET API‑referens"
description: "RunThreadCreateRequest-egenskap. Hämtar eller anger vilket, om något, verktyg som anropas av modellen. none betyder att modellen inte kommer att anropa några verktyg utan istället genererar ett meddelande. auto är standardvärdet och betyder att modellen kan välja mellan att generera ett meddelande eller att anropa ett eller flera verktyg. required betyder att modellen måste anropa ett eller flera verktyg innan den svarar användaren. Att specificera ett särskilt verktyg som type file_search eller type function function name my_function tvingar modellen att anropa det verktyget."
type: docs
weight: 120
url: /sv/net/aspose.pdf.ai/runthreadcreaterequest/toolchoice/
---
## RunThreadCreateRequest.ToolChoice property

Hämtar eller anger vilket (om något) verktyg som modellen anropar. none betyder att modellen inte kommer att anropa några verktyg utan istället genererar ett meddelande. auto är standardvärdet och betyder att modellen kan välja mellan att generera ett meddelande eller anropa ett eller flera verktyg. required betyder att modellen måste anropa ett eller flera verktyg innan den svarar användaren. Att specificera ett särskilt verktyg som {"type": "file_search"} eller {"type": "function", "function": {"name": "my_function"}} tvingar modellen att anropa det verktyget.

```csharp
public string ToolChoice { get; set; }
```

### Se även

* class [RunThreadCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


