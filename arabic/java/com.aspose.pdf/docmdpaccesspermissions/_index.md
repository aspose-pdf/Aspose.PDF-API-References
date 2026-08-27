---
title: "DocMDPAccessPermissions"
linktitle: "DocMDPAccessPermissions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "أذونات الوصول الممنوحة لهذا المستند. القيم الصالحة هي: 1 - لا يُسمح بأي تغييرات على المستند؛ أي تغيير على المستند يبطل التوقيع. 2 -."
type: docs
weight: 1010
url: /ar/java/com.aspose.pdf/docmdpaccesspermissions/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocMDPAccessPermissions > com.aspose.pdf.DocMDPAccessPermissions, java.lang.Enum < DocMDPAccessPermissions >, com.aspose.pdf.DocMDPAccessPermissions

**All Implemented Interfaces:**
Serializable, Comparable < DocMDPAccessPermissions >

```
public enum DocMDPAccessPermissions extends Enum < DocMDPAccessPermissions >
```

أذونات الوصول الممنوحة لهذا المستند. القيم الصالحة هي: 1 - لا يُسمح بأي تغييرات على المستند؛ أي تعديل على المستند يبطل التوقيع. 2 - التغييرات المسموح بها هي ملء النماذج، إنشاء قوالب الصفحات، والتوقيع؛ التغييرات الأخرى تبطل التوقيع. 3 - التغييرات المسموح بها هي نفسها كما في 2، بالإضافة إلى إنشاء التعليقات التوضيحية، حذفها وتعديلها؛ التغييرات الأخرى تبطل التوقيع.

## الحقول

| حقل | الوصف |
| --- | --- |
| [AnnotationModification](#AnnotationModification) | 3 - التغييرات المسموح بها هي نفسها كما في 2، بالإضافة إلى إنشاء التعليقات التوضيحية، حذفها، وتعديلها؛ أي تغييرات أخرى تبطل التوقيع. |
| [FillingInForms](#FillingInForms) | 2 - التغييرات المسموح بها هي تعبئة النماذج، إنشاء قوالب الصفحات، والتوقيع؛ أي تغييرات أخرى تبطل التوقيع. |
| [NoChanges](#NoChanges) | 1 - لا يُسمح بأي تغييرات على المستند؛ أي تغيير على المستند يبطل التوقيع. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | يعيد ثابت التعداد لهذا النوع بالاسم المحدد. |
| [values](#values--) | يعيد مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه. |

### AnnotationModification {#AnnotationModification}
```
public static final DocMDPAccessPermissions AnnotationModification
```

3 - التغييرات المسموح بها هي نفسها كما في 2، بالإضافة إلى إنشاء التعليقات التوضيحية، حذفها، وتعديلها؛ أي تغييرات أخرى تبطل التوقيع.

### FillingInForms {#FillingInForms}
```
public static final DocMDPAccessPermissions FillingInForms
```

2 - التغييرات المسموح بها هي تعبئة النماذج، إنشاء قوالب الصفحات، والتوقيع؛ أي تغييرات أخرى تبطل التوقيع.

### NoChanges {#NoChanges}
```
public static final DocMDPAccessPermissions NoChanges
```

1 - لا يُسمح بأي تغييرات على المستند؛ أي تغيير على المستند يبطل التوقيع.

### getByValue {#getByValue-int-}
```
public static DocMDPAccessPermissions getByValue(int value)
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
public static DocMDPAccessPermissions [] values()
```

يعيد مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه.

**Returns:**
مصفوفة تحتوي على ثوابت هذا النوع من التعداد، بالترتيب الذي تم إعلانه
