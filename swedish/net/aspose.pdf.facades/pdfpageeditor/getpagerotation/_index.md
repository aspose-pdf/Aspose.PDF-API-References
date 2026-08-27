---
title: "PdfPageEditor.GetPageRotation"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfPageEditor-metod. Returnerar rotationen för den angivna sidan"
type: docs
weight: 140
url: /sv/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## PdfPageEditor.GetPageRotation method

Returnerar rotationen för den angivna sidan.

```csharp
public int GetPageRotation(int page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | Int32 | Sidindex. Dokumentets sidor är numrerade från 1. |

### Returvärde

Sidrotation i grader.

## Exempel

Följande exempel visar hur man hämtar sidrotation:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### Se även

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


