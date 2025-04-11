---
title: PdfContentEditor.DeleteStampByIds
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Elimina sellos con IDs especificados de todas las páginas del documento
type: docs
weight: 350
url: /es/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyids/
---
## DeleteStampByIds(int[]) {#deletestampbyids_1}

Elimina sellos con IDs especificados de todas las páginas del documento.

```csharp
public void DeleteStampByIds(int[] stampIds)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stampIds | Int32[] | Array de IDs de sellos. |

## Ejemplos

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(new int[] { 102, 103 } );
contentEditor.Save("outfile.pdf");
```

### Ver También

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampByIds(int, int[]) {#deletestampbyids}

Elimina sellos en la página especificada por múltiples IDs de sellos.

```csharp
public void DeleteStampByIds(int pageNumber, int[] stampIds)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber | Int32 | Número de página donde se eliminarán los sellos. |
| stampIds | Int32[] | Array de IDs de sellos. |

## Ejemplos

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(1, new int[] { 100, 101 } );
contentEditor.Save("outfile.pdf");
```

### Ver También

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)