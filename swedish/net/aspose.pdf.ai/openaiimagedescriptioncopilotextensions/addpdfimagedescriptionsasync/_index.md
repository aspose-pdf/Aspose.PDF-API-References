---
title: OpenAIImageDescriptionCopilotExtensions.AddPdfImageDescriptionsAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIImageDescriptionCopilotExtensions-metod. Asynkront lägger till bildbeskrivningar till en PDF-fil och sparar nya dokument i angivna mappar
type: docs
weight: 10
url: /sv/net/aspose.pdf.ai/openaiimagedescriptioncopilotextensions/addpdfimagedescriptionsasync/
---
## OpenAIImageDescriptionCopilotExtensions.AddPdfImageDescriptionsAsync metod

Asynkront lägger till bildbeskrivningar till en PDF-fil och sparar nya dokument i angivna mappar.

```csharp
public static Task AddPdfImageDescriptionsAsync(
    this IImageDescriptionCopilot imageDescriptionCopilot, string outputDirectory, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageDescriptionCopilot | IImageDescriptionCopilot | Bildbeskrivningscopilot. |
| outputDirectory | Sträng | Utmatningskatalogen där de utmatade PDF-filerna ska sparas. |
| cancellationToken | Nullable`1 | Avbokningstoken (valfritt). |

### Returvärde

En uppgift som representerar den asynkrona operationen.

### Se Även

* interface [IImageDescriptionCopilot](../../iimagedescriptioncopilot/)
* class [OpenAIImageDescriptionCopilotExtensions](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)