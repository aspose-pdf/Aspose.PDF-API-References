---
title: "Enum ImageDeleteAction"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.ImageDeleteAction‑enum. Åtgärd som utförs på bildobjektet när bilden tas bort från samlingen. Om bildobjektet tas bort"
type: docs
weight: 6000
url: /sv/net/aspose.pdf/imagedeleteaction/
---
## ImageDeleteAction enumeration

Åtgärd som utförs med bildobjektet när bilden tas bort från samlingen. Om bildobjektet tas bort

```csharp
public enum ImageDeleteAction
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| KeepContents | `0` | Bilden kommer att tas bort från samlingen. Om sidinnehållet innehåller referenser till bilden kommer de inte att tas bort. Dokumentet kan bli ogiltigt. |
| None | `1` | Bilden kommer att tas bort från samlingen och från sidinnehållet, men bildobjektet kommer inte att raderas. Filstorleken kommer inte att minskas. |
| ForceDelete | `2` | Bilden kommer att tas bort från samlingen och bildobjektet kommer att tas bort från dokumentet. Om andra referenser till samma objekt finns kan dokumentet bli korrupt. |
| Check | `3` | Bilden kommer att tas bort från samlingen och bildobjektet kommer att tas bort endast om inga andra referenser till bilden finns från andra sidor. Detta kan kräva mer tid jämfört med alternativet ForceDelete. |

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


