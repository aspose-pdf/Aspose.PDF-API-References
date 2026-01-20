---
title: System::Security::Cryptography::HashAlgorithm::TransformBlock method
linktitle: TransformBlock
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::HashAlgorithm::TransformBlock method. Processes block of data and copies data to output array in C++.'
type: docs
weight: 800
url: /cpp/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock method


Processes block of data and copies data to output array.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
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

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
