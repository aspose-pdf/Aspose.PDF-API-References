---
title: "System::Security::Cryptography::ToBase64Transform::TransformFinalBlock метод"
linktitle: "TransformFinalBlock"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::ToBase64Transform::TransformFinalBlock метод. Обрабатывает последний блок данных и вычисляет выходное значение в C++."
type: docs
weight: 900
url: /ru/cpp/system.security.cryptography/tobase64transform/transformfinalblock/
---
## ToBase64Transform::TransformFinalBlock method


Обрабатывает последний блок данных и вычисляет выходное значение.

```cpp
System::ArrayPtr<uint8_t> System::Security::Cryptography::ToBase64Transform::TransformFinalBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputBuffer | System::ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) для чтения данных. |
| inputOffset | int32_t | Смещение входного буфера. |
| inputCount | int32_t | Количество байтов для обработки. |

### ReturnValue

Результат рассчитан для всей входной последовательности.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ToBase64Transform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
