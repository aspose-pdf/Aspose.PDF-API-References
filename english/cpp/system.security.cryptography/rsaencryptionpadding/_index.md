---
title: System::Security::Cryptography::RSAEncryptionPadding class
linktitle: RSAEncryptionPadding
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::RSAEncryptionPadding class. Padding mode and parameters for RSA encryption or decryption operations in C++.'
type: docs
weight: 3600
url: /cpp/system.security.cryptography/rsaencryptionpadding/
---
## RSAEncryptionPadding class


Padding mode and parameters for [RSA](../rsa/) encryption or decryption operations.

```cpp
class RSAEncryptionPadding : public System::IEquatable<SharedPtr<RSAEncryptionPadding>>
```

## Methods

| Method | Description |
| --- | --- |
| static [CreateOaep](./createoaep/)(const HashAlgorithmName\&) | Creates [RSAEncryptionPadding](./) with OAEP mode and specified hash algorithm. |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| [Equals](./equals/)(SharedPtr\<RSAEncryptionPadding\>) override |  |
| [get_Mode](./get_mode/)() const | Gets the padding mode. |
| [get_OaepHashAlgorithm](./get_oaephashalgorithm/)() const | Gets the hash algorithm used with OAEP. |
| static [get_OaepSHA1](./get_oaepsha1/)() | Gets OAEP mode with [SHA1](../sha1/) hash algorithm. |
| static [get_OaepSHA256](./get_oaepsha256/)() | Gets OAEP mode with [SHA256](../sha256/) hash algorithm. |
| static [get_OaepSHA384](./get_oaepsha384/)() | Gets OAEP mode with [SHA384](../sha384/) hash algorithm. |
| static [get_OaepSHA512](./get_oaepsha512/)() | Gets OAEP mode with [SHA512](../sha512/) hash algorithm. |
| static [get_Pkcs1](./get_pkcs1/)() | RTTI information. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
## See Also

* Class [IEquatable](../../system/iequatable/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
