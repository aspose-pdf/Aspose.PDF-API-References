---
title: "PageCoordinateType"
linktitle: "PageCoordinateType"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يصف نوع إحداثيات الصفحة. MediaBox = 0 CropBox = 1"
type: docs
weight: 3350
url: /ar/java/com.aspose.pdf/pagecoordinatetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PageCoordinateType > com.aspose.pdf.PageCoordinateType, java.lang.Enum < PageCoordinateType >, com.aspose.pdf.PageCoordinateType

**All Implemented Interfaces:**
Serializable, Comparable < PageCoordinateType >

```
public enum PageCoordinateType extends Enum < PageCoordinateType >
```

يصف نوع إحداثيات الصفحة. MediaBox = 0 CropBox = 1

## الحقول

| حقل | الوصف |
| --- | --- |
| [CropBox](#CropBox) | تحدد CropBox المنطقة التي يجب قص محتويات الصفحة إليها. |
| [MediaBox](#MediaBox) | يُستخدم MediaBox لتحديد عرض وارتفاع الصفحة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | يعيد ثابت التعداد لهذا النوع بالاسم المحدد. |
| [values](#values--) | يعيد مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه. |

### CropBox {#CropBox}
```
public static final PageCoordinateType CropBox
```

تحدد CropBox المنطقة التي يجب قص محتويات الصفحة إليها.

### MediaBox {#MediaBox}
```
public static final PageCoordinateType MediaBox
```

يُستخدم MediaBox لتحديد عرض وارتفاع الصفحة.

### getByValue {#getByValue-int-}
```
public static PageCoordinateType getByValue(int value)
```



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
يعيد ثابت التعداد لهذا النوع بالاسم المحدد.

### values {#values--}
```
public static PageCoordinateType [] values()
```

يعيد مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه.

**Returns:**
مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه
