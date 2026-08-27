---
title: "DocSaveOptions.RecognitionMode"
linktitle: "DocSaveOptions.RecognitionMode"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يسمح بالتحكم في كيفية تحويل مستند PDF إلى مستند معالجة نصية. استخدم وضع RecognitionMode.Textbox عندما لا يكون المستند الناتج سيُستخدم بشكل مكثف."
type: docs
weight: 1050
url: /ar/java/com.aspose.pdf/docsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocSaveOptions.RecognitionMode > com.aspose.pdf.DocSaveOptions.RecognitionMode, java.lang.Enum < DocSaveOptions.RecognitionMode >, com.aspose.pdf.DocSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < DocSaveOptions.RecognitionMode >

```
public static enum DocSaveOptions.RecognitionMode extends Enum < DocSaveOptions.RecognitionMode >
```

يسمح بالتحكم في كيفية تحويل مستند PDF إلى مستند معالجة نصوص. استخدم وضع RecognitionMode.Textbox عندما لا يُنوي تعديل المستند الناتج بشكل كبير لاحقًا. الصناديق النصية سهلة التعديل عندما لا يكون هناك الكثير للقيام به. استخدم وضع RecognitionMode.Flow عندما يحتاج مستند الإخراج إلى تعديل إضافي. الفقرات وخطوط النص في وضع التدفق تسمح بتعديل النص بسهولة، ولكن كائنات التنسيق غير المدعومة ستظهر أسوأ مما هي عليه في وضع RecognitionMode.Textbox.

## الحقول

| حقل | الوصف |
| --- | --- |
| [EnhancedFlow](#EnhancedFlow) | وضع Flow بديل يدعم التعرف على الجداول. |
| [Flow](#Flow) | وضع التعرف الكامل، يقوم المحرك بتجميع وتحليل متعدد المستويات لاستعادة نية مؤلف المستند الأصلي وإنتاج مستند قابل للتحرير إلى أقصى حد. |
| [Textbox](#Textbox) | هذا الوضع سريع ومناسب للحفاظ على المظهر الأصلي لملف PDF إلى أقصى حد، لكن قد تكون قابلية تحرير المستند الناتج محدودة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | يعيد ثابت التعداد لهذا النوع بالاسم المحدد. |
| [values](#values--) | يعيد مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه. |

### EnhancedFlow {#EnhancedFlow}
```
public static final DocSaveOptions.RecognitionMode EnhancedFlow
```

وضع Flow بديل يدعم التعرف على الجداول.

### Flow {#Flow}
```
public static final DocSaveOptions.RecognitionMode Flow
```

وضع التعرف الكامل، يقوم المحرك بتجميع وتحليل متعدد المستويات لاستعادة نية مؤلف المستند الأصلي وإنتاج مستند قابل للتحرير إلى أقصى حد.

### Textbox {#Textbox}
```
public static final DocSaveOptions.RecognitionMode Textbox
```

هذا الوضع سريع ومناسب للحفاظ على المظهر الأصلي لملف PDF إلى أقصى حد، لكن قد تكون قابلية تحرير المستند الناتج محدودة.

### getByValue {#getByValue-int-}
```
public static DocSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
يعيد ثابت التعداد لهذا النوع بالاسم المحدد.

### values {#values--}
```
public static DocSaveOptions.RecognitionMode [] values()
```

يعيد مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه.

**Returns:**
مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه
