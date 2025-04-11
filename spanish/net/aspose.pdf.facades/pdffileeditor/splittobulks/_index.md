---
title: PdfFileEditor.SplitToBulks
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Divide el archivo Pdf en varios documentos. Los documentos pueden ser de una sola página o de varias páginas.
type: docs
weight: 350
url: /es/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

Divide el archivo Pdf en varios documentos. Los documentos pueden ser de una sola página o de varias páginas.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Archivo PDF de entrada. |
| numberOfPage | Int32[][] | Array que contiene un array de elementos dobles, que son las páginas de inicio y fin del documento. |

### Valor de Retorno

Flujos PDF de salida, cada flujo almacena un documento PDF.

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

Divide el archivo Pdf en varios documentos. Los documentos pueden ser de una sola página o de varias páginas.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo PDF de entrada. |
| numberOfPage | Int32[][] | La página de inicio y la página final de cada documento. |

### Valor de Retorno

Flujos PDF de salida, cada flujo almacena un documento PDF.

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)