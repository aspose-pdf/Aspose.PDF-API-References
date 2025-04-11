---
title: PdfFileEditor.TryResizeContents
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor method. Resizes contents of pages of the document
type: docs
weight: 450
url: /it/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

Ridimensiona i contenuti delle pagine nel documento. Se la pagina è ridotta, vengono aggiunti margini bianchi attorno alla pagina. Il risultato è memorizzato nell'oggetto HttpResponse.

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | String | Percorso del file sorgente. |
| pages | Int32[] | Array delle pagine da ridimensionare. |
| parameters | ContentsResizeParameters | Parametri di ridimensionamento. |
| response | HttpResponse | Oggetto HttpResponse dove il risultato è salvato. |

### Valore di Ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryResizeContents è simile al metodo ResizeContents, tranne per il fatto che il metodo TryResizeContents non genera un'eccezione se l'operazione fallisce.

### Vedi Anche

* classe [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

Ridimensiona i contenuti delle pagine nel documento. Se la pagina è ridotta, vengono aggiunti margini bianchi attorno alla pagina. Il risultato è memorizzato nell'oggetto HttpResponse.

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Stream | Stream del file sorgente. |
| pages | Int32[] | Array delle pagine da ridimensionare. |
| parameters | ContentsResizeParameters | Parametri di ridimensionamento. |
| response | HttpResponse | Oggetto HttpResponse dove il risultato è salvato. |

### Valore di Ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryResizeContents è simile al metodo ResizeContents, tranne per il fatto che il metodo TryResizeContents non genera un'eccezione se l'operazione fallisce.

### Vedi Anche

* classe [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents_1}

Ridimensiona i contenuti delle pagine del documento.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Stream | Stream con il documento sorgente. |
| destination | Stream | Stream con il documento di destinazione. |
| pages | Int32[] | Array degli indici delle pagine. |
| parameters | ContentsResizeParameters | Parametri di ridimensionamento. |

### Valore di Ritorno

Restituisce true se ha successo.

## Osservazioni

Il metodo TryResizeContents è simile al metodo ResizeContents, tranne per il fatto che il metodo TryResizeContents non genera un'eccezione se l'operazione fallisce.

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
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### Vedi Anche

* classe [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_1}

Ridimensiona i contenuti delle pagine del documento. Riduce i contenuti della pagina e aggiunge margini. La nuova dimensione dei contenuti è specificata in unità di spazio predefinite.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Stream | Stream che contiene il documento sorgente. |
| destination | Stream | Stream dove il documento risultante sarà salvato. |
| pages | Int32[] | Array degli indici delle pagine. Se null, tutte le pagine del documento saranno elaborate. |
| newWidth | Double | Nuova larghezza dei contenuti della pagina in unità di spazio predefinite. |
| newHeight | Double | Nuova altezza dei contenuti della pagina in unità di spazio predefinite. |

### Valore di Ritorno

true se l'operazione è completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryResizeContents è simile al metodo ResizeContents, tranne per il fatto che il metodo TryResizeContents non genera un'eccezione se l'operazione fallisce.

## Esempi

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

### Vedi Anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

Ridimensiona i contenuti delle pagine nel documento. Se la pagina è ridotta, vengono aggiunti margini bianchi attorno alla pagina.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | String | Percorso del documento sorgente. |
| destination | String | Percorso del documento di destinazione. |
| pages | Int32[] | Array degli indici delle pagine (l'indice della pagina inizia da 1). |
| parameters | ContentsResizeParameters | Parametri di ridimensionamento della pagina. |

### Valore di Ritorno

true se il ridimensionamento è stato effettuato con successo.

## Osservazioni

Il metodo TryResizeContents è simile al metodo ResizeContents, tranne per il fatto che il metodo TryResizeContents non genera un'eccezione se l'operazione fallisce.

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
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### Vedi Anche

* classe [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)