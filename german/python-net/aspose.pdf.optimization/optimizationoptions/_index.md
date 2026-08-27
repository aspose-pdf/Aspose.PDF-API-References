---
title: "OptimizationOptions"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse, die den Dokument‑Optimierungsalgorithmus beschreibt.<br/>            Eine Instanz dieser Klasse kann als Parameter der Methode OptimizeResources() verwendet werden."
type: docs
weight: 20
url: /de/python-net/aspose.pdf.optimization/optimizationoptions/
---

## OptimizationOptions class

Klasse, die den Dokument‑Optimierungsalgorithmus beschreibt.<br/>            Eine Instanz dieser Klasse kann als Parameter der Methode OptimizeResources() verwendet werden.

Der Typ OptimizationOptions stellt die folgenden Member bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| OptimizationOptions() | Initialisiert eine neue Instanz der Klasse OptimizationOptions |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| link_duplcate_streams | Wenn dieses Flag auf true gesetzt ist, werden Ressourcestreams analysiert. Wenn doppelte Streams gefunden werden (d.h. wenn der Stream-Inhalt gleich ist), werden diese Streams als ein Objekt gespeichert. <br/>            Dies ermöglicht in einigen Fällen die Verringerung der Dokumentgröße (zum Beispiel, wenn dasselbe Dokument mehrfach zusammengefügt wurde). |
| allow_reuse_page_content | Wenn true, werden Seiteninhalte wiederverwendet, wenn das Dokument für gleiche Seiten optimiert wird. |
| remove_unused_streams | Wenn dieses Flag auf true gesetzt ist, wird jede Ressource auf ihre Verwendung geprüft. Wenn eine Ressource nie verwendet wird, wird sie entfernt.<br/>            Dies kann die Dokumentgröße verringern, zum Beispiel wenn Seiten aus dem Dokument extrahiert wurden. |
| remove_unused_objects | Wenn dieses Flag auf true gesetzt ist, werden alle Dokumentobjekte geprüft und unbenutzte Objekte (d.h. Objekte, die keine Referenz haben) aus dem Dokument entfernt. |
| image_compression_options | Menge von Optionen, die beschreiben, ob Bilder im Dokument komprimiert werden und die Parameter der Kompression. |
| compress_images | Wenn dieses Flag auf true gesetzt ist, werden Bilder im Dokument komprimiert. Die Komprimierungsstufe wird mit der Eigenschaft ImageQuality angegeben. |
| resize_images | Wenn dieses Flag auf true gesetzt ist und CompressImages true ist, werden Bilder verkleinert, wenn die Bildauflösung größer als der angegebene Parameter MaxResolution ist. |
| image_quality | Gibt das Komprimierungsniveau von Bildern an, wenn das Flag CompressIamges verwendet wird. |
| max_resoultion | Gibt die maximale Auflösung von Bildern an. Wenn ein Bild eine höhere Auflösung hat, wird es skaliert. |
| unembed_fonts | Schriftarten werden nicht eingebettet, wenn das Flag auf true gesetzt ist. |
| subset_fonts | Schriftarten werden in Teilmengen konvertiert, wenn das Flag auf true gesetzt ist. |
| remove_private_info | Entfernt private Informationen (Seitenstück-Info). |
| image_encoding | Bildkodierung, die verwendet wird. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| all() | Erstellt eine Optimierungsstrategie mit allen aktivierten Optionen.<br/>            Bitte beachten Sie, dass nur Optionen aktiviert werden, die keine Funktionalität des Dokuments ändern.<br/>            D. h. Bildkomprimierung und Schriftart-Deeinbettung werden nicht aktiviert (und können manuell eingebettet werden). |

### Siehe auch

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

