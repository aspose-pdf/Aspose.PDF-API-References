---
title: "System::Security::Cryptography::HashAlgorithm::TransformFinalBlock method"
linktitle: "TransformFinalBlock"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::HashAlgorithm::TransformFinalBlock method. Обрабатывает последний блок данных и вычисляет хеш в C++."
type: docs
weight: 900
url: /ru/cpp/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock method


Обрабатывает последний блок данных и вычисляет хеш.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputBuffer | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) для чтения данных. |
| inputOffset | int | Смещение входного буфера. |
| inputCount | int | Количество байтов для обработки. |

### ReturnValue

Хеш, вычисленный для всей последовательности данных.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
