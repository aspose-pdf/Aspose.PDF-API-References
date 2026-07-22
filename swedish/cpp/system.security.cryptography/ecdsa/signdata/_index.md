---
title: "System::Security::Cryptography::ECDsa::SignData metod"
linktitle: "SignData"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::ECDsa::SignData metod. Beräknar hashvärdet för den angivna dataarrayen med den angivna hashalgoritmen och signerar resultatet i C++."
type: docs
weight: 700
url: /sv/cpp/system.security.cryptography/ecdsa/signdata/
---
## ECDsa::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method


Beräknar hashvärdet för den angivna dataarrayen med den angivna hash‑algoritmen och signerar resultatet.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const ByteArrayPtr\& | Inmatningsdataarray. |
| hash_algoritm | const HashAlgorithmName\& | Hashalgoritm. returnerar ECDSA-signatur för indata. |

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsa](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## ECDsa::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method


Beräknar hashvärdet för den angivna dataarrayen med den angivna hash‑algoritmen och signerar resultatet.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const ByteArrayPtr\& | Inmatningsdataarray. |
| förskjutning | int32_t | Offset i **data**. |
| count | int32_t | Antal byte att använda som indata. |
| hash_algoritm | const HashAlgorithmName\& | Hashalgoritm. returnerar ECDSA-signatur för indata. |

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsa](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## ECDsa::SignData(const StreamPtr\&, const HashAlgorithmName\&) method


Beräknar hashvärdet för den angivna binära strömmen med den angivna hash‑algoritmen och signerar resultatet.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | const StreamPtr\& | Binärt flöde. |
| hash_algoritm | const HashAlgorithmName\& | Hashalgoritm. returnerar ECDSA-signatur för indata. |

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsa](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
