---
title: CompletionCreateRequest.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: CompletionCreateRequest-egenskap. Hämtar eller ställer in ett objekt som kontrollerar vilken (om någon) verktyg som anropas av modellen. none betyder att modellen inte kommer att anropa något verktyg och istället genererar ett meddelande. auto betyder att modellen kan välja mellan att generera ett meddelande eller anropa ett eller flera verktyg. required betyder att modellen måste anropa ett eller flera verktyg. Att specificera ett särskilt verktyg via {"type": "function", "function": {"name": "my_function"}} tvingar modellen att anropa det verktyget. none är standard när inga verktyg är närvarande. auto är standard om verktyg är närvarande.
type: docs
weight: 150
url: /sv/net/aspose.pdf.ai/completioncreaterequest/toolchoice/
---
## CompletionCreateRequest.ToolChoice-egenskap

Hämtar eller ställer in ett objekt som kontrollerar vilket (om någon) verktyg som anropas av modellen. none betyder att modellen inte kommer att anropa något verktyg och istället genererar ett meddelande. auto betyder att modellen kan välja mellan att generera ett meddelande eller anropa ett eller flera verktyg. required betyder att modellen måste anropa ett eller flera verktyg. Att specificera ett särskilt verktyg via {"type": "function", "function": {"name": "my_function"}} tvingar modellen att anropa det verktyget. none är standard när inga verktyg är närvarande. auto är standard om verktyg är närvarande.

```csharp
public ToolChoice ToolChoice { get; set; }
```

### Se Även

* klass [ToolChoice](../../toolchoice/)
* klass [CompletionCreateRequest](../)
* namnrymd [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* sammansättning [Aspose.PDF](../../../)