---
title: PdfFileEditor.AddMargins
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-metod. Ändrar storlek på sidinnehåll och lägger till angivna marginaler. Marginaler anges i standard rymdenheter
type: docs
weight: 220
url: /sv/net/aspose.pdf.facades/pdffileeditor/addmargins/
---
## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

Ändrar storlek på sidinnehåll och lägger till angivna marginaler. Marginaler anges i standard rymdenheter.

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | Stream | Stream som innehåller källdokumentet. |
| destination | Stream | Stream där det resulterande dokumentet kommer att sparas. |
| pages | Int32[] | Array av sidindex. Om null kommer alla dokumentets sidor att behandlas. |
| leftMargin | Double | Vänster marginal. |
| rightMargin | Double | Höger marginal. |
| topMargin | Double | Övre marginal. |
| bottomMargin | Double | Nedre marginal. |

### Returvärde

true om operationen var framgångsrik.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
    dest.Close();
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

Ändrar storlek på sidinnehåll och lägger till angivna marginaler. Marginaler anges i standard rymdenheter.

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | String | Sökväg till källdokumentet. |
| destination | String | Sökväg där det resulterande dokumentet kommer att sparas. |
| pages | Int32[] | Array av sidindex. Om null kommer alla dokumentets sidor att behandlas. |
| leftMargin | Double | Vänster marginal. |
| rightMargin | Double | Höger marginal. |
| topMargin | Double | Övre marginal. |
| bottomMargin | Double | Nedre marginal. |

### Returvärde

true om ändringen av storlek var framgångsrik.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)