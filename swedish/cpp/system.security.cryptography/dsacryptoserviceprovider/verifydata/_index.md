---
title: "System::Security::Cryptography::DSACryptoServiceProvider::VerifyData metod"
linktitle: "VerifyData"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::DSACryptoServiceProvider::VerifyData metod. Kontrollerar datasignatur i C++."
type: docs
weight: 1700
url: /sv/cpp/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) method


Kontrollerar datasignatur.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const ByteArrayPtr\& | [Data](../../../system.data/) för att kontrollera signatur för. |
| signatur | const ByteArrayPtr\& | Signatur som mottogs. |

### ReturnValue

Sant om signaturen är giltig, falskt annars.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


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
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method


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
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


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
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
