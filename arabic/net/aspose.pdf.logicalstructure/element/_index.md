---
title: "الفئة Element"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.LogicalStructure.Element. تمثل فئة أساسية للعنصر في البنية المنطقية"
type: docs
weight: 6460
url: /ar/net/aspose.pdf.logicalstructure/element/
---
## Element class

يمثل فئة أساسية للعنصر في البنية المنطقية.

```csharp
public abstract class Element
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | يحصل على مجموعة الأطفال لكائنات Element. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | احصل على العنصر الأب. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | إلحاق Element إلى مجموعة الأطفال. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | مسح جميع الأطفال. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | البحث عن Elements من نوع معين |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | إدراج Element إلى مجموعة الأطفال في الفهرس المحدد. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | إزالة العنصر الفرعي عند. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_2)(Annotation) | ربط عنصر بنية بـ Annotation. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag)(Artifact) | ربط عنصر بنية بـ Artifact. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_1)(BDC) | ربط عنصر بنية بمشغل تدفق المحتوى BDC. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_3)(XForm) | ربط عنصر بنية بتدفق المحتوى XForm. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_4)(XImage) | ربط عنصر بنية بـ XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | يرجع سلسلة تمثل الكائن الحالي. |

### انظر أيضًا

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


