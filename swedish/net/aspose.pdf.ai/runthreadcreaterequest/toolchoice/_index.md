---
title: RunThreadCreateRequest.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: RunThreadCreateRequest-egenskap. Hämtar eller ställer in vilken verktyg som anropas av modellen. none betyder att modellen inte kommer att anropa några verktyg och istället genererar ett meddelande. auto är standardvärdet och betyder att modellen kan välja mellan att generera ett meddelande eller anropa ett eller flera verktyg. required betyder att modellen måste anropa ett eller flera verktyg innan den svarar användaren. Att specificera ett särskilt verktyg som "type" "file_search" eller "type" "function", "function" "name" "my_function" tvingar modellen att anropa det verktyget.
type: docs
weight: 120
url: /sv/net/aspose.pdf.ai/runthreadcreaterequest/toolchoice/
---
## RunThreadCreateRequest.ToolChoice-egenskap

Hämtar eller ställer in vilket (om något) verktyg som anropas av modellen. none betyder att modellen inte kommer att anropa några verktyg och istället genererar ett meddelande. auto är standardvärdet och betyder att modellen kan välja mellan att generera ett meddelande eller anropa ett eller flera verktyg. required betyder att modellen måste anropa ett eller flera verktyg innan den svarar användaren. Att specificera ett särskilt verktyg som {"type": "file_search"} eller {"type": "function", "function": {"name": "my_function"}} tvingar modellen att anropa det verktyget.

```csharp
public string ToolChoice { get; set; }
```

### Se Även

* klass [RunThreadCreateRequest](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../../)