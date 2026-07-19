---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::Initialize метод"
linktitle: "Initialize"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::Initialize метод. Вызывается для инициализации текущего экземпляра для шифрования. Обратите внимание, что при шифровании он будет заполнен данными переданных свойств ICustomSecurityHandler, а при открытии документа из словаря шифрования. Если метод вызывается во время нового шифрования, то EncryptionParameters::UserKey и EncryptionParameters::OwnerKey будут равны null в C++."
type: docs
weight: 1200
url: /ru/cpp/aspose.pdf.security/icustomsecurityhandler/initialize/
---
## ICustomSecurityHandler::Initialize method


Вызывается для инициализации текущего экземпляра для шифрования. [Note](../../../aspose.pdf/note/) что при шифровании он будет заполнен данными переданных свойств [ICustomSecurityHandler](../), а при открытии документа из словаря шифрования. Если метод вызывается во время нового шифрования, то [EncryptionParameters::UserKey](../) и [EncryptionParameters::OwnerKey](../) будут равны null.

```cpp
virtual void Aspose::Pdf::Security::ICustomSecurityHandler::Initialize(System::SharedPtr<EncryptionParameters> parameters)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| параметры | System::SharedPtr\<EncryptionParameters\> | Параметры шифрования. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EncryptionParameters](../../encryptionparameters/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
