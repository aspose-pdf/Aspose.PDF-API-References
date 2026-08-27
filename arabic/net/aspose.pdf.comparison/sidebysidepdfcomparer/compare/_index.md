---
title: "SideBySidePdfComparer.Compare"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة SideBySidePdfComparer. تقارن صفحتين. يتم حفظ النتيجة في مستند PDF تُكتب فيه الصفحة الأولى أولاً ثم الثانية. يمكنك فتحه في Adobe Acrobat في وضع العرض الصفحتين لرؤية التغييرات جنبًا إلى جنب. تُلاحظ الحذفات على الصفحة اليسرى وتُلاحظ الإدخالات على الصفحة اليمنى."
type: docs
weight: 10
url: /ar/net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## Compare(Page, Page, string, SideBySideComparisonOptions) {#compare_1}

يقارن صفحتين. يُحفظ النتيجة في مستند PDF تُكتب فيه الصفحة الأولى أولاً، ثم الثانية. يمكنك فتحه في Adobe Acrobat في وضع العرض ذو الصفحتين لرؤية التغييرات جنبًا إلى جنب. تُلاحظ الحذفات على الصفحة اليسرى، وتُلاحظ الإضافات على الصفحة اليمنى.

```csharp
public static void Compare(Page page1, Page page2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| page1 | صفحة | الصفحة الأولى للمقارنة. |
| page2 | صفحة | الصفحة الأولى للمقارنة. |
| targetPdfPath | String | المسار إلى ملف PDF لحفظ نتيجة المقارنة. |
| options | SideBySideComparisonOptions | خيارات المقارنة. |

### انظر أيضًا

* class [Page](../../../aspose.pdf/page/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare(Document, Document, string, SideBySideComparisonOptions) {#compare}

يقارن مستندين. يتم مقارنة الصفحات واحدة تلو الأخرى. تُنسخ صفحات المستندات المقارنة واحدةً تلو الأخرى إلى المستند الناتج. أولاً الصفحة الأولى من المستند الأول، ثم الصفحة الأولى من المستند الثاني. ثم الصفحة الثانية من المستند الأول ثم الصفحة الثانية من المستند الثاني، وهكذا. يمكنك فتحه في Adobe Acrobat في وضع العرض ذو الصفحتين لرؤية التغييرات جنبًا إلى جنب. تُلاحظ الحذفات على الصفحة اليسرى، وتُلاحظ الإضافات على الصفحة اليمنى.

```csharp
public static void Compare(Document document1, Document document2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| document1 | Document | المستند الأول للمقارنة. |
| document2 | Document | المستند الثاني للمقارنة. |
| targetPdfPath | String | المسار إلى ملف PDF لحفظ نتيجة المقارنة. |
| options | SideBySideComparisonOptions | خيارات المقارنة. |

### انظر أيضًا

* class [Document](../../../aspose.pdf/document/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


