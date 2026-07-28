---
title: "ValidationMethod"
linktitle: "ValidationMethod"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет перечисление, определяющее метод, используемый для проверки сертификата."
type: docs
weight: 10
url: /ru/java/com.aspose.pdf.security.certificatevalidation/validationmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMethod, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMethod, com.aspose.ms.System.Enum, com.aspose.pdf.security.certificatevalidation.ValidationMethod

```
public final class ValidationMethod extends com.aspose.ms.System.Enum
```

Представляет перечисление, определяющее метод, используемый для проверки сертификата.

## Поля

| Поле | Описание |
| --- | --- |
| [All](#All) | Использует все доступные методы (OCSP и CRL) для проверки сертификата. |
| [Auto](#Auto) | Автоматически определяет лучший метод проверки сертификата. |
| [Crl](#Crl) | Проверяет сертификаты, используя метод списка отзыва сертификатов (CRL). |
| [Ocsp](#Ocsp) | Использует протокол онлайн‑проверки статуса сертификата (OCSP) для проверки сертификатов. OCSP — это протокол, который предоставляет статус проверки сертификата, напрямую запрашивая у выдающего сертификат центра сертификации (CA). |

### All {#All}
```
public static final int All
```

Использует все доступные методы (OCSP и CRL) для проверки сертификата.

### Auto {#Auto}
```
public static final int Auto
```

Автоматически определяет лучший метод проверки сертификата.

### Crl {#Crl}
```
public static final int Crl
```

Проверяет сертификаты, используя метод списка отзыва сертификатов (CRL).

### Ocsp {#Ocsp}
```
public static final int Ocsp
```

Использует протокол онлайн‑проверки статуса сертификата (OCSP) для проверки сертификатов. OCSP — это протокол, который предоставляет статус проверки сертификата, напрямую запрашивая у выдающего сертификат центра сертификации (CA).
