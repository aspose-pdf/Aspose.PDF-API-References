---
title: Class Matrix
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Matrix. تمثل الفئة مصفوفة التحويل
type: docs
weight: 6920
url: /ar/net/aspose.pdf/matrix/
---
## فئة المصفوفة

تمثل الفئة مصفوفة التحويل.

```csharp
public sealed class Matrix
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Matrix](matrix/#constructor)() | المنشئ ينشئ مصفوفة قياسية 1 إلى 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](matrix/#constructor_3)(double[]) | المنشئ يقبل مصفوفة بالتنسيق التالي: [ A B C D E F ] |
| [Matrix](matrix/#constructor_4)(float[]) | المنشئ يقبل مصفوفة بالتنسيق التالي: [ A B C D E F ] |
| [Matrix](matrix/#constructor_1)(Matrix) | المنشئ يقبل مصفوفة لإنشاء نسخة |
| [Matrix](matrix/#constructor_2)(double, double, double, double, double, double) | يقوم بتهيئة مصفوفة التحويل بالمعاملات المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [A](../../aspose.pdf/matrix/a/) { get; set; } | عضو من مصفوفة التحويل. |
| [B](../../aspose.pdf/matrix/b/) { get; set; } | عضو B من مصفوفة التحويل. |
| [C](../../aspose.pdf/matrix/c/) { get; set; } | عضو C من مصفوفة التحويل. |
| [D](../../aspose.pdf/matrix/d/) { get; set; } | عضو D من مصفوفة التحويل. |
| [Data](../../aspose.pdf/matrix/data/) { get; } | يحصل على بيانات المصفوفة كمصفوفة. |
| [E](../../aspose.pdf/matrix/e/) { get; set; } | عضو E من مصفوفة التحويل. |
| [Elements](../../aspose.pdf/matrix/elements/) { get; } | عناصر المصفوفة. |
| [F](../../aspose.pdf/matrix/f/) { get; set; } | عضو F من مصفوفة التحويل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation_1)(double) | ينشئ مصفوفة لزاوية الدوران المعطاة. |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation)(Rotation) | ينشئ مصفوفة للدوران المعطى. |
| static [Scale](../../aspose.pdf/matrix/scale/)(double, double, Matrix) | يطبق التحجيم على المصفوفة المعطاة. |
| static [Skew](../../aspose.pdf/matrix/skew/)(double, double) | ينشئ مصفوفة لزاوية الدوران المعطاة. |
| static [Translate](../../aspose.pdf/matrix/translate/)(double, double, Matrix) | ينقل مصفوفة بمقدار محدد في اتجاه x و y. |
| [Add](../../aspose.pdf/matrix/add/)(Matrix) | يضيف مصفوفة إلى مصفوفة أخرى. |
| override [Equals](../../aspose.pdf/matrix/equals/)(object) | يقارن المصفوفة مع كائن آخر. |
| [GetFlipMatrix](../../aspose.pdf/matrix/getflipmatrix/)() | يحصل على مصفوفة الانعكاس. |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode/)() | رمز التجزئة للكائن. |
| [Multiply](../../aspose.pdf/matrix/multiply/)(Matrix) | يضرب المصفوفة بمصفوفة أخرى. |
| [Reverse](../../aspose.pdf/matrix/reverse/)() | يحسب المصفوفة العكسية. |
| [Scale](../../aspose.pdf/matrix/scale/)(double, double, out double, out double) | يقوم بتحجيم x و y باستخدام المصفوفة باستخدام الصيغة التالية: x1 = A*x + C*y; y1 = B*x + D*y; |
| override [ToString](../../aspose.pdf/matrix/tostring/)() | يعيد تمثيل نصي للمصفوفة. |
| [Transform](../../aspose.pdf/matrix/transform/#transform)(Point) | يحول النقطة باستخدام هذه المصفوفة. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_1)(Rectangle) | يحول المستطيل. إذا كانت الزاوية ليست 90 * N درجة، يتم إرجاع المستطيل المحيط. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_2)(double, double, out double, out double) | يحول الإحداثيات باستخدام هذه المصفوفة. |
| [UnScale](../../aspose.pdf/matrix/unscale/)(double, double, out double, out double) | يقوم بإعادة تحجيم x1 و y1 ويعيد x و y قبل تحويل المصفوفة باستخدام الصيغة التالية: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [UnTransform](../../aspose.pdf/matrix/untransform/)(double, double, out double, out double) | يقوم بتحويل x1 و y1 ويعيد x و y قبل تحويل المصفوفة باستخدام الصيغة التالية: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |
| static [GetAngle](../../aspose.pdf/matrix/getangle/)(Rotation) | يترجم الدوران إلى زاوية (درجات) |

### انظر أيضًا

* مساحة الأسماء [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)