---
title: System::Net::CredentialCache::GetCredential method
linktitle: GetCredential
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::CredentialCache::GetCredential method. Returns credentials for the specified host name, port, and authentication type in C++.'
type: docs
weight: 500
url: /cpp/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(String, int32_t, String) method


Returns credentials for the specified host name, port, and authentication type.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The host name with which the credentials are associated. |
| port | int32_t | The port number. |
| authenticationType | String | The authentication type. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [String](../../../system/string/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) method


Returns credentials for the specified URI prefix and authentication type.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| uriPrefix | System::SharedPtr\<Uri\> | The URI prefix. |
| authenticationType | String | An authentication type. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
