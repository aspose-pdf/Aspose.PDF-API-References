---
title: CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable
second_title: Aspose.PDF for .NET API Reference
description: خاصية OriginalFontSpecification. تحصل على قيمة تشير إلى أن الاستبدال لا مفر منه
type: docs
weight: 20
url: /ar/net/aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/issubstitutionunavoidable/
---
## خاصية CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable

تحصل على قيمة تشير إلى أن الاستبدال لا مفر منه.

```csharp
public bool IsSubstitutionUnavoidable { get; }
```

## ملاحظات

ترجع true في حالة تم طلب الاستبدال بسبب غياب الخط الأصلي أو في حالة عدم إمكانية استخدام الخط الأصلي في سياق مهمة معينة. في حالة تجاهل المستخدم للعلامة وعدم استبدال الخط - يتم تنفيذ إجراء استبدال الخط الافتراضي. ولكنها توفر فرصة للمستخدم لتغيير إجراء استبدال الخط القياسي وتعيين خط أفضل للنظام. ترجع false في حالة وجود الخط الأصلي، صالح، ولكن يُسمح للمستخدم باستبداله.

### انظر أيضًا

* class [OriginalFontSpecification](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)