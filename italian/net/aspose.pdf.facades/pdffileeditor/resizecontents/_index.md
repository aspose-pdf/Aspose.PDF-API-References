---
title: "PdfFileEditor.ResizeContents"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileEditor. Ridimensiona i contenuti delle pagine del documento"
type: docs
weight: 320
url: /it/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents}

Ridimensiona il contenuto delle pagine del documento.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
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
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### Vedi anche

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_1}

Ridimensiona il contenuto delle pagine del documento. Riduce il contenuto della pagina e aggiunge margini. La nuova dimensione del contenuto è specificata in unità di spazio predefinite.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
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

True se il ridimensionamento è stato eseguito con successo.

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
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

## ResizeContents(string, string, int[], double, double) {#resizecontents_3}

Ridimensiona il contenuto delle pagine del documento. Riduce il contenuto della pagina e aggiunge margini. La nuova dimensione del contenuto è specificata in unità di spazio predefinite.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | String | Percorso al documento di origine. |
| destination | String | Percorso dove verrà salvato il documento risultante. |
| pagine | Int32[] | Array di indici di pagina. Se null, verranno elaborate tutte le pagine del documento. |
| newWidth | Double | Nuova larghezza dei contenuti della pagina nelle unità di spazio predefinite. |
| newHeight | Double | Nuova altezza dei contenuti della pagina nelle unità di spazio predefinite. |

### Valore di ritorno

true se il ridimensionamento è riuscito.

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
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

## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_2}

Ridimensiona il contenuto delle pagine nel documento. Se la pagina è ridotta, vengono aggiunti margini vuoti attorno alla pagina.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
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
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### Vedi anche

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_5}

Ridimensiona le pagine del documento. Margini bianchi vengono aggiunti attorno alla pagina ridotta.

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Document | Documento di origine. |
| pagine | Int32[] | Elenco degli indici di pagina. |
| parametri | ContentsResizeParameters | Parametri di ridimensionamento. |

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
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
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### Vedi anche

* class [Document](../../../aspose.pdf/document/)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_4}

Ridimensiona le pagine del documento. Margini bianchi vengono aggiunti attorno alla pagina ridotta.

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Document | Documento di origine. |
| parametri | ContentsResizeParameters | Parametri di ridimensionamento. |

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
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
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### Vedi anche

* class [Document](../../../aspose.pdf/document/)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


