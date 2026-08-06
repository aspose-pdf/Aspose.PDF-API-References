---
title: "ImageCompressionOptions"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klassen innehåller en uppsättning alternativ för bildkomprimering."
type: docs
weight: 10
url: /sv/python-net/aspose.pdf.optimization/imagecompressionoptions/
---

## ImageCompressionOptions class

Klassen innehåller en uppsättning alternativ för bildkomprimering.

Typen ImageCompressionOptions exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| ImageCompressionOptions() | Initierar en ny instans av klassen ImageCompressionOptions |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| compress_images | Om denna flagga är satt till true kommer bilder att komprimeras i dokumentet. komprimeringsnivån specificeras med ImageQuality-egenskapen. |
| resize_images | Om denna flagga är satt till true och CompressImages är true kommer bilder att skalas om om bildens upplösning är större än den angivna MaxResolution-parametern. |
| image_quality | Anger komprimeringsnivån för bilder när CompressIamges-flaggan används. |
| max_resolution | Anger maximal upplösning för bilder. Om en bild har högre upplösning kommer den att skalas. |
| version | Version av komprimeringsalgoritmen. Möjliga värden är: 1. standardkomprimering, 2. fast (förbättrad komprimering som är snabbare än standard men kan vara otillämplig för vissa bilder), 3. blandad (standardkomprimering tillämpas på bilder som inte kan komprimeras med den snabbare algoritmen, detta kan ge bästa komprimering men är långsammare än \"fast\"-algoritmen. Version \"Fast\" är inte tillämplig för storleksändring av bilder (standardmetoden kommer att användas). Standard är \"Standard\".) |
| kodning | Hämtar eller anger kodning som används för att lagra bilder. |

### Se även

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

