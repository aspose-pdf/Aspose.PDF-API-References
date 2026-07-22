---
title: "Aspose::Pdf::Optimization::OptimizationOptions klass"
linktitle: "OptimizationOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Optimization::OptimizationOptions klass. Klass som beskriver dokumentoptimeringsalgoritmen. En instans av denna klass kan användas som parameter till metoden OptimizeResources() i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions class


Klassen som beskriver dokumentoptimeringsalgoritmen. En instans av denna klass kan användas som parameter till metoden OptimizeResources().

```cpp
class OptimizationOptions : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [All](./all/)() | Skapar optimeringsstrategi med alla alternativ aktiverade. Observera att endast alternativ som inte förändrar någon funktionalitet i dokumentet aktiveras. Dvs. bildkomprimering och avbäddning av teckensnitt kommer inte att aktiveras (och kan bäddas in manuellt). |
| [get_AllowReusePageContent](./get_allowreusepagecontent/)() const | Om sant kommer sidinnehåll att återanvändas när dokumentet optimeras för lika sidor. |
|  | [get_CompressAllContentStreams](./get_compressallcontentstreams/)() const | Om inställt på **true** |

, alla okomprimerade sidinnehållsströmmar kommer att komprimeras med FlateDecode-filtret under [Document::OptimizeResources()](../../aspose.pdf/document/optimizeresources/). Standard är **false**

för att bevara bakåtkompatibilitet. |
| [get_CompressImages](./get_compressimages/)() | Om denna flagga är satt till true kommer bilder att komprimeras i dokumentet. Komprimeringsnivån anges med egenskapen ImageQuality. |
|  | [get_CompressObjects](./get_compressobjects/)() const | Om denna flagga är satt till **true** |

, [Pdf](../../aspose.pdf/) objekt kommer att packas i Objest Streams och komprimeras för att minska pdf-filens storlek. |
| [get_ImageCompressionOptions](./get_imagecompressionoptions/)() const | Uppsättning av alternativ som beskriver om bilder i dokumentet ska komprimeras och parametrarna för komprimeringen. |
| [get_ImageEncoding](./get_imageencoding/)() const | [Image](../../aspose.pdf/image/) kodning som kommer att användas. |
| [get_ImageQuality](./get_imagequality/)() | Anger komprimeringsnivå för bilder när flaggan CompressIamges används. |
| [get_LinkDuplicateStreams](./get_linkduplicatestreams/)() const | Om denna flagga är satt till true kommer resursströmmar att analyseras. Om dubblettströmmar hittas (dvs. om strömmarnas innehåll är lika) kommer dessa strömmar att lagras som ett objekt. Detta möjliggör minskning av dokumentstorleken i vissa fall (t.ex. när samma dokument har sammanfogats flera gånger). |
| [get_MaxResoultion](./get_maxresoultion/)() | Anger maximal upplösning för bilder. Om en bild har högre upplösning kommer den att skalas. |
| [get_RemovePrivateInfo](./get_removeprivateinfo/)() const | Ta bort privat information (sidstyckeinformation). |
| [get_RemoveUnusedObjects](./get_removeunusedobjects/)() const | Om denna flagga är satt till true kommer alla dokumentobjekt att kontrolleras och oanvända objekt (dvs. objekt som inte har någon referens) tas bort från dokumentet. |
| [get_RemoveUnusedStreams](./get_removeunusedstreams/)() const | Om denna flagga är satt till true kontrolleras varje resurs för dess användning. Om en resurs aldrig används tas resursen bort. Detta kan minska dokumentstorleken, till exempel när sidor har extraherats från dokumentet. |
| [get_ResizeImages](./get_resizeimages/)() | Om denna flagga är satt till true och CompressImages är true kommer bilder att skalas om bildens upplösning är större än den angivna MaxResolution‑parametern. |
| [get_SubsetFonts](./get_subsetfonts/)() const | Typsnitt konverteras till delmängder om de är satta på true. |
| [get_UnembedFonts](./get_unembedfonts/)() const | Gör så att typsnitt inte bäddas in om de är satta på true. |
| [OptimizationOptions](./optimizationoptions/)() |  |
| [set_AllowReusePageContent](./set_allowreusepagecontent/)(bool) | Om sant kommer sidinnehåll att återanvändas när dokumentet optimeras för lika sidor. |
|  | [set_CompressAllContentStreams](./set_compressallcontentstreams/)(bool) | Om inställt på **true** |

, alla okomprimerade sidinnehållsströmmar kommer att komprimeras med FlateDecode-filtret under [Document::OptimizeResources()](../../aspose.pdf/document/optimizeresources/). Standard är **false**

för att bevara bakåtkompatibilitet. |
| [set_CompressImages](./set_compressimages/)(bool) | Om denna flagga är satt till true kommer bilder att komprimeras i dokumentet. Komprimeringsnivån anges med egenskapen ImageQuality. |
|  | [set_CompressObjects](./set_compressobjects/)(bool) | Om denna flagga är satt till **true** |

, [Pdf](../../aspose.pdf/) objekt kommer att packas i Objest Streams och komprimeras för att minska pdf-filens storlek. |
| [set_ImageEncoding](./set_imageencoding/)(Aspose::Pdf::Optimization::ImageEncoding) | [Image](../../aspose.pdf/image/) kodning som kommer att användas. |
| [set_ImageQuality](./set_imagequality/)(int32_t) | Anger komprimeringsnivå för bilder när flaggan CompressIamges används. |
| [set_LinkDuplicateStreams](./set_linkduplicatestreams/)(bool) | Om denna flagga är satt till true kommer resursströmmar att analyseras. Om dubblettströmmar hittas (dvs. om strömmarnas innehåll är lika) kommer dessa strömmar att lagras som ett objekt. Detta möjliggör minskning av dokumentstorleken i vissa fall (t.ex. när samma dokument har sammanfogats flera gånger). |
| [set_MaxResoultion](./set_maxresoultion/)(int32_t) | Anger maximal upplösning för bilder. Om en bild har högre upplösning kommer den att skalas. |
| [set_RemovePrivateInfo](./set_removeprivateinfo/)(bool) | Ta bort privat information (sidstyckeinformation). |
| [set_RemoveUnusedObjects](./set_removeunusedobjects/)(bool) | Om denna flagga är satt till true kommer alla dokumentobjekt att kontrolleras och oanvända objekt (dvs. objekt som inte har någon referens) tas bort från dokumentet. |
| [set_RemoveUnusedStreams](./set_removeunusedstreams/)(bool) | Om denna flagga är satt till true kontrolleras varje resurs för dess användning. Om en resurs aldrig används tas resursen bort. Detta kan minska dokumentstorleken, till exempel när sidor har extraherats från dokumentet. |
| [set_ResizeImages](./set_resizeimages/)(bool) | Om denna flagga är satt till true och CompressImages är true kommer bilder att skalas om bildens upplösning är större än den angivna MaxResolution‑parametern. |
| [set_SubsetFonts](./set_subsetfonts/)(bool) | Typsnitt konverteras till delmängder om de är satta på true. |
| [set_UnembedFonts](./set_unembedfonts/)(bool) | Gör så att typsnitt inte bäddas in om de är satta på true. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Optimization](../)
* Library [Aspose.PDF for C++](../../)
