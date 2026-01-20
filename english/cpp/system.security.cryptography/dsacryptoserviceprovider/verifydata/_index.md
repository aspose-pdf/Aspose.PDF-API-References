---
title: System::Security::Cryptography::DSACryptoServiceProvider::VerifyData method
linktitle: VerifyData
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::DSACryptoServiceProvider::VerifyData method. Checks data signature in C++.'
type: docs
weight: 1700
url: /cpp/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) method


Checks data signature.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const ByteArrayPtr\& | [Data](../../../system.data/) to check signature for. |
| signature | const ByteArrayPtr\& | Signature as received. |

### ReturnValue

True if signature is valid, false otherwise.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Verifies that the signature of the specified data is valid.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


| Parameter | Type | Description |
| --- | --- | --- |
| data | const ByteArrayPtr\& | Signed data. |
| signature | const ByteArrayPtr\& | Signature data. |
| hash_algorithm | const HashAlgorithmName\& | Hash algorithm. return true if signature is valid, otherwise - false. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Verifies that the signature of the specified data is valid.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


| Parameter | Type | Description |
| --- | --- | --- |
| data | const ByteArrayPtr\& | Signed data. |
| offset | int32_t | Offset in **data**. |
| count | int32_t | Number of bytes to hash. |
| signature | const ByteArrayPtr\& | Signature data. |
| hash_algorithm | const HashAlgorithmName\& | Hash algorithm. return true if signature is valid, otherwise - false. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Verifies that the signature of the specified binary stream is valid.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const StreamPtr\& | Signed data. |
| signature | const ByteArrayPtr\& | Signature data. |
| hash_algorithm | const HashAlgorithmName\& | Hash algorithm. return true if signature is valid, otherwise - false. |

## See Also

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
