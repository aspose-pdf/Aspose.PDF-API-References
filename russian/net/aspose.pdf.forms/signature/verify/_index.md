---
title: Signature.Verify
second_title: Aspose.PDF for .NET API Reference
description: Метод подписи. Проверьте документ относительно этой подписи и верните true, если документ действителен, или false в противном случае
type: docs
weight: 170
url: /ru/net/aspose.pdf.forms/signature/verify/
---
## Verify() {#verify}

Проверьте документ относительно этой подписи и верните true, если документ действителен, или false в противном случае.

```csharp
public bool Verify()
```

### Return Value

true, если документ действителен.

### See Also

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(ValidationOptions, out ValidationResult) {#verify_1}

Проверьте документ относительно этой подписи и верните true, если документ действителен, или false в противном случае.

```csharp
public bool Verify(ValidationOptions options, out ValidationResult validationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | ValidationOptions | Параметры проверки. |
| validationResult | ValidationResult& | Результат проверки сертификата. |

### Return Value

true, если документ действителен.

### See Also

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)