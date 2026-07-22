---
title: "System::Security::Cryptography::RSA::VerifyData metod"
linktitle: "VerifyData"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::RSA::VerifyData metod. Verifierar att signaturen för den angivna datan är giltig i C++."
type: docs
weight: 1300
url: /sv/cpp/system.security.cryptography/rsa/verifydata/
---
## RSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Verifierar att signaturen för den angivna datan är giltig.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const ByteArrayPtr\& | Signerad data. |
| signatur | const ByteArrayPtr\& | Signaturdata. |
| hash_algoritm | const HashAlgorithmName\& | Hash-algoritm. |
| utfyllnad | const SharedPtr\<RSASignaturePadding\>\& | Paddingläge. return true om signaturen är giltig, annars - false. |

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Verifierar att signaturen för den angivna datan är giltig.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const ByteArrayPtr\& | Signerad data. |
| förskjutning | int32_t | Offset i **data**. |
| count | int32_t | Antal byte att hash:a. |
| signatur | const ByteArrayPtr\& | Signaturdata. |
| hash_algoritm | const HashAlgorithmName\& | Hash-algoritm. |
| utfyllnad | const SharedPtr\<RSASignaturePadding\>\& | Paddingläge. return true om signaturen är giltig, annars - false. |

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Verifierar att signaturen för den angivna binära strömmen är giltig.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | const StreamPtr\& | Signerad data. |
| signatur | const ByteArrayPtr\& | Signaturdata. |
| hash_algoritm | const HashAlgorithmName\& | Hash-algoritm. |
| utfyllnad | const SharedPtr\<RSASignaturePadding\>\& | Paddingläge. return true om signaturen är giltig, annars - false. |

## Se även

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
