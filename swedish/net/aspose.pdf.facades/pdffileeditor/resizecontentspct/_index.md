---
title: "PdfFileEditor.ResizeContentsPct"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor-metoden. Ändrar storlek på innehållet i Document Page. Krymper innehållet i Page och lägger till marginaler. Ny innehållsstorlek anges i procent."
type: docs
weight: 330
url: /sv/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

Ändrar storlek på dokumentets sidinnehåll. Krymper sidinnehållet och lägger till marginaler. Ny innehållsstorlek anges i procent.

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| källa | Stream | Ström som innehåller källdokumentet. |
| destination | Stream | Ström där det resulterande dokumentet kommer att sparas. |
| sidor | Int32[] | Array av sidindex. Om null kommer alla dokumentsidor att bearbetas. |
| newWidth | Double | Ny bredd på Page-innehållet i procent. |
| newHeight | Double | Ny höjd på Page-innehållet i procent. |

### Returvärde

Sant om storleken ändrades framgångsrikt.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
//ändra storlek på alla dokumentets sidor
null, 
//ny innehållsbredd = 60% av ursprunglig storlek
60, 
//ny innehållshöjd = 60% av ursprunglig storlek
60);
// Återstående område på Page blir tomt (page-marginaler). Storleken på vänster och höger marginal är (100% - 60%) / 2 = 20%.
// Samma gäller för övre och nedre marginaler.
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

Ändrar storlek på dokumentets sidinnehåll. Krymper sidinnehållet och lägger till marginaler. Ny innehållsstorlek anges i procent.

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| källa | String | Sökväg till källdokumentet. |
| destination | String | Sökväg där det resulterande dokumentet kommer att sparas. |
| sidor | Int32[] | Array av sidindex. Om null kommer alla dokumentsidor att bearbetas. |
| newWidth | Double | Ny bredd på Page-innehållet i procent. |
| newHeight | Double | Ny höjd på Page-innehållet i procent. |

### Returvärde

true om storleksändringen lyckades.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
//ändra storlek på alla dokumentets sidor
null, 
//ny innehållsbredd = 60% av ursprunglig storlek
60, 
//ny innehållshöjd = 60% av ursprunglig storlek
60);
// Återstående område på Page blir tomt (page-marginaler). Storleken på vänster och höger marginal är (100% - 60%) / 2 = 20%.
// Samma gäller för övre och nedre marginaler.
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


