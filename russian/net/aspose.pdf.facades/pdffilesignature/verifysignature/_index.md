---
title: PdfFileSignature.VerifySignature
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileSignature. Проверяет действительность подписи
type: docs
weight: 310
url: /ru/net/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## VerifySignature(SignatureName) {#verifysignature}

Проверяет действительность подписи.

```csharp
public bool VerifySignature(SignatureName signName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | SignatureName | Имя подписи. |

### Возвращаемое значение

Возвращает результат типа bool.

### См. также

* класс [SignatureName](../../signaturename/)
* класс [PdfFileSignature](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, ValidationOptions, out ValidationResult) {#verifysignature_1}

Проверяет действительность подписи.

```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | SignatureName | Имя подписи. |
| options | ValidationOptions | Параметры проверки. |
| validationResult | ValidationResult& | Результат проверки сертификата. |

### Возвращаемое значение

Возвращает результат типа bool.

## Примечания

Этот метод позволяет проверить сертификат подписи с использованием OCSP и/или CRL (список отозванных сертификатов) на предмет отзыва. Этот метод не проверяет цепочку сертификатов и ее действительность, но проверяет, был ли отозван конечный сертификат.

### См. также

* класс [SignatureName](../../signaturename/)
* класс [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* класс [ValidationResult](../../../aspose.pdf.security/validationresult/)
* класс [PdfFileSignature](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)