---
title: "TextPdfComparer.CompareFlatDocuments"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة TextPdfComparer. تقارن مستندين صفحة بصفحة. يتم مقارنة المستندات ككل. قبل مقارنة النص يتم دمج نصوص صفحات المستند في نص واحد"
type: docs
weight: 50
url: /ar/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## CompareFlatDocuments(Document, Document, ComparisonOptions) {#compareflatdocuments}

يقارن مستندين صفحة بصفحة. يتم مقارنة المستندات ككل. قبل مقارنة النص، يتم دمج نصوص صفحات المستند في نص واحد.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| document1 | Document | المستند الأول. |
| document2 | Document | المستند الثاني. |
| options | ComparisonOptions | خيارات المقارنة. |

### قيمة الإرجاع

قائمة التغييرات.

### انظر أيضًا

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments(Document, Document, ComparisonOptions, string) {#compareflatdocuments_1}

يقارن مستندين صفحة بصفحة. يتم حفظ النتيجة في ملف PDF. يتم مقارنة المستندات ككل. قبل مقارنة النص، يتم دمج نصوص صفحات المستند في نص واحد.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options, string resultPdfDocumentPath)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| document1 | Document | المستند الأول. |
| document2 | Document | المستند الثاني. |
| options | ComparisonOptions | خيارات المقارنة. |
| resultPdfDocumentPath | String | المسار إلى ملف pdf لحفظ نتائج المقارنة. |

### قيمة الإرجاع

قائمة التغييرات.

### انظر أيضًا

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


