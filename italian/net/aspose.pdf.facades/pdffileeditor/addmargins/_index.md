---
title: "PdfFileEditor.AddMargins"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileEditor. Ridimensiona il contenuto della pagina e aggiunge i margini specificati. I margini sono specificati nelle unità di spazio predefinite."
type: docs
weight: 220
url: /it/net/aspose.pdf.facades/pdffileeditor/addmargins/
---
## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

Ridimensiona i contenuti della pagina e aggiunge i margini specificati. I margini sono specificati nelle unità di spazio predefinite.

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Stream | Stream che contiene il documento source. |
| destination | Stream | Stream dove verrà salvato il documento risultante. |
| pagine | Int32[] | Array di indici di pagina. Se null, verranno elaborate tutte le pagine del documento. |
| leftMargin | Double | Margine sinistro. |
| rightMargin | Double | Margine destro. |
| topMargin | Double | Margine superiore. |
| bottomMargin | Double | Margine inferiore. |

### Valore di ritorno

true se l'operazione è riuscita.

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //elabora le pagine 1, 2, 3
    new int[] { 1, 2, 3}, 
    //il margine sinistro è 10 unità
    10, 
    //il margine destro è 5 unità
    5, 
    //il margine superiore è 5 unità
    5, 
    //il margine inferiore è 5 unità
    5);
    dest.Close();
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

Ridimensiona i contenuti della pagina e aggiunge i margini specificati. I margini sono specificati nelle unità di spazio predefinite.

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | String | Percorso al documento di origine. |
| destination | String | Percorso dove verrà salvato il documento risultante. |
| pagine | Int32[] | Array di indici di pagina. Se null, verranno elaborate tutte le pagine del documento. |
| leftMargin | Double | Margine sinistro. |
| rightMargin | Double | Margine destro. |
| topMargin | Double | Margine superiore. |
| bottomMargin | Double | Margine inferiore. |

### Valore di ritorno

true se il ridimensionamento è riuscito.

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //elabora le pagine 1, 2, 3
    new int[] { 1, 2, 3}, 
    //il margine sinistro è 10 unità
    10, 
    //il margine destro è 5 unità
    5, 
    //il margine superiore è 5 unità
    5, 
    //il margine inferiore è 5 unità
    5);
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


