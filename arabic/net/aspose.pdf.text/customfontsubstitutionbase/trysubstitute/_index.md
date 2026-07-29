---
title: "CustomFontSubstitutionBase.TrySubstitute"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة CustomFontSubstitutionBase. تستبدل الخط الأصلي بخط آخر"
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

| معامل | النوع | الوصف |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | مواصفات الخط الأصلي. |
| substitutionFont | Font& | خط الاستبدال. |

### قيمة الإرجاع

صحيح في حالة نجاح الاستبدال.

## ملاحظات

يجب توريث الفئة CustomFontSubstitutionBase لتنفيذ منطق استبدال الخطوط المخصص. يجب تجاوز طريقة TrySubstitute بشكل صحيح: يجب إرجاع true في حالة الحاجة إلى الاستبدال. يجب تعيين substitutionFont إلى كائن Font صالح. يجب إرجاع false في حالة عدم الحاجة إلى الاستبدال. يمكن تعيين substitutionFont إلى null.

### انظر أيضًا

* class [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* class [Font](../../font/)
* class [CustomFontSubstitutionBase](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


