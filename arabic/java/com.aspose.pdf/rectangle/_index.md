---
title: "Rectangle"
linktitle: "Rectangle"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل مستطيل."
type: docs
weight: 4100
url: /ar/java/com.aspose.pdf/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Rectangle

**All Implemented Interfaces:**
Cloneable, Comparable < Object >

```
public final class Rectangle extends Object implements Comparable < Object >, Cloneable
```

فئة تمثل مستطيل.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Rectangle](#Rectangle-double-double-double-double-) | منشئ Rectangle. |
| [Rectangle](#Rectangle-double-double-double-double-boolean-) | منشئ Rectangle. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [_Intersect](#Z:Z_Intersect-com.aspose.pdf.Rectangle-) | يتقاطع المستطيلات. طريقة قديمة. يرجى استخدام Intersect بدلاً من ذلك. |
| [center](#center--) | إرجاع إحداثيات مركز المستطيل. |
| [clone](#clone--) | ينسخ كائن Rectangle. |
| [compareTo](#compareTo-java.lang.Object-) | CompareTo |
| [contains](#contains-com.aspose.pdf.Point-) | يحدد ما إذا كانت النقطة المعطاة داخل المستطيل. |
| [contains](#contains-com.aspose.pdf.Point-boolean-) | يحدد ما إذا كانت النقطة المعطاة داخل المستطيل. |
| [containsLine](#containsLine-double-double-double-double-) | يحدد ما إذا كان المستطيل يحتوي على خط ممثل بنقطتين. |
| [containsPoint](#containsPoint-double-double-) | يحدد ما إذا كانت النقطة المعطاة موجودة داخل المستطيل. |
| [deepClone](#deepClone--) | ينسخ كائن Rectangle. |
| [equals](#equals-java.lang.Object-) | تحقق مما إذا كانت المستطيلات متساوية أي لها نفس الموقع والحجم. |
| [fromRect](#fromRect-java.awt.Rectangle-) | يُهيئ مستطيلًا جديدًا من نسخة مُعطاة من System.Drawing.Rectangle. |
| [fromRect](#fromRect-java.awt.geom.Rectangle2D.Float-) | يُهيئ مستطيلًا جديدًا من نسخة مُعطاة من System.Drawing.Rectangle. |
| [fromRectInternal](#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [getArea](#getArea--) | يحسب مساحة المستطيل. |
| [getEmpty](#getEmpty--) | يحصل على مستطيل فارغ |
| [getHeight](#getHeight--) | احصل على ارتفاع المستطيل. |
| [getLLX](#getLLX--) | يحصل على إحداثي X للزاوية السفلية اليسرى. |
| [getLLY](#getLLY--) | يحصل على إحداثي Y للزاوية السفلية اليسرى. |
| [getTrivial](#getTrivial--) | يُهيئ مستطيلًا بسيطًا أي مستطيل بموقع وحجم صفر. |
| [getURX](#getURX--) | يحصل على إحداثي X للزاوية العليا اليمنى. |
| [getURY](#getURY--) | يحصل على إحداثي Y للزاوية العليا اليمنى. |
| [getWidth](#getWidth--) | احصل على عرض المستطيل. |
| [hashCode](#hashCode--) | إرجاع قيمة رمز تجزئة (hash code) للكائن. يتم دعم هذه الطريقة لفائدة جداول التجزئة مثل تلك التي توفرها {@link java.util.HashMap}. <p> العقد العام لـ {@code hashCode} هو: <ul> <li>كلما تم استدعاؤها على نفس الكائن أكثر من مرة خلال تنفيذ تطبيق جافا، يجب أن تُعيد طريقة {@code hashCode} نفس العدد الصحيح بشكل ثابت، بشرط عدم تعديل أي معلومات تُستخدم في مقارنات {@code equals} على الكائن. لا يلزم أن يظل هذا العدد ثابتًا بين تنفيذ تطبيق وآخر من نفس التطبيق. <li>إذا كان كائنان متساويان وفقًا للطريقة {@code equals(Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نفس النتيجة العددية. <li>ليس من <em>الضروري</em> أنه إذا كان كائنان غير متساويين وفقًا للطريقة {@link java.lang.Object#equals(java.lang.Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نتائج عددية متميزة. ومع ذلك، يجب أن يكون المبرمج على علم بأن إنتاج نتائج عددية متميزة للكائنات غير المتساوية قد يحسن أداء جداول التجزئة. </ul> <p> بقدر ما يكون عمليًا ومعقولًا، تُعيد طريقة hashCode المعرفة في الفئة {@code Object} أعدادًا صحيحة متميزة للكائنات المتميزة. (عادةً ما يتم تنفيذ ذلك بتحويل العنوان الداخلي للكائن إلى عدد صحيح، لكن هذه التقنية التنفيذية ليست مطلوبة من قبل لغة البرمجة Java<span style="font-size:70%"><sup>TM</sup></span>.) |
| [intersect](#intersect-com.aspose.pdf.Rectangle-) | يتقاطع المستطيلان. |
| [isEmpty](#isEmpty--) | يتحقق مما إذا كان المستطيل فارغًا. |
| [isInclude](#isInclude-com.aspose.pdf.Rectangle-double-) | يتحقق من أن هذا المستطيل يشمل المستطيل الآخر بالكامل. أي أن المستطيل الآخر بالكامل داخل هذا المستطيل. الاختلاف مع طريقة IsIntersect هو أن IsIntersect ستعيد true للمستطيلات المتقاطع جزئيًا لكن IsInclude ستعيد false. |
| [isIntersect](#isIntersect-com.aspose.pdf.Rectangle-) | يحدد ما إذا كان هذا المستطيل يتقاطع مع مستطيل آخر. |
| [isPoint](#isPoint--) | يتحقق مما إذا كان المستطيل نقطة أي أن LLX يساوي URX و LLY يساوي URY. |
| [isTrivial](#isTrivial--) | يتحقق مما إذا كان المستطيل تافه أي أنه بحجم صفر وموقع صفر. |
| [join](#join-com.aspose.pdf.Rectangle-) | يجمع المستطيلات. |
| [moveBy](#moveBy-double-double-) | يُحرك المستطيل بالتحولات المحددة. |
| [nearEquals](#nearEquals-com.aspose.pdf.Rectangle-double-) | تحقق مما إذا كانت المستطيلات متقاربة أي أنها ذات موضع وأحجام متقاربة (حتى دلتا). |
| [parse](#parse-java.lang.String-) | حاول تحليل السلسلة واستخراج مكوّنات المستطيل llx، lly، urx، ury منها. |
| [rotate](#rotate-com.aspose.pdf.Rotation-) | دوّر المستطيل بالزاوية المحددة. |
| [rotateAngle](#rotateAngle-int-) | دوّر المستطيل بالزاوية المحددة. |
| [setLLX](#setLLX-double-) | يضبط إحداثي X للزاوية السفلية اليسرى. |
| [setLLY](#setLLY-double-) | يضبط إحداثي Y للزاوية السفلية اليسرى. |
| [setURX](#setURX-double-) | يضبط إحداثي X للزاوية العليا اليمنى. |
| [setURY](#setURY-double-) | يضبط إحداثي Y للزاوية العليا اليمنى. |
| [toArray](#toArray-com.aspose.pdf.engine.data.ITrailerable-) |  |
| [toPoints](#toPoints--) | يحوّل المستطيل إلى مصفوفة من النقاط ("QuadPoints"). |
| [toRect](#toRect--) | يحوّل المستطيل إلى كائن من System.Drawing.Rectangle. يتم تقصير المواقع والأحجام ذات الفاصلة العائمة. |
| [toString](#toString--) | يحصل على تمثيل المستطيل كسلسلة. |

### Rectangle {#Rectangle-double-double-double-double-}
```
public Rectangle(double llx, double lly, double urx, double ury)
```

منشئ Rectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| llx |  | X للزاوية السفلية اليسرى. |
| lly |  | Y للزاوية السفلية اليسرى. |
| urx |  | X للزاوية العليا اليمنى. |
| ury |  | Y للزاوية العليا اليمنى. |

### Rectangle {#Rectangle-double-double-double-double-boolean-}
```
public Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates)
```

منشئ Rectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| llx |  | X للزاوية السفلية اليسرى. |
| lly |  | Y للزاوية السفلية اليسرى. |
| urx |  | X للزاوية العليا اليمنى. |
| ury |  | Y للزاوية العليا اليمنى. |
| normalizeCoordinates |  | تطبيع إحداثيات المستطيل. |

### _Intersect {#Z:Z_Intersect-com.aspose.pdf.Rectangle-}
يتقاطع المستطيلات. طريقة قديمة. يرجى استخدام Intersect بدلاً من ذلك.

### center {#center--}
```
public Point center()
```

إرجاع إحداثيات مركز المستطيل.

**Returns:**
النقطة التي هي مركز المستطيل.

### clone {#clone--}
```
public Rectangle clone()
```

ينسخ كائن Rectangle.

**Returns:**
استنساخ الكائن.

### compareTo {#compareTo-java.lang.Object-}
CompareTo

### contains {#contains-com.aspose.pdf.Point-}
يحدد ما إذا كانت النقطة المعطاة داخل المستطيل.

### contains {#contains-com.aspose.pdf.Point-boolean-}
يحدد ما إذا كانت النقطة المعطاة داخل المستطيل.

### containsLine {#containsLine-double-double-double-double-}
```
public final boolean containsLine(double x1, double y1, double x2, double y2)
```

يحدد ما إذا كان المستطيل يحتوي على خط ممثل بنقطتين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x1 |  | إحداثي X لنقطة البداية للخط. |
| y1 |  | إحداثي Y لنقطة البداية للخط. |
| x2 |  | إحداثي X لنقطة النهاية للخط. |
| y2 |  | إحداثي Y لنقطة النهاية للخط. |

**Returns:**
{@code true} إذا كان المستطيل يحتوي على الخط؛ وإلا {@code false}.

### containsPoint {#containsPoint-double-double-}
```
public final boolean containsPoint(double x, double y)
```

يحدد ما إذا كانت النقطة المعطاة موجودة داخل المستطيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x |  | إحداثي X للنقطة. |
| y |  | إحداثي Y للنقطة. |

**Returns:**
{@code true} إذا كانت النقطة داخل المستطيل؛ وإلا {@code false}.

### deepClone {#deepClone--}
```
public Rectangle deepClone()
```

ينسخ كائن Rectangle.

**Returns:**
استنساخ الكائن.

### equals {#equals-java.lang.Object-}
تحقق مما إذا كانت المستطيلات متساوية أي لها نفس الموقع والحجم.

### fromRect {#fromRect-java.awt.Rectangle-}
يُهيئ مستطيلًا جديدًا من نسخة مُعطاة من System.Drawing.Rectangle.

### fromRect {#fromRect-java.awt.geom.Rectangle2D.Float-}
يُهيئ مستطيلًا جديدًا من نسخة مُعطاة من System.Drawing.Rectangle.

### fromRectInternal {#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-}


### getArea {#getArea--}
```
public final double getArea()
```

يحسب مساحة المستطيل.

**Returns:**
مساحة المستطيل كقيمة مزدوجة، تُحسب بضرب العرض والارتفاع.

### getEmpty {#getEmpty--}
```
public static Rectangle getEmpty()
```

يحصل على مستطيل فارغ

**Returns:**
كائن Rectangle جديد

### getHeight {#getHeight--}
```
public double getHeight()
```

احصل على ارتفاع المستطيل.

**Returns:**
قيمة double

### getLLX {#getLLX--}
```
public double getLLX()
```

يحصل على إحداثي X للزاوية السفلية اليسرى.

**Returns:**
قيمة double

### getLLY {#getLLY--}
```
public double getLLY()
```

يحصل على إحداثي Y للزاوية السفلية اليسرى.

**Returns:**
قيمة double

### getTrivial {#getTrivial--}
```
public static Rectangle getTrivial()
```

يُهيئ مستطيلًا بسيطًا أي مستطيل بموقع وحجم صفر.

**Returns:**
كائن Rectangle جديد

### getURX {#getURX--}
```
public double getURX()
```

يحصل على إحداثي X للزاوية العليا اليمنى.

**Returns:**
قيمة double

### getURY {#getURY--}
```
public double getURY()
```

يحصل على إحداثي Y للزاوية العليا اليمنى.

**Returns:**
قيمة double

### getWidth {#getWidth--}
```
public double getWidth()
```

احصل على عرض المستطيل.

**Returns:**
قيمة double

### hashCode {#hashCode--}
```
public int hashCode()
```

إرجاع قيمة رمز تجزئة (hash code) للكائن. يتم دعم هذه الطريقة لفائدة جداول التجزئة مثل تلك التي توفرها {@link java.util.HashMap}. <p> العقد العام لـ {@code hashCode} هو: <ul> <li>كلما تم استدعاؤها على نفس الكائن أكثر من مرة خلال تنفيذ تطبيق جافا، يجب أن تُعيد طريقة {@code hashCode} نفس العدد الصحيح بشكل ثابت، بشرط عدم تعديل أي معلومات تُستخدم في مقارنات {@code equals} على الكائن. لا يلزم أن يظل هذا العدد ثابتًا بين تنفيذ تطبيق وآخر من نفس التطبيق. <li>إذا كان كائنان متساويان وفقًا للطريقة {@code equals(Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نفس النتيجة العددية. <li>ليس من <em>الضروري</em> أنه إذا كان كائنان غير متساويين وفقًا للطريقة {@link java.lang.Object#equals(java.lang.Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نتائج عددية متميزة. ومع ذلك، يجب أن يكون المبرمج على علم بأن إنتاج نتائج عددية متميزة للكائنات غير المتساوية قد يحسن أداء جداول التجزئة. </ul> <p> بقدر ما يكون عمليًا ومعقولًا، تُعيد طريقة hashCode المعرفة في الفئة {@code Object} أعدادًا صحيحة متميزة للكائنات المتميزة. (عادةً ما يتم تنفيذ ذلك بتحويل العنوان الداخلي للكائن إلى عدد صحيح، لكن هذه التقنية التنفيذية ليست مطلوبة من قبل لغة البرمجة Java<span style="font-size:70%"><sup>TM</sup></span>.)

**Returns:**
قيمة رمز تجزئة لهذا الكائن. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### intersect {#intersect-com.aspose.pdf.Rectangle-}
يتقاطع المستطيلان.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

يتحقق مما إذا كان المستطيل فارغًا.

**Returns:**
قيمة منطقية

### isInclude {#isInclude-com.aspose.pdf.Rectangle-double-}
يتحقق من أن هذا المستطيل يشمل المستطيل الآخر بالكامل. أي أن المستطيل الآخر بالكامل داخل هذا المستطيل. الاختلاف مع طريقة IsIntersect هو أن IsIntersect ستعيد true للمستطيلات المتقاطع جزئيًا لكن IsInclude ستعيد false.

### isIntersect {#isIntersect-com.aspose.pdf.Rectangle-}
يحدد ما إذا كان هذا المستطيل يتقاطع مع مستطيل آخر.

### isPoint {#isPoint--}
```
public boolean isPoint()
```

يتحقق مما إذا كان المستطيل نقطة أي أن LLX يساوي URX و LLY يساوي URY.

**Returns:**
قيمة منطقية

### isTrivial {#isTrivial--}
```
public boolean isTrivial()
```

يتحقق مما إذا كان المستطيل تافه أي أنه بحجم صفر وموقع صفر.

**Returns:**
قيمة منطقية

### join {#join-com.aspose.pdf.Rectangle-}
يجمع المستطيلات.

### moveBy {#moveBy-double-double-}
```
public final void moveBy(double dx, double dy)
```

يُحرك المستطيل بالتحولات المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx |  | قيمة الإزاحة بمحور X. |
| dy |  | قيمة الإزاحة بمحور Y. |

### nearEquals {#nearEquals-com.aspose.pdf.Rectangle-double-}
تحقق مما إذا كانت المستطيلات متقاربة أي أنها ذات موضع وأحجام متقاربة (حتى دلتا).

### parse {#parse-java.lang.String-}
حاول تحليل السلسلة واستخراج مكوّنات المستطيل llx، lly، urx، ury منها.

### rotate {#rotate-com.aspose.pdf.Rotation-}
دوّر المستطيل بالزاوية المحددة.

### rotateAngle {#rotateAngle-int-}
```
public void rotateAngle(int angle)
```

دوّر المستطيل بالزاوية المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle |  | زاوية الدوران بالدرجات بين 0 و 360. |

### setLLX {#setLLX-double-}
```
public void setLLX(double value)
```

يضبط إحداثي X للزاوية السفلية اليسرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setLLY {#setLLY-double-}
```
public void setLLY(double value)
```

يضبط إحداثي Y للزاوية السفلية اليسرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setURX {#setURX-double-}
```
public void setURX(double value)
```

يضبط إحداثي X للزاوية العليا اليمنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setURY {#setURY-double-}
```
public void setURY(double value)
```

يضبط إحداثي Y للزاوية العليا اليمنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### toArray {#toArray-com.aspose.pdf.engine.data.ITrailerable-}


### toPoints {#toPoints--}
```
public final Point [] toPoints()
```

يحوّل المستطيل إلى مصفوفة من النقاط ("QuadPoints").

**Returns:**
مصفوفة من النقاط.

### toRect {#toRect--}
```
public Rectangle toRect()
```

يحوّل المستطيل إلى كائن من System.Drawing.Rectangle. يتم تقصير المواقع والأحجام ذات الفاصلة العائمة.

**Returns:**
نتيجة التحويل.

### toString {#toString--}
```
public String toString()
```

يحصل على تمثيل المستطيل كسلسلة.

**Returns:**
السلسلة ذات التنسيق llx,lly,urx,ury.
