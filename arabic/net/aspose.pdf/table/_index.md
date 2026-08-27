---
title: "الفئة Table"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Table. تمثل جدولًا يمكن إضافته إلى الصفحة"
type: docs
weight: 10460
url: /ar/net/aspose.pdf/table/
---
## Table class

يمثل جدولًا يمكن إضافته إلى الصفحة.

```csharp
public sealed class Table : BaseParagraph
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Table](table/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment/) { get; set; } | الحصول أو تعيين محاذاة الجدول. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor/) { get; set; } | يحصل أو يضبط لون خلفية الجدول |
| [Border](../../aspose.pdf/table/border/) { get; set; } | يحصل أو يعيّن الحد. |
| [BreakText](../../aspose.pdf/table/breaktext/) { get; set; } | يحصل أو يضبط نص الفاصل للجدول |
| [Broken](../../aspose.pdf/table/broken/) { get; set; } | الحصول أو تعيين كسر عمودي للجدول؛ |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment/) { get; set; } | الحصول أو تعيين تعديل عمود الجدول. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths/) { get; set; } | الحصول على عرض أعمدة الجدول. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle/) { get; set; } | الحصول أو تعيين أنماط زوايا الحدود |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder/) { get; set; } | يحصل على حد الخلية الافتراضي؛ |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding/) { get; set; } | الحصول أو تعيين الحشو الافتراضي للخلية. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate/) { get; set; } | يحصل أو يحدد حالة نص الخلية الافتراضية. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth/) { get; set; } | يحصل على حد الخلية الافتراضي؛ |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | يحصل أو يعيّن محاذاة أفقية للفقرة |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | الحصول على أو تعيين ارتباط الفقرة (لمولد PDF). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded/) { get; set; } | الحصول أو تعيين تضمين الحد في عرض الأعمدة. |
| [IsBroken](../../aspose.pdf/table/isbroken/) { get; set; } | الحصول أو تعيين كسر الجدول - سيتم اقتطاعه للصفحة التالية. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كان هذا الفقرة سيظهر في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | الحصول على أو تعيين ما إذا كانت الفقرة مضمنة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | الحصول على أو تعيين قيمة bool تجبر هذه الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [Left](../../aspose.pdf/table/left/) { get; set; } | يحصل أو يعيّن إحداثي اليسار للجدول. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يعيّن هامشًا خارجيًا للفقرة (لإنشاء PDF) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount/) { get; set; } | يحصل أو يضبط الحد الأقصى لعدد الأعمدة للجدول |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount/) { get; set; } | يحصل على عدد الصفوف الأولى المتكررة لعدة صفحات |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle/) { get; set; } | يحصل على النمط للصفوف المتكررة |
| [Rows](../../aspose.pdf/table/rows/) { get; } | يحصل على صفوف الجدول. |
| [Top](../../aspose.pdf/table/top/) { get; set; } | يحصل أو يعيّن إحداثي أعلى الجدول. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يعيّن محاذاة عمودية للفقرة |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يعيّن قيمة عددية تشير إلى ترتيب Z للرسم البياني. الرسم البياني ذو ZIndex أكبر سيُوضع فوق الرسم البياني ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني ذو ZIndex سالب سيُوضع خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone/)() | استنساخ الجدول. |
| [GetHeight](../../aspose.pdf/table/getheight/)(Page) | احصل على الارتفاع. |
| [GetWidth](../../aspose.pdf/table/getwidth/)() | احصل على العرض. |
| [ImportArray](../../aspose.pdf/table/importarray/)(object[], int, int, bool) | يستورد مصفوفة أحادية البعد من البيانات إلى الجدول. يتم الاستيراد خلية واحدة لكل عنصر في المصفوفة ويبدأ من الصف والعمود المحددين في المعلمات. أثناء الاستيراد، إذا تم اكتشاف أن الصفوف اللازمة لا تزال غير موجودة (أي أن الجدول المستهدف صغير جدًا لاستيعاب جميع البيانات)، سيتم إنشاء الصفوف اللازمة. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_1)(DataTable, bool, int, int) | يستورد البيانات من System.Data.DataTable إلى Aspose.Pdf.Table |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable)(DataTable, bool, int, byte, int, int, bool) | يستورد كائن DataTable إلى الجدول. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | يستورد كائن DataTable، ولكن ليس ككيان كامل. يتم استيراد الصفوف والأعمدة المحددة فقط. |
| [ImportDataView](../../aspose.pdf/table/importdataview/)(DataView, bool, int, int, int, int) | يستورد بيانات كائن DataView إلى الجدول. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate/)(int, TextState) | اضبط الارتفاع. |

### انظر أيضًا

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


