---
title: "PdfFileEditor.ResizeContentsPct"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileEditor. Ridimensiona i contenuti delle Page del Document. Riduce i contenuti della Page e aggiunge i margini. La nuova dimensione dei contenuti è specificata in percentuale."
type: docs
weight: 330
url: /it/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

Ridimensiona il contenuto delle pagine del documento. Riduce il contenuto della pagina e aggiunge margini. La nuova dimensione del contenuto è specificata in percentuale.

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Stream | Stream che contiene il documento source. |
| destination | Stream | Stream dove verrà salvato il documento risultante. |
| pagine | Int32[] | Array di indici di pagina. Se null, verranno elaborate tutte le pagine del documento. |
| newWidth | Double | Nuova larghezza dei contenuti della Page in percentuale. |
| newHeight | Double | Nuova altezza dei contenuti della Page in percentuale. |

### Valore di ritorno

true se ridimensionato con successo.

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
//ridimensiona tutte le pagine del documento
null, 
//nuova larghezza dei contenuti = 60% della dimensione iniziale
60, 
//nuova altezza dei contenuti = 60% della dimensione iniziale
60);
// L'area residua della Page sarà vuota (margini della Page). La dimensione dei margini sinistro e destro è (100% - 60%) / 2 = 20%
// Lo stesso per i margini superiore e inferiore.
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

Ridimensiona il contenuto delle pagine del documento. Riduce il contenuto della pagina e aggiunge margini. La nuova dimensione del contenuto è specificata in percentuale.

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | String | Percorso al documento di origine. |
| destination | String | Percorso dove verrà salvato il documento risultante. |
| pagine | Int32[] | Array di indici di pagina. Se null, verranno elaborate tutte le pagine del documento. |
| newWidth | Double | Nuova larghezza dei contenuti della Page in percentuale. |
| newHeight | Double | Nuova altezza dei contenuti della Page in percentuale. |

### Valore di ritorno

true se il ridimensionamento è riuscito.

## Esempi

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
//ridimensiona tutte le pagine del documento
null, 
//nuova larghezza dei contenuti = 60% della dimensione iniziale
60, 
//nuova altezza dei contenuti = 60% della dimensione iniziale
60);
// L'area residua della Page sarà vuota (margini della Page). La dimensione dei margini sinistro e destro è (100% - 60%) / 2 = 20%
// Lo stesso per i margini superiore e inferiore.
```

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


