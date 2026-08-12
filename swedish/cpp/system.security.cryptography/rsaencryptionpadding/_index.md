---
title: "System::Security::Cryptography::RSAEncryptionPadding-klass"
linktitle: "RSAEncryptionPadding"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::RSAEncryptionPadding-klass. Padding‑läge och parametrar för RSA‑kryptering eller -dekryptering i C++."
type: docs
weight: 3600
url: /sv/cpp/system.security.cryptography/rsaencryptionpadding/
---
## RSAEncryptionPadding class


Padding‑läge och parametrar för [RSA](../rsa/)-kryptering eller -dekryptering.

```cpp
class RSAEncryptionPadding : public System::IEquatable<SharedPtr<RSAEncryptionPadding>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [CreateOaep](./createoaep/)(const HashAlgorithmName\&) | Skapar [RSAEncryptionPadding](./) med OAEP‑läge och angiven hash‑algoritm. |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| [Equals](./equals/)(SharedPtr\<RSAEncryptionPadding\>) override |  |
| [get_Mode](./get_mode/)() const | Hämtar padding‑läget. |
| [get_OaepHashAlgorithm](./get_oaephashalgorithm/)() const | Hämtar hash‑algoritmen som används med OAEP. |
| static [get_OaepSHA1](./get_oaepsha1/)() | Hämtar OAEP‑läge med [SHA1](../sha1/)-hash‑algoritm. |
| static [get_OaepSHA256](./get_oaepsha256/)() | Hämtar OAEP‑läge med [SHA256](../sha256/)-hash‑algoritm. |
| static [get_OaepSHA384](./get_oaepsha384/)() | Hämtar OAEP‑läge med [SHA384](../sha384/)-hash‑algoritm. |
| static [get_OaepSHA512](./get_oaepsha512/)() | Hämtar OAEP‑läge med [SHA512](../sha512/)-hash‑algoritm. |
| static [get_Pkcs1](./get_pkcs1/)() | RTTI-information. |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
## Se även

* Class [IEquatable](../../system/iequatable/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
