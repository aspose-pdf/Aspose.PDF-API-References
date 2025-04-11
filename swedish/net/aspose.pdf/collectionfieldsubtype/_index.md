---
title: Enum CollectionFieldSubtype
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.CollectionFieldSubtype enum. Representerar subtype-parametern för ett fält i en schemakollektion
type: docs
weight: 3040
url: /sv/net/aspose.pdf/collectionfieldsubtype/
---
## CollectionFieldSubtype enumeration

Representerar subtype-parametern för ett fält i en schemakollektion.

```csharp
public enum CollectionFieldSubtype
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Subtypen är inte definierad. |
| S | `1` | En texttyp. Fältdata ska lagras som en PDF-textsträng. |
| D | `2` | En datatyp. Fältdata ska lagras som en PDF-datosträng. |
| N | `3` | En numrerad typ. Fältdata ska lagras som ett PDF-nummer. |
| F | `4` | Fältdata ska vara filnamnet på den inbäddade filströmmen, som identifieras av UF-posten i filspecifikationen, om den finns; annars av F-posten i filspecifikationen |
| Desc | `5` | Fältdata ska vara filnamnet på den inbäddade filströmmen, som identifieras av UF-posten i filspecifikationen, om den finns; annars av F-posten i filspecifikationen |
| ModDate | `6` | Fältdata ska vara ändringsdatumet för den inbäddade filströmmen, som identifieras av ModDate-posten i den inbäddade filparametern. |
| CreationDate | `7` | Fältdata ska vara skapelsedatumet för den inbäddade filströmmen, som identifieras av CreationDate-posten i den inbäddade filen |
| Size | `8` | Fältdata ska vara storleken på den inbäddade filen, som identifieras av Size-posten i den inbäddade filparametern |
| CompressedSize | `9` | (PDF 2.0) Fältdata är längden på den inbäddade filströmmen, som identifieras av Length-posten i den inbäddade filströmmen, och de två värdena ska vara identiska. |

### Se Även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)