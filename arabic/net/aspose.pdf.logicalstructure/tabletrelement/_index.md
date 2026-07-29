---
title: "الفئة TableTRElement"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.LogicalStructure.TableTRElement. تمثل عنصر بنية TR في البنية المنطقية للجدول"
type: docs
weight: 6990
url: /ar/net/aspose.pdf.logicalstructure/tabletrelement/
---
## TableTRElement class

يمثل عنصر بنية TR في الهيكل المنطقي للجدول.

```csharp
public sealed class TableTRElement : TableChildElement
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | يحصل أو يعيّن النص الفعلي لعنصر البنية. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | يحصل أو يعيّن النص البديل لعنصر البنية. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | يحصل على كائن StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tabletrelement/backgroundcolor/) { get; set; } | يحصل أو يعيّن لون خلفية الصف. |
| [Border](../../aspose.pdf.logicalstructure/tabletrelement/border/) { get; set; } | يحصل أو يعيّن حد الصف. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | يحصل على مجموعة الأطفال لكائنات Element. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | يحصل على كائن AttributeOwnerStandard. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellborder/) { get; set; } | الحصول على حد الخلية الافتراضي. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellpadding/) { get; set; } | يحصل أو يعيّن الهامش الافتراضي لخلايا الصف. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tabletrelement/defaultcelltextstate/) { get; set; } | يحصل أو يعيّن حالة النص الافتراضية لخلايا الصف |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | يحصل أو يعيّن نص التوسيع لعنصر البنية. |
| [FixedRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/fixedrowheight/) { get; set; } | يحصل على ارتفاع ثابت للصف - قد يكون للصف ارتفاع ثابت. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | يحصل على المعرف لعنصر البنية. |
| [IsInNewPage](../../aspose.pdf.logicalstructure/tabletrelement/isinnewpage/) { get; set; } | يحصل على ما إذا كان الصف الثابت في صفحة جديدة - يجب طباعة الصفحة التي تحتوي على هذه الخاصية إلى الصفحة التالية. القيمة الافتراضية false. |
| [IsRowBroken](../../aspose.pdf.logicalstructure/tabletrelement/isrowbroken/) { get; set; } | يحصل على ما إذا كان يمكن كسر الصف بين صفحتين. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | يحصل أو يعيّن اللغة لعنصر البنية. |
| [MinRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/minrowheight/) { get; set; } | يحصل على ارتفاع الصف. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | يحصل على الصفحة التي سيتم فيها عرض بعض أو كل العناصر الفرعية. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | احصل على العنصر الأب. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | يحصل على نوع عنصر البنية. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | يحصل أو يعيّن العنوان لعنصر البنية. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tabletrelement/verticalalignment/) { get; set; } | الحصول أو تعيين المحاذاة العمودية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | إلحاق Element إلى مجموعة الأطفال. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | تغيير العنصر الأب لعنصر البنية الحالي |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | مسح جميع الأطفال. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | مسح المعرف لعنصر البنية. |
| [CreateTD](../../aspose.pdf.logicalstructure/tabletrelement/createtd/)() | ينشئ [`TableTHElement`](../tablethelement/) ويضيفه إلى الجدول الحالي. |
| [CreateTH](../../aspose.pdf.logicalstructure/tabletrelement/createth/)() | ينشئ [`TableTHElement`](../tablethelement/) ويضيفه إلى الجدول الحالي. |
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

* class [TableChildElement](../tablechildelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


