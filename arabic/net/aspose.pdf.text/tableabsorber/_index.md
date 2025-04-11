---
title: Class TableAbsorber
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Text.TableAbsorber. تمثل كائن امتصاص لعناصر الجدول. تقوم بإجراء البحث وتوفر الوصول إلى نتائج البحث عبر مجموعة TableList
type: docs
weight: 10790
url: /ar/net/aspose.pdf.text/tableabsorber/
---
## Class TableAbsorber

تمثل كائن امتصاص لعناصر الجدول. تقوم بإجراء البحث وتوفر الوصول إلى نتائج البحث عبر مجموعة [`TableList`](./tablelist/) .

```csharp
public class TableAbsorber
```

## Constructors

| Name | Description |
| --- | --- |
| [TableAbsorber](tableabsorber/#constructor)() | يقوم بتهيئة مثيل جديد من `TableAbsorber`. |
| [TableAbsorber](tableabsorber/#constructor_1)(TextSearchOptions) | يقوم بتهيئة مثيل جديد من `TableAbsorber` مع خيارات بحث نصية. |

## Properties

| Name | Description |
| --- | --- |
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | يعيد IList للقراءة فقط تحتوي على الجداول التي تم العثور عليها |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | يحصل أو يحدد خيارات البحث النصية. |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * تمكين محرك التعرف على الجداول البديل الذي يتفوق في العديد من السيناريوهات وقادر على التعرف على الجداول بدون حدود. لا يدعم تحرير الجداول والحصول على أنماط النص حتى الآن. القيمة الافتراضية هي false؛ |

## Methods

| Name | Description |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | يزيل [`AbsorbedTable`](../absorbedtable/) من الصفحة. |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | يستبدل [`AbsorbedTable`](../absorbedtable/) بـ [`Table`](../../aspose.pdf/table/) على الصفحة. |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | يستخرج الجداول في المستند المحدد. |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | يستخرج الجداول في الصفحة المحددة |

## Examples

المثال يوضح كيفية العثور على جدول في الصفحة الأولى من مستند PDF واستبدال النص في خلية جدول.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(pdfDocument.Pages[1]);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)