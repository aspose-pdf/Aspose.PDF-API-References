---
title: "System::Net::CredentialCache::Add metod"
linktitle: "Add"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::CredentialCache::Add metod. Lägger till de angivna nätverksuppgifterna i cachen i C++."
type: docs
weight: 400
url: /sv/cpp/system.net/credentialcache/add/
---
## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) method


Lägger till de angivna nätverksuppgifterna i cachen.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| host | String | Värdnamnet som autentiseringsuppgifterna är associerade med. |
| port | int32_t | Portnumret. |
| authenticationType | String | Autentiseringsschemat. |
| uppgift | System::SharedPtr\<NetworkCredential\> | Uppgifterna att lägga till. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) method


Lägger till de angivna nätverksuppgifterna i cachen.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uriPrefix | System::SharedPtr\<Uri\> | Resursens URI‑prefix som autentiseringsuppgifterna är associerade med. |
| authenticationType | String | Autentiseringsschemat. |
| uppgift | System::SharedPtr\<NetworkCredential\> | Uppgifterna att lägga till. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [NetworkCredential](../../networkcredential/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
