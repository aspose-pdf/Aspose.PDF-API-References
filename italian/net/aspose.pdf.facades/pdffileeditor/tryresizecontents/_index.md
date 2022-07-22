---
title: TryResizeContents
second_title: Aspose.PDF per .NET API Reference
description: Ridimensiona il contenuto delle pagine nel documento. Se la pagina viene ridotta vengono aggiunti margini vuoti intorno alla pagina. Il risultato viene archiviato nelloggetto HttpResponse.
type: docs
weight: 480
url: /it/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(string, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents_3}

Ridimensiona il contenuto delle pagine nel documento. Se la pagina viene ridotta, vengono aggiunti margini vuoti intorno alla pagina. Il risultato viene archiviato nell'oggetto HttpResponse.

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | String | Percorso del file di origine. |
| pages | Int32[] | Matrice di pagine da ridimensionare. |
| parameters | ContentsResizeParameters | Ridimensiona i parametri. |
| response | HttpResponse | Oggetto HttpResponse in cui viene salvato il risultato. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryResizeContents è come il metodo ResizeContents, tranne per il fatto che il metodo TryResizeContents non genera un'eccezione se l'operazione non riesce.

### Guarda anche

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

Ridimensiona il contenuto delle pagine nel documento. Se la pagina viene ridotta, vengono aggiunti margini vuoti intorno alla pagina. Il risultato viene archiviato nell'oggetto HttpResponse.

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Stream | Flusso del file di origine. |
| pages | Int32[] | Matrice di pagine da ridimensionare. |
| parameters | ContentsResizeParameters | Ridimensiona i parametri. |
| response | HttpResponse | Oggetto HttpResponse in cui viene salvato il risultato. |

### Valore di ritorno

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryResizeContents è come il metodo ResizeContents, tranne per il fatto che il metodo TryResizeContents non genera un'eccezione se l'operazione non riesce.

### Guarda anche

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents_1}

Ridimensiona il contenuto delle pagine del documento.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
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

### Osservazioni

Il metodo TryResizeContents è come il metodo ResizeContents, tranne per il fatto che il metodo TryResizeContents non genera un'eccezione se l'operazione non riesce.

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
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### Guarda anche

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_2}

Ridimensiona il contenuto delle pagine del documento. Rimpicciolisce il contenuto della pagina e aggiunge margini. La nuova dimensione del contenuto è specificata in unità di spazio predefinite.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
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

true se l'operazione è stata completata correttamente; altrimenti falso.

### Osservazioni

Il metodo TryResizeContents è come il metodo ResizeContents, tranne per il fatto che il metodo TryResizeContents non genera un'eccezione se l'operazione non riesce.

### Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
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

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_4}

Ridimensiona il contenuto delle pagine nel documento. Se la pagina viene ridotta, vengono aggiunti margini vuoti intorno alla pagina.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
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

### Osservazioni

Il metodo TryResizeContents è come il metodo ResizeContents, tranne per il fatto che il metodo TryResizeContents non genera un'eccezione se l'operazione non riesce.

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
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### Guarda anche

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffileeditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
