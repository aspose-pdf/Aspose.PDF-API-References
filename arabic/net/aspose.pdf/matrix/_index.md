---
title: Matrix
second_title: Aspose.PDF لمرجع .NET API
description: تمثل الفئة مصفوفة التحويل.
type: docs
weight: 4740
url: /ar/net/aspose.pdf/matrix/
---
## Matrix class

تمثل الفئة مصفوفة التحويل.

```csharp
public sealed class Matrix
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Matrix](matrix#constructor)() | ينشئ Constructor مصفوفة قياسية من 1 إلى 1: [ABCDEF] = [1 ، 0 ، 0 ، 1 ، 0 ، 0] |
| [Matrix](matrix#constructor_3)(double[]) | يقبل Constructor مصفوفة بتمثيل المصفوفة التالي: [ABCDEF] |
| [Matrix](matrix#constructor_4)(float[]) | يقبل Constructor مصفوفة بتمثيل المصفوفة التالي: [ABCDEF] |
| [Matrix](matrix#constructor_1)(Matrix) | يقبل Constructor مصفوفة لإنشاء نسخة |
| [Matrix](matrix#constructor_2)(double, double, double, double, double, double) | تهيئة مصفوفة التحويل بالمعاملات المحددة. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [A](../../aspose.pdf/matrix/a) { get; set; } | عضو مصفوفة التحويل . |
| [B](../../aspose.pdf/matrix/b) { get; set; } | B عضو مصفوفة التحويل . |
| [C](../../aspose.pdf/matrix/c) { get; set; } | C عضو مصفوفة التحويل . |
| [D](../../aspose.pdf/matrix/d) { get; set; } | D عضو مصفوفة التحويل . |
| [Data](../../aspose.pdf/matrix/data) { get; } | الحصول على بيانات المصفوفة كمصفوفة . |
| [E](../../aspose.pdf/matrix/e) { get; set; } | E عضو مصفوفة التحويل. |
| [Elements](../../aspose.pdf/matrix/elements) { get; } | عناصر المصفوفة . |
| [F](../../aspose.pdf/matrix/f) { get; set; } | F عضو مصفوفة التحويل . |

## طُرق

| اسم | وصف |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation#rotation_1)(double) | إنشاء مصفوفة لزاوية دوران معينة. |
| static [Rotation](../../aspose.pdf/matrix/rotation#rotation)(Rotation) | إنشاء مصفوفة لدوران معين . |
| static [Skew](../../aspose.pdf/matrix/skew)(double, double) | إنشاء مصفوفة لزاوية دوران معينة. |
| [Add](../../aspose.pdf/matrix/add)(Matrix) | يضيف مصفوفة إلى مصفوفة أخرى. |
| override [Equals](../../aspose.pdf/matrix/equals)(object) | يقارن المصفوفة مع كائن آخر . |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode)() | كود تجزئة للكائن . |
| [Multiply](../../aspose.pdf/matrix/multiply)(Matrix) | ضرب المصفوفة في مصفوفة أخرى . |
| [Reverse](../../aspose.pdf/matrix/reverse)() | حساب المصفوفة العكسية. |
| override [ToString](../../aspose.pdf/matrix/tostring)() | إرجاع إعادة تمثيل النص للمصفوفة. |
| [Transform](../../aspose.pdf/matrix/transform#transform)(Point) | تحويل النقطة باستخدام هذه المصفوفة . |
| [Transform](../../aspose.pdf/matrix/transform#transform_1)(Rectangle) | تحويل المستطيل. إذا كانت الزاوية ليست 90 * N درجة ، فيتم إرجاع المستطيل المحيط. |
| static [GetAngle](../../aspose.pdf/matrix/getangle)(Rotation) | تحويل إلى زاوية (بالدرجات) |

### أنظر أيضا

* مساحة الاسم [Aspose.Pdf](../../aspose.pdf)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
