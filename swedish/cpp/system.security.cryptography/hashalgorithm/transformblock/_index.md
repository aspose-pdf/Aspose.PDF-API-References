---
title: "System::Security::Cryptography::HashAlgorithm::TransformBlock metod"
linktitle: "TransformBlock"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::HashAlgorithm::TransformBlock metod. Bearbetar ett block med data och kopierar data till utdatabufferten i C++."
type: docs
weight: 800
url: /sv/cpp/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock method


Bearbetar ett datablok och kopierar data till utmatningsarrayen.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputBuffer | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) för att läsa data från. |
| inputOffset | int | Inmatningsbuffertens offset. |
| inputCount | int | Antal byte att bearbeta. |
| outputBuffer | ArrayPtr\<uint8_t\> | Utdatabuffert att kopiera data till; nullptr för att inte kopiera. |
| outputOffset | int | Utdatabuffertens offset. |

### ReturnValue

Antal skrivna byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
