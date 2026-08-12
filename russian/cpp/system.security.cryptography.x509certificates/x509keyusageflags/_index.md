---
title: "System::Security::Cryptography::X509Certificates::X509KeyUsageFlags enum"
linktitle: "X509KeyUsageFlags"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::X509Certificates::X509KeyUsageFlags enum. Определяет, как можно использовать ключ сертификата в C++."
type: docs
weight: 2200
url: /ru/cpp/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags enum


Определяет, как можно использовать ключ сертификата.

```cpp
enum class X509KeyUsageFlags : int32_t
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | 0 | Нет параметров использования ключа. |
| EncipherOnly | 1 | Ключ может использоваться только для шифрования. |
| CrlSign | 2 | Ключ может использоваться для подписи списка отзыва сертификатов. |
| KeyCertSign | 4 | Ключ может использоваться для подписи сертификатов. |
| KeyAgreement | 8 | Ключ может использоваться для определения согласования ключей. |
| DataEncipherment | 16 | Ключ может использоваться для шифрования данных. |
| KeyEncipherment | 32 | Ключ может использоваться для шифрования ключа. |
| NonRepudiation | 64 | Ключ может использоваться для аутентификации. |
| DigitalSignature | 128 | Ключ может использоваться как цифровая подпись. |
| DecipherOnly | 32768 | Ключ может использоваться только для дешифрования. |

## См. также

* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
