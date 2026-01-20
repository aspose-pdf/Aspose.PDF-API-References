---
title: System::Security::Cryptography::ICryptoTransform::TransformFinalBlock method
linktitle: TransformFinalBlock
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::ICryptoTransform::TransformFinalBlock method. Processes last block of data and calculates output value in C++.'
type: docs
weight: 400
url: /cpp/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock method


Processes last block of data and calculates output value.

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) to read data from. |
| inputOffset | int | Input buffer offset. |
| inputCount | int | Number of bytes to process. |

### ReturnValue

Output calculated for the whole input sequence.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
