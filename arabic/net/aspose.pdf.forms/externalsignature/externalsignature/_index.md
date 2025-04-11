---
title: ExternalSignature.ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: مُنشئ ExternalSignature. ينشئ توقيع PKCS7 مفصول باستخدام X509Certificate2. يدعم بطاقات USB الذكية بدون مفاتيح خاصة قابلة للتصدير
type: docs
weight: 10
url: /ar/net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

ينشئ توقيع PKCS#7 `(مفصول)` باستخدام X509Certificate2. يدعم بطاقات USB الذكية، الرموز بدون مفاتيح خاصة قابلة للتصدير.

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | الشهادة مع المفتاح الخاص. |

## Remarks

سيتم اختيار خوارزمية التجزئة تلقائيًا بناءً على بيانات مفتاح الشهادة.

### See Also

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, DigestHashAlgorithm) {#constructor_1}

ينشئ توقيع PKCS#7 `(مفصول)` باستخدام X509Certificate2. يدعم بطاقات USB الذكية، الرموز بدون مفاتيح خاصة قابلة للتصدير.

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | الشهادة مع المفتاح الخاص. |
| digestHashAlgorithm | DigestHashAlgorithm | خوارزمية التجزئة لتوقيع مستند. |

### See Also

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

ينشئ توقيع PKCS#7 باستخدام X509Certificate2. يدعم بطاقات USB الذكية، الرموز بدون مفاتيح خاصة قابلة للتصدير.

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | الشهادة مع المفتاح الخاص. |
| detached | Boolean | صحيح إذا كان يجب أن يكون التوقيع مفصولًا، خلاف ذلك خطأ. |

## Remarks

إذا تم تعيين المفصول إلى خطأ، ستظل خوارزمية التجزئة دائمًا `SHA1`. خلاف ذلك، سيتم اختيار خوارزمية التجزئة تلقائيًا بناءً على بيانات مفتاح الشهادة (انظر تلقائي).

### See Also

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_4}

ينشئ توقيع PKCS#7 باستخدام X509Certificate2 كسلسلة base64.

```csharp
public ExternalSignature(string base64, bool detached)
```

| Parameter | Type | Description |
| --- | --- | --- |
| base64 | String | X509Certificate2 كسلسلة base64. |
| detached | Boolean | صحيح إذا كان يجب أن يكون التوقيع مفصولًا، خلاف ذلك خطأ. |

## Remarks

إذا تم تعيين المفصول إلى خطأ، ستظل خوارزمية التجزئة دائمًا `SHA1`. خلاف ذلك، سيتم اختيار خوارزمية التجزئة تلقائيًا بناءً على بيانات مفتاح الشهادة (انظر تلقائي).

### See Also

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, DigestHashAlgorithm) {#constructor_3}

ينشئ توقيع PKCS#7 `(مفصول)` باستخدام X509Certificate2 كسلسلة base64.

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| Parameter | Type | Description |
| --- | --- | --- |
| base64 | String | X509Certificate2 كسلسلة base64. |
| digestHashAlgorithm | DigestHashAlgorithm | خوارزمية التجزئة لتوقيع مستند. |

### See Also

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)