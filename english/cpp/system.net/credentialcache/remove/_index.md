---
title: System::Net::CredentialCache::Remove method
linktitle: Remove
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::CredentialCache::Remove method. Removes network credentials for the specified host name, port, and authentication type in C++.'
type: docs
weight: 600
url: /cpp/system.net/credentialcache/remove/
---
## CredentialCache::Remove(String, int32_t, String) method


Removes network credentials for the specified host name, port, and authentication type.

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The host name with which the credentials are associated. |
| port | int32_t | The port number. |
| authenticationType | String | An authentication type. |

## See Also

* Class [String](../../../system/string/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) method


Removes network credentials for the specified URI prefix and authentication type.

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| uriPrefix | System::SharedPtr\<Uri\> | The URI prefix. |
| authenticationType | String | The authentication type. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
