---
title: System::Security::Cryptography::ECDsaBotan::HashData method
linktitle: HashData
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::ECDsaBotan::HashData method. Computes the hash value of the specified data array using the specified hash algorithm in C++.'
type: docs
weight: 700
url: /cpp/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) method


Computes the hash value of the specified data array using the specified hash algorithm.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| data | ByteArrayPtr | [Data](../../../system.data/) to hash. |
| offset | int32_t | Offset in **data**. |
| count | int32_t | Number of bytes to hash. |
| hash_algorithm | HashAlgorithmName | Hash algorithm. |

### ReturnValue

Hashed data.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) method


Computes the hash value of the specified binary stream using the specified hash algorithm.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | StreamPtr | Bynary stream to hashed. |
| hash_algorithm | HashAlgorithmName | Hash algorithm. |

### ReturnValue

Hashed data.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
