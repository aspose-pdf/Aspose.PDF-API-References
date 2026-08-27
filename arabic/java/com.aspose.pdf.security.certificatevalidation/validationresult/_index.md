---
title: "ValidationResult"
linktitle: "ValidationResult"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل نتيجة عملية التحقق لشهادة. توفر فئة ValidationResult معلومات حول نتيجة التحقق من شهادة، بما في ذلك ما لها."
type: docs
weight: 40
url: /ar/java/com.aspose.pdf.security.certificatevalidation/validationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationResult

```
public final class ValidationResult extends Object
```

يمثل نتيجة عملية التحقق من شهادة. توفر فئة ValidationResult معلومات حول نتيجة التحقق من الشهادة، بما في ذلك حالتها ورسالة تصف أي مشكلات تم مواجهتها أثناء التحقق.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ValidationResult](#ValidationResult--) | ينشئ مثلاً من الفئة {@link ValidationResult}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getMessage](#getMessage--) | يمثل الرسالة المرتبطة بنتيجة التحقق. توفر الخاصية Message سياقًا إضافيًا أو معلومات حول حالة نتيجة التحقق. |
| [getStatus](#getStatus--) | يحصل على حالة عملية التحقق لشهادة. تشير الخاصية Status إلى نتيجة التحقق من الشهادة. القيم الممكنة معرفة في تعداد {@link ValidationStatus}، مثل Valid أو Invalid أو Undefined. يوفر ذلك نظرة على ما إذا كانت الشهادة قد اجتازت فحوصات التحقق أم لا. |
| [setMessage](#setMessage-java.lang.String-) | يمثل الرسالة المرتبطة بنتيجة التحقق. توفر الخاصية Message سياقًا إضافيًا أو معلومات حول حالة نتيجة التحقق. |
| [setStatus](#setStatus-int-) | يحصل على حالة عملية التحقق لشهادة. تشير الخاصية Status إلى نتيجة التحقق من الشهادة. القيم الممكنة معرفة في تعداد {@link ValidationStatus}، مثل Valid أو Invalid أو Undefined. يوفر ذلك نظرة على ما إذا كانت الشهادة قد اجتازت فحوصات التحقق أم لا. |

### ValidationResult {#ValidationResult--}
```
public ValidationResult()
```

ينشئ مثلاً من الفئة {@link ValidationResult}.

### getMessage {#getMessage--}
```
public final String getMessage()
```

يمثل الرسالة المرتبطة بنتيجة التحقق. توفر الخاصية Message سياقًا إضافيًا أو معلومات حول حالة نتيجة التحقق.

**Returns:**
قيمة سلسلة

### getStatus {#getStatus--}
```
public final int getStatus()
```

يحصل على حالة عملية التحقق لشهادة. تشير الخاصية Status إلى نتيجة التحقق من الشهادة. القيم الممكنة معرفة في تعداد {@link ValidationStatus}، مثل Valid أو Invalid أو Undefined. يوفر ذلك نظرة على ما إذا كانت الشهادة قد اجتازت فحوصات التحقق أم لا.

**Returns:**
ValidationStatus عنصر

### setMessage {#setMessage-java.lang.String-}
يمثل الرسالة المرتبطة بنتيجة التحقق. توفر الخاصية Message سياقًا إضافيًا أو معلومات حول حالة نتيجة التحقق.

### setStatus {#setStatus-int-}
```
public final void setStatus(int value)
```

يحصل على حالة عملية التحقق لشهادة. تشير الخاصية Status إلى نتيجة التحقق من الشهادة. القيم الممكنة معرفة في تعداد {@link ValidationStatus}، مثل Valid أو Invalid أو Undefined. يوفر ذلك نظرة على ما إذا كانت الشهادة قد اجتازت فحوصات التحقق أم لا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | ValidationStatus عنصر |
