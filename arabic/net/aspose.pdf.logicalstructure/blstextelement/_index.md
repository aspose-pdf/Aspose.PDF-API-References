---
title: "الفئة BLSTextElement"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.LogicalStructure.BLSTextElement الفئة. تمثل فئة أساسية لعناصر بنية النص على مستوى الكتلة في البنية المنطقية"
type: docs
weight: 6390
url: /ar/net/aspose.pdf.logicalstructure/blstextelement/
---
## BLSTextElement class

يمثل فئة أساسية لعناصر بنية النص على مستوى الكتلة في البنية المنطقية.

```csharp
public abstract class BLSTextElement : BLSElement, IAdjustPosition, ITextElement
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | يحصل أو يعيّن النص الفعلي لعنصر البنية. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | يحصل أو يعيّن النص البديل لعنصر البنية. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | يحصل على كائن StructureAttributeCollection. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | يحصل على مجموعة الأطفال لكائنات Element. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | يحصل على كائن AttributeOwnerStandard. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | يحصل أو يعيّن نص التوسيع لعنصر البنية. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | يحصل على المعرف لعنصر البنية. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | يحصل أو يعيّن اللغة لعنصر البنية. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | يحصل على الصفحة التي سيتم فيها عرض بعض أو كل العناصر الفرعية. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | احصل على العنصر الأب. |
| [StructureTextState](../../aspose.pdf.logicalstructure/blstextelement/structuretextstate/) { get; } | يحصل على كائن StructureTextState للعنصر الحالي. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | يحصل على نوع عنصر البنية. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | يحصل أو يعيّن العنوان لعنصر البنية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/blstextelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | إلحاق Element إلى مجموعة الأطفال. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | تغيير العنصر الأب لعنصر البنية الحالي |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | مسح جميع الأطفال. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | مسح المعرف لعنصر البنية. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | البحث عن Elements من نوع معين |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | إنشاء معرف لعنصر البنية. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | إدراج Element إلى مجموعة الأطفال في الفهرس المحدد. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | يزيل: عنصرًا من البنية، وإشارة إليه من الكائن الأب، وإشارات إليه من الكائنات الفرعية، والكائن المقابل من المستند. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | يزيل عنصرًا من البنية، وإشارة إليه من الكائن الأب، وإشارات إليه من الكائنات الفرعية، والكائن المقابل من المستند. يُدرج كائنات الأطفال للعنصر المُزال في مجموعة كائنات الأطفال السابقة للوالد بدءًا من فهرس العنصر المُزال. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | إزالة العنصر الفرعي عند. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | يحدد المعرف لعنصر البنية. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | يحدد علامة مخصصة لعنصر البنية. |
| [SetText](../../aspose.pdf.logicalstructure/blstextelement/settext/)(string) |  |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | ربط عنصر بنية بـ Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | ربط عنصر بنية بـ Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | ربط عنصر بنية بمشغل تدفق المحتوى BDC. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | ربط عنصر بنية بتدفق المحتوى XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | ربط عنصر بنية بـ XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | يرجع سلسلة تمثل الكائن الحالي. |

### انظر أيضًا

* class [BLSElement](../blselement/)
* interface [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* interface [ITextElement](../itextelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


