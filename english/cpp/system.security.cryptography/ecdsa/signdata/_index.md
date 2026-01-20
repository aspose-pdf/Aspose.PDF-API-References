---
title: System::Security::Cryptography::ECDsa::SignData method
linktitle: SignData
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::ECDsa::SignData method. Computes the hash value of the specified data array using the specified hash algorithm, and signs the result in C++.'
type: docs
weight: 700
url: /cpp/system.security.cryptography/ecdsa/signdata/
---
## ECDsa::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method


Computes the hash value of the specified data array using the specified hash algorithm, and signs the result.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


| Parameter | Type | Description |
| --- | --- | --- |
| data | const ByteArrayPtr\& | Input data array. |
| hash_algorithm | const HashAlgorithmName\& | Hash algorithm. return ECDSA signature for the input data. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsa](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## ECDsa::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method


Computes the hash value of the specified data array using the specified hash algorithm, and signs the result.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


| Parameter | Type | Description |
| --- | --- | --- |
| data | const ByteArrayPtr\& | Input data array. |
| offset | int32_t | Offset in **data**. |
| count | int32_t | Number of bytes to use as input data. |
| hash_algorithm | const HashAlgorithmName\& | Hash algorithm. return ECDSA signature for the input data. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsa](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## ECDsa::SignData(const StreamPtr\&, const HashAlgorithmName\&) method


Computes the hash value of the specified binary stream using the specified hash algorithm, and signs the result.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const StreamPtr\& | Binary stream. |
| hash_algorithm | const HashAlgorithmName\& | Hash algorithm. return ECDSA signature for the input data. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsa](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
