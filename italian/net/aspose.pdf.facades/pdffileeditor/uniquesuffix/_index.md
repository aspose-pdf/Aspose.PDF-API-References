---
title: PdfFileEditor.UniqueSuffix
second_title: Aspose.PDF for .NET API Reference
description: Proprietà di PdfFileEditor. Formato del suffisso che viene aggiunto al nome del campo per renderlo unico quando i moduli vengono concatenati. Questa stringa deve contenere la sottostringa NUM che sarà sostituita con numeri. Ad esempio, se UniqueSuffix = ABCNUM, allora per il campo fieldName i nomi saranno: fieldNameABC1, fieldNameABC2, fieldNameABC3, ecc.
type: docs
weight: 200
url: /it/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## Proprietà PdfFileEditor.UniqueSuffix

Formato del suffisso che viene aggiunto al nome del campo per renderlo unico quando i moduli vengono concatenati. Questa stringa deve contenere la sottostringa %NUM% che sarà sostituita con numeri. Ad esempio, se UniqueSuffix = "ABC%NUM%", allora per il campo "fieldName" i nomi saranno: fieldNameABC1, fieldNameABC2, fieldNameABC3, ecc.

```csharp
public string UniqueSuffix { get; set; }
```

## Esempi

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### Vedi Anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)