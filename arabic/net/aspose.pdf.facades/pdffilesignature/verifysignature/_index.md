---
title: "PdfFileSignature.VerifySignature"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileSignature. تتحقق من صحة التوقيع"
type: docs
weight: 320
url: /ar/net/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## VerifySignature(SignatureName) {#verifysignature}

يفحص صلاحية التوقيع.

```csharp
public bool VerifySignature(SignatureName signName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| signName | SignatureName | اسم التوقيع. |

### قيمة الإرجاع

إرجاع نتيجة من نوع bool.

### انظر أيضًا

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, ValidationOptions, out ValidationResult) {#verifysignature_1}

يفحص صلاحية التوقيع.

```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| signName | SignatureName | اسم التوقيع. |
| options | ValidationOptions | خيارات التحقق. |
| validationResult | ValidationResult& | نتيجة التحقق من الشهادة. |

### قيمة الإرجاع

إرجاع نتيجة من نوع bool.

## ملاحظات

تتيح لك هذه الطريقة التحقق من شهادة التوقيع باستخدام OCSP و/أو CRL (قائمة إبطال الشهادات) للتحقق من الإبطال. لا تقوم هذه الطريقة بالتحقق من سلسلة الشهادة وصلاحيتها، لكنها تتحقق مما إذا كانت الشهادة النهائية قد تم إبطالها.

### انظر أيضًا

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult) {#verifysignature_3}

يفحص صلاحية التوقيع. يتم إجراء التحقق باستخدام شهادة المفتاح العام الخارجية.

```csharp
public bool VerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate, 
    ValidationOptions options, out ValidationResult validationResult)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| signName | SignatureName | اسم التوقيع. |
| publicKeyCertificate | X509Certificate2 | شهادة المفتاح العام للتحقق. |
| options | ValidationOptions | خيارات التحقق. |
| validationResult | ValidationResult& | نتيجة التحقق من الشهادة. |

### قيمة الإرجاع

إرجاع نتيجة من نوع bool.

## ملاحظات

تتيح لك هذه الطريقة التحقق من شهادة التوقيع باستخدام OCSP و/أو CRL (قائمة إبطال الشهادات) للتحقق من الإبطال. لا تقوم هذه الطريقة بالتحقق من سلسلة الشهادة وصلاحيتها، لكنها تتحقق مما إذا كانت الشهادة النهائية قد تم إبطالها.

### انظر أيضًا

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, X509Certificate2) {#verifysignature_2}

يفحص صلاحية التوقيع. يتم إجراء التحقق باستخدام شهادة المفتاح العام الخارجية.

```csharp
public bool VerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| signName | SignatureName | اسم التوقيع. |
| publicKeyCertificate | X509Certificate2 | شهادة المفتاح العام للتحقق. |

### قيمة الإرجاع

إرجاع نتيجة من نوع bool.

### انظر أيضًا

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


