---
title: "PdfPageEditor.GetPageBoxSize"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfPageEditor-metod. Returnerar storleken på den specificerade rutan i dokumentet"
type: docs
weight: 130
url: /sv/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## PdfPageEditor.GetPageBoxSize method

Returnerar storleken på den angivna rutan i dokumentet.

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | Int32 | Sidindex. Dokumentets sidor är numrerade från 1. |
| pageBoxName | String | Box-typnamn. Giltiga värden är: "art", "bleed", "crop", "media", "trim". |

### Returvärde

Rectangle som innehåller den begärda rutan.

## Exempel

Följande exempel visar hur man får media box för den första sidan:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### Se även

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


