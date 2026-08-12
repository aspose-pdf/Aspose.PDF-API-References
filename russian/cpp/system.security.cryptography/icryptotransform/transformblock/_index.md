---
title: "System::Security::Cryptography::ICryptoTransform::TransformBlock метод"
linktitle: "TransformBlock"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::ICryptoTransform::TransformBlock метод. Информация RTTI в C++."
type: docs
weight: 300
url: /ru/cpp/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock method


Информация RTTI.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
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
## Примечания


Обрабатывает блок данных и копирует данные в выходной массив.
## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
