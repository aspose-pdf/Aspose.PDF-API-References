---
title: "System::Security::Cryptography::RSACryptoServiceProvider::VerifyData method"
linktitle: "VerifyData"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::RSACryptoServiceProvider::VerifyData method. Kontrollerar datasignaturen i C++."
type: docs
weight: 1800
url: /sv/cpp/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData method


Kontrollerar datasignatur.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const ByteArrayPtr\& | [Data](../../../system.data/) för att kontrollera signatur för. |
| halg | const SharedPtr\<Object\>\& | Hash-algoritm att använda. |
| signatur | const ByteArrayPtr\& | Signatur som mottogs. |

### ReturnValue

Sant om signaturen är giltig, falskt annars.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
