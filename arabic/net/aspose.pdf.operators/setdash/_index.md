---
title: "فئة SetDash"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.Operators.SetDash فئة. فئة تمثل مشغل d لتعيين نمط الخط المتقطع"
type: docs
weight: 7830
url: /ar/net/aspose.pdf.operators/setdash/
---
## SetDash class

الفئة التي تمثل المشغل d (تعيين نمط الشرط المتقطع للخط).

```csharp
public class SetDash : Operator
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SetDash](setdash/)(int[], int) | ينشئ مشغل تعيين نمط الخط المتقطع. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | فهرس العامل في قائمة عوامل الصفحة. |
| [Pattern](../../aspose.pdf.operators/setdash/pattern/) { get; set; } | نمط الخط المتقطع. يجب أن تكون عناصر المصفوفة أرقامًا تحدد أطوال الشرط المتناوب والفواصل. في حالة مصفوفة عنصر واحد تكون أطوال الشرط والفاصل متساوية. |
| [Phase](../../aspose.pdf.operators/setdash/phase/) { get; set; } | مرحلة الخط المتقطع. قبل بدء رسم مسار، يجب تمرير مصفوفة الخط المتقطع، مع جمع أطوال الشرط والفواصل. عندما يساوي الطول المتراكم القيمة المحددة بواسطة مرحلة الخط المتقطع، يبدأ رسم المسار، وتُستخدم مصفوفة الخط المتقطع بشكل دوري من تلك النقطة فصاعدًا. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setdash/accept/)(IOperatorSelector) | يقبل كائن الزائر لمعالجة العامل. |
| override [ToString](../../aspose.pdf.operators/setdash/tostring/)() | يحصل على تمثيل النص للمشغل. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | يقارن هذا الكائن بالكيان المعطى. |

### انظر أيضًا

* class [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


