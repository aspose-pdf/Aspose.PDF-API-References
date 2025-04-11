---
title: RunCreateRequest.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: RunCreateRequest-egenskap. Hämtar eller ställer in vilken (om någon) verktyg som anropas av modellen. none betyder att modellen inte kommer att anropa några verktyg och istället genererar ett meddelande. auto är standardvärdet och betyder att modellen kan välja mellan att generera ett meddelande eller anropa ett eller flera verktyg. required betyder att modellen måste anropa ett eller flera verktyg innan den svarar användaren. Att specificera ett särskilt verktyg som {"type": "file_search"} eller {"type": "function", "function": {"name": "my_function"}} tvingar modellen att anropa det verktyget.
type: docs
weight: 130
url: /sv/net/aspose.pdf.ai/runcreaterequest/toolchoice/
---
## RunCreateRequest.ToolChoice-egenskap

Hämtar eller ställer in vilket (om något) verktyg som anropas av modellen. none betyder att modellen inte kommer att anropa några verktyg och istället genererar ett meddelande. auto är standardvärdet och betyder att modellen kan välja mellan att generera ett meddelande eller anropa ett eller flera verktyg. required betyder att modellen måste anropa ett eller flera verktyg innan den svarar användaren. Att specificera ett särskilt verktyg som {"type": "file_search"} eller {"type": "function", "function": {"name": "my_function"}} tvingar modellen att anropa det verktyget.

```csharp
public string ToolChoice { get; set; }
```

### Se Även

* klass [RunCreateRequest](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../../)