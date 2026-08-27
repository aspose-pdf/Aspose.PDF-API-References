---
title: "Signature.Verify"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Signature. تحقق من المستند بالنسبة لهذا التوقيع وأرجع true إذا كان المستند صالحًا أو false otherwise"
type: docs
weight: 170
url: /ar/net/aspose.pdf.forms/signature/verify/
---
## Verify() {#verify}

تحقق من صحة المستند بالنسبة لهذا التوقيع وأرجع true إذا كان المستند صالحًا وإلا false.

```csharp
public bool Verify()
```

### قيمة الإرجاع

true إذا كان المستند صالحًا.

### انظر أيضًا

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(ValidationOptions, out ValidationResult) {#verify_1}

تحقق من صحة المستند بالنسبة لهذا التوقيع وأرجع true إذا كان المستند صالحًا وإلا false.

```csharp
public bool Verify(ValidationOptions options, out ValidationResult validationResult)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| options | ValidationOptions | خيارات التحقق. |
| validationResult | ValidationResult& | نتيجة التحقق من الشهادة. |

### قيمة الإرجاع

true إذا كان المستند صالحًا.

### انظر أيضًا

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(X509Certificate2, ValidationOptions, out ValidationResult) {#verify_2}

تحقق من صحة المستند بالنسبة لهذا التوقيع وأرجع true إذا كان المستند صالحًا وإلا false. يتم إجراء التحقق باستخدام شهادة المفتاح العام الخارجية.

```csharp
public bool Verify(X509Certificate2 publicKeyCertificate, ValidationOptions options, 
    out ValidationResult validationResult)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| publicKeyCertificate | X509Certificate2 | شهادة المفتاح العام للتحقق. |
| options | ValidationOptions | خيارات التحقق. |
| validationResult | ValidationResult& | نتيجة التحقق من الشهادة. |

### قيمة الإرجاع

true إذا كان المستند صالحًا.

### انظر أيضًا

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


