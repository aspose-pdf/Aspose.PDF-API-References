---
title: "System::Security::Cryptography::HashAlgorithm::TransformFinalBlock metod"
linktitle: "TransformFinalBlock"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::HashAlgorithm::TransformFinalBlock metod. Bearbetar sista datablocket och beräknar hash i C++."
type: docs
weight: 900
url: /sv/cpp/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock method


Bearbetar sista datablok och beräknar hash.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputBuffer | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) för att läsa data från. |
| inputOffset | int | Inmatningsbuffertens offset. |
| inputCount | int | Antal byte att bearbeta. |

### ReturnValue

Hash beräknad för hela dataserien.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
