---
title: "فئة MCRElement"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.LogicalStructure.MCRElement. تمثل كائن إشارة المحتوى المميز في البنية المنطقية"
type: docs
weight: 6640
url: /ar/net/aspose.pdf.logicalstructure/mcrelement/
---
## MCRElement class

يمثل كائن إشارة المحتوى المعلَّم في البنية المنطقية.

```csharp
public sealed class MCRElement : Element
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | يحصل على مجموعة الأطفال لكائنات Element. |
| [MCID](../../aspose.pdf.logicalstructure/mcrelement/mcid/) { get; } | يحصل على MCID لكائن إشارة المحتوى المميز. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | احصل على العنصر الأب. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | إلحاق Element إلى مجموعة الأطفال. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | مسح جميع الأطفال. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | البحث عن Elements من نوع معين |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | إدراج Element إلى مجموعة الأطفال في الفهرس المحدد. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | إزالة العنصر الفرعي عند. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_2)(Annotation) | ربط عنصر بنية بـ Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag)(Artifact) | ربط عنصر بنية بـ Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_1)(BDC) | ربط عنصر بنية بمشغل تدفق المحتوى BDC. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_3)(XForm) | ربط عنصر بنية بتدفق المحتوى XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_4)(XImage) | ربط عنصر بنية بـ XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/mcrelement/tostring/)() | يرجع سلسلة تمثل الكائن الحالي. |

### انظر أيضًا

* class [Element](../element/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


