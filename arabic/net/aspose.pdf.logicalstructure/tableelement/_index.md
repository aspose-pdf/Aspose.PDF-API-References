---
title: TableElement
second_title: Aspose.PDF لمرجع .NET API
description: يمثل عنصر بنية الجدول في الهيكل المنطقي.
type: docs
weight: 4610
url: /ar/net/aspose.pdf.logicalstructure/tableelement/
---
## TableElement class

يمثل عنصر بنية الجدول في الهيكل المنطقي.

```csharp
public sealed class TableElement : BLSElement
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext) { get; set; } | الحصول على أو تحديد النص الفعلي لعنصر البنية. |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment) { get; set; } | الحصول على محاذاة الجدول أو تعيينها. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext) { get; set; } | الحصول على أو تعيين النص البديل لعنصر البنية. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes) { get; } | يحصلStructureAttributeCollection الكائن . |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor) { get; set; } | الحصول على أو تعيين لون خلفية الجدول. |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border) { get; set; } | الحصول على حد الجدول أو تعيينه . |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken) { get; set; } | الحصول على أو ضبط الجدول العمودي المكسور |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements) { get; } | يحصل على جمع الأطفال منElement الكائنات . |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment) { get; set; } | الحصول على أو ضبط تعديل عمود الجدول. |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths) { get; set; } | الحصول على عرض أعمدة الجدول. |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle) { get; set; } | الحصول على أو تعيين أنماط زوايا الحدود |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner) { get; } | يحصلAttributeOwnerStandard الكائن . |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder) { get; set; } | يحصل على حد الخلية الافتراضي . |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding) { get; set; } | الحصول على أو تعيين مساحة الخلية الافتراضية. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate) { get; set; } | الحصول على حالة نص الخلية الافتراضية أو تعيينها. |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth) { get; set; } | الحصول على عرض العمود الافتراضي أو تعيينه. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext) { get; set; } | الحصول على أو تعيين نص التوسيع لعنصر البنية. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id) { get; } | يحصل على معرف عنصر الهيكل . |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded) { get; set; } | الحصول على أو تعيين الحدود المضمنة في عروض الأعمدة. |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken) { get; set; } | الحصول على الجدول مكسورًا أو تعيينه - سيتم اقتطاعه للصفحة التالية. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language) { get; set; } | الحصول على أو تعيين لغة عنصر البنية. |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left) { get; set; } | الحصول على أو تحديد إحداثيات يسار الجدول . |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement) { get; } | احصل على العنصر الأصل . |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount) { get; set; } | الحصول على أو تعيين الحد الأقصى لعدد الأعمدة للجدول . |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount) { get; set; } | الحصول على عدد الصفوف الأولى المتكرر لعدة صفحات. |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle) { get; set; } | يحصل على نمط تكرار الصفوف. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype) { get; } | يحصل على نوع عنصر الهيكل . |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title) { get; set; } | الحصول على أو تحديد عنوان عنصر البنية. |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top) { get; set; } | الحصول على أو تحديد إحداثيات أعلى الجدول . |

## طُرق

| اسم | وصف |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild)(Element) | إلحاقElement لجمع الأطفال. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement)(StructureElement) | تغيير العنصر الأصل لعنصر الهيكل الحالي |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid)() | معرف واضح لعنصر الهيكل . |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody)() | يخلق[`TableTHeadElement`](../tabletheadelement) وإضافته إلى الجدول الحالي. |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot)() | يخلق[`TableTFootElement`](../tabletfootelement) وإضافته إلى الجدول الحالي. |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead)() | يخلق[`TableTHeadElement`](../tabletheadelement) وإضافته إلى الجدول الحالي. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements)(bool) | البحث عن عناصر من نوع معين |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid)() | إنشاء معرف لعنصر الهيكل . |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid)(string) | يعين معرف عنصر الهيكل. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag)(string) | تعيين علامة مخصصة لعنصر الهيكل. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring)() | إرجاع سلسلة تمثل الكائن الحالي. |

### أنظر أيضا

* class [BLSElement](../blselement)
* مساحة الاسم [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
