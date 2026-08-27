---
title: "Enum LineJoin"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Operators.LineJoin enum. Linjeanslutningsstilen ska ange formen som används i hörnen på banor som strekas."
type: docs
weight: 7590
url: /sv/net/aspose.pdf.operators/linejoin/
---
## LineJoin enumeration

Linjekopplingsstilen ska ange formen som ska användas i hörnen på banor som strokas.

```csharp
public enum LineJoin
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| MiterJoin | `0` | Miter-anslutning. De yttre kanterna på penseldragen för de två segmenten ska förlängas tills de möts i en vinkel, som i en bildram. Om segmenten möts i en för skarp vinkel enligt mitergränsparametern (se 8.4.3.5, "Miter Limit"), ska en avfasad anslutning användas istället. |
| RoundJoin | `1` | Rund anslutning. En båge av en cirkel med en diameter lika med linjebredden ska ritas runt punkten där de två segmenten möts, och koppla ihop de yttre kanterna på penseldragen för de två segmenten. Denna pajskivaformade figur ska fyllas i, vilket ger ett avrundat hörn. |
| BevelJoin | `2` | Avfasad anslutning. De två segmenten ska avslutas med butt-kapper (se 8.4.3.3, "Line Cap Style") och den resulterande spåret bortom segmentens ändar ska fyllas med en triangel. |

### Se även

* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


