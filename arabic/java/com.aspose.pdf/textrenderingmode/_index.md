---
title: "TextRenderingMode"
linktitle: "TextRenderingMode"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "وضعية عرض النص، Tmode، تحدد ما إذا كان إظهار النص سيؤدي إلى رسم مخططات الحروف، تعبئتها، استخدامها كحدود قص، أو مزيج من الثلاثة."
type: docs
weight: 5240
url: /ar/java/com.aspose.pdf/textrenderingmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextRenderingMode > com.aspose.pdf.TextRenderingMode, java.lang.Enum < TextRenderingMode >, com.aspose.pdf.TextRenderingMode

**All Implemented Interfaces:**
Serializable, Comparable < TextRenderingMode >

```
public enum TextRenderingMode extends Enum < TextRenderingMode >
```

وضعية عرض النص، Tmode، تحدد ما إذا كان إظهار النص سيؤدي إلى رسم مخططات الحروف، تعبئتها، استخدامها كحدود قص، أو مزيج من الثلاثة.

## الحقول

| حقل | الوصف |
| --- | --- |
| [AddPathToClipping](#AddPathToClipping) | أضف النص إلى المسار للقص. |
| [FillText](#FillText) | املأ النص. |
| [FillTextAndAddPathToClipping](#FillTextAndAddPathToClipping) | املأ النص وأضفه إلى المسار للقص (انظر 9.3.6، "وضع عرض النص"). |
| [FillThenStrokeText](#FillThenStrokeText) | املأ، ثم ارسم النص. |
| [FillThenStrokeTextAndAddPathToClipping](#FillThenStrokeTextAndAddPathToClipping) | املأ، ثم ارسم النص وأضفه إلى المسار للقص. |
| [Invisible](#Invisible) | لا ملء ولا رسم للنص (غير مرئي). |
| [StrokeText](#StrokeText) | ارسم النص. |
| [StrokeTextAndAddPathToClipping](#StrokeTextAndAddPathToClipping) | ارسم النص وأضفه إلى المسار للقص. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-int-) |  |
| [valueOf](#valueOf-java.lang.String-) | يعيد ثابت التعداد لهذا النوع بالاسم المحدد. |
| [values](#values--) | يعيد مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه. |

### AddPathToClipping {#AddPathToClipping}
```
public static final TextRenderingMode AddPathToClipping
```

أضف النص إلى المسار للقص.

### FillText {#FillText}
```
public static final TextRenderingMode FillText
```

املأ النص.

### FillTextAndAddPathToClipping {#FillTextAndAddPathToClipping}
```
public static final TextRenderingMode FillTextAndAddPathToClipping
```

املأ النص وأضفه إلى المسار للقص (انظر 9.3.6، "وضع عرض النص").

### FillThenStrokeText {#FillThenStrokeText}
```
public static final TextRenderingMode FillThenStrokeText
```

املأ، ثم ارسم النص.

### FillThenStrokeTextAndAddPathToClipping {#FillThenStrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode FillThenStrokeTextAndAddPathToClipping
```

املأ، ثم ارسم النص وأضفه إلى المسار للقص.

### Invisible {#Invisible}
```
public static final TextRenderingMode Invisible
```

لا ملء ولا رسم للنص (غير مرئي).

### StrokeText {#StrokeText}
```
public static final TextRenderingMode StrokeText
```

ارسم النص.

### StrokeTextAndAddPathToClipping {#StrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode StrokeTextAndAddPathToClipping
```

ارسم النص وأضفه إلى المسار للقص.

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-int-}
```
public static TextRenderingMode valueOf(int value)
```



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  |  |

### valueOf {#valueOf-java.lang.String-}
يعيد ثابت التعداد لهذا النوع بالاسم المحدد.

### values {#values--}
```
public static TextRenderingMode [] values()
```

يعيد مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه.

**Returns:**
مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه
