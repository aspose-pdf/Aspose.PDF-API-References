---
title: Class MCRElement
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.LogicalStructure.MCRElement. تمثل كائن مرجع المحتوى المعلم في الهيكل المنطقي
type: docs
weight: 6500
url: /ar/net/aspose.pdf.logicalstructure/mcrelement/
---
## MCRElement class

تمثل كائن مرجع المحتوى المعلم في الهيكل المنطقي.

```csharp
public sealed class MCRElement : Element
```

## Properties

| Name | Description |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | يحصل على مجموعة الأطفال من كائنات Element. |
| [MCID](../../aspose.pdf.logicalstructure/mcrelement/mcid/) { get; } | يحصل على MCID لكائن مرجع المحتوى المعلم. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | يحصل على العنصر الأب. |

## Methods

| Name | Description |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | إضافة عنصر إلى مجموعة الأطفال. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | مسح جميع الأطفال. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | العثور على العناصر من نوع معين |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | إدراج عنصر في مجموعة الأطفال عند الفهرس المحدد. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | إزالة الطفل عند. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_2)(Annotation) | ربط عنصر الهيكل بالتعليق. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag)(Artifact) | ربط عنصر الهيكل بالأثر. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_1)(BDC) | ربط عنصر الهيكل بمشغل محتوى BDC. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_3)(XForm) | ربط عنصر الهيكل بمحتوى XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_4)(XImage) | ربط عنصر الهيكل بـ XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/mcrelement/tostring/)() | يعيد سلسلة تمثل الكائن الحالي. |

### See Also

* class [Element](../element/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)