---
title: System::Security::Cryptography::RSA::SignData method
linktitle: SignData
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::RSA::SignData method. Computes the hash value of the specified data array using the specified hash algorithm and padding, and signs the result in C++.'
type: docs
weight: 1000
url: /cpp/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Computes the hash value of the specified data array using the specified hash algorithm and padding, and signs the result.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Parameter | Type | Description |
| --- | --- | --- |
| data | const ByteArrayPtr\& | Input data array. |
| hash_algorithm | const HashAlgorithmName\& | Hash algorithm. |
| padding | const SharedPtr\<RSASignaturePadding\>\& | Padding mode. return [RSA](../) signature for the input data. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Computes the hash value of the specified data array using the specified hash algorithm and padding, and signs the result.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Parameter | Type | Description |
| --- | --- | --- |
| data | const ByteArrayPtr\& | Input data array. |
| offset | int32_t | Offset in **data**. |
| count | int32_t | Number of bytes to use as input data. |
| hash_algorithm | const HashAlgorithmName\& | Hash algorithm. |
| padding | const SharedPtr\<RSASignaturePadding\>\& | Padding mode. return [RSA](../) signature for the input data. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Computes the hash value of the specified binary stream using the specified hash algorithm and padding, and signs the result.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const StreamPtr\& | Binary stream. |
| hash_algorithm | const HashAlgorithmName\& | Hash algorithm. |
| padding | const SharedPtr\<RSASignaturePadding\>\& | Padding mode. return [RSA](../) signature for the input data. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
