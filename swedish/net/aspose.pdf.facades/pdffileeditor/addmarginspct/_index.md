---
title: PdfFileEditor.AddMarginsPct
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metod. Ändrar storlek på sidinnehåll och lägger till angivna marginaler. Marginaler anges i procent av den initiala sidstorleken
type: docs
weight: 230
url: /sv/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

Ändrar storlek på sidinnehåll och lägger till angivna marginaler. Marginaler anges i procent av den initiala sidstorleken.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | Stream | Stream som innehåller källdokumentet. |
| destination | Stream | Stream där det resulterande dokumentet kommer att sparas. |
| pages | Int32[] | Array av sidindex. Om null kommer alla dokumentets sidor att bearbetas. |
| leftMargin | Double | Vänster marginal i procent av den initiala sidstorleken. |
| rightMargin | Double | Höger marginal i procent av den initiala sidstorleken. |
| topMargin | Double | Översta marginal i procent av den initiala sidstorleken. |
| bottomMargin | Double | Nedersta marginal i procent av den initiala sidstorleken. |

### Returvärde

true om åtgärden utfördes framgångsrikt.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
    dest.Close();
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

Ändrar storlek på sidinnehåll och lägger till angivna marginaler. Marginaler anges i procent av den initiala sidstorleken.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | String | Sökväg till källdokumentet. |
| destination | String | Sökväg där det resulterande dokumentet kommer att sparas. |
| pages | Int32[] | Array av sidindex. Om null kommer alla dokumentets sidor att bearbetas. |
| leftMargin | Double | Vänster marginal i procent av den initiala sidstorleken. |
| rightMargin | Double | Höger marginal i procent av den initiala sidstorleken. |
| topMargin | Double | Översta marginal i procent av den initiala sidstorleken. |
| bottomMargin | Double | Nedersta marginal i procent av den initiala sidstorleken. |

### Returvärde

true om ändringen av storlek var framgångsrik

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)