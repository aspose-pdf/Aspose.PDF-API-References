---
title: Enum ImageDeleteAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImageDeleteAction enum. Åtgärd som utförs med bildobjekt när bilden tas bort från samlingen. Om bildobjektet tas bort
type: docs
weight: 5870
url: /sv/net/aspose.pdf/imagedeleteaction/
---
## ImageDeleteAction-uppräkning

Åtgärd som utförs med bildobjekt när bilden tas bort från samlingen. Om bildobjektet tas bort

```csharp
public enum ImageDeleteAction
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| KeepContents | `0` | Bilden kommer att tas bort från samlingen. Om sidinnehållet innehåller referenser till bilden kommer de inte att tas bort. Dokumentet kan bli ogiltigt. |
| None | `1` | Bilden kommer att tas bort från samlingen och från sidinnehållet, men bildobjektet kommer inte att raderas. Filstorleken kommer inte att minskas. |
| ForceDelete | `2` | Bilden kommer att tas bort från samlingen och bildobjektet kommer att tas bort från dokumentet. Om andra referenser på samma objekt finns kan dokumentet bli korrupt. |
| Check | `3` | Bilden kommer att tas bort från samlingen och bildobjektet kommer endast att tas bort om det inte finns några andra referenser till bilden från andra sidor. Detta kan kräva mer tid i jämförelse med ForceDelete-alternativet. |

### Se Även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)