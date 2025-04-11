---
title: Enum LineJoin
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.LineJoin enum. Linjeanslutningsstilen ska specificera formen som ska användas vid hörnen av vägar som är strukna
type: docs
weight: 7450
url: /sv/net/aspose.pdf.operators/linejoin/
---
## LineJoin-uppräkning

Linjeanslutningsstilen ska specificera formen som ska användas vid hörnen av vägar som är strukna.

```csharp
public enum LineJoin
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| MiterJoin | `0` | Miteranslutning. De yttre kanterna av sträckorna för de två segmenten ska förlängas tills de möts i en vinkel, som i en bildram. Om segmenten möts i en för skarp vinkel enligt mitergränsparametern (se 8.4.3.5, "Miter Limit"), ska en fasad anslutning användas istället. |
| RoundJoin | `1` | Rund anslutning. En båge av en cirkel med en diameter som är lika med linjebredden ska dras runt punkten där de två segmenten möts, vilket kopplar samman de yttre kanterna av sträckorna för de två segmenten. Denna tårtbitar-formade figur ska fyllas i, vilket ger ett rundat hörn. |
| BevelJoin | `2` | Fasad anslutning. De två segmenten ska avslutas med rak kap (se 8.4.3.3, "Line Cap Style") och den resulterande urgröpningen bortom ändarna av segmenten ska fyllas med en triangel. |

### Se Även

* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)