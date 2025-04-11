---
title: Enum ConversionMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.ConversionMode enum. Definierar konverteringsläge för utdata-dokumentet
type: docs
weight: 8500
url: /sv/net/aspose.pdf.plugins/conversionmode/
---
## ConversionMode-uppräkning

Definierar konverteringsläge för utdata-dokumentet.

```csharp
public enum ConversionMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| TextBox | `0` | Detta läge är snabbt och bra för att maximalt bevara det ursprungliga utseendet av PDF-filen, men redigerbarheten av det resulterande dokumentet kan vara begränsad. |
| Flow | `1` | Fullständig igenkänningsläge, motorn utför gruppering och flernivåanalys för att återställa den ursprungliga dokumentförfattarens avsikt och producera ett maximalt redigerbart dokument. Nackdelen är att utdata-dokumentet kan se annorlunda ut än den ursprungliga PDF-filen. |
| EnhancedFlow | `2` | Ett alternativt Flow-läge som stöder igenkänning av tabeller. |

### Se Även

* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)