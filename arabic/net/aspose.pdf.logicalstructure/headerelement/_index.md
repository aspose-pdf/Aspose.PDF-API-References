---
title: Class HeaderElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.HeaderElement class. يمثل عنصر هيكل الرأس في الهيكل المنطقي
type: docs
weight: 6380
url: /ar/net/aspose.pdf.logicalstructure/headerelement/
---
## HeaderElement class

يمثل عنصر هيكل الرأس في الهيكل المنطقي.

```csharp
public sealed class HeaderElement : BLSTextElement
```

## Properties

| Name | Description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | يحصل أو يحدد النص الفعلي لعنصر الهيكل. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | يحصل أو يحدد النص البديل لعنصر الهيكل. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | يحصل على كائن StructureAttributeCollection. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | يحصل على مجموعة الأطفال من كائنات العنصر. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | يحصل على كائن AttributeOwnerStandard. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | يحصل أو يحدد نص التوسع لعنصر الهيكل. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | يحصل على المعرف لعنصر الهيكل. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | يحصل أو يحدد اللغة لعنصر الهيكل. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | يحصل على الصفحة التي سيتم عرض بعض أو كل العناصر الفرعية عليها. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | يحصل على العنصر الأب. |
| [StructureTextState](../../aspose.pdf.logicalstructure/blstextelement/structuretextstate/) { get; } | يحصل على كائن StructureTextState للعنصر الحالي. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | يحصل على نوع عنصر الهيكل. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | يحصل أو يحدد العنوان لعنصر الهيكل. |

## Methods

| Name | Description |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/blstextelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | إضافة عنصر إلى مجموعة الأطفال. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | تغيير العنصر الأب لعنصر الهيكل الحالي |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | مسح جميع الأطفال. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | مسح المعرف لعنصر الهيكل. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | العثور على عناصر من نوع معين |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | إنشاء معرف لعنصر الهيكل. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | إدراج عنصر في مجموعة الأطفال عند الفهرس المحدد. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | يزيل: عنصر من الهيكل، مرجع له من الكائن الأب، مراجع له من الكائنات الفرعية، الكائن المقابل من الوثيقة. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | يزيل عنصرًا من الهيكل، مرجع له من الكائن الأب، مراجع له من الكائنات الفرعية، والكائن المقابل من الوثيقة. يقوم بإدراج كائنات الأطفال للعنصر الذي تمت إزالته في مجموعة كائنات الأطفال السابقة للأب بدءًا من فهرس العنصر الذي تمت إزالته. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | إزالة الطفل عند. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | تعيين المعرف لعنصر الهيكل. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | تعيين علامة مخصصة لعنصر الهيكل. |
| [SetText](../../aspose.pdf.logicalstructure/blstextelement/settext/)(string) |  |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | ربط عنصر الهيكل بالتعليق. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | ربط عنصر الهيكل بالأثر. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | ربط عنصر الهيكل بمشغل BDC في تدفق المحتوى. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | ربط عنصر الهيكل بتدفق المحتوى XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | ربط عنصر الهيكل بالصورة XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | يعيد سلسلة تمثل الكائن الحالي. |

### See Also

* class [BLSTextElement](../blstextelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)