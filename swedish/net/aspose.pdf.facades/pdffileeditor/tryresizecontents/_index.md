---
title: PdfFileEditor.TryResizeContents
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metod. Ändrar storlek på innehållet på sidorna i dokumentet
type: docs
weight: 450
url: /sv/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

Ändrar storlek på innehållet på sidor i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan. Resultatet lagras i HttpResponse-objektet.

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | Sträng | Sökväg till källfil. |
| pages | Int32[] | Array av sidor som ska ändras i storlek. |
| parameters | ContentsResizeParameters | Parametrar för storleksändring. |
| response | HttpResponse | HttpResponse-objekt där resultatet sparas. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryResizeContents-metoden är som ResizeContents-metoden, förutom att TryResizeContents-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

Ändrar storlek på innehållet på sidor i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan. Resultatet lagras i HttpResponse-objektet.

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | Stream | Stream av källfil. |
| pages | Int32[] | Array av sidor som ska ändras i storlek. |
| parameters | ContentsResizeParameters | Parametrar för storleksändring. |
| response | HttpResponse | HttpResponse-objekt där resultatet sparas. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryResizeContents-metoden är som ResizeContents-metoden, förutom att TryResizeContents-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents_1}

Ändrar storlek på innehållet på sidorna i dokumentet.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | Stream | Stream med källdokument. |
| destination | Stream | Stream med destinationsdokument. |
| pages | Int32[] | Array av sidindex. |
| parameters | ContentsResizeParameters | Parametrar för storleksändring. |

### Returvärde

Returnerar true om det lyckades.

## Kommentarer

TryResizeContents-metoden är som ResizeContents-metoden, förutom att TryResizeContents-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

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
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### Se Även

* klass [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_1}

Ändrar storlek på innehållet på dokumentets sidor. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i standard rumsenheter.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | Stream | Stream som innehåller källdokumentet. |
| destination | Stream | Stream där det resulterande dokumentet kommer att sparas. |
| pages | Int32[] | Array av sidindex. Om null kommer alla dokumentets sidor att bearbetas. |
| newWidth | Dubbel | Ny bredd på sidinnehållet i standard rumsenheter. |
| newHeight | Dubbel | Ny höjd på sidinnehållet i standard rumsenheter. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryResizeContents-metoden är som ResizeContents-metoden, förutom att TryResizeContents-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

Ändrar storlek på innehållet på sidor i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | Sträng | Sökväg till källdokument. |
| destination | Sträng | Sökväg till destinationsdokument. |
| pages | Int32[] | Array av sidindex (sidindex börjar från 1). |
| parameters | ContentsResizeParameters | Parametrar för sidstorleksändring. |

### Returvärde

true om storleksändringen var framgångsrik.

## Kommentarer

TryResizeContents-metoden är som ResizeContents-metoden, förutom att TryResizeContents-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

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
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### Se Även

* klass [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)