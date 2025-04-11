---
title: PdfPageEditor.GetPageRotation
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor-metod. Returnerar rotationen av angiven sida
type: docs
weight: 140
url: /sv/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## PdfPageEditor.GetPageRotation metod

Returnerar rotationen av angiven sida.

```csharp
public int GetPageRotation(int page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | Int32 | Sidanummer. Dokumentets sidor numreras från 1. |

### Returvärde

Sidorotation i grader.

## Exempel

Följande exempel visar hur man får sidrotation:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### Se Även

* klass [PdfPageEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)