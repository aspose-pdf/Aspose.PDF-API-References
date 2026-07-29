---
title: "PasswordType"
linktitle: "PasswordType"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "هذا التعداد يمثل أنواع كلمات المرور المعروفة المستخدمة في مستندات PDF المحمية بكلمة مرور."
type: docs
weight: 3520
url: /ar/java/com.aspose.pdf/passwordtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PasswordType > com.aspose.pdf.PasswordType, java.lang.Enum < PasswordType >, com.aspose.pdf.PasswordType

**All Implemented Interfaces:**
Serializable, Comparable < PasswordType >

```
public enum PasswordType extends Enum < PasswordType >
```

هذا التعداد يمثل أنواع كلمات المرور المعروفة المستخدمة في مستندات PDF المحمية بكلمة مرور.

## الحقول

| حقل | الوصف |
| --- | --- |
| [Inaccessible](#Inaccessible) | مستند PDF محمي بكلمة مرور ولكن كل من كلمة مرور المستخدم وصاحب الملكية ليست فارغة ولا تم تعريف أي من كلمات المرور أو كلمة المرور المقدمة غير صحيحة. |
| [None](#None) | مستند PDF غير محمي بكلمة مرور. |
| [Owner](#Owner) | تم فتح مستند PDF باستخدام كلمة مرور تغيير الأذونات (وصول كامل). |
| [User](#User) | تم فتح مستند PDF باستخدام كلمة مرور فتح المستند (وصول مقيد). |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | يعيد ثابت التعداد لهذا النوع بالاسم المحدد. |
| [values](#values--) | يعيد مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه. |

### Inaccessible {#Inaccessible}
```
public static final PasswordType Inaccessible
```

مستند PDF محمي بكلمة مرور ولكن كل من كلمة مرور المستخدم وصاحب الملكية ليست فارغة ولا تم تعريف أي من كلمات المرور أو كلمة المرور المقدمة غير صحيحة.

### None {#None}
```
public static final PasswordType None
```

مستند PDF غير محمي بكلمة مرور.

### Owner {#Owner}
```
public static final PasswordType Owner
```

تم فتح مستند PDF باستخدام كلمة مرور تغيير الأذونات (وصول كامل).

### User {#User}
```
public static final PasswordType User
```

تم فتح مستند PDF باستخدام كلمة مرور فتح المستند (وصول مقيد).

### getByValue {#getByValue-int-}
```
public static PasswordType getByValue(int value)
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
public static PasswordType [] values()
```

يعيد مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه.

**Returns:**
مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه
