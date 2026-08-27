---
title: "FileSpecification"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klass som representerar inbäddad fil."
type: docs
weight: 360
url: /sv/python-net/aspose.pdf/filespecification/
---

## FileSpecification class

Klass som representerar inbäddad fil.

Typen FileSpecification exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| FileSpecification(file) | Initierar en ny instans av FileSpecification-klassen |
| FileSpecification(stream, name) | Initierar en ny instans av FileSpecification-klassen |
| FileSpecification(file, description) | Initierar en ny instans av FileSpecification-klassen |
| FileSpecification(stream, name, description) | Initierar en ny instans av FileSpecification-klassen |
| FileSpecification(file_name, annot) | Initierar en ny instans av FileSpecification-klassen |
| FileSpecification() | Skapa ny tom filspecificering. |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| kodning | Hämtar eller anger kodningsformat.<br/>            Möjliga värden: Zip - filen är komprimerad med ZIP, <br/>            None - filen är inte komprimerad. |
| include_contents | Om true, kommer filens innehåll att inkluderas i filspecificeringen. |
| encrypted_payload | Hämtar krypterad nyttolast. |
| description | Hämtar eller anger text som är associerad med filspecificeringen. |
| af_relationship | Associerad filrelation. |
| stream_contents | Hämtar filens innehåll som en ström. <br/>            Innehållet laddas inte in i minnet vilket möjliggör minskad minnesanvändning.<br/>            Men denna ström stöder inte positionering och Length-egenskapen. Om du behöver dessa funktioner, använd egenskapen Contents istället. |
| innehåll | Hämtar eller anger innehållsfil. <br/>            Denna egenskap returnerar data som laddas i minnet vilket kan orsaka Out of memory-undantag för stora data.<br/>            För att minska minnesanvändningen, använd StreamContents. |
| params | Hämtar filparametrar. |
| mime_type | Hämtar undertyp av den inbäddade filen |
| name | Hämtar eller anger namn på filspecificering. |
| unicode_name | Hämtar eller anger unicode-namn för filspecificering. |
| file_system | Hämtar eller anger namn på filsystemet. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| get_value(key) | Hämtar applikationsspecifik parameter. |
| set_value(key, value) | Anger applikationsspecifik parameter. |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

