---
title: ResizeContents
second_title: Aspose.PDF per .NET API Reference
description: Ridimensiona il contenuto delle pagine nel documento. Se la pagina viene ridotta vengono aggiunti margini vuoti intorno alla pagina.
type: docs
weight: 350
url: /it/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_4}

Ridimensiona il contenuto delle pagine nel documento. Se la pagina viene ridotta, vengono aggiunti margini vuoti intorno alla pagina.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | String | Percorso del documento di origine. |
| destination | String | Percorso del documento di destinazione. |
| pages | Int32[] | Matrice di indici di pagina (l'indice di pagina inizia da 1). |
| parameters | ContentsResizeParameters | Parametri di ridimensionamento della pagina. |

### Valore di ritorno

true se il ridimensionamento ha avuto esito positivo.

### Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //margine sinistro = 10% della larghezza della pagina
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //nuova larghezza del contenuto calcolata automaticamente come larghezza - margine sinistro - margine destro (100% - 10% - 10% = 80%)
    null,
    //il margine destro è il 10% della pagina 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //margine superiore = 10% dell'altezza
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //l'altezza del nuovo contenuto viene calcolata automaticamente (simile alla larghezza)
    null,
    //il margine inferiore è del 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### Guarda anche

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_7}

Ridimensiona le pagine del documento. I margini vuoti vengono aggiunti intorno alla pagina ridotta.

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Document | Documento di origine. |
| pages | Int32[] | Elenco di indici di pagina. |
| parameters | ContentsResizeParameters | Ridimensiona i parametri. |

### Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //margine sinistro = 10% della larghezza della pagina
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //nuova larghezza del contenuto calcolata automaticamente come larghezza - margine sinistro - margine destro (100% - 10% - 10% = 80%)
    null,
    //il margine destro è il 10% della pagina 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //margine superiore = 10% dell'altezza
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //l'altezza del nuovo contenuto viene calcolata automaticamente (simile alla larghezza)
    null,
    //il margine inferiore è del 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### Guarda anche

* class [Document](../../../aspose.pdf/document)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_6}

Ridimensiona le pagine del documento. I margini vuoti vengono aggiunti intorno alla pagina ridotta.

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Document | Documento di origine. |
| parameters | ContentsResizeParameters | Ridimensiona i parametri. |

### Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //margine sinistro = 10% della larghezza della pagina
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //nuova larghezza del contenuto calcolata automaticamente come larghezza - margine sinistro - margine destro (100% - 10% - 10% = 80%)
    null,
    //il margine destro è il 10% della pagina 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //margine superiore = 10% dell'altezza
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //l'altezza del nuovo contenuto viene calcolata automaticamente (simile alla larghezza)
    null,
    //il margine inferiore è del 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### Guarda anche

* class [Document](../../../aspose.pdf/document)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents_1}

Ridimensiona il contenuto delle pagine del documento.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Stream | Trasmetti in streaming con il documento di origine. |
| destination | Stream | Trasmetti in streaming con il documento di destinazione. |
| pages | Int32[] | Matrice di indici di pagina. |
| parameters | ContentsResizeParameters | Ridimensiona i parametri. |

### Valore di ritorno

Restituisce vero in caso di successo.

### Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //margine sinistro = 10% della larghezza della pagina
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //nuova larghezza del contenuto calcolata automaticamente come larghezza - margine sinistro - margine destro (100% - 10% - 10% = 80%)
    null,
    //il margine destro è il 10% della pagina 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //margine superiore = 10% dell'altezza
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //l'altezza del nuovo contenuto viene calcolata automaticamente (simile alla larghezza)
    null,
    //il margine inferiore è del 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### Guarda anche

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_2}

Ridimensiona il contenuto delle pagine del documento. Rimpicciolisce il contenuto della pagina e aggiunge margini. La nuova dimensione del contenuto è specificata in unità di spazio predefinite.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Stream | Stream che contiene il documento di origine. |
| destination | Stream | Stream in cui verrà salvato il documento risultante. |
| pages | Int32[] | Matrice di indici di pagina. Se nullo, tutte le pagine del documento verranno elaborate. |
| newWidth | Double | Nuova larghezza del contenuto della pagina in unità di spazio predefinite. |
| newHeight | Double | Nuova altezza del contenuto della pagina in unità di spazio predefinite. |

### Valore di ritorno

Vero se il ridimensionamento ha avuto esito positivo.

### Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
//ridimensiona tutte le pagine del documento
null, 
//nuova larghezza del contenuto = 200
200, 
//altezza del nuovo contenuto = 300
300);
// l'area di riposo della pagina sarà vuota
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], double, double) {#resizecontents_5}

Ridimensiona il contenuto delle pagine del documento. Rimpicciolisce il contenuto della pagina e aggiunge margini. La nuova dimensione del contenuto è specificata in unità di spazio predefinite.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | String | Percorso del documento di origine. |
| destination | String | Percorso in cui verrà salvato il documento risultante. |
| pages | Int32[] | Matrice di indici di pagina. Se nullo, tutte le pagine del documento verranno elaborate. |
| newWidth | Double | Nuova larghezza del contenuto della pagina in unità di spazio predefinite. |
| newHeight | Double | Nuova altezza del contenuto della pagina in unità di spazio predefinite. |

### Valore di ritorno

true se il ridimensionamento ha avuto esito positivo.

### Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
//ridimensiona tutte le pagine del documento
null, 
//nuova larghezza del contenuto = 200
200, 
//altezza del nuovo contenuto = 300
300);
// l'area di riposo della pagina sarà vuota
```

### Guarda anche

* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## ResizeContents(string, int[], ContentsResizeParameters, HttpResponse) {#resizecontents_3}

Ridimensiona il contenuto delle pagine nel documento. Se la pagina viene ridotta, vengono aggiunti margini vuoti intorno alla pagina. Il risultato viene archiviato nell'oggetto HttpResponse.

```csharp
public bool ResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | String | Percorso del file di origine. |
| pages | Int32[] | Matrice di pagine da ridimensionare. |
| parameters | ContentsResizeParameters | Ridimensiona i parametri. |
| response | HttpResponse | Oggetto HttpResponse in cui viene salvato il risultato. |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Guarda anche

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## ResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#resizecontents}

Ridimensiona il contenuto delle pagine nel documento. Se la pagina viene ridotta, vengono aggiunti margini vuoti intorno alla pagina. Il risultato viene archiviato nell'oggetto HttpResponse.

```csharp
public bool ResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Stream | Flusso del file di origine. |
| pages | Int32[] | Matrice di pagine da ridimensionare. |
| parameters | ContentsResizeParameters | Ridimensiona i parametri. |
| response | HttpResponse | Oggetto HttpResponse in cui viene salvato il risultato. |

### Valore di ritorno

Vero se l'operazione è riuscita.

### Guarda anche

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
