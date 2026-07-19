---
title: "System::Security::Cryptography::X509Certificates::X500DistinguishedNameFlags enum"
linktitle: "X500DistinguishedNameFlags"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::X509Certificates::X500DistinguishedNameFlags enum. Правила форматирования отличительного имени сертификата X509 в C++."
type: docs
weight: 1700
url: /ru/cpp/system.security.cryptography.x509certificates/x500distinguishednameflags/
---
## X500DistinguishedNameFlags enum


Правила форматирования отличительного имени X509‑сертификата.

```cpp
enum class X500DistinguishedNameFlags
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | 0 | Нет особых характеристик. |
| Обратный | 1 | Имя зарезервировано. |
| UseSemicolons | 16 | Использовать точки с запятой. |
| DoNotUsePlusSign | 32 | Имя не использует знак плюс. |
| DoNotUseQuotes | 64 | Отключает кавычки в имени. |
| UseCommas | 128 | Разрешает использование запятых. |
| UseNewLines | 256 | Разрешает использование новых строк. |
| UseUTF8Encoding | 4096 | Переключается с использования Unicode на использование кодировки UTF-8. |
| UseT61Encoding | 8192 | Переключается на кодировку T61. |
| ForceUTF8Encoding | 16384 | Принудительно использует UTF-8 при кодировании конкретных ключей X500. |

## См. также

* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
