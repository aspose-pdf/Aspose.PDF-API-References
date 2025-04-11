---
title: PdfContentEditor.DeleteStamp
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metod. Tar bort flera stämplar på den angivna sidan efter stämpelindex
type: docs
weight: 330
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/
---
## PdfContentEditor.DeleteStamp metod

Tar bort flera stämplar på den angivna sidan efter stämpelindex.

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | Int32 | Sidnummer där stämpeln kommer att tas bort. |
| index | Int32[] | Stämpelindex. |

## Exempel

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStamp(1, new int[] { 2, 3, 5} );
contentEditor.Save("outfile.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)