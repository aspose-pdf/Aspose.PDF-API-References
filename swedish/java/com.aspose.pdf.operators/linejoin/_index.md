---
title: "LineJoin"
linktitle: "LineJoin"
second_title: "Aspose.PDF för Java API-referens"
description: "Linjeföreningsstilen ska ange formen som ska användas i hörnen på vägar som penslas."
type: docs
weight: 370
url: /sv/java/com.aspose.pdf.operators/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.operators.LineJoin, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.operators.LineJoin, com.aspose.ms.System.Enum, com.aspose.pdf.operators.LineJoin

```
public final class LineJoin extends com.aspose.ms.System.Enum
```

Linjeföreningsstilen ska ange formen som ska användas i hörnen på vägar som penslas.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [BevelJoin](#BevelJoin) | Fasettfog. De två segmenten ska avslutas med butt-kappar (se 8.4.3.3, "Line Cap Style") och den resulterande notchen bortom segmentens ändar ska fyllas med en triangel. |
| [MiterJoin](#MiterJoin) | Miterfog. De yttre kanterna på strecken för de två segmenten ska förlängas tills de möts i en vinkel, som i en bildram. Om segmenten möts i en för skarp vinkel enligt mitergränsparametern (se 8.4.3.5, "Miter Limit"), ska en fasettfog användas istället. |
| [RoundJoin](#RoundJoin) | Rund fog. En båge av en cirkel med en diameter lika med linjebredden ska ritas runt punkten där de två segmenten möts, och koppla de yttre kanterna på strecken för de två segmenten. Denna pajliknande figur ska fyllas i, vilket ger ett avrundat hörn. |

### BevelJoin {#BevelJoin}
```
public static final int BevelJoin
```

Fasettfog. De två segmenten ska avslutas med butt-kappar (se 8.4.3.3, "Line Cap Style") och den resulterande notchen bortom segmentens ändar ska fyllas med en triangel.

### MiterJoin {#MiterJoin}
```
public static final int MiterJoin
```

Miterfog. De yttre kanterna på strecken för de två segmenten ska förlängas tills de möts i en vinkel, som i en bildram. Om segmenten möts i en för skarp vinkel enligt mitergränsparametern (se 8.4.3.5, "Miter Limit"), ska en fasettfog användas istället.

### RoundJoin {#RoundJoin}
```
public static final int RoundJoin
```

Rund fog. En båge av en cirkel med en diameter lika med linjebredden ska ritas runt punkten där de två segmenten möts, och koppla de yttre kanterna på strecken för de två segmenten. Denna pajliknande figur ska fyllas i, vilket ger ett avrundat hörn.
