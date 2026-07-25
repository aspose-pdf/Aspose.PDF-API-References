---
title: "CustomFontSubstitutionBase.OriginalFontSpecification"
linktitle: "CustomFontSubstitutionBase.OriginalFontSpecification"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "<p> يمثل مواصفات الخط الأصلي. </p> <hr> <p> يوفر معلومات متعلقة بالخط الأصلي مثل ، علامة. كما يوفر علامة تساعد في التحقق مما إذا كان الاستبدال سيحدث. </p>"
type: docs
weight: 20
url: /ar/java/com.aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification

```
public static final class CustomFontSubstitutionBase.OriginalFontSpecification extends Object
```

<p> يمثل مواصفات الخط الأصلي. </p> <hr> <p> يوفر معلومات متعلقة بالخط الأصلي مثل , العلم. كما يوفر علمًا يساعد على التحقق مما إذا كان الاستبدال سيحدث على أي حال مع الخط ويمكن للمستخدم تجاوز منطق الاستبدال الافتراضي. </p>

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [OriginalFontSpecification](#OriginalFontSpecification-java.lang.String-boolean-boolean-) | يقوم بتهيئة كائن OriginalFontSpecification جديد. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | يحصل على اسم الخط الأصلي. |
| [isEmbedded](#isEmbedded--) | يحصل على قيمة تشير إلى ما إذا كان الخط مضمنًا. |
| [isSubstitutionUnavoidable](#isSubstitutionUnavoidable--) | <p> يحصل على قيمة تشير إلى أن الاستبدال لا مفر منه. </p> |

### OriginalFontSpecification {#OriginalFontSpecification-java.lang.String-boolean-boolean-}
يقوم بتهيئة كائن OriginalFontSpecification جديد.

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

يحصل على اسم الخط الأصلي.

**Returns:**
قيمة سلسلة

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

يحصل على قيمة تشير إلى ما إذا كان الخط مضمنًا.

**Returns:**
قيمة منطقية

### isSubstitutionUnavoidable {#isSubstitutionUnavoidable--}
```
public boolean isSubstitutionUnavoidable()
```

<p> يحصل على قيمة تشير إلى أن الاستبدال لا مفر منه. </p>

**Returns:**
قيمة منطقية <hr> <p> تُرجع true في حالة طلب الاستبدال بسبب عدم وجود الخط الأصلي أو في حالة عدم إمكانية استخدام الخط الأصلي في سياق مهمة معينة. إذا تجاهل المستخدم العلامة ولم يستبدل الخط - يتم تنفيذ إجراء الاستبدال الافتراضي للخط. لكنه يوفر للمستخدم فرصة لتغيير إجراء الاستبدال القياسي وتعيين خط أفضل للنظام. تُرجع false في حالة وجود الخط الأصلي، وصحته، ولكن يُسمح للمستخدم باستبداله. </p>
