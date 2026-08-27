---
title: "ExternalSignature"
linktitle: "ExternalSignature"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "ينشئ توقيع PKCS#7Detached منفصل باستخدام X509Certificate2. يدعم بطاقات ذكية USB، والرموز دون مفاتيح خاصة قابلة للتصدير."
type: docs
weight: 1350
url: /ar/java/com.aspose.pdf/externalsignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature com.aspose.pdf.ExternalSignature, com.aspose.pdf.Signature, com.aspose.pdf.ExternalSignature

```
public class ExternalSignature extends Signature
```

ينشئ توقيع PKCS#7Detached منفصل باستخدام X509Certificate2. يدعم بطاقات ذكية USB، والرموز دون مفاتيح خاصة قابلة للتصدير.

## الحقول

| حقل | الوصف |
| --- | --- |
| [Certificate](#Certificate) | الشهادة مع المفتاح الخاص. |

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ExternalSignature](#ExternalSignature-java.lang.String-boolean-) | ينشئ توقيع PKCS#7 (منفصل) باستخدام X509Certificate2 كسلسلة base64. |
| [ExternalSignature](#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | ينشئ توقيع PKCS#7 {@code (detached)} باستخدام X509Certificate2 كسلسلة base64. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | مهمل. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-) | ينشئ توقيع PKCS#7Detached منفصل باستخدام X509Certificate2. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-) | ينشئ توقيع PKCS#7 (منفصل) باستخدام X509Certificate2. |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | مهمل. |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-) | ينشئ توقيع PKCS#7 (منفصل) باستخدام java.security.cert.X509Certificate و java.security.PrivateKey. |

### Certificate {#Certificate}
```
public com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 Certificate
```

الشهادة مع المفتاح الخاص.

### ExternalSignature {#ExternalSignature-java.lang.String-boolean-}
ينشئ توقيع PKCS#7 (منفصل) باستخدام X509Certificate2 كسلسلة base64.

### ExternalSignature {#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
ينشئ توقيع PKCS#7 {@code (detached)} باستخدام X509Certificate2 كسلسلة base64.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
مهمل.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-}
ينشئ توقيع PKCS#7Detached منفصل باستخدام X509Certificate2.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-}
ينشئ توقيع PKCS#7 (منفصل) باستخدام X509Certificate2.

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
مهمل.

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-}
ينشئ توقيع PKCS#7 (منفصل) باستخدام java.security.cert.X509Certificate و java.security.PrivateKey.
