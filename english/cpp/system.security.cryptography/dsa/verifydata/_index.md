---
title: System::Security::Cryptography::DSA::VerifyData method
linktitle: VerifyData
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::DSA::VerifyData method. Verifies that the signature of the specified data is valid in C++.'
type: docs
weight: 700
url: /cpp/system.security.cryptography/dsa/verifydata/
---
## DSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


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
* Class [DSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## DSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method


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
* Class [DSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## DSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


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
* Class [DSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
