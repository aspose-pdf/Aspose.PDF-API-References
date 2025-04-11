---
title: PdfFileEditor.UniqueSuffix
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de PdfFileEditor. Formato del sufijo que se añade al nombre del campo para hacerlo único cuando se concatenan formularios. Esta cadena debe contener la subcadena NUM que será reemplazada por números. Por ejemplo, si UniqueSuffix = ABCNUM, entonces para el campo fieldName los nombres serán: fieldNameABC1, fieldNameABC2, fieldNameABC3, etc.
type: docs
weight: 200
url: /es/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## Propiedad PdfFileEditor.UniqueSuffix

Formato del sufijo que se añade al nombre del campo para hacerlo único cuando se concatenan formularios. Esta cadena debe contener la subcadena %NUM% que será reemplazada por números. Por ejemplo, si UniqueSuffix = "ABC%NUM%", entonces para el campo "fieldName" los nombres serán: fieldNameABC1, fieldNameABC2, fieldNameABC3, etc.

```csharp
public string UniqueSuffix { get; set; }
```

## Ejemplos

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)