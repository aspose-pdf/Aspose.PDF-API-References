---
title: "الفئة TableAbsorber"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Text.TableAbsorber. تمثل كائن ماص لعناصر الجدول. يقوم بالبحث ويوفر الوصول إلى نتائج البحث عبر مجموعة TableList"
type: docs
weight: 10970
url: /ar/net/aspose.pdf.text/tableabsorber/
---
## TableAbsorber class

يمثل كائن ماص لعناصر الجدول. يقوم بالبحث ويوفر الوصول إلى نتائج البحث عبر مجموعة [`TableList`](./tablelist/).

```csharp
public class TableAbsorber
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TableAbsorber](tableabsorber/#constructor)() | يُنشئ مثيلاً جديدًا من `TableAbsorber`. |
| [TableAbsorber](tableabsorber/#constructor_1)(TextSearchOptions) | يُنشئ مثيلاً جديدًا من `TableAbsorber` مع خيارات البحث النصي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | يرجع IList للقراءة فقط يحتوي على الجداول التي تم العثور عليها |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | يحصل أو يعيّن خيارات بحث النص. |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * تمكين محرك التعرف على الجداول البديل الذي يتفوق في العديد من السيناريوهات ويستطيع التعرف على الجداول بدون حدود. لا يدعم تحرير الجداول أو الحصول على أنماط النص حتى الآن. القيمة الافتراضية هي false; |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | يزيل [`AbsorbedTable`](../absorbedtable/) من الصفحة. |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | يستبدل [`AbsorbedTable`](../absorbedtable/) بـ [`Table`](../../aspose.pdf/table/) على الصفحة. |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | يستخرج الجداول في المستند المحدد. |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | يستخرج الجداول في الصفحة المحددة |

## أمثلة

يوضح المثال كيفية العثور على جدول في الصفحة الأولى من مستند PDF واستبدال النص داخل خلية الجدول.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TableAbsorber للعثور على الجداول
TableAbsorber absorber = new TableAbsorber();

// زيارة الصفحة الأولى باستخدام الماص
absorber.Visit(pdfDocument.Pages[1]);

// احصل على الوصول إلى أول جدول في الصفحة، وخليته الأولى ومقاطع النص الموجودة فيه
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// غيّر نص أول مقطع نصي في الخلية
fragment.Text = "hi world";

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


