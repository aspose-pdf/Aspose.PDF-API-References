---
title: PdfFileEditor.ResizeContents
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Ridimensiona i contenuti delle pagine del documento
type: docs
weight: 320
url: /it/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents}

Ridimensiona i contenuti delle pagine del documento.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Stream | Stream con il documento sorgente. |
| destination | Stream | Stream con il documento di destinazione. |
| pages | Int32[] | Array degli indici delle pagine. |
| parameters | ContentsResizeParameters | Parametri di ridimensionamento. |

### Valore di ritorno

Restituisce true se ha avuto successo.

## Esempi

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

### Vedi anche

* classe [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_1}

Ridimensiona i contenuti delle pagine del documento. Riduce i contenuti della pagina e aggiunge margini. La nuova dimensione dei contenuti è specificata in unità di spazio predefinite.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Stream | Stream che contiene il documento sorgente. |
| destination | Stream | Stream dove verrà salvato il documento risultante. |
| pages | Int32[] | Array degli indici delle pagine. Se null, tutte le pagine del documento verranno elaborate. |
| newWidth | Double | Nuova larghezza dei contenuti della pagina in unità di spazio predefinite. |
| newHeight | Double | Nuova altezza dei contenuti della pagina in unità di spazio predefinite. |

### Valore di ritorno

True se il ridimensionamento è stato effettuato con successo.

## Esempi

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

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], double, double) {#resizecontents_3}

Ridimensiona i contenuti delle pagine del documento. Riduce i contenuti della pagina e aggiunge margini. La nuova dimensione dei contenuti è specificata in unità di spazio predefinite.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | String | Percorso del documento sorgente. |
| destination | String | Percorso dove verrà salvato il documento risultante. |
| pages | Int32[] | Array degli indici delle pagine. Se null, tutte le pagine del documento verranno elaborate. |
| newWidth | Double | Nuova larghezza dei contenuti della pagina in unità di spazio predefinite. |
| newHeight | Double | Nuova altezza dei contenuti della pagina in unità di spazio predefinite. |

### Valore di ritorno

true se il ridimensionamento è stato effettuato con successo.

## Esempi

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

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_2}

Ridimensiona i contenuti delle pagine nel documento. Se la pagina è ridotta, vengono aggiunti margini vuoti attorno alla pagina.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | String | Percorso del documento sorgente. |
| destination | String | Percorso del documento di destinazione. |
| pages | Int32[] | Array degli indici delle pagine (l'indice della pagina inizia da 1). |
| parameters | ContentsResizeParameters | Parametri di ridimensionamento della pagina. |

### Valore di ritorno

true se il ridimensionamento è stato effettuato con successo.

## Esempi

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

### Vedi anche

* classe [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_5}

Ridimensiona le pagine del documento. Vengono aggiunti margini vuoti attorno alla pagina ridotta.

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Document | Documento sorgente. |
| pages | Int32[] | Elenco degli indici delle pagine. |
| parameters | ContentsResizeParameters | Parametri di ridimensionamento. |

## Esempi

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

### Vedi anche

* classe [Document](../../../aspose.pdf/document/)
* classe [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_4}

Ridimensiona le pagine del documento. Vengono aggiunti margini vuoti attorno alla pagina ridotta.

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Document | Documento sorgente. |
| parameters | ContentsResizeParameters | Parametri di ridimensionamento. |

## Esempi

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

### Vedi anche

* classe [Document](../../../aspose.pdf/document/)
* classe [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)