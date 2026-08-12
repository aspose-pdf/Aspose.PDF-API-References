---
title: "System::Security::Cryptography::ICryptoTransform::TransformFinalBlock метод"
linktitle: "TransformFinalBlock"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::ICryptoTransform::TransformFinalBlock метод. Обрабатывает последний блок данных и вычисляет выходное значение в C++."
type: docs
weight: 400
url: /ru/cpp/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock method


Обрабатывает последний блок данных и вычисляет выходное значение.

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputBuffer | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) для чтения данных. |
| inputOffset | int | Смещение входного буфера. |
| inputCount | int | Количество байтов для обработки. |

### ReturnValue

Результат рассчитан для всей входной последовательности.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
