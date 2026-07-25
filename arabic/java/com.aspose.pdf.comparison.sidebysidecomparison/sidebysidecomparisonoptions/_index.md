---
title: "SideBySideComparisonOptions"
linktitle: "SideBySideComparisonOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة خيارات لمقارنة المستندات مع مخرجات جنبًا إلى جنب."
type: docs
weight: 60
url: /ar/java/com.aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget, com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions

```
public class SideBySideComparisonOptions extends IVentureLicenseTarget
```

يمثل فئة خيارات لمقارنة المستندات مع مخرجات جنبًا إلى جنب.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SideBySideComparisonOptions](#SideBySideComparisonOptions--) | ينشئ مثيلًا لفئة {@link SideBySideComparisonOptions}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAdditionalChangeMarks](#getAdditionalChangeMarks--) | احصل على الخاصية أو اضبطها التي تحدد ما إذا كانت علامات التغيير الإضافية تُعرض. إذا تم الضبط، تُظهر علامات التغيير التي ليست في الصفحة الحالية ولكنها موجودة في صفحة أخرى. إذا كان التغيير يقع بين الكلمات، قد لا يتم وضع العلامة بدقة بالنسبة لحرف المسافة. القيمة الافتراضية هي {@code false}. |
| [getComparisonArea1](#getComparisonArea1--) | احصل على منطقة المقارنة أو اضبطها. تُستخدم للصفحة أو المستند الأول في طريقة المقارنة. لا يمكن ضبط هذا الخيار مع خيارات {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) و {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) . |
| [getComparisonArea2](#getComparisonArea2--) | احصل على منطقة المقارنة أو اضبطها. تُستخدم للصفحة أو المستند الثاني في طريقة المقارنة. لا يمكن ضبط هذا الخيار مع خيارات {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) و {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) . |
| [getComparisonMode](#getComparisonMode--) | يحصل على وضع المقارنة أو يضبطه. القيمة الافتراضية هي {@link ComparisonMode#IgnoreSpaces}. |
| [getDeleteColor](#getDeleteColor--) | يحصل على اللون المستخدم لتمييز المحتوى المحذوف أثناء مقارنة جنبًا إلى جنب. تحدد هذه الخاصية التمثيل البصري للحذف في نتيجة المقارنة. |
| [getExcludeAreas1](#getExcludeAreas1--) | احصل على وضبط مناطق الاستبعاد. تُستخدم للصفحة الأولى أو المستند في طريقة المقارنة. يمكن تعيين هذا الخيار مع {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). لا يمكن تعيين هذا الخيار مع خيار {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}). |
| [getExcludeAreas2](#getExcludeAreas2--) | احصل على وضبط مناطق الاستبعاد. تُستخدم للصفحة الثانية أو المستند في طريقة المقارنة. يمكن تعيين هذا الخيار مع {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). لا يمكن تعيين هذا الخيار مع خيار {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). |
| [getExcludeTables](#getExcludeTables--) | احصل على وضبط الخيار الذي يحدد ما إذا كانت الجداول مستبعدة من المقارنة. لا يمكن تعيين هذا الخيار مع {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) و {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). القيمة الافتراضية هي {@code false}. |
| [getInsertColor](#getInsertColor--) | يحصل على اللون المستخدم لتمييز المحتوى المُدرج أثناء مقارنة جنبًا إلى جنب. تحدد هذه الخاصية التمثيل البصري للإدراج في نتيجة المقارنة. |
| [setAdditionalChangeMarks](#setAdditionalChangeMarks-boolean-) | احصل على الخاصية أو اضبطها التي تحدد ما إذا كانت علامات التغيير الإضافية تُعرض. إذا تم الضبط، تُظهر علامات التغيير التي ليست في الصفحة الحالية ولكنها موجودة في صفحة أخرى. إذا كان التغيير يقع بين الكلمات، قد لا يتم وضع العلامة بدقة بالنسبة لحرف المسافة. القيمة الافتراضية هي {@code false}. |
| [setComparisonArea1](#setComparisonArea1-com.aspose.pdf.Rectangle-) | احصل على منطقة المقارنة أو اضبطها. تُستخدم للصفحة أو المستند الأول في طريقة المقارنة. لا يمكن ضبط هذا الخيار مع خيارات {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) و {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) . |
| [setComparisonArea2](#setComparisonArea2-com.aspose.pdf.Rectangle-) | احصل على منطقة المقارنة أو اضبطها. تُستخدم للصفحة أو المستند الثاني في طريقة المقارنة. لا يمكن ضبط هذا الخيار مع خيارات {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) و {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) . |
| [setComparisonMode](#setComparisonMode-int-) | يحصل على وضع المقارنة أو يضبطه. القيمة الافتراضية هي {@link ComparisonMode#IgnoreSpaces}. |
| [setDeleteColor](#setDeleteColor-com.aspose.pdf.Color-) | يضبط اللون المستخدم لتمييز المحتوى المحذوف أثناء مقارنة جنبًا إلى جنب. تحدد هذه الخاصية التمثيل البصري للحذف في نتيجة المقارنة. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | احصل على وضبط مناطق الاستبعاد. تُستخدم للصفحة الأولى أو المستند في طريقة المقارنة. يمكن تعيين هذا الخيار مع {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). لا يمكن تعيين هذا الخيار مع خيار {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}). |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | احصل على وضبط مناطق الاستبعاد. تُستخدم للصفحة الثانية أو المستند في طريقة المقارنة. يمكن تعيين هذا الخيار مع {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). لا يمكن تعيين هذا الخيار مع خيار {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). |
| [setExcludeTables](#setExcludeTables-boolean-) | احصل على وضبط الخيار الذي يحدد ما إذا كانت الجداول مستبعدة من المقارنة. لا يمكن تعيين هذا الخيار مع {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) و {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). القيمة الافتراضية هي {@code false}. |
| [setInsertColor](#setInsertColor-com.aspose.pdf.Color-) | يضبط اللون المستخدم لتمييز المحتوى المُدرج أثناء مقارنة جنبًا إلى جنب. تحدد هذه الخاصية التمثيل البصري للإدراج في نتيجة المقارنة. |
| [setVentureLicense](#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-) |  |

### SideBySideComparisonOptions {#SideBySideComparisonOptions--}
```
public SideBySideComparisonOptions()
```

ينشئ مثيلًا لفئة {@link SideBySideComparisonOptions}.

### getAdditionalChangeMarks {#getAdditionalChangeMarks--}
```
public final boolean getAdditionalChangeMarks()
```

احصل على الخاصية أو اضبطها التي تحدد ما إذا كانت علامات التغيير الإضافية تُعرض. إذا تم الضبط، تُظهر علامات التغيير التي ليست في الصفحة الحالية ولكنها موجودة في صفحة أخرى. إذا كان التغيير يقع بين الكلمات، قد لا يتم وضع العلامة بدقة بالنسبة لحرف المسافة. القيمة الافتراضية هي {@code false}.

**Returns:**
قيمة منطقية

### getComparisonArea1 {#getComparisonArea1--}
```
public final Rectangle getComparisonArea1()
```

احصل على منطقة المقارنة أو اضبطها. تُستخدم للصفحة أو المستند الأول في طريقة المقارنة. لا يمكن ضبط هذا الخيار مع خيارات {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) و {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) .

**Returns:**
مثيل Rectangle

### getComparisonArea2 {#getComparisonArea2--}
```
public final Rectangle getComparisonArea2()
```

احصل على منطقة المقارنة أو اضبطها. تُستخدم للصفحة أو المستند الثاني في طريقة المقارنة. لا يمكن ضبط هذا الخيار مع خيارات {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) و {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) .

**Returns:**
مثيل Rectangle

### getComparisonMode {#getComparisonMode--}
```
public final int getComparisonMode()
```

يحصل على وضع المقارنة أو يضبطه. القيمة الافتراضية هي {@link ComparisonMode#IgnoreSpaces}.

**Returns:**
عنصر ComparisonMode

### getDeleteColor {#getDeleteColor--}
```
public final Color getDeleteColor()
```

يحصل على اللون المستخدم لتمييز المحتوى المحذوف أثناء مقارنة جنبًا إلى جنب. تحدد هذه الخاصية التمثيل البصري للحذف في نتيجة المقارنة.

**Returns:**
اللون المستخدم لتمييز المحتوى المحذوف أثناء مقارنة جنبًا إلى جنب.

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

احصل على وضبط مناطق الاستبعاد. تُستخدم للصفحة الأولى أو المستند في طريقة المقارنة. يمكن تعيين هذا الخيار مع {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). لا يمكن تعيين هذا الخيار مع خيار {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}).

**Returns:**
مصفوفة من كائنات Rectangle.

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

احصل على وضبط مناطق الاستبعاد. تُستخدم للصفحة الثانية أو المستند في طريقة المقارنة. يمكن تعيين هذا الخيار مع {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). لا يمكن تعيين هذا الخيار مع خيار {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}).

**Returns:**
مصفوفة من كائنات Rectangle.

### getExcludeTables {#getExcludeTables--}
```
public final boolean getExcludeTables()
```

احصل على وضبط الخيار الذي يحدد ما إذا كانت الجداول مستبعدة من المقارنة. لا يمكن تعيين هذا الخيار مع {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) و {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). القيمة الافتراضية هي {@code false}.

**Returns:**
قيمة منطقية

### getInsertColor {#getInsertColor--}
```
public final Color getInsertColor()
```

يحصل على اللون المستخدم لتمييز المحتوى المُدرج أثناء مقارنة جنبًا إلى جنب. تحدد هذه الخاصية التمثيل البصري للإدراج في نتيجة المقارنة.

**Returns:**
اللون المستخدم لتمييز المحتوى المُدرج أثناء مقارنة جنبًا إلى جنب.

### setAdditionalChangeMarks {#setAdditionalChangeMarks-boolean-}
```
public final void setAdditionalChangeMarks(boolean value)
```

احصل على الخاصية أو اضبطها التي تحدد ما إذا كانت علامات التغيير الإضافية تُعرض. إذا تم الضبط، تُظهر علامات التغيير التي ليست في الصفحة الحالية ولكنها موجودة في صفحة أخرى. إذا كان التغيير يقع بين الكلمات، قد لا يتم وضع العلامة بدقة بالنسبة لحرف المسافة. القيمة الافتراضية هي {@code false}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setComparisonArea1 {#setComparisonArea1-com.aspose.pdf.Rectangle-}
احصل على منطقة المقارنة أو اضبطها. تُستخدم للصفحة أو المستند الأول في طريقة المقارنة. لا يمكن ضبط هذا الخيار مع خيارات {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) و {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) .

### setComparisonArea2 {#setComparisonArea2-com.aspose.pdf.Rectangle-}
احصل على منطقة المقارنة أو اضبطها. تُستخدم للصفحة أو المستند الثاني في طريقة المقارنة. لا يمكن ضبط هذا الخيار مع خيارات {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) و {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) .

### setComparisonMode {#setComparisonMode-int-}
```
public final void setComparisonMode(int value)
```

يحصل على وضع المقارنة أو يضبطه. القيمة الافتراضية هي {@link ComparisonMode#IgnoreSpaces}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر ComparisonMode |

### setDeleteColor {#setDeleteColor-com.aspose.pdf.Color-}
يضبط اللون المستخدم لتمييز المحتوى المحذوف أثناء مقارنة جنبًا إلى جنب. تحدد هذه الخاصية التمثيل البصري للحذف في نتيجة المقارنة.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
احصل على وضبط مناطق الاستبعاد. تُستخدم للصفحة الأولى أو المستند في طريقة المقارنة. يمكن تعيين هذا الخيار مع {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). لا يمكن تعيين هذا الخيار مع خيار {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}).

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
احصل على وضبط مناطق الاستبعاد. تُستخدم للصفحة الثانية أو المستند في طريقة المقارنة. يمكن تعيين هذا الخيار مع {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). لا يمكن تعيين هذا الخيار مع خيار {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}).

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

احصل على وضبط الخيار الذي يحدد ما إذا كانت الجداول مستبعدة من المقارنة. لا يمكن تعيين هذا الخيار مع {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) و {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). القيمة الافتراضية هي {@code false}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setInsertColor {#setInsertColor-com.aspose.pdf.Color-}
يضبط اللون المستخدم لتمييز المحتوى المُدرج أثناء مقارنة جنبًا إلى جنب. تحدد هذه الخاصية التمثيل البصري للإدراج في نتيجة المقارنة.

### setVentureLicense {#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-}
