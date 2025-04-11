---
title: Class SetColor
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Operators.SetColor. تمثل فئة لمشغل sc لتعيين اللون للعمليات غير المرسومة
type: docs
weight: 7630
url: /ar/net/aspose.pdf.operators/setcolor/
---
## SetColor class

تمثل فئة لمشغل sc (تعيين اللون للعمليات غير المرسومة).

```csharp
public class SetColor : BasicSetColorOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetColor](setcolor/#constructor)() | يقوم بتهيئة المشغل. |
| [SetColor](setcolor/#constructor_1)(double) | تعيين اللون لمشغلات الرسم للألوان DeviceGray و CalGray و Indexed. |
| [SetColor](setcolor/#constructor_4)(double[]) | مُنشئ يسمح بتحديد مكونات اللون. |
| [SetColor](setcolor/#constructor_2)(double, double, double) | تعيين اللون لمشغل الرسم لألوان DeviceRGB و CalRGB و Lab |
| [SetColor](setcolor/#constructor_3)(double, double, double, double) | تعيين اللون لمشغل غير مرسوم لمساحة اللون CMYK |

## Properties

| Name | Description |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolor/b/) { get; set; } | يحصل على أو يحدد مكون اللون الأزرق. |
| [C](../../aspose.pdf.operators/setcolor/c/) { get; set; } | يحصل على أو يحدد مكون اللون السماوي. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | يحصل على مصفوفة مكونات اللون. |
| [G](../../aspose.pdf.operators/setcolor/g/) { get; set; } | يحصل على أو يحدد مكون اللون الأخضر. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | يحصل على مكون اللون الأسود من اللون الرمادي. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | فهرس المشغل في قائمة مشغلات الصفحة. |
| [K](../../aspose.pdf.operators/setcolor/k/) { get; set; } | يحصل على أو يحدد مكون اللون الأسود. |
| [M](../../aspose.pdf.operators/setcolor/m/) { get; set; } | يحصل على أو يحدد مكون اللون الأرجواني. |
| [R](../../aspose.pdf.operators/setcolor/r/) { get; set; } | يحصل على أو يحدد مكون اللون الأحمر. |
| [Y](../../aspose.pdf.operators/setcolor/y/) { get; set; } | يحصل على أو يحدد مكون اللون الأصفر. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolor/accept/)(IOperatorSelector) | يقبل كائن الزائر لمعالجة المشغل. |
| override [getColor](../../aspose.pdf.operators/setcolor/getcolor/)() | يعيد اللون المحدد بواسطة المشغل. |
| override [ToString](../../aspose.pdf.operators/setcolor/tostring/)() | يعيد تمثيل سلسلة للون. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | يقارن هذه النسخة مع الكائن المعطى. |

### See Also

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)