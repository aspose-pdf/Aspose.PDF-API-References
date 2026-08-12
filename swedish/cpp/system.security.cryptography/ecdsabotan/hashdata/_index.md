---
title: "System::Security::Cryptography::ECDsaBotan::HashData metod"
linktitle: "HashData"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::ECDsaBotan::HashData metod. Beräknar hashvärdet för den angivna dataarrayen med den angivna hashalgoritmen i C++."
type: docs
weight: 700
url: /sv/cpp/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) method


Beräknar hash‑värdet för den angivna dataarrayen med den angivna hash‑algoritmen.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | ByteArrayPtr | [Data](../../../system.data/) att hasha. |
| förskjutning | int32_t | Offset i **data**. |
| count | int32_t | Antal byte att hash:a. |
| hash_algoritm | HashAlgorithmName | Hash-algoritm. |

### ReturnValue

Hashad data.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) method


Beräknar hashvärdet för den angivna binära strömmen med den angivna hashalgoritmen.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | StreamPtr | Binär ström för hashning. |
| hash_algoritm | HashAlgorithmName | Hash-algoritm. |

### ReturnValue

Hashad data.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
