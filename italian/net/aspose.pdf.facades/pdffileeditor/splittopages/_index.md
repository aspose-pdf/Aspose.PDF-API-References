---
title: PdfFileEditor.SplitToPages
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileEditor. Divide il file PDF in documenti a pagina singola
type: docs
weight: 370
url: /it/net/aspose.pdf.facades/pdffileeditor/splittopages/
---
## SplitToPages(string) {#splittopages_1}

Divide il file PDF in documenti a pagina singola.

```csharp
public MemoryStream[] SplitToPages(string inputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Nome del file PDF di input. |

### Valore di ritorno

Flussi PDF di output, ogni flusso memorizza un documento PDF a pagina singola.

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

Divide il file Pdf in documenti a pagina singola.

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso Pdf di input. |

### Valore di ritorno

Array di flussi di memoria che contengono le pagine del documento.

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

Divide il file Pdf in documenti a pagina singola e lo salva nel percorso specificato. Il percorso è specificato dal nome del campo template.

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | Nome del file di input. |
| fileNameTemplate | String | Template del nome del file risultante. Deve contenere %NUM% che viene sostituito con il numero di pagina. Ad esempio, se viene specificato c:/dir/page%NUM%.pdf, i file risultanti avranno i seguenti nomi: c:/dir/page1.pdf, c:/dir/page2.pdf ecc. |

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

Divide il file Pdf in documenti a pagina singola e lo salva nel percorso specificato. Il percorso è specificato dal nome del campo template.

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso del documento sorgente. |
| fileNameTemplate | String | Template del nome del file risultante. Deve contenere %NUM% che viene sostituito con il numero di pagina. Ad esempio, se viene specificato c:/dir/page%NUM%.pdf, i file risultanti avranno i seguenti nomi: c:/dir/page1.pdf, c:/dir/page2.pdf ecc. |

### Vedi anche

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)