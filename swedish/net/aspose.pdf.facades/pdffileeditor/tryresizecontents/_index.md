---
title: "PdfFileEditor.TryResizeContents"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor‑metoden. Ändrar storlek på innehållet i dokumentets sidor."
type: docs
weight: 450
url: /sv/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

Ändrar storlek på innehållet i dokumentets sidor.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| källa | Stream | Ström med källdokumentet. |
| destination | Stream | Ström med destinationsdokumentet. |
| sidor | Int32[] | Array med sidindex. |
| parametrar | ContentsResizeParameters | Parametrar för storleksändring. |

### Returvärde

Returnerar true om lyckas.

## Anmärkningar

Metoden TryResizeContents är som metoden ResizeContents, förutom att TryResizeContents‑metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //vänster marginal = 10 % av sidbredden
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //ny innehållsbredd beräknas automatiskt som bredd - vänster marginal - höger marginal (100 % - 10 % - 10 % = 80 %)
    null,
    //höger marginal är 10 % av sidan
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //övre marginal = 10 % av höjden
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //ny innehållshöjd beräknas automatiskt (liknande bredden)
    null,
    //nedre marginal är 10 %
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### Se även

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_1}

Ändrar storlek på dokumentets sidinnehåll. Krymper sidinnehållet och lägger till marginaler. Ny storlek på innehållet anges i standardenhetsmått.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| källa | Stream | Ström som innehåller källdokumentet. |
| destination | Stream | Ström där det resulterande dokumentet kommer att sparas. |
| sidor | Int32[] | Array av sidindex. Om null kommer alla dokumentsidor att bearbetas. |
| newWidth | Double | Ny bredd på sidinnehållet i standardenhetsmått. |
| newHeight | Double | Ny höjd på sidinnehållet i standardenhetsmått. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Anmärkningar

Metoden TryResizeContents är som metoden ResizeContents, förutom att TryResizeContents‑metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
//ändra storlek på alla dokumentets sidor
null, 
//ny innehållsbredd = 200
200, 
//ny innehållshöjd = 300
300);
// återstående område på sidan blir tomt
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

Ändrar storlek på innehållet i dokumentets sidor. Om en sida är krympad läggs tomma marginaler till runt sidan.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| källa | String | Sökväg till källdokumentet. |
| destination | String | Sökväg till destinationsdokumentet. |
| sidor | Int32[] | Array med sidindex (sidindex börjar på 1). |
| parametrar | ContentsResizeParameters | Parametrar för sidstorleksändring. |

### Returvärde

true om storleksändringen lyckades.

## Anmärkningar

Metoden TryResizeContents är som metoden ResizeContents, förutom att TryResizeContents‑metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //vänster marginal = 10 % av sidbredden
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //ny innehållsbredd beräknas automatiskt som bredd - vänster marginal - höger marginal (100 % - 10 % - 10 % = 80 %)
    null,
    //höger marginal är 10 % av sidan
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //övre marginal = 10 % av höjden
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //ny innehållshöjd beräknas automatiskt (liknande bredden)
    null,
    //nedre marginal är 10 %
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### Se även

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


