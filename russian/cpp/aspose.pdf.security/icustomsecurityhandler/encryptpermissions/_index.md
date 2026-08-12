---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::EncryptPermissions method"
linktitle: "EncryptPermissions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::EncryptPermissions method. Шифрует поле разрешений документа''. Результат будет записан в поле словаря шифрования Perms. При открытии документа значение можно получить в EncryptionParameters через поле Perms. Позволяет проверить, изменились ли разрешения документа в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.pdf.security/icustomsecurityhandler/encryptpermissions/
---
## ICustomSecurityHandler::EncryptPermissions method


Шифрует поле разрешений документа. Результат будет записан в поле словаря шифрования Perms. При открытии документа значение можно получить в [EncryptionParameters](../../encryptionparameters/) через поле Perms. Позволяет проверить, изменились ли разрешения документа.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::EncryptPermissions(int32_t permissions)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| разрешения | int32_t | Разрешения документа в целочисленном представлении. |

### ReturnValue

Зашифрованный массив.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
