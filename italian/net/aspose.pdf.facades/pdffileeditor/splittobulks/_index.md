---
title: "PdfFileEditor.SplitToBulks"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileEditor. Divide il file PDF in diversi documenti. I documenti possono essere a pagina singola o multipagina."
type: docs
weight: 350
url: /it/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

Divide il file Pdf in più documenti. I documenti possono essere a pagina singola o multi-pagina.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | File PDF di input. |
| numberOfPage | Int32[][] | Array che contiene un array di elementi double, che rappresentano le pagine di inizio e fine del documento. |

### Valore di ritorno

Flussi PDF di output, ogni flusso memorizza in buffer un documento PDF.

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

Divide il file Pdf in più documenti. I documenti possono essere a pagina singola o multi-pagina.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso PDF di input. |
| numberOfPage | Int32[][] | La pagina iniziale e la pagina finale di ogni documento. |

### Valore di ritorno

Flussi PDF di output, ogni flusso memorizza in buffer un documento PDF.

### Vedi anche

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


