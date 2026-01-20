---
title: System::Security::Cryptography::DSACryptoServiceProvider::SignHash method
linktitle: SignHash
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::DSACryptoServiceProvider::SignHash method. Computes the signature of specified input value in C++.'
type: docs
weight: 1600
url: /cpp/system.security.cryptography/dsacryptoserviceprovider/signhash/
---
## DSACryptoServiceProvider::SignHash method


Computes the signature of specified input value.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | const ByteArrayPtr\& | Hash value of data to be signed. |
| str | const String\& | Hash algorithm identifier used to create the hash. |

### ReturnValue

[DSA](../../dsa/) signature for specified data.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
