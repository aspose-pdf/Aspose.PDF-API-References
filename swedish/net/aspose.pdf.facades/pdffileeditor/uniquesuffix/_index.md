---
title: PdfFileEditor.UniqueSuffix
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-egenskap. Formatet på suffixet som läggs till fältnamnet för att göra det unikt när formulär sammanfogas. Denna sträng måste innehålla NUM-delsträngen som kommer att ersättas med siffror. Till exempel om UniqueSuffix = ABCNUM så kommer fältnamnen för "fieldName" att bli fieldNameABC1, fieldNameABC2, fieldNameABC3 osv.
type: docs
weight: 200
url: /sv/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## PdfFileEditor.UniqueSuffix-egenskap

Formatet på suffixet som läggs till fältnamnet för att göra det unikt när formulär sammanfogas. Denna sträng måste innehålla %NUM% delsträngen som kommer att ersättas med siffror. Till exempel om UniqueSuffix = "ABC%NUM%" så kommer fältnamnen för "fieldName" att bli: fieldNameABC1, fieldNameABC2, fieldNameABC3 osv.

```csharp
public string UniqueSuffix { get; set; }
```

## Exempel

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)