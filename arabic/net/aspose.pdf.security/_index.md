---
title: "Aspose.Pdf.Security"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "تحتوي مساحة الأسماء Aspose.Pdf.Security على فئات تُستخدم للتشفير والتوقيع الرقمي"
type: docs
weight: 210
url: /ar/net/aspose.pdf.security/
---
تحتوي مساحة الاسم **Aspose.Pdf.Security** على فئات تُستخدم للتشفير والتوقيع الرقمي.

## الفئات

| فئة | الوصف |
| --- | --- |
| [CertificateEncryptionOptions](./certificateencryptionoptions/) | تمثل فئة لخيارات تشفير مستند PDF باستخدام طريقة تشفير تعتمد على الشهادة. تُستخدم لفتح مستندات PDF المشفرة |
| [DsaAlgorithmInfo](./dsaalgorithminfo/) | تمثل فئة للمعلومات حول خوارزمية توقيع DSA |
| [EcdsaAlgorithmInfo](./ecdsaalgorithminfo/) | تمثل فئة للمعلومات حول خوارزمية توقيع ECDSA |
| [EncryptionParameters](./encryptionparameters/) | تمثل فئة معلمات التشفير |
| [KeyedSignatureAlgorithmInfo](./keyedsignaturealgorithminfo/) | تمثل فئة للمعلومات حول خوارزمية توقيع مفتاحية |
| [RsaAlgorithmInfo](./rsaalgorithminfo/) | تمثل فئة للمعلومات حول خوارزمية توقيع RSA |
| [SignatureAlgorithmInfo](./signaturealgorithminfo/) | تمثل فئة للمعلومات حول خوارزمية توقيع، بما في ذلك نوعها، المعيار التشفيري، وخوارزمية تجزئة الملخص |
| [SignatureLengthMismatchException](./signaturelengthmismatchexception/) | تمثل الأخطاء التي تحدث أثناء توقيع PDF. يحدث إذا تم استخدام [`SignHash`](../aspose.pdf.forms/signhash/) لتوقيع مستند وكان الطول الفعلي للتوقيع أكبر من ذلك المحدد في خيار [`DefaultSignatureLength`](../aspose.pdf.forms/signature/defaultsignaturelength/). |
| [TimestampAlgorithmInfo](./timestampalgorithminfo/) | تمثل فئة للمعلومات حول خوارزمية توقيع الطابع الزمني |
| [UnknownSignatureAlgorithmInfo](./unknownsignaturealgorithminfo/) | تمثل فئة للمعلومات حول خوارزمية توقيع غير معروفة |
| [ValidationOptions](./validationoptions/) | تمثل خيارات للتحقق من صحة توقيع رقمي في مستند PDF |
| [ValidationResult](./validationresult/) | تمثل نتيجة عملية التحقق من شهادة |
## الواجهات

| واجهة | الوصف |
| --- | --- |
| [ICustomSecurityHandler](./icustomsecurityhandler/) | واجهة معالج الأمان المخصص |
## تعداد

| تعداد | الوصف |
| --- | --- |
| [CryptographicStandard](./cryptographicstandard/) | يمثل المعايير التشفيرية المتاحة لتأمين مستندات PDF. |
| [SignatureAlgorithmType](./signaturealgorithmtype/) | يسرد أنواع خوارزميات التوقيع المستخدمة في التوقيعات الرقمية. |
| [ValidationMethod](./validationmethod/) | يمثل enum يحدد الطريقة المستخدمة للتحقق من صحة الشهادة. |
| [ValidationMode](./validationmode/) | يحدد وضع التحقق لعمليات التحقق من توقيع PDF. |
| [ValidationStatus](./validationstatus/) | يمثل حالة التحقق من صحة الشهادة. |


