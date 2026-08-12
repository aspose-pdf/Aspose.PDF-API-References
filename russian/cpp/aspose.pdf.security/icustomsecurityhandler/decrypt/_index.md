---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::Decrypt метод"
linktitle: "Decrypt"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::Decrypt метод. Расшифровать массив данных в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.security/icustomsecurityhandler/decrypt/
---
## ICustomSecurityHandler::Decrypt method


Расшифруйте массив данных.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::Decrypt(System::ArrayPtr<uint8_t> data, int32_t objectNumber, int32_t generation, System::ArrayPtr<uint8_t> key)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | System::ArrayPtr\<uint8_t\> | Данные для расшифровки. |
| objectNumber | int32_t | Номер объекта, содержащего зашифрованные данные. |
| generation | int32_t | Создание объекта. |
| ключ | System::ArrayPtr\<uint8_t\> | Ключ, полученный методом CalculateEncryptionKey |

### ReturnValue

Расшифрованные данные.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
