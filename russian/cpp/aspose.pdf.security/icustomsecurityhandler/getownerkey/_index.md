---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::GetOwnerKey method"
linktitle: "GetOwnerKey"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::GetOwnerKey method. Создает закодированный массив на основе паролей, который будет записан в поле O словаря шифрования. Должен опираться только на переданные аргументы. Пароль пользователя можно вычислить из этого поля, используя пароль владельца. Вызывается во время шифрования для его подготовки и заполнения словаря шифрования. Значение будет доступно в CalculateEncryptionKey для получения ключа из UserKey. Пароли, указанные пользователем при вызове шифрования документа, будут переданы. Пароли могут не быть указаны или может быть указан только один пароль в C++."
type: docs
weight: 1000
url: /ru/cpp/aspose.pdf.security/icustomsecurityhandler/getownerkey/
---
## ICustomSecurityHandler::GetOwnerKey method


Создает закодированный массив на основе паролей, который будет записан в поле O словаря шифрования. Должен опираться только на переданные аргументы. Пароль пользователя можно вычислить из этого поля, используя пароль владельца. Вызывается во время шифрования для его подготовки и заполнения словаря шифрования. Значение будет доступно в [CalculateEncryptionKey](../calculateencryptionkey/) для получения ключа из UserKey. Пароли, указанные пользователем при вызове шифрования документа, будут переданы. Пароли могут не быть указаны или может быть указан только один пароль.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::GetOwnerKey(System::String userPassword, System::String ownerPassword)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | System::String | Пароль пользователя. |
| ownerPassword | System::String | Пароль владельца. |

### ReturnValue

Массив ключа владельца.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
