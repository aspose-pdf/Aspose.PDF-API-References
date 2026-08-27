---
title: "PdfBookmarkEditor.CreateBookmarkOfPage"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfBookmarkEditor. تنشئ إشارة مرجعية للصفحة المحددة"
type: docs
weight: 20
url: /ar/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/
---
## CreateBookmarkOfPage(string, int) {#createbookmarkofpage}

ينشئ إشارة مرجعية للصفحة المحددة.

```csharp
public void CreateBookmarkOfPage(string bookmarkName, int pageNumber)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| bookmarkName | String | اسم الإشارة المرجعية المحدد. |
| pageNumber | Int32 | الصفحة المحددة كوجهة. |

## أمثلة

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarkOfPage(string[], int[]) {#createbookmarkofpage_1}

ينشئ إشارات مرجعية للصفحات المحددة.

```csharp
public void CreateBookmarkOfPage(string[] bookmarkName, int[] pageNumber)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| bookmarkName | String[] | مصفوفة عناوين الإشارات المرجعية. |
| pageNumber | Int32[] | مصفوفة صفحات الإشارة المرجعية للوجهة. |

## أمثلة

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


