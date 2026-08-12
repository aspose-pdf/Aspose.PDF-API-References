---
title: "System::Security::Cryptography::ToBase64Transform::TransformBlock метод"
linktitle: "TransformBlock"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::ToBase64Transform::TransformBlock метод. Обрабатывает блок данных и копирует данные в выходной массив в C++."
type: docs
weight: 800
url: /ru/cpp/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock method


Обрабатывает блок данных и копирует данные в выходной массив.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputBuffer | System::ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) для чтения данных. |
| inputOffset | int32_t | Смещение входного буфера. |
| inputCount | int32_t | Количество байтов для обработки. |
| outputBuffer | System::ArrayPtr\<uint8_t\> | Выходной буфер для копирования данных; nullptr для отсутствия копирования. |
| outputOffset | int32_t | Смещение в выходном буфере. |

### ReturnValue

Количество записанных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ToBase64Transform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
