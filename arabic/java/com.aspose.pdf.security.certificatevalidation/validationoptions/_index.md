---
title: "ValidationOptions"
linktitle: "ValidationOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل خيارات التحقق من توقيع رقمي في مستند PDF."
type: docs
weight: 30
url: /ar/java/com.aspose.pdf.security.certificatevalidation/validationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationOptions

```
public final class ValidationOptions extends Object
```

يمثل خيارات التحقق من توقيع رقمي في مستند PDF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ValidationOptions](#ValidationOptions--) | ينشئ مثلاً من الفئة {@link ValidationOptions}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCheckCertificateChain](#getCheckCertificateChain--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب فحص سلسلة الشهادات أثناء عملية التحقق. عندما يتم تعيين الخاصية، سيتم فحص وجود سلسلة من الشهادات، إذا كانت غير موجودة، فإن نتيجة التحقق ستكون {@link ValidationStatus#Undefined}، وهو ما يتطابق مع سلوك Adobe Acrobat. إذا كنت ترغب فقط في فحص حالة الإلغاء عبر الإنترنت، فعيّن الحقل إلى {@code false}. القيمة الافتراضية هي {@code false}. |
| [getRequestTimeout](#getRequestTimeout--) | يحصل أو يعيّن مدة مهلة الانتظار، بالميلي ثانية، للعمليات المتعلقة بالشبكة أثناء عملية التحقق. تحدد الخاصية RequestTimeout الحد الأقصى للوقت الذي يجب أن ينتظره النظام لاستجابة الشبكة عند الوصول إلى الموارد عبر الإنترنت، مثل حالة الإلغاء أو خوادم OCSP. |
| [getValidationMethod](#getValidationMethod--) | يحصل أو يعيّن الطريقة المستخدمة للتحقق من شهادة. |
| [getValidationMode](#getValidationMode--) | يحصل أو يعيّن وضع التحقق للتوقيعات الرقمية في مستند PDF. تحدد الخاصية ValidationMode صرامة عملية التحقق. |
| [setCheckCertificateChain](#setCheckCertificateChain-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب فحص سلسلة الشهادات أثناء عملية التحقق. عندما يتم تعيين الخاصية، سيتم فحص وجود سلسلة من الشهادات، إذا كانت غير موجودة، فإن نتيجة التحقق ستكون {@link ValidationStatus#Undefined}، وهو ما يتطابق مع سلوك Adobe Acrobat. إذا كنت ترغب فقط في فحص حالة الإلغاء عبر الإنترنت، فعيّن الحقل إلى {@code false}. القيمة الافتراضية هي {@code false}. |
| [setRequestTimeout](#setRequestTimeout-int-) | يحصل أو يعيّن مدة مهلة الانتظار، بالميلي ثانية، للعمليات المتعلقة بالشبكة أثناء عملية التحقق. تحدد الخاصية RequestTimeout الحد الأقصى للوقت الذي يجب أن ينتظره النظام لاستجابة الشبكة عند الوصول إلى الموارد عبر الإنترنت، مثل حالة الإلغاء أو خوادم OCSP. |
| [setValidationMethod](#setValidationMethod-int-) | يحصل أو يعيّن الطريقة المستخدمة للتحقق من شهادة. |
| [setValidationMode](#setValidationMode-int-) | يحصل أو يعيّن وضع التحقق للتوقيعات الرقمية في مستند PDF. تحدد الخاصية ValidationMode صرامة عملية التحقق. |

### ValidationOptions {#ValidationOptions--}
```
public ValidationOptions()
```

ينشئ مثلاً من الفئة {@link ValidationOptions}.

### getCheckCertificateChain {#getCheckCertificateChain--}
```
public final boolean getCheckCertificateChain()
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب فحص سلسلة الشهادات أثناء عملية التحقق. عندما يتم تعيين الخاصية، سيتم فحص وجود سلسلة من الشهادات، إذا كانت غير موجودة، فإن نتيجة التحقق ستكون {@link ValidationStatus#Undefined}، وهو ما يتطابق مع سلوك Adobe Acrobat. إذا كنت ترغب فقط في فحص حالة الإلغاء عبر الإنترنت، فعيّن الحقل إلى {@code false}. القيمة الافتراضية هي {@code false}.

**Returns:**
قيمة منطقية

### getRequestTimeout {#getRequestTimeout--}
```
public final int getRequestTimeout()
```

يحصل أو يعيّن مدة مهلة الانتظار، بالميلي ثانية، للعمليات المتعلقة بالشبكة أثناء عملية التحقق. تحدد الخاصية RequestTimeout الحد الأقصى للوقت الذي يجب أن ينتظره النظام لاستجابة الشبكة عند الوصول إلى الموارد عبر الإنترنت، مثل حالة الإلغاء أو خوادم OCSP.

**Returns:**
قيمة int

### getValidationMethod {#getValidationMethod--}
```
public final int getValidationMethod()
```

يحصل أو يعيّن الطريقة المستخدمة للتحقق من شهادة.

**Returns:**
ValidationMethod عنصر

### getValidationMode {#getValidationMode--}
```
public final int getValidationMode()
```

يحصل أو يعيّن وضع التحقق للتوقيعات الرقمية في مستند PDF. تحدد الخاصية ValidationMode صرامة عملية التحقق.

**Returns:**
ValidationMode عنصر

### setCheckCertificateChain {#setCheckCertificateChain-boolean-}
```
public final void setCheckCertificateChain(boolean value)
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب فحص سلسلة الشهادات أثناء عملية التحقق. عندما يتم تعيين الخاصية، سيتم فحص وجود سلسلة من الشهادات، إذا كانت غير موجودة، فإن نتيجة التحقق ستكون {@link ValidationStatus#Undefined}، وهو ما يتطابق مع سلوك Adobe Acrobat. إذا كنت ترغب فقط في فحص حالة الإلغاء عبر الإنترنت، فعيّن الحقل إلى {@code false}. القيمة الافتراضية هي {@code false}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setRequestTimeout {#setRequestTimeout-int-}
```
public final void setRequestTimeout(int value)
```

يحصل أو يعيّن مدة مهلة الانتظار، بالميلي ثانية، للعمليات المتعلقة بالشبكة أثناء عملية التحقق. تحدد الخاصية RequestTimeout الحد الأقصى للوقت الذي يجب أن ينتظره النظام لاستجابة الشبكة عند الوصول إلى الموارد عبر الإنترنت، مثل حالة الإلغاء أو خوادم OCSP.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setValidationMethod {#setValidationMethod-int-}
```
public final void setValidationMethod(int value)
```

يحصل أو يعيّن الطريقة المستخدمة للتحقق من شهادة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | ValidationMethod عنصر |

### setValidationMode {#setValidationMode-int-}
```
public final void setValidationMode(int value)
```

يحصل أو يعيّن وضع التحقق للتوقيعات الرقمية في مستند PDF. تحدد الخاصية ValidationMode صرامة عملية التحقق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | ValidationMode عنصر |
