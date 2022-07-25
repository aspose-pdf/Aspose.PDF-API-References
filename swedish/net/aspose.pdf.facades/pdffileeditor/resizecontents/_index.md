---
title: ResizeContents
second_title: Aspose.PDF för .NET API Referens
description: Ändrar storleken på innehållet på sidorna i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan.
type: docs
weight: 350
url: /sv/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_4}

Ändrar storleken på innehållet på sidorna i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
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
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### Se även

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_7}

Ändrar storlek på dokumentsidor. Tomma marginaler läggs till runt den krympta sidan.

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | Document | Källdokument. |
| pages | Int32[] | Lista över sidindex. |
| parameters | ContentsResizeParameters | Ändra storlek på parametrar. |

### Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
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
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### Se även

* class [Document](../../../aspose.pdf/document)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_6}

Ändrar storlek på dokumentsidor. Tomma marginaler läggs till runt den krympta sidan.

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | Document | Källdokument. |
| parameters | ContentsResizeParameters | Ändra storlek på parametrar. |

### Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
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
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### Se även

* class [Document](../../../aspose.pdf/document)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents_1}

Ändrar storleken på innehållet på sidorna i dokumentet.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
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
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### Se även

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_2}

Ändrar storleken på innehållet på dokumentsidorna. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i standardutrymmesenheter.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
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

Sant om storleksändringen lyckades.

### Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
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

## ResizeContents(string, string, int[], double, double) {#resizecontents_5}

Ändrar storleken på innehållet på dokumentsidorna. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i standardutrymmesenheter.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | String | Sökväg till källdokument. |
| destination | String | Sökväg där det resulterande dokumentet kommer att sparas. |
| pages | Int32[] | Uppsättning av sidindex. Om null kommer alla dokumentsidor att behandlas. |
| newWidth | Double | Ny bredd på sidinnehållet i standardutrymmesenheter. |
| newHeight | Double | Ny höjd på sidinnehållet i standardutrymmesenheter. |

### Returvärde

sant om storleksändringen lyckades.

### Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
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

## ResizeContents(string, int[], ContentsResizeParameters, HttpResponse) {#resizecontents_3}

Ändrar storleken på innehållet på sidorna i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan. Resultatet lagras i HttpResponse-objektet.

```csharp
public bool ResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | String | Sökväg till källfil. |
| pages | Int32[] | Array av sidor som ska storleksändras. |
| parameters | ContentsResizeParameters | Ändra storlek på parametrar. |
| response | HttpResponse | HttpResponse-objekt där resultatet sparas. |

### Returvärde

Sant om operationen lyckades.

### Se även

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## ResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#resizecontents}

Ändrar storleken på innehållet på sidorna i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan. Resultatet lagras i HttpResponse-objektet.

```csharp
public bool ResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | Stream | Ström av källfil. |
| pages | Int32[] | Array av sidor som ska storleksändras. |
| parameters | ContentsResizeParameters | Ändra storlek på parametrar. |
| response | HttpResponse | HttpResponse-objekt där resultatet sparas. |

### Returvärde

Sant om operationen lyckades.

### Se även

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
