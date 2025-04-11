---
title: SideBySidePdfComparer.Compare
second_title: Aspose.PDF for .NET API Reference
description: طريقة SideBySidePdfComparer. تقارن بين صفحتين. يتم حفظ النتيجة في مستند PDF حيث يتم كتابة الصفحة الأولى أولاً ثم الثانية. يمكنك فتحه في Adobe Acrobat في عرض الصفحتين لرؤية التغييرات جنبًا إلى جنب. يتم ملاحظة الحذف على الصفحة اليسرى والإضافات على الصفحة اليمنى.
type: docs
weight: 10
url: /ar/net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## Compare(Page, Page, string, SideBySideComparisonOptions) {#compare_1}

تقارن بين صفحتين. يتم حفظ النتيجة في مستند PDF حيث يتم كتابة الصفحة الأولى أولاً، ثم الثانية. يمكنك فتحه في Adobe Acrobat في عرض الصفحتين لرؤية التغييرات جنبًا إلى جنب. يتم ملاحظة الحذف على الصفحة اليسرى، والإضافات على الصفحة اليمنى.

```csharp
public static void Compare(Page page1, Page page2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page1 | Page | الصفحة الأولى للمقارنة. |
| page2 | Page | الصفحة الثانية للمقارنة. |
| targetPdfPath | String | المسار إلى ملف PDF لحفظ نتيجة المقارنة. |
| options | SideBySideComparisonOptions | خيارات المقارنة. |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare(Document, Document, string, SideBySideComparisonOptions) {#compare}

تقارن بين مستندين. يتم مقارنة الصفحات واحدة تلو الأخرى. يتم نسخ صفحات المستندات المقارنة واحدة تلو الأخرى إلى المستند الناتج. أولاً الصفحة الأولى من المستند الأول، ثم الصفحة الأولى من المستند الثاني. بعد ذلك الصفحة الثانية من المستند الأول ثم الصفحة الثانية من المستند الثاني، وهكذا. يمكنك فتحه في Adobe Acrobat في عرض الصفحتين لرؤية التغييرات جنبًا إلى جنب. يتم ملاحظة الحذف على الصفحة اليسرى، والإضافات على الصفحة اليمنى.

```csharp
public static void Compare(Document document1, Document document2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | المستند الأول للمقارنة. |
| document2 | Document | المستند الثاني للمقارنة. |
| targetPdfPath | String | المسار إلى ملف PDF لحفظ نتيجة المقارنة. |
| options | SideBySideComparisonOptions | خيارات المقارنة. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)