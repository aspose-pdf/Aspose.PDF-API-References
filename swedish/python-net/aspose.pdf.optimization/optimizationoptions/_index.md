---
title: "OptimizationOptions"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klass som beskriver dokumentoptimeringsalgoritmen.<br/>            En instans av denna klass kan användas som parameter till metoden OptimizeResources()."
type: docs
weight: 20
url: /sv/python-net/aspose.pdf.optimization/optimizationoptions/
---

## OptimizationOptions class

Klass som beskriver dokumentoptimeringsalgoritmen.<br/>            En instans av denna klass kan användas som parameter till metoden OptimizeResources().

Typen OptimizationOptions exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| OptimizationOptions() | Initierar en ny instans av klassen OptimizationOptions |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| link_duplcate_streams | Om denna flagga är satt till true analyseras resurströmmar. Om dubblettströmmar hittas (dvs. om strömmarnas innehåll är lika) lagras dessa strömmar som ett objekt. <br/>            Detta möjliggör att minska dokumentstorleken i vissa fall (till exempel när samma dokument har sammanfogats flera gånger). |
| allow_reuse_page_content | Om true återanvänds sidinnehåll när dokumentet optimeras för lika sidor. |
| remove_unused_streams | Om denna flagga är satt till true kontrolleras varje resurs för dess användning. Om en resurs aldrig används tas den bort.<br/>            Detta kan minska dokumentstorleken, till exempel när sidor har extraherats från dokumentet. |
| remove_unused_objects | Om denna flagga är satt till true kontrolleras alla dokumentobjekt och oanvända objekt (dvs. objekt som inte har någon referens) tas bort från dokumentet. |
| image_compression_options | Uppsättning av alternativ som beskriver om bilder i dokumentet ska komprimeras och parametrarna för komprimeringen. |
| compress_images | Om denna flagga är satt till true kommer bilder att komprimeras i dokumentet. komprimeringsnivån specificeras med ImageQuality-egenskapen. |
| resize_images | Om denna flagga är satt till true och CompressImages är true kommer bilder att skalas om om bildens upplösning är större än den angivna MaxResolution-parametern. |
| image_quality | Anger komprimeringsnivån för bilder när CompressIamges-flaggan används. |
| max_resoultion | Anger maximal upplösning för bilder. Om en bild har högre upplösning kommer den att skalas. |
| unembed_fonts | Gör så att typsnitt inte bäddas in om de är satta till true. |
| subset_fonts | Typsnitt kommer att konverteras till delmängder om de är satta till true. |
| remove_private_info | Ta bort privat information (sidstyckeinformation). |
| image_encoding | Bildkodning som kommer att användas. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| all() | Skapar en optimeringsstrategi med alla alternativ aktiverade.<br/>            Observera att endast alternativ som inte förändrar någon funktionalitet i dokumentet aktiveras.<br/>            Dvs. bildkomprimering och avbäddning av typsnitt kommer inte att aktiveras (och kan bäddas in manuellt). |

### Se även

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

