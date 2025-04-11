---
title: Class Tool
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.Tool klass. Representerar ett verktyg som kan anropas av modellen
type: docs
weight: 1190
url: /sv/net/aspose.pdf.ai/tool/
---
## Verktygsklass

Representerar ett verktyg som kan anropas av modellen.

```csharp
public class Tool
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Tool](tool/#constructor)() | Initierar en ny instans av `Tool` klassen. |
| [Tool](tool/#constructor_1)(Function) | Initierar en ny instans av `Tool` klassen med den angivna funktionen. |
| [Tool](tool/#constructor_2)(string) | Initierar en ny instans av `Tool` klassen med den angivna verktygstypen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [CodeInterpreter](../../aspose.pdf.ai/tool/codeinterpreter/) { get; } | Hämtar en verktygsinstans som representerar en kodtolk. |
| static [FileSearch](../../aspose.pdf.ai/tool/filesearch/) { get; } | Hämtar en verktygsinstans som representerar ett fil sökverktyg. |
| [ToolFunction](../../aspose.pdf.ai/tool/toolfunction/) { get; set; } | Hämtar eller ställer in funktionen som modellen kan anropa. |
| [ToolType](../../aspose.pdf.ai/tool/tooltype/) { get; set; } | Hämtar eller ställer in typen av verktyget. För närvarande stöds endast funktion. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Function](../../aspose.pdf.ai/tool/function/)(Function) | Skapar en ny verktygsinstans med den angivna funktionen. |

### Se Även

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)