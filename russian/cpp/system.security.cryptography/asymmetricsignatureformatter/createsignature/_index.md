---
title: "Метод System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature"
linktitle: "CreateSignature"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature. Информация RTTI в C++."
type: docs
weight: 100
url: /ru/cpp/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) method


Информация RTTI.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rgbHash | System::ArrayPtr\<uint8_t\> | [Data](../../../system.data/) для вычисления хеша. |

### ReturnValue

Вычисленная подпись в виде массива байтов.
## Примечания


Создает подпись для указанных данных.
## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [AsymmetricSignatureFormatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) method


Создаёт подпись для указанного хеш‑значения.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| хеш | System::SharedPtr\<HashAlgorithm\> | Алгоритм хеширования, используемый при создании подписи. |

### ReturnValue

Вычисленная подпись в виде массива байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashAlgorithm](../../hashalgorithm/)
* Class [AsymmetricSignatureFormatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
