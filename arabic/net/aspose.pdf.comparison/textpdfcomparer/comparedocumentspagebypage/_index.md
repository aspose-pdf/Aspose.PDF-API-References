---
title: TextPdfComparer.CompareDocumentsPageByPage
second_title: Aspose.PDF for .NET API Reference
description: طريقة TextPdfComparer. تقارن بين مستندين صفحة بصفحة
type: docs
weight: 40
url: /ar/net/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/
---
## CompareDocumentsPageByPage(Document, Document, ComparisonOptions) {#comparedocumentspagebypage}

تقارن بين مستندين صفحة بصفحة.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | المستند الأول.. |
| document2 | Document | المستند الثاني. |
| options | ComparisonOptions | خيارات المقارنة. |

### Return Value

قائمة بالتغييرات حسب الصفحة.

### See Also

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareDocumentsPageByPage(Document, Document, ComparisonOptions, string) {#comparedocumentspagebypage_1}

تقارن بين مستندين صفحة بصفحة. يتم حفظ النتيجة في ملف PDF.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options, string resultPdfDocumentPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | المستند الأول.. |
| document2 | Document | المستند الثاني. |
| options | ComparisonOptions | خيارات المقارنة. |
| resultPdfDocumentPath | String | المسار إلى ملف pdf لحفظ نتائج المقارنة. |

### Return Value

قائمة بالتغييرات حسب الصفحة.

### See Also

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)