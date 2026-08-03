---
title: "PdfFileEditor.AddMarginsPct"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor-metoden. Ändrar storlek på Page-innehållet och lägger till angivna marginaler. Marginalerna anges i procent av den ursprungliga Page-storleken."
type: docs
weight: 230
url: /sv/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

Ändrar storlek på sidinnehållet och lägger till angivna marginaler. Marginalerna specificeras i procent av den ursprungliga sidstorleken.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| källa | Stream | Ström som innehåller källdokumentet. |
| destination | Stream | Ström där det resulterande dokumentet kommer att sparas. |
| sidor | Int32[] | Array av sidindex. Om null kommer alla dokumentsidor att bearbetas. |
| leftMargin | Double | Vänster marginal i procent av den ursprungliga Page-storleken. |
| rightMargin | Double | Höger marginal i procent av den ursprungliga Page-storleken. |
| topMargin | Double | Övre marginal i procent av ursprunglig sidstorlek. |
| bottomMargin | Double | Nedre marginal i procent av ursprunglig sidstorlek. |

### Returvärde

Sant om åtgärden utfördes framgångsrikt.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //bearbeta sidor 1, 2, 3
    new int[] { 1, 2, 3}, 
    //Vänster marginal är 15% av sidbredden 
    15, 
    //Höger marginal är 10% av sidbredden
    10, 
    //Övre marginal är 20% av sidbredden
    20, 
    //Nedre marginal är 5% av sidbredden
    5);
    dest.Close();
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

Ändrar storlek på sidinnehållet och lägger till angivna marginaler. Marginalerna specificeras i procent av den ursprungliga sidstorleken.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| källa | String | Sökväg till källdokumentet. |
| destination | String | Sökväg där det resulterande dokumentet kommer att sparas. |
| sidor | Int32[] | Array av sidindex. Om null kommer alla dokumentsidor att bearbetas. |
| leftMargin | Double | Vänster marginal i procent av den ursprungliga Page-storleken. |
| rightMargin | Double | Höger marginal i procent av den ursprungliga Page-storleken. |
| topMargin | Double | Övre marginal i procent av ursprunglig sidstorlek. |
| bottomMargin | Double | Nedre marginal i procent av ursprunglig sidstorlek. |

### Returvärde

Sant om storleksändringen lyckades

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //bearbeta sidor 1, 2, 3
    new int[] { 1, 2, 3}, 
    //Vänster marginal är 15% av sidbredden 
    15, 
    //Höger marginal är 10% av sidbredden
    10, 
    //Övre marginal är 20% av sidbredden
    20, 
    //Nedre marginal är 5% av sidbredden
    5);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


