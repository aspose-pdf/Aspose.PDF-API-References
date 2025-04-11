---
title: Class ToUnicodeProcessingRules
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ToUnicodeProcessingRules klass. Denna klass beskriver regler som kan användas för att lösa Adobe Preflight-fel "Text kan inte mappas till Unicode"
type: docs
weight: 11110
url: /sv/net/aspose.pdf/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules klass

Denna klass beskriver regler som kan användas för att lösa Adobe Preflight-fel "Text kan inte mappas till Unicode".

```csharp
public class ToUnicodeProcessingRules
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | Initierar en ny instans av klassen `ToUnicodeProcessingRules`. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | Initierar en ny instans av klassen `ToUnicodeProcessingRules` med det angivna alternativet att ta bort mellanslag från CMap-namn. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | Initierar en ny instans av klassen `ToUnicodeProcessingRules` med angivna alternativ. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | Vissa typsnitt tillhandahåller inte information om unicodes för vissa textsymboler. Denna brist på information orsakar ett fel "Text kan inte mappas till Unicode". Använd denna flagga för att mappa icke-länkade symboler på unicode "mellanslag" (kod 32). |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | Vissa typsnitt har ToUnicode-teckenkodkartor med mellanslag i namnen. Dessa mellanslag kan orsaka fel med unicode-textmappning. Denna flagga kommanderar att ta bort mellanslag från namnen på ToUnicode-teckenkodkartor. Som standard falskt. |

### Se Även

* namnrum [Aspose.Pdf](../../aspose.pdf/)
* samling [Aspose.PDF](../../)