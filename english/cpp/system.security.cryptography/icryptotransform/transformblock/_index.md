---
title: System::Security::Cryptography::ICryptoTransform::TransformBlock method
linktitle: TransformBlock
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::ICryptoTransform::TransformBlock method. RTTI information in C++.'
type: docs
weight: 300
url: /cpp/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock method


RTTI information.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) to read data from. |
| inputOffset | int | Input buffer offset. |
| inputCount | int | Number of bytes to process. |
| outputBuffer | ArrayPtr\<uint8_t\> | Output buffer to copy data into; nullptr to do no copying. |
| outputOffset | int | Output buffer offset. |

### ReturnValue

Number of bytes written.
## Remarks


Processes block of data and copies data to output array. 
## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
