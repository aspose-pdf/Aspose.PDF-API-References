---
title: "Перечисление ValidationMethod"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Перечисление Aspose.Pdf.Security.ValidationMethod. Представляет перечисление, определяющее метод, используемый для проверки сертификата"
type: docs
weight: 10230
url: /ru/net/aspose.pdf.security/validationmethod/
---
## ValidationMethod enumeration

Представляет перечисление, определяющее метод, используемый для проверки сертификата.

```csharp
public enum ValidationMethod
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Auto | `0` | Автоматически определяет лучший метод проверки сертификата. |
| Ocsp | `1` | Использует протокол Online Certificate Status Protocol (OCSP) для проверки сертификата. OCSP — это протокол, который предоставляет статус проверки сертификата путем прямого запроса к выдающему сертификат Удостоверяющему центру (CA). |
| Crl | `2` | Проверяет сертификаты с использованием метода списка отзыва сертификатов (CRL). |
| All | `3` | Использует все доступные методы (OCSP и CRL) для проверки сертификата. |

### См. также

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


