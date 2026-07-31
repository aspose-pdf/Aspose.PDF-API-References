---
title: "PdfFileEditor.AddMarginsPct"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileEditor. Ridimensiona i contenuti della pagina e aggiunge i margini specificati. I margini sono specificati in percentuale della dimensione iniziale della pagina."
type: docs
weight: 230
url: /it/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

Ridimensiona i contenuti della pagina e aggiunge i margini specificati. I margini sono specificati in percentuale della dimensione iniziale della pagina.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Stream | Stream che contiene il documento source. |
| destination | Stream | Stream dove verrà salvato il documento risultante. |
| pagine | Int32[] | Array di indici di pagina. Se null, verranno elaborate tutte le pagine del documento. |
| leftMargin | Double | Margine sinistro in percentuale della dimensione iniziale della pagina. |
| rightMargin | Double | Margine destro in percentuale della dimensione iniziale della pagina. |
| topMargin | Double | Margine superiore in percentuale della dimensione iniziale della pagina. |
| bottomMargin | Double | Margine inferiore in percentuale della dimensione iniziale della pagina. |

### Valore di ritorno

true se l'azione è stata eseguita con successo.

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //elabora le pagine 1, 2, 3
    new int[] { 1, 2, 3}, 
    //Il margine sinistro è il 15% della larghezza della pagina
    15, 
    //Il margine destro è il 10% della larghezza della pagina
    10, 
    //Il margine superiore è il 20% della larghezza della pagina
    20, 
    //Il margine inferiore è il 5% della larghezza della pagina
    5);
    dest.Close();
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

Ridimensiona i contenuti della pagina e aggiunge i margini specificati. I margini sono specificati in percentuale della dimensione iniziale della pagina.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | String | Percorso al documento di origine. |
| destination | String | Percorso dove verrà salvato il documento risultante. |
| pagine | Int32[] | Array di indici di pagina. Se null, verranno elaborate tutte le pagine del documento. |
| leftMargin | Double | Margine sinistro in percentuale della dimensione iniziale della pagina. |
| rightMargin | Double | Margine destro in percentuale della dimensione iniziale della pagina. |
| topMargin | Double | Margine superiore in percentuale della dimensione iniziale della pagina. |
| bottomMargin | Double | Margine inferiore in percentuale della dimensione iniziale della pagina. |

### Valore di ritorno

true se il ridimensionamento è stato eseguito con successo

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //elabora le pagine 1, 2, 3
    new int[] { 1, 2, 3}, 
    //Il margine sinistro è il 15% della larghezza della pagina
    15, 
    //Il margine destro è il 10% della larghezza della pagina
    10, 
    //Il margine superiore è il 20% della larghezza della pagina
    20, 
    //Il margine inferiore è il 5% della larghezza della pagina
    5);
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


