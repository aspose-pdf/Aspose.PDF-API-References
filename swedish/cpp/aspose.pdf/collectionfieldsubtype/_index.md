---
title: "Aspose::Pdf::CollectionFieldSubtype enum"
linktitle: "CollectionFieldSubtype"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::CollectionFieldSubtype enum. Representerar undertyp‑parametern för ett fält i en schemainsamling i C++."
type: docs
weight: 21800
url: /sv/cpp/aspose.pdf/collectionfieldsubtype/
---
## CollectionFieldSubtype enum


Representerar subtypparametern för ett fält i en schemasamling.

```cpp
enum class CollectionFieldSubtype
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Ingen | 0 | Undertypen är inte definierad. |
| S | 1 | En texttyp. Fältdata ska lagras som en PDF-textsträng. |
| D | 2 | En datumtyp. Fältdata ska lagras som en PDF-datumsträng. |
| N | 3 | En numerisk typ. Fältdata ska lagras som ett PDF‑nummer. |
| F | 4 | Fältdata ska vara filnamnet på den inbäddade filströmmen, enligt UF‑posten i filspecificeringen, om den finns; annars enligt F‑posten i filspecificeringen. |
| Desc | 5 | Fältdata ska vara filnamnet på den inbäddade filströmmen, enligt UF‑posten i filspecificeringen, om den finns; annars enligt F‑posten i filspecificeringen. |
| ModDate | 6 | Fältdata ska vara ändringsdatumet för den inbäddade filströmmen, enligt ModDate‑posten i den inbäddade filens parameterdictionary. |
| CreationDate | 7 | Fältdata ska vara skapelsedatumet för den inbäddade filströmmen, enligt CreationDate‑posten i den inbäddade filen. |
| Size | 8 | Fältdata ska vara storleken på den inbäddade filen, enligt Size-posten i den inbäddade filens parameterordbok. |
| CompressedSize | 9 | (PDF 2.0) Fältdata är längden på den inbäddade filströmmen, enligt Length-posten i den inbäddade filströmmenordboken, och de två värdena ska vara identiska. |

## Se även

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
