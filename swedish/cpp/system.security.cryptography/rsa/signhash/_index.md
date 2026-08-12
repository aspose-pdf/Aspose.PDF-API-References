---
title: "System::Security::Cryptography::RSA::SignHash metod"
linktitle: "SignHash"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::RSA::SignHash metod. Beräknar signaturen för det specificerade hash‑värdet i C++."
type: docs
weight: 1100
url: /sv/cpp/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash method


Beräknar signaturen för det specificerade hashvärdet.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hash | ByteArrayPtr | Hash‑värde. |
| hash_algoritm | HashAlgorithmName | Hash-algoritm. |
| padding | SharedPtr\<RSASignaturePadding\> | Padding‑läge. returnerar [RSA](../) signatur för det specificerade hash‑värdet. |

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
