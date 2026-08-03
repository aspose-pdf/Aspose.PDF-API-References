---
title: "PdfFileEditor.ResizeContents"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor‑metoden. Ändrar storlek på innehållet i dokumentets sidor."
type: docs
weight: 320
url: /sv/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents}

Ändrar storlek på innehållet i dokumentets sidor.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
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
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### Se även

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_1}

Ändrar storlek på dokumentets sidinnehåll. Krymper sidinnehållet och lägger till marginaler. Ny storlek på innehållet anges i standardenhetsmått.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
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

Sant om storleksändringen lyckades.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
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

## ResizeContents(string, string, int[], double, double) {#resizecontents_3}

Ändrar storlek på dokumentets sidinnehåll. Krymper sidinnehållet och lägger till marginaler. Ny storlek på innehållet anges i standardenhetsmått.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| källa | String | Sökväg till källdokumentet. |
| destination | String | Sökväg där det resulterande dokumentet kommer att sparas. |
| sidor | Int32[] | Array av sidindex. Om null kommer alla dokumentsidor att bearbetas. |
| newWidth | Double | Ny bredd på sidinnehållet i standardenhetsmått. |
| newHeight | Double | Ny höjd på sidinnehållet i standardenhetsmått. |

### Returvärde

true om storleksändringen lyckades.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
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

## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_2}

Ändrar storlek på innehållet i dokumentets sidor. Om en sida är krympad läggs tomma marginaler till runt sidan.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
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
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### Se även

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_5}

Ändrar storlek på dokumentets sidor. Tomma marginaler läggs till runt den krympade sidan.

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| källa | Dokument | Källdokument. |
| sidor | Int32[] | Lista över sidindex. |
| parametrar | ContentsResizeParameters | Parametrar för storleksändring. |

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
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
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### Se även

* class [Document](../../../aspose.pdf/document/)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_4}

Ändrar storlek på dokumentets sidor. Tomma marginaler läggs till runt den krympade sidan.

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| källa | Dokument | Källdokument. |
| parametrar | ContentsResizeParameters | Parametrar för storleksändring. |

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
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
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### Se även

* class [Document](../../../aspose.pdf/document/)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


