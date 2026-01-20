---
title: System::Net::ICredentialsByHost::GetCredential method
linktitle: GetCredential
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::ICredentialsByHost::GetCredential method. RTTI information in C++.'
type: docs
weight: 100
url: /cpp/system.net/icredentialsbyhost/getcredential/
---
## ICredentialsByHost::GetCredential method


RTTI information.

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentialsByHost::GetCredential(String host, int32_t port, String authenticationType)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| host | String | The host that authenticates the client. |
| port | int32_t | The host port number. |
| authenticationType | String | The authentication type. |
## Remarks


Returns credentials for the specified host and authentication type. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [String](../../../system/string/)
* Class [ICredentialsByHost](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
