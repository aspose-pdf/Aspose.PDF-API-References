---
title: PdfFileEditor.SplitToBulks
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Divide o arquivo Pdf em vários documentos. Os documentos podem ser de uma página ou várias páginas.
type: docs
weight: 350
url: /pt/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

Divide o arquivo Pdf em vários documentos. Os documentos podem ser de uma página ou várias páginas.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFile | String | Arquivo PDF de entrada. |
| numberOfPage | Int32[][] | Array que contém um array de elementos duplos, que são as páginas inicial e final do documento. |

### Valor de Retorno

Fluxos PDF de saída, cada fluxo armazena um documento PDF.

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

Divide o arquivo Pdf em vários documentos. Os documentos podem ser de uma página ou várias páginas.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Fluxo PDF de entrada. |
| numberOfPage | Int32[][] | A página inicial e a página final de cada documento. |

### Valor de Retorno

Fluxos PDF de saída, cada fluxo armazena um documento PDF.

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)