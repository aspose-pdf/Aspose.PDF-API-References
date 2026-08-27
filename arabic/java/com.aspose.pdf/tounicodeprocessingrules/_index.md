---
title: "ToUnicodeProcessingRules"
linktitle: "ToUnicodeProcessingRules"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "تصف هذه الفئة القواعد التي يمكن استخدامها لحل خطأ Adobe Preflight \"لا يمكن تعيين النص إلى Unicode\"."
type: docs
weight: 5380
url: /ar/java/com.aspose.pdf/tounicodeprocessingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ToUnicodeProcessingRules

```
public class ToUnicodeProcessingRules extends Object
```

هذه الفئة تصف القواعد التي يمكن استخدامها لحل خطأ Adobe Preflight "لا يمكن تعيين النص إلى Unicode".

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules--) | يُنشئ مثيلًا جديدًا للفئة {@link ToUnicodeProcessingRules}. |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-) | يُنشئ مثيلًا جديدًا للفئة {@link ToUnicodeProcessingRules} مع الخيار المحدد لإزالة المسافات من أسماء CMap. |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-boolean-) | يُنشئ مثيلًا جديدًا للفئة {@link ToUnicodeProcessingRules} مع الخيارات المحددة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getMapNonLinkedSymbolsOnSpace](#getMapNonLinkedSymbolsOnSpace--) | بعض الخطوط لا توفر معلومات عن Unicode لبعض رموز النص. هذا النقص في المعلومات يسبب الخطأ "لا يمكن تعيين النص إلى Unicode". استخدم هذه العلامة لتعيين الرموز غير المرتبطة إلى Unicode "مسافة" (الرمز 32). |
| [getRemoveSpacesFromCMapNames](#getRemoveSpacesFromCMapNames--) | بعض الخطوط تحتوي على خرائط رموز ToUnicode بأسماء تحتوي على مسافات. هذه المسافات قد تتسبب في أخطاء عند تعيين النص إلى Unicode. هذه العلامة تُلزم بإزالة المسافات من أسماء خرائط رموز ToUnicode. القيمة الافتراضية false. |
| [setMapNonLinkedSymbolsOnSpace](#setMapNonLinkedSymbolsOnSpace-boolean-) | بعض الخطوط لا توفر معلومات عن Unicode لبعض رموز النص. هذا النقص في المعلومات يسبب الخطأ "لا يمكن تعيين النص إلى Unicode". استخدم هذه العلامة لتعيين الرموز غير المرتبطة إلى Unicode "مسافة" (الرمز 32). |
| [setRemoveSpacesFromCMapNames](#setRemoveSpacesFromCMapNames-boolean-) | بعض الخطوط تحتوي على خرائط رموز ToUnicode بأسماء تحتوي على مسافات. هذه المسافات قد تتسبب في أخطاء عند تعيين النص إلى Unicode. هذه العلامة تُلزم بإزالة المسافات من أسماء خرائط رموز ToUnicode. القيمة الافتراضية false. |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules()
```

يُنشئ مثيلًا جديدًا للفئة {@link ToUnicodeProcessingRules}.

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces)
```

يُنشئ مثيلًا جديدًا للفئة {@link ToUnicodeProcessingRules} مع الخيار المحدد لإزالة المسافات من أسماء CMap.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| removeSpaces |  | قيمة منطقية تشير إلى ما إذا كان يجب إزالة المسافات من أسماء CMap. |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace)
```

يُنشئ مثيلًا جديدًا للفئة {@link ToUnicodeProcessingRules} مع الخيارات المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| removeSpaces |  | تشير إلى ما إذا كان يجب إزالة المسافات من أسماء CMap. |
| mapNonLinkedUnicodesOnSpace |  | تشير إلى ما إذا كان يجب تعيين رموز Unicode غير المرتبطة إلى مسافات. |

### getMapNonLinkedSymbolsOnSpace {#getMapNonLinkedSymbolsOnSpace--}
```
public boolean getMapNonLinkedSymbolsOnSpace()
```

بعض الخطوط لا توفر معلومات عن Unicode لبعض رموز النص. هذا النقص في المعلومات يسبب الخطأ "لا يمكن تعيين النص إلى Unicode". استخدم هذه العلامة لتعيين الرموز غير المرتبطة إلى Unicode "مسافة" (الرمز 32).

**Returns:**
قيمة منطقية

### getRemoveSpacesFromCMapNames {#getRemoveSpacesFromCMapNames--}
```
public boolean getRemoveSpacesFromCMapNames()
```

بعض الخطوط تحتوي على خرائط رموز ToUnicode بأسماء تحتوي على مسافات. هذه المسافات قد تتسبب في أخطاء عند تعيين النص إلى Unicode. هذه العلامة تُلزم بإزالة المسافات من أسماء خرائط رموز ToUnicode. القيمة الافتراضية false.

**Returns:**
قيمة منطقية

### setMapNonLinkedSymbolsOnSpace {#setMapNonLinkedSymbolsOnSpace-boolean-}
```
public void setMapNonLinkedSymbolsOnSpace(boolean value)
```

بعض الخطوط لا توفر معلومات عن Unicode لبعض رموز النص. هذا النقص في المعلومات يسبب الخطأ "لا يمكن تعيين النص إلى Unicode". استخدم هذه العلامة لتعيين الرموز غير المرتبطة إلى Unicode "مسافة" (الرمز 32).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setRemoveSpacesFromCMapNames {#setRemoveSpacesFromCMapNames-boolean-}
```
public void setRemoveSpacesFromCMapNames(boolean value)
```

بعض الخطوط تحتوي على خرائط رموز ToUnicode بأسماء تحتوي على مسافات. هذه المسافات قد تتسبب في أخطاء عند تعيين النص إلى Unicode. هذه العلامة تُلزم بإزالة المسافات من أسماء خرائط رموز ToUnicode. القيمة الافتراضية false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
