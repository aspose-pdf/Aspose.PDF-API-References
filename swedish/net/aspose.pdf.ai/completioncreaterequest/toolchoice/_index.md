---
title: "CompletionCreateRequest.ToolChoice"
second_title: "Aspose.PDF för .NET API‑referens"
description: "CompletionCreateRequest-egenskap. Hämtar eller anger ett objekt som styr vilket, om något, verktyg som modellen anropar. none betyder att modellen inte kommer att anropa något verktyg utan istället genererar ett meddelande. auto betyder att modellen kan välja mellan att generera ett meddelande eller anropa ett eller flera verktyg. required betyder att modellen måste anropa ett eller flera verktyg. Att specificera ett särskilt verktyg via type function function name my_function tvingar modellen att anropa det verktyget. none är standard när inga verktyg finns. auto är standard när verktyg finns."
type: docs
weight: 150
url: /sv/net/aspose.pdf.ai/completioncreaterequest/toolchoice/
---
## CompletionCreateRequest.ToolChoice property

Hämtar eller anger ett objekt som styr vilket (om något) verktyg som modellen anropar. none betyder att modellen inte kommer att anropa något verktyg utan istället genererar ett meddelande. auto betyder att modellen kan välja mellan att generera ett meddelande eller anropa ett eller flera verktyg. required betyder att modellen måste anropa ett eller flera verktyg. Att specificera ett särskilt verktyg via {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} tvingar modellen att anropa det verktyget. none är standard när inga verktyg finns. auto är standard om verktyg finns.

```csharp
public ToolChoice ToolChoice { get; set; }
```

### Se även

* class [ToolChoice](../../toolchoice/)
* class [CompletionCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


