---
title: "UnsignedContentAbsorber.Result"
linktitle: "UnsignedContentAbsorber.Result"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يُغلف نتيجة العملية التي تحاول استخراج المحتوى غير الموقع من مستند PDF. توفر هذه الفئة معلومات حول نجاح العملية، وتفاصيلها."
type: docs
weight: 40
url: /ar/java/com.aspose.pdf.security/unsignedcontentabsorber.result/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.Result

```
public static final class UnsignedContentAbsorber.Result extends Object
```

يغلف نتيجة عملية محاولة استخراج المحتوى غير الموقع من مستند PDF. توفر هذه الفئة معلومات حول نجاح العملية، تفاصيل المحتوى غير الموقع، رسالة تصف النتيجة، وحالة تغطية توقيعات المستند.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCoverage](#getCoverage--) | يحصل على قيمة تشير إلى مدى تغطية المستند بالتوقيعات الرقمية الصالحة. |
| [getMessage](#getMessage--) | يحصل على رسالة تصف نتيجة العملية. |
| [getSuccess](#getSuccess--) | يحصل على قيمة تشير إلى ما إذا كانت عملية استرجاع المحتوى غير الموقع من المستند ناجحة. |
| [getUnsignedContent](#getUnsignedContent--) | يحصل على محتوى غير موقع. |

### getCoverage {#getCoverage--}
```
public final int getCoverage()
```

يحصل على قيمة تشير إلى مدى تغطية المستند بالتوقيعات الرقمية الصالحة.

**Returns:**
قيمة تشير إلى مدى تغطية المستند بالتوقيعات الرقمية الصالحة.

### getMessage {#getMessage--}
```
public final String getMessage()
```

يحصل على رسالة تصف نتيجة العملية.

**Returns:**
رسالة تصف نتيجة العملية.

### getSuccess {#getSuccess--}
```
public final boolean getSuccess()
```

يحصل على قيمة تشير إلى ما إذا كانت عملية استرجاع المحتوى غير الموقع من المستند ناجحة.

**Returns:**
قيمة تشير إلى ما إذا كانت عملية استرجاع المحتوى غير الموقع من المستند ناجحة.

### getUnsignedContent {#getUnsignedContent--}
```
public final UnsignedContentAbsorber.UnsignedContent getUnsignedContent()
```

يحصل على محتوى غير موقع.

**Returns:**
محتوى غير موقع.
