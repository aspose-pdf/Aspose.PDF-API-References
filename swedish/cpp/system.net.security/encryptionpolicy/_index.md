---
title: "System::Net::Security::EncryptionPolicy enum"
linktitle: "EncryptionPolicy"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Security::EncryptionPolicy enum. Enumererar krypteringspolicyerna i C++."
type: docs
weight: 400
url: /sv/cpp/system.net.security/encryptionpolicy/
---
## EncryptionPolicy enum


Enumererar krypteringspolicyerna.

```cpp
enum class EncryptionPolicy
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| RequireEncryption | 0 | Kräv kryptering och tillåt aldrig en 'Null' chiffer. |
| AllowNoEncryption | 1 | Föredra att använda full kryptering men ett 'Null' chiffer kan användas om servern samtycker. |
| NoEncryption | 2 | Tillåt ingen kryptering och begär att ett 'Null' chiffer används om den andra ändpunkten kan hantera ett 'Null' chiffer. |

## Se även

* Namespace [System::Net::Security](../)
* Library [Aspose.PDF for C++](../../)
