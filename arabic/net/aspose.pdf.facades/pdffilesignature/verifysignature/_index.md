---
title: PdfFileSignature.VerifySignature
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileSignature. تتحقق من صحة التوقيع
type: docs
weight: 310
url: /ar/net/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## VerifySignature(SignatureName) {#verifysignature}

تتحقق من صحة التوقيع.

```csharp
public bool VerifySignature(SignatureName signName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | SignatureName | اسم التوقيع. |

### Return Value

ترجع نتيجة من نوع bool.

### See Also

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, ValidationOptions, out ValidationResult) {#verifysignature_1}

تتحقق من صحة التوقيع.

```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | SignatureName | اسم التوقيع. |
| options | ValidationOptions | خيارات التحقق. |
| validationResult | ValidationResult& | نتيجة التحقق من الشهادة. |

### Return Value

ترجع نتيجة من نوع bool.

## Remarks

تسمح لك هذه الطريقة بالتحقق من شهادة التوقيع باستخدام OCSP و/أو CRL (قائمة إلغاء الشهادات) للإلغاء. لا تتحقق هذه الطريقة من سلسلة الشهادات وصحتها، لكنها تتحقق مما إذا كانت الشهادة النهائية قد تم إلغاؤها.

### See Also

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)