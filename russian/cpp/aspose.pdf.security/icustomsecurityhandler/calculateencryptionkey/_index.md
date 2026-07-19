---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::CalculateEncryptionKey method"
linktitle: "CalculateEncryptionKey"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::CalculateEncryptionKey method. Вычисляет EncryptionKey. Обычно ключ рассчитывается на основе UserKey. Вы можете использовать значения из EncryptionParams, которые содержат текущие параметры на момент вызова. Это значение передаётся в качестве аргумента key в Encrypt и Decrypt в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/
---
## ICustomSecurityHandler::CalculateEncryptionKey method


Вычисляет EncryptionKey. Обычно ключ рассчитывается на основе UserKey. Вы можете использовать значения из EncryptionParams, которые содержат текущие параметры на момент вызова. Это значение передаётся в качестве аргумента key в [Encrypt](../encrypt/) и [Decrypt](../decrypt/).

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::CalculateEncryptionKey(System::String password)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| password | System::String | Пароль, введённый пользователем. |

### ReturnValue

Массив ключа шифрования.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
