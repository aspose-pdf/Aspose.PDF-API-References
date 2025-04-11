---
title: Class OBJRElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.OBJRElement class. يمثل كيان مرجع الكائن في الهيكل المنطقي
type: docs
weight: 6530
url: /ar/net/aspose.pdf.logicalstructure/objrelement/
---
## OBJRElement class

يمثل كيان مرجع الكائن في الهيكل المنطقي.

```csharp
public sealed class OBJRElement : Element
```

## Properties

| Name | Description |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | يحصل على مجموعة الأطفال من كائنات Element. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | يحصل على العنصر الأب. |

## Methods

| Name | Description |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | يضيف عنصر إلى مجموعة الأطفال. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | يمسح جميع الأطفال. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | يجد العناصر من نوع معين |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | يُدخل عنصرًا إلى مجموعة الأطفال في الفهرس المحدد. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | يزيل الطفل في. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag_2)(Annotation) | يربط عنصر الهيكل بالتعليق التوضيحي. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag)(Artifact) | يربط عنصر الهيكل بالأثر. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag_1)(BDC) | يربط عنصر الهيكل بمشغل محتوى BDC. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag_3)(XForm) | يربط عنصر الهيكل بمحتوى XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag_4)(XImage) | يربط عنصر الهيكل بـ XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/objrelement/tostring/)() | يُرجع سلسلة تمثل الكائن الحالي. |

### See Also

* class [Element](../element/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)