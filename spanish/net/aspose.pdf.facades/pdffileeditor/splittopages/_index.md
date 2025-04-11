---
title: PdfFileEditor.SplitToPages
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Divide el archivo PDF en documentos de una sola página
type: docs
weight: 370
url: /es/net/aspose.pdf.facades/pdffileeditor/splittopages/
---
## SplitToPages(string) {#splittopages_1}

Divide el archivo PDF en documentos de una sola página.

```csharp
public MemoryStream[] SplitToPages(string inputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Nombre del archivo PDF de entrada. |

### Valor de Retorno

Flujos PDF de salida, cada flujo almacena un documento PDF de una sola página.

### Véase También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

Divide el archivo Pdf en documentos de una sola página.

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo Pdf de entrada. |

### Valor de Retorno

Array de flujos de memoria que contienen las páginas del documento.

### Véase También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

Divide el archivo Pdf en documentos de una sola página y lo guarda en la ruta especificada. La ruta se especifica mediante el nombre del campo de plantilla.

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Nombre del archivo de entrada. |
| fileNameTemplate | String | Plantilla del nombre del archivo resultante. Debe contener %NUM% que se reemplaza con el número de página. Por ejemplo, si se especifica c:/dir/page%NUM%.pdf, los archivos resultantes tendrán los siguientes nombres: c:/dir/page1.pdf, c:/dir/page2.pdf, etc. |

### Véase También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

Divide el archivo Pdf en documentos de una sola página y lo guarda en la ruta especificada. La ruta se especifica mediante el nombre del campo de plantilla.

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo del documento fuente. |
| fileNameTemplate | String | Plantilla del nombre del archivo resultante. Debe contener %NUM% que se reemplaza con el número de página. Por ejemplo, si se especifica c:/dir/page%NUM%.pdf, los archivos resultantes tendrán los siguientes nombres: c:/dir/page1.pdf, c:/dir/page2.pdf, etc. |

### Véase También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)