---
title: ILSTextElement
second_title: Aspose.PDF لمرجع .NET API
description: يمثل فئة أساسية لعناصر بنية النص المضمنة في البنية المنطقية.
type: docs
weight: 4230
url: /ar/net/aspose.pdf.logicalstructure/ilstextelement/
---
## ILSTextElement class

يمثل فئة أساسية لعناصر بنية النص المضمنة في البنية المنطقية.

```csharp
public abstract class ILSTextElement : ILSElement, ITextElement
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext) { get; set; } | الحصول على أو تحديد النص الفعلي لعنصر البنية. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext) { get; set; } | الحصول على أو تعيين النص البديل لعنصر البنية. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes) { get; } | يحصلStructureAttributeCollection الكائن . |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements) { get; } | يحصل على جمع الأطفال منElement الكائنات . |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner) { get; } | يحصلAttributeOwnerStandard الكائن . |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext) { get; set; } | الحصول على أو تعيين نص التوسيع لعنصر البنية. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id) { get; } | يحصل على معرف عنصر الهيكل . |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language) { get; set; } | الحصول على أو تعيين لغة عنصر البنية. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement) { get; } | احصل على العنصر الأصل . |
| [StructureTextState](../../aspose.pdf.logicalstructure/ilstextelement/structuretextstate) { get; } | يحصلStructureTextState كائن للعنصر الحالي. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype) { get; } | يحصل على نوع عنصر الهيكل . |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title) { get; set; } | الحصول على أو تحديد عنوان عنصر البنية. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild)(Element) | إلحاقElement لجمع الأطفال. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement)(StructureElement) | تغيير العنصر الأصل لعنصر الهيكل الحالي |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid)() | معرف واضح لعنصر الهيكل . |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements)(bool) | البحث عن عناصر من نوع معين |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid)() | إنشاء معرف لعنصر الهيكل . |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid)(string) | يعين معرف عنصر الهيكل. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag)(string) | تعيين علامة مخصصة لعنصر الهيكل. |
| [SetText](../../aspose.pdf.logicalstructure/ilstextelement/settext)(string) | إلحاق محتوى نصي بعنصر النص الحالي. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring)() | إرجاع سلسلة تمثل الكائن الحالي. |

### أنظر أيضا

* class [ILSElement](../ilselement)
* interface [ITextElement](../itextelement)
* مساحة الاسم [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->