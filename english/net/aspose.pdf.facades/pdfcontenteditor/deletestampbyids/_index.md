---
title: "PdfContentEditor.DeleteStampByIds"
linktitle: "DeleteStampByIds"
articleTitle: "DeleteStampByIds"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Deletes stamps with specified IDs from all pages of the document."
type: docs
weight: 540
url: "/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyids/"
product_version: "26.9"
---
## DeleteStampByIds(int[]) {#deletestampbyids}

Deletes stamps with specified IDs from all pages of the document.

```csharp
public void DeleteStampByIds(int[] stampIds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stampIds | Int32[] | Array of stamp IDs. |

## Examples

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(new int[] { 102, 103 } );
contentEditor.Save("outfile.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampByIds(int, int[]) {#deletestampbyids_1}

Deletes stamps on the specified page by multiple stamp IDs.

```csharp
public void DeleteStampByIds(int pageNumber, int[] stampIds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Page number where stamps will be deleted. |
| stampIds | Int32[] | Array of stamp IDs. |

## Examples

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(1, new int[] { 100, 101 } );
contentEditor.Save("outfile.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

