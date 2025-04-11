---
title: PdfBookmarkEditor.CreateBookmarkOfPage
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfBookmarkEditor. تنشئ إشارة مرجعية للصفحة المحددة
type: docs
weight: 20
url: /ar/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/
---
## CreateBookmarkOfPage(string, int) {#createbookmarkofpage}

تنشئ إشارة مرجعية للصفحة المحددة.

```csharp
public void CreateBookmarkOfPage(string bookmarkName, int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| bookmarkName | String | اسم الإشارة المرجعية المحدد. |
| pageNumber | Int32 | الصفحة المحددة. |

## Examples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### See Also

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarkOfPage(string[], int[]) {#createbookmarkofpage_1}

تنشئ إشارات مرجعية للصفحات المحددة.

```csharp
public void CreateBookmarkOfPage(string[] bookmarkName, int[] pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| bookmarkName | String[] | مصفوفة عناوين الإشارات المرجعية. |
| pageNumber | Int32[] | مصفوفة الصفحات المحددة للإشارات المرجعية. |

## Examples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### See Also

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)