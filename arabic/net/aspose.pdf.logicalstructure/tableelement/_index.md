---
title: "فئة TableElement"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.LogicalStructure.TableElement. تمثّل عنصر بنية Table في الهيكل المنطقي"
type: docs
weight: 6920
url: /ar/net/aspose.pdf.logicalstructure/tableelement/
---
## TableElement class

يمثل عنصر بنية Table في الهيكل المنطقي.

```csharp
public sealed class TableElement : BLSElement, IAdjustPosition
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | يحصل أو يعيّن النص الفعلي لعنصر البنية. |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment/) { get; set; } | الحصول أو تعيين محاذاة الجدول. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | يحصل أو يعيّن النص البديل لعنصر البنية. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | يحصل على كائن StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor/) { get; set; } | الحصول أو تعيين لون خلفية الجدول. |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border/) { get; set; } | الحصول أو تعيين حد الجدول. |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken/) { get; set; } | الحصول أو تعيين كسر عمودي للجدول؛ |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | يحصل على مجموعة الأطفال لكائنات Element. |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment/) { get; set; } | الحصول أو تعيين تعديل عمود الجدول. |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths/) { get; set; } | الحصول على عرض أعمدة الجدول. |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle/) { get; set; } | الحصول أو تعيين أنماط زوايا الحدود |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | يحصل على كائن AttributeOwnerStandard. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder/) { get; set; } | الحصول على حد الخلية الافتراضي. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding/) { get; set; } | الحصول أو تعيين الحشو الافتراضي للخلية. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate/) { get; set; } | يحصل أو يحدد حالة نص الخلية الافتراضية. |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth/) { get; set; } | الحصول أو تعيين عرض العمود الافتراضي. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | يحصل أو يعيّن نص التوسيع لعنصر البنية. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | يحصل على المعرف لعنصر البنية. |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded/) { get; set; } | الحصول أو تعيين تضمين الحد في عرض الأعمدة. |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken/) { get; set; } | الحصول أو تعيين كسر الجدول - سيتم اقتطاعه للصفحة التالية. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | يحصل أو يعيّن اللغة لعنصر البنية. |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left/) { get; set; } | يحصل أو يعيّن إحداثي اليسار للجدول. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | يحصل على الصفحة التي سيتم فيها عرض بعض أو كل العناصر الفرعية. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | احصل على العنصر الأب. |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount/) { get; set; } | الحصول أو تعيين الحد الأقصى لعدد الأعمدة للجدول. |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount/) { get; set; } | الحصول على عدد الصفوف الأولى المتكررة لعدة صفحات. |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle/) { get; set; } | الحصول على النمط للصفوف المتكررة. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | يحصل على نوع عنصر البنية. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | يحصل أو يعيّن العنوان لعنصر البنية. |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top/) { get; set; } | يحصل أو يعيّن إحداثي أعلى الجدول. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tableelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | إلحاق Element إلى مجموعة الأطفال. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | تغيير العنصر الأب لعنصر البنية الحالي |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | مسح جميع الأطفال. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | مسح المعرف لعنصر البنية. |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody/)() | ينشئ [`TableTHeadElement`](../tabletheadelement/) ويضيفه إلى الجدول الحالي. |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot/)() | ينشئ [`TableTFootElement`](../tabletfootelement/) ويضيفه إلى الجدول الحالي. |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead/)() | ينشئ [`TableTHeadElement`](../tabletheadelement/) ويضيفه إلى الجدول الحالي. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | البحث عن Elements من نوع معين |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | إنشاء معرف لعنصر البنية. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | إدراج Element إلى مجموعة الأطفال في الفهرس المحدد. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | يزيل: عنصرًا من البنية، وإشارة إليه من الكائن الأب، وإشارات إليه من الكائنات الفرعية، والكائن المقابل من المستند. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | يزيل عنصرًا من البنية، وإشارة إليه من الكائن الأب، وإشارات إليه من الكائنات الفرعية، والكائن المقابل من المستند. يُدرج كائنات الأطفال للعنصر المُزال في مجموعة كائنات الأطفال السابقة للوالد بدءًا من فهرس العنصر المُزال. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | إزالة العنصر الفرعي عند. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | يحدد المعرف لعنصر البنية. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | يحدد علامة مخصصة لعنصر البنية. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | ربط عنصر بنية بـ Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | ربط عنصر بنية بـ Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | ربط عنصر بنية بمشغل تدفق المحتوى BDC. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | ربط عنصر بنية بتدفق المحتوى XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | ربط عنصر بنية بـ XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | يرجع سلسلة تمثل الكائن الحالي. |

### انظر أيضًا

* class [BLSElement](../blselement/)
* interface [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


