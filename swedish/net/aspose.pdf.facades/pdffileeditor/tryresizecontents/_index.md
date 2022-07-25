---
title: TryResizeContents
second_title: Aspose.PDF för .NET API Referens
description: Ändrar storleken på innehållet på sidorna i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan. Resultatet lagras i HttpResponse-objektet.
type: docs
weight: 480
url: /sv/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(string, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents_3}

Ändrar storleken på innehållet på sidorna i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan. Resultatet lagras i HttpResponse-objektet.

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | String | Sökväg till källfil. |
| pages | Int32[] | Array av sidor som ska storleksändras. |
| parameters | ContentsResizeParameters | Ändra storlek på parametrar. |
| response | HttpResponse | HttpResponse-objekt där resultatet sparas. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

Metoden TryResizeContents är som metoden ResizeContents, förutom att metoden TryResizeContents inte ger ett undantag om operationen misslyckas.

### Se även

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

Ändrar storleken på innehållet på sidorna i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan. Resultatet lagras i HttpResponse-objektet.

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | Stream | Ström av källfil. |
| pages | Int32[] | Array av sidor som ska storleksändras. |
| parameters | ContentsResizeParameters | Ändra storlek på parametrar. |
| response | HttpResponse | HttpResponse-objekt där resultatet sparas. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

Metoden TryResizeContents är som metoden ResizeContents, förutom att metoden TryResizeContents inte ger ett undantag om operationen misslyckas.

### Se även

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents_1}

Ändrar storleken på innehållet på sidorna i dokumentet.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | Stream | Streama med källdokument. |
| destination | Stream | Streama med måldokumentet. |
| pages | Int32[] | Uppsättning av sidindex. |
| parameters | ContentsResizeParameters | Ändra storlek på parametrar. |

### Returvärde

Returnerar sant om framgång.

### Anmärkningar

Metoden TryResizeContents är som metoden ResizeContents, förutom att metoden TryResizeContents inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //vänstermarginal = 10 % av sidbredden
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //nytt innehållsbredd beräknas automatiskt som bredd - vänstermarginal - högermarginal (100% - 10% - 10% = 80%)
    null,
    //högermarginalen är 10% av sidan 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //toppmarginal = 10% av höjden
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //nytt innehålls höjd beräknas automatiskt (liknar bredd)
    null,
    //bottenmarginalen är 10 %
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### Se även

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_2}

Ändrar storleken på innehållet på dokumentsidorna. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i standardutrymmesenheter.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | Stream | Stream som innehåller källdokument. |
| destination | Stream | Streama där det resulterande dokumentet kommer att sparas. |
| pages | Int32[] | Uppsättning av sidindex. Om null kommer alla dokumentsidor att behandlas. |
| newWidth | Double | Ny bredd på sidinnehållet i standardutrymmesenheter. |
| newHeight | Double | Ny höjd på sidinnehållet i standardutrymmesenheter. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

Metoden TryResizeContents är som metoden ResizeContents, förutom att metoden TryResizeContents inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
//ändra storlek på alla sidor i dokumentet
null, 
//ny innehållsbredd = 200
200, 
//nytt innehållshöjd = 300
300);
// viloområdet på sidan kommer att vara tomt
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_4}

Ändrar storleken på innehållet på sidorna i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | String | Sökväg till källdokument. |
| destination | String | Destinationsdokumentets sökväg. |
| pages | Int32[] | Array av sidindex (sidindex börjar från 1). |
| parameters | ContentsResizeParameters | Parametrar för att ändra storlek på sidan. |

### Returvärde

sant om storleksändringen lyckades.

### Anmärkningar

Metoden TryResizeContents är som metoden ResizeContents, förutom att metoden TryResizeContents inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //vänstermarginal = 10 % av sidbredden
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //nytt innehållsbredd beräknas automatiskt som bredd - vänstermarginal - högermarginal (100% - 10% - 10% = 80%)
    null,
    //högermarginalen är 10% av sidan 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //toppmarginal = 10% av höjden
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //nytt innehålls höjd beräknas automatiskt (liknar bredd)
    null,
    //bottenmarginalen är 10 %
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### Se även

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
