---
title: "LineJoin"
linktitle: "LineJoin"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يجب أن يحدد نمط وصل الخط الشكل الذي سيُستخدم في زوايا المسارات التي تُرسم."
type: docs
weight: 370
url: /ar/java/com.aspose.pdf.operators/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.operators.LineJoin, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.operators.LineJoin, com.aspose.ms.System.Enum, com.aspose.pdf.operators.LineJoin

```
public final class LineJoin extends com.aspose.ms.System.Enum
```

يجب أن يحدد نمط وصل الخط الشكل الذي سيُستخدم في زوايا المسارات التي تُرسم.

## الحقول

| حقل | الوصف |
| --- | --- |
| [BevelJoin](#BevelJoin) | تقاطع مائل. يجب إنهاء الجزأين بغطاءات مسطحة (انظر 8.4.3.3، "Line Cap Style") ويجب ملء الفتحة الناتجة وراء نهايات الجزأين بمثلث. |
| [MiterJoin](#MiterJoin) | تقاطع ميتّر. يجب تمديد الحواف الخارجية للخطوط للجزأين حتى تلتقي بزاوية، كما في إطار صورة. إذا التقى الجزأين بزاوية حادة جدًا كما يحددها معامل حد الميتّر (انظر 8.4.3.5، "Miter Limit")، يجب استخدام تقاطع مائل بدلاً من ذلك. |
| [RoundJoin](#RoundJoin) | تقاطع مستدير. يجب رسم قوس دائرة بقطر يساوي عرض الخط حول النقطة التي يلتقي فيها الجزأين، موصولًا الحواف الخارجية للخطوط للجزأين. يجب ملء هذا الشكل الشبه فطيرة، مما ينتج زاوية مستديرة. |

### BevelJoin {#BevelJoin}
```
public static final int BevelJoin
```

تقاطع مائل. يجب إنهاء الجزأين بغطاءات مسطحة (انظر 8.4.3.3، "Line Cap Style") ويجب ملء الفتحة الناتجة وراء نهايات الجزأين بمثلث.

### MiterJoin {#MiterJoin}
```
public static final int MiterJoin
```

تقاطع ميتّر. يجب تمديد الحواف الخارجية للخطوط للجزأين حتى تلتقي بزاوية، كما في إطار صورة. إذا التقى الجزأين بزاوية حادة جدًا كما يحددها معامل حد الميتّر (انظر 8.4.3.5، "Miter Limit")، يجب استخدام تقاطع مائل بدلاً من ذلك.

### RoundJoin {#RoundJoin}
```
public static final int RoundJoin
```

تقاطع مستدير. يجب رسم قوس دائرة بقطر يساوي عرض الخط حول النقطة التي يلتقي فيها الجزأين، موصولًا الحواف الخارجية للخطوط للجزأين. يجب ملء هذا الشكل الشبه فطيرة، مما ينتج زاوية مستديرة.
