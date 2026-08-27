---
title: "PdfFileEditor.UniqueSuffix"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà PdfFileEditor. Formato del suffisso che viene aggiunto al nome del campo per renderlo univoco quando i moduli sono concatenati. Questa stringa deve contenere la sottostringa NUM che verrà sostituita con numeri. Per esempio, se UniqueSuffix è ABCNUM, allora per il campo fieldName i nomi saranno fieldNameABC1 fieldNameABC2 fieldNameABC3 ecc."
type: docs
weight: 200
url: /it/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## PdfFileEditor.UniqueSuffix property

Formato del suffisso che viene aggiunto al nome del campo per renderlo unico quando i moduli sono concatenati. Questa stringa deve contenere la sottostringa %NUM% che sarà sostituita con numeri. Per esempio, se UniqueSuffix = "ABC%NUM%" allora per il campo "fieldName" i nomi saranno: fieldNameABC1, fieldNameABC2, fieldNameABC3 ecc.

```csharp
public string UniqueSuffix { get; set; }
```

## Esempi

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


