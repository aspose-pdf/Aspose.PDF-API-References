---
title: "ComparisonMode"
linktitle: "ComparisonMode"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "تعداد وضع المقارنة."
type: docs
weight: 10
url: /ar/java/com.aspose.pdf.comparison.sidebysidecomparison/comparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.Enum, com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode

```
public final class ComparisonMode extends com.aspose.ms.System.Enum
```

تعداد وضع المقارنة.

## الحقول

| حقل | الوصف |
| --- | --- |
| [IgnoreSpaces](#IgnoreSpaces) | يتم تجاهل جميع المسافات. يتم البحث عن التغييرات فقط في الكلمات. |
| [Normal](#Normal) | الوضع العادي. تُؤخذ المسافات داخل قطع النص في الاعتبار فقط (حسب طريقة إنشاء المستند.) |
| [ParseSpaces](#ParseSpaces) | الوضع مشابه للوضع العادي، لكنه يحاول مراعاة التباعد البصري بين قطع النص بناءً على المسافة. قد لا يكون التعرف على عدد المسافات بين القطع دقيقًا لأن ذلك يعتمد بشكل كبير على طريقة إنشاء المستندات. إذا تم إنشاء المستندات بواسطة مولدات مختلفة، قد تكون هناك عدم دقة في مقارنة المسافات بين قطع النص. قد ينتج عن هذا الخيار نتائج، رغم منطقيتها، تختلف عن نتائج المقارنة المتوقعة عند تطبيقها على مستندات ذات هيكلية معقدة. |

### IgnoreSpaces {#IgnoreSpaces}
```
public static final int IgnoreSpaces
```

يتم تجاهل جميع المسافات. يتم البحث عن التغييرات فقط في الكلمات.

### Normal {#Normal}
```
public static final int Normal
```

الوضع العادي. تُؤخذ المسافات داخل قطع النص في الاعتبار فقط (حسب طريقة إنشاء المستند.)

### ParseSpaces {#ParseSpaces}
```
public static final int ParseSpaces
```

الوضع مشابه للوضع العادي، لكنه يحاول مراعاة التباعد البصري بين قطع النص بناءً على المسافة. قد لا يكون التعرف على عدد المسافات بين القطع دقيقًا لأن ذلك يعتمد بشكل كبير على طريقة إنشاء المستندات. إذا تم إنشاء المستندات بواسطة مولدات مختلفة، قد تكون هناك عدم دقة في مقارنة المسافات بين قطع النص. قد ينتج عن هذا الخيار نتائج، رغم منطقيتها، تختلف عن نتائج المقارنة المتوقعة عند تطبيقها على مستندات ذات هيكلية معقدة.
