---
title: PdfFileEditor.ResizeContents
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metod. Ändrar storlek på innehållet på sidorna i dokumentet
type: docs
weight: 320
url: /sv/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents}

Ändrar storlek på innehållet på sidorna i dokumentet.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | Stream | Stream med källdokumentet. |
| destination | Stream | Stream med destinationsdokumentet. |
| pages | Int32[] | Array av sidindex. |
| parameters | ContentsResizeParameters | Parametrar för storleksändring. |

### Return Value

Returnerar true om det lyckades.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### See Also

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_1}

Ändrar storlek på innehållet på dokumentets sidor. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i standard rumsenheter.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | Stream | Stream som innehåller källdokumentet. |
| destination | Stream | Stream där det resulterande dokumentet kommer att sparas. |
| pages | Int32[] | Array av sidindex. Om null kommer alla dokument sidor att bearbetas. |
| newWidth | Double | Ny bredd på sidinnehållet i standard rumsenheter. |
| newHeight | Double | Ny höjd på sidinnehållet i standard rumsenheter. |

### Return Value

True om storleksändringen var framgångsrik.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], double, double) {#resizecontents_3}

Ändrar storlek på innehållet på dokumentets sidor. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i standard rumsenheter.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | String | Sökväg till källdokumentet. |
| destination | String | Sökväg där det resulterande dokumentet kommer att sparas. |
| pages | Int32[] | Array av sidindex. Om null kommer alla dokument sidor att bearbetas. |
| newWidth | Double | Ny bredd på sidinnehållet i standard rumsenheter. |
| newHeight | Double | Ny höjd på sidinnehållet i standard rumsenheter. |

### Return Value

true om storleksändringen var framgångsrik.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_2}

Ändrar storlek på innehållet på sidorna i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | String | Sökväg till källdokumentet. |
| destination | String | Sökväg till destinationsdokumentet. |
| pages | Int32[] | Array av sidindex (sidindex börjar från 1). |
| parameters | ContentsResizeParameters | Parametrar för sidstorleksändring. |

### Return Value

true om storleksändringen var framgångsrik.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### See Also

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_5}

Ändrar storlek på sidorna i dokumentet. Tomma marginaler läggs till runt den krympta sidan.

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | Document | Källdokument. |
| pages | Int32[] | Lista över sidindex. |
| parameters | ContentsResizeParameters | Parametrar för storleksändring. |

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_4}

Ändrar storlek på sidorna i dokumentet. Tomma marginaler läggs till runt den krympta sidan.

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | Document | Källdokument. |
| parameters | ContentsResizeParameters | Parametrar för storleksändring. |

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)