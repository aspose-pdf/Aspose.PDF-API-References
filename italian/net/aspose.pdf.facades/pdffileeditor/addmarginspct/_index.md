---
title: PdfFileEditor.AddMarginsPct
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Ridimensiona i contenuti della pagina e aggiunge margini specificati. I margini sono specificati in percentuale rispetto alla dimensione iniziale della pagina
type: docs
weight: 230
url: /it/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

Ridimensiona i contenuti della pagina e aggiunge margini specificati. I margini sono specificati in percentuale rispetto alla dimensione iniziale della pagina.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream | Stream che contiene il documento sorgente. |
| destination | Stream | Stream dove il documento risultante sarà salvato. |
| pages | Int32[] | Array degli indici delle pagine. Se nullo, tutte le pagine del documento saranno elaborate. |
| leftMargin | Double | Margine sinistro in percentuale rispetto alla dimensione iniziale della pagina. |
| rightMargin | Double | Margine destro in percentuale rispetto alla dimensione iniziale della pagina. |
| topMargin | Double | Margine superiore in percentuale rispetto alla dimensione iniziale della pagina. |
| bottomMargin | Double | Margine inferiore in percentuale rispetto alla dimensione iniziale della pagina. |

### Return Value

true se l'azione è stata eseguita con successo.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
    dest.Close();
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

Ridimensiona i contenuti della pagina e aggiunge margini specificati. I margini sono specificati in percentuale rispetto alla dimensione iniziale della pagina.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | String | Percorso del documento sorgente. |
| destination | String | Percorso dove il documento risultante sarà salvato. |
| pages | Int32[] | Array degli indici delle pagine. Se nullo, tutte le pagine del documento saranno elaborate. |
| leftMargin | Double | Margine sinistro in percentuale rispetto alla dimensione iniziale della pagina. |
| rightMargin | Double | Margine destro in percentuale rispetto alla dimensione iniziale della pagina. |
| topMargin | Double | Margine superiore in percentuale rispetto alla dimensione iniziale della pagina. |
| bottomMargin | Double | Margine inferiore in percentuale rispetto alla dimensione iniziale della pagina. |

### Return Value

true se il ridimensionamento è stato eseguito con successo

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)