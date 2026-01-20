---
title: System::Security::Cryptography::ToBase64Transform::TransformFinalBlock method
linktitle: TransformFinalBlock
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::ToBase64Transform::TransformFinalBlock method. Processes last block of data and calculates output value in C++.'
type: docs
weight: 900
url: /cpp/system.security.cryptography/tobase64transform/transformfinalblock/
---
## ToBase64Transform::TransformFinalBlock method


Processes last block of data and calculates output value.

```cpp
System::ArrayPtr<uint8_t> System::Security::Cryptography::ToBase64Transform::TransformFinalBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | System::ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) to read data from. |
| inputOffset | int32_t | Input buffer offset. |
| inputCount | int32_t | Number of bytes to process. |

### ReturnValue

Output calculated for the whole input sequence.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ToBase64Transform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
