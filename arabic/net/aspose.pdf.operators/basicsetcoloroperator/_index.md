---
title: Class BasicSetColorOperator
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Operators.BasicSetColorOperator. الفئة الأساسية لمشغلات تعيين اللون
type: docs
weight: 7160
url: /ar/net/aspose.pdf.operators/basicsetcoloroperator/
---
## BasicSetColorOperator class

الفئة الأساسية لمشغلات تعيين اللون.

```csharp
public abstract class BasicSetColorOperator : SetColorOperator
```

## Properties

| Name | Description |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | يحصل على مكون اللون الأحمر |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | يحصل على مكون السايان من لون CMYK. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | يحصل على مصفوفة مكونات اللون. |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | يحصل على مكون اللون الأخضر |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | يحصل على مكون اللون الأسود من اللون الرمادي. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | فهرس المشغل في قائمة مشغلات الصفحة. |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | يحصل على مكون اللون الأسود من لون CMYK. |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | يحصل على مكون الماجنتا من لون CMYK. |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | يحصل على مكون اللون الأحمر |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | يحصل على مكون اللون الأصفر من لون CMYK. |

## Methods

| Name | Description |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | يقبل الزائر IOperatorSelector الذي يوفر معالجة المشغلات. |
| abstract [getColor](../../aspose.pdf.operators/setcoloroperator/getcolor/)() | يعيد اللون المحدد بواسطة المشغل. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | يعيد نص المشغل ومعاييره. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | يقارن هذه النسخة مع الكائن المعطى. |

### See Also

* class [SetColorOperator](../setcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)