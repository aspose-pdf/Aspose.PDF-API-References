---
title: TextPdfComparer.CompareFlatDocuments
second_title: Aspose.PDF for .NET API Reference
description: طريقة TextPdfComparer. تقارن بين مستندين صفحة بصفحة. يتم مقارنة المستندات ككل. قبل مقارنة النصوص، يتم دمج نصوص صفحات المستند في نص واحد
type: docs
weight: 50
url: /ar/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## CompareFlatDocuments(Document, Document, ComparisonOptions) {#compareflatdocuments}

تقارن بين مستندين صفحة بصفحة. يتم مقارنة المستندات ككل. قبل مقارنة النص، يتم دمج نصوص صفحات المستند في نص واحد.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | المستند الأول. |
| document2 | Document | المستند الثاني. |
| options | ComparisonOptions | خيارات المقارنة. |

### Return Value

قائمة بالتغييرات.

### See Also

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments(Document, Document, ComparisonOptions, string) {#compareflatdocuments_1}

تقارن بين مستندين صفحة بصفحة. يتم حفظ النتيجة في ملف PDF. يتم مقارنة المستندات ككل. قبل مقارنة النص، يتم دمج نصوص صفحات المستند في نص واحد.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options, string resultPdfDocumentPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | المستند الأول. |
| document2 | Document | المستند الثاني. |
| options | ComparisonOptions | خيارات المقارنة. |
| resultPdfDocumentPath | String | المسار إلى ملف PDF لحفظ نتائج المقارنة. |

### Return Value

قائمة بالتغييرات.

### See Also

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)