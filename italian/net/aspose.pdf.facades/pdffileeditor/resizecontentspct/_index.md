---
title: PdfFileEditor.ResizeContentsPct
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Ridimensiona i contenuti delle pagine del documento. Riduce i contenuti della pagina e aggiunge margini. La nuova dimensione dei contenuti è specificata in percentuale
type: docs
weight: 330
url: /it/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

Ridimensiona i contenuti delle pagine del documento. Riduce i contenuti della pagina e aggiunge margini. La nuova dimensione dei contenuti è specificata in percentuale.

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | Stream | Stream che contiene il documento sorgente. |
| destination | Stream | Stream dove il documento risultante sarà salvato. |
| pages | Int32[] | Array degli indici delle pagine. Se nullo, tutte le pagine del documento saranno elaborate. |
| newWidth | Double | Nuova larghezza dei contenuti della pagina in percentuale. |
| newHeight | Double | Nuova altezza dei contenuti della pagina in percentuale. |

### Return Value

true se ridimensionato con successo.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
//resize all pages of document
null, 
//new contents width = 60% of initial size
60, 
//new contents height = 60% of initial size
60);
// Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
// The same for top and bottom margins.
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

Ridimensiona i contenuti delle pagine del documento. Riduce i contenuti della pagina e aggiunge margini. La nuova dimensione dei contenuti è specificata in percentuale.

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | String | Percorso del documento sorgente. |
| destination | String | Percorso dove il documento risultante sarà salvato. |
| pages | Int32[] | Array degli indici delle pagine. Se nullo, tutte le pagine del documento saranno elaborate. |
| newWidth | Double | Nuova larghezza dei contenuti della pagina in percentuale. |
| newHeight | Double | Nuova altezza dei contenuti della pagina in percentuale. |

### Return Value

true se il ridimensionamento è stato riuscito.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
//resize all pages of document
null, 
//new contents width = 60% of initial size
60, 
//new contents height = 60% of initial size
60);
// Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
// The same for top and bottom margins.
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)