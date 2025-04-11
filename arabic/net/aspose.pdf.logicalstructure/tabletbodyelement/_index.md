---
title: Class TableTBodyElement
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.LogicalStructure.TableTBodyElement. تمثل عنصر هيكل TBody في الهيكل المنطقي للجدول
type: docs
weight: 6800
url: /ar/net/aspose.pdf.logicalstructure/tabletbodyelement/
---
## Class TableTBodyElement

تمثل عنصر هيكل TBody في الهيكل المنطقي للجدول.

```csharp
public sealed class TableTBodyElement : TableRowCollectionElement
```

## Properties

| Name | Description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | يحصل أو يحدد النص الفعلي لعنصر الهيكل. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | يحصل أو يحدد النص البديل لعنصر الهيكل. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | يحصل على كائن StructureAttributeCollection. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | يحصل على مجموعة الأطفال من كائنات Element. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | يحصل على كائن AttributeOwnerStandard. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | يحصل أو يحدد نص التوسع لعنصر الهيكل. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | يحصل على المعرف لعنصر الهيكل. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | يحصل أو يحدد اللغة لعنصر الهيكل. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | يحصل على الصفحة التي سيتم عرض بعض أو كل العناصر الفرعية عليها. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | يحصل على العنصر الأب. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | يحصل على نوع عنصر الهيكل. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | يحصل أو يحدد العنوان لعنصر الهيكل. |

## Methods

| Name | Description |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | يضيف عنصر إلى مجموعة الأطفال. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | يغير العنصر الأب لعنصر الهيكل الحالي |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | يمسح جميع الأطفال. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | يمسح المعرف لعنصر الهيكل. |
| virtual [CreateTR](../../aspose.pdf.logicalstructure/tablerowcollectionelement/createtr/)() | ينشئ [`TableTRElement`](../tabletrelement/) ويضيفه إلى الجدول الحالي. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | يجد العناصر من نوع معين |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | يولد معرفًا لعنصر الهيكل. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | يُدخل عنصرًا إلى مجموعة الأطفال عند الفهرس المحدد. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | يزيل: عنصرًا من الهيكل، مرجعًا له من الكائن الأب، مراجع له من الكائنات الفرعية، الكائن المقابل من الوثيقة. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | يزيل عنصرًا من الهيكل، مرجعًا له من الكائن الأب، مراجع له من الكائنات الفرعية، والكائن المقابل من الوثيقة. يُدخل الكائنات الفرعية للعنصر المزال إلى مجموعة كائنات الأطفال الخاصة بالأب السابق بدءًا من فهرس العنصر المزال. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | يزيل الطفل عند. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | يحدد المعرف لعنصر الهيكل. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | يحدد علامة مخصصة لعنصر الهيكل. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | يربط عنصر الهيكل بالتعليق. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | يربط عنصر الهيكل بالأثر. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | يربط عنصر الهيكل بمشغل BDC في تدفق المحتوى. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | يربط عنصر الهيكل بتدفق المحتوى XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | يربط عنصر الهيكل بالصورة XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | يُرجع سلسلة تمثل الكائن الحالي. |

### See Also

* class [TableRowCollectionElement](../tablerowcollectionelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)