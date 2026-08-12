---
title: "System::Net::Security::EncryptionPolicy перечисление"
linktitle: "EncryptionPolicy"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Security::EncryptionPolicy перечисление. Перечисляет политики шифрования в C++."
type: docs
weight: 400
url: /ru/cpp/system.net.security/encryptionpolicy/
---
## EncryptionPolicy enum


Перечисляет политики шифрования.

```cpp
enum class EncryptionPolicy
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| RequireEncryption | 0 | Требовать шифрование и никогда не разрешать шифр 'Null'. |
| AllowNoEncryption | 1 | Предпочитать полное шифрование, но шифр 'Null' может быть использован, если сервер согласен. |
| NoEncryption | 2 | Разрешить отсутствие шифрования и запросить использование шифра 'Null', если другая сторона может обработать шифр 'Null'. |

## См. также

* Namespace [System::Net::Security](../)
* Library [Aspose.PDF for C++](../../)
