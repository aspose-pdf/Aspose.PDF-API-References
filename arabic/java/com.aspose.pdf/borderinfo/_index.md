---
title: "BorderInfo"
linktitle: "BorderInfo"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "هذه الفئة تمثل الحد لعناصر الرسوميات."
type: docs
weight: 370
url: /ar/java/com.aspose.pdf/borderinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BorderInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class BorderInfo extends Object implements com.aspose.ms.System.ICloneable
```

هذه الفئة تمثل الحد لعناصر الرسوميات.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [BorderInfo](#BorderInfo--) | يُنشئ نسخة جديدة من الفئة {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-) | يُنشئ نسخة جديدة من الفئة {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.Color-) | يُنشئ نسخة جديدة من الفئة {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-float-) | يُنشئ نسخة جديدة من الفئة {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-float-com.aspose.pdf.Color-) | يُنشئ نسخة جديدة من الفئة {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.GraphInfo-) | يُنشئ نسخة جديدة من الفئة {@code BorderInfo}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone](#deepClone--) | ينسخ كائن BorderInfo جديد. |
| [getBottom](#getBottom--) | يحصل على الكائن الذي يشير إلى أسفل الحد. |
| [getLeft](#getLeft--) | يحصل على كائن {@code GraphInfo} الذي يشير إلى اليسار من الحد. |
| [getRight](#getRight--) | يحصل على كائن {@code GraphInfo} الذي يشير إلى اليمين من الحد. |
| [getRoundedBorderRadius](#getRoundedBorderRadius--) | يحصل على نصف قطر الحد المستدير. |
| [getTop](#getTop--) | يحصل على كائن {@code GraphInfo} الذي يشير إلى الحد العلوي. |
| [setBottom](#setBottom-com.aspose.pdf.GraphInfo-) | يضبط الكائن الذي يشير إلى أسفل الحد. |
| [setLeft](#setLeft-com.aspose.pdf.GraphInfo-) | يضبط كائن {@code GraphInfo} الذي يشير إلى اليسار من الحد. |
| [setRight](#setRight-com.aspose.pdf.GraphInfo-) | يضبط كائن {@code GraphInfo} الذي يشير إلى اليمين من الحد. |
| [setRoundedBorderRadius](#setRoundedBorderRadius-double-) | يضبط نصف قطر الحد المستدير. |
| [setTop](#setTop-com.aspose.pdf.GraphInfo-) | يضبط كائن {@code GraphInfo} الذي يشير إلى أعلى الحد. |

### BorderInfo {#BorderInfo--}
```
public BorderInfo()
```

يُنشئ نسخة جديدة من الفئة {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-}
```
public BorderInfo(int borderSide)
```

يُنشئ نسخة جديدة من الفئة {@code BorderInfo}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| borderSide |  | يشير إلى معلومات جوانب الحد. على سبيل المثال: (BorderSide.Left \ | BorderSide.Top). |

### BorderInfo {#BorderInfo-int-com.aspose.pdf.Color-}
يُنشئ نسخة جديدة من الفئة {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-float-}
```
public BorderInfo(int borderSide, float borderWidth)
```

يُنشئ نسخة جديدة من الفئة {@code BorderInfo}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| borderSide |  | يشير إلى معلومات جوانب الحد. على سبيل المثال: (BorderSide.Left \ | BorderSide.Top). |
| borderWidth |  | عرض الحد. |

### BorderInfo {#BorderInfo-int-float-com.aspose.pdf.Color-}
يُنشئ نسخة جديدة من الفئة {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-com.aspose.pdf.GraphInfo-}
يُنشئ نسخة جديدة من الفئة {@code BorderInfo}.

### deepClone {#deepClone--}
```
public Object deepClone()
```

ينسخ كائن BorderInfo جديد.

**Returns:**
كائن BorderInfo الجديد.

### getBottom {#getBottom--}
```
public GraphInfo getBottom()
```

يحصل على الكائن الذي يشير إلى أسفل الحد.

**Returns:**
الأسفل

### getLeft {#getLeft--}
```
public GraphInfo getLeft()
```

يحصل على كائن {@code GraphInfo} الذي يشير إلى اليسار من الحد.

**Returns:**
كائن يشير إلى اليسار من الحد.

### getRight {#getRight--}
```
public GraphInfo getRight()
```

يحصل على كائن {@code GraphInfo} الذي يشير إلى اليمين من الحد.

**Returns:**
كائن يشير إلى اليمين من الحد.

### getRoundedBorderRadius {#getRoundedBorderRadius--}
```
public double getRoundedBorderRadius()
```

يحصل على نصف قطر الحد المستدير.

**Returns:**
قيمة

### getTop {#getTop--}
```
public GraphInfo getTop()
```

يحصل على كائن {@code GraphInfo} الذي يشير إلى الحد العلوي.

**Returns:**
كائن يشير إلى الحد العلوي

### setBottom {#setBottom-com.aspose.pdf.GraphInfo-}
يضبط الكائن الذي يشير إلى أسفل الحد.

### setLeft {#setLeft-com.aspose.pdf.GraphInfo-}
يضبط كائن {@code GraphInfo} الذي يشير إلى اليسار من الحد.

### setRight {#setRight-com.aspose.pdf.GraphInfo-}
يضبط كائن {@code GraphInfo} الذي يشير إلى اليمين من الحد.

### setRoundedBorderRadius {#setRoundedBorderRadius-double-}
```
public void setRoundedBorderRadius(double value)
```

يضبط نصف قطر الحد المستدير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setTop {#setTop-com.aspose.pdf.GraphInfo-}
يضبط كائن {@code GraphInfo} الذي يشير إلى أعلى الحد.
