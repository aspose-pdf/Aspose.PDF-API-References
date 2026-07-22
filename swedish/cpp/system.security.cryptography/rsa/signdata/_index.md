---
title: "System::Security::Cryptography::RSA::SignData metod"
linktitle: "SignData"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::RSA::SignData metod. Beräknar hashvärdet för den angivna dataarrayen med den angivna hash‑algoritmen och padding, och signerar resultatet i C++."
type: docs
weight: 1000
url: /sv/cpp/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Beräknar hashvärdet för den specificerade dataarrayen med den specificerade hash‑algoritmen och utfyllnad, och signerar resultatet.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const ByteArrayPtr\& | Inmatningsdataarray. |
| hash_algoritm | const HashAlgorithmName\& | Hash-algoritm. |
| padding | const SharedPtr\<RSASignaturePadding\>\& | Paddingläge. return [RSA](../) signatur för indata. |

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Beräknar hashvärdet för den specificerade dataarrayen med den specificerade hash‑algoritmen och utfyllnad, och signerar resultatet.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const ByteArrayPtr\& | Inmatningsdataarray. |
| förskjutning | int32_t | Offset i **data**. |
| count | int32_t | Antal byte att använda som indata. |
| hash_algoritm | const HashAlgorithmName\& | Hash-algoritm. |
| padding | const SharedPtr\<RSASignaturePadding\>\& | Paddingläge. return [RSA](../) signatur för indata. |

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Beräknar hashvärdet för den specificerade binära strömmen med den specificerade hash‑algoritmen och utfyllnad, och signerar resultatet.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | const StreamPtr\& | Binärt flöde. |
| hash_algoritm | const HashAlgorithmName\& | Hash-algoritm. |
| padding | const SharedPtr\<RSASignaturePadding\>\& | Paddingläge. return [RSA](../) signatur för indata. |

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
