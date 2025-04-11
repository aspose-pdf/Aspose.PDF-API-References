---
title: PdfFileEditor.AddMargins
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Ridimensiona i contenuti della pagina e aggiunge margini specificati. I margini sono specificati in unità di spazio predefinite
type: docs
weight: 220
url: /it/net/aspose.pdf.facades/pdffileeditor/addmargins/
---
## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

Ridimensiona i contenuti della pagina e aggiunge margini specificati. I margini sono specificati in unità di spazio predefinite.

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream | Stream che contiene il documento sorgente. |
| destination | Stream | Stream dove il documento risultante sarà salvato. |
| pages | Int32[] | Array degli indici delle pagine. Se nullo, tutte le pagine del documento saranno elaborate. |
| leftMargin | Double | Margine sinistro. |
| rightMargin | Double | Margine destro. |
| topMargin | Double | Margine superiore. |
| bottomMargin | Double | Margine inferiore. |

### Return Value

true se l'operazione è stata completata con successo.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
    dest.Close();
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

Ridimensiona i contenuti della pagina e aggiunge margini specificati. I margini sono specificati in unità di spazio predefinite.

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | String | Percorso del documento sorgente. |
| destination | String | Percorso dove il documento risultante sarà salvato. |
| pages | Int32[] | Array degli indici delle pagine. Se nullo, tutte le pagine del documento saranno elaborate. |
| leftMargin | Double | Margine sinistro. |
| rightMargin | Double | Margine destro. |
| topMargin | Double | Margine superiore. |
| bottomMargin | Double | Margine inferiore. |

### Return Value

true se il ridimensionamento è stato completato con successo.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)