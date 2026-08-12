---
title: "System::Security::Cryptography::X509Certificates::X509KeyStorageFlags перечисление"
linktitle: "X509KeyStorageFlags"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::X509Certificates::X509KeyStorageFlags перечисление. Определяет, как хранить ключ в C++."
type: docs
weight: 2100
url: /ru/cpp/system.security.cryptography.x509certificates/x509keystorageflags/
---
## X509KeyStorageFlags enum


Определяет, как хранить ключ.

```cpp
enum class X509KeyStorageFlags : int32_t
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| DefaultKeySet | 0 | Использовать набор ключей по умолчанию. |
| UserKeySet | 1 | Использовать хранилище, связанное с пользователем, вместо локального машинного. |
| MachineKeySet | 2 | Использовать локальное машинное хранилище вместо пользовательского. |
| Exportable | 4 | Помечает импортированные ключи как экспортируемые. |
| UserProtected | 8 | Уведомить пользователя, что ключ используется. |
| PersistKeySet | 16 | Ключ сохраняется при импорте сертификата. |

## См. также

* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
