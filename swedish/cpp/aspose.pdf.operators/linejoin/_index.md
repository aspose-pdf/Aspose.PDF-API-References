---
title: "Aspose::Pdf::Operators::LineJoin enum"
linktitle: "LineJoin"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Operators::LineJoin enum. Linjeanslutningsstilen ska specificera formen som ska användas i hörnen på banor som strokas i C++."
type: docs
weight: 8400
url: /sv/cpp/aspose.pdf.operators/linejoin/
---
## LineJoin enum


Linjekopplingsstilen ska ange formen som ska användas i hörnen på banor som ritas.

```cpp
enum class LineJoin
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| MiterJoin | 0 | Miter-anslutning. De yttre kanterna på strecken för de två segmenten ska förlängas tills de möts i en vinkel, som i en bildram. Om segmenten möts i en för skarp vinkel enligt mitergränsparametern (se 8.4.3.5, \"Miter Limit\"), ska en fasningsanslutning användas istället. |
| RoundJoin | 1 | Rund anslutning. En båge av en cirkel med en diameter lika med linjebredden ska ritas runt punkten där de två segmenten möts, och koppla de yttre kanterna på strecken för de två segmenten. Denna pajskivaformade figur ska fyllas i, vilket ger ett avrundat hörn. |
| BevelJoin | 2 | Fasningsanslutning. De två segmenten ska avslutas med butt-kapper (se 8.4.3.3, \"Line Cap Style\") och den resulterande notchen bortom segmentens ändar ska fyllas med en triangel. |

## Se även

* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
