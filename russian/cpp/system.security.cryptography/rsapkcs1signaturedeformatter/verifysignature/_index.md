---
title: "System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature метод"
linktitle: "VerifySignature"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature метод. Проверяет подпись хеша данных в C++."
type: docs
weight: 400
url: /ru/cpp/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature method


Проверяет подпись хеша данных.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rgbHash | System::ArrayPtr\<uint8_t\> | Хеш, вычисленный для данных. |
| rgbSignature | System::ArrayPtr\<uint8_t\> | Подпись, полученная для данных. |

### ReturnValue

Истина, если подпись действительна, иначе ложь.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [RSAPKCS1SignatureDeformatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
