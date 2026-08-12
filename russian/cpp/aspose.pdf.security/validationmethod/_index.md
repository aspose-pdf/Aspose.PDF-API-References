---
title: "Aspose::Pdf::Security::ValidationMethod enum"
linktitle: "ValidationMethod"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Security::ValidationMethod enum. Представляет перечисление, определяющее метод, используемый для проверки сертификата в C++."
type: docs
weight: 1700
url: /ru/cpp/aspose.pdf.security/validationmethod/
---
## ValidationMethod enum


Представляет перечисление, определяющее метод, используемый для проверки сертификата.

```cpp
enum class ValidationMethod
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Auto | 0 | Автоматически определяет лучший метод проверки сертификата. |
| Ocsp | 1 | Использует протокол Online Certificate Status Protocol (OCSP) для проверки сертификата. OCSP — это протокол, который предоставляет статус проверки сертификата, напрямую запрашивая у выдающего центра сертификации (CA). |
| Crl | 2 | Проверяет сертификаты с использованием метода списка отзыва сертификатов (CRL). |
| Все | 3 | Использует все доступные методы (OCSP и CRL) для проверки сертификата. |

## См. также

* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
