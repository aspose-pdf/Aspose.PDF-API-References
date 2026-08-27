---
title: "PdfPageEditor.GetPageSize"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfPageEditor metod. Returnerar sidstorleken för den angivna sidan"
type: docs
weight: 160
url: /sv/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## PdfPageEditor.GetPageSize method

Returnerar sidstorleken för den angivna sidan.

```csharp
public PageSize GetPageSize(int page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | Int32 | Sidindex. Dokumentets sidor är numrerade från 1. |

### Returvärde

Resultatet är en instans av PageSize. Använd Width- och Height-egenskaperna hos det returnerade objektet för att få sidans bredd och höjd.

## Exempel

Följande exempel demonstrerar användning av GetPageSize-metoden:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### Se även

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


