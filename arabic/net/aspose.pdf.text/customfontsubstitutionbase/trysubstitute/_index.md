---
title: CustomFontSubstitutionBase.TrySubstitute
second_title: Aspose.PDF for .NET API Reference
description: طريقة استبدال الخط المخصص. تستبدل الخط الأصلي بخط آخر
type: docs
weight: 20
url: /ar/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase.TrySubstitute method

يستبدل الخط الأصلي بخط آخر.

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| Parameter | Type | Description |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | مواصفات الخط الأصلي. |
| substitutionFont | Font& | خط الاستبدال. |

### Return Value

صحيح في حالة نجاح الاستبدال.

## Remarks

يجب أن يتم وراثة فئة CustomFontSubstitutionBase لتنفيذ منطق استبدال الخطوط المخصص. يجب تجاوز طريقة TrySubstitute بشكل صحيح: يجب أن تعيد true في حالة الحاجة إلى الاستبدال. يجب تعيين substitutionFont إلى كائن Font صالح. يجب أن تعيد false في حالة عدم الحاجة إلى الاستبدال. يمكن تعيين substitutionFont إلى null.

### See Also

* class [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* class [Font](../../font/)
* class [CustomFontSubstitutionBase](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)