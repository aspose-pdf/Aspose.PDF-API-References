---
title: "TableAbsorber.Visit"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة TableAbsorber. تستخرج الجداول في الصفحة المحددة"
type: docs
weight: 70
url: /ar/net/aspose.pdf.text/tableabsorber/visit/
---
## Visit(Page) {#visit_1}

يستخرج الجداول في الصفحة المحددة

```csharp
public virtual void Visit(Page page)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صفحة | صفحة | كائن صفحة مستند Pdf. |

## أمثلة

يوضح المثال كيفية استخراج جدول في الصفحة الأولى من مستند PDF.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TableAbsorber للعثور على الجداول
TableAbsorber absorber = new TableAbsorber();

// زيارة الصفحة الأولى باستخدام الماص
absorber.Visit(doc.Pages[1]);

// احصل على الوصول إلى أول جدول في الصفحة، وخليته الأولى ومقاطع النص الموجودة فيه
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// غيّر نص أول مقطع نصي في الخلية
fragment.Text = "hi world";

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [Page](../../../aspose.pdf/page/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

يستخرج الجداول في المستند المحدد.

```csharp
public void Visit(Document pdf)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| pdf | Document | كائن Pdf pocument. |

## أمثلة

يوضح المثال كيفية استخراج جدول في الصفحة الأولى من مستند PDF.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TableAbsorber للعثور على الجداول
TableAbsorber absorber = new TableAbsorber();

// زيارة الصفحة الأولى باستخدام الماص
absorber.Visit(doc);

// احصل على الوصول إلى أول جدول في الصفحة، وخليته الأولى ومقاطع النص الموجودة فيه
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// غيّر نص أول مقطع نصي في الخلية
fragment.Text = "hi world";

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [Document](../../../aspose.pdf/document/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


