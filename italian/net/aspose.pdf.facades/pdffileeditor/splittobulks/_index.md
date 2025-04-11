---
title: PdfFileEditor.SplitToBulks
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Divide il file Pdf in diversi documenti. I documenti possono essere a pagina singola o multipagina
type: docs
weight: 350
url: /it/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

Divide il file Pdf in diversi documenti. I documenti possono essere a pagina singola o multipagina.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | File PDF di input. |
| numberOfPage | Int32[][] | Array che contiene array di elementi doppi, che sono le pagine di inizio e fine del documento. |

### Return Value

Flussi PDF di output, ogni flusso memorizza un documento PDF.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

Divide il file Pdf in diversi documenti. I documenti possono essere a pagina singola o multipagina.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flusso PDF di input. |
| numberOfPage | Int32[][] | La pagina di inizio e la pagina di fine di ciascun documento. |

### Return Value

Flussi PDF di output, ogni flusso memorizza un documento PDF.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)