---
title: PdfContentEditor.DeleteStampById
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Elimina el sello en la página especificada por ID de sello
type: docs
weight: 340
url: /es/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyid/
---
## DeleteStampById(int, int) {#deletestampbyid_1}

Elimina el sello en la página especificada por ID de sello.

```csharp
public void DeleteStampById(int pageNumber, int stampId)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber | Int32 | Número de página donde se eliminará el sello. |
| stampId | Int32 | Identificador del sello que debe ser eliminado. |

## Ejemplos

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(1, 100);
contentEditor.Save("outfile.pdf");
```

### Ver También

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampById(int) {#deletestampbyid}

Elimina el sello por ID de todas las páginas del documento.

```csharp
public void DeleteStampById(int stampId)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stampId | Int32 | Identificador del sello que debe ser eliminado. |

## Ejemplos

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(100);
contentEditor.Save("outfile.pdf");
```

### Ver También

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)