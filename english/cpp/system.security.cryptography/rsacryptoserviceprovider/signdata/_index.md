---
title: System::Security::Cryptography::RSACryptoServiceProvider::SignData method
linktitle: SignData
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::RSACryptoServiceProvider::SignData method. Computes the signature of specified input value in C++.'
type: docs
weight: 1600
url: /cpp/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) method


Computes the signature of specified input value.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const ByteArrayPtr\& | [Buffer](../../../system/buffer/) to read input data from. |
| halg | const SharedPtr\<Object\>\& | Hash algorithm to use. |

### ReturnValue

[RSA](../../rsa/) signature for specified data.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) method


Computes the signature of specified input value.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const ByteArrayPtr\& | [Buffer](../../../system/buffer/) to read input data from. |
| offset | int32_t | Input buffer slice beginning index. |
| count | int32_t | Input buffer slice size. |
| halg | const SharedPtr\<Object\>\& | Hash algorithm to use. |

### ReturnValue

[RSA](../../rsa/) signature for specified data.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) method


Computes the signature of specified input value.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input_stream | const SharedPtr\<IO::Stream\>\& | Stream to read data being signed from. |
| halg | const SharedPtr\<Object\>\& | Hash algorithm to use. |

### ReturnValue

[RSA](../../rsa/) signature for specified data.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
