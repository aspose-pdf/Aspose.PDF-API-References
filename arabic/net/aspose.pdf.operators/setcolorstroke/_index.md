---
title: Class SetColorStroke
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Operators.SetColorStroke. فئة تمثل مشغل SC لتعيين اللون لمشغلات لون التظليل
type: docs
weight: 7680
url: /ar/net/aspose.pdf.operators/setcolorstroke/
---
## SetColorStroke class

فئة تمثل مشغل SC لتعيين اللون لمشغلات لون التظليل.

```csharp
public class SetColorStroke : BasicSetColorOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetColorStroke](setcolorstroke/#constructor)() | يقوم بتهيئة المشغل. |
| [SetColorStroke](setcolorstroke/#constructor_1)(double) | تعيين اللون لمشغلات التظليل لألوان DeviceGray و CalGray و Indexed. |
| [SetColorStroke](setcolorstroke/#constructor_4)(double[]) | مُنشئ يسمح بتعيين مكونات اللون. |
| [SetColorStroke](setcolorstroke/#constructor_2)(double, double, double) | تعيين اللون لمشغل التظليل لألوان DeviceRGB و CalRGB و Lab. |
| [SetColorStroke](setcolorstroke/#constructor_3)(double, double, double, double) | تعيين اللون لمشغل التظليل لمساحة اللون CMYK. |

## Properties

| Name | Description |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolorstroke/b/) { get; set; } | يحصل على أو يحدد المكون الأزرق. |
| [C](../../aspose.pdf.operators/setcolorstroke/c/) { get; set; } | يحصل على أو يحدد المكون السماوي. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | يحصل على مصفوفة مكونات اللون. |
| [G](../../aspose.pdf.operators/setcolorstroke/g/) { get; set; } | يحصل على أو يحدد المكون الأخضر. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | يحصل على المكون الأسود من اللون الرمادي. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | فهرس المشغل في قائمة مشغلات الصفحة. |
| [K](../../aspose.pdf.operators/setcolorstroke/k/) { get; set; } | يحصل على أو يحدد المكون الأسود. |
| [M](../../aspose.pdf.operators/setcolorstroke/m/) { get; set; } | يحصل على أو يحدد المكون الأرجواني. |
| [R](../../aspose.pdf.operators/setcolorstroke/r/) { get; set; } | يحصل على أو يحدد المكون الأحمر. |
| [Y](../../aspose.pdf.operators/setcolorstroke/y/) { get; set; } | يحصل على أو يحدد المكون الأصفر. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolorstroke/accept/)(IOperatorSelector) | يقبل كائن الزائر لمعالجة المشغل. |
| override [getColor](../../aspose.pdf.operators/setcolorstroke/getcolor/)() | يعيد اللون المحدد بواسطة المشغل. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | يعيد نص المشغل ومعاييره. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | يقارن هذه النسخة مع الكائن المعطى. |

### See Also

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)