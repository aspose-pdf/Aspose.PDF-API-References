---
title: "System::Security::Cryptography::HashAlgorithm::TransformBlock method"
linktitle: "TransformBlock"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::HashAlgorithm::TransformBlock метод. Обрабатывает блок данных и копирует данные в выходной массив в C++."
type: docs
weight: 800
url: /ru/cpp/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock method


Обрабатывает блок данных и копирует данные в выходной массив.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputBuffer | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) для чтения данных. |
| inputOffset | int | Смещение входного буфера. |
| inputCount | int | Количество байтов для обработки. |
| outputBuffer | ArrayPtr\<uint8_t\> | Выходной буфер для копирования данных; nullptr для отсутствия копирования. |
| outputOffset | int | Смещение в выходном буфере. |

### ReturnValue

Количество записанных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
