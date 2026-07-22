---
title: "System::Net::CredentialCache::GetCredential metod"
linktitle: "GetCredential"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::CredentialCache::GetCredential metod. Returnerar autentiseringsuppgifter för det angivna värdnamnet, porten och autentiseringstypen i C++."
type: docs
weight: 500
url: /sv/cpp/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(String, int32_t, String) method


Returnerar autentiseringsuppgifter för det angivna värdnamnet, porten och autentiseringstypen.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| host | String | Värdnamnet som autentiseringsuppgifterna är associerade med. |
| port | int32_t | Portnumret. |
| authenticationType | String | Autentiseringstypen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [String](../../../system/string/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) method


Returnerar autentiseringsuppgifter för det angivna URI-prefixet och autentiseringstypen.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uriPrefix | System::SharedPtr\<Uri\> | URI‑prefixet. |
| authenticationType | String | En autentiseringstyp. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
