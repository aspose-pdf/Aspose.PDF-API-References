---
title: "System::Security::Cryptography::ECDsa::VerifyHash метод"
linktitle: "VerifyHash"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::ECDsa::VerifyHash метод. Проверяет подпись данных в C++."
type: docs
weight: 1000
url: /ru/cpp/system.security.cryptography/ecdsa/verifyhash/
---
## ECDsa::VerifyHash method


Проверяет подпись данных.

```cpp
virtual bool System::Security::Cryptography::ECDsa::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| хеш | ByteArrayPtr | Хеш, рассчитанный для полученных данных. |
| подпись | ByteArrayPtr | Подпись как получена. |

### ReturnValue

Истина, если подпись действительна, иначе ложь.

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsa](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
