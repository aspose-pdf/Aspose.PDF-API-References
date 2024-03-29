---
title: AddMarginsPct
second_title: Aspose.PDF för .NET API Referens
description: Ändrar storlek på sidinnehåll och lägg till specificerade marginaler. Marginaler anges i procent av den ursprungliga sidstorleken.
type: docs
weight: 260
url: /sv/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

Ändrar storlek på sidinnehåll och lägg till specificerade marginaler. Marginaler anges i procent av den ursprungliga sidstorleken.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | String | Sökväg till källdokument. |
| destination | String | Sökväg där det resulterande dokumentet kommer att sparas. |
| pages | Int32[] | Uppsättning av sidindex. Om null kommer alla dokumentsidor att behandlas. |
| leftMargin | Double | Vänstermarginal i procent av den ursprungliga sidstorleken. |
| rightMargin | Double | Högermarginal i procent av den ursprungliga sidstorleken. |
| topMargin | Double | Toppmarginal i procent av den ursprungliga sidstorleken. |
| bottomMargin | Double | Nedre marginal i procent av den ursprungliga sidstorleken. |

### Returvärde

sant om storleksändringen lyckades

### Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //bearbeta sidorna 1, 2, 3
    new int[] { 1, 2, 3}, 
    //vänstermarginalen är 15 % av sidbredden 
    15, 
    //högermarginalen är 10 % av sidbredden
    10, 
    //toppmarginalen är 20 % av sidbredden
    20, 
    //bottenmarginalen är 5 % av sidbredden
    5);
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

Ändrar storlek på sidinnehåll och lägg till specificerade marginaler. Marginaler anges i procent av den ursprungliga sidstorleken.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | Stream | Stream som innehåller källdokument. |
| destination | Stream | Streama där det resulterande dokumentet kommer att sparas. |
| pages | Int32[] | Uppsättning av sidindex. Om null kommer alla dokumentsidor att behandlas. |
| leftMargin | Double | Vänstermarginal i procent av den ursprungliga sidstorleken. |
| rightMargin | Double | Högermarginal i procent av den ursprungliga sidstorleken. |
| topMargin | Double | Toppmarginal i procent av den ursprungliga sidstorleken. |
| bottomMargin | Double | Nedre marginal i procent av den ursprungliga sidstorleken. |

### Returvärde

sant om åtgärden utfördes framgångsrikt.

### Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //bearbeta sidorna 1, 2, 3
    new int[] { 1, 2, 3}, 
    //vänstermarginalen är 15 % av sidbredden 
    15, 
    //högermarginalen är 10 % av sidbredden
    10, 
    //toppmarginalen är 20 % av sidbredden
    20, 
    //bottenmarginalen är 5 % av sidbredden
    5);
    dest.Close();
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
