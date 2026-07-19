---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::GetUserKey метод"
linktitle: "GetUserKey"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::GetUserKey method. Создает закодированный массив на основе пароля пользователя''. Это значение обычно используется для проверки, принадлежит ли пароль пользователю или владельцу, и для получения ключа шифрования. Вызывается во время шифрования для его подготовки и заполнения словаря шифрования. Указанный пользователем пароль передаётся в качестве аргумента при вызове шифрования документа в C++."
type: docs
weight: 1100
url: /ru/cpp/aspose.pdf.security/icustomsecurityhandler/getuserkey/
---
## ICustomSecurityHandler::GetUserKey method


Создаёт закодированный массив на основе пароля пользователя. Это значение обычно используется для проверки, принадлежит ли пароль пользователю или владельцу, и для получения ключа шифрования. Вызывается во время шифрования для его подготовки и заполнения словаря шифрования. Указанный пользователем пароль передаётся в качестве аргумента при вызове шифрования документа.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::GetUserKey(System::String userPassword)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | System::String | Пароль пользователя. |

### ReturnValue

Массив пользовательского ключа.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
