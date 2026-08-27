---
title: "ReplyType"
linktitle: "ReplyType"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يسرد أنواع العلاقات (\"نوع الرد\") بين التعليق والتعليق المحدد بواسطة InReplyTo."
type: docs
weight: 4210
url: /ar/java/com.aspose.pdf/replytype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ReplyType > com.aspose.pdf.ReplyType, java.lang.Enum < ReplyType >, com.aspose.pdf.ReplyType

**All Implemented Interfaces:**
Serializable, Comparable < ReplyType >

```
public enum ReplyType extends Enum < ReplyType >
```

يسرد أنواع العلاقات (\"نوع الرد\") بين التعليق التوضيحي والواحد المحدد بواسطة InReplyTo.

## الحقول

| حقل | الوصف |
| --- | --- |
| [Group](#Group) | يتم تجميع التعليق مع التعليق المحدد بواسطة InReplyTo. |
| [Reply](#Reply) | يُعتبر التعليق ردًا على التعليق المحدد بواسطة InReplyTo. |
| [Undefined](#Undefined) | علاقة غير معرفة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | يعيد ثابت التعداد لهذا النوع بالاسم المحدد. |
| [values](#values--) | يعيد مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه. |

### Group {#Group}
```
public static final ReplyType Group
```

يتم تجميع التعليق مع التعليق المحدد بواسطة InReplyTo.

### Reply {#Reply}
```
public static final ReplyType Reply
```

يُعتبر التعليق ردًا على التعليق المحدد بواسطة InReplyTo.

### Undefined {#Undefined}
```
public static final ReplyType Undefined
```

علاقة غير معرفة.

### getByValue {#getByValue-int-}
```
public static ReplyType getByValue(int value)
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
public static ReplyType [] values()
```

يعيد مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه.

**Returns:**
مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه
