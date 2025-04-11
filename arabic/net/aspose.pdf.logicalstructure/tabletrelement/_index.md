---
title: Class TableTRElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.TableTRElement class. يمثل عنصر هيكل TR في الهيكل المنطقي للجدول
type: docs
weight: 6850
url: /ar/net/aspose.pdf.logicalstructure/tabletrelement/
---
## TableTRElement class

يمثل عنصر هيكل TR في الهيكل المنطقي للجدول.

```csharp
public sealed class TableTRElement : TableChildElement
```

## Properties

| Name | Description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | يحصل أو يحدد النص الفعلي لعنصر الهيكل. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | يحصل أو يحدد النص البديل لعنصر الهيكل. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | يحصل على كائن StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tabletrelement/backgroundcolor/) { get; set; } | يحصل أو يحدد لون خلفية الصف. |
| [Border](../../aspose.pdf.logicalstructure/tabletrelement/border/) { get; set; } | يحصل أو يحدد حدود الصف. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | يحصل على مجموعة الأطفال من كائنات Element. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | يحصل على كائن AttributeOwnerStandard. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellborder/) { get; set; } | يحصل على حدود الخلية الافتراضية. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellpadding/) { get; set; } | يحصل أو يحدد الهامش الافتراضي لخلايا الصف. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tabletrelement/defaultcelltextstate/) { get; set; } | يحصل أو يحدد حالة النص الافتراضية لخلايا الصف |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | يحصل أو يحدد نص التوسع لعنصر الهيكل. |
| [FixedRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/fixedrowheight/) { get; set; } | يحصل على ارتفاع الصف الثابت - قد يكون للصف ارتفاع ثابت. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | يحصل على المعرف لعنصر الهيكل. |
| [IsInNewPage](../../aspose.pdf.logicalstructure/tabletrelement/isinnewpage/) { get; set; } | يحصل على الصف الثابت في صفحة جديدة - يجب طباعة الصفحة التي تحتوي على هذه الخاصية إلى الصفحة التالية. الافتراضي هو خطأ. |
| [IsRowBroken](../../aspose.pdf.logicalstructure/tabletrelement/isrowbroken/) { get; set; } | يحصل على ما إذا كان يمكن كسر الصف بين صفحتين. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | يحصل أو يحدد اللغة لعنصر الهيكل. |
| [MinRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/minrowheight/) { get; set; } | يحصل على ارتفاع الصف. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | يحصل على الصفحة التي سيتم عرض بعض أو كل عناصر الأطفال عليها. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | يحصل على العنصر الأب. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | يحصل على نوع عنصر الهيكل. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | يحصل أو يحدد العنوان لعنصر الهيكل. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tabletrelement/verticalalignment/) { get; set; } | يحصل أو يحدد المحاذاة الرأسية. |

## Methods

| Name | Description |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | إضافة عنصر إلى مجموعة الأطفال. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | تغيير العنصر الأب لعنصر الهيكل الحالي |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | مسح جميع الأطفال. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | مسح المعرف لعنصر الهيكل. |
| [CreateTD](../../aspose.pdf.logicalstructure/tabletrelement/createtd/)() | ينشئ [`TableTHElement`](../tablethelement/) ويضيفه إلى الجدول الحالي. |
| [CreateTH](../../aspose.pdf.logicalstructure/tabletrelement/createth/)() | ينشئ [`TableTHElement`](../tablethelement/) ويضيفه إلى الجدول الحالي. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | العثور على عناصر من نوع معين |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | توليد معرف لعنصر الهيكل. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | إدراج عنصر في مجموعة الأطفال عند الفهرس المحدد. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | يزيل: عنصر من الهيكل، مرجع له من الكائن الأب، مراجع له من الكائنات الفرعية، الكائن المقابل من الوثيقة. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | يزيل عنصرًا من الهيكل، مرجع له من الكائن الأب، مراجع له من الكائنات الفرعية، والكائن المقابل من الوثيقة. يقوم بإدراج كائنات الأطفال للعنصر الذي تمت إزالته في مجموعة كائنات الأطفال الخاصة بالأب السابق بدءًا من فهرس العنصر الذي تمت إزالته. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | إزالة الطفل عند. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | تعيين المعرف لعنصر الهيكل. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | تعيين علامة مخصصة لعنصر الهيكل. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | ربط عنصر الهيكل بالتعليق. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | ربط عنصر الهيكل بالأثر. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | ربط عنصر الهيكل بمشغل BDC في تدفق المحتوى. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | ربط عنصر الهيكل بتدفق المحتوى XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | ربط عنصر الهيكل بالصورة XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | يعيد سلسلة تمثل الكائن الحالي. |

### See Also

* class [TableChildElement](../tablechildelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)