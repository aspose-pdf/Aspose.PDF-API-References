---
title: "Signature.Verify"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Signature. Проверяет документ относительно этой подписи и возвращает true, если документ действителен, иначе false."
type: docs
weight: 170
url: /ru/net/aspose.pdf.forms/signature/verify/
---
## Verify() {#verify}

Проверяет документ относительно этой подписи и возвращает true, если документ действителен, иначе false.

```csharp
public bool Verify()
```

### Возвращаемое значение

true, если документ действителен.

### См. также

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(ValidationOptions, out ValidationResult) {#verify_1}

Проверяет документ относительно этой подписи и возвращает true, если документ действителен, иначе false.

```csharp
public bool Verify(ValidationOptions options, out ValidationResult validationResult)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | ValidationOptions | Параметры проверки. |
| validationResult | ValidationResult& | Результат проверки сертификата. |

### Возвращаемое значение

true, если документ действителен.

### См. также

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(X509Certificate2, ValidationOptions, out ValidationResult) {#verify_2}

Проверяет документ относительно этой подписи и возвращает true, если документ действителен, иначе false. Проверка выполняется с использованием внешнего сертификата открытого ключа.

```csharp
public bool Verify(X509Certificate2 publicKeyCertificate, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| publicKeyCertificate | X509Certificate2 | Сертификат открытого ключа для проверки. |
| options | ValidationOptions | Параметры проверки. |
| validationResult | ValidationResult& | Результат проверки сертификата. |

### Возвращаемое значение

true, если документ действителен.

### См. также

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


