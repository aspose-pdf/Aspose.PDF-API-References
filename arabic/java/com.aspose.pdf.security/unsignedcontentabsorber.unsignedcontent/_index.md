---
title: "UnsignedContentAbsorber.UnsignedContent"
linktitle: "UnsignedContentAbsorber.UnsignedContent"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يحتوي على عناصر المحتوى غير الموقع المستخرجة من مستند PDF. توفر هذه الفئة إمكانية الوصول إلى الصفحات، حقول النماذج، XForms، والتعليقات التوضيحية التي هي جزء من غير الموقع."
type: docs
weight: 50
url: /ar/java/com.aspose.pdf.security/unsignedcontentabsorber.unsignedcontent/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.UnsignedContent

```
public static final class UnsignedContentAbsorber.UnsignedContent extends Object
```

يغلف عناصر المحتوى غير الموقع المستخرجة من مستند PDF. توفر هذه الفئة الوصول إلى الصفحات، حقول النماذج، XForms، والتعليقات التوضيحية التي هي جزء من المحتوى غير الموقع داخل المستند.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAnnotations](#getAnnotations--) | يحصل على قاموس للتعليقات التوضيحية المعدلة التي قد تكون تغيرت أو أضيفت. |
| [getForms](#getForms--) | يحصل على حقول النماذج التي تم تعديلها أو إضافتها بشكل تدريجي. |
| [getPages](#getPages--) | يحصل على قائمة بالصفحات التي يكون محتواها غير موقع أو تم تغييره تدريجيًا. تُعتبر الصفحة مُعدَّلة ولا يتم فحص XForms ولا تظهر في قائمة XForms. |
| [getXForms](#getXForms--) | يحصل على قاموس لكائنات XForm المعدلة التي قد تكون تغيرت، على الرغم من أن الصفحة نفسها لم تتغير (غير موجودة في قائمة الصفحات). |
| [setXForms](#setXForms-java.util.HashMap-) | قاموس لكائنات XForm المعدلة التي قد تكون تغيرت، على الرغم من أن الصفحة نفسها لم تتغير (غير موجودة في قائمة الصفحات). |

### getAnnotations {#getAnnotations--}
```
public final HashMap < Integer , Annotation > getAnnotations()
```

يحصل على قاموس للتعليقات التوضيحية المعدلة التي قد تكون تغيرت أو أضيفت.

**Returns:**
قاموس للتعليقات التوضيحية المعدلة التي قد تكون تغيرت أو أضيفت.

### getForms {#getForms--}
```
public final List < WidgetAnnotation > getForms()
```

يحصل على حقول النماذج التي تم تعديلها أو إضافتها بشكل تدريجي.

**Returns:**
حقول النماذج التي تم تغييرها أو إضافتها تدريجيًا.

### getPages {#getPages--}
```
public final List < Page > getPages()
```

يحصل على قائمة بالصفحات التي يكون محتواها غير موقع أو تم تغييره تدريجيًا. تُعتبر الصفحة مُعدَّلة ولا يتم فحص XForms ولا تظهر في قائمة XForms.

**Returns:**
قائمة بالصفحات التي يكون محتواها غير موقع أو تم تغييره تدريجيًا.

### getXForms {#getXForms--}
```
public final HashMap < Integer , XForm > getXForms()
```

يحصل على قاموس لكائنات XForm المعدلة التي قد تكون تغيرت، على الرغم من أن الصفحة نفسها لم تتغير (غير موجودة في قائمة الصفحات).

**Returns:**
قاموس لكائنات XForm المعدلة التي قد تكون تغيرت، على الرغم من أن الصفحة نفسها لم تتغير (غير موجودة في قائمة الصفحات).

### setXForms {#setXForms-java.util.HashMap-}
قاموس لكائنات XForm المعدلة التي قد تكون تغيرت، على الرغم من أن الصفحة نفسها لم تتغير (غير موجودة في قائمة الصفحات).
