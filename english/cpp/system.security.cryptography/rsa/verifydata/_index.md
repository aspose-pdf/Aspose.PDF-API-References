---
title: System::Security::Cryptography::RSA::VerifyData method
linktitle: VerifyData
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::RSA::VerifyData method. Verifies that the signature of the specified data is valid in C++.'
type: docs
weight: 1300
url: /cpp/system.security.cryptography/rsa/verifydata/
---
## RSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Verifies that the signature of the specified data is valid.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Parameter | Type | Description |
| --- | --- | --- |
| data | const ByteArrayPtr\& | Signed data. |
| signature | const ByteArrayPtr\& | Signature data. |
| hash_algorithm | const HashAlgorithmName\& | Hash algorithm. |
| padding | const SharedPtr\<RSASignaturePadding\>\& | Padding mode. return true if signature is valid, otherwise - false. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Verifies that the signature of the specified data is valid.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Parameter | Type | Description |
| --- | --- | --- |
| data | const ByteArrayPtr\& | Signed data. |
| offset | int32_t | Offset in **data**. |
| count | int32_t | Number of bytes to hash. |
| signature | const ByteArrayPtr\& | Signature data. |
| hash_algorithm | const HashAlgorithmName\& | Hash algorithm. |
| padding | const SharedPtr\<RSASignaturePadding\>\& | Padding mode. return true if signature is valid, otherwise - false. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Verifies that the signature of the specified binary stream is valid.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const StreamPtr\& | Signed data. |
| signature | const ByteArrayPtr\& | Signature data. |
| hash_algorithm | const HashAlgorithmName\& | Hash algorithm. |
| padding | const SharedPtr\<RSASignaturePadding\>\& | Padding mode. return true if signature is valid, otherwise - false. |

## See Also

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
