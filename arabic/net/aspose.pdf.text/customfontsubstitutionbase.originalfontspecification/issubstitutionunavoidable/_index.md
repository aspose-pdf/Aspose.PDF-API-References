---
title: "CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية OriginalFontSpecification. تحصل على قيمة تشير إلى أن الاستبدال لا يمكن تجنبه"
type: docs
weight: 20
url: /ar/net/aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/issubstitutionunavoidable/
---
## CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable property

يحصل على قيمة تشير إلى أن الاستبدال لا يمكن تجنبه.

```csharp
public bool IsSubstitutionUnavoidable { get; }
```

## ملاحظات

يرجع true في حالة طلب الاستبدال بسبب عدم وجود الخط الأصلي أو في حالة عدم إمكانية استخدام الخط الأصلي في سياق مهمة معينة. إذا تجاهل المستخدم العلامة ولم يستبدل الخط - يتم تنفيذ إجراء استبدال الخط الافتراضي. لكنه يوفر للمستخدم فرصة لتغيير إجراء استبدال الخط القياسي وتعيين خط أفضل للنظام. يرجع false في حالة وجود الخط الأصلي، وصحته، ولكن يُسمح للمستخدم باستبداله.

### انظر أيضًا

* class [OriginalFontSpecification](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


