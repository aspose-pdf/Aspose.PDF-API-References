---
title: Class Element
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.LogicalStructure.Element. تمثل فئة أساسية للعنصر في الهيكل المنطقي
type: docs
weight: 6320
url: /ar/net/aspose.pdf.logicalstructure/element/
---
## فئة العنصر

تمثل فئة أساسية للعنصر في الهيكل المنطقي.

```csharp
public abstract class Element
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | يحصل على مجموعة الأطفال من كائنات العنصر. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | يحصل على العنصر الأب. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | يضيف عنصر إلى مجموعة الأطفال. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | يمسح جميع الأطفال. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | يجد العناصر من نوع معين |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | يُدخل عنصرًا إلى مجموعة الأطفال في الفهرس المحدد. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | يزيل الطفل في. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_2)(Annotation) | يربط عنصر الهيكل بالتعليق. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag)(Artifact) | يربط عنصر الهيكل بالأثر. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_1)(BDC) | يربط عنصر الهيكل بمشغل محتوى BDC. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_3)(XForm) | يربط عنصر الهيكل بمحتوى XForm. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_4)(XImage) | يربط عنصر الهيكل بصورة X. |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | يُرجع سلسلة تمثل الكائن الحالي. |

### انظر أيضًا

* مساحة الاسم [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* التجميع [Aspose.PDF](../../)