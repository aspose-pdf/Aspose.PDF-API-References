---
title: "PdfFileEditor.UniqueSuffix"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor-egenskap. Formatet på suffixet som läggs till fältnamnet för att göra det unikt när formulär sammansätts. Denna sträng måste innehålla understrängen NUM som kommer att ersättas med siffror. Till exempel, om UniqueSuffix är ABCNUM så blir fältnamnen fieldNameABC1, fieldNameABC2, fieldNameABC3 osv."
type: docs
weight: 200
url: /sv/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## PdfFileEditor.UniqueSuffix property

Formatet för suffixet som läggs till fältnamnet för att göra det unikt när formulär sammanfogas. Denna sträng måste innehålla %NUM%-delsträngen som kommer att ersättas med siffror. Till exempel om UniqueSuffix = \"ABC%NUM%\" så blir fältnamnen för \"fieldName\": fieldNameABC1, fieldNameABC2, fieldNameABC3 osv.

```csharp
public string UniqueSuffix { get; set; }
```

## Exempel

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


