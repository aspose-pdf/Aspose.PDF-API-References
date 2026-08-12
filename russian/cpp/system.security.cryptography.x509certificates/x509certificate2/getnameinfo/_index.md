---
title: "System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo method"
linktitle: "GetNameInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo method. Получает имя субъекта или издателя из сертификата в C++."
type: docs
weight: 2100
url: /ru/cpp/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo method


Получает имя субъекта или издателя из сертификата.

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| name_type | X509NameType | Параметры форматирования имени. |
| for_issuer | bool | Если true, возвращает имя издателя, иначе возвращает имя субъекта. |

### ReturnValue

Отформатированное имя издателя или субъекта.

## См. также

* Class [String](../../../system/string/)
* Enum [X509NameType](../../x509nametype/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
