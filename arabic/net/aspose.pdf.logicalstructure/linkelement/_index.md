---
title: Class LinkElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.LinkElement class. يمثل عنصر هيكل الرابط في الهيكل المنطقي
type: docs
weight: 6440
url: /ar/net/aspose.pdf.logicalstructure/linkelement/
---
## LinkElement class

يمثل عنصر هيكل الرابط في الهيكل المنطقي.

```csharp
public sealed class LinkElement : AnnotationElement, IAdjustPosition, ITextElement
```

## Properties

| Name | Description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | يحصل على أو يحدد النص الفعلي لعنصر الهيكل. |
| [AlternateDescriptions](../../aspose.pdf.logicalstructure/annotationelement/alternatedescriptions/) { get; set; } | يحصل على أو يحدد الأوصاف البديلة للتعليق. النص الذي يجب عرضه للتعليق أو، إذا لم يعرض هذا النوع من التعليق نصًا، وصف بديل لمحتويات التعليق بشكل قابل للقراءة البشرية. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | يحصل على أو يحدد النص البديل لعنصر الهيكل. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | يحصل على كائن StructureAttributeCollection. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | يحصل على مجموعة الأطفال من كائنات العنصر. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | يحصل على كائن AttributeOwnerStandard. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | يحصل على أو يحدد نص التوسع لعنصر الهيكل. |
| [Hyperlink](../../aspose.pdf.logicalstructure/linkelement/hyperlink/) { get; set; } | يحصل على أو يحدد الارتباط التشعبي لعنصر الرابط. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | يحصل على المعرف لعنصر الهيكل. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | يحصل على أو يحدد اللغة لعنصر الهيكل. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | يحصل على الصفحة التي سيتم عرض بعض أو كل عناصر الأطفال عليها. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | يحصل على العنصر الأب. |
| [StructureTextState](../../aspose.pdf.logicalstructure/linkelement/structuretextstate/) { get; } | يحصل على كائن StructureTextState للعنصر الحالي. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | يحصل على نوع عنصر الهيكل. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | يحصل على أو يحدد العنوان لعنصر الهيكل. |

## Methods

| Name | Description |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/linkelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | إضافة عنصر إلى مجموعة الأطفال. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | تغيير العنصر الأب لعنصر الهيكل الحالي |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | مسح جميع الأطفال. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | مسح المعرف لعنصر الهيكل. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | العثور على عناصر من نوع معين |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | توليد معرف لعنصر الهيكل. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | إدراج عنصر في مجموعة الأطفال عند الفهرس المحدد. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | يزيل: عنصرًا من الهيكل، مرجعًا له من الكائن الأب، مراجع له من كائنات الأطفال، الكائن المقابل من الوثيقة. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | يزيل عنصرًا من الهيكل، مرجعًا له من الكائن الأب، مراجع له من كائنات الأطفال، والكائن المقابل من الوثيقة. يقوم بإدراج كائنات الأطفال للعنصر الذي تمت إزالته في مجموعة كائنات الأطفال الخاصة بالأب السابق بدءًا من فهرس العنصر الذي تمت إزالته. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | إزالة الطفل عند. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | تعيين المعرف لعنصر الهيكل. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | تعيين علامة مخصصة لعنصر الهيكل. |
| [SetText](../../aspose.pdf.logicalstructure/linkelement/settext/)(string) |  |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | ربط عنصر الهيكل بالتعليق. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | ربط عنصر الهيكل بالأثر. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | ربط عنصر الهيكل بمشغل BDC لتدفق المحتوى. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | ربط عنصر الهيكل بمشغل XForm لتدفق المحتوى. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | ربط عنصر الهيكل بصورة X. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | يعيد سلسلة تمثل الكائن الحالي. |

### See Also

* class [AnnotationElement](../annotationelement/)
* interface [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* interface [ITextElement](../itextelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)