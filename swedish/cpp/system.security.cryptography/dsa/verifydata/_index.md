---
title: "System::Security::Cryptography::DSA::VerifyData metod"
linktitle: "VerifyData"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::DSA::VerifyData metod. Verifierar att signaturen för den specificerade datan är giltig i C++."
type: docs
weight: 700
url: /sv/cpp/system.security.cryptography/dsa/verifydata/
---
## DSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Verifierar att signaturen för den angivna datan är giltig.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const ByteArrayPtr\& | Signerad data. |
| signatur | const ByteArrayPtr\& | Signaturdata. |
| hash_algoritm | const HashAlgorithmName\& | Hash-algoritm. return true om signaturen är giltig, annars - false. |

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## DSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Verifierar att signaturen för den angivna datan är giltig.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const ByteArrayPtr\& | Signerad data. |
| förskjutning | int32_t | Offset i **data**. |
| count | int32_t | Antal byte att hash:a. |
| signatur | const ByteArrayPtr\& | Signaturdata. |
| hash_algoritm | const HashAlgorithmName\& | Hash-algoritm. return true om signaturen är giltig, annars - false. |

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## DSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Verifierar att signaturen för den angivna binära strömmen är giltig.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | const StreamPtr\& | Signerad data. |
| signatur | const ByteArrayPtr\& | Signaturdata. |
| hash_algoritm | const HashAlgorithmName\& | Hash-algoritm. return true om signaturen är giltig, annars - false. |

## Se även

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
