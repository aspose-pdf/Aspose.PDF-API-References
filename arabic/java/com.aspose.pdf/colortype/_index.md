---
title: "ColorType"
linktitle: "ColorType"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يحدد نوع اللون للعناصر على الصفحة."
type: docs
weight: 710
url: /ar/java/com.aspose.pdf/colortype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ColorType > com.aspose.pdf.ColorType, java.lang.Enum < ColorType >, com.aspose.pdf.ColorType

**All Implemented Interfaces:**
Serializable, Comparable < ColorType >

```
public enum ColorType extends Enum < ColorType >
```

يحدد نوع اللون للعناصر على الصفحة.

## الحقول

| حقل | الوصف |
| --- | --- |
| [BlackAndWhite](#BlackAndWhite) | نوع اللون الأسود والأبيض. |
| [Grayscale](#Grayscale) | نوع اللون الرمادي. |
| [Rgb](#Rgb) | نوع اللون RGB. |
| [Undefined](#Undefined) | قيمة نوع اللون غير معرفة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getName](#getName-int-) | <p> يعيد اسم السلسلة للقيمة enum. </p> <hr> مثال: <br> {@code String s = ColorType.getName(ColorType.Grayscale); } |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | يعيد ثابت التعداد لهذا النوع بالاسم المحدد. |
| [values](#values--) | يعيد مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه. |

### BlackAndWhite {#BlackAndWhite}
```
public static final ColorType BlackAndWhite
```

نوع اللون الأسود والأبيض.

### Grayscale {#Grayscale}
```
public static final ColorType Grayscale
```

نوع اللون الرمادي.

### Rgb {#Rgb}
```
public static final ColorType Rgb
```

نوع اللون RGB.

### Undefined {#Undefined}
```
public static final ColorType Undefined
```

قيمة نوع اللون غير معرفة.

### getByValue {#getByValue-int-}
```
public static ColorType getByValue(int value)
```



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  |  |

### getName {#getName-int-}
```
public static String getName(int value)
```

<p> يعيد اسم السلسلة للقيمة enum. </p> <hr> مثال: <br> {@code String s = ColorType.getName(ColorType.Grayscale); }

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة التعداد |

**Returns:**
اسم القيمة

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
يعيد ثابت التعداد لهذا النوع بالاسم المحدد.

### values {#values--}
```
public static ColorType [] values()
```

يعيد مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه.

**Returns:**
مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه
