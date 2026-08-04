---
title: "ImageCompressionOptions"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse enthält eine Reihe von Optionen für die Bildkompression."
type: docs
weight: 10
url: /de/python-net/aspose.pdf.optimization/imagecompressionoptions/
---

## ImageCompressionOptions class

Klasse enthält eine Reihe von Optionen für die Bildkompression.

Der Typ ImageCompressionOptions stellt die folgenden Member bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| ImageCompressionOptions() | Initialisiert eine neue Instanz der Klasse ImageCompressionOptions |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| compress_images | Wenn dieses Flag auf true gesetzt ist, werden Bilder im Dokument komprimiert. Die Komprimierungsstufe wird mit der Eigenschaft ImageQuality angegeben. |
| resize_images | Wenn dieses Flag auf true gesetzt ist und CompressImages true ist, werden Bilder verkleinert, wenn die Bildauflösung größer als der angegebene Parameter MaxResolution ist. |
| image_quality | Gibt das Komprimierungsniveau von Bildern an, wenn das Flag CompressIamges verwendet wird. |
| max_resolution | Gibt die maximale Auflösung von Bildern an. Wenn ein Bild eine höhere Auflösung hat, wird es skaliert. |
| version | Version des Komprimierungsalgorithmus. Mögliche Werte sind: 1. Standardkomprimierung, 2. Schnell (verbesserte Komprimierung, die schneller ist als die Standardkomprimierung, aber möglicherweise nicht für alle Bilder anwendbar ist), 3. Gemischt (Standardkomprimierung wird auf Bilder angewendet, die nicht durch den schnelleren Algorithmus komprimiert werden können; dies kann die beste Komprimierung ergeben, ist jedoch langsamer als der "Schnell"-Algorithmus. Die Version "Schnell" ist nicht für die Größenänderung von Bildern anwendbar (es wird die Standardmethode verwendet). Standard ist "Standard".) |
| encoding | Ruft die Kodierung ab oder legt sie fest, die zum Speichern von Bildern verwendet wird. |

### Siehe auch

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

