---
title: System::Security::Cryptography::ToBase64Transform::TransformBlock method
linktitle: TransformBlock
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::ToBase64Transform::TransformBlock method. Processes block of data and copies data to output array in C++.'
type: docs
weight: 800
url: /cpp/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock method


Processes block of data and copies data to output array.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | System::ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) to read data from. |
| inputOffset | int32_t | Input buffer offset. |
| inputCount | int32_t | Number of bytes to process. |
| outputBuffer | System::ArrayPtr\<uint8_t\> | Output buffer to copy data into; nullptr to do no copying. |
| outputOffset | int32_t | Output buffer offset. |

### ReturnValue

Number of bytes written.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ToBase64Transform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
