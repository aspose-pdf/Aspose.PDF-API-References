---
title: Class SetDash
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Operators.SetDash. فئة تمثل نمط خط التقطيع لمجموعة المشغلين d
type: docs
weight: 7690
url: /ar/net/aspose.pdf.operators/setdash/
---
## SetDash class

فئة تمثل مشغل d (تعيين نمط خط متقطع).

```csharp
public class SetDash : Operator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetDash](setdash/)(int[], int) | ينشئ مشغل نمط متقطع. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | فهرس المشغل في قائمة مشغلات الصفحة. |
| [Pattern](../../aspose.pdf.operators/setdash/pattern/) { get; set; } | نمط المتقطع. يجب أن تكون عناصر المصفوفة أرقامًا تحدد أطوال المتقطعات والفجوات المتناوبة. في حالة مصفوفة ذات عنصر واحد، تكون أطوال المتقطع والفجوة متساوية. |
| [Phase](../../aspose.pdf.operators/setdash/phase/) { get; set; } | مرحلة المتقطع. قبل البدء في رسم مسار، يجب أن يتم تدوير مصفوفة المتقطع، مع إضافة أطوال المتقطعات والفجوات. عندما تساوي الطول المتراكم القيمة المحددة بواسطة مرحلة المتقطع، يجب أن يبدأ رسم المسار، ويجب استخدام مصفوفة المتقطع بشكل دوري من تلك النقطة فصاعدًا. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setdash/accept/)(IOperatorSelector) | يقبل كائن الزائر لمعالجة المشغل. |
| override [ToString](../../aspose.pdf.operators/setdash/tostring/)() | يحصل على تمثيل سلسلة للمشغل. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | يقارن هذه النسخة مع الكائن المعطى. |

### See Also

* class [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)