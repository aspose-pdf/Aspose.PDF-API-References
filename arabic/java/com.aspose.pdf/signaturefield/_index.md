---
title: "SignatureField"
linktitle: "SignatureField"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل حقل نموذج التوقيع."
type: docs
weight: 4510
url: /ar/java/com.aspose.pdf/signaturefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Field, com.aspose.pdf.SignatureField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class SignatureField extends Field
```

يمثل حقل نموذج التوقيع.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SignatureField](#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | يُنشئ نسخة جديدة من الفئة {@code SignatureField}. |
| [SignatureField](#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | يُنشئ نسخة جديدة من الفئة {@code SignatureField}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [clear](#clear--) | يزيل كائن التوقيع من الحقل. |
| [extractCertificate](#extractCertificate--) | يستخرج شهادة X.509 الوحيدة بتنسيق DER كتيار. |
| [extractCertificateObject](#extractCertificateObject--) | يستخرج كائن شهادة X.509 الوحيدة. |
| [extractImage](#extractImage--) | يستخرج صورة التوقيع كتيار مُشفّر بصيغة JPEG. |
| [extractImage](#extractImage-com.aspose.pdf.ImageType-) | يستخرج صورة التوقيع كتيار مُشفّر بصيغة JPEG. |
| [getSignature](#getSignature--) | يحصل على كائن التوقيع. يحتوي هذا الكائن على بيانات التوقيع المتعلقة بمعايير التشفير بالمفتاح العام. تمثل الفئات {@code PKCS1} و {@code PKCS7} و {@code PKCS7Detached} جميع أنواع كائنات التوقيع المدعومة. |
| [sign](#sign-com.aspose.pdf.Signature-) | وقّع المستند باستخدام حقل التوقيع هذا. |
| [sign](#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-) | يوقّع المستند باستخدام حقل التوقيع هذا. |

### SignatureField {#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
يُنشئ نسخة جديدة من الفئة {@code SignatureField}.

### SignatureField {#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
يُنشئ نسخة جديدة من الفئة {@code SignatureField}.

### clear {#clear--}
```
public void clear()
```

يزيل كائن التوقيع من الحقل.

### extractCertificate {#extractCertificate--}
```
public InputStream extractCertificate()
```

يستخرج شهادة X.509 الوحيدة بتنسيق DER كتيار.

**Returns:**
إذا تم العثور على الشهادة، تُعيد شهادة X.509 الوحيدة؛ وإلا، null.

### extractCertificateObject {#extractCertificateObject--}
```
public final com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 extractCertificateObject()
```

يستخرج كائن شهادة X.509 الوحيدة.

**Returns:**
إذا تم العثور على الشهادة، تُعيد شهادة X.509 الوحيدة؛ وإلا، null.

### extractImage {#extractImage--}
```
public InputStream extractImage()
```

يستخرج صورة التوقيع كتيار مُشفّر بصيغة JPEG.

**Returns:**
إذا تم العثور على الصورة بنجاح، تُعيد كائن تيار مُشفّر بصيغة JPEG؛ وإلا، null.

### extractImage {#extractImage-com.aspose.pdf.ImageType-}
يستخرج صورة التوقيع كتيار مُشفّر بصيغة JPEG.

**Returns:**
إذا تم العثور على الصورة بنجاح، تُعيد كائن تيار مُشفّر بصيغة JPEG؛ وإلا، null.

### getSignature {#getSignature--}
```
public final Signature getSignature()
```

يحصل على كائن التوقيع. يحتوي هذا الكائن على بيانات التوقيع المتعلقة بمعايير التشفير بالمفتاح العام. تمثل الفئات {@code PKCS1} و {@code PKCS7} و {@code PKCS7Detached} جميع أنواع كائنات التوقيع المدعومة.

**Returns:**
كائن التوقيع

### sign {#sign-com.aspose.pdf.Signature-}
وقّع المستند باستخدام حقل التوقيع هذا.

### sign {#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-}
يوقّع المستند باستخدام حقل التوقيع هذا.
