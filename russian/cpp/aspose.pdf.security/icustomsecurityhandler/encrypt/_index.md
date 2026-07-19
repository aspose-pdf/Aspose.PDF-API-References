---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::Encrypt метод"
linktitle: "Шифровать"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::Encrypt метод. Шифрует массив данных в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.pdf.security/icustomsecurityhandler/encrypt/
---
## ICustomSecurityHandler::Encrypt method


Зашифруйте массив данных.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::Encrypt(System::ArrayPtr<uint8_t> data, int32_t objectNumber, int32_t generation, System::ArrayPtr<uint8_t> key)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | System::ArrayPtr\<uint8_t\> | Данные для шифрования. |
| objectNumber | int32_t | Номер объекта, содержащего зашифрованные данные. |
| generation | int32_t | Создание объекта. |
| ключ | System::ArrayPtr\<uint8_t\> | Ключ, полученный методом CalculateEncryptionKey |

### ReturnValue

Зашифрованные данные.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
