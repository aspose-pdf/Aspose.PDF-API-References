---
title: PdfContentEditor.DeleteStampByIds
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تحذف الطوابع ذات المعرفات المحددة من جميع صفحات المستند
type: docs
weight: 350
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyids/
---
## DeleteStampByIds(int[]) {#deletestampbyids_1}

تحذف الطوابع ذات المعرفات المحددة من جميع صفحات المستند.

```csharp
public void DeleteStampByIds(int[] stampIds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stampIds | Int32[] | مصفوفة من معرفات الطوابع. |

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

تحذف الطوابع في الصفحة المحددة بواسطة معرفات طوابع متعددة.

```csharp
public void DeleteStampByIds(int pageNumber, int[] stampIds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | رقم الصفحة التي سيتم حذف الطوابع منها. |
| stampIds | Int32[] | مصفوفة من معرفات الطوابع. |

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