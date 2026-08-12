---
title: "System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature method"
linktitle: "VerifySignature"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature method. Проверяет подпись данных в C++."
type: docs
weight: 300
url: /ru/cpp/system.security.cryptography/asymmetricsignaturedeformatter/verifysignature/
---
## AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Проверяет подпись данных.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rgbHash | System::ArrayPtr\<uint8_t\> | [Data](../../../system.data/) подписано с помощью **rgbSignature**. |
| rgbSignature | System::ArrayPtr\<uint8_t\> | Подпись, подлежащая проверке для данных. |

### ReturnValue

True, если проверка подписи успешна, иначе false.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [AsymmetricSignatureDeformatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) method


Проверяет подпись данных. Не реализовано.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr<HashAlgorithm> hash, System::ArrayPtr<uint8_t> rgbSignature)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| хеш | System::SharedPtr\<HashAlgorithm\> | Алгоритм, используемый для хеширования. |
| rgbSignature | System::ArrayPtr\<uint8_t\> | Подпись, подлежащая проверке для данных. |

### ReturnValue

True, если проверка подписи успешна, иначе false.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashAlgorithm](../../hashalgorithm/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [AsymmetricSignatureDeformatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
