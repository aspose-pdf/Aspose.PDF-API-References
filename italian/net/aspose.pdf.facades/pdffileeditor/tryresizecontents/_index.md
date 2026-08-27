---
title: "PdfFileEditor.TryResizeContents"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileEditor. Ridimensiona i contenuti delle pagine del documento"
type: docs
weight: 450
url: /it/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

Ridimensiona il contenuto delle pagine del documento.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Stream | Stream con il documento di origine. |
| destination | Stream | Stream con il documento di destinazione. |
| pagine | Int32[] | Array di indici di pagina. |
| parametri | ContentsResizeParameters | Parametri di ridimensionamento. |

### Valore di ritorno

Restituisce true se ha successo.

## Osservazioni

Il metodo TryResizeContents è simile al metodo ResizeContents, tranne che il metodo TryResizeContents non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //margine sinistro = 10% della larghezza della pagina
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //la nuova larghezza dei contenuti viene calcolata automaticamente come larghezza - margine sinistro - margine destro (100% - 10% - 10% = 80%)
    null,
    //il margine destro è il 10% della pagina
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //margine superiore = 10% dell'altezza
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //l'altezza dei nuovi contenuti è calcolata automaticamente (simile alla larghezza)
    null,
    //Il margine inferiore è 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### Vedi anche

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_1}

Ridimensiona il contenuto delle pagine del documento. Riduce il contenuto della pagina e aggiunge margini. La nuova dimensione del contenuto è specificata in unità di spazio predefinite.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Stream | Stream che contiene il documento source. |
| destination | Stream | Stream dove verrà salvato il documento risultante. |
| pagine | Int32[] | Array di indici di pagina. Se null, verranno elaborate tutte le pagine del documento. |
| newWidth | Double | Nuova larghezza dei contenuti della pagina nelle unità di spazio predefinite. |
| newHeight | Double | Nuova altezza dei contenuti della pagina nelle unità di spazio predefinite. |

### Valore di ritorno

true se l'operazione è stata completata con successo; altrimenti, false.

## Osservazioni

Il metodo TryResizeContents è simile al metodo ResizeContents, tranne che il metodo TryResizeContents non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
//ridimensiona tutte le pagine del documento
null, 
//larghezza dei nuovi contenuti = 200
200, 
//altezza dei nuovi contenuti = 300
300);
// l'area restante della pagina sarà vuota
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

Ridimensiona il contenuto delle pagine nel documento. Se la pagina è ridotta, vengono aggiunti margini vuoti attorno alla pagina.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | String | Percorso del documento di origine. |
| destination | String | Percorso del documento di destinazione. |
| pagine | Int32[] | Array di indici di pagina (l'indice della pagina inizia da 1). |
| parametri | ContentsResizeParameters | Parametri del ridimensionamento della pagina. |

### Valore di ritorno

true se il ridimensionamento è riuscito.

## Osservazioni

Il metodo TryResizeContents è simile al metodo ResizeContents, tranne che il metodo TryResizeContents non genera un'eccezione se l'operazione fallisce.

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //margine sinistro = 10% della larghezza della pagina
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //la nuova larghezza dei contenuti viene calcolata automaticamente come larghezza - margine sinistro - margine destro (100% - 10% - 10% = 80%)
    null,
    //il margine destro è il 10% della pagina
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //margine superiore = 10% dell'altezza
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //l'altezza dei nuovi contenuti è calcolata automaticamente (simile alla larghezza)
    null,
    //Il margine inferiore è 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### Vedi anche

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


