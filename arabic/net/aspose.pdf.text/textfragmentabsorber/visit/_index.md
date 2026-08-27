---
title: "TextFragmentAbsorber.Visit"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة TextFragmentAbsorber. تقوم بالبحث على الصفحة المحددة"
type: docs
weight: 150
url: /ar/net/aspose.pdf.text/textfragmentabsorber/visit/
---
## Visit(Page) {#visit_1}

ينفّذ البحث على الصفحة المحددة.

```csharp
public override void Visit(Page page)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صفحة | صفحة | كائن صفحة مستند PDF. |

## أمثلة

يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// العثور على الخط الذي سيُستخدم لتغيير خط نص المستند
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
absorber.Visit(doc.Pages[1]);

// غيّر نص جميع حالات البحث
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [Page](../../../aspose.pdf/page/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

ينفّذ البحث على المستند المحدد.

```csharp
public override void Visit(Document pdf)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| pdf | Document | كائن مستند PDF. |

## أمثلة

يوضح المثال كيفية العثور على النص في مستند PDF واستبدال نص جميع حالات البحث.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// العثور على الخط الذي سيُستخدم لتغيير خط نص المستند
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
absorber.Visit(doc);

// غيّر نص أول حالة نصية
absorber.TextFragments[1].Text = "hi world";

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

ينفّذ البحث على كائن النموذج المحدد.

```csharp
public void Visit(XForm xForm)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| xForm | XForm | كائن نموذج Pdf. |

### انظر أيضًا

* class [XForm](../../../aspose.pdf/xform/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


