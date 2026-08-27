---
title: "HeadingLevels"
linktitle: "HeadingLevels"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة للعمل مع مستويات العناوين بناءً على حجم الخط."
type: docs
weight: 20
url: /ar/java/com.aspose.pdf.markdownoptions/headinglevels/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.markdownoptions.HeadingLevels

```
public class HeadingLevels extends Object
```

يمثل فئة للعمل مع مستويات العناوين بناءً على حجم الخط.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [HeadingLevels](#HeadingLevels--) | ينشئ نسخة جديدة من الفئة HeadingLevels. |
| [HeadingLevels](#HeadingLevels-double-) | ينشئ نسخة جديدة من الفئة HeadingLevels. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addLevels](#addLevels-java.lang.Iterable-) | يضيف مستويات العناوين. |
| [estimateLevel](#estimateLevel-double-) | يقدّر مستوى الرأس المحتمل. إذا لم يتم العثور على fontSize في قائمة المستويات، سيتم إرجاع المستوى الأقرب إلى قيمة حجم الخط هذه. إذا كان fontSize خارج الحد الأدنى والحد الأقصى لمستويات الرؤوس المحددة، ستعيد الطريقة false. |
| [findLevel](#findLevel-double-int:A-) | يبحث عن المستوى المناسب لحجم الخط المقابل. يبحث عن تطابق دقيق. |
| [getAllLevels](#getAllLevels--) | يحصل على جميع مستويات العناوين. |

### HeadingLevels {#HeadingLevels--}
```
public HeadingLevels()
```

ينشئ نسخة جديدة من الفئة HeadingLevels.

### HeadingLevels {#HeadingLevels-double-}
```
public HeadingLevels(double threshold)
```

ينشئ نسخة جديدة من الفئة HeadingLevels.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold |  | قيمة العتبة لمقارنة أحجام الخطوط. ضمن العتبة، تكون مستويات الرؤوس متساوية. القيمة الافتراضية للعتبة هي 0.01. |

### addLevels {#addLevels-java.lang.Iterable-}
يضيف مستويات العناوين.

### estimateLevel {#estimateLevel-double-}
```
public final int estimateLevel(double fontSize)
```

يقدّر مستوى الرأس المحتمل. إذا لم يتم العثور على fontSize في قائمة المستويات، سيتم إرجاع المستوى الأقرب إلى قيمة حجم الخط هذه. إذا كان fontSize خارج الحد الأدنى والحد الأقصى لمستويات الرؤوس المحددة، ستعيد الطريقة false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontSize |  | حجم الخط. |

**Returns:**
مستوى العنوان.

### findLevel {#findLevel-double-int:A-}
```
public final boolean findLevel(double fontSize, int[] level)
```

يبحث عن المستوى المناسب لحجم الخط المقابل. يبحث عن تطابق دقيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontSize |  | حجم الخط. |
| المستوى |  | مستوى العنوان المقابل لحجم الخط المعطى. |

**Returns:**
False إذا لم يكن fontSize ضمن النطاق المحدد.

### getAllLevels {#getAllLevels--}
```
public final com.aspose.ms.System.Collections.IEnumerable< Double > getAllLevels()
```

يحصل على جميع مستويات العناوين.

**Returns:**
IEnumerable of Double
