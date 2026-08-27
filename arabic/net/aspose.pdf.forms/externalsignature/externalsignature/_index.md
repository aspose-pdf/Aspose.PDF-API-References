---
title: "ExternalSignature.ExternalSignature"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "منشئ ExternalSignature. ينشئ توقيع PKCS7 منفصل باستخدام X509Certificate2. يدعم بطاقات ذكية USB دون مفاتيح خاصة قابلة للتصدير"
type: docs
weight: 10
url: /ar/net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

يُنشئ توقيع PKCS#7 منفصل `(detached)` باستخدام X509Certificate2. يدعم بطاقات usb الذكية، والرموز دون مفاتيح خاصة قابلة للتصدير.

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| شهادة | X509Certificate2 | الشهادة مع المفتاح الخاص. |

## ملاحظات

سيتم اختيار خوارزمية التجزئة تلقائيًا بناءً على بيانات مفتاح الشهادة.

### انظر أيضًا

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, DigestHashAlgorithm) {#constructor_1}

يُنشئ توقيع PKCS#7 منفصل `(detached)` باستخدام X509Certificate2. يدعم بطاقات usb الذكية، والرموز دون مفاتيح خاصة قابلة للتصدير.

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| شهادة | X509Certificate2 | الشهادة مع المفتاح الخاص. |
| digestHashAlgorithm | DigestHashAlgorithm | خوارزمية التجزئة لتوقيع مستند. |

### انظر أيضًا

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

ينشئ توقيع PKCS#7 منفصل باستخدام X509Certificate2. يدعم بطاقات ذكية USB، ورموز بدون مفاتيح خاصة قابلة للتصدير.

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| شهادة | X509Certificate2 | الشهادة مع المفتاح الخاص. |
| منفصل | Boolean | صحيح إذا كان يجب أن يكون التوقيع منفصلاً، وإلا خطأ. |

## ملاحظات

عند ضبط منفصل إلى false، ستكون خوارزمية التجزئة دائمًا `SHA1`. وإلا، سيتم اختيار خوارزمية التجزئة تلقائيًا بناءً على بيانات مفتاح الشهادة (انظر Auto).

### انظر أيضًا

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_4}

يُنشئ توقيع PKCS#7 باستخدام X509Certificate2 كسلسلة base64.

```csharp
public ExternalSignature(string base64, bool detached)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| base64 | String | X509Certificate2 كسلسلة base64. |
| منفصل | Boolean | صحيح إذا كان يجب أن يكون التوقيع منفصلاً، وإلا خطأ. |

## ملاحظات

عند ضبط منفصل إلى false، ستكون خوارزمية التجزئة دائمًا `SHA1`. وإلا، سيتم اختيار خوارزمية التجزئة تلقائيًا بناءً على بيانات مفتاح الشهادة (انظر Auto).

### انظر أيضًا

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, DigestHashAlgorithm) {#constructor_3}

يُنشئ توقيع PKCS#7 `(detached)` باستخدام X509Certificate2 كسلسلة base64.

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| base64 | String | X509Certificate2 كسلسلة base64. |
| digestHashAlgorithm | DigestHashAlgorithm | خوارزمية التجزئة لتوقيع مستند. |

### انظر أيضًا

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


