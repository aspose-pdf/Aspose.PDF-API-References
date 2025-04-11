---
title: Class SetAdvancedColorStroke
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Operators.SetAdvancedColorStroke. فئة تمثل مشغل SCN لتعيين اللون لعمليات التظليل
type: docs
weight: 7570
url: /ar/net/aspose.pdf.operators/setadvancedcolorstroke/
---
## SetAdvancedColorStroke class

فئة تمثل مشغل SCN (تعيين اللون لعمليات التظليل).

```csharp
public class SetAdvancedColorStroke : BasicSetColorAndPatternOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor)() | يقوم بتهيئة المشغل. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_1)(double) | مُنشئ لمشغل scn |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_4)(double, string) | مُنشئ لمشغل scn. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_5)(double[], string) | مُنشئ لمشغل scn. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_3)(double, double, double, string) | مُنشئ لمشغل scn. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_2)(double, double, double, double, string) | مُنشئ لمشغل scn. |

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
| [PatternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/patternname/) { get; } | يحصل على اسم النمط. |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | يحصل على مكون اللون الأحمر |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | يحصل على مكون اللون الأصفر من لون CMYK. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setadvancedcolorstroke/accept/)(IOperatorSelector) | يقبل كائن الزائر لمعالجة المشغل. |
| override [getColor](../../aspose.pdf.operators/setadvancedcolorstroke/getcolor/)() | يعيد اللون المحدد بواسطة المشغل. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | يعيد نص المشغل ومعاييره. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | يقارن هذه النسخة مع الكائن المعطى. |

### See Also

* class [BasicSetColorAndPatternOperator](../basicsetcolorandpatternoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)