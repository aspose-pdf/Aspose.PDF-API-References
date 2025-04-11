---
title: PdfPageEditor.GetPageBoxSize
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor-metod. Returnerar storlek på angiven ruta i dokumentet
type: docs
weight: 130
url: /sv/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## PdfPageEditor.GetPageBoxSize metod

Returnerar storlek på angiven ruta i dokumentet.

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | Int32 | Sidindex. Dokumentets sidor numreras från 1. |
| pageBoxName | String | Rutatypens namn. Giltiga värden är: "art", "bleed", "crop", "media", "trim". |

### Returvärde

Rektangel som innehåller begärd ruta.

## Exempel

Följande exempel visar hur man får mediarutan för den första sidan:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### Se Även

* klass [PdfPageEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)