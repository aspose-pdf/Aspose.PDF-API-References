---
title: "PdfFileEditor.AddMargins"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor-metod. Ändrar storlek på sidinnehåll och lägger till angivna marginaler. Marginaler anges i standardrymdsenheter."
type: docs
weight: 220
url: /sv/net/aspose.pdf.facades/pdffileeditor/addmargins/
---
## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

Ändrar storlek på sidinnehållet och lägger till angivna marginaler. Marginalerna specificeras i standardenheterna för utrymme.

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| källa | Stream | Ström som innehåller källdokumentet. |
| destination | Stream | Ström där det resulterande dokumentet kommer att sparas. |
| sidor | Int32[] | Array av sidindex. Om null kommer alla dokumentsidor att bearbetas. |
| leftMargin | Double | Vänster marginal. |
| rightMargin | Double | Höger marginal. |
| topMargin | Double | Övre marginal. |
| bottomMargin | Double | Nedre marginal. |

### Returvärde

true om operationen lyckades.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //bearbeta sidor 1, 2, 3
    new int[] { 1, 2, 3}, 
    //vänster marginal är 10 enheter
    10, 
    //höger marginal är 5 enheter
    5, 
    //övre marginal är 5 enheter
    5, 
    //nedre marginal är 5 enheter
    5);
    dest.Close();
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

Ändrar storlek på sidinnehållet och lägger till angivna marginaler. Marginalerna specificeras i standardenheterna för utrymme.

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| källa | String | Sökväg till källdokumentet. |
| destination | String | Sökväg där det resulterande dokumentet kommer att sparas. |
| sidor | Int32[] | Array av sidindex. Om null kommer alla dokumentsidor att bearbetas. |
| leftMargin | Double | Vänster marginal. |
| rightMargin | Double | Höger marginal. |
| topMargin | Double | Övre marginal. |
| bottomMargin | Double | Nedre marginal. |

### Returvärde

true om storleksändringen lyckades.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //bearbeta sidor 1, 2, 3
    new int[] { 1, 2, 3}, 
    //vänster marginal är 10 enheter
    10, 
    //höger marginal är 5 enheter
    5, 
    //övre marginal är 5 enheter
    5, 
    //nedre marginal är 5 enheter
    5);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


