---
title: Visit
second_title: Aspose.PDF لمرجع .NET API
description: يقوم بالبحث في الصفحة المحددة .
type: docs
weight: 140
url: /ar/net/aspose.pdf.text/textfragmentabsorber/visit/
---
## Visit(Page) {#visit_1}

يقوم بالبحث في الصفحة المحددة .

```csharp
public override void Visit(Page page)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| page | Page | كائن صفحة وثيقة PDF. |

### أمثلة

يوضح المثال كيفية البحث عن نص في صفحة مستند PDF الأولى واستبدال النص.

```csharp
// افتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// ابحث عن الخط الذي سيتم استخدامه لتغيير خط نص المستند
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات نص "أهلًا بالعالم"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
absorber.Visit(doc.Pages[1]);

// تغيير نص جميع تكرارات البحث
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// حفظ الوثيقة
doc.Save(@"D:\Tests\output.pdf");  
```

### أنظر أيضا

* class [Page](../../../aspose.pdf/page)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* مساحة الاسم [Aspose.Pdf.Text](../../textfragmentabsorber)
* المجسم [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

يقوم بالبحث في المستند المحدد.

```csharp
public override void Visit(Document pdf)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pdf | Document | كائن مستند PDF. |

### أمثلة

يوضح المثال كيفية العثور على نص في مستند PDF واستبدال نص جميع حالات البحث.

```csharp
// افتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// ابحث عن الخط الذي سيتم استخدامه لتغيير خط نص المستند
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات نص "أهلًا بالعالم"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
absorber.Visit(doc);

// تغيير نص تواجد النص الأول
absorber.TextFragments[1].Text = "hi world";

// حفظ الوثيقة
doc.Save(@"D:\Tests\output.pdf");  
```

### أنظر أيضا

* class [Document](../../../aspose.pdf/document)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* مساحة الاسم [Aspose.Pdf.Text](../../textfragmentabsorber)
* المجسم [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

يقوم بالبحث عن كائن النموذج المحدد.

```csharp
public void Visit(XForm xForm)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| xForm | XForm | كائن شكل PDF. |

### أنظر أيضا

* class [XForm](../../../aspose.pdf/xform)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* مساحة الاسم [Aspose.Pdf.Text](../../textfragmentabsorber)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->