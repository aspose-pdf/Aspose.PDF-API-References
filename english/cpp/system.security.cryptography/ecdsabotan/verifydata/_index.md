---
title: System::Security::Cryptography::ECDsaBotan::VerifyData method
linktitle: VerifyData
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::ECDsaBotan::VerifyData method. Verifies that the signature of the specified data is valid in C++.'
type: docs
weight: 1400
url: /cpp/system.security.cryptography/ecdsabotan/verifydata/
---
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) method


Verifies that the signature of the specified data is valid.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature)
```


| Parameter | Type | Description |
| --- | --- | --- |
| data | const ByteArrayPtr\& | Signed data. |
| signature | const ByteArrayPtr\& | Signature data. return true if signature is valid, otherwise - false. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Verifies that the signature of the specified data is valid.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


| Parameter | Type | Description |
| --- | --- | --- |
| data | const ByteArrayPtr\& | Signed data. |
| signature | const ByteArrayPtr\& | Signature data. |
| hash_algorithm | const HashAlgorithmName\& | Hash algorithm. return true if signature is valid, otherwise - false. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) method


Verifies that the signature of the specified data is valid.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature)
```


| Parameter | Type | Description |
| --- | --- | --- |
| data | const ByteArrayPtr\& | Signed data. |
| offset | int32_t | Offset in **data**. |
| count | int32_t | Number of bytes to hash. |
| signature | const ByteArrayPtr\& | Signature data. return true if signature is valid, otherwise - false. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Verifies that the signature of the specified data is valid.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
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
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&) method


Verifies that the signature of the specified binary stream is valid.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const StreamPtr\& | Signed data. |
| signature | const ByteArrayPtr\& | Signature data. return true if signature is valid, otherwise - false. |

## See Also

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Verifies that the signature of the specified binary stream is valid.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const StreamPtr\& | Signed data. |
| signature | const ByteArrayPtr\& | Signature data. |
| hash_algorithm | const HashAlgorithmName\& | Hash algorithm. return true if signature is valid, otherwise - false. |

## See Also

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
