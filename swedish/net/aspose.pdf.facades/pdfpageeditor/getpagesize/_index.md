---
title: PdfPageEditor.GetPageSize
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor-metod. Returnerar sidstorleken för den angivna sidan
type: docs
weight: 160
url: /sv/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## PdfPageEditor.GetPageSize metod

Returnerar sidstorleken för den angivna sidan.

```csharp
public PageSize GetPageSize(int page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | Int32 | Sidindex. Dokumentets sidor numreras från 1. |

### Returvärde

Resultatet är en instans av PageSize. Använd egenskaperna Width och Height för det returnerade objektet för att få sidans bredd och höjd.

## Exempel

Följande exempel visar användningen av GetPageSize-metoden:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfPageEditor](../)
* namnrum [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)