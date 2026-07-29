---
title: "ComparisonOptions"
linktitle: "ComparisonOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة خيارات مقارنة مستند PDF."
type: docs
weight: 10
url: /ar/java/com.aspose.pdf.comparison/comparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.ComparisonOptions

```
public class ComparisonOptions extends Object
```

يمثل فئة خيارات مقارنة مستند PDF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ComparisonOptions](#ComparisonOptions--) | ينشئ مثيلًا لفئة {@link ComparisonOptions}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getEditOperationsOrder](#getEditOperationsOrder--) | يسترجع ويضبط ترتيب عمليات التحرير. |
| [getExcludeAreas1](#getExcludeAreas1--) | احصل على مناطق الاستبعاد واضبطها. تُستخدم للصفحة أو المستند الأول في طريقة المقارنة. يمكن ضبط هذا الخيار مع {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). لا يمكن ضبط هذا الخيار مع خيار {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). |
| [getExcludeAreas2](#getExcludeAreas2--) | احصل على مناطق الاستبعاد واضبطها. تُستخدم للصفحة أو المستند الثاني في طريقة المقارنة. يمكن ضبط هذا الخيار مع {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). لا يمكن ضبط هذا الخيار مع خيار {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). |
| [getExtractionArea](#getExtractionArea--) | احصل على المنطقة المستطيلة التي سيتم مقارنة نص الصفحات فيها واضبطها. لا يمكن ضبط هذا الخيار مع خيارات {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) و { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) . |
| [isExcludeTables](#isExcludeTables--) | احصل على الخيار الذي يحدد ما إذا كانت الجداول مستبعدة من المقارنة واضبطه. لا يمكن ضبط هذا الخيار مع خيار {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). القيمة الافتراضية هي {@code false}. |
| [setEditOperationsOrder](#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-) | يسترجع ويضبط ترتيب عمليات التحرير. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | احصل على مناطق الاستبعاد واضبطها. تُستخدم للصفحة أو المستند الأول في طريقة المقارنة. يمكن ضبط هذا الخيار مع {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). لا يمكن ضبط هذا الخيار مع خيار {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | احصل على مناطق الاستبعاد واضبطها. تُستخدم للصفحة أو المستند الثاني في طريقة المقارنة. يمكن ضبط هذا الخيار مع {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). لا يمكن ضبط هذا الخيار مع خيار {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). |
| [setExcludeTables](#setExcludeTables-boolean-) | احصل على الخيار الذي يحدد ما إذا كانت الجداول مستبعدة من المقارنة واضبطه. لا يمكن ضبط هذا الخيار مع خيار {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). القيمة الافتراضية هي {@code false}. |
| [setExtractionArea](#setExtractionArea-com.aspose.pdf.Rectangle-) | احصل على المنطقة المستطيلة التي سيتم مقارنة نص الصفحات فيها واضبطها. لا يمكن ضبط هذا الخيار مع خيارات {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) و { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) . |

### ComparisonOptions {#ComparisonOptions--}
```
public ComparisonOptions()
```

ينشئ مثيلًا لفئة {@link ComparisonOptions}.

### getEditOperationsOrder {#getEditOperationsOrder--}
```
public final EditOperationsOrder getEditOperationsOrder()
```

يسترجع ويضبط ترتيب عمليات التحرير.

**Returns:**
عنصر EditOperationsOrder

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

احصل على مناطق الاستبعاد واضبطها. تُستخدم للصفحة أو المستند الأول في طريقة المقارنة. يمكن ضبط هذا الخيار مع {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). لا يمكن ضبط هذا الخيار مع خيار {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}).

**Returns:**
مصفوفة من كائنات Rectangle.

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

احصل على مناطق الاستبعاد واضبطها. تُستخدم للصفحة أو المستند الثاني في طريقة المقارنة. يمكن ضبط هذا الخيار مع {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). لا يمكن ضبط هذا الخيار مع خيار {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}).

**Returns:**
مصفوفة من كائنات Rectangle.

### getExtractionArea {#getExtractionArea--}
```
public final Rectangle getExtractionArea()
```

احصل على المنطقة المستطيلة التي سيتم مقارنة نص الصفحات فيها واضبطها. لا يمكن ضبط هذا الخيار مع خيارات {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) و { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) .

**Returns:**
مثيل Rectangle

### isExcludeTables {#isExcludeTables--}
```
public final boolean isExcludeTables()
```

احصل على الخيار الذي يحدد ما إذا كانت الجداول مستبعدة من المقارنة واضبطه. لا يمكن ضبط هذا الخيار مع خيار {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). القيمة الافتراضية هي {@code false}.

**Returns:**
قيمة منطقية

### setEditOperationsOrder {#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-}
يسترجع ويضبط ترتيب عمليات التحرير.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
احصل على مناطق الاستبعاد واضبطها. تُستخدم للصفحة أو المستند الأول في طريقة المقارنة. يمكن ضبط هذا الخيار مع {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). لا يمكن ضبط هذا الخيار مع خيار {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}).

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
احصل على مناطق الاستبعاد واضبطها. تُستخدم للصفحة أو المستند الثاني في طريقة المقارنة. يمكن ضبط هذا الخيار مع {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). لا يمكن ضبط هذا الخيار مع خيار {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}).

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

احصل على الخيار الذي يحدد ما إذا كانت الجداول مستبعدة من المقارنة واضبطه. لا يمكن ضبط هذا الخيار مع خيار {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). القيمة الافتراضية هي {@code false}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setExtractionArea {#setExtractionArea-com.aspose.pdf.Rectangle-}
احصل على المنطقة المستطيلة التي سيتم مقارنة نص الصفحات فيها واضبطها. لا يمكن ضبط هذا الخيار مع خيارات {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) و { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) .
