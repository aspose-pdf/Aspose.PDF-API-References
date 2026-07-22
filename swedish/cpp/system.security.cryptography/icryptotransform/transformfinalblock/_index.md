---
title: "System::Security::Cryptography::ICryptoTransform::TransformFinalBlock-metod"
linktitle: "TransformFinalBlock"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::ICryptoTransform::TransformFinalBlock metod. Bearbetar sista blocket av data och beräknar utdata i C++."
type: docs
weight: 400
url: /sv/cpp/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock method


Behandlar sista datablocket och beräknar utdatavärdet.

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputBuffer | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) för att läsa data från. |
| inputOffset | int | Inmatningsbuffertens offset. |
| inputCount | int | Antal byte att bearbeta. |

### ReturnValue

Utdata beräknad för hela indatasekvensen.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
