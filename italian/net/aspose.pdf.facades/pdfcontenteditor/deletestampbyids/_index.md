---
title: PdfContentEditor.DeleteStampByIds
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor method. Deletes stamps with specified IDs from all pages of the document
type: docs
weight: 350
url: /it/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyids/
---
## DeleteStampByIds(int[]) {#deletestampbyids_1}

Elimina i timbri con ID specificati da tutte le pagine del documento.

```csharp
public void DeleteStampByIds(int[] stampIds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stampIds | Int32[] | Array di ID timbri. |

## Examples

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(new int[] { 102, 103 } );
contentEditor.Save("outfile.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampByIds(int, int[]) {#deletestampbyids}

Elimina i timbri nella pagina specificata tramite più ID timbri.

```csharp
public void DeleteStampByIds(int pageNumber, int[] stampIds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Numero di pagina da cui verranno eliminati i timbri. |
| stampIds | Int32[] | Array di ID timbri. |

## Examples

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(1, new int[] { 100, 101 } );
contentEditor.Save("outfile.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)