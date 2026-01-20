---
title: System::Net::CredentialCache::Add method
linktitle: Add
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::CredentialCache::Add method. Adds the specified network credentials to the cache in C++.'
type: docs
weight: 400
url: /cpp/system.net/credentialcache/add/
---
## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) method


Adds the specified network credentials to the cache.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The host name with which the credentials are associated. |
| port | int32_t | The port number. |
| authenticationType | String | The authentication scheme. |
| credential | System::SharedPtr\<NetworkCredential\> | The credentials to add. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) method


Adds the specified network credentials to the cache.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


| Parameter | Type | Description |
| --- | --- | --- |
| uriPrefix | System::SharedPtr\<Uri\> | The resource's URI prefix with which the credentials are associated. |
| authenticationType | String | The authentication scheme. |
| credential | System::SharedPtr\<NetworkCredential\> | The credentials to add. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [NetworkCredential](../../networkcredential/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
