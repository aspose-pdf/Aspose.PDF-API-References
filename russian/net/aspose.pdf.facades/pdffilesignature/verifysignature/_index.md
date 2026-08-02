---
title: "PdfFileSignature.VerifySignature"
second_title: "Справочник API Aspose.PDF для .NET"
description: "PdfFileSignature method. Проверяет действительность подписи."
type: docs
weight: 320
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

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

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

Этот метод позволяет проверить подписывающий сертификат с использованием OCSP и/или CRL (списка отзыва сертификатов) на предмет отзыва. Этот метод не проверяет цепочку сертификатов и её действительность, но проверяет, был ли отозван конечный сертификат.

### См. также

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult) {#verifysignature_3}

Проверяет действительность подписи. Проверка выполняется с использованием внешнего сертификата открытого ключа.

```csharp
public bool VerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate, 
    ValidationOptions options, out ValidationResult validationResult)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | SignatureName | Имя подписи. |
| publicKeyCertificate | X509Certificate2 | Сертификат открытого ключа для проверки. |
| options | ValidationOptions | Параметры проверки. |
| validationResult | ValidationResult& | Результат проверки сертификата. |

### Возвращаемое значение

Возвращает результат типа bool.

## Примечания

Этот метод позволяет проверить подписывающий сертификат с использованием OCSP и/или CRL (списка отзыва сертификатов) на предмет отзыва. Этот метод не проверяет цепочку сертификатов и её действительность, но проверяет, был ли отозван конечный сертификат.

### См. также

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, X509Certificate2) {#verifysignature_2}

Проверяет действительность подписи. Проверка выполняется с использованием внешнего сертификата открытого ключа.

```csharp
public bool VerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | SignatureName | Имя подписи. |
| publicKeyCertificate | X509Certificate2 | Сертификат открытого ключа для проверки. |

### Возвращаемое значение

Возвращает результат типа bool.

### См. также

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


