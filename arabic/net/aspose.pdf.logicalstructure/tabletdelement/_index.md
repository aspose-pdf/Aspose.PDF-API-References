---
title: Class TableTDElement
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.LogicalStructure.TableTDElement. تمثل عنصر هيكلي TD في الهيكل المنطقي للجدول
type: docs
weight: 6810
url: /ar/net/aspose.pdf.logicalstructure/tabletdelement/
---
## TableTDElement class

تمثل عنصر هيكلي TD في الهيكل المنطقي للجدول.

```csharp
public sealed class TableTDElement : TableCellElement
```

## Properties

| Name | Description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | يحصل أو يحدد النص الفعلي لعنصر الهيكل. |
| [Alignment](../../aspose.pdf.logicalstructure/tablecellelement/alignment/) { get; set; } | يحصل أو يحدد محاذاة الخلية. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | يحصل أو يحدد النص البديل لعنصر الهيكل. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | يحصل على كائن StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tablecellelement/backgroundcolor/) { get; set; } | يحصل أو يحدد لون خلفية الخلية. |
| [Border](../../aspose.pdf.logicalstructure/tablecellelement/border/) { get; set; } | يحصل أو يحدد حدود الخلية. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | يحصل على مجموعة الأطفال من كائنات Element. |
| [ColSpan](../../aspose.pdf.logicalstructure/tablecellelement/colspan/) { get; set; } | يحصل أو يحدد مدى العمود. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | يحصل على كائن AttributeOwnerStandard. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tablecellelement/defaultcelltextstate/) { get; set; } | يحصل أو يحدد حالة نص الخلية الافتراضية. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | يحصل أو يحدد نص التوسع لعنصر الهيكل. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | يحصل على المعرف لعنصر الهيكل. |
| [IsNoBorder](../../aspose.pdf.logicalstructure/tablecellelement/isnoborder/) { get; set; } | يحصل أو يحدد ما إذا كانت الخلية تحتوي على حدود. |
| [IsWordWrapped](../../aspose.pdf.logicalstructure/tablecellelement/iswordwrapped/) { get; set; } | يحصل أو يحدد ما إذا كان نص الخلية ملفوفًا. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | يحصل أو يحدد اللغة لعنصر الهيكل. |
| [Margin](../../aspose.pdf.logicalstructure/tablecellelement/margin/) { get; set; } | يحصل أو يحدد الحشو. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | يحصل على الصفحة التي سيتم عرض بعض أو كل عناصر الأطفال عليها. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | يحصل على العنصر الأب. |
| [RowSpan](../../aspose.pdf.logicalstructure/tablecellelement/rowspan/) { get; set; } | يحصل أو يحدد مدى الصف. |
| [StructureTextState](../../aspose.pdf.logicalstructure/tablecellelement/structuretextstate/) { get; } | يحصل على كائن StructureTextState للعنصر الحالي. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | يحصل على نوع عنصر الهيكل. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | يحصل أو يحدد العنوان لعنصر الهيكل. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tablecellelement/verticalalignment/) { get; set; } | يحصل أو يحدد المحاذاة الرأسية. |

## Methods

| Name | Description |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tablecellelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | إضافة عنصر إلى مجموعة الأطفال. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | تغيير العنصر الأب لعنصر الهيكل الحالي |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | مسح جميع الأطفال. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | مسح المعرف لعنصر الهيكل. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | العثور على عناصر من نوع معين |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | توليد معرف لعنصر الهيكل. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | إدراج عنصر في مجموعة الأطفال عند الفهرس المحدد. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | يزيل: عنصر من الهيكل، مرجع له من الكائن الأب، مراجع له من الكائنات الفرعية، الكائن المقابل من الوثيقة. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | يزيل عنصرًا من الهيكل، مرجع له من الكائن الأب، مراجع له من الكائنات الفرعية، والكائن المقابل من الوثيقة. يقوم بإدراج كائنات الأطفال للعنصر المحذوف في مجموعة كائنات الأطفال الخاصة بالأب السابق بدءًا من فهرس العنصر المحذوف. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | إزالة الطفل عند. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | تعيين المعرف لعنصر الهيكل. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | تعيين علامة مخصصة لعنصر الهيكل. |
| [SetText](../../aspose.pdf.logicalstructure/tablecellelement/settext/)(string) |  |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | ربط عنصر هيكلي بالتعليق. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | ربط عنصر هيكلي بالأثر. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | ربط عنصر هيكلي بمشغل BDC في تدفق المحتوى. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | ربط عنصر هيكلي بتدفق المحتوى XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | ربط عنصر هيكلي بصورة X. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | يعيد سلسلة تمثل الكائن الحالي. |

### See Also

* class [TableCellElement](../tablecellelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)